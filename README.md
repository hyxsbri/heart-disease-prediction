# 심장병 분류 예측 프로젝트(VotingClassifier, ACC 0.97%)

## Project Outline


> ### 수행 기간: *23.05.22 ~ 23.05.31*

> ### 활용 데이터셋: *heart_cleaned.csv(319795 * 17 features, 1 binary target)*
    2022년 미국 성인 약 30만 명의 건강 상태와 관련된 연간 CDC 설문조사 데이터셋을 활용했습니다.
    Kaggle 컴페티션에서 csv 형태 파일을 수집했으며, 이진 타겟 변수(HeatDisease) 의 불균형이 심한 특징을 갖고 있습니다.

> ### 사용 모델: *VotingClassifier(총 네 개의 트리 모델 예측 결과에 대한 다수결 방식 취합)*

> ### 모델 최종 성능: *ACC 0.97%*

> ### 작업 환경: *Google Colab(GPU T4)*
