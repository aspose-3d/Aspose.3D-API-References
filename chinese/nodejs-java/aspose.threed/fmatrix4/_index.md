---
title: "FMatrix4"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/fmatrix4/
---
## FMatrix4 class

矩阵 4x4，所有分量为 float 类型


## 属性

| 名称 | 描述 |
| --- | --- |
| m00 | 该 m00。 |
| m01 | 该 m01。 |
| m02 | 该 m02。 |
| m03 | 该 m03。 |
| m10 | 该 m10。 |
| m11 | 该 m11。 |
| m12 | 此 m12。 |
| m13 | 此 m13。 |
| m20 | 此 m20。 |
| m21 | 此 m21。 |
| m22 | 此 m22。 |
| m23 | 此 m23。 |
| m30 | 此 m30。 |
| m31 | 此 m31。 |
| m32 | 此 m32。 |
| m33 | 此 m33。 |
| 标识 | 该单位矩阵 |

## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | 初始化 FMatrix4 的实例 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| m0 | 数字 | null |
| m0 | 数字 | null |
| m0 | 数字 | null |
| m0 | 数字 | null |
| m1 | 数字 | null |
| m1 | 数字 | null |
| m1 | 数字 | null |
| m1 | 数字 | null |
| m2 | 数字 | null |
| m2 | 数字 | null |
| m2 | 数字 | null |
| m2 | 数字 | null |
| m3 | 数字 | null |
| m3 | 数字 | null |
| m3 | 数字 | null |
| m3 | 数字 | null |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名称 | 描述 |
| --- | --- |
| constructor_overload2(mat) | 从 Matrix4 实例初始化 FMatrix4 实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| ma | Matrix4 | null |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| 名称 | 描述 |
| --- | --- |
| constructor_overload3(r0, r1, r2, r3) | 从 4 行构造矩阵。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| r0 | FVector4 | R0. |
| r1 | FVector4 | R1. |
| r2 | FVector4 | R2. |
| r3 | FVector4 | R3. |

 **Result:**



---


### concatenate{#concatenate}

| 名称 | 描述 |
| --- | --- |
| concatenate(m2) | 连接两个矩阵 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| m2 | FMatrix4 | M2. |

 **Result:**
FMatrix4


---


### concatenate{#concatenate}

| 名称 | 描述 |
| --- | --- |
| concatenate(m2) | 连接两个矩阵 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

 **Result:**
FMatrix4


---


### transpose{#transpose}

| 名称 | 描述 |
| --- | --- |
| transpose() | 转置此实例。 |

 **Result:**
FMatrix4


---


### inverse{#inverse}

| 名称 | 描述 |
| --- | --- |
| inverse() | 计算当前实例的逆矩阵。 |

 **Result:**
FMatrix4


---



