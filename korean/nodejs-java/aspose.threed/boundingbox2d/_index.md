---
title: "BoundingBox2D"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/boundingbox2d/
---
## BoundingBox2D class

Vector2에 대한 축 정렬 경계 상자


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
| minimum | Vector2 | 최소 코너 |
| maximum | Vector2 | 최대 코너 |

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


### merge{#merge}

| 이름 | 설명 |
| --- | --- |
| merge(pt) | 새 상자를 현재 경계 상자에 병합합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| p | Vector2 | null |

 **Result:**



---


### merge{#merge}

| 이름 | 설명 |
| --- | --- |
| merge(bb) | 새 상자를 현재 경계 상자에 병합합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| b | BoundingBox2D | null |

 **Result:**



---


### toString{#toString}

| 이름 | 설명 |
| --- | --- |
| toString() | 경계 상자의 문자열 표현을 가져옵니다. |

 **Result:**
String


---



