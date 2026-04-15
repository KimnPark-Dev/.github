<!-- ══════════════════════════════════════════════════════
   KimnPark-Dev  ·  GitHub Organization Profile
══════════════════════════════════════════════════════ -->

<div align="center">

<br/>

<h1>
  <span style="color:#c084fc">Kim</span>
  <span style="color:#6b7280">&</span>
  <span style="color:#38bdf8">Park</span>
</h1>

### We build things together.

<p>두 개발자가 아이디어를 코드로 만드는 공간</p>

<br/>

[![Status](https://img.shields.io/badge/●%20함께%20만들고%20있습니다-4ade80?style=flat-square&labelColor=0d0d14&color=4ade80)](https://github.com/KimnPark-Dev)
&nbsp;
[![GitHub Org](https://img.shields.io/badge/KimnPark--Dev-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/KimnPark-Dev)

<br/>

---

</div>

## 👥 Who we are

> 같은 기수, 같은 목표. 아이디어가 생기면 바로 코드로 옮기는 듀오입니다.

<br/>

<table>
<tr>
<td align="center" width="50%">

### 🟣 INSONG KIM

[![GitHub](https://img.shields.io/badge/insongK-c084fc?style=for-the-badge&logo=github&logoColor=white)](https://github.com/insongK)

**Security & Dev**

네트워크 보안부터 Chrome Extension까지 폭넓게 다룹니다.
ARP Spoofing, pcap 분석, CNN 모델 구현 경험을 바탕으로
시스템 레벨부터 응용 레이어까지 설계합니다.

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C%2FC++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Network Security](https://img.shields.io/badge/Network%20Security-c084fc?style=flat-square)
![AI/CNN](https://img.shields.io/badge/AI%2FCNN-c084fc?style=flat-square)

</td>
<td align="center" width="50%">

### 🔵 DOHYUN PARK

[![GitHub](https://img.shields.io/badge/0206pdh-38bdf8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/0206pdh)

**Backend & Cloud**

클라우드 네이티브 백엔드와 AI 파이프라인을 설계합니다.
AWS Serverless, FastAPI 기반 서비스 구축과 LLM 활용
시스템 개발에 집중합니다.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![LLM](https://img.shields.io/badge/LLM-38bdf8?style=flat-square)
![Serverless](https://img.shields.io/badge/Serverless-FD5750?style=flat-square&logo=serverless&logoColor=white)

</td>
</tr>
</table>

<br/>

---

## ⚙️ Tech Stack

> 개발을 위해 함께 활용하는 기술들

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Chrome Extension](https://img.shields.io/badge/Chrome%20Extension-4285F4?style=flat-square&logo=googlechrome&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-6b7280?style=flat-square)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Algorithm](https://img.shields.io/badge/Algorithm%20%7C%20BOJ-6b7280?style=flat-square)

</div>

<br/>

---

## 🚀 Projects

### `01` TalkTime &nbsp; ![Status](https://img.shields.io/badge/Phase%201%20완료-4ade80?style=flat-square) ![Date](https://img.shields.io/badge/2026.04%20—-6b7280?style=flat-square)

> **GPS proximity 매칭 + 2D 메타버스 기반 실시간 스몰토크 플랫폼**

닉네임 · 인스타그램 ID · GPS를 입력하고 입장하면, 실제 위치 기반 허브에 배치됩니다.
2D 맵에서 근처 사람에게 커피 ☕ 또는 담배 🚬 대화를 신청하고, 상대가 수락하면
30초 1:1 채팅이 시작됩니다. 종료 후 양측이 동의하면 인스타그램 ID를 교환합니다.

| 분류 | 내용 |
|------|------|
| GPS 매칭 | Haversine 거리 계산 · 서울 5개 허브(강남 / 광화문 / 여의도 / 서초 / 구로가산) |
| Realtime | socket.io 4 · 50ms 위치 동기화 (20Hz) · lerp(0.18) 보간 |
| 대화 플로우 | 커피 / 담배 요청 → 30초 1:1 채팅 → 인스타그램 ID 교환 모달 |
| 프라이버시 | 인스타그램 ID 서버에서만 보관, 양측 수락 시에만 채팅으로 공개 |

![React](https://img.shields.io/badge/React%2018-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Canvas API](https://img.shields.io/badge/Canvas%20API-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![socket.io](https://img.shields.io/badge/socket.io%204-010101?style=flat-square&logo=socketdotio&logoColor=white)

---

### `02` AlgoNotion &nbsp; ![Status](https://img.shields.io/badge/●%20출시%20완료-38bdf8?style=flat-square) ![Date](https://img.shields.io/badge/2026.03%20—%202026.04-6b7280?style=flat-square)

> **BOJ·SWEA 풀이 기록을 Notion으로 저장**

백준과 SWEA에서 풀이한 알고리즘 문제를 Notion 데이터베이스로 정리하는 Chrome Extension입니다.
Chrome Web Store에 배포되어 실제 사용 가능한 상태입니다.

| 분류 | 내용 |
|------|------|
| Extension | Content Script · Service Worker · Manifest V3 |
| Integration | Notion API · solved.ac API · BOJ · SWEA |

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Chrome Extension](https://img.shields.io/badge/Chrome%20Extension-4285F4?style=flat-square&logo=googlechrome&logoColor=white)
![Notion API](https://img.shields.io/badge/Notion%20API-000000?style=flat-square&logo=notion&logoColor=white)
![solved.ac](https://img.shields.io/badge/solved.ac-6b7280?style=flat-square)
![Manifest V3](https://img.shields.io/badge/Manifest%20V3-4285F4?style=flat-square)

[![View on GitHub](https://img.shields.io/badge/GitHub-Extension%20Repo-181717?style=flat-square&logo=github)](https://github.com/KimnPark-Dev/AlgoNotion_Extention/tree/main)

---

### `03` MoveRadar &nbsp; ![Status](https://img.shields.io/badge/●%20해커톤%20출품%20완료-f59e0b?style=flat-square) ![Date](https://img.shields.io/badge/2026.04%20—%202026.04-6b7280?style=flat-square)

> **이사 수요를 1~2개월 선행 탐지하는 Snowflake Native 인텔리전스 파이프라인**

Snowflake KR Hackathon 2026 테크 트랙 출품작입니다.
기존 CRM은 이미 관심을 드러낸 사람에게만 반응하지만, MoveRadar는 아직 이사를 인지하지 못한 사람을 **구조적 시장 신호**로 먼저 탐지합니다.

| 분류 | 내용 |
|------|------|
| 데이터 소스 | Snowflake Marketplace 4개 — 아파트 시세(Dataknows) · 전입인구(Dataknows) · 통신 가동(삼성네트웍스) · 카드소비(SPH) |
| Pipeline | 전처리 → 고객 프로파일 → Cortex Anomaly Detection(4모델) → REGION_ALERTS 통합 → LLM 문구 생성 |
| 신호 가중치 | 시세 0.40 · 전입인구 0.25 · 통신 가동 0.20 · 카드소비 0.15 |
| LLM | Cortex COMPLETE / mistral-large2 · 15가지 경보 유형별 맞춤 마케팅 카피 자동 생성 |
| Dashboard | Streamlit Native App 4탭 — 경보 지도 · 신호 트렌드 · 마케팅 문구 · 렌탈/통신 트렌드 |

![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Cortex ML](https://img.shields.io/badge/Cortex%20ML-29B5E8?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![LLM](https://img.shields.io/badge/mistral--large2-6b7280?style=flat-square)
![Hackathon](https://img.shields.io/badge/Hackathon-f59e0b?style=flat-square)

---

## 📬 Contact

<div align="center">

| | |
|---|---|
| 🏢 **Team GitHub** | [github.com/KimnPark-Dev](https://github.com/KimnPark-Dev) |
| 🟣 **INSONG KIM** | [github.com/insongK](https://github.com/insongK) |
| 🔵 **DOHYUN PARK** | [github.com/0206pdh](https://github.com/0206pdh) |
| 📧 **Email** | [0206pdh@naver.com](mailto:0206pdh@naver.com) |

<br/>

> 협업 제안, 피드백, 아니면 그냥 안녕도 환영합니다 👋

<br/>

---

<sub>© 2026 Kim & Park · Built together.</sub>

</div>
