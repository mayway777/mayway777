# 👋 안녕하세요!

---
## 🗂️ 프로젝트 분류

| 구분       | 프로젝트명         | 설명                            |
|------------|--------------------|---------------------------------|
| **메인**   | EmpAI              | AI 기반 맞춤형 취업 플랫폼      |
|            | AI 면접 분석 서버  | 감정, 시선, 음성 분석 기능 구현 |
| **활용/사이드** | 관제 솔루션         | YOLO 기반 실시간 위험 감지      |
|            | 관제 시스템        | 위험 상황 시각화 클라이언트     |
|            | 관제 분석 서버     | 백엔드 분석 서버 구성            |
| **학습용** | WCF 가족오락관     | WCF 기반 미니게임                |
|            | 키오스크           | 주문 흐름 구현 UI               |
|            | 예약 시스템        | Python 기반 데이터 처리/시각화  |
---
# 🚀 EmpAI - AI 기반 맞춤형 취업 플랫폼  
> **공식 배포 사이트**: [https://emp-ai.kro.kr](https://emp-ai.kro.kr)  
> GitHub: [Client](https://github.com/mayway77/empai-client) ｜ [Server](https://github.com/mayway77/empai-server)
---
 프로젝트 email : root1@naver.com, password : 123456
               
자기소개서 분석부터 AI 면접 피드백, 커뮤니티 기반 피드백까지 제공하는 **올인원 취업 플랫폼**입니다.

### 📌 주요 기능
- **GPT 기반 자소서 분석**: 문장 구조, 키워드, 논리성 피드백
- **AI 면접 피드백**: 감정·시선·음성 분석을 통한 실시간 피드백
- **커뮤니티 기능**: 자소서 공유, 맞춤형 추천, 후기 제공

### 🔧 주요 기술
- `Next.js`, `TypeScript`, `Tailwind` (클라이언트)
- `FastAPI`, `Python`, `Whisper`, `firebase-admin` (서버/AI 분석)
- `OpenAI GPT`, 감정 분석 모델, Firebase Firestore

---

## 📦 시스템 구성

| 구성 요소 | 기술 스택 | 역할 |
|----------|------------|------|
| **Frontend** | Next.js, TypeScript, Tailwind | 사용자 인터페이스 및 피드백 뷰 |
| **Backend** | FastAPI, Python | 분석 요청 처리, DB 관리 |
| **AI 분석** | GPT, Whisper, Emotion/Tracking Model | 실시간 인터뷰 분석 |
| **DB** | MongoDB | 유저별 분석 결과 저장 |

---

## 🎯 프로젝트 목표

1. **지원자 맞춤형 피드백 제공**
2. **AI 기반 실시간 분석 기술의 실무 적용**
3. **실제 채용 프로세스 대응 가능한 결과 제공**

---

# 💼 실전 프로젝트

### ✅ 관제 솔루션 - 위험 상황 감지 및 시각화
> 실시간 낙상/화재 감지, 프론트-백 분리 구성

- [분석 서버 (YOLOv5 + FastAPI)](https://github.com/mayway77/Risk_Detection_Server)  
- [프론트엔드 (React + Socket 통신)](https://github.com/mayway77/Risk_Detection_Client)

### ✅ 교통사고 분석 AI 솔루션
> 대전 유성구 사고 데이터를 기반으로 사고 예측, 히트맵 시각화 제공 및 솔루션 제시  
[🔗 GitHub](https://github.com/mayway77/Daejeon_Yuseong_Accidents)

---

# 🛠 학습 기반 프로젝트

| 프로젝트명 | 기술 스택 | 요약 |
|------------|-----------|------|
| **WCF 가족오락관** | C#, WCF | 양방향 통신 미니게임 |
| **휴게소 키오스크** | C#, WCF | 주문 흐름 기반 UI 시뮬레이션 |
| **음식점 예약 시스템** | C#, WCF | 예약 관리 및 시각화 실습 |

---

## ✨ GitHub에서 주목할 점

🧩 EmpAI - 실전 기술을 직접 다룬 경험  
GPT, Whisper, 감정 인식, 시선 추적 등 **AI 기반 기술**을 직접 연동하고 구현하며,  
자기소개서 분석부터 AI 면접 피드백까지 **취업 플랫폼의 실전 기능 흐름**을 체득했습니다.

🌐 배포 경험 - 실사용 환경 설계  
`emp-ai.kro.kr`에 실제 플랫폼을 배포하고,  
**로그인 → 입력 → 분석 → 결과 출력**까지 사용자가 바로 체험할 수 있는 구조를 만들었습니다.

🧱 프론트-백 분리 구조 경험  
Next.js 프론트엔드와 FastAPI 백엔드를 분리 구성하고 연동하여  
**클라이언트/서버의 역할 분리, REST API 설계, 통신 흐름의 실전 이해도**를 높였습니다.

🔧 문제 중심 개발 관점  
단순 기능 구현이 아닌, **취업 준비생이 겪는 문제를 해결하는 방식**으로  
자기소개서 피드백, AI 면접 등 기능을 설계하며 **목적 중심 사고**를 키웠습니다.

📊 전방위 개발 경험  
Firebase DB 설계, 영상 분석 API, UI 구성까지 한 흐름에서  
**백엔드부터 데이터 분석, UI 표현까지 전체 과정**을 직접 담당했습니다.

---

🎯 사이드 & 학습 프로젝트로 실전 감각 다지기

🛠 **관제 시스템**  
YOLOv5 기반 위험 감지 모델을 통해 **백엔드 서버 구현**,  
React 기반 시각화 클라이언트를 통해 **실시간 위험 대응 시스템** 구축 경험을 쌓았습니다.

📌 **교통사고 분석**  
지역 데이터를 수집·분석하고, **실질적인 사고 패턴을 시각화**하여  
데이터 분석 → 인사이트 도출의 과정을 직접 수행했습니다.

💬 **WCF 학습 프로젝트**  
C# 기반 WCF를 활용한 가족오락관 게임, 키오스크, 예약 시스템 등  
**통신 기반 프로그램의 구조와 흐름**을 실습했습니다.

---

## 🙋‍♂️ 개발 철학

🎯 성장하는 개발자가 되기 위한 태도
실무 경험은 없지만, 빠른 적응력과 책임감 있는 태도로 어떤 환경에서도 최선을 다합니다.
모르면 배우고, 배운 건 나누며 함께 성장하는 개발자가 되겠습니다.

---

## 📬 연락처

- Email: **kimminsu288@gmail.com**  
- GitHub: [github.com/mayway77](https://github.com/mayway77)  
- 포트폴리오 링크: [emp-ai.kro.kr](https://emp-ai.kro.kr)
