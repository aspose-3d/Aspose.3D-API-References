---
title: "MorphTargetDeformer"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/morphtargetdeformer/
---
## MorphTargetDeformer class

MorphTargetDeformer 는 정점별 애니메이션을 제공합니다.  MorphTargetDeformer 는 모든 대상을 MorphTargetChannel 을 통해 조직하며, 각 채널은 여러 대상을 조직할 수 있습니다.  morph target deformer 의 일반적인 사용 사례는 캐릭터에 얼굴 표정을 적용하는 것입니다.  자세한 내용은 https://en.wikipedia.org/wiki/Morph_target_animation 에서 확인할 수 있습니다.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor(name) | MorphTargetDeformer 클래스의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 이름. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload() | MorphTargetDeformer 클래스의 새 인스턴스를 초기화합니다. |

 **Result:**



---


### getChannels{#getChannels}

| 이름 | 설명 |
| --- | --- |
| getChannels() | 이 디포머에 포함된 모든 채널을 가져옵니다. |

 **Result:**



---


### getOwner{#getOwner}

| 이름 | 설명 |
| --- | --- |
| getOwner() | 이 디포머를 소유하는 지오메트리를 가져옵니다. |

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



