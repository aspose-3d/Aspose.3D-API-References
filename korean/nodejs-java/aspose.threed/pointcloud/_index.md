---
title: "PointCloud"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/pointcloud/
---
## PointCloud class

포인트 클라우드에는 토폴로지 정보가 없고 제어점과 정점 요소만 포함됩니다.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor(name) | PointCloud의 생성자 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 이 엔터티의 이름 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload() | PointCloud의 생성자 |

 **Result:**



---


### getVisible{#getVisible}

| 이름 | 설명 |
| --- | --- |
| getVisible() | 지오메트리가 보이는지 가져오거나 설정합니다. |

 **Result:**



---


### setVisible{#setVisible}

| 이름 | 설명 |
| --- | --- |
| setVisible(value) | 지오메트리가 보이는지 가져오거나 설정합니다. |

 **Result:**



---


### getDeformers{#getDeformers}

| 이름 | 설명 |
| --- | --- |
| getDeformers() | 이 지오메트리와 연결된 모든 디포머를 가져옵니다. 디포머. |

 **Result:**



---


### getControlPoints{#getControlPoints}

| 이름 | 설명 |
| --- | --- |
| getControlPoints() | 모든 제어점을 가져옵니다. |

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


### getVertexElements{#getVertexElements}

| 이름 | 설명 |
| --- | --- |
| getVertexElements() | 모든 정점 요소를 가져옵니다. |

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


### getEntityRendererKey{#getEntityRendererKey}

| 이름 | 설명 |
| --- | --- |
| getEntityRendererKey() | 렌더러에 등록된 엔터티 렌더러의 키를 가져옵니다. |

 **Result:**
EntityRendererKey


---


### fromGeometry{#fromGeometry}

| 이름 | 설명 |
| --- | --- |
| fromGeometry(g) | 지오메트리 객체에서 새로운 PointCloud 인스턴스를 생성합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
|  | Geometry | null |

 **Result:**
PointCloud


---


### fromGeometry{#fromGeometry}

| 이름 | 설명 |
| --- | --- |
| fromGeometry(g, density) | 지오메트리 객체에서 새로운 포인트 클라우드 인스턴스를 생성합니다. 밀도는 단위 삼각형당 포인트 수를 의미합니다(단위 삼각형은 메시에서 최대 표면적을 가진 삼각형입니다). |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| g | Geometry | Mesh 또는 기타 지오메트리 인스턴스 |
| density | 숫자 | 단위 삼각형당 포인트 수 |

 **Result:**
PointCloud


---


### getElement{#getElement}

| 이름 | 설명 |
| --- | --- |
| getElement(type) | 지정된 타입의 정점 요소를 가져옵니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### getVertexElementOfUV{#getVertexElementOfUV}

| 이름 | 설명 |
| --- | --- |
| getVertexElementOfUV(textureMapping) | 주어진 텍스처 매핑 타입으로 VertexElementUV 인스턴스를 가져옵니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| textureMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElement{#createElement}

| 이름 | 설명 |
| --- | --- |
| createElement(type) | 지정된 타입의 정점 요소를 생성하고 이를 지오메트리에 추가합니다. 타입이 VertexElementType.UV인 경우, TextureMapping.DIFFUSE 타입의 텍스처 매핑을 가진 VertexElementUV가 생성됩니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### addElement{#addElement}

| 이름 | 설명 |
| --- | --- |
| addElement(element) | 기존 정점 요소를 현재 지오메트리에 추가합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| element | VertexElement | 추가할 정점 요소 |

 **Result:**
VertexElement


---


### createElement{#createElement}

| 이름 | 설명 |
| --- | --- |
| createElement(type, mappingMode, referenceMode) | 지정된 타입의 정점 요소를 생성하고 이를 지오메트리에 추가합니다. 타입이 VertexElementType.UV인 경우, TextureMapping.DIFFUSE 타입의 텍스처 매핑을 가진 VertexElementUV가 생성됩니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElement


---


### createElementUV{#createElementUV}

| 이름 | 설명 |
| --- | --- |
| createElementUV(uvMapping) | 주어진 텍스처 매핑 유형으로 VertexElementUV를 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElementUV{#createElementUV}

| 이름 | 설명 |
| --- | --- |
| createElementUV(uvMapping, mappingMode, referenceMode) | 주어진 텍스처 매핑 유형으로 VertexElementUV를 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElementUV


---


### getBoundingBox{#getBoundingBox}

| 이름 | 설명 |
| --- | --- |
| getBoundingBox() | 현재 엔터티의 객체 공간 좌표계에서 경계 상자를 가져옵니다. |

 **Result:**
VertexElementUV


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



