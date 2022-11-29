# sts-model

* colab에서 테스트됐고, 여러 환경 의존적인 코드가 포함되어 있기 때문에 로컬에서 동작하지 않을 수 있습니다.

1. data_process.ipynb : 수능특강/완성 데이터셋을 학습 가능하도록 전처리하는 코드
2. train.ipynb : 수능특강/완성 데이터셋으로 sbert를 학습시키는 코드
3. train_external.ipynb : 수능특강/완성 데이터셋 + 외부 데이터셋으로 sbert를 학습시키는 코드
4. model_test.ipynb : 학습된 모델을 로드해서 inference해보는 코드
5. Integrated.ipynb : 테스트셋으로 성능을 테스트하는 최종 코드(요약 -> sbert 추론)
