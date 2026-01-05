![header](https://capsule-render.vercel.app/api?type=venom&color=auto&height=300&section=header&text=GOD%20Hand&fontSize=90&stroke=ffffff)


# 🧤 Smart Rehabilitation Glove Project  
### Five’s Tab

손가락 움직임을 Flex Sensor로 감지하여 웹 기반 게임과 연동하고,  
운동 데이터를 시각화하는 **교육·연구 목적 스마트 재활 글러브 프로젝트**

---

## 👥 팀 구성

| 역할 | 이름 | 주요 담당 |
|---|---|---|
| PM & Docs | 이영수 | 프로젝트 총괄, 일정 관리, 문서화, 발표 |
| HW | 정채영 | 글러브 외형, 센서 회로, Arduino 연동 |
| HW | 권효성 | 센서 회로 구현, 하드웨어 테스트 |
| FE | 최현서 | 웹/게임 UI, 게임 로직, 시각화 |
| BE | 신령미 | 센서 데이터 처리, 통신, 데이터 저장 |

---

## 기술 스택
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) 
![Chart.js](https://img.shields.io/badge/chart.js-F5788D.svg?style=for-the-badge&logo=chart.js&logoColor=white)
<br>
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/sqlalchemy-%23D71F00.svg?style=for-the-badge&logo=sqlalchemy&logoColor=white)
<br>
![Arduino IDE](https://img.shields.io/badge/Arduino%20IDE-%2300979D.svg?style=for-the-badge&logo=Arduino&logoColor=white)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
<br>
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)
<br>
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)

---

## 📅 단계별 일정 분할

| 단계 | 기간 | 목표 | 완성 기준 (Feature) | 비고 |
|---|---|---|---|---|
| 1 | 2026-03-03 ~ 03-16 (2주) | 프로젝트 정의 | MVP 정의<br>기능 명세서<br>시스템 아키텍처<br>데이터 수집 항목 | Git 협업 규칙 |
| 2 | 2026-03-17 ~ 04-06 (3주) | 센서 → PC 통신 | 센서 회로<br>Arduino 데이터 수신<br>웹 게임 프로토타입 | 센서 인식 성공 |
| 3 | 2026-04-07 ~ 04-27 (3주) | 게임 동작 | 웹 게임 MVP<br>API 구조<br>DB 스키마 | |
| 4 | 2026-04-28 ~ 05-18 | HW-SW 통합 | 실시간 제어<br>에러 핸들링<br>캘리브레이션<br>데이터 저장 | 노이즈 처리 |
| 5 | 2026-05-19 ~ 06-07 (3주) | 시각화 & 배포 | 그래프 구현<br>웹 배포 완료 | 사용자 통계 |
| 6 | 2026-06-08 ~ 06-22 (2주) | 기능 동결 & 발표 | PPT<br>시연 영상<br>아키텍처 설명 | 코드 최소 수정 |

---

## 📅 기간별 완성도 데드라인

