# Fashion-Fruits
아이펠 해커톤 3차 Fashion-Fruits 팀 repo

# Team

- 김진영 (jinyeongkim37@gmail.com)
- 김준모 (wnsah1008@gmail.com)
- 김창희 (kimchda210@naver.com)
- 이지연 (i3048i@naver.com)
- 정희민 (scr02070@naver.com)

# 주요 과업

- 데이터셋 확보
    - DeepFashion2 데이터셋을 사용할 예정.
- 의류 Detection 모델 개발
- 의류 Segmentation 모델 개발
    - Detectioin ⇒ Segmentation 순차적으로 진행
- 모델 테스트
- 모델을 활용한 시범 사이트를 배포하여 사용자 반응 수집
- 사업적 활용 가능성 도출

# Dataset
[DeepFashion2](https://github.com/switchablenorms/DeepFashion2)

## 브랜치 정보
- main : 리뷰를 거친 최종 작업 내용
- release : 개발 이후 main으로 합쳐지기 전 리뷰가 필요한 내용
- dev : 핵심적으로 개발중인 내용
- feature : 실험적으로 개발중인 내용

1. 프로젝트의 핵심 내용 (모델 개발 등)으로 분류되는 작업은 dev 브랜치에서 작업, 실험적으로 개발하는 내용으로 분류되는 작업은 feature 브랜치에서 작업합니다.   
2. 작업이 완료되면, release 브랜치에 추가합니다.   
3. release 브랜치에서 리뷰를 거친 후, 적합한 내용인 경우 main 브랜치에 PR 를 보냅니다.
4. 적합하지 않은 경우 다시 dev 혹은 feature 브랜치로 가져가서 후속 작업 후 다시 (2) 과정으로 넘어갑니다.