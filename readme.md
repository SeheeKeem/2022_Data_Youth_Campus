# 2002 데이터 청년 캠퍼스 'MTWT' - '관광지 혼잡도를 기반으로 한 관광객 분산 시스템'

1. EDA  (프로젝트 주제에 맞춰 데이터 탐색, 분석 진행)
2. Data_collection (데이터를 수집하고 전처리하기 위한 코드들을 포함)
3. Dataset (원본 데이터와 학습에 사용하기 위해 가공한 데이터 포함)
    * raw_data (원본 데이터)
    * final_data (모델 학습을 위해 가공한 데이터)
4. LSTM-Modeling (혼잡도 예측을 위한 LSTM을 모델을 생성하고 학습시키는 코드)
5. Recommender System (특정 관광지에 대해 유사한 관광지 10개를 추천해주는 코드)
 


## EDA
 * tourist_num_EDA.ipynb : 관광형태의 변화를 이동 통신 데이터를 이용해 2019 ~ 2021년 지역별 관광객 수를 변화량을 분석하는 코드 
 
## Data_collection
 * humidity.ipynb
 * minimum_temperature.ipynb
 * maximum_temperature.ipynb
 * type_of_rain.ipynb
 * probability_of_rain.ipynb
 * date_data.ipynb

 위의 파일 5개는 순서대로 습도, 최저기온, 최고기온, 강수형태, 강수확률을 365일 기준으로 처리하기 위한 코드

 ## Dataset
 * 원본데이터를 포함해 모델 학습에 사용하기 위해 가공한 데이터 일체를 포함
 

 * target_j.ipynb
 * target_s.ipynb

 위의 파일은 각각 제주도와 서귀포시에 대해 정답 레이블을 전처리하기 위한 코드


 * naverblog_crawler.ipynb
 * social_buzz_concat_weather.ipynb

 소셜 버즈량을 확인하기 위해 일자별 블로그 게시글 건수를 크롤링하기 위한 데이터


## LSTM-Modeling
 * LSTM_CNNLSTM.ipynb : 다음날의 관광수요를 미리 예측하기 위해 딥러닝 모델인 LSTM과 CNN-LSTM을 RMSE로 비교 하는 코드

## Recommender System
 * Recommendation_sys.ipnyb : 사용자 사전을 반영하여 문서유사도를 구하고 그 결과로 추천시스템을 구현하는 코드


