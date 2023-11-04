## 과제 3

### 1. 기계 학습에서 학습이란 무엇인지를 정리하시오(2점).

> ( 가중치, 손실함수가 무엇인지를 정리하고, 데이터, 가중치, 손실함수를 이용하여 학습이 무엇인지를 정리함.)

- 가중치란: 전체에서 가지는 중요성을 높이기 위해 특정 부분이나 요소에 일정 수치를 더하는 것이다.

- 손실함수란: 학습에서 정답값과 예측값의 오차를 계선해준 함수다.

학습이란 훈려데이터로부터 가중치 매개변수를 조절하여 손실함수로 계산된 정답값과 예측값의 오차를 줄여나가며 최적의 값을 자동으로 획득하는 것이다.

<br>

### 2. 확률적 경사 하강법의 소스 코드를 분석하시오(2점).

```python
import numpy as np


# 임시로 데이터를 생성함.
m = 100  # 샘플 수
X = 6 * np.random.rand(m, 1) - 3
X_b = np.c_[np.ones((m, 1)), X]  # 모든 샘플에 x0 = 1을 추가
y = 0.5 * X**2 + X + 2 + np.random.randn(m, 1)


n_epochs = 50   # 에포크 횟수
t0, t1 = 5, 50  # 러닝 스케줄 하이퍼파라미터


# 학습 스케줄 함수 정의: 에포크 횟수 t에 따라 학습률을 반환
# 에포크가 증가할수록 학습률이 감소
def learning_schedule(t):
    return t0 / (t + t1)


theta = np.random.randn(2, 1)  # 무작위 초기화


# n_epochs x m번 반복
for epoch in range(n_epochs):
    for i in range(m):
        # 무작위로 샘플링
        random_index = np.random.randint(m)
        xi = X_b[random_index:random_index+1]
        yi = y[random_index:random_index+1]

        # Backpropagation을 이용한 그레이디언트 계산
        gradients = 2 * xi.T.dot(xi.dot(theta) - yi)

        # 학습률 계산
        eta = learning_schedule(epoch * m + i)

        # 파라미터 업데이트
        theta = theta - eta * gradients


# print(theta)
```
