# Youjin Kim (김유진) — Blockchain Forensics & Security Research

온체인 데이터에서 범죄 패턴을 찾아내고, 그 결과를 실제로 쓸 수 있는 도구로 만드는 보안 연구자입니다.
연구(논문)와 구현(오픈소스 툴)을 함께 하며, 동시에 4개국어 상용 서비스를 1인으로 운영하는 풀스택 개발자이기도 합니다.

## Contact

| | |
|---|---|
| **Email** | business@luwei.kr |
| **GitHub** | https://github.com/u0jin |
| **소속** | 고려대학교 정보보호대학원 정보보호학과 석사과정 (지도교수: 윤지원) |

---

## Highlights

- **JKIISC(한국정보보호학회논문지) Vol.35 No.3 제1저자 게재** — 비트코인 범죄 지갑 네트워크 트랜잭션 패턴 분석
- **35만 건**의 의심 주소 데이터를 온체인에서 직접 수집·디코딩하여 **4개 범죄 유형**으로 분류
- 연구 결과를 실제 동작하는 도구(BTC/ETH Anomaly Lens 등) **3종**으로 직접 구현
- **KITRI BoB 8기** 취약점분석트랙 수료
- 4개 언어(한/영/중/일) 상용 웹·앱 서비스를 기획부터 배포까지 **1인으로 완결**한 실전 엔지니어링 역량

---

## 논문

### 비트코인 범죄 지갑 네트워크의 트랜잭션 패턴 분석 연구
**한국정보보호학회논문지(JKIISC) Vol.35 No.3, 2025 · 제1저자**

비트코인 온체인에서 35만 건의 의심 주소 트랜잭션 데이터를 수집하고, 이를 정형화하여 4개 범죄 유형(예: 믹싱, 다크마켓 연계, 랜섬웨어 자금세탁 등)으로 분류하는 파이프라인을 설계·구현했습니다. Raw 데이터 추출 → 정제 → 패턴 분석 → 분류 전 과정을 직접 수행했습니다.

---

## Projects

### 🔍 BTC Anomaly Lens
`Python` `Streamlit` `NetworkX`

실시간 비트코인 거래 이상 탐지 도구.

- 거래 그래프 기반 자동 위험 점수(risk score) 산정
- 블랙리스트 주소 스캔 및 매칭
- 동적 수수료(fee) 이상 패턴 분석
- 시계열 기반 이상 거래 탐지

→ [github.com/u0jin](https://github.com/u0jin)

---

### 🔍 ETH Anomaly Lens
`Python` `Streamlit` `Solidity`

이더리움 스마트 컨트랙트 보안 분석 도구.

- `selfdestruct`, `delegatecall`, `tx.origin` 등 위험 함수 호출 자동 탐지
- 컨트랙트 바이트코드 레벨 취약점 스캐닝

→ [github.com/u0jin](https://github.com/u0jin)

---

### 🔍 BTC Anomaly Korea Signal
`Python` `Streamlit`

한국 기반 금융 범죄 패턴에 특화된 암호화폐 이상 탐지 포렌식 도구. 국내 보이스피싱·불법 사금융 연계 지갑 패턴에 초점을 맞춰 설계했습니다.

→ [github.com/u0jin](https://github.com/u0jin)

---

## Engineering — 상용 서비스 운영 경험

연구뿐 아니라, 실제 사용자가 쓰는 서비스를 혼자 기획·개발·운영해본 경험이 있습니다. 데이터 파이프라인 설계 능력이 실제 프로덕션 환경에서도 통한다는 근거입니다.

### LUWEI — 4개국어 웰니스 큐레이션 플랫폼
`Next.js` `TypeScript` `Supabase` `PostgreSQL` `Vercel` `Cloudflare` `Swift` `React Native`

2025.11 ~ 현재 · 1인 기획·개발·운영

한국 웰니스 공간(스파·사우나·온천 등)을 외국인에게 소개하는 한/영/중/일 4개 언어 플랫폼. 414개 이상의 장소 데이터, 파트너 자가등록 기반 B2B 입점 시스템, 결제 연동, iOS/Android 앱까지 전 과정을 직접 구축했습니다.

- 4개 언어 반응형 웹 정식 운영 + iOS/Android 앱 스토어 출시
- 파트너 자가등록 → 입점비·수수료 기반 자동 수익 구조 설계
- Klook, Agoda, Amazon Associates 등 어필리에이트 연동

→ https://luwei.kr

---

## Skills

**Blockchain / Data** :: Web3.py, Etherscan API, ABI 기반 이벤트 디코딩, Pandas, NetworkX, on-chain 데이터 파이프라인 설계

**Security** :: 취약점 분석, 스마트 컨트랙트 보안 분석, 이상거래 탐지 로직 설계

**Backend / Data Engineering** :: Python, FastAPI, PostgreSQL, Supabase, REST API 설계

**Frontend / Mobile** :: Next.js, React, TypeScript, React Native, Swift

**Infra** :: Vercel, Cloudflare, AWS

**Visualization** :: Streamlit, Plotly, PDF 자동 리포트 생성

**Language** :: 한국어(모국어), 영어(기초 회화)

---

## Education & Certification

- 고려대학교 정보보호대학원 정보보호학과 석사과정 (2021 ~ 재학 중)
- 서경대학교 컴퓨터과학과 (2017 ~ 2021)
- KITRI Best of the Best (BoB) 8기 취약점분석트랙 수료 (2019 ~ 2020)
- Microsoft Learn Student Ambassador — Gold Milestone (2021 ~ 2023, 국내 최초 Gold 달성)

---

<details>
<summary>이전 프로젝트 (2018 ~ 2020)</summary>

**웹 개발**
- 강의 평가 사이트 :: JSP, JDK, MySQL, 톰캣 :: [code](https://github.com/u0jin/Lecture_Evaluation)
- 웹사이트 파일 전송 기능 구현 :: Go :: [code](https://github.com/u0jin/Go_Website_first)
- 알고리즘 튜터 웹 :: JS, WebRTC, seccomp 기반 샌드박스(Judger) :: [code](https://github.com/u0jin/Algorithm-Tutor-Web)

**앱 개발**
- 대학생 팀 프로젝트 관리 서비스(DITO) :: Android, Java :: [code](https://github.com/u0jin/DITO_Android)
- 공개 웹 플랫폼 소스코드 내 중요정보 탐지 도구 :: Python, YARA rule, 크롤링 :: [code1](https://github.com/u0jin/korea_api_endpoint) · [code2](https://github.com/u0jin/data_go_kr_api)

**오픈소스 기여**
- [uftrace](https://github.com/u0jin/uftrace) — 디버깅 툴 소스코드 기여

</details>
