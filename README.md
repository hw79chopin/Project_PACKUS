# PACKUS Project
![](https://i.pinimg.com/originals/48/bd/3f/48bd3f6e928d7cb4b8d499cb0f96b8a8.jpg)

## 프로젝트 소개
 - 내가 최초로 나갔던 데이터 공모전!!
 - 2019년 2학기에 열렸던 '연세 데이터사이언스 경진대회'에 출전했을 때 했던 프로젝트!  
   <우수상 수상작>
 - 위 경진대회는 신한카드, NICE지니, PACKUS 총 3개의 회사의 데이터를 바탕으로 데이터기반 의사결정 지원 혹은 새로운 가치를 창출하는 대회였음
 - 본 조는 PACKUS의 데이터를 활용한 프로젝트를 진행하였음  
  `PACKUS는 소상공인을 대상으로 한 포장용기 판매 전문업체`
 - 참여자: 정현우, 고예희
  
## 프로젝트 목표
 1. 기존 회원등급체제 수정을 통해 누락된 충성고객을 모두 회원등급체제에 포함시키기
 2. PACKUS의 배송프로세스를 절감한 당일배송을 실시
 3. 신규고객 유치를 위한 타겟마케팅 전략을 제시하자
 
## 요약
 1. 본 조는 PACKUS의 고객을 분석해보면서 충성고객들의 상당부분이 기존 회원등급체제에서 누락하고 있음을 발견하였다. 이에 충성고객들을 군집분석한 결과를 바탕으로 새로운 회원등급체제를 제시하였다. 새로운 회원등급를 적용하면 관리대상회원이 약 4배 이상 증가한다.
 2. 관리대상회원이 4배 증가하면 이에 따른 비용도 4배 증가하게 된다. 이럼에도 불구하고 회원등급체제 수정을 제시한 이유는 비용을 상쇄하고도 남을 정도로 고객 1인당 지출(per capita expenditure)을 높일 수 있을 것이라 생각했기 때문이다. 고객 1인당 지출을 높이기 위해서 우수고객에게 차별화된 혜택을 제공해야 한다. 그 혜택이 당일배송이다. 우수고객들의 수요를 예측해서 미리 재고를 보유하는 방식으로 배송을 하면 배송시간을 26% 이상 절감이 가능하였다. 줄어든 배송시간을 바탕으로 우수고객에게 당일배송을 적용하는 것이다.
 3. PACKUS는 기존에 무작위로 전단지를 돌리는 방법으로 신규고객을 유치하였다. 이러한 방법은 비용이 많이 들며 효율이 떨어진다. 이에 본 조는 기존 고객들이 모여있는 곳에서 신규 고객을 유치할 것을 제안하였다. 기존 고객들이 몰려있다는 것은 그 곳에 배달수요가 높다는 것을 의미했기 때문이다. 1.5km 반경 내에 기존 고객들이 8명이상 몰려있는 50여개의 지역을 찾아내어 위 지역을 우선적으로 공략할 것을 제안하였다.
 
## 사용 기법들
 1. 기존 회원등급체제 수정
    - Clustering: K-means Clustering, Hierarchical Clustering
 2. 당일배송 실시
    - 끊임없는 Pandas와 python
 3. 타겟마케팅 전략 제시
    - Regression: 단순 선형회귀분석 (검색량 데이터와 패커스 매출)
    - Folium: 지도시각화

## 한계점  
1. Machine Learning 알고리즘 (random Forest, Xgboost 등)을 사용했다면..  
   - 각 상품별 수요를 더 정확히 예측할 수 있었을 것이다.  
   - 시간적인 한계와 자원의 한계(팀원이 2명)에 ML까지 돌려보지는 못했다.  
   - 현재 상품별 수요를 위한 Feature를 추출하고 있음! 이후 ML 알고리즘을 돌려보려고 함  
   - 나아가 딥러닝 모델 중 RNN을 써서 정확한 수요를 예측하고자 한다.  
   
 
