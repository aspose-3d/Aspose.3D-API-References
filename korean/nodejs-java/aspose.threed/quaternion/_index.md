---
title: "Quaternion"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/quaternion/
---
## Quaternion class

Quaternion은 일반적으로 컴퓨터 그래픽스에서 회전을 수행하는 데 사용됩니다.


## Properties

| 이름 | 설명 |
| --- | --- |
| w | w 구성 요소입니다. |
| x | x 구성 요소. |
| y | y 구성 요소. |
| z | z 구성 요소. |
| IDENTITY | 단위 사원수. |

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
| constructor_overload(w, x, y, z) | Quaternion 클래스의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| w | 숫자 | 사원수의 w 구성 요소 |
| x | 숫자 | 사원수의 x 구성 요소 |
| y | 숫자 | 사원수의 y 구성 요소 |
| z | 숫자 | 사원수의 z 구성 요소 |

 **Result:**



---


### getLength{#getLength}

| 이름 | 설명 |
| --- | --- |
| getLength() | 사원수의 길이를 가져옵니다 |

 **Result:**



---


### equals{#equals}

| 이름 | 설명 |
| --- | --- |
| equals(obj) | 두 사원수가 같은지 확인합니다 |

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
| hashCode() | Quaternion의 해시 코드를 가져옵니다 |

 **Result:**
숫자


---


### conjugate{#conjugate}

| 이름 | 설명 |
| --- | --- |
| conjugate() | 현재 사원수의 켤레 사원수를 반환합니다 |

 **Result:**
Quaternion


---


### inverse{#inverse}

| 이름 | 설명 |
| --- | --- |
| inverse() | 현재 사원수의 역 사원수를 반환합니다 |

 **Result:**
Quaternion


---


### dot{#dot}

| 이름 | 설명 |
| --- | --- |
| dot(q) | 점곱 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| q | Quaternion | 쿼터니언 |

 **Result:**
숫자


---


### eulerAngles{#eulerAngles}

| 이름 | 설명 |
| --- | --- |
| eulerAngles() | 쿼터니언을 오일러 각으로 표현된 회전으로 변환합니다. 모든 구성 요소는 라디안 단위입니다. |

 **Result:**
Vector3


---


### normalize{#normalize}

| 이름 | 설명 |
| --- | --- |
| normalize() | 쿼터니언을 정규화합니다. |

 **Result:**
Quaternion


---


### concat{#concat}

| 이름 | 설명 |
| --- | --- |
| concat(rhs) | 두 개의 쿼터니언을 연결합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| rh | Quaternion | null |

 **Result:**
Quaternion


---


### fromAngleAxis{#fromAngleAxis}

| 이름 | 설명 |
| --- | --- |
| fromAngleAxis(a, axis) | 주어진 축을 중심으로 시계 방향으로 회전하는 쿼터니언을 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| a | 숫자 | 시계 방향 회전 (라디안) |
| axis | Vector3 | 축 |

 **Result:**
Quaternion


---


### fromRotation{#fromRotation}

| 이름 | 설명 |
| --- | --- |
| fromRotation(orig, dest) | 원래 방향에서 목적지 방향으로 회전하는 쿼터니언을 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| orig | Vector3 | 원래 방향 |
| dest | Vector3 | 목적지 방향 |

 **Result:**
Quaternion


---


### fromEulerAngle{#fromEulerAngle}

| 이름 | 설명 |
| --- | --- |
| fromEulerAngle(pitch, yaw, roll) | 주어진 오일러 각으로부터 쿼터니언을 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| pitch | 숫자 | 피치 (라디안) |
| yaw | 숫자 | 요 (라디안) |
| 롤 | 숫자 | 라디안 단위 롤 |

 **Result:**
Quaternion


---


### fromEulerAngle{#fromEulerAngle}

| 이름 | 설명 |
| --- | --- |
| fromEulerAngle(eulerAngle) | 주어진 오일러 각으로부터 쿼터니언을 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| eulerAngle | Vector3 | 라디안 단위 Euler 각 |

 **Result:**
Quaternion


---


### toMatrix{#toMatrix}

| 이름 | 설명 |
| --- | --- |
| toMatrix() | 쿼터니언으로 표현된 회전을 변환 행렬로 변환합니다. |

 **Result:**
Matrix4


---


### toString{#toString}

| 이름 | 설명 |
| --- | --- |
| toString() | 쿼터니언을 문자열로 표현한 값을 가져옵니다 |

 **Result:**
String


---


### interpolate{#interpolate}

| 이름 | 설명 |
| --- | --- |
| interpolate(t, from, to) | 주어진 quaternion 인수들 사이에서 t가 from와 to 사이일 때, 이 quaternion을 보간된 값으로 채웁니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| t | 숫자 | 보간에 사용할 계수. |
| from | Quaternion | 소스 quaternion. |
| to | Quaternion | 대상 quaternion. |

 **Result:**
Quaternion


---



