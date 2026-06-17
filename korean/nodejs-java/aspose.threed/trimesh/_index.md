---
title: "TriMesh"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/trimesh/
---
## TriMesh class

TriMesh는 GPU에서 직접 사용할 수 있는 원시 데이터를 포함합니다. 이 클래스는 정점당 데이터만 포함하는 메쉬를 구성하는 데 도움이 되는 유틸리티입니다.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor(name, declaration) | TriMesh 인스턴스를 초기화합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 이 TriMesh의 이름 |
| declaration | VertexDeclaration | 버텍스 선언 |

 **Result:**



---


### getVertexDeclaration{#getVertexDeclaration}

| 이름 | 설명 |
| --- | --- |
| getVertexDeclaration() | TriMesh의 버텍스 레이아웃. |

 **Result:**



---


### getVerticesCount{#getVerticesCount}

| 이름 | 설명 |
| --- | --- |
| getVerticesCount() | 이 TriMesh의 버텍스 개수 |

 **Result:**



---


### getIndicesCount{#getIndicesCount}

| 이름 | 설명 |
| --- | --- |
| getIndicesCount() | 이 TriMesh의 인덱스 수 |

 **Result:**



---


### getUnmergedVerticesCount{#getUnmergedVerticesCount}

| 이름 | 설명 |
| --- | --- |
| getUnmergedVerticesCount() | beginVertex()와 endVertex()에 의해 전달된 병합되지 않은 정점의 수. |

 **Result:**



---


### getCapacity{#getCapacity}

| 이름 | 설명 |
| --- | --- |
| getCapacity() | 미리 할당된 정점의 용량. |

 **Result:**



---


### getVerticesSizeInBytes{#getVerticesSizeInBytes}

| 이름 | 설명 |
| --- | --- |
| getVerticesSizeInBytes() | 모든 정점의 총 크기(바이트 단위) |

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


### fromMesh{#fromMesh}

| 이름 | 설명 |
| --- | --- |
| fromMesh(declaration, mesh) | 주어진 메시 객체와 지정된 정점 레이아웃으로 TriMesh를 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |
| mes | Mesh | null |

 **Result:**
TriMesh


---


### copyFrom{#copyFrom}

| 이름 | 설명 |
| --- | --- |
| copyFrom(input, vd) | 새 정점 레이아웃을 사용하여 입력에서 TriMesh를 복사합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| input | TriMesh | 복사를 위한 입력 TriMesh |
| vd | VertexDeclaration | 출력 TriMesh의 새로운 정점 선언 |

 **Result:**
TriMesh


---


### fromMesh{#fromMesh}

| 이름 | 설명 |
| --- | --- |
| fromMesh(mesh, useFloat) | 주어진 메시 객체에서 TriMesh를 생성하며, 정점 선언은 입력 메시의 구조를 기반으로 합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| mes | Mesh | null |
| useFloat | boolean | 각 정점 요소 구성 요소에 대해 double 대신 float 타입을 사용합니다. |

 **Result:**
TriMesh


---


### beginVertex{#beginVertex}

| 이름 | 설명 |
| --- | --- |
| beginVertex() | 정점 추가 시작 |

 **Result:**
정점


---


### endVertex{#endVertex}

| 이름 | 설명 |
| --- | --- |
| endVertex() | 정점 추가 종료 |

 **Result:**
정점


---


### verticesToArray{#verticesToArray}

| 이름 | 설명 |
| --- | --- |
| verticesToArray() | 정점 데이터를 바이트 배열로 변환합니다 |

 **Result:**
byte[]


---


### toString{#toString}

| 이름 | 설명 |
| --- | --- |
| toString() |  |

 **Result:**
String


---


### fromRawData{#fromRawData}

