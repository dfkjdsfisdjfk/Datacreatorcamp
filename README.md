# 2022 Data Creatorcamp
- 2022 데이터 크리에이터 캠프 대상
- 컴퓨터 드로잉 툴을 사용해 그린 일러스트레이션 영상을 효과적으로 분류할 수 있는 모델 개발
- 20개의 클래스를 가지는 25,503개의 그림들을 분류


# 요약

- 기간 : 2022.10 ~ 2022.11
- 팀원 : 총 4명
- 개발 언어 : Python, Keras
- 주요 역할 : EDA , 이미지 클러스터링 , VGG 19 모델 개발

# 상세 내용
1. EDA
2. 학습에 불필요한 사진 제거(이미지 변환 및 비지도학습 사용)
3. 클래스 불균형 해결을 위해 다수의 클래스는 다운 샘플링, 소수의 클래스는 업 샘플링
4. 전처리를 거친 이미지를 사용하여 Base Model, VGG19, Resnet 개발
5. 성능이 우수한 Resnet 모델 채택