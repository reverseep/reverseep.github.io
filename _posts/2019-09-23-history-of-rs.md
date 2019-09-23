---
title: (1) A Priori Algorithm
categories: Recommendation_system
---
# 연관규칙분석 / 장바구니분석  
대학 시절 머신러닝 수업을 수강한 학생들이라면 제일 처음 chapter 혹은 두번째 chapter로 배우는 내용이 연관규칙분석(A Priori Algorithm)일 것입니다.
연관규칙분석이라는 방법론이 생소하시다면 장바구니 분석(Market Basket Analysis)은 다들 들어보셨을텐데요, 아기 기저귀를 사는 고객들에게 맥주를 추천했더니
매출이 상승했다는 유명한 사례에 사용된 바로 그 방법론입니다. 소비자들의 구매 데이터를 바탕으로 "X 아이템을 구매하는 고객들은 Y 아이템을 구매할 확률이 높다."라는,
아이템 간의 연관성을 분석하는 것이지요. 추천시스템을 분류하는 방식은 다양할 수 있지만 크게 user-based와 item-based로 구분했을 때, item을 기반으로
연관 상품을 추천해주는 가장 기본적인 알고리즘이라고 할 수 있습니다. 현재는 좀 더 정확성이 높은 발전된 모델들이 사용됨에 따라 거의 쓰이지 않는
방법론 중 하나지만, 추천 관련 용어나 알고리즘을 이해하는데 있어서 가장 기초가 되는 알고리즘이기에 짚고 넘어가겠습니다.  

# 사용 데이터 소개(Transactions from a bakery)  
케글에 공개되어 있는 베이커리의 구매 데이터를 활용하도록 하겠습니다.  
*링크:

# Confidence/Support/Coverage/Lift  
(1) Confidence
