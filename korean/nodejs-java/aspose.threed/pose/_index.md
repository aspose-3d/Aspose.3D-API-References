---
title: "포즈"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/pose/
---
## Pose class

포즈는 지오메트리가 스키닝될 때 변환 행렬을 저장하는 데 사용됩니다. 포즈는 BonePose의 집합이며, 각 BonePose는 본 노드의 구체적인 변환 정보를 저장합니다.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor(name) | Pose 클래스의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 이름 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload() | Pose 클래스의 새 인스턴스를 초기화합니다. |

 **Result:**



---


### getPoseType{#getPoseType}

| 이름 | 설명 |
| --- | --- |
| getPoseType() | 포즈의 유형을 가져오거나 설정합니다. 속성 값은 PoseType 정수 상수입니다. 포즈의 유형. |

 **Result:**



---


### setPoseType{#setPoseType}

| 이름 | 설명 |
| --- | --- |
| setPoseType(value) | 포즈의 유형을 가져오거나 설정합니다. 속성 값은 PoseType 정수 상수입니다. 포즈의 유형. |

 **Result:**



---


### getBonePoses{#getBonePoses}

| 이름 | 설명 |
| --- | --- |
| getBonePoses() | 모든 BonePose를 가져옵니다. 노드들. |

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


### addBonePose{#addBonePose}

| 이름 | 설명 |
| --- | --- |
| addBonePose(node, matrix, localMatrix) | 주어진 본 노드에 대한 포즈 변환 행렬을 저장합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| node | Node | 본 노드. |
| matrix | Matrix4 | 변환 행렬. |
| localMatrix | boolean | 설정된 경우 |

 **Result:**



---


### addBonePose{#addBonePose}

| 이름 | 설명 |
| --- | --- |
| addBonePose(node, matrix) | 주어진 본 노드에 대한 포즈 변환 행렬을 저장합니다. 전역 변환 행렬이 암시됩니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| node | Node | 본 노드. |
| matrix | Matrix4 | 변환 행렬. |

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



