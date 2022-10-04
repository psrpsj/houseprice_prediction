# House Prices - Advanced Regression Techniques
House Prices from Kaggle
## 1. Project Overview
  - 목표
    - Regression 및 boosting 모델을 이용한 집값예측.
  - 모델
    - Catboost등 다양한 모델을 AutoML을 이용한 최적의 모델 탐색 후 제출.

## 2. Code Structure
``` text
├── dataset
|   ├── train.csv
|   └── test.csv 
└── house_prediction.ipynb
```

## 3. Detail 
  - Preprocess 
    - EDA를 통한 결측치 특성 확인, 특성에 따른 결측치 전처리
    - Correlation에 따른 데이터 전처리.
  - Model
    - AutoML을 최적의 모델을 찾은후, 해당 모델을 학습시킴(제출모델: Catboost)
  - 최종성적
    - Public Score(RMSE): 0.14773
