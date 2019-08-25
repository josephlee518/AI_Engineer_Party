# AI_Engineer_Party

- 출처: 송호연(https://www.facebook.com/ai.chris.chris)님 Facebook 게시글

- 제출은 다음 링크 (https://forms.gle/AaqDME7sA7TobnXy5)를 통해서 제출할 수 있음

    - Github Repo Link
    - Serverless API Call Example (CURL)

- AI Engineer Party 문제 제출

## 요구사항

* Serverless API (Google Functions, Azure Functions, AWS Lambda)로 머신러닝 모델 CPU 서빙
* 데이터셋은 Google BigQuery에 적제하고 꺼내서 사용
* 학습 실험 관리 OpenSource(Microsoft NNI, Google Adanet, Optuna 등)을 사용하여 AutoML 수행
* 학습이 완료되면 Model Validation을 자동으로 수행해서 지금 서빙되고 있는 모델보다 우수한지 자동으로 검증
* 모델리스트가 관리되어야 하고, 선택적으로 배포 및 롤벡이 가능함
* 모든 코드는 Pylint 가이드에 맞춰 깔끔함을 유지 (PEP6, Google Style 등)

## 사용할 부분

* Serverless API (~~Google Functions~~, ~~Azure Functions~~, **AWS Lambda**)로 머신러닝 모델 CPU 서빙
* 데이터셋은 **Google BigQuery**에 적제하고 꺼내서 사용
* 학습 실험 관리 OpenSource(Microsoft NNI, Google Adanet, Optuna 등)을 사용하여 AutoML 수행
* 학습이 완료되면 Model Validation을 자동으로 수행해서 지금 서빙되고 있는 모델보다 우수한지 자동으로 검증
* 모델리스트가 관리되어야 하고, 선택적으로 배포 및 롤벡이 가능함
* 모든 코드는 **Pylint** 가이드에 맞춰 깔끔함을 유지 (**PEP6**, ~~Google Style~~ 등)
