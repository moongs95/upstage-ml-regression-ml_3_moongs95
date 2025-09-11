<!-- Header -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=timeGradient&text=ML%20Group3%20Third%20Party%20👋&animation=twinkling&fontSize=35&fontAlignY=40&fontAlign=70&height=250&width=800" style="width:800px; display:block; margin:auto;">
</div>

<h2 align="center">🧑‍💼👩‍💼👩‍💼 Introduce Our Team 👩‍💼👩‍💼👨‍💼</h2>
<div align="center">

<table>
<tr>
<td align="center">
  <div style="background-color:#9370db; style="width:100px; height:100px; overflow:hidden; border-radius:50%;">
    <img src="https://avatars.githubusercontent.com/u/89570502?v=4" width="200" height="200" style="border-radius:50%"><br>
    <b>권문진 (팀장)</b><br>
    Preprocessing, Feature Engineering,<br>
    Data EDA (Making material), Modeling
  </div>
</td>
<td align="center">
  <div style="background-color:#8a2be2; style="width:100px; height:100px; overflow:hidden; border-radius:50%;">
    <img src="https://avatars.githubusercontent.com/u/221927853?v=4" width="200" height="200" style="border-radius:50%"><br>
    <b>고민서</b><br>
    Preprocessing, Feature Engineering,<br>
    Data EDA (Making material), Modeling
  </div>
</td>
<td align="center">
  <div style="background-color:#7b68ee; style="width:100px; height:100px; overflow:hidden; border-radius:50%;">
    <img src="https://avatars.githubusercontent.com/u/219617394?v=4" width="200" height="200" style="border-radius:50%"><br>
    <b>허예경</b><br>
    Data Collection, Feature Engineering, Modeling
  </div>
</td>
</tr>
<tr>
<td align="center">
  <div style="background-color:#9370db; style="width:100px; height:100px; overflow:hidden; border-radius:50%;">
    <img src="https://avatars.githubusercontent.com/u/221468673?v=4" width="200" height="200" style="border-radius:50%"><br>
    <b>김동근</b><br>
    Data Collection, Domain Knowledge for Consultation and Literature Analysis,<br>
    Data EDA Analyze, Modeling
  </div>
</td>
<td align="center">
  <div style="background-color:#9370db; style="width:100px; height:100px; overflow:hidden; border-radius:50%;">
    <img src="https://avatars.githubusercontent.com/u/218931464?v=4" width="200" height="200" style="border-radius:50%"><br>
    <b>이수민</b><br>
    Data Collection, Domain Knowledge for Consultation and Literature Analysis,<br>
    Data EDA Analyze, Modeling
  </div>
</td>
<td align="center">
  <div style="background-color:#9370db; style="width:100px; height:100px; overflow:hidden; border-radius:50%;">
    <img src="https://avatars.githubusercontent.com/u/228438426?v=4" width="200" height="200" style="border-radius:50%"><br>
    <b>이승호</b><br>
    Data Collection
  </div>
</td>
</tr>
</table>

</div>




## 0. Overview

### 💻 Tech Stack:
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Scipy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white) ![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

## 1. Competiton Info

### Overview

- _Write competition information_

### Timeline

- ex) January 10, 2024 - Start Date
- ex) February 10, 2024 - Final submission deadline

## 2. Components

### Directory

- _Insert your directory structure_

e.g.
```
├── code
│   ├── jupyter_notebooks
│   │   └── model_train.ipynb
│   └── train.py
├── docs
│   ├── pdf
│   │   └── (Template) [패스트캠퍼스] Upstage AI Lab 1기_그룹 스터디 .pptx
│   └── paper
└── input
    └── data
        ├── eval
        └── train
```

## 3. Data descrption

### Dataset overview

| Feature | Description | Note |
|---------|-------------|------|
| 강남권 여부 | 기존 데이터 기준 | 서울시 구별 평균 거래가 |
| 계약년월 | - | - |
| 전용면적(㎡, log) | 평수 변환 | - |
| X좌표, Y좌표 | 기존 좌표 삭제 | 번지, 본번, 부번, 도로명 등으로 지오코딩 예정 |
| 건축년도 | - | - |
| 매매가격지수 | - | Time Split에 있어야 하나 설명 미흡 |
| 건설공사비지수 | - | 기존 데이터(Time Split) |
| 구 | - | 기존 데이터(분석계획서 기준) |
| 대장아파트거리(km, log) | - | - |
| 지하철거리 | - | - |
| 버스정류장수 | - | - |
| 버스거리 | - | - |
| 연식 | - | 강남권/비강남권 연식별 거래가격 |
| 1km 이내 학교수 | - | - |
| 아파트명 | - | 아파트 브랜드별 평균 거래가격 |
| 초등학교 거리 | - | - |
| 고등학교 진학률 | - | 상관관계 낮음 |
| 지하철수 | - | 상관관계 낮음 |
| 회사채금리 | - | 기존 데이터(Time Split) |
| 전용면적 구간 | - | 상관관계 낮음 |
| 층 | - | 층 수별 거래가격 |
| 거래량 | - | 기존 데이터(Time Split) |
| 대장아파트거리 접근성 | - | 상관관계 낮음 |

### EDA

- _Describe your EDA process and step-by-step conclusion_

### Data Processing

- _Describe data processing process (e.g. Data Labeling, Data Cleaning..)_

## 4. Modeling

### Model descrition

- _Write model information and why your select this model_

### Modeling Process

- _Write model train and test process with capture_

## 5. Result

### Leader Board

- _Insert Leader Board Capture_
- _Write rank and score_

### Presentation

- _Insert your presentaion file(pdf) link_

## etc

### Meeting 

- _Insert your meeting log link like Notion or Google Docs_

### Reference

- [아파트 매매가 횡단면 분석](https://rstudio-pubs-static.s3.amazonaws.com/770609_5fa09d74e4b64257aa56fd6aef42d7fe.html)
- [아파트 전세가율의 변동](https://www.ejrea.org/archive/view_article?pid=jrea-9-2-95)
- [관련논문](http://lps3.kiss.kstudy.com.kims.kmu.ac.kr/Detail/Ar?key=4005911)
- [주소 추출](https://www.biz-gis.com/index.php?mid=QnA&page=134&listStyle=list&m=0&document_srl=27034)
- [코로나19 팬데믹 기간 아파트가격 결정](https://scienceon.kisti.re.kr/commons/util/originalView.do?cn=JAKO202309672000765&dbt=JAKO&koi=KISTI1.1003%2FJNL.JAKO202309672000765)
- [관련논문](https://konkuk.dcollection.net/public_resource/pdf/200000686187_20250904110840.pdf)
