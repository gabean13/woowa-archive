# 우아한테크코스 7기 백엔드 학습 정리
> [우아한테크코스](https://www.woowacourse.io/intro)는 우아한형제들에서 운영하는 개발자 교육 프로그램입니다.

<br>

## 1️⃣ Level 1: Java
> 25.02 ~ 25.04

**자바 콘솔 애플리케이션 개발**을 통해 기본 문법 → 테스트 → 리팩터링 → 객체지향 → DB을 학습했습니다.

| 프로젝트 | 키워드 | 1단계 | 2단계 | 
| :---: | :---:  | :---: | :---: |
| 로또 | 단위테스트 | [로또 구현](https://github.com/woowacourse/java-lotto/pull/519) | [로또 리팩터링](https://github.com/woowacourse/java-lotto/pull/648) |
| 출석 체크 | TDD | [출석 구현](https://github.com/woowacourse/java-attendance/pull/16) | [출석 다시 구현하기](https://github.com/woowacourse/java-attendance/pull/99) |
| 블랙잭 | CleanCode | [블랙잭 구현](https://github.com/woowacourse/java-blackjack/pull/812) | [블랙잭 베팅](https://github.com/woowacourse/java-blackjack/pull/891) |
| 장기 | OOP, DB | [장기 구현1](https://github.com/woowacourse/java-janggi/pull/18) | [장기 구현2](https://github.com/woowacourse/java-janggi/pull/121) |

<br>

## 2️⃣ Level 2: SpringBot
> 25.04 ~ 25.06

**SpringBoot로 방탈출 웹 서비스**를 개발하며 주어진 요구사항에 맞춰 기능을 추가, 변경하고 리팩터링하며 운영하는 경험을 했습니다.

| 프로젝트 | 키워드 | 1단계 | 2단계 | 
| :---: | :---: | :---: | :---: |
| 방탈출 예약 관리 | 레이어드 아키텍쳐, DI | [1-3단계](https://github.com/woowacourse/spring-roomescape-admin/pull/240)| [4-9단계](https://github.com/woowacourse/spring-roomescape-admin/pull/313) |
| 방탈출 사용자 예약 | HTTP, 인증/인가 | [1-3단계](https://github.com/woowacourse/spring-roomescape-member/pull/184)| [4-6단계](https://github.com/woowacourse/spring-roomescape-member/pull/311) |
| 방탈출 예약 대기 | JPA, 연관관계 | [1-2단계](https://github.com/woowacourse/spring-roomescape-waiting/pull/205)| [3-4단계](https://github.com/woowacourse/spring-roomescape-waiting/pull/317) |
| 방탈출 결제/배포 | 외부 API, AWS | [1단계](https://github.com/woowacourse/spring-roomescape-payment/pull/201)| [2-4단계](https://github.com/woowacourse/spring-roomescape-payment/pull/321) |

<br>

## 3️⃣ Level 3: 팀 프로젝트 개발
> 25.07 ~ 25.09

**히어릿: IT 팟캐스트 서비스**를 개발했습니다.
2주마다 데모데이 요구사항을 지켜나갔습니다.

| 차수 | 요구사항 | 증빙자료 |
| :--- | :--- | :--- |
| **1차** | 프로젝트 셋팅(local) | [Github](https://github.com/woowacourse-teams/2025-hEARit) |
| | 개발(코드 컨벤션 등) 문서 만들기 | [컨벤션 문서](https://github.com/woowacourse-teams/2025-hEARit/wiki/%5BBE%5D-%EC%BD%94%EB%93%9C-%EC%BB%A8%EB%B2%A4%EC%85%98) |
| | 기술 스택 선택 및 이유 정리 | [기술스택 정리](https://github.com/woowacourse-teams/2025-hEARit/wiki/%5BBE%5D-%EA%B8%B0%EC%88%A0-%EC%8A%A4%ED%83%9D)|
| **2차** | 개발(dev) 환경 구축 | dev 환경 구축 완료 |
| | 개발 서버에 서비스 띄우기 | [개발 서버 API문서](https://hearit-dev.o-r.kr/swagger-ui/index.html#/) |
| | CI와 쉘 스크립트 등을 활용한 배포 자동화 | [CI/CD 흐름](https://github.com/woowacourse-teams/2025-hEARit/wiki/%5BBE%5D-%EA%B0%9C%EB%B0%9C-%ED%99%98%EA%B2%BD#3-cicd)|
| **3차** | 서비스 운영 환경 구축 | prod 환경 구축 완료 |
| | 로깅 프레임워크 적용 | [로깅 적용 PR](https://github.com/woowacourse-teams/2025-hEARit/pull/230)|
| | API 문서 작성 | [API 문서](https://hearit.o-r.kr/swagger-ui/index.html#/)|
| |(로그, 매트릭) 모니터링 대시보드 구성 | [모니터링 환경](https://github.com/woowacourse-teams/2025-hEARit/wiki/%5BBE%5D-%EC%8B%9C%EC%8A%A4%ED%85%9C-%EC%84%A4%EA%B3%84-%EB%AC%B8%EC%84%9C#%EB%AA%A8%EB%8B%88%ED%84%B0%EB%A7%81-%EC%8B%9C%EC%8A%A4%ED%85%9C-%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98) |
| **4차** | 프로덕션 서버에 서비스 띄우기 | [시스템 설계 문서](https://github.com/woowacourse-teams/2025-hEARit/wiki/%5BBE%5D-%EC%8B%9C%EC%8A%A4%ED%85%9C-%EC%84%A4%EA%B3%84-%EB%AC%B8%EC%84%9C) |
| | 실 서버 도메인 연결, HTTPS 적용 | https 적용 완료 |
| | DB 데이터를 drop할 수 없음 | [DB 권한 & 백업 & 복구](https://glistening-eclipse-58b.notion.site/DB-256d39b9c3c380cd9f8ded97bf9fb222?source=copy_link) |

<br>

## 4️⃣ Level 4: 팀 프로젝트 운영 & 고도화, SpringBoot 직접 구현
> 25.10 ~ 25.11

서비스를 배포하고, 실제로 운영하면서 서비스를 고도화했습니다.
| 차수 | 요구사항 | 증빙자료 |
| :--- | :--- | :--- |
| **5차** | 핵심 테이블에(핵심 기능에서 read/write 되는 테이블) 대량의 데이터를 쌓고 성능을 개선 | 실제 데이터베이스에 50만/100만 건의 데이터를 넣고 실험계획 수행 ( MySQL .csv 파일 bulkInsert ) |
| | 서비스에서 사용하는 쿼리를 정리하고, 각 쿼리에서 사용하는 인덱스 설정| [히어릿 쿼리 문서화 및 인덱스 전략](https://glistening-eclipse-58b.notion.site/272d39b9c3c3800d9784ce29fd507033) |
| **6차** | 인스턴스 한 대 기준으로 핵심기능에 목표 TPS를 정하고, 안정적으로 서비스 될 수 있게 값을 설정하고 이유 공유| [서버 부하 테스트: 목표 TPS 설정 및 개선 과정 문서](https://github.com/woowacourse-teams/2025-hEARit/discussions/695) |
| | 무중단 배포 구현 | [무중단 배포 설계](https://github.com/woowacourse-teams/2025-hEARit/discussions/697) |
| | 현재 아키텍처에서 사용자가 늘어났을 때 문제가 될 수 있는 부분 설명, 개선 방법 작성| [사용자 증가에 따른 인프라 설계 및 운영 전략](https://github.com/woowacourse-teams/2025-hEARit/discussions/703) |

<br>

SpringBoot의 tomcat, dispatcher servlet, jdbcTemplate을 직접 구현하며 스프링 서버의 로드 과정과 HTTP 요청이 Servlet Container에서 처리되는 흐름, spring이 DB왜 통신하는 방법을 이해했습니다.
| 프로젝트 | 1단계 | 2단계 | 3단계 | 4단계 |  
| :--- | :---: | :---: | :---: | :---: |
| Tomcat 구현하기 | [HTTP 서버](https://github.com/woowacourse/java-http/pull/822) | [로그인 구현하기](https://github.com/woowacourse/java-http/pull/911) | [리팩터링](https://github.com/woowacourse/java-http/pull/968) | [동시성 확장하기](https://github.com/woowacourse/java-http/pull/1016) |
| @MVC 구현하기 | [@MVC 프레임워크](https://github.com/woowacourse/java-mvc/pull/892)| [점진적인리팩터링](https://github.com/woowacourse/java-mvc/pull/978) | [JsonView 구현하기](https://github.com/woowacourse/java-mvc/pull/1019) | |
| JDBC 라이브러리 구현하기 | [JDBC 라이브러리](https://github.com/woowacourse/java-jdbc/pull/1015) | [리팩터링](https://github.com/woowacourse/java-jdbc/pull/1083) | [Transaction 적용](https://github.com/woowacourse/java-jdbc/pull/1140) | [Trasaction synchroziaztion 적용](https://github.com/woowacourse/java-jdbc/pull/1217) |

<br>

## 🧑‍🏫 스터디

| 스터디 | 기간 | 자료 |
| :--- | :---: | :---: |
| 자수마스터(이펙티브자바) | 25.03 ~ 25.04 |[notion](https://educated-icebreaker-525.notion.site/1c04d1b9773a8044abcbe3aee0fb8c0d)|
| 네트워크(퓨터 네트워킹 하향식 접근) | 25.04 ~ 25.07 |[notion](https://educated-icebreaker-525.notion.site/1d94d1b9773a80fcba21d536f57bec89?pvs=73)|
| 면접 CS 스터디 | 25.07 ~ 25.11 | [notion](https://educated-icebreaker-525.notion.site/CS-2374d1b9773a80af8a3efd38bfd4b228)|

<br>

## 📝 글쓰기

| 레벨 | 제목 |
| :---: | :--- |
|Level1| [유강스 회고 : 불편해지기](https://github.com/gabean13/woowa-writing/blob/main/level1/%EC%9C%A0%EA%B0%95%EC%8A%A4%ED%9A%8C%EA%B3%A0.md)|
|Level2| [4개월 동안 우테코를 하면서 전과 달라진 점](https://github.com/gabean13/woowa-writing/blob/main/level2/level2%EA%B8%80%EC%93%B0%EA%B8%B0.md)|
|Level3| [솔직한 인터뷰 with 히어릿 팀](https://github.com/woowacourse-teams/2025-hEARit/wiki/%EC%86%94%EC%A7%81%ED%95%9C-%EC%9D%B8%ED%84%B0%EB%B7%B0-with-%ED%9E%88%EC%96%B4%EB%A6%BF-%ED%8C%80)|
|Level4| [Technical Writing: 스트리밍 어떻게 했나요? (그냥 되던데요..)](https://github.com/gabean13/woowa-writing/blob/main/level4/TechnicalWriting.md)|
|우테코 수료| []()|

<br>

## 🎥 테코톡
[[10분 테코톡] 가콩의 Spring Bean은 왜](https://www.youtube.com/watch?si=vKUyZt2wGs_U-hkN&v=JHuk4ouuvs4&feature=youtu.be)

스프링을 개발할 때 당연하게 사용하는 @Controller, @Bean, @Component가 왜 등장하게 되었는지, 없으면 어떻게 되는지를 직접 실험해보며 배운 점을 공유하고자 발표를 진행하였습니다.

<br>
