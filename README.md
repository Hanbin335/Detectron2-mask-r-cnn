# 프로젝트 소개
---
Detectron2 기반 Mask R-CNN을 이용한 토마토 객체 탐지 및 상태 분류 프로젝트

# 프로젝트 전체 과정
---
![스크린샷 2024-12-24 193615](https://github.com/user-attachments/assets/cdbdbd08-c28a-4b1e-acef-4b4080dbaf7d)


# 주요기능
---
● Detectron2를 활용하여 토마토 이미지 데이터를 처리하고, Mask R-CNN 모델을 사용하여 객체 탐지 및 인스턴스 분할을 수행하도록 설계

● COCO 데이터셋에서 사전 학습된 가중치를 사용하여 모델을 초기화하고, 이를 기반으로 토마토 데이터셋에 맞춰 전이 학습을 진행하여 더 빠르고 효율적인 학습 진행

● JSON 파일을 읽어 데이터셋을 로드하고, 각 이미지와 해당하는 객체의 정보(바운딩 박스, 카테고리 등)를 포함한 데이터셋 딕셔너리 리스트를 생성하는 함수 구현

● 10000번의 훈련을 통해 모델의 정확도와 손실을 추적하며, 평가 지표로는 mAP(평균 정밀도)와 IoU(Intersection over Union)를 사용하여 성능을 평가

● 더 많은 데이터셋 및 훈련을 할 시 더 좋은 성능을 보일거라고 추정

# 개발환경
---
● Google Colab : 클라우드 기반 Python 개발 환경으로 , GPU를 사용하여 모델 학습에 사용

● Python : 주요 프로그래밍 언어로 사용

● Google Drive : 데이터를 저장하고 불러오는 파일 시스템으로 사용

# 기술스택
---

● Detectron2: 객체 탐지 및 인스턴스 분할을 위한 Facebook AI Research의 고성능 라이브러리이며 Mask R-CNN과 같은 최신 모델을 기반으로 하여 고급 컴퓨터 비전 작업을 수행

● TensorFlow: 딥러닝 모델 구축 및 학습을 위해 사용

● OpenCV: 이미지 처리 및 컴퓨터 비전 작업을 위한 라이브러리. 데이터 전처리, 이미지 크기 조정, 객체 탐지 등에 사용

● Matplotlib: 데이터 시각화 및 분석을 위한 라이브러리. 학습 과정 및 모델 성능을 시각적으로 표현

● COCO Dataset: 객체 탐지 및 인스턴스 분할을 위한 대표적인 대규모 데이터셋. Detectron2 모델의 학습 및 평가에 사용

# 성능평가
---
![스크린샷 2024-12-24 190901](https://github.com/user-attachments/assets/7ee22cfa-16cf-4811-b9b3-b4c6d5fab85f)

# 이미지 예측
---
![스크린샷 2024-12-24 190259](https://github.com/user-attachments/assets/e1493f7f-3d27-41df-a6ab-7dad76e42a14)
![스크린샷 2024-12-24 190651](https://github.com/user-attachments/assets/cfe1035c-9667-484f-af4f-5bbec1dc9042)
![스크린샷 2024-12-24 194819](https://github.com/user-attachments/assets/036bb406-e5c2-4225-a5c8-648b3f8c8b81)






