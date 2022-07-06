# Dacon 따릉이 대여량 예측 AI 경진대회 - 3중대 3소대장, Priviate 4위

## Requirements
conda env create -f environment.yml   
conda activate Darreung

## train

총 4개 모델에 대한 training 코드이며 아래 코드 실행.
```
python train.py --model nn
```

```
Argument Options:
  --model      nn(신경망), lgbm(lightgbm), xgboost(xgboost), catboost(catboost) -> 4개 중 1개 선택

```

## test
훈련한 4개 모델에 대한 앙상블 실시.
코드 실행 후, Private leaderboard 재현이 가능한 ```3중대3소대장_submission.csv``` 파일이 생성됨
```
python test.py
```
