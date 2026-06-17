---
title: "NurbsCurve"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/nurbscurve/
---
## NurbsCurve class

NURBS 곡선은 NURBS(Non-uniform rational basis spline) 로 표현되는 곡선이며, NURBS 곡선은 Order, 가중치가 적용된 Geometry.ControlPoints 집합 및 KnotVectors 로 정의됩니다. 컨트롤 포인트의 w 구성 요소는 해당 포인트의 가중치로 사용되며, CurveDimension.TWO_DIMENSIONAL 이든 CurveDimension.THREE_DIMENSIONAL 이든 동일합니다.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() | NurbsCurve 클래스의 새 인스턴스를 초기화합니다. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload(name) | NurbsCurve 클래스의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 이름 |

 **Result:**



---


### getControlPoints{#getControlPoints}

| 이름 | 설명 |
| --- | --- |
| getControlPoints() | 모든 제어점을 가져옵니다. |

 **Result:**



---


### getMultiplicity{#getMultiplicity}

| 이름 | 설명 |
| --- | --- |
| getMultiplicity() | 중복성을 가져옵니다. 중복성입니다. |

 **Result:**



---


### getOrder{#getOrder}

| 이름 | 설명 |
| --- | --- |
| getOrder() | NURBS 곡선의 차수를 가져오거나 설정합니다. 차수는 곡선상의 임의의 점에 영향을 주는 인접 제어점의 수를 정의합니다. 차수입니다. |

 **Result:**



---


### setOrder{#setOrder}

| 이름 | 설명 |
| --- | --- |
| setOrder(value) | NURBS 곡선의 차수를 가져오거나 설정합니다. 차수는 곡선상의 임의의 점에 영향을 주는 인접 제어점의 수를 정의합니다. 차수입니다. |

 **Result:**



---


### getDimension{#getDimension}

| 이름 | 설명 |
| --- | --- |
| getDimension() | 곡선의 차원을 가져오거나 설정합니다. 이 속성의 값은 CurveDimension 정수 상수입니다. CurveDimension.TWO_DIMENSIONAL 곡선의 경우, 제어점의 z 구성 요소는 사용되지 않습니다. |

 **Result:**



---


### setDimension{#setDimension}

| 이름 | 설명 |
| --- | --- |
| setDimension(value) | 곡선의 차원을 가져오거나 설정합니다. 이 속성의 값은 CurveDimension 정수 상수입니다. CurveDimension.TWO_DIMENSIONAL 곡선의 경우, 제어점의 z 구성 요소는 사용되지 않습니다. |

 **Result:**



---


### getCurveType{#getCurveType}

| 이름 | 설명 |
| --- | --- |
| getCurveType() | 곡선의 유형을 가져오거나 설정합니다. 속성 값은 NurbsType 정수 상수입니다. 곡선의 유형. |

 **Result:**



---


### setCurveType{#setCurveType}

| 이름 | 설명 |
| --- | --- |
| setCurveType(value) | 곡선의 유형을 가져오거나 설정합니다. 속성 값은 NurbsType 정수 상수입니다. 곡선의 유형. |

 **Result:**



---


### getKnotVectors{#getKnotVectors}

| 이름 | 설명 |
| --- | --- |
| getKnotVectors() | 노트 벡터를 가져옵니다. 이는 매개변수 값들의 시퀀스로, 제어점이 NURBS 곡선에 영향을 주는 위치와 방식을 결정합니다. |

 **Result:**



---


### getRational{#getRational}

| 이름 | 설명 |
| --- | --- |
| getRational() | 합리적인지 여부를 가져오거나 설정합니다. 이 값은 NurbsCurve가 유리 스플라인인지 비유리 스플라인인지를 나타냅니다. 비유리 B-스플라인은 유리 B-스플라인의 특수한 경우입니다. 유리 스플라인이면 true; 그렇지 않으면 비유리 스플라인은 false. |

 **Result:**



---


### setRational{#setRational}

| 이름 | 설명 |
| --- | --- |
| setRational(value) | 합리적인지 여부를 가져오거나 설정합니다. 이 값은 NurbsCurve가 유리 스플라인인지 비유리 스플라인인지를 나타냅니다. 비유리 B-스플라인은 유리 B-스플라인의 특수한 경우입니다. 유리 스플라인이면 true; 그렇지 않으면 비유리 스플라인은 false. |

 **Result:**



---


### getColor{#getColor}

| 이름 | 설명 |
| --- | --- |
| getColor() | 선의 색상을 가져오거나 설정합니다. 기본값은 흰색(1, 1, 1)입니다. |

 **Result:**



---


### setColor{#setColor}

| 이름 | 설명 |
| --- | --- |
| setColor(value) | 선의 색상을 가져오거나 설정합니다. 기본값은 흰색(1, 1, 1)입니다. |

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


### evaluate{#evaluate}

| 이름 | 설명 |
| --- | --- |
| evaluate(steps) | NURBS 곡선을 평가합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 단계 | 숫자 | 두 인접 노트 사이의 평가 빈도, 기본값은 20입니다. |

 **Result:**
Vector4[]


---


### evaluateAt{#evaluateAt}

| 이름 | 설명 |
| --- | --- |
| evaluateAt(u) | 지정된 위치에서 곡선의 점을 평가합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| u | 숫자 | 곡선 내 위치, 0과 1 사이 |

 **Result:**
Vector4


---


### getEntityRendererKey{#getEntityRendererKey}

| 이름 | 설명 |
| --- | --- |
| getEntityRendererKey() | 렌더러에 등록된 엔터티 렌더러의 키를 가져옵니다. |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| 이름 | 설명 |
| --- | --- |
| getBoundingBox() | 현재 엔터티의 객체 공간 좌표계에서 경계 상자를 가져옵니다. |

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



