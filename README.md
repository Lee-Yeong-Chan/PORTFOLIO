# 이영찬 포트폴리오
##### Lee Yeong Chan portfolio

## 진행한 프로젝트
목록<br>
[1. drony](#1-drony)<br>
[2. H-moca](#2-h-moca)<br>
[3. BCF](#3-bcfbee-careful)

### 1. drony
> 기간 : 2023/06/23 ~ 2023/08/07<br>
> 드론 업자와 드론이 필요로 하는 사람들을 매칭해주는 웹 사이트<br>
> 역할 : 프론트엔드, 백엔드, DB설계, 파이썬 데이터 크롤링<br>

- 프론트엔드
  - language : javascript, ajax
    - Library : JQUERY
  - 개발내용 : 채팅, 회원가입시 아이디 중복체크, 필수입력항목체크
- 백엔드
  - language : JSP, servlet
  - WAS : Apache Tomcat
  - 개발내용 : 로그인, 회원가입, 게시글기능
- DB설계
  - DB : oracleDB
- 데이터 크롤링
  - language : python
    - Library : selenium
  - 개발내용 : 드론판매업체 및 수리업체 크롤링
- [링크](https://github.com/Lee-Yeong-Chan/drony)
<hr/>

### 2. H-moca
> 기간 : 2023/08/10 ~ 2023/09/26<br>
> 유통 데이터 활용 경진대회<br>
> 10개의 제품 데이터 분석 및 예측<br>
> 역할 : 데이터 분석, 생수 분야 데이터 모델링 및 예측<br>

- 데이터분석
  - language : python
  - Library : matplotlib, seaborn
  - 내용 : 데이터 plot 및 상관계수 분석, 이상치 제거
- 생수분야 데이터 모델링 및 예측
  - language : python
  - Library : matplotlib, tensorflow, LSTM, statsmodels.api, sklearn, graphviz, xgboost, lightgbm
  - 내용 : sklearn 비선형 모델링, xgboost, lightgbm, statsmodels.api의 모델을 각각 시계열모델링과 제품마다 높은 상관계수를 가지는 변수를 추가한 모델링해서 두 개의 모델링으로 R2스코어가 가장 높은 모델을 선정 및 예측
- [링크](https://github.com/Lee-Yeong-Chan/H-moca)
<hr/>

### 3. BCF(Bee CareFul)
> 기간 : 2023/09/11 ~ 2023/10/26<br>
> 양봉업을 위한 꿀벌 해충을 미리 감지하는 시스템 및 웹 사이트<br>
> 역할 : 프론트엔드, 백엔드, DB설계, 파이썬 데이터 크롤링, YOLO v5 모델링, flask<br>

- 프론트엔드
  - language : javascript, ajax
    - Library : JQUERY, chartJS
  - 개발내용 : 회원가입시 아이디 중복체크, 필수입력항목체크, 데이터 시각화
- 백엔드
  - language : spring framework
  - WAS : Apache Tomcat
  - 개발내용 : 로그인, 회원가입, 카메라 관리, 알람리스트 관리
- DB설계
  - DB : MySQLDB
- 데이터 크롤링
  - language : python
    - Library : selenium
  - 개발내용 : 꿀벌 사진 데이터 크롤링
- YOLO v5 모델링
  - language : python
  - 개발내용 : YOLO v5를 활용한 데이터 학습 후 모델의 best.pt추출
- 파이썬
  - language : python
    - Library : Flask, cv2, pymysql, torch
  - 개발내용 : 노트북 카메라로 모델 연결 및 웹 사이트로 영상 출력, 영상 내 감지한 개체 박싱, 알람 시간에 따른 데이터 저장, 사진 데이터 저장
- [링크](https://github.com/Lee-Yeong-Chan/BCF)
<hr/>
