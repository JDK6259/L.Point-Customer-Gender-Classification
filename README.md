# L.Point-Customer-Gender-Classification
> L.Point 고객 성별 분류 모델

## Description
L.Point 고객데이터을 여러 가지 분류 모델과 기법으로 학습시켜 최종적으로 고객들의 성별을 분류하는 머신러닝 대회

## Environments
- Jupyter Notebook
- CPU 

## Code 실행순서 
- 1-Make_Features 
- 2-Build_Models_1
- 3-Build_Models_2
- 4-Build_Models_with_BOW
- 5-Build_Models_with_W2V
- 6-Power_Mean_Ensemble_1
- 7-Power_Mean_Ensemble_2

## Code 설명
- 1-Make_Features : 거래데이터를 기반으로 모델에 필요한 파생변수들을 생성하여 X_train/X_test에 저장
- 2-Build_Models_1 & 3-Build_Models_2 : 생성된 데이터의 전처리 및 EDA 실행과 모델링 및 하이퍼 파라미터 튜닝, 제출 모델 선정
- 4-Build_Models_with_BOW : Baf of Words 기반의 feature 생성 및 모델링 
- 5-Build_Models_with_W2V : Word2Vec 기반의 feature 생성 및 모델링 
- 6-Power_Mean_Ensemble_1 & 7-Power_Mean_Ensemble_2 : 앞선 모델링 과정을 통해 저장된 예측값들의 멱평균 앙상블 실행 
