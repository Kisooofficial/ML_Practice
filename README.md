# ML_Practice
practicing machine learning model

# 데이콘 영화 관객수 예측 모델
+ EDA
title, distributor 제외
year 변수 추가, year 변수 추가 후 label encoding(그 해에 영화 관객 수가 높은 순서로 라벨인코딩)
skewness가 너무 큰 것에 대해서는 log화
+ 1차 시도 결과 - 1418237.41828(rmse)
+ 2차 시도 결과 - 1724238.xxxxx(rmse)
이상한게, 1차 시도때 보다 전처리도 잘한 것 같고 validation score도 훨씬 좋게 나왔는데, 1차 때보다 스코어가 올라가버림 ;; 
다른 솔루션도 없어서 영화 관객수 예측은 여기서 마무리를 함.

# 캐글 산탄데르 고객 예측
