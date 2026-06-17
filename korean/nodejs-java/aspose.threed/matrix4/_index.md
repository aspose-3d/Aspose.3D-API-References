---
title: "Matrix4"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/matrix4/
---
## Matrix4 class

4x4 행렬 구현.


## Properties

| 이름 | 설명 |
| --- | --- |
| m00 | m00 값. |
| m01 | m01 값. |
| m02 | m02 값. |
| m03 | m03 값. |
| m10 | m10 값. |
| m11 | m11 값. |
| m12 | 그 m12. |
| m13 | 그 m13. |
| m20 | 그 m20. |
| m21 | 그 m21. |
| m22 | 그 m22. |
| m23 | 그 m23. |
| m30 | 그 m30. |
| m31 | 그 m31. |
| m32 | 그 m32. |
| m33 | 그 m33. |

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
| constructor_overload(r0, r1, r2, r3) | 4개의 행으로부터 행렬을 구성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| r0 | Vector4 | R0. |
| r1 | Vector4 | R1. |
| r2 | Vector4 | R2. |
| r3 | Vector4 | R3. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 이름 | 설명 |
| --- | --- |
| constructor_overload2(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Matrix4 구조체의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| m00 | 숫자 | M00. |
| m01 | 숫자 | M01. |
| m02 | 숫자 | M02. |
| m03 | 숫자 | M03. |
| m10 | 숫자 | M10. |
| m11 | 숫자 | M11. |
| m12 | 숫자 | M12. |
| m13 | 숫자 | M13. |
| m20 | 숫자 | M20. |
| m21 | 숫자 | M21. |
| m22 | 숫자 | M22. |
| m23 | 숫자 | M23. |
| m30 | 숫자 | M30. |
| m31 | 숫자 | M31. |
| m32 | 숫자 | M32. |
| m33 | 숫자 | M33. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| 이름 | 설명 |
| --- | --- |
| constructor_overload3(m) | FMatrix4 인스턴스로부터 Matrix4를 구성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
|  | FMatrix4 | null |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| 이름 | 설명 |
| --- | --- |
| constructor_overload4(m) | Matrix4 구조체의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| m | Number[] | M. |

 **Result:**



---


### getIdentity{#getIdentity}

| 이름 | 설명 |
| --- | --- |
| getIdentity() | 단위 행렬을 가져옵니다. 단위 행렬. |

 **Result:**



---


### getDeterminant{#getDeterminant}

| 이름 | 설명 |
| --- | --- |
| getDeterminant() | 행렬의 행렬식을 가져옵니다. 행렬식. |

 **Result:**



---


### concatenate{#concatenate}

| 이름 | 설명 |
| --- | --- |
| concatenate(m2) | 두 행렬을 연결합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

 **Result:**
Matrix4


---


### transpose{#transpose}

| 이름 | 설명 |
| --- | --- |
| transpose() | 이 인스턴스를 전치합니다. |

 **Result:**
Matrix4


---


### normalize{#normalize}

| 이름 | 설명 |
| --- | --- |
| normalize() | 이 인스턴스를 정규화합니다. |

 **Result:**
Matrix4


---


### inverse{#inverse}

| 이름 | 설명 |
| --- | --- |
| inverse() | 이 인스턴스를 역행렬로 변환합니다. |

 **Result:**
Matrix4


---


### setTRS{#setTRS}

| 이름 | 설명 |
| --- | --- |
| setTRS(translation, rotation, scale) | 행렬을 변환/회전/스케일로 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 변환 | Vector3 | 변환. |
| 회전 | Vector3 | 회전을 위한 오일러 각도, 필드는 도 단위입니다. |
| 스케일 | Vector3 | 스케일. |

 **Result:**
Matrix4


---


### toArray{#toArray}

| 이름 | 설명 |
| --- | --- |
| toArray() | 행렬을 배열로 변환합니다. |

 **Result:**
Number[]


---


### toString{#toString}

| 이름 | 설명 |
| --- | --- |
| toString() | 현재 Matrix4를 나타내는 java.lang.String을 반환합니다. |

 **Result:**
String


---


### translate{#translate}

| 이름 | 설명 |
| --- | --- |
| translate(t) | x축, y축 및 z축을 따라 변환하는 행렬을 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| t | Vector3 | 변환 오프셋 |

 **Result:**
Matrix4


---


### translate{#translate}

| 이름 | 설명 |
| --- | --- |
| translate(tx, ty, tz) | x축, y축 및 z축을 따라 변환하는 행렬을 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| tx | 숫자 | X 좌표 오프셋 |
| ty | 숫자 | Y 좌표 오프셋 |
| tz | 숫자 | Z 좌표 오프셋 |

 **Result:**
Matrix4


---


### scale{#scale}

| 이름 | 설명 |
| --- | --- |
| scale(s) | x축, y축 및 z축을 따라 스케일링하는 행렬을 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| s | Vector3 | 스케일링 팩터리는 x축, y축 및 z축에 적용됩니다. |

 **Result:**
Matrix4


---


### scale{#scale}

| 이름 | 설명 |
| --- | --- |
| scale(s) | x축, y축 및 z축을 따라 스케일링하는 행렬을 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| s | 숫자 | 스케일링 팩터리는 모든 축에 적용됩니다. |

 **Result:**
Matrix4


---


### scale{#scale}

| 이름 | 설명 |
| --- | --- |
| scale(sx, sy, sz) | x축, y축 및 z축을 따라 스케일링하는 행렬을 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| sx | 숫자 | 스케일링 팩터리는 x축에 적용됩니다. |
| sy | 숫자 | 스케일링 팩터리는 y축에 적용됩니다. |
| sz | 숫자 | 스케일링 팩터리는 z축에 적용됩니다. |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| 이름 | 설명 |
| --- | --- |
| rotateFromEuler(eul) | Euler 각도에서 회전 행렬을 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| eul | Vector3 | 라디안 단위 회전 |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| 이름 | 설명 |
| --- | --- |
| rotateFromEuler(rx, ry, rz) | Euler 각도에서 회전 행렬을 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| rx | 숫자 | x축에 대한 라디안 단위 회전 |
| ry | 숫자 | y축에 대한 라디안 단위 회전 |
| rz | 숫자 | z 축의 회전 (라디안) |

 **Result:**
Matrix4


---


### rotate{#rotate}

| 이름 | 설명 |
| --- | --- |
| rotate(angle, axis) | 회전 각도와 축을 사용하여 회전 행렬을 생성합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| angle | 숫자 | 라디안 단위 회전 각도 |
| axis | Vector3 | 회전 축 |

 **Result:**
Matrix4


---


### rotate{#rotate}

| 이름 | 설명 |
| --- | --- |
| rotate(q) | 쿼터니언으로부터 회전 행렬을 생성합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| q | Quaternion | 회전 쿼터니언 |

 **Result:**
Matrix4


---



