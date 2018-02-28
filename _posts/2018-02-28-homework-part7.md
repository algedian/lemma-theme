---
title: 성능 교육 진행을 위한 과제 - part 7 (chap 15,16)
tags: [assignment]
---

Microsoft의 `[Performance Testing Guidance for Web Applications]` 를 보고 요약하는 과제.

# Part 7 을 읽고 테스트 결과 분석에 대해 정리 (word 2 page)

- 테스트 결과 분석에는 수학적인 접근이 가능하다
  - 평균, 퍼센타일, 중앙값, normal value, 표준편차, 균등 분포, 정규 분포, 통계적 유의도, 통계적 동등성, 아웃라이어, 신뢰구간 등

- 테스트 결과를 리포팅할 때에 유의할 사항들은 다음과 같다 (챕터 16내용)

------

## chap 15 key mathematic principles for performance testers

### overview
- 소프트웨어 개발 팀, 개발자, 테스터, 관리자 및 관리자 모두가 업무를 효과적으로 수행하기 위해 수학을 적용하고 통계 데이터를 해석하는 방법을 알고 있어야합니다. 성과 분석 및보고는 특히 수학 집중적입니다. 이 장에서는 성능 테스트에서 가장 일반적으로 사용되는 오용되고 오해 된 수학적 및 통계적 개념을 팀원에게 도움이되는 방식으로 설명합니다.

- 많은 수학적 및 통계적 개념을 이해해야 할 필요성이 있음에도 불구하고 많은 소프트웨어 개발자, 테스터 및 관리자는 수학 및 통계에 강한 배경이 없거나 즐겁지 않습니다. 이는 상당한 허위 진술과 성능 테스트 결과의 오역을 초래합니다. 이 기사에 제공된 정보는이 분야의 공식 교육을 대체하기위한 것이 아니라 성능 테스트를 이해하는 데 유용한 수학 및 통계 작업에 대한 공통 언어 및 상식적인 설명을 제공하기위한 것입니다.

### average


### percentiles


### medians


### normal values


### standard deviations


### uniform distributions


### normal distributions


### statistical significance


### statistical equivalence


### statistical outliers


### confidence intervals


### summary
- 모두가 수학을 적용하고 통계 데이터를 해석하여 업무를 효율적으로 수행하는 방법을 알아야 한다.
- 성능 분석 및 리포팅은 특히 수학-집중적이다.
- 정확한 성능 테스트 분석과 리포팅을 위해서 성능 테스트 안의 수학적인 개념과 통계적인 개념은 중요하다.

## chap 16 performance test reporting fundamentals

### overview
- 관리자와 이해 관계자는 단순히 다양한 테스트의 결과 이상을 필요로합니다. 이러한 결과를 기반으로 결론을 내리고 이러한 결론을 뒷받침하는 데이터를 통합해야합니다. 기술 팀 구성원은 단순한 결과 이상을 필요로합니다. 분석, 비교 및 ​​결과를 얻는 방법에 대한 세부 사항이 필요합니다. 모든 유형의 팀원은 실적 결과에서 얻는 가치를보다 자주 공유합니다. 이 장에서는 다양한보고 및 결과 공유 기술을 사용하고 각 기술이 잘 받아 들여지는 모범 시나리오를 학습하여 성능 테스트 결과 및 데이터의 모든 소비자의 요구를 충족시키는 방법을 학습합니다.

### principles of effective reporting
- 리포트는 빨리, 자주
- 리포트는 시각화해서
- 리포트는 직관적으로
- 올바르게 통계 사용하기
- 정확하게 데이터 통합하기
- 효과적으로 데이터 요약하기
- 대상 독자를 위한 리포트 커스터마이즈
- 간결한 말 요약 사용하기
- 사용가능한 데이터 만들기

### frequently reported performance data
- end-user response times
- resource utilization
- volumes, capacities, and rates


- trends

### types of results sharing
- 날 것의 데이터 보이기
- 테크니컬 리포트
- 이해 관계자 리포트

### 테크니컬 리포트 만들기


### 스테이크 가진 사람 리포트 만들기


### summary
- 성능 테스트 리포팅은 기술적, 비즈니스적으로 중요한 결정을 내릴 때 도움이 되는 결과 데이터를 표현하는 과정이다.
- 효과적인 리포트를 만드는 열쇠는 어떻게 데이터를 ㅍ현할지를 정하는 것보다 누가 데이터를 보게 될지를 고려하는 것이다.
- 가장 효과적인 성능 테스트 결과는 결과를 얻은 방법보다는 결과의 분석, 비교, 디테일 등으로 표현될 것이며, 이는 비즈니스 의사-결정에 중요한 역할을 할 것이다.