# 실생활에 적용된 결정 트리, 앙상블 모델, 랜덤 포레스트 사례 조사

### 팀원

201904008 곽재원

201904042 박성훈

<br>

# 결정 트리

## 공급 사슬 관리

결정 트리(Decision Tree) 기술이 공급 사슬 관리(Supply Chain Management, SCM) 분야에서 어떻게 활용되는지에 대해 조사하였습니다. 결정 트리는 불확실성 하에서의 복잡한 결정을 단순화하고 명확하게 표현할 수 있어 공급 사슬 관리에 있어 중요한 도구로 활용되고 있습니다[1].

<br>

### **활용 분야**

- **불확실한 시나리오 평가**:
  공급 사슬 설계 결정을 평가하는 데 있어서, 결정 트리는 가격, 수요, 환율, 그리고 인플레이션 등의 불확실성을 고려할 수 있게 합니다[2].
- **물류 최적화**:
  물류 분야에서 결정 트리는 경로, 재고 수준, 그리고 운송 결정을 최적화하는 데 도움을 줍니다[3].
- **다중 에이전트 의사 결정**:
  복잡한 공급 사슬 구조에서 결정 트리는 다중 주체간의 의사 결정을 촉진시킵니다[4].
- **데이터 기반 의사 결정**:
  조직이 데이터 기반 의사 결정으로 이동함에 따라, 결정 트리는 큰 데이터 세트를 구성하고 분석하여 실행 가능한 통찰력을 제공합니다[5].

<br>

### **실제 사례**

Chopra와 Meindl의 공급 사슬 관리 책에서 가져온 "Trips 물류 예제"를 기반으로 한 결정 트리의 형성에 대한 비디오 튜토리얼이 있습니다. 이 예제는 결정 트리가 어떻게 물류 결정, 예를 들어 상품을 운송하는 데 가장 효율적인 경로를 선택하는 데 도움이 되는지 보여줍니다[3].

<br>

### 결론

결정 트리는 공급 사슬 관리의 여러 측면에서 유용하게 활용될 수 있으며, 불확실성을 평가하고, 물류를 최적화하며, 다중 에이전트 의사 결정을 촉진시키는 데 중요한 도구로 작용합니다. 그러나 결정 트리의 정적인 특성과 복잡한 공급 사슬 구조를 만드는 데 드는 시간과 노력은 일부 시나리오에서 도전 과제로 작용할 수 있습니다.

<br>

### 출처

