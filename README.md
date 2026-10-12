<div align="center">

# 이시현 · Shihyun Lee

### AI Data · Backend Engineer

**흩어진 데이터를 모으고, 정제하고, AI가 믿고 쓸 수 있는 지식으로 만듭니다.**

<a href="mailto:seolbaek56@gmail.com"><img src="https://img.shields.io/badge/Email-seolbaek56@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
<img src="https://img.shields.io/badge/SKKU-Software-0A3D2E?style=flat-square"/>
<img src="https://img.shields.io/badge/SSAFY-Embedded_Track-1428A0?style=flat-square&logo=samsung&logoColor=white"/>
<img src="https://img.shields.io/badge/TOEIC-970-4B8BBE?style=flat-square"/>
<img src="https://img.shields.io/badge/OPIc-AL-4B8BBE?style=flat-square"/>
<img src="https://img.shields.io/badge/SQLD-Certified-336791?style=flat-square"/>

</div>

---

## 👋 About

- **데이터 파이프라인** — Drive·Notion·로컬·웹 등 출처가 다른 데이터를 수집해 정제·분할·메타데이터를 붙여 적재합니다.
- **AI가 쓰는 지식 설계** — 벡터 DB 기반 RAG, 실행 전 컨텍스트 주입, 도구를 호출하는 멀티 에이전트 구조를 만들어 왔습니다.
- **정합성과 안정성** — 트랜잭션·트리거, 식별자 기반 연결, 단위 예외 격리로 "한 건의 실패가 전체를 멈추지 않는" 구조를 지향합니다.
- **근거로 판단** — 추측보다 로그와 데이터로 원인을 좁히고, 같은 문제가 반복되지 않도록 구조를 바꿉니다.

<br/>

## 🛠 Tech Stack

| 분야 | 기술 |
|:---:|:---|
| **Language** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) |
| **Data · AI** | ![PostgreSQL](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) |
| **Infra** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |
| **Client** | ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white) |

<br/>

## 📌 Projects at a Glance

| # | 프로젝트 | 핵심 키워드 | 역할 |
|:---:|:---|:---|:---|
| 1 | **개인 지식 검색 서비스** | 문서 수집·정제·분할·벡터 적재, 멀티 에이전트 | 수집·검색 파이프라인 |
| 2 | **LLM 에이전트 개인화 추천** | RAG 메모리, 피드백 학습 루프, K8s 배포 | RAG·피드백 파이프라인 |
| 3 | **퍼스널 컬러 AI 진단·추천** | 인터페이스 설계, 서버 추론, 데이터 수집 | 3인 팀장 |
| 4 | **수어 인식 VR 게임** 🏆 | AI 서버 실시간 연동, 비동기 구조 | AI–게임 연동 |
| 5 | **한국어 이미지 VQA 챌린지** | 학습·추론·앙상블 자동화, 로짓 스코어링 | 인프라·파이프라인 |
| 6 | **교내 매칭 웹앱** | 트랜잭션, SQL 트리거, API 스펙 | 백엔드 |
| 7 | **인터랙티브 게임 10종 (인턴)** | 공통 프레임워크, 운영 안정화 | 기획·개발·배포 |

<br/>

---

## 1. 개인 지식 검색 서비스
> Google Drive · Notion · 로컬 문서를 수집해 의미 기반으로 검색하는 지식 검색 서비스

