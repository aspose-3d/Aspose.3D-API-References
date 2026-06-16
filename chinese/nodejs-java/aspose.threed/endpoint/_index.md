---
title: "EndPoint"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/endpoint/
---
## EndPoint class

用于修剪曲线的终点，可以是参数值或笛卡尔点。


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
| constructor_overload(point) | 从笛卡尔点构造一个 EndPoint。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| poin | Vector3 | null |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名称 | 描述 |
| --- | --- |
| constructor_overload2(v) | 从实数参数构造一个 EndPoint。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
|  | 数字 | null |

 **Result:**



---


### isCartesianPoint{#isCartesianPoint}

| 名称 | 描述 |
| --- | --- |
| isCartesianPoint() | 该端点是笛卡尔点吗？ |

 **Result:**



---


### getAsPoint{#getAsPoint}

| 名称 | 描述 |
| --- | --- |
| getAsPoint() | 获取端点作为笛卡尔坐标点，或抛出异常。 |

 **Result:**



---


### getAsValue{#getAsValue}

| 名称 | 描述 |
| --- | --- |
| getAsValue() | 获取端点作为实数参数，或抛出异常。 |

 **Result:**



---


### fromDegree{#fromDegree}

| 名称 | 描述 |
| --- | --- |
| fromDegree(degree) | 创建以度数衡量的端点。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 度 | 数字 | null |

 **Result:**
EndPoint


---


### fromRadian{#fromRadian}

| 名称 | 描述 |
| --- | --- |
| fromRadian(degree) | 创建以弧度衡量的端点。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 度 | 数字 | null |

 **Result:**
EndPoint


---


### toString{#toString}

| 名称 | 描述 |
| --- | --- |
| toString() | 返回当前端点的字符串表示。 |

 **Result:**
字符串


---