[1] [Decision Trees: Simplifying Decisions in Supply Chain Management - LinkedIn](https://www.linkedin.com/pulse/decision-trees-simplifying-decisions-supply-chain-david-mcmillan/)

[2] [Evaluating Supply Chain Network Design Decisions Using Decision Trees](https://phantran.net/evaluating-supply-chain-network-design-decisions-using-decision-trees/)

[3] [SCM (14): Making a decision tree (Trips Logistics Example)](https://www.youtube.com/watch?v=9vKU-xk2Z-M)

[4] 논문: [A MULTI AGENT DECISION TREE ALGORITHM FOR SUPPLY CHAIN MANAGEMENT](https://www.researchgate.net/publication/324989086_A_MULTI_AGENT_DECISION_TREE_ALGORITHM_FOR_SUPPLY_CHAIN_MANAGEMENT)

[5] [Supply Chain Decision Trees - Medium](https://medium.com/difrentur/supply-chain-decision-trees-ce3375d7ad07)

<br>

## 고객 관계 관리(CRM)

고객 관계 관리(Customer Relationship Management, CRM) 분야에서 결정 트리가 어떻게 활용되는지 조사하였습니다. 결정 트리는 고객 서비스의 효율성과 일관성을 향상시키며, 고객 만족도를 높이는 데 중요한 도구로 활용되고 있습니다[1].

### **활용 분야**

- **고객 상호 작용의 간소화**:
  결정 트리는 중요한 질문을 뛰어넘지 않고 각 고객 상호 작용을 일관되게 처리하기 위해 고객 서비스 에이전트를 구조화된 질의 경로로 안내합니다[2].
- **교육 및 온보딩**:
  결정 트리의 구조화된 특성은 신규 에이전트의 온보딩 시간을 최대 80%까지 줄일 수 있습니다[2].
- **고객 만족도 향상**:
  대기 시간을 최소화하고 고객 질문을 효율적으로 해결함으로써 결정 트리는 고객 만족도를 크게 향상시킵니다[3].
- **고객 행동 예측**:
  결정 트리는 고객 데이터를 분석하여 미래의 구매 행동을 예측하는 데 사용할 수 있으며, 이는 타겟 마케팅 및 개인화된 서비스 제공에 매우 유용합니다[4].

<br>

### **실제 사례**

보험 회사를 호출하여 기존 정책을 변경하려는 경우를 예로 들 수 있습니다. 결정 트리의 도움을 받아 에이전트는 결혼 상태, 기존 정책 세부 정보, 고객 기간, 건강 정보 등 여러 조건을 확인해야 합니다. 이러한 체계적인 질의는 고객에게 적절한 해결책을 제공하기 위해 필요한 모든 정보를 수집하도록 보장합니다[2].

<br>

### 결론

결정 트리는 CRM 시스템에 통합함으로써 효율적이고 일관된 고객 서비스를 보장하는 데 중요한 도구로 작용합니다. 그러나 이러한 결정 트리를 만들고 유지하는 데 드는 시간과 노력, 그리고 그들의 구조화된 특성이 일부 고객과의 개인적인 상호 작용을 제한할 수 있는 가능성이 있다는 점을 감안할 때, 이러한 도전 과제를 해결하기 위해 노력이 필요합니다.

<br>

### 출처

[1] [How to Use Decision Trees for more Efficient Customer Service](https://www.linkedin.com/pulse/how-use-decision-trees-more-efficient-customer-service-chris-rall/)

[2] [How Decision Trees Improves Customer Experience In Call Centers?](https://knowmax.ai/blog/decision-trees-improve-customer-experience/)

[3] 논문: [Customer churn analysis using XGBoosted decision trees - ResearchGate](https://www.researchgate.net/publication/357653312_Customer_churn_analysis_using_XGBoosted_decision_trees)

[4] 논문: [Customer Relationship Management and Data Mining: A Classification Decision Tree to Predict Customer Purchasing Behavior in Global Market](https://www.researchgate.net/publication/259740867_Customer_Relationship_Management_and_Data_Mining_A_Classification_Decision_Tree_to_Predict_Customer_Purchasing_Behavior_in_Global_Market)

<br>

# 앙상블 모델

## 날씨 예측

<br>

### 활용 분야

앙상블 학습은 날씨 예보 분야에서 중요한 역할을 합니다. 이 기술은 다양한 모델 또는 단일 모델의 여러 실행을 통해 일련의 예보를 생성하여 예보의 불확실성을 정량화합니다. 앙상블 예보는 가능한 날씨 결과의 범위를 제공하며, 이는 날씨 예측의 불확실성을 이해하는 데 중요합니다[1][2].

<br>

### 실제 사례

2017년 허리케인 이르마와 같은 날씨 이벤트의 현실적인 예보를 생성할 수 있는 계절 전 예보 모델이 앙상블 학습의 한 예입니다. 이 앙상블 날씨 모델은 미래의 네 주에서 여섯 주까지의 기온 예보에 대한 유럽 중기 기상 예보 센터(ECMWF) 앙상블의 성능을 거의 일치시킬 수 있는 능력을 보여주었습니다[1].

<br>

### 결론

앙상블 학습은 날씨 예보를 개선하는 데 중요한 자산으로, 다양한 모델 예측의 집계를 통해 다양한 날씨 상황에 대한 보다 높은 이해를 제공하며 이로 인해 다양한 날씨 조건에 대한 더 나은 준비와 응답을 돕습니다. 그러나 이러한 모델은 실행 비용이 높고 높은 계산 요구 사항으로 인해 예측의 복잡성을 증가시키는 단점이 있습니다. 앙상블 기법은 예측의 정확성을 향상시키며, 모델 오류와 대기 역학의 고유한 혼돈성에 대한 견고성을 제공하는 등 다양한 이점을 제공합니다.

<br>

### 출처

[1] [https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2020MS002331](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2020MS002331)

[2] [https://www.science.org/doi/10.1126/science.1115255](https://www.science.org/doi/10.1126/science.1115255)

<br>

## 질병 예측

<br>

### 활용 분야

앙상블 학습은 병변 감지에 있어 중요한 기술로 취급되며, 특히 의료 진단 분야에서는 복잡한 데이터 패턴을 식별함으로써 이를 활용합니다. 앙상블 학습은 다양한 모델을 조합하여 더 정확한 제품 추천을 사용자에게 제공하거나, 금융 부문에서 리스크 평가, 사기 탐지 및 알고리즘 트레이딩과 같은 분야에서 더 정확하고 안정적인 결과를 얻기 위해 사용됩니다[1].

<br>

### 실제 사례

*Scientific Reports*에서 발표된 한 연구는 진단 질병 예측을 위해 깊은 신경망(DNN) 모델과 두 개의 기계 학습 모델을 결합하여 최적화된 앙상블 모델을 구축하려는 것이었습니다. 이 연구에서는 5145개의 사례에 대한 샘플 데이터 세트를 수집하고, 이를 사용하여 총 39개의 특정 질병에 대해 조사하였으며, 이 연구의 최적화된 앙상블 모델은 가장 흔한 다섯 가지 질병에 대해 81%의 F1 점수와 92%의 예측 정확도를 달성하였습니다[2].

<br>

### 결론

앙상블 학습은 병변 감지와 의료 진단 분야에서 중요한 기술로 여겨져, 다양한 모델의 예측을 집계함으로써 더 정확하고 믿을 수 있는 결과를 제공합니다. 이 기술은 복잡한 데이터 패턴을 식별하고, 정확한 진단을 돕기 위해 효과적으로 활용되고 있습니다. 그러나 앙상블 모델은 높은 계산 비용과 모델의 복잡성이 증가하는 단점도 있습니다. 그럼에도 불구하고, 앙상블 학습은 질병 탐지와 진단의 정확성과 효율성을 향상시키는 데 기여할 수 있으며, 이는 의료 분야에서 더 나은 의사 결정을 내리고, 환자의 건강을 개선하는 데 도움이 됩니다.

<br>

### 출처

[1] [https://www.nature.com/articles/s41598-021-87171-5](https://www.nature.com/articles/s41598-021-87171-5)

<br>

# 랜덤 포레스트

## AI 행동 모델링

<br>

### 활용 분야

랜덤 포레스트는 AI 시스템의 행동을 모델링하고 예측하는데 사용됩니다. 이는 대량의 데이터를 처리하고 복잡한 패턴을 식별하는 능력을 통해, 다양한 입력과 조건에 대한 AI 알고리즘의 반응을 이해하고 예측하는 데 도움이 됩니다[1]. 또한 랜덤 포레스트는 다양한 센서 입력과 과거의 행동을 분석하여 미래 시스템의 행동을 예측하는데 사용될 수 있습니다.

<br>

### 실제 사례

중국 난징의 여행 일지 데이터를 분석하여 여행 모드 선택을 모델링하는데 랜덤 포레스트를 사용한 사례가 있습니다[2]. 이 사례는 랜덤 포레스트가 인간의 행동을 이해하고 예측하는 데 어떻게 사용될 수 있는지를 보여줍니다.

<br>

### 결론

랜덤 포레스트는 AI 행동 모델링에서 강력한 도구로 작용할 수 있으며, 복잡한 데이터 세트를 처리하고, 피처의 중요성을 파악하며, 높은 정확도의 예측을 제공하는 데 유용합니다. 그러나 이 알고리즘은 계산적으로 집중적이며, 노이즈가 많은 데이터에서 오버피팅이 발생할 수 있으며, 모델 복잡성이 높아질 수 있어 이해하기 어려울 수 있습니다.

<br>

### 출처

[1] [https://towardsdatascience.com/understanding-random-forest-58381e0602d2](https://towardsdatascience.com/understanding-random-forest-58381e0602d2)

[2] 논문: [https://www.sciencedirect.com/science/article/abs/pii/S2214367X18300863](https://www.sciencedirect.com/science/article/abs/pii/S2214367X18300863)

<br>

## 날씨 예보

<br>

### 활용 분야

랜덤 포레스트는 고차원 데이터를 처리하는 능력과 회귀 및 분류 작업 모두에 내재된 기능으로 인해 날씨 예측에 중요한 도구로 사용됩니다. 랜덤 포레스트는 기온, 습도, 풍속 및 태양 복사량과 같은 다양한 날씨 매개 변수를 예측하고, 강수량을 예측하며, 심각한 날씨 이벤트를 예측하는 데 사용됩니다. 또한 랜덤 포레스트는 날씨 조건을 예측하여 날씨에 따라 달라지는 작업을 제어하고, 재해 구조 준비를 돕습니다.

<br>

### 실제 사례

인도 타밀 나두 주에서 랜덤 포레스트 머신 러닝 모델을 사용하여 전역 태양 복사량과 풍속을 예측하는 실제 사례가 있습니다[1]. 또한 랜덤 포레스트 모델은 미국 전역에서 심각한 날씨를 확률적으로 예측하기 위해 훈련되었으며, 이는 토네이도, 우박, 그리고 심한 바람 예측에 사용되었습니다[2].

<br>

### 결론

랜덤 포레스트는 고차원 데이터 처리, 높은 예측 정확도, 회귀 및 분류 작업의 다양성과 같은 장점을 제공하여 날씨 예측에 강력한 도구로 작용합니다. 그러나 모델의 복잡성, 계산 집약성, 그리고 하이퍼 파라미터 튜닝의 필요성과 같은 단점으로 인해 기상학자들이나 기계 학습 전문 지식이 부족한 팀이 해석하는 데 어려움이 있을 수 있습니다.

<br>

### 출처

[1] 논문: [https://www.researchgate.net/publication/352110820_Weather_prediction_using_random_forest_machine_learning_model](https://www.researchgate.net/publication/352110820_Weather_prediction_using_random_forest_machine_learning_model)

[2] [https://journals.ametsoc.org/view/journals/wefo/34/1/waf-d-18-0034.1.xml](https://journals.ametsoc.org/view/journals/wefo/34/1/waf-d-18-0034.1.xml)

<br>

## 마케팅

<br>

### 활용 분야

랜덤 포레스트는 마케팅 분야에서 고객의 행동을 이해하고, 잠재 고객을 더 효과적으로 대상으로 하며, 마케팅 캠페인을 최적화하는데 사용됩니다. 랜덤 포레스트는 고객 데이터를 분석하여 구매 행동, 인구 통계학, 그리고 선호도에 따라 서로 다른 고객 그룹을 식별하는데 도움이 됩니다. 또한 이 알고리즘은 과거 마케팅 캠페인 데이터를 분석하여 미래 캠페인의 잠재적 성공을 예측하고, 리소스 할당과 전략 계획에 도움이 됩니다[1].

<br>

### 실제 사례

랜덤 포레스트는 판매량 예측과 같은 마케팅의 중요한 부분에서 활용됩니다. 랜덤 포레스트 회귀를 사용하여 판매량을 예측하는 실제 사례가 있습니다[2]. 이 예측은 판매 추세를 이해하고 예측하는데 도움이 되어, 더욱 근거 있는 마케팅 결정을 내릴 수 있게 합니다.

<br>

### 결론

랜덤 포레스트는 마케팅 분석에 대한 깊은 분석을 제공하며, 높은 정확도와 피처 중요도 식별을 통해 마케팅 전략에 유용한 통찰력을 제공합니다. 그러나 이 알고리즘은 복잡할 수 있으며, 큰 데이터 세트와 많은 수의 트리를 요구하며, 특히 마케팅 팀이 머신 러닝 전문 지식이 부족한 경우에는 해석이 어려울 수 있습니다[3].

<br>

### 출처

[1] [https://www.kiranvoleti.com/random-forest-algorithm-for-marketing-analytics](https://www.kiranvoleti.com/random-forest-algorithm-for-marketing-analytics)

[2] ["Random Forests Algorithm Explained with a Real Life Example and Some Python Code", Towards Data Science, https://towardsdatascience.com/random-forests-algorithm-explained-with-a-real-life-example-and-some-python-code-cb7fc2b8eb4](https://towardsdatascience.com/random-forests-algorithm-explained-with-a-real-life-example-and-some-python-code-affbfa5a942c)

[3] [https://theprofessionalspoint.blogspot.com/2019/02/advantages-and-disadvantages-of-random.html](https://theprofessionalspoint.blogspot.com/2019/02/advantages-and-disadvantages-of-random.html)
