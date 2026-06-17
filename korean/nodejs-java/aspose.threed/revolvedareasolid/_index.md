---
title: "RevolvedAreaSolid"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/revolvedareasolid/
---
## RevolvedAreaSolid class

이 클래스는 프로파일이 제공하는 단면을 축을 중심으로 회전시켜 고체 모델을 나타냅니다.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getAngleStart{#getAngleStart}

| 이름 | 설명 |
| --- | --- |
| getAngleStart() | 회전 절차의 시작 각도를 가져오거나 설정합니다. 라디안으로 측정되며, 기본값은 0입니다. |

 **Result:**



---


### setAngleStart{#setAngleStart}

| 이름 | 설명 |
| --- | --- |
| setAngleStart(value) | 회전 절차의 시작 각도를 가져오거나 설정합니다. 라디안으로 측정되며, 기본값은 0입니다. |

 **Result:**



---


### getAngleEnd{#getAngleEnd}

| 이름 | 설명 |
| --- | --- |
| getAngleEnd() | 회전 절차의 종료 각도를 가져오거나 설정합니다. 라디안으로 측정되며, 기본값은 π입니다. |

 **Result:**



---


### setAngleEnd{#setAngleEnd}

| 이름 | 설명 |
| --- | --- |
| setAngleEnd(value) | 회전 절차의 종료 각도를 가져오거나 설정합니다. 라디안으로 측정되며, 기본값은 π입니다. |

 **Result:**



---


### getAxis{#getAxis}

| 이름 | 설명 |
| --- | --- |
| getAxis() | 축 방향을 가져오거나 설정합니다. 기본값은 (0, 1, 0)입니다. |

 **Result:**



---


### setAxis{#setAxis}

| 이름 | 설명 |
| --- | --- |
| setAxis(value) | 축 방향을 가져오거나 설정합니다. 기본값은 (0, 1, 0)입니다. |

 **Result:**



---


### getOrigin{#getOrigin}

| 이름 | 설명 |
| --- | --- |
| getOrigin() | 회전의 원점 위치를 가져오거나 설정합니다. 기본값은 (0, 0, 0)입니다. |

 **Result:**



---


### setOrigin{#setOrigin}

| 이름 | 설명 |
| --- | --- |
| setOrigin(value) | 회전의 원점 위치를 가져오거나 설정합니다. 기본값은 (0, 0, 0)입니다. |

 **Result:**



---


### getShape{#getShape}

| 이름 | 설명 |
| --- | --- |
| getShape() | 회전에 사용되는 기본 프로파일을 가져오거나 설정합니다. |

 **Result:**



---


### setShape{#setShape}

| 이름 | 설명 |
| --- | --- |
| setShape(value) | 회전에 사용되는 기본 프로파일을 가져오거나 설정합니다. |

 **Result:**



---


### getParentNodes{#getParentNodes}

| 이름 | 설명 |
| --- | --- |
| getParentNodes() | 모든 부모 노드를 가져옵니다. 엔터티는 기하학 인스턴싱을 위해 여러 부모 노드에 부착될 수 있습니다. |

 **Result:**



---


### getExcluded{#getExcluded}

| 이름 | 설명 |
| --- | --- |
| getExcluded() | 내보내기 중에 이 엔터티를 제외할지 여부를 가져오거나 설정합니다. |

 **Result:**



---


### setExcluded{#setExcluded}

| 이름 | 설명 |
| --- | --- |
| setExcluded(value) | 내보내기 중에 이 엔터티를 제외할지 여부를 가져오거나 설정합니다. |

 **Result:**



---


### getParentNode{#getParentNode}

| 이름 | 설명 |
| --- | --- |
| getParentNode() | 첫 번째 부모 노드를 가져오거나 설정합니다. 첫 번째 부모 노드를 설정하면 이 엔터티는 다른 부모 노드에서 분리됩니다. 부모 노드. |

 **Result:**



---


### setParentNode{#setParentNode}

| 이름 | 설명 |
| --- | --- |
| setParentNode(value) | 첫 번째 부모 노드를 가져오거나 설정합니다. 첫 번째 부모 노드를 설정하면 이 엔터티는 다른 부모 노드에서 분리됩니다. 부모 노드. |

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


### toMesh{#toMesh}

| 이름 | 설명 |
| --- | --- |
| toMesh() | RevolvedAreaSolid을 메시로 변환합니다. |

 **Result:**
Mesh


---


### getBoundingBox{#getBoundingBox}

| 이름 | 설명 |
| --- | --- |
| getBoundingBox() | 현재 엔터티의 객체 공간 좌표계에서 경계 상자를 가져옵니다. |

 **Result:**
Mesh


---


### getEntityRendererKey{#getEntityRendererKey}

| 이름 | 설명 |
| --- | --- |
| getEntityRendererKey() | 렌더러에 등록된 엔터티 렌더러의 키를 가져옵니다. |

 **Result:**
EntityRendererKey


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



