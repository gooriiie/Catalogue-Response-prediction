## Introduction  
- 최대 반응금액 찾기

## Model
- Classifier : RandomForest 사용
- Regression : LinearRegression 사용

## 수행 과정
 1. Classification 전에 class imbalance를 해결하기 위해서 SMOTE 알고리즘으로 data UpSampling
 2. 반응자 학습을 위해서 training data로 RandomForest 학습
 3. 학습시킨 RandomForest 모델로 반응자 예측
 4. training data 중 반응한 사람에 대한 data로만 LinearRegression 모델 학습
 5. 학습시킨 LinearRegression 모델로 2번에서 예측된 반응자들에 대한 반응금액 예측
 6. 반응금액 순서로 출력

## Installation
- Python 3.9 가상환경 사용

### Virtual Environment
```
conda create -n project_name python==3.9
```

### Prerequisites  
- Numpy : `pip install numpy`  
- Pandas : `pip install pandas`
- Matplotlib : `pip install matplotlib`

### Install from source
```
pip install -r requirements.txt
```
