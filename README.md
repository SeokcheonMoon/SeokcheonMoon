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

`Python` · `JavaScript` · `TypeScript` · `SQL`

### Infrastructure, Deployment & Operations

`GitHub` · `Vercel` · `Gabia` · `DNS` · `Upstash Redis` · `Vercel Cron`

- 가비아에서 구매한 도메인을 DNS 설정으로 Vercel 배포 서비스에 연결
- 사용자 지정 도메인 `www.moneykawaii.store`를 적용한 웹서비스 구축
- GitHub 비공개 저장소와 Vercel을 연동해 코드 변경에 따른 자동 배포 구성
- Vercel 환경변수로 API 키·Redis 토큰·예약 실행 비밀키 관리
- Upstash Redis를 연결해 증시 브리핑, 방문 통계와 재방문 이력 저장
- Redis TTL을 활용한 데이터 보관 기간과 Lua 기반 중복 집계 방지 구현
- Vercel Cron으로 한국·미국 증시 브리핑의 일일 자동 갱신 구성
- 배포용 빌드, 상태 확인 API, 메타데이터 검사를 통한 운영 점검
- 
### Web & Service Development

`Next.js` · `React` · `Node.js` · `FastAPI` · `HTML/CSS` · `Vercel` · `Docker`

- 사용자 흐름에 맞춘 페이지 구성과 반응형 웹 인터페이스 구현
- 재사용 가능한 컴포넌트와 타입 기반 입력·응답 구조 설계
- 클라이언트 계산, 서버 API, 외부 데이터 연동을 연결하는 서비스 개발
- GitHub·Vercel 기반 배포와 환경변수 관리
- Open Graph, 페이지별 메타데이터, sitemap·robots 등 검색·공유 환경 구성

### Data Engineering & Analysis

`Pandas` · `NumPy` · `SciPy` · `MySQL` · `SQLAlchemy` · `Redis` · `KRX Open API` · `ETL Pipeline`

- 공식·외부 데이터를 수집하고, 정제·적재·재처리 가능한 데이터 파이프라인 설계
- EDA, 가설검정(CDA), 피처 엔지니어링을 통한 데이터 분석
- 데이터 품질 검증, 실행 이력 관리, 증분 적재 자동화
- Redis 기반 공유 데이터 저장, TTL 적용, Lua를 활용한 원자적 중복 처리
- 데이터의 사용 목적에 따른 서버 저장소·브라우저 저장소 구분

### Machine Learning

`scikit-learn` · `XGBoost` · `LightGBM`

- 불균형 데이터 분석 및 분류·회귀 모델 비교
- 워크포워드 검증과 독립 홀드아웃 평가를 통한 데이터 누수 방지
- ROC-AUC, PR-AUC, F2 등 문제 목적에 맞는 지표 기반 모델 평가

### Generative AI & Automation

`OpenAI API` · `Gemini API` · `Prompt Engineering` · `Playwright` · `Selenium` · `BeautifulSoup` · `Requests`

- 생성형 AI 기반 콘텐츠·리포트 생성 흐름 설계
- Google 검색 근거를 활용한 요약 생성과 응답 형식·기준일 검증
- 웹 크롤링, RSS 연동, 브라우저 제어, 반복 업무 자동화
- 예약 실행, 실패 시 이전 데이터 유지, 중복 호출 제한 등 운영 흐름 구성
- 사용자 검토 단계를 유지하는 발행·운영 자동화

### AI-Assisted Development & Vibe Coding

`Codex` · `Requirements Engineering` · `Code Review` · `Regression Testing`

- 자연어 요구사항을 화면 구성·데이터 흐름·예외 조건으로 구체화
- AI 개발 도구를 활용해 기존 프로젝트 구조에 맞는 기능 구현·수정 진행
- 생성된 코드의 입력 검증, 비동기 처리, 비밀키 노출 여부와 저장 정책 점검
- 운영 중 발견한 문제를 원인 분석 → 로직 수정 → 회귀 테스트로 연결
- 구현 결과와 검증 한계를 구분해 README·릴리스 기록으로 문서화

### Visualization & Quality

`Streamlit` · `Plotly` · `Matplotlib` · `SVG` · `Node.js Test Runner`

