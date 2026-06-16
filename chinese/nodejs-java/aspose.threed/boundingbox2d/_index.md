---
title: "BoundingBox2D"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/boundingbox2d/
---
## BoundingBox2D class

Vector2 的轴对齐包围盒


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
| minimum | Vector2 | 最小角 |
| maximum | Vector2 | 最大角 |

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


### merge{#merge}

| 名称 | 描述 |
| --- | --- |
| merge(pt) | 将新盒子合并到当前边界框中。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| p | Vector2 | null |

 **Result:**



---


### merge{#merge}

| 名称 | 描述 |
| --- | --- |
| merge(bb) | 将新盒子合并到当前边界框中。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| b | BoundingBox2D | null |

 **Result:**



---


### toString{#toString}

| 名称 | 描述 |
| --- | --- |
| toString() | 获取边界框的字符串表示形式。 |

 **Result:**
字符串


---



