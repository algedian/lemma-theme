---
title: 성능 교육 진행을 위한 과제 - part 6 (chap 14) ()
tags: [assignment]
---

Microsoft의 `[Performance Testing Guidance for Web Applications]` 를 보고 요약하는 과제.

# Part 6 을 읽고 테스트 실행에 대해 정리 (word 2 page)

## chap 14 test execution

### overview
- 성능 테스트 실행은 테스트 스크립트 개발과 테스트 결과보고 및 분석 사이에 발생하는 활동입니다. 현재 이용할 수있는 성능 테스트 관련 교육의 대부분은이 활동을 테스트를 시작하고 테스트하여 기대 한대로 실행되고 있는지 확인하는 것 이상을 다루고 있습니다. 사실이 작업은 단추를 클릭하고 컴퓨터를 모니터링하는 것보다 훨씬 복잡합니다. 이 장에서는 수많은 실제 프로젝트 경험을 토대로 이러한 복잡성을 다룹니다.

### approach for test execution


### validate the test environment


### validate tests


### run tests


### baseline and benchmark


### archive tests


### summary
- 성능 테스트 실행에는 테스트 환경 / 스크립트의 유효성 검사, 테스트 실행 및 테스트 결과 생성과 같은 활동이 포함됩니다. 또한 성능 특성의 기준선 및 / 또는 벤치 마크를 생성하는 것도 포함 할 수 있습니다.

- 환경이 실제로 프로덕션 환경을 나타내도록 테스트 환경의 유효성을 확인하는 것이 중요합니다.

- 올바른 메트릭이 수집되고 있는지, 그리고 테스트 스크립트 디자인이 작업 부하 특성을 정확하게 시뮬레이션하고 있는지 확인하기 위해 테스트 스크립트의 유효성을 검사합니다.
