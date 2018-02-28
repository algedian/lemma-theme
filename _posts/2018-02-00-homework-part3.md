---
title: 성능 교육 진행을 위한 과제 - part 1 (chap 1, 2)
tags: [assignment]
---

Microsoft의 `[Performance Testing Guidance for Web Applications]` 를 보고 요약하는 과제.

# Part 3 를 읽고 테스트 환경에 대해 정리 (word 1 page)
- 이 파트는 테스트 환경에 대해서 확인하는 부분, 그래서 어떤 방법으로 테스트 환경을 확인하는 지에 대해서 나와있다. 그래서 테스트 환경이 뭐니? 에 대한 질문이다.
- 테스트 환경이란?
  - 테스트가 이루어지는 곳이 테스트 환경이겠지.
  - 

### approach for evaluating the system
- 시스템을 평가하는 활동들
  - 시스템에서 유저가 보는 기능들 확인하기
  - 배치 작업과 같이 유저가 시작하지 않는 프로세스나 기능들 확인하기
  - 예상되는 유저 활동 결정하기
  - 예상되는 것 외에 잠재적인 유저 활동의 합리적인 이해 개발하기
  - 테스트와 프로덕션 아키텍처의 정확한 모델 개발하기
  - 실제 유저 환경의 합리적인 모델 개발하기
  - 같은 아키텍처를 사용하는 다른 프로세스나 시스템들 확인하기
- 위와 같은 활동들은 다음과 같은 과정들을 달성할 수 있다.
  - capture system functions and/or business processes
  - capture user activites
  - capture the logical and physical architecture

### 시스템 기능과 비즈니스 과정 포착하기 capture system functions and/or business processes

- 고려사항
### 사용자 활동 포착하기 capture user activites

- 고려사항
### 논리 아키텍처와 물리 아키텍처 포착하기 capture the logical and physical architecture

- 고려사항
### summary
- 시스템 평가는 성능 테스트 작업 전반적으로 진행되는 작업이지만, 성능 테스트 초반에 많은 가치를 준다.
- 시스템 평가 작업이 일어나는 동안에, 위의 3가지 같은 정보를 모으면, 프로젝트의 특정 요구를 만족하기 때문에? 성능 테스트를 가이드하는데에 도움을 준다.
- 이러한 정보들은 성능 목표와 요구사항을 정의하고, 워크로드를 특징화하고, 성능 테스트 전략과 계획을 만들고, 프로젝트와 시스템 위험을 평가하는데에 도움을 준다.