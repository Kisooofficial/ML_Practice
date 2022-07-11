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
+ 3차 시도 결과 - 1711238.xxxxx(rmse)


# 캐글 산탄데르 고객 예측 (1등꺼 커널 필사)
+ 1일차 : 데이터 overview 확인 및 기초 데이터 분석 완료
+ 2일차 : 추가 EDA, 변수 추가, StratifiedKFold, LGBM 10 KFold
=> 이 사람이 첨도랑 왜도까지 첨부한 이유를 모르겠음. 단순히 roc-auc score를 높이기 위함인거 같기도 ..

