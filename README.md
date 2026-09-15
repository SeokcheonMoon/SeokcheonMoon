# 👋 About Me

**Data × AI × Automation**

Python을 기반으로 데이터를 수집·가공하고,
생성형 AI와 자동화를 활용해 데이터 기반 서비스를 만드는 데 관심이 있습니다.

* 🌐 Web Crawling & Data Engineering
* 🤖 Generative AI & Prompt Engineering
* ⚙️ Automation & Service Development
* 📈 Financial Data & Investing

---

# 💼 Experience

### 고투엑스코리아

**AI뉴스팀 · 사업기획 및 프롬프트 연구 / 사원·매니저**
`2025.10 ~ Present`

* 생성형 AI Prompt 설계를 통한 맞춤형 기사 콘텐츠 생성 및 언론사 송출
* Python 및 바이브 코딩을 활용한 관리자 페이지 개발·기능 개선
* Selenium, BeautifulSoup, Requests 기반 웹 크롤링 자동화
* 사업용 데이터 수집·가공 프로세스 자동화
* 사용자 시나리오 기반 QA 및 서비스 운영

### 프롬에이아이

**AI뉴스팀 · 언론플랫폼운영 / 인턴**
`2025.02 ~ 2025.10`

* 생성형 AI Prompt 설계 및 개발을 통한 맞춤형 기사 콘텐츠 생성
* 네이버 제휴 언론 매체 뉴스 송출 및 콘텐츠 운영
* 키워드·콘텐츠 전략 수립 및 트렌드 데이터 분석
* Python 기반 방송 사업 데이터 수집·정제·매핑

### 키토크에이아이

**데이터팀 · 데이터 크롤링 및 데이터베이스 관리 / 인턴**
`2024.06 ~ 2024.11`

* 외부 플랫폼의 영화·연예·여행 관련 사업 데이터 수집 자동화
* 웹 크롤링 데이터 정제·전처리 및 DB 적재를 위한 ETL Pipeline 구축
* SQL 기반 데이터 조회 및 테이블 설계·관리

---

# 🛠️ Tech Stack

### Core

`Python` · `JavaScript` · `SQL`

### Data Engineering & Analysis

`Pandas` · `NumPy` · `SciPy` · `MySQL` · `SQLAlchemy` · `KRX Open API` · `ETL Pipeline`

- 공식·외부 데이터를 수집하고, 정제·적재·재처리 가능한 데이터 파이프라인 설계
- EDA, 가설검정(CDA), 피처 엔지니어링을 통한 데이터 분석
- 데이터 품질 검증, 실행 이력 관리, 증분 적재 자동화

### Machine Learning

`scikit-learn` · `XGBoost` · `LightGBM`

- 불균형 데이터 분석 및 분류·회귀 모델 비교
- 워크포워드 검증과 독립 홀드아웃 평가를 통한 데이터 누수 방지
- ROC-AUC, PR-AUC, F2 등 문제 목적에 맞는 지표 기반 모델 평가

### Generative AI & Automation

`OpenAI API` · `Gemini API` · `Prompt Engineering` · `Playwright` · `Selenium` · `BeautifulSoup` · `Requests`

- 생성형 AI 기반 콘텐츠·리포트 생성 흐름 설계
- 웹 크롤링, 브라우저 제어, 반복 업무 자동화
- 사용자 검토 단계를 유지하는 안전한 발행·운영 자동화

### Service & Visualization

`Streamlit` · `Plotly` · `Node.js` · `FastAPI` · `Docker`

- 분석·예측 결과를 확인할 수 있는 대시보드와 로컬 서비스 구현
- 데이터 처리부터 사용자 화면까지 연결하는 서비스 개발

---

# 🚀 Featured Projects

## 01. FATE — Financial Analysis Trend Engine

> **KRX 공식 데이터 기반 KOSPI 금융 분석 및 다음 거래일 상승 가능성 예측 시스템**

국내 주식 데이터를 안정적으로 수집·관리하고, EDA·피처 엔지니어링·머신러닝 검증·일일 예측 대시보드까지 연결한 개인 프로젝트입니다.

### What I Built

- KRX Open API 기반 KOSPI 종목 마스터 및 일별 OHLCV 데이터 수집
- 날짜 단위 Upsert, 재시도, ETL 로그, 증분 적재를 적용한 데이터 파이프라인 구축
- KOSPI 944종목, OHLCV 675,189건 데이터셋 구성 및 품질 검증
- 기술지표와 시장 피처를 활용한 다음 거래일 상승 가능성 예측
- Logistic Regression, Random Forest, XGBoost, LightGBM 모델 비교
- 워크포워드 검증 및 독립 홀드아웃 평가
- 종목별 예측 확률, 상위 20개 종목, 예측 성과를 보여주는 Streamlit 대시보드 구현

