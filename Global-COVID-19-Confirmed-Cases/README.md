# COVID19 전세계 확진자 데이터 분석
* CSSE @ Johns Hopkins University 에서 제공하는 2020 1월부터 2023년 2월까지의 전세계 확진자 데이터를 ORANGE3의 time slice로 다루고 있습니다.
* 해당 자료와 Worldwide Happiness Report를 합병한 후, Seaborn을 이용하여 행복 지수에 영향을 미치는 요소와 COVID 19 확진자 수의 관계도에 대해 분석합니다. 

## 궁금증
* 나라별 코로나19 확진자 수는 해당 나라의 행복지수와 관련성이 있을까?
* 확진자가 가장 많이 나온 나라는 어디일까?
* 2020년 1월부터 2023년 2월 동월별로 확진자 수가 가장 많았던 나라는 어디일까?

## 문제 정의
* 행복 지수에 영향을 미치는 요소들과 코로나19의 확산 속도는 어떤 관계가 있을까?

## 가설
행복 지수가 낮을수록 코로나19의 확산 속도가 빠를 것이다.
코로나19의 유행 초기엔 진원지인 중국의 확진자가 많지만 2020년 중반에 접어들수록 개발도상국들에서 확진자 수가 급격히 늘어날 것이다.

## 결과
![Timeslice](https://github.com/user-attachments/assets/b85fd0b0-6aaf-41d2-8e63-655a6669d3fb)

## 스킬
Orange3, Seaborn, matplotlib, pandas
## 출처
* 코딩이 필요 없는 데이터분석, 머신러닝 - 오렌지3(Orange3) 기초: https://www.inflearn.com/course/오렌지3-기초/dashboard
* CSSE COVID 19 Data: https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv
* COVID19 Data Analysis Using Python: https://www.coursera.org/projects/covid19-data-analysis-using-python&sa=D&source=editors&ust=1742818369804439&usg=AOvVaw26DnBlKZnxjJt-Qu8vU-jp

