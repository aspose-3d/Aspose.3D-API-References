---
title: "Vector3"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/vector3/
---
## Vector3 class

具有三个分量的向量。


## 属性

| 名称 | 描述 |
| --- | --- |
| x | x 分量。 |
| y | y 分量。 |
| z | z 分量。 |
| ORIGIN | 获取原点位置。原点。 |
| UNIT_SCALE | 获取单位缩放向量。 |
| X_AXIS | 获取 X 轴。 X 轴。 |
| Y_AXIS | 获取 Y 轴。 Y 轴。 |
| Z_AXIS | 获取 Z 轴。 Z 轴。 |

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
| constructor_overload(x, y, z) | 初始化 Vector3 结构的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| x | 数字 | x 坐标。 |
| y | 数字 | y 坐标。 |
| z | 数字 | z 坐标。 |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名称 | 描述 |
| --- | --- |
| constructor_overload2(vec) | 初始化 Vector3 结构的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| vec | FVector3 | x 坐标。 |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| 名称 | 描述 |
| --- | --- |
| constructor_overload3(v) | 初始化 Vector3 结构的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| v | 数字 | V. |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| 名称 | 描述 |
| --- | --- |
| constructor_overload4(vec4) | 初始化 Vector3 结构的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| vec4 | Vector4 | Vec4. |

 **Result:**



---


### getLength2{#getLength2}

| 名称 | 描述 |
| --- | --- |
| getLength2() | 获取长度的平方。 length2。 |

 **Result:**



---


### getLength{#getLength}

| 名称 | 描述 |
| --- | --- |
| getLength() | 获取此向量的长度。长度。 |

 **Result:**



---


### equals{#equals}

| 名称 | 描述 |
| --- | --- |
| equals(obj) | 检查两个 vector3 是否相等 |

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
| hashCode() | 获取 Vector3 的哈希码 |

 **Result:**
数字


---


### dot{#dot}

| 名称 | 描述 |
| --- | --- |
| dot(rhs) | 获取两个向量的点积 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| rhs | Vector3 | 右侧值。 |

 **Result:**
数字


---


### normalize{#normalize}

| 名称 | 描述 |
| --- | --- |
| normalize() | 对该实例进行归一化。 |

 **Result:**
Vector3


---


### sin{#sin}

| 名称 | 描述 |
| --- | --- |
| sin() | 计算每个分量的正弦 |

 **Result:**
Vector3


---


### cos{#cos}

| 名称 | 描述 |
| --- | --- |
| cos() | 计算每个分量的余弦 |

 **Result:**
Vector3


---


### cross{#cross}

| 名称 | 描述 |
| --- | --- |
| cross(rhs) | 两个向量的叉积 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| rhs | Vector3 | 右侧值。 |

 **Result:**
Vector3


---


### set{#set}

| 名称 | 描述 |
| --- | --- |
| set(newX, newY, newZ) | 一次调用设置 x/y/z 分量。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| newX | 数字 | x 分量。 |
| newY | 数字 | y 分量。 |
| newZ | 数字 | z 分量。 |

 **Result:**
Vector3


---


### toString{#toString}

| 名称 | 描述 |
| --- | --- |
| toString() | 返回一个 java.lang.String，表示当前的 Vector3。 |

 **Result:**
字符串


---


### angleBetween{#angleBetween}

| 名称 | 描述 |
| --- | --- |
| angleBetween(dir, up) | 计算两个方向之间的内部角度。两个方向可以是非归一化的向量。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| dir | Vector3 | 用于比较的方向向量 |
| up | Vector3 | 两个方向共享平面的上向量 |

 **Result:**
数字


---


### angleBetween{#angleBetween}

| 名称 | 描述 |
| --- | --- |
| angleBetween(dir) | 计算两个方向之间的内部角度。两个方向可以是非归一化的向量。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| dir | Vector3 | 用于比较的方向向量 |

 **Result:**
数字


---


### compareTo{#compareTo}

| 名称 | 描述 |
| --- | --- |
| compareTo(other) | 将当前向量与另一个实例进行比较。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| othe | Vector3 | null |

 **Result:**
数字


---



