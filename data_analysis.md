# 삼성멀티캠퍼스 빅데이터를 활용한 파이썬 프로그래밍

## Part4. 데이터 분석(Data Analysis)

### 1. 데이터 수집(Data Crawling)

#### 1) API를 제공하여 이를 이용하여 수집
- 네이버 개발자
( https://developers.naver.com/docs/datalab/search/#python )
- 다음 개발자
( https://developers.kakao.com/docs/restapi/search )

#### 2) request를 이용하여 html을 획득 beautifulsoup4(bs4)를 이용하여 데이터 추출 수집
- 네이버 평점  
( https://movie.naver.com/movie/sdb/rank/rmovie.nhn?sel=cur&tg=0&date=20050207 )
- 네이버 환율  
( https://finance.naver.com/marketindex/?tabSel=exchange#tab_section )

#### 3) **selenium**을 이용하여 자동화 처리후 데이터를 추출 수집
- 국내 주유가격  
( http://www.opinet.co.kr/searRgSelect.do )
- YouTube  
( https://www.youtube.com/ )

데이터 클라우드, 관공서 등 데이터를 제공받으면 가장 좋은 방법이지만 통상 개인정보 등 보안 이슈때문에 제공을 하지 않는다. 그래서 오픈 데이터를 이용하도록 하자. 만약 직접 수집을 한다면 DB를 이용하게 되야할 것이다.

#### 서울시 공공데이터 광장
https://data.seoul.go.kr/  
이 홈페이지에서 csv나 json파일로 제공을 해준다.

---

### 2. 데이터 전처리(Data Preprocessing)
- 여기서는 **정규화**를 이용한 전처리
- 분석 전에 수행
- 텍스트 정리
- numpy와 pandas를 통해 데이터 분석
    - 수치 보정
    - 타입보정
    - 필요한 값 추출

---

### 3. 데이터 분석(Data Analysis)
- **데이터 시각화(Visualization)** 를 통해 데이터를 이해하고 분석 결과를 보여줌
- 통계적인 접근을 통해 결론을 도출

---

```
공식적으로는 여기까지가 이번 교육과정의 마지막이 될듯
```

---

### 4. 데이터 예측
- **머신러닝/딥러닝** 학습을 통해 예측을 하는 방식으로 갈 수도 있음

### 5. 빅데이터 분석(Big Data)
- 하둡 시스템을 구축하여 병렬로 구성
- 기가 이상 단위의 데이터를 하둡에 설정하여 머신러닝, 딥러닝 등등 연결하여 학습하고 예측함
- 예측의 정확도!