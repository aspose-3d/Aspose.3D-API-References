---
title: "실린더"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/cylinder/
---
## Cylinder class

매개변수화된 실린더. radiusTop 또는 radiusBottom 중 하나가 0일 때 원뿔을 나타내는 데에도 사용할 수 있습니다.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() | Cylinder 클래스의 새 인스턴스를 초기화합니다. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload(radius, height) | Cylinder 클래스의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 반경 | 숫자 | 상단 및 하단 캡의 반지름. |
| height | 숫자 | 높이. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 이름 | 설명 |
| --- | --- |
| constructor_overload2(radiusTop, radiusBottom, height) | Cylinder 클래스의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| radiusTop | 숫자 | 상단 반지름. |
| radiusBottom | 숫자 | 하단 반지름. |
| height | 숫자 | 높이. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| 이름 | 설명 |
| --- | --- |
| constructor_overload3(radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded) | Cylinder 클래스의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| radiusTop | 숫자 | 실린더 상단 캡의 반지름. |
| radiusBottom | 숫자 | 실린더 하단 캡의 반지름. |
| height | 숫자 | 실린더의 높이. |
| radialSegments | 숫자 | 상단 및 하단 원의 방사형 세그먼트.. |
| heightSegments | 숫자 | 세로 세그먼트. |
| openEnded | boolean | 설정된 경우 |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| 이름 | 설명 |
| --- | --- |
| constructor_overload4(name, radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded, thetaStart, thetaLength) | Cylinder 클래스의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 이 객체의 이름 |
| radiusTop | 숫자 | 실린더 상단 캡의 반지름. |
| radiusBottom | 숫자 | 실린더 하단 캡의 반지름. |
| height | 숫자 | 실린더의 높이. |
| radialSegments | 숫자 | 상단 및 하단 원의 방사형 세그먼트.. |
| heightSegments | 숫자 | 세로 세그먼트. |
| openEnded | boolean | 설정된 경우 |
| thetaStart | 숫자 | Theta 시작. |
| thetaLength | 숫자 | Theta 길이. |

 **Result:**



---


### getOffsetBottom{#getOffsetBottom}

| 이름 | 설명 |
| --- | --- |
| getOffsetBottom() | 하단 측면의 정점 변환 오프셋을 가져오거나 설정합니다. |

 **Result:**



---


### setOffsetBottom{#setOffsetBottom}

| 이름 | 설명 |
| --- | --- |
| setOffsetBottom(value) | 하단 측면의 정점 변환 오프셋을 가져오거나 설정합니다. |

 **Result:**



---


### getOffsetTop{#getOffsetTop}

| 이름 | 설명 |
| --- | --- |
| getOffsetTop() | 상단 측면의 정점 변환 오프셋을 가져오거나 설정합니다. |

 **Result:**



---


### setOffsetTop{#setOffsetTop}

| 이름 | 설명 |
| --- | --- |
| setOffsetTop(value) | 상단 측면의 정점 변환 오프셋을 가져오거나 설정합니다. |

 **Result:**



---


### getGenerateFanCylinder{#getGenerateFanCylinder}

| 이름 | 설명 |
| --- | --- |
| getGenerateFanCylinder() | ThetaLength가 2PI보다 작을 때 팬 스타일 실린더를 생성할지 여부를 가져오거나 설정합니다. 그렇지 않으면 모델이 잘리지 않습니다. |

 **Result:**



---


### setGenerateFanCylinder{#setGenerateFanCylinder}

| 이름 | 설명 |
| --- | --- |
| setGenerateFanCylinder(value) | ThetaLength가 2PI보다 작을 때 팬 스타일 실린더를 생성할지 여부를 가져오거나 설정합니다. 그렇지 않으면 모델이 잘리지 않습니다. |

 **Result:**



---


### getShearBottom{#getShearBottom}

| 이름 | 설명 |
| --- | --- |
| getShearBottom() | 하단 측면의 전단 변환을 가져오거나 설정합니다. 벡터는 라디안으로 측정된 (x축, z축) 전단 값을 저장하며, 기본값은 (0, 0)입니다. |

 **Result:**



---


### setShearBottom{#setShearBottom}

| 이름 | 설명 |
| --- | --- |
| setShearBottom(value) | 하단 측면의 전단 변환을 가져오거나 설정합니다. 벡터는 라디안으로 측정된 (x축, z축) 전단 값을 저장하며, 기본값은 (0, 0)입니다. |

 **Result:**



---


### getShearTop{#getShearTop}

