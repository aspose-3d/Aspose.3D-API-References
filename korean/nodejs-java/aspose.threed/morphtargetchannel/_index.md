---
title: "MorphTargetChannel"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/morphtargetchannel/
---
## MorphTargetChannel class

MorphTargetChannel 은 MorphTargetDeformer 가 대상 기하학을 정리하는 데 사용됩니다.  FBX 와 같은 일부 파일 형식은 여러 채널을 동시에 지원합니다.  가중치는 0에서 1.0 사이이며, 대상의 기본 가중치는 0.0입니다;


## Properties

| 이름 | 설명 |
| --- | --- |
| DEFAULT_WEIGHT | 모프 타겟의 기본 무게. |

## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor(name) | MorphTargetChannel 클래스의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 이름. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload() | MorphTargetChannel 클래스의 새 인스턴스를 초기화합니다. |

 **Result:**



---


### getWeights{#getWeights}

| 이름 | 설명 |
| --- | --- |
| getWeights() | 대상 기하학의 전체 무게 값을 가져옵니다. 전체 무게. |

 **Result:**



---


### getChannelWeight{#getChannelWeight}

| 이름 | 설명 |
| --- | --- |
| getChannelWeight() | 이 채널의 디포머 무게를 가져오거나 설정합니다. 무게는 0.0에서 1.0 사이입니다. |

 **Result:**



---


### setChannelWeight{#setChannelWeight}

| 이름 | 설명 |
| --- | --- |
| setChannelWeight(value) | 이 채널의 디포머 무게를 가져오거나 설정합니다. 무게는 0.0에서 1.0 사이입니다. |

 **Result:**



---


### getTargets{#getTargets}

| 이름 | 설명 |
| --- | --- |
| getTargets() | 채널과 연결된 모든 타겟을 가져옵니다. |

 **Result:**



---


### getName{#getName}

| 이름 | 설명 |
| --- | --- |
| getName() | 이름을 가져오거나 설정합니다. 이름. |

 **Result:**



---


### setName{#setName}

| 이름 | 설명 |
| --- | --- |
| setName(value) | 이름을 가져오거나 설정합니다. 이름. |

 **Result:**



---


### getProperties{#getProperties}

| 이름 | 설명 |
| --- | --- |
| getProperties() | 모든 속성의 컬렉션을 가져옵니다. |

 **Result:**



---


### get{#get}

| 이름 | 설명 |
| --- | --- |
| get(target) |  |

 **Result:**



---


### set{#set}

| 이름 | 설명 |
| --- | --- |
| set(target, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| 이름 | 설명 |
| --- | --- |
| getWeight(target) | 지정된 대상의 무게를 가져옵니다. 대상이 이 채널에 속하지 않으면 기본값 0이 반환됩니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 대상 | 모양 | null |

 **Result:**
숫자


---


### setWeight{#setWeight}

| 이름 | 설명 |
| --- | --- |
| setWeight(target, weight) | 지정된 대상의 무게를 설정합니다. 기본값은 1이며, 범위는 0~1 사이여야 합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 대상 | 모양 | null |
| 무게 | 숫자 | null |

 **Result:**
숫자


---


### removeProperty{#removeProperty}

| 이름 | 설명 |
| --- | --- |
| removeProperty(property) | 동적 속성을 제거합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 속성 | 속성 | 제거할 속성은 무엇입니까 |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| 이름 | 설명 |
| --- | --- |
| removeProperty(property) | 이름으로 식별된 지정된 속성을 제거합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| 이름 | 설명 |
| --- | --- |
| getProperty(property) | 지정된 속성의 값을 가져옵니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 속성 | String | 속성 이름 |

 **Result:**
Object


---


### setProperty{#setProperty}

| 이름 | 설명 |
| --- | --- |
| setProperty(property, value) | 지정된 속성의 값을 설정합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 속성 | String | 속성 이름 |
| value | Object | 속성의 값 |

 **Result:**
Object


---


### findProperty{#findProperty}

| 이름 | 설명 |
| --- | --- |
| findProperty(propertyName) | 속성을 찾습니다. 동적 속성 (Created by CreateDynamicProperty/SetProperty) 또는 네이티브 속성(Identified by its name) 일 수 있습니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| propertyName | String | 속성 이름. |

 **Result:**
속성


---



