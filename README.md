# Shopping_GG > jinji

## TimeSeries ver  
|Date|Model|Comment|ETC|
|:---:|:---|:---|:---|  
|08.23|0823_FE_TimeSeries_yj.ipynb|jupyter notebook FE||    
|08.23|0823_FE_TimeSeries_yj.py|조기매진 함수 with python||
|09.03|0903_TS_prophet_yj.ipynb|TS with prophat, 2020.1~ 취급액 예측||  

## ML_modeling ver  
|Date|Model|Comment|ETC|
|:---:|:---|:---|:---|  
|0906|0906_ML_embedded_data_yj.ipynb|임베딩 피쳐 ver4 with lgbm||  
|0907|0907_ML_basic_catboost_yj.ipynb|basic ml model & catboost||

## CrossValidation
|Date|Model|Comment|ETC|
|:---:|:---|:---|:---|  
|0910|0910_ML_cv_yj.ipynb|ML CV용 함수|파이썬 라이브러리는 model.train 유의 / pickle로 각자 저장 후 기록 필요|     
>cv = 5 (5 fold validation)  
>random_state = 77  
>gbm 계열 epoch = 5000, early = 50 으로  

## Task
- 하이퍼파라미터 튜닝  
- Task2 진행  
- modeling with all features  
- modeling with Ensemble  
- catboost tunning  
- mape cv5 로 stacking 용 pred 값 뽑으면서 돌리면 lgbm 100 넘음 - 0910
