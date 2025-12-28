# Image Preprocessing and Filtering

## Overview
This project focuses on analyzing the impact of noise on images and
comparing basic filtering techniques through controlled experiments.

## Data Preprocessing Experience
- 이미지에 인위적으로 소금·후추 노이즈(Salt-and-Pepper Noise)를 생성하여
  노이즈가 시각적 정보에 미치는 영향을 확인함.
- 가우시안 필터를 적용하여 노이즈를 완화하고,
  필터링 전·후 이미지를 비교 분석함.
- 미디언 필터를 추가로 적용하여
  소금·후추 노이즈 제거 및 경계 보존 효과를 확인함.

## Techniques
- Salt-and-Pepper Noise Generation
- Gaussian Filtering
- Median Filtering

## Outcome
- 가우시안 필터는 전반적인 노이즈 완화에는 효과적이었으나
  일부 경계 정보 손실이 발생함.
- 미디언 필터는 이상값 제거에 강점을 보여
  소금·후추 노이즈 환경에서 더 효과적인 결과를 보임.
- 중앙값필터(median filtering)는 이상값 즉, 튀는 노이즈 제거에 강함
- 가우시안 필터는 전반적 랜덤 노이즈를 부드럽게 평균 냄

