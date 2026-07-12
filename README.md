<h1 align="center">강희림 · Kang Heerim</h1>
<h3 align="center">DB Administrator</h3>

<p align="center">
  <i>데이터가 쌓이는 곳에서, 쓸 수 있는 데이터로 만드는 사람.</i>
</p>

---
## Portfolio

[포트폴리오 PDF](./강희림_포트폴리오.pdf)

---

## Introduction

Python 기반 데이터 처리와 MariaDB 구축·운영 경험을 보유한 **DBA**입니다.

AI 모델이 만들어낸 분석 결과를 안정적으로 적재하고 활용할 수 있도록 데이터베이스를 관리해왔습니다.

데이터가 매일 쌓이는 환경에서, 그 데이터를 신뢰할 수 있는 형태로 관리하고 연결하는 사람이 되고자 합니다.


---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/PYTHON-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/JAVA-007396?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)

**DB**

![MariaDB](https://img.shields.io/badge/MARIADB-003545?style=flat-square&logo=mariadb&logoColor=white)
![MySQL](https://img.shields.io/badge/MYSQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/ORACLE-F80000?style=flat-square&logo=oracle&logoColor=white)

**Infra**

![AWS EC2](https://img.shields.io/badge/AWS%20EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![Linux](https://img.shields.io/badge/LINUX-FCC624?style=flat-square&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/UBUNTU-E95420?style=flat-square&logo=ubuntu&logoColor=white)

**AI Model**

![YOLO](https://img.shields.io/badge/YOLO-111F68?style=flat-square&logo=yolo&logoColor=white)
![DeepLabV3+](https://img.shields.io/badge/DeepLabV3%2B-2E8B57?style=flat-square)

**Tools**

![VS Code](https://img.shields.io/badge/VS%20CODE-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Notion](https://img.shields.io/badge/NOTION-000000?style=flat-square&logo=notion&logoColor=white)
![Slack](https://img.shields.io/badge/SLACK-4A154B?style=flat-square&logo=slack&logoColor=white)
![Git](https://img.shields.io/badge/GIT-F05032?style=flat-square&logo=git&logoColor=white)

---

## Career Timeline

교육 → 실무 → 현직, 데이터를 다루는 일관된 흐름

| 기간 | 소속 | 내용 |
|---|---|---|
| 2023.09–2024.03 | 엔코아 플레이데이터 | SQL·Python·Linux·Hadoop 기반 데이터 처리 및 파이프라인 구축 실습 |
| 2024.10–2024.12 | ㈜에이더 | 시장조사 및 고객 데이터 수집·분석을 통한 신규 제품 기획 의사결정 지원 |
| 2025.05–재직중 | ㈜코드오브네이처 | AI 모델 개발·DB 운영·웹 서비스 구현·서버 운영 수행 |


---

## Project

### ◼️​ AI 이미지 모델 개발 프로젝트
`2025.08 – 2025.11` · ㈜코드오브네이처 · 1~2인 · 기여도 ★★★

> 산불·화산지형처럼 망가진 땅에 이끼를 심은 뒤, 사람이 일일이 사진을 보며 확인하는 대신 AI가 자동으로 이끼의 종류와 면적을 분석해 주는 시스템입니다.

이끼 탐지(YOLO) + 면적 분할(DeepLabV3+) 모델을 통합해 이끼 이미지 분석 웹 서비스로 배포한 프로젝트.

입사 시점 데이터 정리 체계가 없던 상태에서, 이미지 분석 결과와 사용자 로그를 저장할 MariaDB 구조를 처음부터 직접 설계했습니다.

- 배우체 탐지 모델: 기존 모델 고도화, DB 구축 및 운영, 웹 구현 및 배포 중심으로 참여
- 면적 분할 모델: 모델 개발, DB 구축 및 운영, 웹 구현 및 배포 수행
- **Stack**: `Python` `SQL` `HTML` `MariaDB` `AWS EC2` 

### ◼️​ 복원 예측 모델 웹 서비스 개발 프로젝트
`2026.02 – 2026.05` · ㈜코드오브네이처 · 1인 · 기여도 ★★★

생태 복원 예측 모델을 웹 서비스로 배포한 프로젝트.
기존 초기 코드를 바탕으로 기능을 구체화하고 배포까지 단독 수행했으며, 투자자 대상 IR 발표 자료로 실제 활용되었습니다.

- Input(주소+토양 데이터) → AI Model(복원 결과 예측) → Output(웹 결과 시각화)
- **Stack**: `Python` `SQL` `HTML`

### ◼️​ 팝업스토어 정보 저장 & 추천 웹서비스 개발 프로젝트
`2024.01 – 2024.03` · 엔코아 플레이데이터 (5인 팀) · 기여도 ★☆☆

팝업스토어 정보를 저장하고 추천하는 모바일 웹 서비스를 개발한 프로젝트.

뉴스 아카이브에서 팝업스토어 관련 데이터를 수집·정제해 MariaDB에 적재하고, 프로젝트 기간 동안 DB를 관리했습니다. 

데이터 수집 → 전처리 → 적재 → 추천 모델 서빙까지의 파이프라인을 전 자동화로 구현하고 실제 유저가 이용할 수 있도록 배포까지 완료.

- **Stack**: `Python` `SQL` `MariaDB`

---

## Certificates & Language

| 자격 | 발급기관 | 취득일 |
|---|---|---|
| TOEIC Speaking · Advanced Low | YBM | 2026.06 |
| TOEIC 890점 | YBM | 2026.06 |
| 데이터분석준전문가 (ADsP) | 한국데이터산업진흥원 | 2025.03 |
| 정보처리기사 | 한국산업인력공단 | 2024.06 |
| SQL개발자 (SQLD) | 한국데이터산업진흥원 | 2024.04 |
| MOS Master 2016 | Microsoft | 2022.01 |


---
