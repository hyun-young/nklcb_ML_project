# 딥러닝 프로젝트 - 스터디 1조 

## 주제선정 및 배경

:seedling: **예비 카페 창업자를 위한 서울특별시 카페 창업 상권 위험도 분석**

![tree](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/c5299ae5-f3da-4d3b-ab9a-24ea46c1542c/%EC%B0%BD%EC%97%85.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220102%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220102T073927Z&X-Amz-Expires=86400&X-Amz-Signature=5eaece4b6c380aff6044309354ad32cc18156ebc2918a883f5ef5c46d5aa9562&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22%25EC%25B0%25BD%25EC%2597%2585.png%22&x-id=GetObject)

* 단기간에 분석이 어려운 상권 특성 파악 및 매출에 영향을 줄 수 있는 요소들을 종합적으로 고려해 창업 위험도 분석

* 대형 프랜차이즈에서 상권 분석 시스템을 제공하고 있으나, 일반 개인 카페는 상권 입지에 대한 정보를 구하기 어려움

* 예비 카페 창업자를 위한 데이터 분석 및 머신러닝을 통해 카페 창업 지역을 추천, 위험도 분석


## 목적

:bulb: **실제 창업을 위해 현장조사 시 중요하게 고려해야 할 사항들을 제시함으로써 개인 카페 예비 창업자들에게 최적의 입지(행정동 기준)를 찾도록 인싸이트 도출**


## 데이터 종류 및 수집 경로

:memo: :memo: :memo:

**1. 행정동별 서울생활인구(내국인) - 시간대,성별,나이대별 생활인구**
:link: <https://data.seoul.go.kr/dataList/OA-14991/S/1/datasetView.do](https://data.seoul.go.kr/dataList/OA-14991/S/1/datasetView.do>

**2. 서울시 우리마을가게 상권분석서비스(행정동별 상권변화지표)**
:link: <https://data.seoul.go.kr/dataList/OA-15575/S/1/datasetView.do>

**3. 서울시 지하철호선별 역별 승하차 인원 정보**
:link: <https://data.seoul.go.kr/dataList/OA-12914/S/1/datasetView.do>

**4. 인스타그램 게시글 크롤링(트렌드 분석)**

**5. 서울시 우리마을가게 상권분석서비스(상권-추정매출)**
:link: <https://data.seoul.go.kr/dataList/OA-15572/S/1/datasetView.do](https://data.seoul.go.kr/dataList/OA-15572/S/1/datasetView.do)>

**6. 교통 및 유동인구량**
:link: <https://www.bigdata-telecom.kr/invoke/SOKBP2603/?goodsCode=ICTTRAF000001](https://www.bigdata-telecom.kr/invoke/SOKBP2603/?goodsCode=ICTTRAF000001>


## 개발 환경

<div align=left> 
   <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"> 
   <img src="https://img.shields.io/badge/jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white">
   <img src="https://img.shields.io/badge/google colab-F9AB00?style=for-the-badge&logo=google colab&logoColor=white"> 
   <br>
</div>

## 프로젝트 추진 전략

**1. 요건 정의**
- 계획수립 및 자료조사, 현황분석

**2. 데이터 수집 및 전처리**
- 데이터 수집 대상목록 및 정리, 데이터 관리 및 수집 자동화

**3. 분석 모델링**
- 분석 시나리오(분석 대상, 범위, 방법론 등) 작성, 분석모델 설계

**4. 모델구현**
- 분석 및 알고리즘 구현

**5. 시각화**
- 시각화 방안 설계 및 스토리보드 작성, 분석 결과별 시각화

**6. 검증 및 안정화**
- 검증 계획 수립 및 테스트

## 프로젝트 기대효과
- 카페 예비 창업자에게 입지 인싸이트(행정동 기준) 제공
- 카페 매출에 영향을 미치는 요소 탐색


## 노션

:link: <https://www.notion.so/suminstudyspace/a12decc55d4f42e79ae434bdb3d23173>