| 이름 | 설명 |
| --- | --- |
| fromRawData(vd, vertices, indices, generateVertexMapping) | 원시 데이터에서 TriMesh를 생성합니다. 반환된 TriMesh는 성능을 위해 입력 바이트 배열을 복사하지 않으며, 배열에 대한 외부 변경이 이 인스턴스에 반영됩니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| vd | VertexDeclaration | 정점 선언은 최소 하나의 필드를 포함해야 합니다. |
| vertices | byte[] | 입력 정점 데이터이며, 정점 배열의 최소 길이는 정점 선언 크기보다 크거나 같아야 합니다. |
| 인덱스 | Number[] | 삼각형 인덱스 |
| generateVertexMapping | boolean | 생성 |

 **Result:**
TriMesh


---


### loadVerticesFromBytes{#loadVerticesFromBytes}

| 이름 | 설명 |
| --- | --- |
| loadVerticesFromBytes(verticesInBytes) | 바이트에서 정점을 로드합니다. 바이트 길이는 정점 크기의 정수 배여야 합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| verticesInByte | byte[] | null |

 **Result:**
TriMesh


---


### readVector4{#readVector4}

| 이름 | 설명 |
| --- | --- |
| readVector4(idx, field) | vector4 필드를 읽습니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| idx | 숫자 | 읽을 정점의 인덱스 |
| field | VertexField | Vector4/FVector4 데이터 타입을 가진 필드 |

 **Result:**
Vector4


---


### readFVector4{#readFVector4}

| 이름 | 설명 |
| --- | --- |
| readFVector4(idx, field) | vector4 필드를 읽습니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| idx | 숫자 | 읽을 정점의 인덱스 |
| field | VertexField | Vector4/FVector4 데이터 타입을 가진 필드 |

 **Result:**
FVector4


---


### readVector3{#readVector3}

| 이름 | 설명 |
| --- | --- |
| readVector3(idx, field) | vector3 필드를 읽습니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| idx | 숫자 | 읽을 정점의 인덱스 |
| field | VertexField | Vector3/FVector3 데이터 유형을 가진 필드 |

 **Result:**
Vector3


---


### readFVector3{#readFVector3}

| 이름 | 설명 |
| --- | --- |
| readFVector3(idx, field) | vector3 필드를 읽습니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| idx | 숫자 | 읽을 정점의 인덱스 |
| field | VertexField | Vector3/FVector3 데이터 유형을 가진 필드 |

 **Result:**
FVector3


---


### readVector2{#readVector2}

| 이름 | 설명 |
| --- | --- |
| readVector2(idx, field) | vector2 필드를 읽습니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| idx | 숫자 | 읽을 정점의 인덱스 |
| field | VertexField | Vector2/FVector2 데이터 유형을 가진 필드 |

 **Result:**
Vector2


---


### readFVector2{#readFVector2}

| 이름 | 설명 |
| --- | --- |
| readFVector2(idx, field) | vector2 필드를 읽습니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| idx | 숫자 | 읽을 정점의 인덱스 |
| field | VertexField | Vector2/FVector2 데이터 유형을 가진 필드 |

 **Result:**
FVector2


---


### readDouble{#readDouble}

| 이름 | 설명 |
| --- | --- |
| readDouble(idx, field) | double 필드를 읽습니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| idx | 숫자 | 읽을 정점의 인덱스 |
| field | VertexField | float/double 호환 데이터 유형을 가진 필드 |

 **Result:**
숫자


---


### readFloat{#readFloat}

| 이름 | 설명 |
| --- | --- |
| readFloat(idx, field) | float 필드를 읽습니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| idx | 숫자 | 읽을 정점의 인덱스 |
| field | VertexField | float/double 호환 데이터 유형을 가진 필드 |

 **Result:**
숫자


---


### getBoundingBox{#getBoundingBox}

| 이름 | 설명 |
| --- | --- |
| getBoundingBox() | 현재 엔터티의 객체 공간 좌표계에서 경계 상자를 가져옵니다. |

 **Result:**
숫자


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


### iterator{#iterator}

| 이름 | 설명 |
| --- | --- |
| iterator() | 내부 사용을 위해 예약되었습니다. |

 **Result:**
속성


---