### Key Result

- 최종 홀드아웃 ROC-AUC: **0.5800**
- 상승확률 상위 20% 종목의 실제 상승률: 전체 종목 대비 **+10.90%p**
- 예측 결과를 투자 권유가 아닌 **분석 참고용 순위 정보**로 명확히 한정

**Tech**  
`Python` `KRX Open API` `MySQL` `SQLAlchemy` `Pandas` `scikit-learn` `XGBoost` `LightGBM` `Streamlit` `Plotly`

👉 [Repository](https://github.com/SeokcheonMoon/fate)

---

## 02. 티스토리 콘텐츠 자동화

> **키워드 입력부터 AI 콘텐츠·썸네일 생성, 예약 발행 보조까지 연결한 개인용 콘텐츠 자동화 도구**

반복적인 블로그 콘텐츠 제작 과정을 줄이기 위해 생성형 AI와 브라우저 자동화를 결합한 로컬 서비스입니다.

### What I Built

- 키워드 한 줄당 블로그 글 한 편을 생성하는 다중 콘텐츠 생성 흐름
- Gemini와 GPT 중 원하는 모델을 선택하는 콘텐츠 생성 기능
- AI 기반 제목, HTML 본문, 해시태그 생성
- Gemini 이미지 모델 기반 썸네일 생성 및 비율 선택 기능
- Playwright로 티스토리 편집기의 제목·본문·태그 입력 자동화
- 여러 글을 한 시간 간격으로 예약 발행하는 흐름 구현
- 캡챠와 로그인은 사용자가 직접 처리하도록 설계해 계정 통제권 유지

**Tech**  
`Node.js` `JavaScript` `Gemini API` `OpenAI API` `Playwright` `HTML/CSS`

---

## 03. Heart Disease Prediction

> **31만여 명의 건강 설문 데이터를 활용한 심장질환 위험 신호 분류 분석 프로젝트**

불균형 데이터 환경에서 심장질환 위험 신호를 분석하고, 통계 검정과 독립 테스트를 통해 모델 성능을 검증했습니다.

### What I Built

- 319,795명 응답 데이터와 17개 건강·생체 특성 분석
- EDA를 통한 클래스 불균형 및 특성별 유병률 패턴 확인
- 카이제곱 검정, Mann–Whitney U 검정, FDR 보정을 활용한 CDA 수행
- 데이터 누수를 막기 위한 Pipeline 기반 전처리와 계층 분할
- Logistic Regression과 Random Forest 성능 비교
- 검증 세트에서 F2 기준 임계값 선택 후 독립 테스트 평가

### Key Result

- 테스트 ROC-AUC: **0.837**
- 심장질환 재현율: **73.3%**
- 의료 진단 도구가 아닌 **연구·학습용 위험 신호 분석**으로 해석 범위 명시

**Tech**  
`Python` `Pandas` `NumPy` `SciPy` `scikit-learn` `Matplotlib`

👉 [Repository](https://github.com/SeokcheonMoon/heart_disease_predictions)

---

# 📌 Additional Projects

### EV Price Prediction

**데이콘 전기차 가격 예측 해커톤**

- 전기차 가격 데이터 EDA 및 전처리
- XGBoost, LightGBM 기반 회귀 모델 실험
- 데이터 시각화 및 예측 결과 비교

**Tech**  
`Python` `Pandas` `Seaborn` `XGBoost` `LightGBM`

👉 [Repository](https://github.com/SeokcheonMoon/dacon_EV_analysis)

### Game Feedback Analysis

**게임 이용자 건의사항 데이터 분석 및 업데이트 기획 프로젝트**

- Selenium 기반 이용자 건의사항 데이터 수집
- 텍스트 데이터 분석과 시각화
- 분석 결과를 바탕으로 게임 업데이트 방향 및 기획안 제안

**Tech**  
`Python` `Selenium` `Pandas` `Data Visualization`

👉 [Repository](https://github.com/SeokcheonMoon/summoners_war_development_analysis)

### Path-finder

**관광·숙박·교통 데이터를 활용한 맞춤형 여행 추천 서비스**

- 관광·숙박·교통 데이터 수집 자동화
- MongoDB 기반 데이터 관리
- 관광객 데이터 분석 및 추천 서비스 개발

**Tech**  
`Python` `Selenium` `MongoDB` `FastAPI`

👉 [Repository](https://github.com/nohjuhyeon/AI_L.K.J_hubs)

---

# 📦 Archive

- [Path-finder 1차](https://github.com/nohjuhyeon/AI_L.K.J)
- [Path-finder 3차 / FastAPI](https://github.com/nohjuhyeon/AI_LKJ_hubs_fastapi)
