---
title: "Matrix4"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/matrix4/
---
## Matrix4 class

4x4 矩阵实现。


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
| constructor_overload(r0, r1, r2, r3) | 从 4 行构造矩阵。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| r0 | Vector4 | R0. |
| r1 | Vector4 | R1. |
| r2 | Vector4 | R2. |
| r3 | Vector4 | R3. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名称 | 描述 |
| --- | --- |
| constructor_overload2(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | 初始化 Matrix4 结构的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| m00 | 数字 | M00. |
| m01 | 数字 | M01. |
| m02 | 数字 | M02. |
| m03 | 数字 | M03. |
| m10 | 数字 | M10. |
| m11 | 数字 | M11. |
| m12 | 数字 | M12. |
| m13 | 数字 | M13. |
| m20 | 数字 | M20. |
| m21 | 数字 | M21. |
| m22 | 数字 | M22. |
| m23 | 数字 | M23. |
| m30 | 数字 | M30. |
| m31 | 数字 | M31. |
| m32 | 数字 | M32. |
| m33 | 数字 | M33. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| 名称 | 描述 |
| --- | --- |
| constructor_overload3(m) | 从 FMatrix4 实例构建 Matrix4。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
|  | FMatrix4 | null |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| 名称 | 描述 |
| --- | --- |
| constructor_overload4(m) | 初始化 Matrix4 结构的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| m | Number[] | M. |

 **Result:**



---


### getIdentity{#getIdentity}

| 名称 | 描述 |
| --- | --- |
| getIdentity() | 获取单位矩阵。单位矩阵。 |

 **Result:**



---


### getDeterminant{#getDeterminant}

| 名称 | 描述 |
| --- | --- |
| getDeterminant() | 获取矩阵的行列式。行列式。 |

 **Result:**



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
Matrix4


---


### transpose{#transpose}

| 名称 | 描述 |
| --- | --- |
| transpose() | 转置此实例。 |

 **Result:**
Matrix4


---


### normalize{#normalize}

| 名称 | 描述 |
| --- | --- |
| normalize() | 对该实例进行归一化。 |

 **Result:**
Matrix4


---


### inverse{#inverse}

| 名称 | 描述 |
| --- | --- |
| inverse() | 对该实例求逆。 |

 **Result:**
Matrix4


---


### setTRS{#setTRS}

| 名称 | 描述 |
| --- | --- |
| setTRS(translation, rotation, scale) | 使用平移/旋转/缩放初始化矩阵 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 平移 | Vector3 | 平移。 |
| 旋转 | Vector3 | 用于旋转的欧拉角，字段的单位为度。 |
| 缩放 | Vector3 | 缩放。 |

 **Result:**
Matrix4


---


### toArray{#toArray}

| 名称 | 描述 |
| --- | --- |
| toArray() | 将矩阵转换为数组。 |

 **Result:**
Number[]


---


### toString{#toString}

| 名称 | 描述 |
| --- | --- |
| toString() | 返回一个表示当前 Matrix4 的 java.lang.String。 |

 **Result:**
字符串


---


### translate{#translate}

| 名称 | 描述 |
| --- | --- |
| translate(t) | 创建一个沿 x 轴、y 轴和 z 轴平移的矩阵 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| t | Vector3 | 平移偏移 |

 **Result:**
Matrix4


---


### translate{#translate}

| 名称 | 描述 |
| --- | --- |
| translate(tx, ty, tz) | 创建一个沿 x 轴、y 轴和 z 轴平移的矩阵 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| tx | 数字 | X 坐标偏移 |
| ty | 数字 | Y 坐标偏移 |
| tz | 数字 | Z 坐标偏移 |

 **Result:**
Matrix4


---


### scale{#scale}

| 名称 | 描述 |
| --- | --- |
| scale(s) | 创建一个在 x 轴、y 轴和 z 轴上进行缩放的矩阵。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| s | Vector3 | 缩放因子适用于 x 轴、y 轴和 z 轴 |

 **Result:**
Matrix4


---


### scale{#scale}

| 名称 | 描述 |
| --- | --- |
| scale(s) | 创建一个在 x 轴、y 轴和 z 轴上进行缩放的矩阵。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| s | 数字 | 缩放因子适用于所有轴 |

 **Result:**
Matrix4


---


### scale{#scale}

| 名称 | 描述 |
| --- | --- |
| scale(sx, sy, sz) | 创建一个在 x 轴、y 轴和 z 轴上进行缩放的矩阵。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sx | 数字 | 缩放因子适用于 x 轴 |
| sy | 数字 | 缩放因子适用于 y 轴 |
| sz | 数字 | 缩放因子适用于 z 轴 |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| 名称 | 描述 |
| --- | --- |
| rotateFromEuler(eul) | 从欧拉角创建旋转矩阵 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| eul | Vector3 | 弧度制旋转 |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| 名称 | 描述 |
| --- | --- |
| rotateFromEuler(rx, ry, rz) | 从欧拉角创建旋转矩阵 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| rx | 数字 | x 轴的弧度制旋转 |
| ry | 数字 | y 轴的弧度制旋转 |
| rz | 数字 | z 轴的旋转（弧度） |

 **Result:**
Matrix4


---


### rotate{#rotate}

| 名称 | 描述 |
| --- | --- |
| rotate(angle, axis) | 通过旋转角度和轴创建旋转矩阵 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | 数字 | 旋转角度（弧度） |
| 轴 | Vector3 | 旋转轴 |

 **Result:**
Matrix4


---


### rotate{#rotate}

| 名称 | 描述 |
| --- | --- |
| rotate(q) | 从四元数创建旋转矩阵 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| q | 四元数 | 旋转四元数 |

 **Result:**
Matrix4


---



