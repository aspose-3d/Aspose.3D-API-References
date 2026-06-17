---
title: "AnimationNode"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/animationnode/
---
## AnimationNode class

Aspose.3D는 애니메이션 계층 구조를 지원하며, 각 애니메이션은 여러 애니메이션 및 애니메이션의 키프레임 정의로 구성될 수 있습니다. AnimationNode는 시간에 따라 속성 값의 변환을 정의합니다. 예를 들어, animation node는 노드의 변환이나 다른 A3DObject 객체의 수치 속성을 제어하는 데 사용할 수 있습니다.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor(name) | AnimationNode 클래스의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 이름 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload() | AnimationNode 클래스의 새 인스턴스를 초기화합니다. |

 **Result:**



---


### getBindPoints{#getBindPoints}

| 이름 | 설명 |
| --- | --- |
| getBindPoints() | 현재 속성 바인드 포인트를 가져옵니다. |

 **Result:**



---


### getSubAnimations{#getSubAnimations}

| 이름 | 설명 |
| --- | --- |
| getSubAnimations() | 현재 애니메이션 아래의 서브 애니메이션 노드를 가져옵니다. |

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


### findBindPoint{#findBindPoint}

| 이름 | 설명 |
| --- | --- |
| findBindPoint(name) | 이름으로 바인드 포인트를 찾습니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 찾을 바인드 포인트의 이름. |

 **Result:**
BindPoint


---


### getBindPoint{#getBindPoint}

| 이름 | 설명 |
| --- | --- |
| getBindPoint(target, propName, create) | 주어진 속성에 대한 애니메이션 바인드 포인트를 가져옵니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 대상 | A3DObject | 바인드 포인트를 생성할 객체를 지정합니다. |
| propName | String | 속성의 이름입니다. |
| 생성 | boolean | 설정된 경우 |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| 이름 | 설명 |
| --- | --- |
| getKeyframeSequence(target, propName, channelName, create) | 주어진 속성 및 채널에 대한 키프레임 시퀀스를 가져옵니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 대상 | A3DObject | 키프레임 시퀀스를 생성할 인스턴스를 지정합니다. |
| propName | String | 속성의 이름입니다. |
| channelName | String | 채널 이름입니다. |
| 생성 | boolean | 설정된 경우 |

 **Result:**
KeyframeSequence


---


### getKeyframeSequence{#getKeyframeSequence}

| 이름 | 설명 |
| --- | --- |
| getKeyframeSequence(target, propName, create) | 주어진 속성에 대한 키프레임 시퀀스를 가져옵니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 대상 | A3DObject | 키프레임 시퀀스를 생성할 인스턴스를 지정합니다. |
| propName | String | 속성의 이름입니다. |
| 생성 | boolean | 설정된 경우 |

 **Result:**
KeyframeSequence


---


### createBindPoint{#createBindPoint}

| 이름 | 설명 |
| --- | --- |
| createBindPoint(obj, propName) | 속성 데이터 유형을 기반으로 BindPoint를 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| obj | A3DObject | 객체. |
| propName | String | 속성 이름. |

 **Result:**
BindPoint


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



