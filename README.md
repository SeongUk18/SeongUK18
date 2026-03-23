# Hi there! 👋 I'm SeongUk Han

[![Gmail Badge](https://img.shields.io/badge/Gmail-EA4335.svg?&style=for-the-badge&logo=Gmail&logoColor=white)](mailto:adulty22@gmail.com)
[![Tistory Badge](https://img.shields.io/badge/Tistory-000000.svg?&style=for-the-badge&logo=Tistory&logoColor=white)](https://dev-studyingblog.tistory.com/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-181717.svg?&style=for-the-badge&logo=GitHub&logoColor=white)](https://github.com/SeongUk18)
[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=LinkedIn&logoColor=white)](https://www.linkedin.com/in/seonguk-han-6b2307314/)

---

## 👨‍💻 About Me

데이터 모델링과 API 서버 개발, AI 파이프라인 설계에 강점을 가진 백엔드 중심의 Software Engineer 한성욱입니다.

### **[Backend & System]**
- Django, FastAPI 기반 서버 아키텍처 설계 및 운영
- PostgreSQL Full-Text Search 도입, ORM 최적화를 통한 대용량 데이터 조회 성능 개선
- Docker, Docker Compose 기반 컨테이너 환경 구축 및 배포

### **[AI & Data Engineering]**
- Bi-Encoder + Cross-Encoder 결합 다단계 인재 추천 파이프라인 구축
- LangGraph 활용 데이터 증강 및 LLM 기반 자연어 검색·이력서 요약 기능 개발
- LSTM 딥러닝 모델을 활용한 설비 에너지 사용량 최적화 (약 20% 비용 절감)

---

## 💼 Work Experience

### **Smilegate Holdings**
**Talent Relations 팀 / 인턴** | 2025.04 —

> **DX/AX 기반 토탈 인텔리전스 플랫폼 (Project TIPS) 개발**
>
> 게임 업계에 분산된 인재 데이터를 통합 관리하고, AI 임베딩/리랭킹·LLM 모델을 활용하여 검색·평가·매칭을 자동화한 TA 자체 HR 플랫폼을 Full-stack으로 기획·설계·개발·운영까지 전 과정을 주도했습니다.

#### 🛠 주요 성과
- **Profile List 검색 성능 96% 개선** (10s → 0.4s)
  - PostgreSQL Full-Text Search 도입 및 Django ORM 최적화
  - N+1 쿼리 해결 (Subquery, OuterRef 활용), Raw SQL 구조 개선
- **통합 검색 API 성능 94% 개선** (3.5s → 0.2s)
  - 불필요한 prefetch_related 제거 및 only() 메서드를 통한 17.5배 성능 향상
- **대용량 DOM 렌더링 99% 개선** (48s → 0.61s)
  - 정적 드롭다운을 Debouncing + 지연 로딩 기반 동적 API 구조로 리팩토링

#### 🤖 AI & 데이터
- **인재 추천 시스템**: Bi-Encoder와 Cross-Encoder를 결합한 다단계 인재 추천 파이프라인 구축
- **LLM 연동**: 자연어 인재 검색, 이력서 요약 및 스킬셋 자동 등급 평가
- **데이터 증강**: LangGraph 활용 게임 프로젝트 데이터 맥락 정보 확장 및 30개 이상 컬럼 자동 증강
- **시스템 설계**: 인재-개발 조직-게임 프로젝트 간 복잡한 구조를 유연하게 매핑하는 TRM 데이터 모델 설계

<br>

### **Genexine**
**의약품 분석팀 / 연구원** | 2016.10 — 2021.06 (4년 7개월)
- 원료 의약품 및 안정성 시험 의약품 품질 분석 및 분석법 개발
- 분석 데이터를 통한 의약품 안정성 결과 예측 업무 진행

---

## 🚀 Projects

### 1. [에이닷 실버 — 어르신 맞춤형 음성 인식 스마트폰 애플리케이션](https://github.com/SKT-FLY/bbd-be)
- **기간**: 2024.07 — 2024.08 (2개월)
- **기술 스택**: Python, FastAPI, MySQL, Docker
- **설명**: 고령층의 디지털 소외 문제를 해결하기 위해 SKT 에이닷 플랫폼을 활용한 음성 인식 기반 맞춤형 서비스 백엔드 개발
- **주요 역할**:
  - ChatGPT API 기반 발화 텍스트 의도 추출 및 서비스 연결 기능 개발
  - TMAP API 활용 사용자 위치 기반 정보 추천 및 콜택시 연결 기능 개발
  - Database 설계 및 구축, Docker Compose 기반 서버 배포
- **성과**: 비동기 처리 도입으로 API 응답 속도 3초 → 1초 미만으로 단축

<br>

### 2. [AIoT 기반 펌프 모터 설비 운영 최적화](https://github.com/AIOT-25)
- **기간**: 2023.09 — 2023.11 (2개월)
- **기술 스택**: Python, Deep Learning, Git
- **설명**: 오폐수 처리 설비에 AIoT 솔루션을 적용하여 에너지 효율을 최적화하는 시스템 구현
- **주요 역할**:
  - Advantech WISE-PaaS SDK를 활용한 NoSQL 기반 센서 데이터 수집
  - 실시간 에너지 사용량, 입력 대비 출력 유량 시각화 대시보드 개발
  - LSTM 딥러닝 알고리즘을 통한 입력 유량 기반 출력값 조절
- **성과**: LSTM 알고리즘 + 심야 시간대 전력 최적화를 통해 에너지 비용 약 20% 절감, **최우수상** 수상

<br>

### 3. 가상환경 기반 자율주행 경진대회 (특별상)
- **기간**: 2023.12 — 2024.02 (3개월)
- **기술 스택**: Python, C++, ROS, Ubuntu, Git
- **주요 역할**:
  - LIDAR 센서와 ICP 알고리즘을 활용한 SLAM 및 내비게이션 구현
  - OpenCV 기반 카메라 데이터 전처리 후 규칙 기반 자율주행 시뮬레이터 개발

<br>

### 4. 인하 인공지능 챌린지 — Multimodal 추천 시스템 (최우수상)
- **기간**: 2023.07 — 2023.08 (2개월)
- **기술 스택**: Python, Deep Learning
- **주요 역할**:
  - 평점, 텍스트, 이미지 데이터를 각각 cosine similarity로 매트릭스 구현
  - Soft voting 방식으로 결합한 멀티모달 추천 시스템 개발

---

## 🏅 Honors and Awards

| 연도 | 대회명 | 수상 |
|------|--------|------|
| 2023.11 | 2023 Advantech AIoT Innoworks Project | 최우수상 |
| 2023.08 | 인하 인공지능 챌린지 | 최우수상 |
| 2024.02 | 가상환경 기반 자율주행 경진대회 | 특별상 |

---

## 📜 Certifications

| 취득일 | 자격증 |
|--------|--------|
| 2025.12 | 정보처리기사 |
| 2025.06 | SQL 개발자 (SQLD) |
| 2025.06 | 데이터분석 준전문가 (ADsP) |

---

## 📚 Education & Training

### SKT FLY AI 프로그램
- **기간**: 2024.06 — 2024.08 (3개월)
- Python 기반 빅데이터 분석·시각화, AI 모델 개발(Decision Trees, DNN, CNN, RNN) 실습
- Docker, Kubernetes, Jenkins, GitHub Actions, Azure 등 클라우드 인프라 및 자동화 도구 실습

### 인하대학교
- **소프트웨어융합공학과** (2021.03 — 2024.08) | GPA 4.14 / 4.5

---

## 📞 Contact

- **Email**: [adulty22@gmail.com](mailto:adulty22@gmail.com)
- **GitHub**: [SeongUk18](https://github.com/SeongUk18)
- **Tistory Blog**: [dev-studyingblog](https://dev-studyingblog.tistory.com/)
- **LinkedIn**: [seonguk-han](https://www.linkedin.com/in/seonguk-han-6b2307314/)
