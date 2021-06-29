# **projects**
AI 부트캠프에서 배운 내용을 바탕으로 수행한 프로젝트를 모아두었습니다.
모든 프로젝트는 

최초 작성 : 2021.03.31

수정 : 2021.06.30

*일부 라이브러리는 github에서 바로 보이지않습니다. 첨부링크를 클릭하시면 더 빠르고 간편하게 보실 수 있습니다.*

---

### **Section3. [NLP] 리뷰로 알아보는 감성분석(sentiment analysis) : 별점 5점은 진짜 만족도 5점일까?**
[nbviewer로 바로보기](https://nbviewer.jupyter.org/github/scarletdskim/projects/blob/main/AI_02_%EA%B9%80%EB%8B%A4%EC%86%94_Section4.ipynb)

리뷰 텍스트를 활용해 고객 세그먼트(Segment)를 나누는 기준을 만들 수 있을까요? 
추천 알고리즘에 이 데이터를 어떻게 활용할 수 있을까요?

음식점에 남긴 리뷰 텍스트와 별점 데이터를 바탕으로, 
리뷰 텍스트에서 느껴지는 감성이 긍정(1), 부정(0)중 어디에 해당하는지 예측하기 위해 tensorflow로 기계 학습을 진행합니다. 
1) 한국어를 학습시키기 위한 전처리 방법
2) 부정적/긍정적인 리뷰의 특징
3) Confusion Matrix를 활용해 더 좋은 모델 결정하기



### **Section2. 구매패턴으로 고객의 LTR(LifeTime Revenue) 예측하기**
[nbviewer로 바로보기](https://nbviewer.jupyter.org/github/scarletdskim/projects/blob/main/AI_02_%EA%B9%80%EB%8B%A4%EC%86%94_Section2.ipynb)

구매데이터를 가지고, 고객의 구매패턴을 분석하고 3개월 뒤 매출을 예측합니다.
1) Growth Hacking 용어로 보는 고객 구매패턴 분석
2) RMF를 활용한 고객집단 K-means Clustering
3) 고객이 가져다줄 매출이 높을지, 낮을지 분류하는 모델 검증과 해석 
4) 고객 군집별로 세울 수 있는 마케팅 전략



### **Section1. Video Game Sales 톺아보기**
[nbviewer로 바로보기](https://nbviewer.jupyter.org/github/scarletdskim/projects/blob/main/AI_02_%EA%B9%80%EB%8B%A4%EC%86%94_Section1.ipynb)

[다음 분기에 어떤 게임을 설계할까?] 에 대답하기 위해 아래 3가지를 고민해봅니다.
1) 출고량이 많은 게임들의 패턴이 어떤지
2) 시간흐름에 따라 트렌드가 있는지
3) 지역에 따라 선호하는 게임 장르가 다른지
EDA, 기초통계를 사용해 얻은 인사이트로 결론을 내는 과정이 담겨있습니다.





