---
title: 성능 교육 진행을 위한 과제 - part 5 (chap 12,13)
tags: [assignment]
---

Microsoft의 `[Performance Testing Guidance for Web Applications]` 를 보고 요약하는 과제.

# Part 5 를 읽고 테스트의 계획과 디자인에 대해 정리 (word 2 page)

- 테스트를 계획할 때 염두해두어야 할 부분은 어플리케이션 사용 방법 모델링

------

## chap 12 modeling application usage

### overview
- 웹 로드 테스트의 가장 공통되는 목적은
- 를 위해서, 테스트 워크로드는
- 생성하기 위해서, 반드시 이해해야 한다.
- 


- 웹 사이트 테스트는 예술보다 과학이다.
- 


- 비현실적인 워크로드 모델을 시뮬레이션하면 성능 테스트를 수행 할 때 가치 있는 정보를 제공할 수 있지만 실제 작업 부하 모델을 시뮬레이션 할 때만 프로덕션 환경에서 성능에 대한 정확한 예측이나 성능 최적화의 우선 순위를 지정할 수 있습니다.

### identify the objectives


### determine key usage scenarios


### determine navigation paths for key scenarios


### determine individual user data and variances


### determine the relative distribution of scenarios


### identify target load levels


### perpare to implement the model


### summary
- 성능 테스트를 만들 때, 테스트 조건은 프로덕션 사용방법이나 미래의 비즈니스 영업량과 비슷해야 한다.
- 정확하고 예측적인 테스트 결과를 위해서, 유저 행동은 반드시 유저가 웹 사이트와 상호작용을 어떻게 하는지를 나타낼 수 있는 요소들을 기반으로 한 소비자 세션 모델링을 포함해야 한다. 


## chap 13 determining individual user data and variances

### overview
- 이 챕터는 현실적인 유저 딜레이, 유저 데이터, 유저 포기?를 결정하는 프로세스에 관한 챕터
- 성능 테스트가 결과를 낳기 위해서는, 워크로드는 반드시 표현해야 한다.
- 합리적이고 정확한 표현을 위해서는, 반드시 유저들을 모델링 해야한다. ?

### user delays


### consequences of improperly modeling user delays


### determining individual user data


### user abandonment


### summary
- 


- asdf