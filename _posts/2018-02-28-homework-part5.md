---
title: 성능 교육 진행을 위한 과제 - part 5 (chap 12,13) ()
tags: [assignment]
---

Microsoft의 `[Performance Testing Guidance for Web Applications]` 를 보고 요약하는 과제.

# Part 5 를 읽고 테스트의 계획과 설계에 대해 정리 (word 2 page)

- 테스트를 계획할 때 염두해두어야 할 부분은 어플리케이션 사용 방법 모델링

------

## chap 12 modeling application usage

### overview
- 웹 로드 테스트의 가장 공통되는 목적은
- 를 위해서, 테스트 워크로드는
- 생성하기 위해서, 반드시 이해해야 한다.
-

-


- 비현실적인 워크로드 모델을 시뮬레이션하면 성능 테스트를 수행 할 때 가치 있는 정보를 제공할 수 있지만 실제 작업 부하 모델을 시뮬레이션 할 때만 프로덕션 환경에서 성능에 대한 정확한 예측이나 성능 최적화의 우선 순위를 지정할 수 있습니다.


- 성능 테스트를 만들 때, 테스트 조건은 프로덕션 사용방법이나 미래의 비즈니스 영업량과 비슷해야 한다.
- 정확하고 예측적인 테스트 결과를 위해서, 유저 행동은 반드시 유저가 웹 사이트와 상호작용을 어떻게 하는지를 나타낼 수 있는 요소들을 기반으로 한 소비자 세션 모델링을 포함해야 한다.

### identify the objectives


### determine key usage scenarios


### determine navigation paths for key scenarios


### determine individual user data and variances


### determine the relative distribution of scenarios


### identify target load levels


### prepare to implement the model


### summary



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
- 워크로드 특성화가 정확한 결과를 생성하려면 테스트 및 테스트 스크립트에 대한 실제 사용자 지연을 설계하는 프로세스가 중요합니다. 프로덕션 환경에서 응용 프로그램의 성능 특성 또는 향후 예상되는 비즈니스 볼륨을 이해하는 데 직접 적용 할 수있는 성능 테스트를 위해 테스트 된 작업 부하는 사용자 지연 패턴을 복제하여 현실을 나타낼 수 있어야합니다.

- 현실을 합리적으로 정확하게 표현하려면 대표적인 사용자 교차 영역과 마찬가지로 개별 사용자 데이터 및 사용자 포기를 고려하여 가변성 및 임의성을 가진 사용자 지연을 모델링해야합니다.
