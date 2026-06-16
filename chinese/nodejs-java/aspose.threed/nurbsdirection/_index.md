---
title: "NurbsDirection"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/nurbsdirection/
---
## NurbsDirection class

3D NurbsSurface 有两个方向，NurbsSurface.U 和 NurbsSurface.V，NurbsDirection 为每个方向定义数据。方向实际上是一条 NURBS 曲线，这意味着它也由阶次、KnotVectors 和一组加权控制点（在 NurbsSurface 中定义）决定。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getKnotVectors{#getKnotVectors}

| 名称 | 描述 |
| --- | --- |
| getKnotVectors() | 获取结点向量，它是一系列参数值，决定控制点在 NURBS 曲线上的影响位置和方式。 |

 **Result:**



---


### getMultiplicity{#getMultiplicity}

| 名称 | 描述 |
| --- | --- |
| getMultiplicity() | 获取多重性。多重性。 |

 **Result:**



---


### getOrder{#getOrder}

| 名称 | 描述 |
| --- | --- |
| getOrder() | 获取或设置 NURBS 曲线的阶数，它定义了影响曲线上任意点的邻近控制点的数量。 |

 **Result:**



---


### setOrder{#setOrder}

| 名称 | 描述 |
| --- | --- |
| setOrder(value) | 获取或设置 NURBS 曲线的阶数，它定义了影响曲线上任意点的邻近控制点的数量。 |

 **Result:**



---


### getDivisions{#getDivisions}

| 名称 | 描述 |
| --- | --- |
| getDivisions() | 获取或设置当前方向上相邻控制点之间的划分数量。步长。 |

 **Result:**



---


### setDivisions{#setDivisions}

| 名称 | 描述 |
| --- | --- |
| setDivisions(value) | 获取或设置当前方向上相邻控制点之间的划分数量。步长。 |

 **Result:**



---


### getType{#getType}

| 名称 | 描述 |
| --- | --- |
| getType() | 获取或设置当前方向的类型。属性的值是 NurbsType 整数常量。 |

 **Result:**



---


### setType{#setType}

| 名称 | 描述 |
| --- | --- |
| setType(value) | 获取或设置当前方向的类型。属性的值是 NurbsType 整数常量。 |

 **Result:**



---


### getCount{#getCount}

| 名称 | 描述 |
| --- | --- |
| getCount() | 获取或设置当前方向的控制点数量。计数。 |

 **Result:**



---


### setCount{#setCount}

| 名称 | 描述 |
| --- | --- |
| setCount(value) | 获取或设置当前方向的控制点数量。计数。 |

 **Result:**



---



