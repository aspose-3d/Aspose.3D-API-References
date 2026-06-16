---
title: "四元数"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/quaternion/
---
## Quaternion class

四元数通常用于在计算机图形学中执行旋转。


## 属性

| 名称 | 描述 |
| --- | --- |
| w | 该 w 组件。 |
| x | x 分量。 |
| y | y 分量。 |
| z | z 分量。 |
| 标识 | 单位四元数。 |

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
| constructor_overload(w, x, y, z) | 初始化 Quaternion 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| w | 数字 | 四元数的 w 分量 |
| x | 数字 | 四元数的 x 分量 |
| y | 数字 | 四元数的 y 分量 |
| z | 数字 | 四元数的 z 分量 |

 **Result:**



---


### getLength{#getLength}

| 名称 | 描述 |
| --- | --- |
| getLength() | 获取四元数的长度 |

 **Result:**



---


### equals{#equals}

| 名称 | 描述 |
| --- | --- |
| equals(obj) | 检查两个四元数是否相等 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| obj | 对象 | 用于检查相等性的对象。 |

 **Result:**
boolean


---


### hashCode{#hashCode}

| 名称 | 描述 |
| --- | --- |
| hashCode() | 获取 Quaternion 的哈希码 |

 **Result:**
数字


---


### conjugate{#conjugate}

| 名称 | 描述 |
| --- | --- |
| conjugate() | 返回当前四元数的共轭四元数 |

 **Result:**
四元数


---


### inverse{#inverse}

| 名称 | 描述 |
| --- | --- |
| inverse() | 返回当前四元数的逆四元数 |

 **Result:**
四元数


---


### dot{#dot}

| 名称 | 描述 |
| --- | --- |
| dot(q) | 点积 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| q | 四元数 | 四元数 |

 **Result:**
数字


---


### eulerAngles{#eulerAngles}

| 名称 | 描述 |
| --- | --- |
| eulerAngles() | 将四元数转换为欧拉角表示的旋转，所有分量均为弧度 |

 **Result:**
Vector3


---


### normalize{#normalize}

| 名称 | 描述 |
| --- | --- |
| normalize() | 归一化四元数 |

 **Result:**
四元数


---


### concat{#concat}

| 名称 | 描述 |
| --- | --- |
| concat(rhs) | 连接两个四元数 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| rh | 四元数 | null |

 **Result:**
四元数


---


### fromAngleAxis{#fromAngleAxis}

| 名称 | 描述 |
| --- | --- |
| fromAngleAxis(a, axis) | 围绕给定轴创建四元数并顺时针旋转 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| a | 数字 | 顺时针旋转（弧度） |
| 轴 | Vector3 | 轴 |

 **Result:**
四元数


---


### fromRotation{#fromRotation}

| 名称 | 描述 |
| --- | --- |
| fromRotation(orig, dest) | 创建一个从原始方向旋转到目标方向的四元数 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| orig | Vector3 | 原始方向 |
| dest | Vector3 | 目标方向 |

 **Result:**
四元数


---


### fromEulerAngle{#fromEulerAngle}

| 名称 | 描述 |
| --- | --- |
| fromEulerAngle(pitch, yaw, roll) | 根据给定的欧拉角创建四元数 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pitch | 数字 | 俯仰角（弧度） |
| yaw | 数字 | 偏航角（弧度） |
| 滚动 | 数字 | 以弧度表示的滚动 |

 **Result:**
四元数


---


### fromEulerAngle{#fromEulerAngle}

| 名称 | 描述 |
| --- | --- |
| fromEulerAngle(eulerAngle) | 根据给定的欧拉角创建四元数 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| eulerAngle | Vector3 | 欧拉角（弧度） |

 **Result:**
四元数


---


### toMatrix{#toMatrix}

| 名称 | 描述 |
| --- | --- |
| toMatrix() | 将四元数表示的旋转转换为变换矩阵。 |

 **Result:**
Matrix4


---


### toString{#toString}

| 名称 | 描述 |
| --- | --- |
| toString() | 获取四元数的字符串表示 |

 **Result:**
字符串


---


### interpolate{#interpolate}

| 名称 | 描述 |
| --- | --- |
| interpolate(t, from, to) | 在 t 介于 from 和 to 之间时，用给定四元数参数之间的插值填充此四元数。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| t | 数字 | 用于插值的系数。 |
| from | 四元数 | 源四元数。 |
| to | 四元数 | 目标四元数。 |

 **Result:**
四元数


---



