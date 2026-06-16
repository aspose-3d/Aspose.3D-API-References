---
title: "BoundingBox"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/boundingbox/
---
## BoundingBox class

轴对齐包围盒


## 属性

| 名称 | 描述 |
| --- | --- |
| NULL | 空的边界框 |
| INFINITE | 无限的边界框 |

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
| constructor_overload(minimum, maximum) | 使用给定的最小角和最大角初始化有限的边界框 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| minimum | Vector3 | 最小角 |
| maximum | Vector3 | 最大角 |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名称 | 描述 |
| --- | --- |
| constructor_overload2(minX, minY, minZ, maxX, maxY, maxZ) | 使用给定的最小角和最大角初始化有限的边界框 |

 **Result:**



---


### getExtent{#getExtent}

| 名称 | 描述 |
| --- | --- |
| getExtent() | 获取边界框的范围。该属性的值是 BoundingBoxExtent 整数常量。 |

 **Result:**



---


### getMinimum{#getMinimum}

| 名称 | 描述 |
| --- | --- |
| getMinimum() | 边界框的最小角 |

 **Result:**



---


### getMaximum{#getMaximum}

| 名称 | 描述 |
| --- | --- |
| getMaximum() | 边界框的最大角 |

 **Result:**



---


### getSize{#getSize}

| 名称 | 描述 |
| --- | --- |
| getSize() | 边界框的大小 |

 **Result:**



---


### getCenter{#getCenter}

| 名称 | 描述 |
| --- | --- |
| getCenter() | 边界框的中心。 |

 **Result:**



---


### fromGeometry{#fromGeometry}

| 名称 | 描述 |
| --- | --- |
| fromGeometry(geometry) | 根据给定的几何体构建边界框 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| geometr | 几何 | null |

 **Result:**
BoundingBox


---


### toString{#toString}

| 名称 | 描述 |
| --- | --- |
| toString() | 获取边界框的字符串表示形式。 |

 **Result:**
字符串


---


### hashCode{#hashCode}

| 名称 | 描述 |
| --- | --- |
| hashCode() | 返回此实例的哈希码 |

 **Result:**
数字


---


### equals{#equals}

| 名称 | 描述 |
| --- | --- |
| equals(obj) | 确定两个对象是否相等 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| ob | 对象 | null |

 **Result:**
boolean


---



