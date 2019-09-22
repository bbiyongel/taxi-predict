# taxi-predict
랜덤포레스트를 활용한 택시 승하차 예측 모델

택시 데이터가 있는 csv파일을 받아 eda과정을 거치며 데이터를 가공하고
eda과정에서의 결과들을 통해 cda과정 모델을 학습시켜 모델을 만든다음
python flask와 naver,kakao map api를 이용하여 웹에서 예측결과를 가시화 시킴
