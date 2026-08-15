> 한국어: 권위 있는 영어 소스의 기계 지원 번역입니다. 모국어 수정을 환영합니다. [영어](../../README.md) | [모든 언어](../README.md)

# 시스템이 함께 유지되는 방법

![교체 가능한 전문가와 검사 가능한 제어 평면을 지원하는 보존된 기록](../../assets/core-architecture-layers.png)

## 책임의 분리

플랫폼은 서로가 되지 않고 협력하는 네 가지 관심사를 분리합니다.

1. **보존**은 원래의 증거와 관찰된 출처를 유지합니다.
2. **이해**는 버전이 지정된 의미 개체, 관계, 시간 상태를 추가합니다.
  그리고 지원되는 해석.
3. **검색 및 상호작용**은 질문에 대한 요청별 증거를 수집하고,
  탐색과 대화.
4. **아티팩트 재구성**은 제한된 증거 세계를 선언된 증거 세계로 변환합니다.
  선언된 수신자를 위한 제품입니다.

제품 지침은 코퍼스 진실로 역방향으로 유출되지 않습니다. 장, 청중, 장르, 수사적 움직임 또는 단어 예산은 하나의 철회에 속합니다. 소스 아티팩트의 고유 레이블이 아닙니다.

## 계층화된 토폴로지

```text
PRIMARY EVIDENCE
  immutable artifacts, interaction events, source identity, observed arrival
        |
        v
VERSIONED REPRESENTATIONS
  extracted text, media observations, chunks, entities, embeddings, locators
        |
        v
SEMANTIC AND TEMPORAL MAPS
  propositions, discourse links, argument edges, chronology, supersession,
  uncertainty, open attachment points, Personal Meaning Matrix contributions
        |
        +---------------------------+
        |                           |
        v                           v
INTERACTIVE CONTEXT             ARTIFACT CONTRACT
  request-scoped traversal        receiver, purpose, form, budget, evidence rules
        |                           |
        |                           v
        |                       REVERSE EXPANSION
        |                           |
        |                       WHOLE-TREE COLLAPSE
        |                           |
        |                       FORWARD RECONSTRUCTION
        |                           |
        +----------------------> HUMAN PROTOCOL + WEAVE
                                    |
                                INDEPENDENT GATES
                                    |
                              RECEIPT-GATED PRODUCT
```

## 가입은 아는 척 하지 않습니다

도착 기록에는 특정 바이트가 특정 채널을 통해 시스템에 도달했음을 명시할 수 있습니다. 아티팩트를 만든 사람, 그 안에 나타나는 사람, 제목이 발생한 시기, 파일 이름이 정확한지, 파일 이름이 중요한 이유 또는 콘텐츠의 소유자를 자동으로 결정하지 않습니다. 이는 별도의 증거와 권위가 있는 별도의 관찰입니다.

아키텍처는 원본 아티팩트와 파생된 표현을 구별합니다. 추출된 텍스트, 설명, 임베딩, 분류, 요약 및 관계는 재생성되거나 대체될 수 있습니다. 소스를 대체하지 않습니다.

## 대화형 및 문서 경로

대화형 응답 및 아티팩트 생성은 증거, 출처, 유형화된 관계, 불확실성 및 검증 메커니즘을 공유합니다. 이는 동일한 작업 흐름과 별개로 유지됩니다.

대화형 요청에는 완전한 대화, 작업 수명 주기, 좁은 관계 순회 또는 설명이 필요할 수 있습니다. 책 컨테이너를 구성하고 히스토리 트리를 전역적으로 축소할 필요가 없습니다.

아티팩트 생성에는 선언된 제품, 수신자, 예산 및 전체 아티팩트 계획이 필요합니다. 가지치기 전에 관련 임시 구조를 확인하고 누락된 부분을 설명해야 합니다.

## 고정된 체인이 아닌 동적 아키텍처

조립 라인은 제품에 맞게 컴파일됩니다. 다양한 출력에서는 다양한 전문가를 사용하거나, 동일한 전문가를 다르게 주문하거나, 하나의 기능에 대해 여러 인스턴스가 필요할 수 있습니다. 관리자는 하드코딩된 단계 이름만 사용하기보다는 기능 계약과 사전 증거를 사용합니다.

보편적 불변성은 소스 신원, 소유권, 인식론적 상태, 불확실성, 손실 계산, 유형화된 핸드오프, 비용 관찰, 독립적 검증 및 롤백 등 모든 라인에서 안정적으로 유지됩니다.

외부 일반 모델은 측정된 기여도가 핸드오프를 정당화할 때 하나의 유형 스테이션을 차지할 수 있습니다. 해당 스테이션에 필요한 요청 범위의 페이로드만 수신하며, 유지 관리된 코퍼스나 더 넓은 제어 평면에서 인코딩된 권한은 수신하지 않습니다. 해당 스테이션을 교체하거나 제거하면 내구성 있는 기록과 향후 재구성 기능이 그대로 유지됩니다. 경계가 있는 스테이션은 중앙 집중식 시스템이 제도적 가치로 평탄화될 인간의 지식을 받지 않고도 기여할 수 있습니다.
