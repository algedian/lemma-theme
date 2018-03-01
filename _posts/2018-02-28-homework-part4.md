---
title: 성능 교육 진행을 위한 과제 - part 4 (chap 9,10) (xx)
tags: [assignment]
---

Microsoft의 `[Performance Testing Guidance for Web Applications]` 를 보고 요약하는 과제.

# Part 4 를 읽고 성능테스트의 목적에 대해 정리 (word 2 page) ?????

- 성능 테스트의 목적
  - ..
- 성능 테스트 목적을 정하고 기록하는 것은 프로젝트가 마일스톤을 통해 발전함에 따라 팀과 의사소통하여 이러한 목표를 설정하고 업데이트하는 것을 포함한다.

## ch 9 determining performance testing

### overview
- 성능 테스트의 목적을 정하는 키는 개선했을 때에 바뀌는 점, 잠재되어 있는 위험, 그리고 기회를 확인하는 것이다.

### approach for determining performance testing objectives


### determine the objective of performance testing
- 전체적인 목표를 정한다
- 프로젝트 계획을 리뷰한다
- 아키텍처를 리뷰한다
- 팀 멤버들에게 물어본다


### capture or estimate resource usage targets and thresholds


### capture or estimate resource budgets


### identify metrics


### communicate results


### stay aware of changing objectives, targets, and budgets


### summary
- 성능 테스트 목표를 결정하고 기록하는 것은 프로젝트가 이정표를 진행함에 따라 팀과 의사 소통하여 이러한 목표를 수립하고 업데이트하는 것입니다. 각 팀원들과 시간을 계획하는 것이 항상 쉬운 것은 아니지만, 특히 프로젝트 팀이 경영진의 이해 관계자, 분석가 및 심지어 대 표적 인 사용자를 포함한다고 생각할 때, 그들은 귀중한 성과 테스트의 수립에 도움이되는 정보 공유에 대해 일반적으로 수용적입니다. 목표. 이러한 목표에는 비즈니스 관련 메트릭 제공,로드시 자원 활용 데이터 확보, 응용 프로그램 서버 조정에 도움이되는 특정로드 생성 또는 각 웹 페이지에서 요청한 오브젝트 수 보고서 제공이 포함될 수 있습니다.



## ch 10 quantifying end-user response time goals

### overview
- 궁극적으로 최종 사용자 응답 시간 메트릭에는 문제가 있습니다. 즉, 성능 저하로 인해 좌절하는 응용 프로그램 사용자의 비율입니다. 응용 프로그램 사용자는 성능 테스트 결과의 값, 화면이 "너무 오래"에 대한 사용자의 임계 값을 초과하여 표시되는 데 걸리는 시간 또는 처리량 값을 알지 못하거나 신경 쓰지 않습니다. 그러나 사용자는 응용 프로그램의 속도가 느려지는지 여부를 확인하고 해당 응용 프로그램의 기분에서부터 응용 프로그램에 대한 이전 경험에 이르기까지 모든 작업을 기반으로 할 수 있습니다. 이 장에서는 이러한 사용자 인식을 테스트 가능한 숫자로 변환하는 방법에 대해 설명합니다.

- 사용자가 성능면에서 "수용 가능"하다고 판단하는 것은 어려울 수 있으며, 선호도는 단기간에 크게 변화 될 수 있습니다. 소프트웨어 개발 회사는 시간과 비용이 들기 때문에 대표적인 사용자 그룹과 정기적으로 사용성 연구를 수행하기를 원하지 않습니다. 대부분의 경우, 이들 회사는 원할 경우에도 유용성 연구를 수행하기위한 자원이나 교육을 제공하지 않습니다.

