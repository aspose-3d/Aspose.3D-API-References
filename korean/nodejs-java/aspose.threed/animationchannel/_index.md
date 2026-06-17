---
title: "AnimationChannel"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/animationchannel/
---
## AnimationChannel class

채널은 속성의 구성 요소 필드를 일련의 키프레임 시퀀스로 매핑합니다  @hideconstructor


## 메서드

### getComponentType{#getComponentType}

| 이름 | 설명 |
| --- | --- |
| getComponentType() | 구성 요소 필드의 유형을 가져옵니다 |

 **Result:**



---


### getName{#getName}

| 이름 | 설명 |
| --- | --- |
| getName() | 채널의 이름을 가져옵니다 |

 **Result:**



---


### getDefaultValue{#getDefaultValue}

| 이름 | 설명 |
| --- | --- |
| getDefaultValue() | 채널의 기본값을 가져오거나 설정합니다. 채널에 키프레임 시퀀스가 연결되지 않은 경우, 애니메이션 평가 중에 기본값이 사용됩니다. 실제 시나리오: 애니메이션이 노드의 x 좌표만 애니메이션하고 y와 z는 변경되지 않을 때, 전체 변환 평가 중에 기본값이 사용됩니다. |

 **Result:**



---


### setDefaultValue{#setDefaultValue}

| 이름 | 설명 |
| --- | --- |
| setDefaultValue(value) | 채널의 기본값을 가져오거나 설정합니다. 채널에 키프레임 시퀀스가 연결되지 않은 경우, 애니메이션 평가 중에 기본값이 사용됩니다. 실제 시나리오: 애니메이션이 노드의 x 좌표만 애니메이션하고 y와 z는 변경되지 않을 때, 전체 변환 평가 중에 기본값이 사용됩니다. |

 **Result:**



---


### getKeyframeSequences{#getKeyframeSequences}

| 이름 | 설명 |
| --- | --- |
| getKeyframeSequences() | 이 채널 내부의 모든 키프레임 시퀀스를 가져옵니다 |

 **Result:**



---


### addKeyframeSequence{#addKeyframeSequence}

| 이름 | 설명 |
| --- | --- |
| addKeyframeSequence(sequence) | 키프레임 시퀀스를 이 채널에 추가합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| sequence | KeyframeSequence | 추가할 키프레임 시퀀스입니다. |

 **Result:**



---


### iterator{#iterator}

| 이름 | 설명 |
| --- | --- |
| iterator() | 내부 사용을 위해 예약되었습니다. |

 **Result:**



---



