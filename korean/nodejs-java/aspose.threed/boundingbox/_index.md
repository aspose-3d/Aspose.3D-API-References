---
title: "BoundingBox"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/boundingbox/
---
## BoundingBox class

축 정렬 경계 상자


## Properties

| 이름 | 설명 |
| --- | --- |
| NULL | null 경계 상자 |
| INFINITE | 무한 경계 상자 |

## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload(minimum, maximum) | 주어진 최소 및 최대 코너로 유한 경계 상자를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| minimum | Vector3 | 최소 코너 |
| maximum | Vector3 | 최대 코너 |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 이름 | 설명 |
| --- | --- |
| constructor_overload2(minX, minY, minZ, maxX, maxY, maxZ) | 주어진 최소 및 최대 코너로 유한 경계 상자를 초기화합니다. |

 **Result:**



---


### getExtent{#getExtent}

| 이름 | 설명 |
| --- | --- |
| getExtent() | 경계 상자의 범위를 가져옵니다. 해당 속성의 값은 BoundingBoxExtent 정수 상수입니다. |

 **Result:**



---


### getMinimum{#getMinimum}

| 이름 | 설명 |
| --- | --- |
| getMinimum() | 경계 상자의 최소 코너 |

 **Result:**



---


### getMaximum{#getMaximum}

| 이름 | 설명 |
| --- | --- |
| getMaximum() | 경계 상자의 최대 코너 |

 **Result:**



---


### getSize{#getSize}

| 이름 | 설명 |
| --- | --- |
| getSize() | 경계 상자의 크기 |

 **Result:**



---


### getCenter{#getCenter}

| 이름 | 설명 |
| --- | --- |
| getCenter() | 경계 상자의 중심. |

 **Result:**



---


### fromGeometry{#fromGeometry}

| 이름 | 설명 |
| --- | --- |
| fromGeometry(geometry) | 주어진 기하학으로부터 경계 상자를 구성합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| geometr | Geometry | null |

 **Result:**
BoundingBox


---


### toString{#toString}

| 이름 | 설명 |
| --- | --- |
| toString() | 경계 상자의 문자열 표현을 가져옵니다. |

 **Result:**
String


---


### hashCode{#hashCode}

| 이름 | 설명 |
| --- | --- |
| hashCode() | 이 인스턴스의 해시 코드를 반환합니다 |

 **Result:**
숫자


---


### equals{#equals}

| 이름 | 설명 |
| --- | --- |
| equals(obj) | 두 객체가 같은지 판단합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| ob | Object | null |

 **Result:**
boolean


---



