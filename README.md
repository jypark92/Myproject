# CNN 분류모델을 활용한 COVID-19 환자 분류

## 수행프로젝트 개요 ## 

- #### 프로젝트명
   * CNN 모델 기반 lungs X-ray  image를 활용한 코로나 환자 분류 
   
- #### 개발인원 및 참여기여도
   * 인원 : 1명 , 참여기여도 : 100%

- #### 수행기간
   * 2020.06.01 ~ 2020.09.10
   
- #### 프로젝트 목표
   * Kaggle 오픈 이미지 DataSet을 활용한 COVID-19 환자 분류모델구현
   * 데이터 수집 / 데이터 전처리 / 모델링 / 테스트 & 검증 전 단계 구현
   * Confusin Matrix를 통한 성능 평가 및 성능 향상 

- #### 개발 환경 및 개발 언어
   * 개발환경  : Anaconda Spyder
   * 언어      : Python
   * 라이브러리 
      * Numpy : Data를 array형태로 생성하여 모델 학습 시 array형태의 연산을 위하여 사용
      * os : 운영체제 내 파일경로를 파악하기 위하여 사용
      * Matplotlib : 시각화하기 위하여 사용
      * Pillow : 저장된 이미지 데이터를 불러오기 위하여 사용
      * glob : 이미지 데이터를 집단으로 불러오기 위하여 사용
      * Pandas : 이미지 데이터 정보인 픽셀 값 chart형태 .csv형태로 저장
      * opencv : 이미지 데이터의 사이즈를 변환하기 위하여 사용
      * tensorflow, keras : 모델을 구축하고 학습 및 검증하여 모델의 성능을 분석하기 위하여 사용

- #### 오류발생 및 해결 내역
   * Train / Test으로 분리하여 데이터셋을 구성했을 경우 Overfitting이 발생하여 테스트 수행 시 정확도가 80~90% 사이로 나타남
   * 문제해결을 위하여 K-fold(5겹) 교차 검증을 수행하여 문제 해결
   * 문제해결을 위하여 추가적인 데이터 확보
   
- #### 수행프로젝트 상세내역 
   * COVID-19 분류 PPT 참조

