---
title: "VertexDeclaration"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/vertexdeclaration/
---
## VertexDeclaration class

사용자 정의 정점 구조의 선언


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getSealed{#getSealed}

| 이름 | 설명 |
| --- | --- |
| getSealed() | VertexDeclaration은 com.aspose.threed.TriMesh`1 또는 TriMesh에 사용된 경우 봉인되며, 더 이상 수정할 수 없습니다. |

 **Result:**



---


### getCount{#getCount}

| 이름 | 설명 |
| --- | --- |
| getCount() | 이 VertexDeclaration에 정의된 모든 필드의 개수를 가져옵니다. |

 **Result:**



---


### getSize{#getSize}

| 이름 | 설명 |
| --- | --- |
| getSize() | 버텍스 구조의 바이트 단위 크기입니다. |

 **Result:**



---


### get{#get}

| 이름 | 설명 |
| --- | --- |
| get(index) |  |

 **Result:**



---


### clear{#clear}

| 이름 | 설명 |
| --- | --- |
| clear() | 모든 필드를 지웁니다. |

 **Result:**



---


### addField{#addField}

| 이름 | 설명 |
| --- | --- |
| addField(dataType, semantic, index, alias) | 새 버텍스 필드를 추가합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| dataType | 숫자 | VertexFieldDataType |
| semantic | VertexFieldSemantic | VertexFieldSemantic |
| 인덱스 | 숫자 | 동일 필드 의미에 대한 인덱스이며, -1은 자동 생성입니다. |
| alias | String | 필드의 별칭 이름 |

 **Result:**



---


### fromGeometry{#fromGeometry}

| 이름 | 설명 |
| --- | --- |
| fromGeometry(geometry, useFloat) | Geometry 레이아웃을 기반으로 VertexDeclaration을 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| geometr | Geometry | null |
| useFloat | boolean | double 타입 대신 float를 사용합니다. |

 **Result:**
VertexDeclaration


---


### compareTo{#compareTo}

| 이름 | 설명 |
| --- | --- |
| compareTo(other) | 이 인스턴스를 지정된 객체와 비교하고 그 상대값에 대한 표시를 반환합니다. |

 **Result:**
VertexDeclaration


---


### toString{#toString}

| 이름 | 설명 |
| --- | --- |
| toString() |  |

 **Result:**
String


---


### hashCode{#hashCode}

| 이름 | 설명 |
| --- | --- |
| hashCode() |  |

 **Result:**
숫자


---


### equals{#equals}

| 이름 | 설명 |
| --- | --- |
| equals(obj) | 이 인스턴스와 지정된 객체(또한 VertexDeclaration 객체여야 함)가 동일한 값을 갖는지 여부를 결정합니다. |

 **Result:**
숫자


---


### iterator{#iterator}

| 이름 | 설명 |
| --- | --- |
| iterator() | 내부 사용을 위해 예약되었습니다. |

 **Result:**
숫자


---



