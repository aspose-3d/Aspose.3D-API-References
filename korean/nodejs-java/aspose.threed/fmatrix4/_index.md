---
title: "FMatrix4"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/fmatrix4/
---
## FMatrix4 class

모든 구성 요소가 float 타입인 4x4 행렬


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
| IDENTITY | 그 단위 행렬 |

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
| constructor_overload(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | FMatrix4의 인스턴스를 초기화합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| m0 | 숫자 | null |
| m0 | 숫자 | null |
| m0 | 숫자 | null |
| m0 | 숫자 | null |
| m1 | 숫자 | null |
| m1 | 숫자 | null |
| m1 | 숫자 | null |
| m1 | 숫자 | null |
| m2 | 숫자 | null |
| m2 | 숫자 | null |
| m2 | 숫자 | null |
| m2 | 숫자 | null |
| m3 | 숫자 | null |
| m3 | 숫자 | null |
| m3 | 숫자 | null |
| m3 | 숫자 | null |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 이름 | 설명 |
| --- | --- |
| constructor_overload2(mat) | Matrix4 인스턴스로부터 FMatrix4 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| ma | Matrix4 | null |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| 이름 | 설명 |
| --- | --- |
| constructor_overload3(r0, r1, r2, r3) | 4개의 행으로부터 행렬을 구성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| r0 | FVector4 | R0. |
| r1 | FVector4 | R1. |
| r2 | FVector4 | R2. |
| r3 | FVector4 | R3. |

 **Result:**



---


### concatenate{#concatenate}

| 이름 | 설명 |
| --- | --- |
| concatenate(m2) | 두 행렬을 연결합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| m2 | FMatrix4 | M2. |

 **Result:**
FMatrix4


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
FMatrix4


---


### transpose{#transpose}

| 이름 | 설명 |
| --- | --- |
| transpose() | 이 인스턴스를 전치합니다. |

 **Result:**
FMatrix4


---


### inverse{#inverse}

| 이름 | 설명 |
| --- | --- |
| inverse() | 현재 인스턴스의 역행렬을 계산합니다. |

 **Result:**
FMatrix4


---



