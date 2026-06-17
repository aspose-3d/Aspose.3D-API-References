---
title: "EndPoint"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/endpoint/
---
## EndPoint class

곡선을 자를 끝점으로, 매개변수 값이거나 직교 좌표점일 수 있습니다.


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
| constructor_overload(point) | 데카르트 좌표점을 사용하여 EndPoint를 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| poin | Vector3 | null |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 이름 | 설명 |
| --- | --- |
| constructor_overload2(v) | 실수 매개변수를 사용하여 EndPoint를 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
|  | 숫자 | null |

 **Result:**



---


### isCartesianPoint{#isCartesianPoint}

| 이름 | 설명 |
| --- | --- |
| isCartesianPoint() | 끝점이 데카르트 좌표점인가요? |

 **Result:**



---


### getAsPoint{#getAsPoint}

| 이름 | 설명 |
| --- | --- |
| getAsPoint() | 끝점을 직교 좌표점으로 가져오고, 예외를 발생시킵니다. |

 **Result:**



---


### getAsValue{#getAsValue}

| 이름 | 설명 |
| --- | --- |
| getAsValue() | 끝점을 실수 매개변수로 가져오고, 예외를 발생시킵니다. |

 **Result:**



---


### fromDegree{#fromDegree}

| 이름 | 설명 |
| --- | --- |
| fromDegree(degree) | 각도로 측정된 끝점을 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| degre | 숫자 | null |

 **Result:**
EndPoint


---


### fromRadian{#fromRadian}

| 이름 | 설명 |
| --- | --- |
| fromRadian(degree) | 라디안으로 측정된 끝점을 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| degre | 숫자 | null |

 **Result:**
EndPoint


---


### toString{#toString}

| 이름 | 설명 |
| --- | --- |
| toString() | 현재 끝점의 문자열 표현을 반환합니다. |

 **Result:**
String


---



