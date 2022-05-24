# DACON_Stock
![20220524_124834](https://user-images.githubusercontent.com/84311270/169945031-e7942ec7-e46c-47b8-8e02-e89db9094030.png)
KOSPI-200과 KOSDAQ-150의 주어진 기간 중 마지막으로 거래된 가격(종가) 예측

## Dataset
1.stock_list.csv : 종목 번호 데이터  
종목명 : 주식 종목 명  
종목코드 : 주식 종목 코드번호  
상장시장 : 주식 종목 상장 시장 (KOSPI or KOSDAQ)  
 
2.sample_submission.csv  
	sample_submission 데이터  
	sample_submission.shape : (10, 371)  
  
finance-datareader 모듈을 사용하여 데이터 수집

## Model
다양한 파생변수 생성과 Machine-Learning 모델을 사용하여 학습을 진행. 최종적으로 Xgboost 모델과 FbProphet 모델을 사용하여 학습.

## Result
Private Score : 5.0806으로 최종 32등으로 대회를 마무리.