- Performance and Reliability (WOPR, http://www.performance-workshop.org/ ) 워크샵과 같은 피어 워크샵에서 공유되는 최고의 성능 테스터의 사용자 경험 보고서 는 팀의 애플리케이션 성능 목표 및 요구 사항을 간단히 말하면 팀이 논리적, 물적, 경영 적 과제를 극복하고 성공적인 애플리케이션을 성취 할 수있는 방법을 찾아야합니다. 이러한 동일한 성능 테스터는 정량화 된 목표 및 요구 사항을 충족시키고 종종 무시한다는보고합니다. 요구 사항과 목표가 참고 사항이되지 않는 한 목표와 요구 사항이 만족스럽지 않은 사용자와 관련이있는 경우는 거의 없습니다.

### approach for quantifying end-user response time


### determine application functionality and usage


### verbalize and capture performance requirements and goals


### quantify performance requirements and goals


### record performance requirements and goals


### summary
- 응답 시간 목표를 정량화하는 것은 사용자의 응용 프로그램 성능에 대한 인식을 표현하는 것과 밀접하게 관련됩니다. 대부분의 경우 응용 프로그램 사용자는 화면에 데이터를 표시하는 데 걸리는 시간, 응용 프로그램 처리량, 데이터베이스에서 지원해야하는 초당 트랜잭션 수를 명확하게 나타낼 수 없습니다. 그러나 사용자는 이전 경험, 작업의 중요성 및 기대치 설정 방법과 같은 여러 요소의 결과 인 노출 수를 기준으로 응용 프로그램의 성능 동작을 확인합니다.


## ch 11 consolidating various types of performance acceptance criteria

### overview
- 성능 요구 사항 및 테스트 목표는 일반적으로 시스템 사용자의 시각, 시스템의 비즈니스 소유자 및 프로젝트 팀의 다섯 가지 출처뿐만 아니라 규정 준수 기대치 및 기술적 고려 사항에서 파생됩니다. 이 장에서는 이러한 소스에서 수집 한 정보를 검증 가능하고 보완적인 성능 요구 사항 및 테스트 목적의 단일 세트로 혼합 및 통합하는 방법을 보여줍니다.

- 특정 관점에서 시스템에 대해 원하는 성능 특성을 결정하는 것은 해당 시스템에 대한 전반적인 성능 허용 기준을 결정하는 첫 번째 부분 일뿐입니다. 제한된 관점에서 원하는 성능 특성을 검토 한 후에는 이러한 특성을 서로 비교해야합니다. 예를 들어, 최종 사용자는 모든 트랜잭션에 대해 1 초 미만의 응답 시간을 원할 수 있습니다. 비즈니스 이해 관계자는 시스템이 수백만 명의 사용자를 지원하기를 원할 수 있습니다. 컴플라이언스 기준은 엄격한 보안 정책을 요구할 수 있습니다.

- 개별적으로 이러한 특성은 달성 될 수 있지만 시간, 기술 및 / 또는 예산 제약으로 인해 집합 적으로 불가능할 수 있습니다. 이러한 바람직한 특성을 달성 할 수있는 방법을 찾는 것은 팀 전반에 걸친 도전 과제를 제시합니다. 테스트를 통해 충돌이 명백해진 후에는 사전 대응 적으로 대응해야합니다.

### approach for consolidating acceptance criteria


### investigate end-user requirements


### collect business requirements


### determine technical requirements


### research standards, compliance, adn contracts


### establish performance-testing objectives


### compare and consolidate performance characteristics


### review and update the performance plan


### summary
- 성능 요구 사항 및 테스트 목적은 일반적으로 시스템 사용자, 비즈니스 소유자 및 프로젝트 팀의 관점뿐만 아니라 규정 준수 기대치 및 기술적 고려 사항으로부터 도출됩니다.

- 시스템 수용 기준의 완성도에 대한 확신을 갖기 위해서는 이러한 모든 다른 관점에서 수집 된 정보를 기반으로해야하며, 이는 검증 가능한 보완 성능 요구 사항 및 테스트 목표의 단일 세트가되어야합니다.

- 가장 중요한 성능 특성은 응용 프로그램 사용자가 성능 저하로 좌절하지 않아야한다는 것입니다.
