<!-- 상단 헤더 및 타이핑 애니메이션 -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=A9DFBF&height=100&section=header&animation=fadeIn" width="100%">
</p>

<div>
  <h3>안녕하세요! 👋</h3>
  <h4>
    다양한 시선으로 일상을 관찰하고, 기술로 가치를 더하는 개발자 <br><br>
  <img src="https://readme-typing-svg.demolab.com?font=Noto+Sans+KR&weight=700&size=24&height=26&duration=2500&pause=1500&color=A9DFBF&center=false&vCenter=true&width=155&lines=%20%EB%B0%B0%ED%98%84%EC%A7%80;Bae+Hyeon-ji" alt="이름 타이핑" style="vertical-align: middle; display: inline-block;">
    입니다.
  </h4>
</div>
<br>

## 🧑‍💻 About Me
> <b>"다양한 시선으로 일상을 관찰하고, 기술로 가치를 더합니다."</b><br>
> 전시기획·운영 실무에서 다진 사용자 경험(UX) 시야와 비즈니스 커뮤니케이션 역량을 바탕으로, <br>
> 견고한 백엔드 아키텍처와 사용자 중심 UI/UX의 조화를 추구하는 풀스택 개발자입니다.
<br>

- 🎓 **Education & Training**
  - SSAFY (삼성 청년 SW 아카데미) | 14기 Python 비전공 트랙 수료 (2025.07 ~ 2026.06)
  - 국비지원 [차세대 가상 엔터테인먼트 콘텐츠 엔지니어 양성 과정] | SW 개발자 양성과정 수료 (2024.08 ~ 2025.03)
  - 동국대학교 WISE캠퍼스 | 호텔관광경영학부 학사 (일어일문학 복수전공)
    
- 📜 **Certificates**
  - 정보처리기사 
  - SQLD 
  - 컴퓨터활용능력 1급 / 워드프로세서 1급
    
- 🗣️ **Language**
  - TOEIC Speaking IM3

<br>

## 🛠️ Tech Stacks
### 💻 Frontend & Mobile
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=black"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=TypeScript&logoColor=white"/> <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=Flutter&logoColor=white"/> <img src="https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=white"/> 


### ⚙️ Backend
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=FastAPI&logoColor=white"/> <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=Django&logoColor=white"/> <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"/> <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=white"/> 

### 🗄️ Database & DevOps
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white"/>

### 🔧 Tools & Platforms
<img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white"/> <img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white"/> <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white"/> <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white"/>

<br>

## 🚀 Projects

### 📱 [Mediger](https://github.com/hyundingi/mediger) — AIoT 기반 시니어 복약 관리 시스템
- **프로젝트 정보:** 고령층 및 디지털 소외 계층을 위해 스마트 약 디스펜서와 앱을 연동하여 안전한 복약을 돕는 방문 약사용 서비스
- **기술 스택:** FastAPI, MQTT, PostgreSQL, Redis, Ubuntu, Docker, Nginx, Kotlin
- **주요 역할 (Infra | Backend):**
  - MQTT 프로토콜을 활용한 스마트 디스펜서 기기 간 실시간 통신 및 데이터 검증 로직 구현
  - 정형화된 환자 데이터를 활용한 AI 방문 보고서 자동 생성 로직 구현
  - 복약 관리 현장 사용성 확보를 위한 비동기(`asyncio.gather`) 및 DB 커넥션 순차 바인딩 최적화로 API 응답 속도 단축
  - Docker, Nginx 기반의 운영 인프라 고도화 및 배포 자동화 파이프라인 구축

---

### 💳 [PaliPay](https://github.com/hyundingi/palipay) — 외국인 관광객을 위한 핀테크 플랫폼
- **프로젝트 정보:** 국내 계좌가 없는 외국인 관광객을 위해 간편한 계좌 이체와 실시간 모바일 결제를 지원하는 금융 서비스
- **기술 스택:** Spring Boot, FastAPI, MySQL, Redis, Jenkins, Docker, Kubernetes, Flutter
- **주요 역할 (Frontend | Backend):**
  - Spring Security 및 JWT를 활용한 분산 환경 기반의 토큰 보안 인증·인가 로직 설계
  - 4개국 분산 DB 아키텍처 환경에서 발생하는 지연 결함을 동시성 비동기 병렬 구조 및 고유 인덱스 생성으로 리팩토링하여 응답 속도 획기적 단축
  - 충전 및 환불 프로세스에 따른 플랫폼 간 실시간 금융 데이터 연동 처리 및 Flutter 기반의 단계별 인증 화면 구현

---

### 🎮 [개소릴레이](https://github.com/gaesorelay/frontend) — 실시간 문장 이어가기 게임 플랫폼
- **프로젝트 정보:** 사용자들이 실시간으로 자유롭게 문장을 이어가며 하나의 창의적인 이야기를 완성하는 텍스트 기반 웹 게임
- **기술 스택:** Nest.js, Redis, Docker, Nginx, React, TypeScript
- **주요 역할 (Frontend):**
  - 아이디어 구체화 단계의 게임 서비스 기획 및 와이어프레임 컴포넌트 구조 설계
  - Framer Motion 및 CSS Keyframes 애니메이션을 활용해 게임의 몰입감을 극대화하는 인터랙션 UI 개발
  - 웹 오디오 사운드 아키텍처 및 공통 플레이어 모듈 개발, 컴포넌트 모듈화를 통한 데이터 흐름 최적화

---

