# lg-aimers-resort-demand forecast

## 📌 프로젝트 개요
이 프로젝트는 **리조트 내 식음업장 메뉴별 1주일 수요 예측 AI 모델**을 개발하는 실습 과제입니다.  
과거 판매 데이터를 기반으로 시계열 예측 모델을 구현하여 향후 7일간 각 메뉴의 판매량을 예측합니다.

본 프로젝트는 **LG Aimers AI 실습 과정**의 일환으로 수행되었습니다.

---

## 🎯 목표
- 과거 판매 데이터를 분석하여 **메뉴별 주간 판매량을 예측**
- LSTM, GRU 등 **시계열 예측 모델**을 활용한 성능 비교
- 데이터 전처리 및 모델 튜닝을 통한 **예측 정확도 향상**

---

## 📂 데이터셋
- **train.csv**: 과거 판매 이력 (메뉴명, 판매일자, 판매량 등)
- **test.csv**: 향후 1주일간 예측 대상 데이터
- **submission.csv**: 예측 결과 제출 파일

---

## 🛠 기술 스택
- **Python 3.x**
- **Pandas, NumPy** – 데이터 전처리 및 분석
- **Matplotlib, Seaborn** – 데이터 시각화
- **TensorFlow / Keras** – 딥러닝 모델 구현
- **Scikit-learn** – 전처리 및 성능 평가

---

## 📊 모델 구조
- **기본 모델**: LSTM 기반 시계열 예측
- **개선 모델**: GRU 기반 모델, 하이퍼파라미터 튜닝 적용
- **성능 지표**: MAE, MSE, RMSE

---

## 🚀 실행 방법
```bash
# 1. 저장소 클론
git clone https://github.com/username/lg-aimers-resort-demand.git
cd lg-aimers-resort-demand

# 2. 필요한 라이브러리 설치
pip install -r requirements.txt

# 3. 모델 학습 및 예측 실행
jupyter notebook
