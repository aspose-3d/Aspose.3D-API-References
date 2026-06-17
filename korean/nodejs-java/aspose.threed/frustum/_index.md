---
title: "프러스텀"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/frustum/
---
## Frustum class

Camera와 Light의 기본 클래스  @hideconstructor


## 메서드

### getRotationMode{#getRotationMode}

| 이름 | 설명 |
| --- | --- |
| getRotationMode() | 프러스텀의 방향 모드를 가져오거나 설정합니다. 이 속성은 Target이 null인 경우에만 작동합니다. 값이 RotationMode.FIXED_TARGET이면 방향은 항상 LookAt 속성에 의해 계산됩니다. 그렇지 않으면 LookAt은 항상 Direction에 의해 계산됩니다. 이 속성의 값은 RotationMode 정수 상수입니다. |

 **Result:**



---


### setRotationMode{#setRotationMode}

| 이름 | 설명 |
| --- | --- |
| setRotationMode(value) | 프러스텀의 방향 모드를 가져오거나 설정합니다. 이 속성은 Target이 null인 경우에만 작동합니다. 값이 RotationMode.FIXED_TARGET이면 방향은 항상 LookAt 속성에 의해 계산됩니다. 그렇지 않으면 LookAt은 항상 Direction에 의해 계산됩니다. 이 속성의 값은 RotationMode 정수 상수입니다. |

 **Result:**



---


### getNearPlane{#getNearPlane}

| 이름 | 설명 |
| --- | --- |
| getNearPlane() | 프러스텀의 근접 평면 거리를 가져오거나 설정합니다. |

 **Result:**



---


### setNearPlane{#setNearPlane}

| 이름 | 설명 |
| --- | --- |
| setNearPlane(value) | 프러스텀의 근접 평면 거리를 가져오거나 설정합니다. |

 **Result:**



---


### getFarPlane{#getFarPlane}

| 이름 | 설명 |
| --- | --- |
| getFarPlane() | 프러스텀의 원거리 평면 거리를 가져오거나 설정합니다. |

 **Result:**



---


### setFarPlane{#setFarPlane}

| 이름 | 설명 |
| --- | --- |
| setFarPlane(value) | 프러스텀의 원거리 평면 거리를 가져오거나 설정합니다. |

 **Result:**



---


### getAspect{#getAspect}

| 이름 | 설명 |
| --- | --- |
| getAspect() | 프러스텀의 종횡비를 가져오거나 설정합니다. |

 **Result:**



---


### setAspect{#setAspect}

| 이름 | 설명 |
| --- | --- |
| setAspect(value) | 프러스텀의 종횡비를 가져오거나 설정합니다. |

 **Result:**



---


### getOrthoHeight{#getOrthoHeight}

| 이름 | 설명 |
| --- | --- |
| getOrthoHeight() | 프러스텀을 직교 투영으로 사용할 때 높이를 가져오거나 설정합니다. |

 **Result:**



---


### setOrthoHeight{#setOrthoHeight}

| 이름 | 설명 |
| --- | --- |
| setOrthoHeight(value) | 프러스텀을 직교 투영으로 사용할 때 높이를 가져오거나 설정합니다. |

 **Result:**



---


### getUp{#getUp}

| 이름 | 설명 |
| --- | --- |
| getUp() | 카메라의 위쪽 방향을 가져오거나 설정합니다. |

 **Result:**



---


### setUp{#setUp}

| 이름 | 설명 |
| --- | --- |
| setUp(value) | 카메라의 위쪽 방향을 가져오거나 설정합니다. |

 **Result:**



---


### getLookAt{#getLookAt}

| 이름 | 설명 |
| --- | --- |
| getLookAt() | 카메라가 바라보는 관심 위치를 가져오거나 설정합니다. |

 **Result:**



---


### setLookAt{#setLookAt}

| 이름 | 설명 |
| --- | --- |
| setLookAt(value) | 카메라가 바라보는 관심 위치를 가져오거나 설정합니다. |

 **Result:**



---


### getDirection{#getDirection}

| 이름 | 설명 |
| --- | --- |
| getDirection() | 카메라가 바라보는 방향을 가져오거나 설정합니다. 이 속성의 변경은 LookAt 및 Target에도 영향을 줍니다. |

 **Result:**



---


### setDirection{#setDirection}

| 이름 | 설명 |
| --- | --- |
| setDirection(value) | 카메라가 바라보는 방향을 가져오거나 설정합니다. 이 속성의 변경은 LookAt 및 Target에도 영향을 줍니다. |

 **Result:**



---


### getTarget{#getTarget}

| 이름 | 설명 |
| --- | --- |
| getTarget() | 카메라가 바라보는 대상을 가져오거나 설정합니다. 사용자가 이 속성을 지원하는 경우 LookAt 속성보다 먼저 설정해야 합니다. |

 **Result:**



---


### setTarget{#setTarget}

| 이름 | 설명 |
| --- | --- |
| setTarget(value) | 카메라가 바라보는 대상을 가져오거나 설정합니다. 사용자가 이 속성을 지원하는 경우 LookAt 속성보다 먼저 설정해야 합니다. |

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


### getBoundingBox{#getBoundingBox}

| 이름 | 설명 |
| --- | --- |
| getBoundingBox() | 현재 엔터티의 객체 공간 좌표계에서 경계 상자를 가져옵니다. |

 **Result:**



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



