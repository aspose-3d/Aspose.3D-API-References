---
title: "본"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/bone/
---
## Bone class

Bone은 지오메트리의 컨트롤 포인트 하위 집합을 정의하고, 각 컨트롤 포인트에 대한 블렌드 가중치를 정의합니다. Bone 객체는 직접 사용할 수 없으며, SkinDeformer 인스턴스를 사용하여 지오메트리를 변형합니다. SkinDeformer는 여러 Bone을 포함하며, 각 Bone은 노드에 연결됩니다. NOTE: 지오메트리의 컨트롤 포인트는 둘 이상의 Bone에 바인딩될 수 있습니다.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor(name) | Bone 클래스의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 이름. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload() | Bone 클래스의 새 인스턴스를 초기화합니다. |

 **Result:**



---


### getWeightCount{#getWeightCount}

| 이름 | 설명 |
| --- | --- |
| getWeightCount() | 가중치 수를 가져옵니다. 이는 setWeight(int, double)로 자동으로 확장됩니다. |

 **Result:**



---


### getTransform{#getTransform}

| 이름 | 설명 |
| --- | --- |
| getTransform() | 본을 포함하는 노드의 변환 행렬을 가져오거나 설정합니다. |

 **Result:**



---


### setTransform{#setTransform}

| 이름 | 설명 |
| --- | --- |
| setTransform(value) | 본을 포함하는 노드의 변환 행렬을 가져오거나 설정합니다. |

 **Result:**



---


### getBoneTransform{#getBoneTransform}

| 이름 | 설명 |
| --- | --- |
| getBoneTransform() | 본의 변환 행렬을 가져오거나 설정합니다. |

 **Result:**



---


### setBoneTransform{#setBoneTransform}

| 이름 | 설명 |
| --- | --- |
| setBoneTransform(value) | 본의 변환 행렬을 가져오거나 설정합니다. |

 **Result:**



---


### getNode{#getNode}

| 이름 | 설명 |
| --- | --- |
| getNode() | 노드를 가져오거나 설정합니다. 본 노드는 스킨이 부착되는 본이며, SkinDeformer는 본 노드를 사용하여 컨트롤 포인트의 변위를 영향을 줍니다. 본 노드에는 일반적으로 Skeleton이 연결되어 있지만 필수는 아닙니다. 연결된 Skeleton은 보통 DCC 소프트웨어에서 사용자가 스켈레톤을 볼 수 있도록 사용됩니다. |

 **Result:**



---


### setNode{#setNode}

| 이름 | 설명 |
| --- | --- |
| setNode(value) | 노드를 가져오거나 설정합니다. 본 노드는 스킨이 부착되는 본이며, SkinDeformer는 본 노드를 사용하여 컨트롤 포인트의 변위를 영향을 줍니다. 본 노드에는 일반적으로 Skeleton이 연결되어 있지만 필수는 아닙니다. 연결된 Skeleton은 보통 DCC 소프트웨어에서 사용자가 스켈레톤을 볼 수 있도록 사용됩니다. |

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
| get(index) |  |

 **Result:**



---


### set{#set}

| 이름 | 설명 |
| --- | --- |
| set(index, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| 이름 | 설명 |
| --- | --- |
| getWeight(index) | 인덱스로 지정된 컨트롤 포인트의 가중치를 가져옵니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 인덱스 | 숫자 | 컨트롤 포인트 인덱스 |

 **Result:**
숫자


---


### setWeight{#setWeight}

| 이름 | 설명 |
| --- | --- |
| setWeight(index, weight) | 인덱스로 지정된 컨트롤 포인트의 가중치를 설정합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 인덱스 | 숫자 | 컨트롤 포인트 인덱스 |
| 무게 | 숫자 | 새 무게 |

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



