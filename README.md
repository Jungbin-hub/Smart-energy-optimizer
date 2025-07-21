# Smart-energy-optimizer
AI 기반 에너지 소비 예측 및 이상 탐지 시스템
# 스마트 에너지 소비 예측 및 최적화 시스템

## 프로젝트 개요
이 프로젝트는 시간에 따른 에너지 사용량 데이터를 분석하여 머신러닝 모델로 다음 시간대의 에너지 소비를 예측하고, 시각화하는 시스템입니다.  
실무형 포트폴리오를 목표로 데이터 분석부터 예측, 시각화, 그리고 웹 대시보드 구축까지 확장할 예정입니다.

## 기술 스택
- Python 3.13
- pandas
- matplotlib
- scikit-learn
- Jupyter Notebook (개발 및 실험 환경)

## 현재 구현된 기능
- 에너지 사용량 데이터 로딩 및 기초 통계 분석
- 시간 기반 선형 회귀 모델을 통한 에너지 소비 예측
- 시계열 데이터 시각화 및 예측 결과 그래프 출력

## 예측 결과 예시
2025-07-01 04:00 에너지 예측 사용량: 136.67 kWh


## 향후 계획
- 모델 고도화 (RandomForest, XGBoost, LSTM 등)
- 외부 요인(요일, 기온 등) 추가한 다중 특성 예측
- 이상치 탐지 및 경고 시스템 구현
- Streamlit 기반 웹 대시보드 개발
- 실시간 데이터 연동 및 클라우드 배포

## 사용 방법
1. 프로젝트 클론 및 가상환경 설정
```bash
git clone https://github.com/Jungbin-hub/Smart-energy-optimizer.git
cd Smart-energy-optimizer
python -m venv venv
source venv/Scripts/activate  # Windows PowerShell
pip install -r requirements.txt

2.Jupyter Notebook 실행 및 energy_data.csv 확인 후 코드 실행
jupyter notebook
