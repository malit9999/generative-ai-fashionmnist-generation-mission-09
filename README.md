# Conditional FashionMNIST Generation

> **Bootcamp Mission 09** | Generative AI

## 미션 소개
FashionMNIST 데이터셋의 의류 카테고리를 조건으로 사용해 이미지를 생성하는 생성형 AI 미션입니다. 클래스 조건에 따라 서로 다른 패션 아이템을 생성하는 과정을 실습합니다.

## 구현 목표
- 생성 모델의 입력과 학습 목표를 이해한다.
- 클래스 조건을 이미지 생성 과정에 반영한다.
- 생성 결과를 카테고리별로 비교한다.

## 주요 구현 내용
- FashionMNIST 데이터 처리
- 조건부 이미지 생성
- 생성 샘플의 클래스별 시각화

## 사용 기술
- Python
- PyTorch
- Generative AI
- FashionMNIST
- Jupyter Notebook

## 실행 방법
`ash
pip install -r requirements.txt
jupyter notebook notebooks/mission09.ipynb
`

> 데이터셋 또는 사전학습 모델이 외부에서 제공되는 경우, 실행 전에 노트북 또는 코드의 데이터 로드 설정을 확인해야 합니다.

## 폴더 구조
`	ext
notebooks/
  mission09.ipynb
README.md
requirements.txt
.gitignore
`

## 학습 내용
- 생성 모델은 정답 레이블을 직접 예측하는 모델과 다른 품질 평가가 필요하다는 점
- 조건 정보를 입력에 결합하는 방식

## 트러블슈팅 및 재현 시 참고 사항
생성 품질은 학습 시간과 하이퍼파라미터에 민감하므로 결과 이미지를 함께 비교합니다.

## 결과 확인
조건별 생성 이미지는 노트북의 시각화 출력에서 확인할 수 있습니다.

## 포트폴리오 관점
이 저장소는 **Generative AI** 역량을 학습·실험한 결과물입니다. 구현 범위와 실행 조건은 코드 및 노트북을 기준으로 확인할 수 있습니다.