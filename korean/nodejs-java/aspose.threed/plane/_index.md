---
title: "Plane"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/plane/
---
## Plane class

매개변수화된 평면.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() | Plane의 새 인스턴스를 기본 크기 1x1로 초기화합니다. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload(length, width) | Plane의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 길이 | 숫자 | 평면의 길이. |
| 너비 | 숫자 | 평면의 너비. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 이름 | 설명 |
| --- | --- |
| constructor_overload2(name, length, width, lengthSegments, widthSegments) | Plane의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 이름. |
| 길이 | 숫자 | 평면의 길이. |
| 너비 | 숫자 | 평면의 너비. |
| lengthSegments | 숫자 | 길이 세그먼트. |
| widthSegments | 숫자 | 너비 세그먼트. |

 **Result:**



---


### getUp{#getUp}

| 이름 | 설명 |
| --- | --- |
| getUp() | 평면의 up 벡터를 가져오거나 설정합니다. 기본값은 (0, 1, 0)이며, 이는 평면 생성에 영향을 줍니다. |

 **Result:**



---


### setUp{#setUp}

| 이름 | 설명 |
| --- | --- |
| setUp(value) | 평면의 up 벡터를 가져오거나 설정합니다. 기본값은 (0, 1, 0)이며, 이는 평면 생성에 영향을 줍니다. |

 **Result:**



---


### getLength{#getLength}

| 이름 | 설명 |
| --- | --- |
| getLength() | 평면의 길이를 가져오거나 설정합니다. 길이. |

 **Result:**



---


### setLength{#setLength}

| 이름 | 설명 |
| --- | --- |
| setLength(value) | 평면의 길이를 가져오거나 설정합니다. 길이. |

 **Result:**



---


### getWidth{#getWidth}

| 이름 | 설명 |
| --- | --- |
| getWidth() | 평면의 너비를 가져오거나 설정합니다. 너비. |

 **Result:**



---


### setWidth{#setWidth}

| 이름 | 설명 |
| --- | --- |
| setWidth(value) | 평면의 너비를 가져오거나 설정합니다. 너비. |

 **Result:**



---


### getLengthSegments{#getLengthSegments}

| 이름 | 설명 |
| --- | --- |
| getLengthSegments() | 길이 세그먼트를 가져오거나 설정합니다. 길이 세그먼트. |

 **Result:**



---


### setLengthSegments{#setLengthSegments}

| 이름 | 설명 |
| --- | --- |
| setLengthSegments(value) | 길이 세그먼트를 가져오거나 설정합니다. 길이 세그먼트. |

 **Result:**



---


### getWidthSegments{#getWidthSegments}

| 이름 | 설명 |
| --- | --- |
| getWidthSegments() | 너비 세그먼트를 가져오거나 설정합니다. 너비 세그먼트. |

 **Result:**



---


### setWidthSegments{#setWidthSegments}

| 이름 | 설명 |
| --- | --- |
| setWidthSegments(value) | 너비 세그먼트를 가져오거나 설정합니다. 너비 세그먼트. |

 **Result:**



---


### getCastShadows{#getCastShadows}

| 이름 | 설명 |
| --- | --- |
| getCastShadows() | 이 지오메트리가 그림자를 드리울 수 있는지 가져오거나 설정합니다. |

 **Result:**



---


### setCastShadows{#setCastShadows}

| 이름 | 설명 |
| --- | --- |
| setCastShadows(value) | 이 지오메트리가 그림자를 드리울 수 있는지 가져오거나 설정합니다. |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| 이름 | 설명 |
| --- | --- |
| getReceiveShadows() | 이 지오메트리가 그림자를 받을 수 있는지 가져오거나 설정합니다. |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| 이름 | 설명 |
| --- | --- |
| setReceiveShadows(value) | 이 지오메트리가 그림자를 받을 수 있는지 가져오거나 설정합니다. |

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
| toMesh() | 현재 객체를 메시로 변환합니다 |

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



