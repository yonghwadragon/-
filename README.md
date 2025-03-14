# 인공 신경망 함수 근사 (ANN-Function-Approximation)
이 인공 신경망 함수 근사 저장소에는 인공 신경망(ANN)을 활용한 함수 근사 실험을 포함한 Jupyter Notebook이 포함되어 있습니다. 이론적 개념, 수치 실험, 그리고 PyTorch 구현을 다룹니다.

# README - Artificial Neural Network (ANN) Study

## 개요
이 프로젝트는 **인공 신경망(Artificial Neural Network, ANN)** 에 대한 이론적 개념과 수학적 기초를 정리한 Jupyter Notebook 파일입니다. 해당 내용은 **Byung Chun Kim 박사님**께 배운 내용을 바탕으로 작성되었으며, 신경망의 기본 구조, 아핀 변환(Affine Maps), 성분별 함수 적용(Component-wise Composition), 보편 근사 정리(Universal Approximation Theorem) 등을 다룹니다.

## 주요 내용
1. **인공 신경망(ANN)의 개요**
    - ANN의 기본 개념 및 수학적 모델링
    - 입력층, 은닉층, 출력층의 구성
    - 가중치(weight) 및 편향(bias) 설명

2. **수학적 개념**
    - 아핀 변환(Affine Maps)
    - 성분별 함수 적용(Component-wise Composition)
    - 신경망을 수식으로 표현하는 방법

3. **보편 근사 정리(Universal Approximation Theorem)**
    - ANN이 임의의 연속 함수를 근사할 수 있음을 보이는 정리
    - 특정 활성화 함수(예: 시그모이드, ReLU)를 사용한 근사 가능성

4. **박스카 함수(Boxcar Function)와 근사 기법**
    - 계단 함수(Heaviside Step Function)를 활용한 근사
    - 신경망 표현을 통한 연속 함수 근사 방법

5. **PyTorch 기반 신경망 학습**
    - PyTorch를 활용한 신경망 모델 구현
    - ReLU, 시그모이드 활성화 함수 적용
    - MSE Loss를 사용한 모델 학습 과정

6. **데이터 및 시각화**
    - 함수 근사 실험을 수행하며 시각화된 결과
    - 다양한 n 값(샘플 수)에 따른 근사 오차 비교

## 실행 방법
이 프로젝트는 Jupyter Notebook (.ipynb) 형식으로 제공되며, Google Colab 또는 로컬 환경에서 실행할 수 있습니다.

1. Google Drive에 업로드 후 Colab에서 열기
2. 필수 라이브러리 설치 (`numpy`, `matplotlib`, `torch` 필요)
3. 코드를 실행하며 수식 및 그래프를 확인

## 관련 기술 및 키워드
- **신경망 모델링**
- **머신러닝 기초**
- **딥러닝 이론**
- **수학적 기초 (선형대수, 미적분, 확률론)**
- **PyTorch를 활용한 인공 신경망 구현**

## 카테고리 분류
이 프로젝트는 **📊 Data Science & Visualization** 및 **🛠 Automation & Engineering** 분야에 해당합니다.