- 분석·예측 결과를 확인할 수 있는 대시보드 구현
- 포트폴리오 구성과 지출 비중을 보여주는 시각화 개발
- 계산 공식, 날짜 경계, 외부 응답 실패, 데이터 복원 등에 대한 자동 테스트
- TypeScript 검사와 프로덕션 빌드를 통한 배포 전 검증

---

# 🚀 Featured Projects

## 01. 머니카와이 — MoneyKawaii

> **금융·급여 계산기, 배당 포트폴리오, 가계부와 AI 증시 브리핑을 연결한 한국형 웹 플랫폼**

로그인 없이 필요한 도구를 바로 이용할 수 있도록 구성한 개인 웹서비스입니다. Codex를 개발 보조 도구로 활용하며 요구사항 구체화, 기능 설계, 외부 서비스 연결, 테스트와 배포까지 개발 흐름을 관리했습니다.

### What I Built

- Next.js·React·TypeScript 기반 반응형 웹사이트와 공통 컴포넌트 구성
- 금융 계산기 4개, 급여·근로 계산기 4개와 달력형 가계부 구현
- 한국·미국 종목명·코드·티커 검색과 공개 배당 자료 조회 연결
- 보유 수량·평균 주가에 따른 포트폴리오 비중, 예상 배당금·배당률 계산
- 원화·달러 혼합 포트폴리오의 통화 환산과 시각화 구현
- localStorage 기반 가계부 저장, JSON 백업·병합, 월·연 PNG 저장
- Gemini·Google 검색·Vercel Cron·Redis를 연결한 한국·미국 증시 브리핑 구성
- IP 원문 대신 HMAC 변환 값을 활용한 일별 방문 중복 제거·재방문 이력 저장
- 네이버 블로그 RSS를 연동한 ‘텐버거 인사이트’ 최신 글 목록 구현
- Open Graph, 검색 소유권 확인 태그, 페이지별 SEO와 배포 환경 구성
- 가비아 도메인·DNS와 Vercel을 연결해 사용자 지정 도메인으로 서비스 배포
- GitHub 자동 배포, 서버 환경변수, Upstash Redis와 예약 실행을 연결한 운영 환경 구성

### Engineering Highlights

**생성일과 거래일을 구분한 AI 응답 검증**

오늘 생성된 브리핑이 과거 거래일 자료를 요약하는 문제를 확인했습니다. 한국·미국의 시간대와 주말을 반영해 대상 거래일을 계산하고, 반환된 거래일이 다르면 새 결과로 저장하지 않도록 개선했습니다.

**비동기 응답과 중복 요청 처리**

검색어·통화 변경 시 이전 응답이 최신 입력을 덮어쓰지 않도록 요청 취소와 버전 검사를 적용했습니다. 방문 통계는 Redis Lua로 중복 판정과 합계 증가를 묶어 처리했습니다.

**사용자 기록 보존과 복원 설계**

가계부의 이미지 저장과 데이터 백업을 구분했습니다. JSON 형식·날짜·금액·중복 ID를 검증하고, 기존 기록을 덮어쓰지 않는 병합 흐름을 구성했습니다.

### Key Result

- **금융·급여 계산기 8개와 가계부**를 하나의 서비스로 통합
- **한국·미국 17,321개 종목 스냅샷** 기반 검색 구성
- **자동 테스트 60개**, TypeScript 검사·프로덕션 빌드 통과
- 실제 운영 문제를 거래일 검증·중복 집계·데이터 복원 회귀 테스트로 연결

※ 종목 수는 2026-10-18 스냅샷 기준입니다. IP 기반 집계에는 공유 IP·동적 IP에 따른 오차가 있으며, AI 요약의 사실성과 외부 서비스 연결은 운영 환경에서 별도 확인합니다.

**Tech**  
`Next.js` `React` `TypeScript` `CSS` `Node.js` `Gemini API` `Google Search Grounding` `Redis` `Lua` `RSS` `Vercel` `Codex`

👉 [Live Service](https://www.moneykawaii.store)

---

## 03. 티스토리 콘텐츠 자동화

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

## 02. FATE — Financial Analysis Trend Engine

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

## 04. Heart Disease Prediction

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