| 이름 | 설명 |
| --- | --- |
| getShearTop() | 상단 측면의 전단 변환을 가져오거나 설정합니다. 벡터는 라디안으로 측정된 (x축, z축) 전단 값을 저장하며, 기본값은 (0, 0)입니다. |

 **Result:**



---


### setShearTop{#setShearTop}

| 이름 | 설명 |
| --- | --- |
| setShearTop(value) | 상단 측면의 전단 변환을 가져오거나 설정합니다. 벡터는 라디안으로 측정된 (x축, z축) 전단 값을 저장하며, 기본값은 (0, 0)입니다. |

 **Result:**



---


### getRadiusTop{#getRadiusTop}

| 이름 | 설명 |
| --- | --- |
| getRadiusTop() | 실린더 상단 캡의 반경을 가져오거나 설정합니다. 상단 캡의 반경입니다. |

 **Result:**



---


### setRadiusTop{#setRadiusTop}

| 이름 | 설명 |
| --- | --- |
| setRadiusTop(value) | 실린더 상단 캡의 반경을 가져오거나 설정합니다. 상단 캡의 반경입니다. |

 **Result:**



---


### getRadiusBottom{#getRadiusBottom}

| 이름 | 설명 |
| --- | --- |
| getRadiusBottom() | 실린더 하단 캡의 반경을 가져오거나 설정합니다. 하단 캡의 반경입니다. |

 **Result:**



---


### setRadiusBottom{#setRadiusBottom}

| 이름 | 설명 |
| --- | --- |
| setRadiusBottom(value) | 실린더 하단 캡의 반경을 가져오거나 설정합니다. 하단 캡의 반경입니다. |

 **Result:**



---


### getHeight{#getHeight}

| 이름 | 설명 |
| --- | --- |
| getHeight() | 실린더의 높이를 가져오거나 설정합니다. 높이입니다. |

 **Result:**



---


### setHeight{#setHeight}

| 이름 | 설명 |
| --- | --- |
| setHeight(value) | 실린더의 높이를 가져오거나 설정합니다. 높이입니다. |

 **Result:**



---


### getRadialSegments{#getRadialSegments}

| 이름 | 설명 |
| --- | --- |
| getRadialSegments() | 방사형 세그먼트를 가져오거나 설정합니다. 방사형 세그먼트입니다. |

 **Result:**



---


### setRadialSegments{#setRadialSegments}

| 이름 | 설명 |
| --- | --- |
| setRadialSegments(value) | 방사형 세그먼트를 가져오거나 설정합니다. 방사형 세그먼트입니다. |

 **Result:**



---


### getHeightSegments{#getHeightSegments}

| 이름 | 설명 |
| --- | --- |
| getHeightSegments() | 세로 세그먼트를 가져오거나 설정합니다. 세로 세그먼트. |

 **Result:**



---


### setHeightSegments{#setHeightSegments}

| 이름 | 설명 |
| --- | --- |
| setHeightSegments(value) | 세로 세그먼트를 가져오거나 설정합니다. 세로 세그먼트. |

 **Result:**



---


### getOpenEnded{#getOpenEnded}

| 이름 | 설명 |
| --- | --- |
| getOpenEnded() | 이 실린더가 개방형인지 여부를 나타내는 값을 가져오거나 설정합니다. 기본값은 false이며, 개방형이면 true; 그렇지 않으면 상단/하단 캡이 존재합니다. |

 **Result:**



---


### setOpenEnded{#setOpenEnded}

| 이름 | 설명 |
| --- | --- |
| setOpenEnded(value) | 이 실린더가 개방형인지 여부를 나타내는 값을 가져오거나 설정합니다. 기본값은 false이며, 개방형이면 true; 그렇지 않으면 상단/하단 캡이 존재합니다. |

 **Result:**



---


### getThetaStart{#getThetaStart}

| 이름 | 설명 |
| --- | --- |
| getThetaStart() | Theta 시작값을 가져오거나 설정합니다. 기본값은 0이며, Theta 시작값입니다. |

 **Result:**



---


### setThetaStart{#setThetaStart}

| 이름 | 설명 |
| --- | --- |
| setThetaStart(value) | Theta 시작값을 가져오거나 설정합니다. 기본값은 0이며, Theta 시작값입니다. |

 **Result:**



---


### getThetaLength{#getThetaLength}

| 이름 | 설명 |
| --- | --- |
| getThetaLength() | Theta 길이를 가져오거나 설정합니다. 기본값은 2π이며, Theta 길이입니다. |

 **Result:**



---


### setThetaLength{#setThetaLength}

| 이름 | 설명 |
| --- | --- |
| setThetaLength(value) | Theta 길이를 가져오거나 설정합니다. 기본값은 2π이며, Theta 길이입니다. |

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



