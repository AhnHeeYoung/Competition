# Dacon 따릉이 대여량 예측 AI 경진대회 - 3중대 3소대장, Priviate 4위

## Requirements
conda env create -f environment.yml   
conda activate Darreung

## train

총 4개 모델에 대한 훈련.
python train.py --model nn

```
Argument Options:
  --model      nn(신경망), lgbm(lightgbm), xgboost(xgboost), catboost(catboost) -> 4개 중 1개 선택

```

## test
훈련한 4개 모델에 대한 앙상블 실시.
코드 실행 후, 3중대 3소대장_
python test.py
