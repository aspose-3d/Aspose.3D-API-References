---
title: "Light"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/light/
---
## Light class

빛이 장면을 비춥니다.  빛의 전체 감쇠를 계산하는 공식은 다음과 같습니다:  A = ConstantAttenuation + (Dist  LinearAttenuation) + ((Dist^2)  QuadraticAttenuation)


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() | Light 클래스의 새 인스턴스를 초기화합니다. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload(name) | Light 클래스의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 이름 |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 이름 | 설명 |
| --- | --- |
| constructor_overload2(name, type) | Light 클래스의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 이름 |
| type | LightType | LightType |

 **Result:**



---


### getColor{#getColor}

| 이름 | 설명 |
| --- | --- |
| getColor() | 광원의 색상을 가져오거나 설정합니다 |

 **Result:**



---


### setColor{#setColor}

| 이름 | 설명 |
| --- | --- |
| setColor(value) | 광원의 색상을 가져오거나 설정합니다 |

 **Result:**



---


### getLightType{#getLightType}

| 이름 | 설명 |
| --- | --- |
| getLightType() | 광원의 유형을 가져오거나 설정합니다. 해당 속성의 값은 LightType 정수 상수입니다. |

 **Result:**



---


### setLightType{#setLightType}

| 이름 | 설명 |
| --- | --- |
| setLightType(value) | 광원의 유형을 가져오거나 설정합니다. 해당 속성의 값은 LightType 정수 상수입니다. |

 **Result:**



---


### getCastLight{#getCastLight}

| 이름 | 설명 |
| --- | --- |
| getCastLight() | 현재 광원 인스턴스가 다른 객체를 비출 수 있는지 여부를 가져오거나 설정합니다. |

 **Result:**



---


### setCastLight{#setCastLight}

| 이름 | 설명 |
| --- | --- |
| setCastLight(value) | 현재 광원 인스턴스가 다른 객체를 비출 수 있는지 여부를 가져오거나 설정합니다. |

 **Result:**



---


### getIntensity{#getIntensity}

| 이름 | 설명 |
| --- | --- |
| getIntensity() | 광원의 강도를 가져오거나 설정합니다. 기본값은 100입니다. |

 **Result:**



---


### setIntensity{#setIntensity}

| 이름 | 설명 |
| --- | --- |
| setIntensity(value) | 광원의 강도를 가져오거나 설정합니다. 기본값은 100입니다. |

 **Result:**



---


### getHotSpot{#getHotSpot}

| 이름 | 설명 |
| --- | --- |
| getHotSpot() | 핫 스팟 콘 각도(도)를 가져오거나 설정합니다. |

 **Result:**



---


### setHotSpot{#setHotSpot}

| 이름 | 설명 |
| --- | --- |
| setHotSpot(value) | 핫 스팟 콘 각도(도)를 가져오거나 설정합니다. |

 **Result:**



---


### getFalloff{#getFalloff}

| 이름 | 설명 |
| --- | --- |
| getFalloff() | 감쇠 콘 각도(도)를 가져오거나 설정합니다. |

 **Result:**



---


### setFalloff{#setFalloff}

| 이름 | 설명 |
| --- | --- |
| setFalloff(value) | 감쇠 콘 각도(도)를 가져오거나 설정합니다. |

 **Result:**



---


### getConstantAttenuation{#getConstantAttenuation}

| 이름 | 설명 |
| --- | --- |
| getConstantAttenuation() | 빛의 전체 감쇠를 계산하기 위한 상수 감쇠를 가져오거나 설정합니다. |

 **Result:**



---


### setConstantAttenuation{#setConstantAttenuation}

| 이름 | 설명 |
| --- | --- |
| setConstantAttenuation(value) | 빛의 전체 감쇠를 계산하기 위한 상수 감쇠를 가져오거나 설정합니다. |

 **Result:**



---


### getLinearAttenuation{#getLinearAttenuation}

| 이름 | 설명 |
| --- | --- |
| getLinearAttenuation() | 빛의 전체 감쇠를 계산하기 위한 선형 감쇠를 가져오거나 설정합니다. |

 **Result:**



---


### setLinearAttenuation{#setLinearAttenuation}

| 이름 | 설명 |
| --- | --- |
| setLinearAttenuation(value) | 빛의 전체 감쇠를 계산하기 위한 선형 감쇠를 가져오거나 설정합니다. |

 **Result:**



---


### getQuadraticAttenuation{#getQuadraticAttenuation}

| 이름 | 설명 |
| --- | --- |
| getQuadraticAttenuation() | 빛의 전체 감쇠를 계산하기 위한 2차 감쇠를 가져오거나 설정합니다. |

 **Result:**



---


### setQuadraticAttenuation{#setQuadraticAttenuation}

| 이름 | 설명 |
| --- | --- |
| setQuadraticAttenuation(value) | 빛의 전체 감쇠를 계산하기 위한 2차 감쇠를 가져오거나 설정합니다. |

 **Result:**



---


### getCastShadows{#getCastShadows}

| 이름 | 설명 |
| --- | --- |
| getCastShadows() | 빛이 다른 객체에 그림자를 드리울 수 있는지 여부를 가져오거나 설정합니다. |

 **Result:**



---


### setCastShadows{#setCastShadows}

| 이름 | 설명 |
| --- | --- |
| setCastShadows(value) | 빛이 다른 객체에 그림자를 드리울 수 있는지 여부를 가져오거나 설정합니다. |

 **Result:**



---


### getShadowColor{#getShadowColor}

| 이름 | 설명 |
| --- | --- |
| getShadowColor() | 그림자의 색상을 가져오거나 설정합니다. |

 **Result:**



---


### setShadowColor{#setShadowColor}

| 이름 | 설명 |
| --- | --- |
| setShadowColor(value) | 그림자의 색상을 가져오거나 설정합니다. |

 **Result:**



---


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



