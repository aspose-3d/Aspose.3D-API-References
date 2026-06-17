---
title: "TransformBuilder"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/transformbuilder/
---
## TransformBuilder class

TransformBuilder는 일련의 변환을 통해 변환 행렬을 구축하는 데 사용됩니다.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor(initial, order) | 초기 변환 행렬과 지정된 합성 순서를 사용하여 TransformBuilder를 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| initia | Matrix4 | null |
| order | ComposeOrder | ComposeOrder |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload(order) | 초기 단위 변환 행렬과 지정된 합성 순서를 사용하여 TransformBuilder를 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| order | ComposeOrder | ComposeOrder |

 **Result:**



---


### getMatrix{#getMatrix}

| 이름 | 설명 |
| --- | --- |
| getMatrix() | 현재 행렬 값을 가져오거나 설정합니다. |

 **Result:**



---


### setMatrix{#setMatrix}

| 이름 | 설명 |
| --- | --- |
| setMatrix(value) | 현재 행렬 값을 가져오거나 설정합니다. |

 **Result:**



---


### getComposeOrder{#getComposeOrder}

| 이름 | 설명 |
| --- | --- |
| getComposeOrder() | 체인 합성 순서를 가져오거나 설정합니다. 이 속성의 값은 ComposeOrder 정수 상수입니다. |

 **Result:**



---


### setComposeOrder{#setComposeOrder}

| 이름 | 설명 |
| --- | --- |
| setComposeOrder(value) | 체인 합성 순서를 가져오거나 설정합니다. 이 속성의 값은 ComposeOrder 정수 상수입니다. |

 **Result:**



---


### compose{#compose}

| 이름 | 설명 |
| --- | --- |
| compose(m) | 인수(argument)를 내부 행렬에 추가하거나 앞에 삽입합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### append{#append}

| 이름 | 설명 |
| --- | --- |
| append(m) | 새 변환 행렬을 변환 체인에 추가합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### prepend{#prepend}

| 이름 | 설명 |
| --- | --- |
| prepend(m) | 새 변환 행렬을 변환 체인 앞에 추가합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### rearrange{#rearrange}

| 이름 | 설명 |
| --- | --- |
| rearrange(newX, newY, newZ) | 축의 레이아웃을 재배열합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| newX | 축 | 축 |
| newY | 축 | 축 |
| newZ | 축 | 축 |

 **Result:**



---


### scale{#scale}

| 이름 | 설명 |
| --- | --- |
| scale(s) | 구성 요소가 s로 스케일된 스케일 변환 행렬을 연결합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
|  | 숫자 | null |

 **Result:**



---


### scale{#scale}

| 이름 | 설명 |
| --- | --- |
| scale(x, y, z) | 스케일 변환 행렬을 연결합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
|  | 숫자 | null |
|  | 숫자 | null |
|  | 숫자 | null |

 **Result:**



---


### scale{#scale}

| 이름 | 설명 |
| --- | --- |
| scale(s) | 스케일 변환을 연결합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### rotateDegree{#rotateDegree}

| 이름 | 설명 |
| --- | --- |
| rotateDegree(angle, axis) | 각도 단위 회전 변환을 연결합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| angle | 숫자 | 도 단위 회전 각도 |
| axis | Vector3 | 회전할 축 |

 **Result:**



---


### rotateRadian{#rotateRadian}

| 이름 | 설명 |
| --- | --- |
| rotateRadian(angle, axis) | 라디안 단위 회전 변환을 연결합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| angle | 숫자 | 라디안 단위 회전 각도 |
| axis | Vector3 | 회전할 축 |

 **Result:**



---


### rotate{#rotate}

| 이름 | 설명 |
| --- | --- |
| rotate(q) | 쿼터니언으로 회전을 연결합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
|  | Quaternion | null |

 **Result:**



---


### rotateEulerDegree{#rotateEulerDegree}

| 이름 | 설명 |
| --- | --- |
| rotateEulerDegree(degX, degY, degZ) | 도 단위 오일러 각도로 회전을 연결합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| deg | 숫자 | null |
| deg | 숫자 | null |
| deg | 숫자 | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| 이름 | 설명 |
| --- | --- |
| rotateEulerRadian(x, y, z) | 라디안 단위 오일러 각도로 회전을 연결합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
|  | 숫자 | null |
|  | 숫자 | null |
|  | 숫자 | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| 이름 | 설명 |
| --- | --- |
| rotateEulerRadian(r) | 라디안 단위 오일러 각도로 회전을 연결합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### translate{#translate}

| 이름 | 설명 |
| --- | --- |
| translate(tx, ty, tz) | 이동 변환을 연결합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| t | 숫자 | null |
| t | 숫자 | null |
| t | 숫자 | null |

 **Result:**



---


### translate{#translate}

| 이름 | 설명 |
| --- | --- |
| translate(v) | 이동 변환을 연결합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### reset{#reset}

| 이름 | 설명 |
| --- | --- |
| reset() | 변환을 단위 행렬로 재설정합니다 |

 **Result:**



---


### rotateDegree{#rotateDegree}

| 이름 | 설명 |
| --- | --- |
| rotateDegree(rot, order) | 지정된 순서로 회전을 추가합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| rot | Vector3 | 도 단위 회전 |
| order | RotationOrder | RotationOrder |

 **Result:**



---


### rotateRadian{#rotateRadian}

| 이름 | 설명 |
| --- | --- |
| rotateRadian(rot, order) | 지정된 순서로 회전을 추가합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| rot | Vector3 | 라디안 단위 회전 |
| order | RotationOrder | RotationOrder |

 **Result:**



---



