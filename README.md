<h1 align="center">GitHub Profile README

## 🤔Introduction
빠른 흡수력과 집요함을 강점으로 더 어려운 문제를 풀고자하는 욕심이 많은 백엔드 개발자입니다. 최근에는 짧은 시간에 다양한 Backend 기술과 LangGraph기반 AI-Agent를 결합하여 고난도 기능을 실서비스 수준으로 구현해낸 경험이 있습니다. 시스템의 비효율이나 결함을 개선하는 과정을 즐기며 문제 분석과 디버깅에도 장점을 가지고 있습니다. 
([Agent아키텍처 리팩토링](https://computer-travel.netlify.app/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8/%EB%82%98%EB%A7%8C%EB%AC%B4/ai-agent/ai-agent%20%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98%20%EB%A6%AC%ED%8C%A9%ED%86%A0%EB%A7%81%20-%20tool%20%EC%96%B4%EB%8C%91%ED%84%B0%20%ED%8C%A8%ED%84%B4%EA%B3%BC%20%ED%9B%84%EC%B2%98%EB%A6%AC%20%EB%85%B8%EB%93%9C%20%EB%B6%84%EB%A6%AC%20%ED%8C%A8%ED%84%B4/), [대용량 데이터 성능 최적화](https://computer-travel.netlify.app/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8/monew/%EC%9D%B4%EC%A0%84%20%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%20-%20%EC%B5%9C%EC%A0%81%ED%99%94%20%ED%95%B4%EB%B3%B4%EA%B8%B0/), [PintOS전체후기](https://computer-travel.netlify.app/pintos/pintos%20%EC%A0%84%EC%B2%B4%20%ED%9B%84%EA%B8%B0/))

## ⚡Projects

### 동행 매칭 및 AI 기반 실시간 협업 플래너 - Backend/AI/DB 담당 (PL)
2025년 10월 25일 ~ 2025년 11월 29일 -  Front(2), Back(4)
- **LangGraph 기반 AI Agent 구현** : 사용자와 대화하며 맥락을 이해하고 장소 추천, 일정 생성/수정/진단, 서비스 내 각종 서비스 제공 등 상태기반 대화형 AI Agent 시스템 구현
- **Prompt Caching 적용을 통한 비용 최적화 구조 설계** : AI Agent에 Prompt Caching을 도입하여 26k tokens 규모의 시스템 프롬프트를 캐시에 고정하여 평균 입력 토큰을 34k → 8k(76% 감소), 장기 세션에서는 100% Cache Hit을 유지하는 비용 최적화 구조를 완성
- **Redis I/O Adapter, Cache 기반 실시간 협업 시스템 구현** : 분산 환경에서도 모든 사용자에게 동일한 상태(채팅-마킹-일정-커서 등)가 동기화. 마킹/수정/삭제 이벤트로 인한 DB 부하를 줄이고 초기 로딩 시간을 단축하기 위해 Cache 설계.
- **공간 검색 최적화** : 공간 검색 구조를 전면리팩토링하여 최대 181배의 반경 검색 속도 개선을 달성. 뷰포트 조회는 20-80ms 수준으로 지연 분산을 안정화
- 그 외 : 장소 데이터 수집/가공 파이프라인 구축 후 배포, 행동 추적 기반 개인화/전체 추천 시스템, DB 설계-관리, 프로젝트 세팅, OR-Tools를 활용한 경로 최적화 기능 등

### 코드잇 중급 프로젝트 - 개인 맞춤형 뉴스, 소셜 기능 제공 뉴스 플랫폼 - Backend
2025년 04월 16일 ~ 2025년 5월 12일 - Back(5)
- Spring Batch 기반 뉴스 기사 수집 및 알림 자동화 : 뉴스 수집·필터링·저장 과정을 배치로 자동화하여 기사 처리 흐름 구축
- S3를 통한 기사 백업 및 복구 프로세스 구현 : 기사 원문을 S3에 주기적으로 백업하고 장애 상황에서도 복구 가능한 저장 구조를 설계
- 배치 알림 생성 최적화 : 조인 기반 한방 쿼리를 리팩토링하고 재설계하여, 5개 테이블 50M~100M 데이터 환경에서 무한 로딩이던 배치를 125ms로 단축



## 📝공부 일지들 
1. 커스텀 블로그, 옵시디언(2025. 5 ~ ing)
    - [배포된 자료 사이트](https://computer-travel.netlify.app/)
    - [미배포 자료 포함](https://github.com/ARlegro/obsidian-backup)

2. 노션(2024. 10 ~ 2025. 5) - JAVA, SPRING, JPA 위주 
    - [개발 공부](https://www.notion.so/717c531d38de4a248608354bcf95a9bd)
  
3. 티스토리(중간에 옵시디언으로 이주)
    - https://inform-f-e.tistory.com/

## 🎿MY STACK

---
### 💻 Backend
![Java](https://img.shields.io/badge/Java-007396?logo=java&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?logo=spring&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?logo=hibernate&logoColor=white)
![Querydsl](https://img.shields.io/badge/Querydsl-0769AD?logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)

---

**🤖 AI / LLM Stack**

![LangGraph](https://img.shields.io/badge/LangGraph-000000?logo=github&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=python&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?logo=postgresql&logoColor=white)

---
### 🏗️ Infra 
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?logo=rabbitmq&logoColor=white)

![AWS S3](https://img.shields.io/badge/AWS%20S3-569A31?logo=amazonaws&logoColor=white) 
![AWS RDS](https://img.shields.io/badge/AWS%20RDS-527FFF?logo=amazonaws&logoColor=white) 
![AWS EC2](https://img.shields.io/badge/AWS%20EC2-FF9900?logo=amazonaws&logoColor=white)
![ECS Fargate](https://img.shields.io/badge/ECS%20Fargate-FF9900?logo=amazonaws&logoColor=white) 
![ECR](https://img.shields.io/badge/AWS%20ECR-FF9900?logo=amazonaws&logoColor=white) 

---
### 🧰 Tools & Productivity
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)
![DBeaver](https://img.shields.io/badge/DBeaver-372923?logo=dbeaver&logoColor=white)

![Obsidian](https://img.shields.io/badge/Obsidian-483699?logo=obsidian&logoColor=white)

![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000?logo=intellijidea&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/VS%20Code-007ACC?logo=visualstudiocode&logoColor=white)



## 🏫Education 
- 홍익대학교(2016. 3 ~ 2024.7)
- 코드잇 SB 1기(2024.12.28 ~ 25.07.04)
- 크래프톤 정글 10기(2025.07.07 ~ 25.12.12)
  - [회고 시작](https://computer-travel.netlify.app/retrospect/0707%20~%201204%20-%20crafton%20jungle/0710%20~%200716%20%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98,%20cs%20%EC%8B%9C%EC%9E%91/) (Retrospect -> 0707 ~ 1204)
  - [Pintos 후기 글](https://computer-travel.netlify.app/pintos/pintos%20vm/pintos%20%EC%A0%84%EC%B2%B4%20%ED%9B%84%EA%B8%B0/)


## contact
gmail : icb1696@gmail.com
naver : icb1696@naver.com
