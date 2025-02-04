## 1차 프로젝트; 1,3,4,5장 새로운 데이터로 분석/실습해기

### 김찬진
사용 데이터 : 개인 의료비 데이터셋 (https://www.kaggle.com/datasets/mirichoi0218/insurance)

[코드 보러가기](./1차프로젝트/김찬진.ipynb)


### 박준환
사용 데이터 : 타이타닉 데이터셋 (https://www.kaggle.com/c/titanic/data)

[코드 보러가기](./1차프로젝트/박준환1.ipynb)


### 이지민
사용 데이터 : 공기질 데이터셋 (https://archive.ics.uci.edu/dataset/360/air+quality)

[코드 보러가기](./1차프로젝트/이지민.ipynb)

### 정해림
사용 데이터 : 심장병 데이터셋 (https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

[코드 보러가기](./1차프로젝트/정해림.ipynb)

## 2차 프로젝트; [2024년 문화체육관광 데이터 활용 대회](https://stat.mcst.go.kr/portal/duc/duc/ducDetail?boardId=NBRD-1002548&boardType=000312&target=%EB%8C%80%ED%9A%8C%20%EA%B3%B5%EC%A7%80%EC%82%AC%ED%95%AD&page=1&searchText=&orderRowNum=2)

[코드 보러가기](./2차프로젝트)

### 주제: 독서 인구 증가를 위한 챌린지 제안
1. 크롤링한 yes24리뷰 데이터를 통해 도서 키워드를 추출한다.
2. 사용자는 추출한 키워드 중 관심있는 키워드를 지정한다.
3. 카드 사용 데이터와 결합하여 사용자 맞춤형 챌린지 생성한다.
4. 맞춤형 챌린지를 통한 독서인구 증가 도모한다.
### 사용한 데이터 분석 기술
**시각화**

<img width="800" alt="image" src="https://github.com/user-attachments/assets/06d41f90-396b-41b3-ab36-5e35cafb2b6d">

* 한강작가의 노벨상 수상 전후 도서 대출량을 시각화하여 노벨상의 영향력을 보인다.
* 도서관 내 프로그램 수와 도서관 회원수의 상관관계를 시각화하여 독서프로그램의 영향력을 보인다.

**DBSCAN**

<img width="700" alt="image" src="https://github.com/user-attachments/assets/77e32179-61ce-4be5-b9d6-53e9ff5dd74a">

* yes24 리뷰 데이터를 keybert를 통해 키워드로 변환한다.
* 변환한 키워드는 DBSCAN을 통해 대표 키워드를 추출한다.
  
**k-means clustering**

<img width="700" alt="image" src="https://github.com/user-attachments/assets/2f49a0cb-4d99-4f64-871d-2e0de5099f72">

* 가맹업종을 기준으로 사용자의 소비집단을 분류한다.