### 🎤 [weverse+ egg](https://github.com/hyundingi/JavaProject_weeg) — 팬덤 활동 결합형 아이돌 육성 시뮬레이션
- **프로젝트 정보:** 기존 글로벌 팬덤 플랫폼에 육성 시뮬레이션 요소를 도입하여 팬들의 경제적 손실을 보완하고 다채로운 팬 활동을 지원하는 웹 서비스
- **기술 스택:** Spring Framework, Oracle DB, Apache Tomcat, HTML/CSS, JavaScript, jQuery, Ajax
- **주요 역할 (Full-Stack):**
  - 카카오 로그인 API 연동 및 JavaScript 정규식을 통한 보안성 높은 회원가입 비밀번호 유효성 검사 로직 구현
  - 카카오페이 API를 접목한 인게임 결제(Jelly Shop) 시스템 및 결제 완료 시 실시간 보유 자화 정합성 업데이트 구현
  - Java Stream API 기반의 캐릭터 인기도 및 매력도 내림차순 연산을 통한 실시간 인게임 랭킹 시스템 구축
  - 메인 페이지 및 인게임 탭 내 이벤트 배너 자동 슬라이드, 무한 스크롤 애니메이션 프론트엔드 최적화 구현
  - 관리자 관점의 편리성을 고려한 이벤트/공지사항 CRUD 인터페이스 및 상태 제어 토글 시스템, 멀티미디어 통합 관리 DB 설계

---

### 📝 [Bon.D](https://github.com/hyundingi) — AI 감정 분석 기반 가족 공유형 일기장
- **프로젝트 정보:** 멀리 떨어져 있거나 소통이 서툰 가족들이 일기를 쓰고 AI 감정 분석 결과를 시각적으로 공유하며 소통하는 정서 중심 커뮤니케이션 플랫폼
- **기술 스택:** Django, Oracle DB, HTML/CSS, JavaScript, jQuery, Ajax
- **주요 역할 (Full-Stack):**
  - Google API를 통해 분석된 원시 텍스트(txt)에서 정규표현식(re) 패턴 매칭을 통해 행복도 점수와 다이어리 식별자를 정밀 추출하여 DB 구조에 적재하는 파이프라인 구현
  - 추출된 유저별 감정 점수 통계를 바탕으로 Chart.js 라이브러리를 연동하여 일별·주별 가족 감정 동향 그래프 시각화 구현
  - 사용자 소통 활성화를 위한 리액션 통계(댓글/좋아요 최다 유저) 및 최근 4개월간의 활동도 분석 대시보드 화면 개발
  - 개인 정보 수정, 비밀번호 일치 검증 팝업 및 관리자 연동형 고객센터(공지사항, 자주 묻는 질문, 1:1 문의 제어 및 답변 처리) 백엔드 기능 전반 개발
<br>

## 📰 Log & Algorithm

<table>
  <tr>
    <td width="60%" valign="top">
      <h3>✍️ Latest Blog Posts (Velog)</h3>
      <br>
      <ul>
      <!-- BLOG-POST-LIST:START --><li><a href='https://velog.io/@hyunding/Spring-Boot-Strategy-Factory-Pattern-%EA%B5%AC%ED%98%84%ED%95%98%EA%B8%B0'>[Spring Boot] Strategy + Factory Pattern 구현하기</a></li><li><a href='https://velog.io/@hyunding/Frontend-React-TS-Vue-%EB%B0%96%EC%97%90-%EB%AA%A8%EB%A5%B4%EB%8A%94%EB%8D%B0%EC%9A%94'>[Frontend] React? TS? Vue 밖에 모르는데요?</a></li><li><a href='https://velog.io/@hyunding/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98-%EC%B1%8C%EB%A6%B0%EC%A7%80-%EC%9E%91%EC%8B%AC%ED%81%B0%EC%9D%BC-2%EC%9D%BC%EC%B0%A8-%EC%8A%A4%ED%83%9D%EC%9D%84-%EC%82%AC%EC%9A%A9%ED%95%98%EC%97%AC-%ED%81%90-%EA%B5%AC%ED%98%84'>[알고리즘 챌린지] 작심큰일 2일차 - 스택을 사용하여 큐 구현</a></li><li><a href='https://velog.io/@hyunding/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98-%EC%B1%8C%EB%A6%B0%EC%A7%80-%EC%9E%91%EC%8B%AC%ED%81%B0%EC%9D%BC-2%EC%9D%BC%EC%B0%A8-%EB%B0%B1%EC%A4%8010820-%EB%AC%B8%EC%9E%90%EC%97%B4-%EB%B6%84%EC%84%9D'>[알고리즘 챌린지] 작심큰일 2일차 - 백준/10820 문자열 분석</a></li><li><a href='https://velog.io/@hyunding/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98-%EC%B1%8C%EB%A6%B0%EC%A7%80-%EC%9E%91%EC%8B%AC%ED%81%B0%EC%9D%BC-1%EC%9D%BC%EC%B0%A8-%EB%B0%B1%EC%A4%801032-%EB%AA%85%EB%A0%B9-%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8'>[알고리즘 챌린지] 작심큰일 1일차 - 백준/1032 명령 프롬프트</a></li><!-- BLOG-POST-LIST:END -->
      </ul>
    </td>
    <td width="40%" valign="top" align="center">
      <h3>💻 Algorithm </h3>
      <br>
      <a href="https://solved.ac/qoswl0723">
        <img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=qoswl0723" alt="Solved.ac 핸디" />
      </a>
    </td>
  </tr>
</table>

<br>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=A9DFBF&height=100&section=footer&animation=fadeIn" width="100%">
</p>