`3인 팀` `FastAPI` `ChromaDB` `ko-sroberta` `LangChain` `Docker Compose` · [Repository](https://github.com/chaerinotcherry/personal-search-agent)

**담당** 수집 커넥터 · 문서 정제/분할/임베딩 · 검색 API · 지식 공백 분석

```mermaid
flowchart LR
    A[Google Drive] --> D
    B[Notion] --> D
    C[Local Files] --> D
    D[수집 커넥터] --> E[정제<br/>제어문자·짧은 조각 제거]
    E --> F[분할<br/>문단·문장 경계 우선]
    F --> G[메타데이터<br/>출처·경로·작성일·순서]
    G --> H[(벡터 DB<br/>ID 기반 upsert)]
    H --> I[검색 API]
    H --> J[지식 공백 분석<br/>3-Agent]
```

<details>
<summary><b>설계 포인트 자세히 보기</b></summary>
<br/>

| 구분 | 내용 |
|---|---|
| **분할** | 문단 → 문장 → 공백 순으로 경계를 우선하는 재귀 분할, 512자 · 64자 오버랩 |
| **정제** | 제어문자·null 문자 제거, 의미 없는 10자 이하 조각 제외, 입력 길이 상한 |
| **중복 방지** | `문서 식별자 해시 + 조각 순서`로 ID를 만들어 재수집 시 덮어쓰기(upsert) |
| **확장성** | 저장 방식을 환경 변수로 전환하는 커넥터 팩토리 구조로 로컬 → 클라우드 전환 대비 |
| **지식 공백 분석** | 단순 군집화 방식을 역할을 나눈 3개 에이전트가 도구를 호출하며 협력하는 구조로 재설계, 목표 기반 학습 로드맵, LLM API 호출 제한 처리 |
| **배운 점** | 출처마다 작성일 형식이 달라 정렬이 어긋나는 문제를 겪으며, 메타데이터는 **수집 시점에 표준화**해야 한다는 기준을 세움 |

</details>

---

## 2. LLM 에이전트 기반 개인화 추천 서비스
> 쓸수록 사용자에게 맞춰지는 멀티 에이전트 라이프스타일 추천 서비스

`3인 팀` `8주` `pgvector` `LangGraph` `DSPy` `React PWA` `Kubernetes`

**문제** 에이전트가 실행할 때마다 사용자를 처음 보는 것처럼 동작해 추천이 개인화되지 않음

```mermaid
flowchart LR
    A[추천 요청] --> B[(취향 메모리<br/>pgvector)]
    B -->|관련 이력 검색| C[에이전트 실행<br/>컨텍스트 주입]
    C --> D[추천 결과]
    D --> E[사용자 피드백]
    E -->|저장·프롬프트 최적화| B
```

- 사용자 취향 이력을 벡터 DB에 저장하고 **에이전트 실행 직전 검색해 주입하는 RAG 메모리** 설계
- 피드백 수집 화면 → 저장 → 프롬프트 최적화 반영까지 **학습 루프** 구현
- 히스토리 뷰와 PWA 클라이언트 구현, Kubernetes 환경에 배포

---

## 3. 퍼스널 컬러 AI 진단 · 화장품 추천 서비스
> 얼굴 사진으로 퍼스널 컬러를 진단하고 맞춤 색조 화장품을 추천하는 Android 서비스

`룰루랩 산학협력` `3인 팀장` `2024.04–12` `Kotlin` `Flask` `PyTorch` `Firebase`

```mermaid
flowchart LR
    A[Android 앱<br/>CameraX] -->|이미지 전송| B[Flask AI 서버<br/>진단 모델]
    B -->|결과 즉시 전달| A
    B -.->|이력 저장| C[(Firebase)]
    C -.->|추천·즐겨찾기 조회| A
```

| 결정 / 문제 | 해결 | 결과 |
|---|---|---|
| 모델을 어디서 실행할까 | 발열·모델 교체 비용을 고려해 단말 대신 **서버 추론** 선택 | 앱 재배포 없이 모델 개선 |
| 피부톤 신호 왜곡 | 색조·채도 변환 증강을 빼고 **색상 보존 증강만** 사용 | 정확도 **83% → 88.7%** |
| 결과 화면 0.5초 지연 | 저장 후 재조회 왕복을 찾아 **전달과 저장 경로 분리** | 지연 제거 |
| 경계선 사용자 신뢰 문제 | 응답 형식을 **상위 2개 결과 + 확률**로 먼저 정하고 파트별 반영 | 기업 요구 반영 |
| 추천 데이터 수집 실패 | 옵션명 대신 **상품 코드+옵션 코드 복합 식별자**, 상품 단위 예외 격리 | 옵션 765개·리뷰 수집 |

---

## 4. 수어 인식 VR 게임 — Magic & Merge 🏆
> 수어 동작을 콤보로 조합해 마법을 발동하는 핸드 트래킹 VR 게임

`2024 메타버스 개발자 경진대회 Meta상(장려상)` `Unity` `C#` `Flask` `AWS EC2` `LSTM` · [Repository](https://github.com/sighen/MetaConte)

```mermaid
flowchart LR
    A[Meta Quest 2<br/>핸드 트래킹] --> B{제스처 필터<br/>일정 시간 유지?}
    B -->|Yes| C[비동기 요청]
    C --> D[AWS EC2<br/>Flask + LSTM]
    D -->|결과 콜백| E[스킬 발동]
    B -->|No| A
```

- **문제** 스킬 발동 지연과 화면 끊김 → 팀은 모델 정확도를 의심해 재학습했지만 해결되지 않음
- **원인** 서버 응답 로그와 게임 루프 프레임 타이밍을 비교해 **동기 블로킹**을 찾아냄
- **해결** 요청·응답 대기를 렌더링과 비동기로 분리, 매 프레임 호출을 **제스처 유지 시에만 호출**하도록 필터링 → 끊김 제거, 서버 부하·오인식 감소
- 개발 전 MVP로 사용자 설문·인터뷰를 진행해 튜토리얼·가이드 UI로 기획 보완

---

## 5. 한국어 이미지 기반 VQA 챌린지
> 이미지·질문·4개 선택지에서 정답을 고르는 과제, API 없이 로컬 오픈웨이트 모델만 사용

`SSAFY` `4인 팀` `3일` `Qwen-VL` `Gemma` `LoRA SFT`

- **담당** 팀 인프라와 학습·추론·앙상블 파이프라인을 **스크립트로 자동화**, 생성 대신 **로짓 스코어링 추론**(파싱 실패 제거)과 **TTA** 구현
- **팀 결과** 해상도 384 → 1280 조정으로 8B 모델 81.4% → 95.4%, 4개 모델 확률 소프트보팅 앙상블 검증셋 97.4%
- **회고** 74문항에서 좋아 보이던 기법이 933문항에서는 효과가 없음 → 실제 규모 재검증 원칙 / 약한 라벨 추가 시 성능 하락 → 노이즈 비율 측정 후 투입 기준 수립

---

## 6. 교내 밥약 매칭 웹 애플리케이션 (스푼메이트)
> 학생 간 식사 약속을 매칭하는 웹 서비스

`소프트웨어공학개론` `7인 팀` `2024.03–07` `React` `Node.js` `Express` `RDB`

- 매칭 확정 시 상태 변경과 알림 생성을 **하나의 트랜잭션**으로 묶어 한쪽만 성공하는 불일치 방지
- 폴링 대신 확정 이벤트에 알림 레코드를 자동 생성하는 **트리거를 SQL로 직접 작성**
- 연동 단계 응답 형식 충돌을 **구현 전 API 스펙 확정·SRS 문서화**로 해결, 통합 파싱 오류 감소

---

## 7. 대형 스크린 인터랙티브 게임 10종 — 에스엠메이커스 인턴
> 10주 안에 전시용 게임 10종을 기획부터 배포까지

`2인 팀` `2024.12–2025.02` `Unity` `C#`

- 초반 1~2주를 **제네릭 싱글턴 + 공통 베이스 클래스** 설계에 투자 → 새 게임은 상속만으로 추가
- 게임 시작 코루틴 중복 실행을 **상태 기반 제어**로 막고 공통 구조에 반영
- UI 입력 가로채기 문제를 판정 로직 분리로 해결, 전시 환경별 해상도 대응
- **10종 전부 기한 내 전시 시연 완료**

---

## 🏆 Awards · Certificates · Education

| 구분 | 내용 |
|---|---|
| 🏆 수상 | **2024 메타버스 개발자 경진대회 Meta상(장려상)** · 과학기술정보통신부 주최 / 한국전파진흥협회 시상 (2024.10) |
| 📜 자격 | SQLD · TOEIC 970 · OPIc AL |
| 🎓 학력 | 성균관대학교 소프트웨어학과 (2026.08 졸업) |
| 📚 교육 | SSAFY 임베디드 트랙 (2026.07~) |
| 🤝 봉사 | 고등학생 대상 C언어 멘토링 8회 (2025) |
