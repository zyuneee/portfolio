# Chest X-Ray Medical Diagnosis

## 1. Project Overview
본 프로젝트는 흉부 X-ray 이미지 데이터를 활용하여  
pneumonia(폐렴)/normal 여부를 분류하는 이미지 분류 모델을 구축한 경험을 정리한 것입니다.  
의료 전문 진단 목적이 아닌, **이미지 데이터 라벨 이해와 모델링 흐름 학습**에 초점을 두었습니다.

---

## 2. Data Description
- 데이터 유형: 흉부 X-ray 이미지 (2D grayscale)
- 데이터 출처: kaggle 공개 의료 이미지 데이터셋
- 라벨: Normal / Abnormal
- 데이터 특성:
  - 클래스 불균형 존재
  - 이미지 해상도 및 품질 편차

-- 실제) 하이퍼파라미터 설정, 라벨링 코드
image_size = 224
batch_size = 32
learning_rate = 5e-4
epochs = 15
class_labels = ['normal','pneumonia']


## 3. Problem Definition
흉부 X-ray 이미지에서 육안으로 확인 가능한 이상 징후를  
기계 학습 모델이 구분할 수 있도록 학습시키는 것을 목표로 함.

---

## 4. Approach
- 데이터 전처리
  - 이미지 리사이징 및 정규화
  - 데이터 증강(Augmentation)
- 모델링
  - CNN 기반 이미지 분류 모델 설계
  - 학습/검증 데이터 분리
- 학습 환경
  - Google Colab 환경에서 수행

---

## 5. Evaluation
- 평가 지표:
  - Accuracy
  - Precision / Recall (클래스 불균형 고려)

---

## 6. Results
- 정상/비정상 분류 가능성 확인
- 라벨 기준에 따라 예측 결과 차이 발생 확인

---

## 7. Practical Relevance
- 이미지 라벨링 기준 이해
- 영상 기반 AI 보조 및 데이터 라벨링 업무에 활용 가능


##본 프로젝트는 학습 및 포트폴리오 목적의 프로젝트이며,
코드 구현보다는 데이터 이해와 라벨 기준 정리에 초점을 두었습니다.
