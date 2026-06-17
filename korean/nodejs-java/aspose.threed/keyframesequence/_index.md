---
title: "KeyframeSequence"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/keyframesequence/
---
## KeyframeSequence class

키 프레임의 시퀀스로, 시간에 따라 샘플 값의 변환을 설명합니다.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor(name) | KeyframeSequence 클래스의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 이름 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload() | KeyframeSequence 클래스의 새 인스턴스를 초기화합니다. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| 이름 | 설명 |
| --- | --- |
| getBindPoint() | 이 곡선을 소유하는 속성 바인드 포인트를 가져옵니다. |

 **Result:**



---


### getKeyFrames{#getKeyFrames}

| 이름 | 설명 |
| --- | --- |
| getKeyFrames() | 이 곡선의 키 프레임을 가져옵니다. 키들. |

 **Result:**



---


### getPostBehavior{#getPostBehavior}

| 이름 | 설명 |
| --- | --- |
| getPostBehavior() | 마지막 키 프레임 이후에 샘플링된 값이 어떻게 될지 나타내는 포스트 동작을 가져옵니다. |

 **Result:**



---


### getPreBehavior{#getPreBehavior}

| 이름 | 설명 |
| --- | --- |
| getPreBehavior() | 첫 번째 키 이전에 샘플링된 값이 어떻게 될지 나타내는 프리 동작을 가져옵니다. |

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


### add{#add}

| 이름 | 설명 |
| --- | --- |
| add(time, value) | 지정된 값으로 새 키 프레임을 생성합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| time | 숫자 | 시간 위치(초 단위 측정) |
| value | 숫자 | 이 시간 위치의 값 |

 **Result:**



---


### add{#add}

| 이름 | 설명 |
| --- | --- |
| add(time, value, interpolation) | 지정된 값으로 새 키 프레임을 생성합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| time | 숫자 | 시간 위치(초 단위 측정) |
| value | 숫자 | 이 시간 위치의 값 |
| 보간 | 보간 | 보간 |

 **Result:**



---


### reset{#reset}

| 이름 | 설명 |
| --- | --- |
| reset() | 모든 키 프레임을 제거하고 포스트/프리 행동을 재설정합니다. |

 **Result:**



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


### iterator{#iterator}

| 이름 | 설명 |
| --- | --- |
| iterator() | 내부 사용을 위해 예약되었습니다. |

 **Result:**
속성


---



