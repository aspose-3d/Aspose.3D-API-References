---
title: "AnimationClip"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/animationclip/
---
## AnimationClip class

Animation 클립은 애니메이션의 컬렉션입니다. 씬은 하나 이상의 애니메이션 클립을 가질 수 있습니다.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() | AnimationClip 클래스의 새 인스턴스를 초기화합니다. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload(name) | AnimationClip 클래스의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 이름 |

 **Result:**



---


### getAnimations{#getAnimations}

| 이름 | 설명 |
| --- | --- |
| getAnimations() | 클립에 포함된 애니메이션을 가져옵니다. 레이어. |

 **Result:**



---


### getDescription{#getDescription}

| 이름 | 설명 |
| --- | --- |
| getDescription() | 이 애니메이션 클립의 설명을 가져오거나 설정합니다. |

 **Result:**



---


### setDescription{#setDescription}

| 이름 | 설명 |
| --- | --- |
| setDescription(value) | 이 애니메이션 클립의 설명을 가져오거나 설정합니다. |

 **Result:**



---


### getStart{#getStart}

| 이름 | 설명 |
| --- | --- |
| getStart() | 클립 시작 시점의 시간을 초 단위로 가져오거나 설정합니다. |

 **Result:**



---


### setStart{#setStart}

| 이름 | 설명 |
| --- | --- |
| setStart(value) | 클립 시작 시점의 시간을 초 단위로 가져오거나 설정합니다. |

 **Result:**



---


### getStop{#getStop}

| 이름 | 설명 |
| --- | --- |
| getStop() | 클립 종료 시점의 시간을 초 단위로 가져오거나 설정합니다. |

 **Result:**



---


### setStop{#setStop}

| 이름 | 설명 |
| --- | --- |
| setStop(value) | 클립 종료 시점의 시간을 초 단위로 가져오거나 설정합니다. |

 **Result:**



---


### getScene{#getScene}

| 이름 | 설명 |
| --- | --- |
| getScene() | 이 객체가 속한 씬을 가져옵니다. |

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


### createAnimationNode{#createAnimationNode}

| 이름 | 설명 |
| --- | --- |
| createAnimationNode(nodeName) | 현재 클립에 애니메이션 노드를 생성하고 등록하는 단축 함수입니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| nodeName | String | 새 애니메이션 노드의 이름 |

 **Result:**
AnimationNode


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