| 단계 | 기간 | 역할 | 완성 기준 (Deadline Definition) | 비고 |
|---|---|---|---|---|
| 1 | 2026-03-03 ~ 03-16 | H/W + CE | 글러브 구조 스케치<br>센서 배치안 확정<br>부품 리스트 작성 | 시스템 설계 |
|   |                    | S/W | 전체 아키텍처 설계<br>WebSocket 통신 구조<br>게임 MVP 스펙 정의 | |
| 2 | 2026-03-17 ~ 03-21 | H/W + CE | Flex 센서 회로도<br>Arduino 핀맵 확정<br>센서 단독 테스트 성공 | 회로 1차 |
|   |                    | S/W | Flask 서버 구조 생성<br>WebSocket 연결 PoC 성공 | |
| 3 | 2026-03-22 ~ 04-04 | H/W + CE | 글러브 실물 제작 완료<br>센서 인식률 90% 이상<br>USB 연결 안정화 | HW 완성 |
|   |                    | S/W | Serial 데이터 수신 코드<br>JSON 파싱 구조 완성 | |
| 4 | 2026-04-05 ~ 04-25 | H/W + CE | 센서 값 정규화<br>Moving Average 필터 적용<br>노이즈 기준 정의 | 통신 안정 |
|   |                    | S/W (FE) | 임시 데이터 시각화 페이지 구현 | |
|   |                    | S/W (BE) | WebSocket ↔ Serial 브리지 구현<br>실시간 데이터 전송 | |
| 5 | 2026-04-26 ~ 05-23 | H/W + CE | 캘리브레이션 기준값 고정<br>입력 오작동 최소화 | 게임 연동 |
|   |                    | S/W (FE) | HTML/JS 미니게임 MVP 완성<br>Threshold 입력 처리 | |
|   |                    | S/W (Full) | 게임 ↔ 서버 ↔ 센서 통합 성공 | |
| 6 | 2026-05-24 ~ 06-07 | H/W + CE | 연속 사용 10분 이상 오류 없음 | 통합 안정 |
|   |                    | S/W (FE/Data) | 운동량·반복 횟수 시각화 그래프 | |
|   |                    | S/W (BE) | 세션 데이터 CSV 저장<br>사용자 구분 로직 | |
| 7 | 2026-06-08 ~ 06-13 | ALL | 기능 동결<br>Latency 150ms 이하 | 시연 고정 |
| 8 | 2026-06-14 ~ 06-22 | ALL | 시연 영상<br>PPT<br>아키텍처·역할 정리 | 발표 |

---

## ⚠️ 리스크 대응 방안

| 구분 | 리스크 | 세부 문제 | 대응 방안 |
|---|---|---|---|
| 기술적 | 센서 데이터 노이즈 | Flex 센서 미세 흔들림<br>사용자별 기준값 차이 | 1. Moving Average Filter 적용<br>2. 사용자별 캘리브레이션 UI<br>3. 연속 입력 안정 구간 도입 |
| 기술적 | 실시간 통신 불안정 | USB Serial/WebSocket 지연<br>데이터 유실 가능 | 1. 데이터 최소화 전송<br>2. Fail-safe 처리<br>3. 오프라인 CSV 시연 루트 |
| 기술적 | 게임·시각화 난이도 | FE/BE/Data 경험 부족<br>구현 지연 위험 | 1. 검증된 라이브러리 사용<br>2. 지표 수 최소화<br>3. 코드 리뷰 전담 |
| 일정·인적 | 개인 일정 공백 | MT, 시험, 대외활동 등 | 1. 핵심 기능 2인 이상 이해<br>2. 주 1회 진행 공유<br>3. 대체 인원 지정 |
| 일정·인적 | 프로젝트 경험 부족 | 범위 과대 설정<br>일정 지연 | 1. MVP 우선 구현<br>2. 단계별 기능 동결<br>3. 동작 여부 기준 평가 |
| 일정·인적 | 통합 단계 붕괴 | HW-SW 의존성 증가<br>디버깅 장기화 | 1. 통합 전용 기간 확보<br>2. 키보드 기반 대체 시연<br>3. 축소 시연 시나리오 |
| 윤리·법적 | 개인 신체 데이터 | 생체 활동 정보 수집 | 1. 사전 동의 절차 명시<br>2. 사용 목적·보관 기간 고지<br>3. 익명화 처리 |
| 윤리·법적 | 의료기기 오인 | 재활 용어로 오해 가능 | 1. 교육·연구 목적 명시<br>2. 의학적 효능 표현 배제<br>3. 비의료기기 고지 |
| 윤리·법적 | 오픈소스 라이선스 | 라이선스 미확인 사용 | 1. 라이선스 사전 확인<br>2. README 출처 명시<br>3. 비상업적 목적 명시 |

---

## ⚖️ 윤리 및 법적 고지

본 프로젝트는 **교육 및 연구 목적의 프로토타입**이며,  
의료기기 또는 치료·진단 목적이 아닙니다.  
수집된 모든 데이터는 익명화 처리되며 외부로 공유되지 않습니다.

---

## 📌 Repository 구성

- `/GOD-Hand-Arduino` : Arduino 코드, 회로 자료
- `/GOD-Hand-FE` : 웹/게임 UI
- `/GOD-Hand-BE` : Python 서버, 데이터 처리
- /GOD-Hand-Docs` : 문서
- `.github/profile/README.md` : 팀/프로젝트 소개
