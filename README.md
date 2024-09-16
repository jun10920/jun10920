![header](https://capsule-render.vercel.app/api?type=waving&color=0:0b0f4d,100:1c1c86&height=200&section=header&text=Welcome!%20Bamlatte's%20Github&fontColor=FFD700&fontSize=60&fontAlignY=35&desc=Backend%20Developer&descAlignY=65&descAlign=60&animation=fadeIn&speed=3)

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fbamlatte&count_bg=%23002f6c&title_bg=%23002f6c&icon=&icon_color=%23E7E7E7&title=VISIT&edge_flat=false)](https://github.com/bamlatte)
[![Gmail Badge](https://img.shields.io/badge/Gmail-D14836?style=flat&logo=Gmail&logoColor=white)](mailto:jun109209@gmail.com)
[![Tech Blog Badge](https://img.shields.io/badge/Tech%20Blog-555263?style=flat&logoColor=white)](https://jun10920.tistory.com/)
[![Threads Badge](https://img.shields.io/badge/Threads-000000?style=flat&logo=Threads&logoColor=white)](https://www.threads.net/@jun_2.6)
[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0a66c2?style=flat&logo=LinkedIn&logoColor=white)](https://www.linkedin.com/in/jun10920)

## 👋 About Me

안녕하세요! 저는 백엔드 개발자로서 **비즈니스 가치**와 **성능 최적화**를 동시에 추구하는 개발자입니다.  
저는 **대규모 트래픽 처리**와 **실시간 데이터 처리**문제를 해결하는 것에 열정이 있습니다.  
복잡한 시스템을 깔끔하게 최적화하고, 동시에 **유저 경험**을 개선하는 것을 목표로 하고 있습니다.

> **"성능은 단지 숫자가 아니라, 사용자와의 첫 만남에서의 인상이다."**  
> 제가 가장 중요하게 여기는 철학 중 하나입니다.

- 🏃‍♂️ **현재**: 백엔드 개발에 집중하며, 실시간 처리와 최적화에 도전하고 있습니다.
- 💬 **성능 테스트**: 단순히 코드를 짜는 것이 아니라, **어떻게 하면 더 나은 성능을 낼 수 있을지** 고민합니다.
- 🚀 **미래 목표**: 대규모 분산 시스템 설계 및 오픈소스 프로젝트의 기여를 지속적으로 확장하고 싶습니다.

---

## 🔧 What I’m Working On

## 🚀 Projects

### Now, Here: **이벤트 기반 실시간 매칭 플랫폼**
> **2024.07 ~ 운영중**  
> **Stack**: Spring Boot, PostgreSQL, JPA(Hibernate), Caffeine, GCP, Swagger  

"Now, Here"는 이벤트에 참여한 사용자들을 실시간으로 매칭해주는 플랫폼입니다.<br>
이 프로젝트에서 **대규모 트래픽 처리**와 **DB 성능 최적화**를 주도하며, 실시간 서비스의 효율성과 안정성을 높이는 데 집중했습니다.

> **"성능은 단순한 속도 측정이 아니라, 사용자 경험을 좌우하는 핵심 요소다."**

### 주요 기여
- **실시간 매칭 알고리즘 최적화**: 동적 가중치 조정과 DB 분석 자동화를 통해 고객 중심의 개발을 실현했습니다.
- **대규모 트래픽 대응 아키텍처 설계**:
  - **Master-Slave DB 아키텍처**를 설계해 로드밸런싱을 구현하고, **고가용성**을 확보했습니다.
  - **Event ID 기반 파티셔닝**을 적용하여 대용량 데이터를 효율적으로 처리하고, 트랜잭션 처리 속도를 개선했습니다.
- **DB 성능 최적화**:
  - 응답 시간을 7.5초에서 4.4초로 **41% 개선**.
  - **Caffeine 캐시**를 도입하여 배너 매칭 목록 조회 시간을 **88% 단축**.
  - **복합 인덱스 설계**를 통해 매칭 페이지 응답 시간을 **43% 개선**.
  - **HikariCP 연결 풀 최적화**로 전체 시스템 성능을 **39% 향상**.
- **성능 테스트 및 시스템 안정성 검증**:
  - **500명 사용자, 25만 매칭 데이터** 처리 시나리오 기반으로 **대규모 동시 접속 시뮬레이션**을 수행해 시스템의 안정성을 검증했습니다.
  - **3단계 최적화**: HikariCP 설정 → Caffeine 캐싱 → 인덱싱 및 트랜잭션 최적화를 통해 지속적인 성능 개선을 달성했습니다.

이 프로젝트를 통해 **대규모 트래픽 처리와 성능 최적화**라는 백엔드의 핵심 과제를 다루며 <br>
안정적인 시스템 설계를 위해 깊이 있는 기술적 경험을 쌓을 수 있었습니다.

🔗 [프로젝트 링크](https://github.com/now-here-5/.github)

---

### TrueEcho
> **2024.01 ~ 2024.07**  
> **Stack**: Java, Spring Boot, MariaDB, Firebase  

SNS 플랫폼에서 성능을 극대화하고, **JPA N+1 문제**와 **엔티티 최적화**로 **66%~97% 성능 개선**을 달성했습니다.  
- **FOF 추천 알고리즘** 설계 및 **CI/CD 자동화** 구축.
- **Firebase Cloud Messaging**으로 사용자 맞춤형 알림 구현.

🔗 [프로젝트 링크](https://github.com/TrueEchoProject/TrueEcho_Main)

---

### 고양시 내 최적의 고깃집 위치 분석 프로젝트
> **2023.12**  
> **Stack**: Python, Jupyter Notebook, pandas, numpy

고양시 내에서 고깃집을 창업할 최적의 위치를 데이터 분석을 통해 도출한 프로젝트입니다.  
- 금융 데이터를 전처리하고, **다중 회귀 분석**을 통해 **비즈니스 인사이트** 도출.  
- **변수 선택법**을 적용해 AIC가 낮은 요인을 찾아내고, 매출 예측 모델을 최적화.

🔗 [프로젝트 링크](https://github.com/jun10920/Goyang_BBQ_Analysis)

---

## 💡 What I’ve Learned

- **성능 최적화**: 단순히 속도를 높이는 것이 아니라, **어떤 부분을 개선해야 진짜 성능을 개선할 수 있는지**를 파악하는 것이 중요합니다.  
  - ex) HikariCP, Caffeine 캐시, DB 인덱싱을 통해 응답 시간을 7.5초에서 4.4초로 단축!

- **협업과 커뮤니케이션**: 백엔드 개발은 팀워크 없이는 완성되지 않습니다. 오픈소스 기여와 팀 프로젝트에서 **효과적인 협업**을 경험하고 있습니다.

---

## 🌱 Currently Exploring

- **실시간 데이터 처리**와 **대규모 트래픽 대응**에 관한 최신 기술.
- **오픈소스 프로젝트** 참여 및 기여.
- 데이터 중심의 **AI 시스템** 통합.

---

## 🛠 Tech Stack

### **Backend**  
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-007396?style=for-the-badge&logo=hibernate&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![Caffeine](https://img.shields.io/badge/Caffeine_Cache-1e1e1e?style=for-the-badge&logo=coffeescript&logoColor=white)

### **Frontend**  
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### **DevOps & Tools**  
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)


---

## 🚀 기타 정보

- **항상 새로운 도전을 준비합니다.** 오픈소스 컨트리뷰션에 기여하고, 다양한 성능 최적화 도전 과제를 풀어내는 것이 저의 즐거움입니다.
- 개발 외에도 **웨이트 트레이닝**과 **파워리프팅**으로 몸과 마음을 단련하며, 끊임없는 성장을 추구하고 있습니다.

---

## 📫 Contact Me

- **이메일**: jun109209@gmail.com
- **블로그**: [jun10920.tistory.com](https://jun10920.tistory.com)
- **LinkedIn**: [www.linkedin.com/in/jun10920](https://www.linkedin.com/in/jun10920)

