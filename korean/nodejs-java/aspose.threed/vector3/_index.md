---
title: "Vector3"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/vector3/
---
## Vector3 class

세 개의 구성 요소를 가진 벡터.


## Properties

| 이름 | 설명 |
| --- | --- |
| x | x 구성 요소. |
| y | y 구성 요소. |
| z | z 구성 요소. |
| ORIGIN | 원점 위치를 가져옵니다. 원점. |
| UNIT_SCALE | 단위 스케일 벡터를 가져옵니다. |
| X_AXIS | X 축을 가져옵니다. X 축. |
| Y_AXIS | Y 축을 가져옵니다. Y 축. |
| Z_AXIS | Z 축을 가져옵니다. Z 축. |

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
| constructor_overload(x, y, z) | Vector3 구조체의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| x | 숫자 | x 좌표. |
| y | 숫자 | y 좌표. |
| z | 숫자 | z 좌표. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 이름 | 설명 |
| --- | --- |
| constructor_overload2(vec) | Vector3 구조체의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| vec | FVector3 | x 좌표. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| 이름 | 설명 |
| --- | --- |
| constructor_overload3(v) | Vector3 구조체의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| v | 숫자 | V. |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| 이름 | 설명 |
| --- | --- |
| constructor_overload4(vec4) | Vector3 구조체의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| vec4 | Vector4 | Vec4. |

 **Result:**



---


### getLength2{#getLength2}

| 이름 | 설명 |
| --- | --- |
| getLength2() | 길이의 제곱을 가져옵니다. length2. |

 **Result:**



---


### getLength{#getLength}

| 이름 | 설명 |
| --- | --- |
| getLength() | 이 벡터의 길이를 가져옵니다. 길이. |

 **Result:**



---


### equals{#equals}

| 이름 | 설명 |
| --- | --- |
| equals(obj) | 두 vector3가 같은지 확인합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| obj | Object | 동등성을 확인할 객체입니다. |

 **Result:**
boolean


---


### hashCode{#hashCode}

| 이름 | 설명 |
| --- | --- |
| hashCode() | Vector3의 해시 코드를 가져옵니다 |

 **Result:**
숫자


---


### dot{#dot}

| 이름 | 설명 |
| --- | --- |
| dot(rhs) | 두 벡터의 내적을 가져옵니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| rhs | Vector3 | 우변 값입니다. |

 **Result:**
숫자


---


### normalize{#normalize}

| 이름 | 설명 |
| --- | --- |
| normalize() | 이 인스턴스를 정규화합니다. |

 **Result:**
Vector3


---


### sin{#sin}

| 이름 | 설명 |
| --- | --- |
| sin() | 각 구성 요소에 대한 사인 값을 계산합니다 |

 **Result:**
Vector3


---


### cos{#cos}

| 이름 | 설명 |
| --- | --- |
| cos() | 각 구성 요소에 대한 코사인 값을 계산합니다 |

 **Result:**
Vector3


---


### cross{#cross}

| 이름 | 설명 |
| --- | --- |
| cross(rhs) | 두 벡터의 외적 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| rhs | Vector3 | 우변 값입니다. |

 **Result:**
Vector3


---


### set{#set}

| 이름 | 설명 |
| --- | --- |
| set(newX, newY, newZ) | 한 번의 호출로 x/y/z 구성 요소를 설정합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| newX | 숫자 | x 구성 요소. |
| newY | 숫자 | y 구성 요소. |
| newZ | 숫자 | z 구성 요소. |

 **Result:**
Vector3


---


### toString{#toString}

| 이름 | 설명 |
| --- | --- |
| toString() | 현재 Vector3를 나타내는 java.lang.String을 반환합니다. |

 **Result:**
String


---


### angleBetween{#angleBetween}

| 이름 | 설명 |
| --- | --- |
| angleBetween(dir, up) | 두 방향 사이의 내부 각도를 계산합니다. 두 방향은 정규화되지 않은 벡터일 수 있습니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| dir | Vector3 | 비교할 방향 벡터 |
| up | Vector3 | 두 방향이 공유하는 평면의 up 벡터 |

 **Result:**
숫자


---


### angleBetween{#angleBetween}

| 이름 | 설명 |
| --- | --- |
| angleBetween(dir) | 두 방향 사이의 내부 각도를 계산합니다. 두 방향은 정규화되지 않은 벡터일 수 있습니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| dir | Vector3 | 비교할 방향 벡터 |

 **Result:**
숫자


---


### compareTo{#compareTo}

| 이름 | 설명 |
| --- | --- |
| compareTo(other) | 현재 벡터를 다른 인스턴스와 비교합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| othe | Vector3 | null |

 **Result:**
숫자


---



