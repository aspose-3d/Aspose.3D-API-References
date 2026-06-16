---
title: "NurbsCurve"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/nurbscurve/
---
## NurbsCurve class

NURBS 曲线是由 NURBS（非均匀有理基样条）表示的曲线。NURBS 曲线由其阶次、加权的 Geometry.ControlPoints 集合以及 KnotVectors 定义。控制点中的 w 分量用作控制点的权重，无论它是 CurveDimension.TWO_DIMENSIONAL 还是 CurveDimension.THREE_DIMENSIONAL。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | 初始化 NurbsCurve 类的新实例。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(name) | 初始化 NurbsCurve 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 名称 |

 **Result:**



---


### getControlPoints{#getControlPoints}

| 名称 | 描述 |
| --- | --- |
| getControlPoints() | 获取所有控制点。 |

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
| getOrder() | 获取或设置 NURBS 曲线的阶数，它定义影响曲线上任意点的邻近控制点的数量。阶数。 |

 **Result:**



---


### setOrder{#setOrder}

| 名称 | 描述 |
| --- | --- |
| setOrder(value) | 获取或设置 NURBS 曲线的阶数，它定义影响曲线上任意点的邻近控制点的数量。阶数。 |

 **Result:**



---


### getDimension{#getDimension}

| 名称 | 描述 |
| --- | --- |
| getDimension() | 获取或设置曲线的维度。该属性的值是 CurveDimension 整数常量。对于 CurveDimension.TWO_DIMENSIONAL 曲线，控制点中的 z 分量未使用。 |

 **Result:**



---


### setDimension{#setDimension}

| 名称 | 描述 |
| --- | --- |
| setDimension(value) | 获取或设置曲线的维度。该属性的值是 CurveDimension 整数常量。对于 CurveDimension.TWO_DIMENSIONAL 曲线，控制点中的 z 分量未使用。 |

 **Result:**



---


### getCurveType{#getCurveType}

| 名称 | 描述 |
| --- | --- |
| getCurveType() | 获取或设置曲线的类型。属性的值是 NurbsType 整数常量。曲线的类型。 |

 **Result:**



---


### setCurveType{#setCurveType}

| 名称 | 描述 |
| --- | --- |
| setCurveType(value) | 获取或设置曲线的类型。属性的值是 NurbsType 整数常量。曲线的类型。 |

 **Result:**



---


### getKnotVectors{#getKnotVectors}

| 名称 | 描述 |
| --- | --- |
| getKnotVectors() | 获取结点向量，它是一系列参数值，决定控制点在 NURBS 曲线上的影响位置和方式。 |

 **Result:**



---


### getRational{#getRational}

| 名称 | 描述 |
| --- | --- |
| getRational() | 获取或设置它是否为有理的，此值指示该 NurbsCurve 是有理样条还是非有理样条。非有理 B-spline 是有理 B-spline 的一种特殊情况。若为有理样条则为 true；否则为 false，表示非有理样条。 |

 **Result:**



---


### setRational{#setRational}

| 名称 | 描述 |
| --- | --- |
| setRational(value) | 获取或设置它是否为有理的，此值指示该 NurbsCurve 是有理样条还是非有理样条。非有理 B-spline 是有理 B-spline 的一种特殊情况。若为有理样条则为 true；否则为 false，表示非有理样条。 |

 **Result:**



---


### getColor{#getColor}

| 名称 | 描述 |
| --- | --- |
| getColor() | 获取或设置线条的颜色，默认值为白色(1, 1, 1)。 |

 **Result:**



---


### setColor{#setColor}

| 名称 | 描述 |
| --- | --- |
| setColor(value) | 获取或设置线条的颜色，默认值为白色(1, 1, 1)。 |

 **Result:**



---


### getParentNodes{#getParentNodes}

| 名称 | 描述 |
| --- | --- |
| getParentNodes() | 获取所有父节点，实体可以附加到多个父节点以实现几何实例化。 |

 **Result:**



---


### getExcluded{#getExcluded}

| 名称 | 描述 |
| --- | --- |
| getExcluded() | 获取或设置在导出期间是否排除此实体。 |

 **Result:**



---


### setExcluded{#setExcluded}

| 名称 | 描述 |
| --- | --- |
| setExcluded(value) | 获取或设置在导出期间是否排除此实体。 |

 **Result:**



---


### getParentNode{#getParentNode}

| 名称 | 描述 |
| --- | --- |
| getParentNode() | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。父节点。 |

 **Result:**



---


### setParentNode{#setParentNode}

| 名称 | 描述 |
| --- | --- |
| setParentNode(value) | 获取或设置第一个父节点，如果设置了第一个父节点，则此实体将从其他父节点分离。父节点。 |

 **Result:**



---


### getScene{#getScene}

| 名称 | 描述 |
| --- | --- |
| getScene() | 获取此对象所属的场景 |

 **Result:**



---


### getName{#getName}

| 名称 | 描述 |
| --- | --- |
| getName() | 获取或设置名称。名称。 |

 **Result:**



---


### setName{#setName}

| 名称 | 描述 |
| --- | --- |
| setName(value) | 获取或设置名称。名称。 |

 **Result:**



---


### getProperties{#getProperties}

| 名称 | 描述 |
| --- | --- |
| getProperties() | 获取所有属性的集合。 |

 **Result:**



---


### evaluate{#evaluate}

| 名称 | 描述 |
| --- | --- |
| evaluate(steps) | 评估 NURBS 曲线 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| steps | 数字 | 两个相邻结点之间的评估频率，默认值为 20 |

 **Result:**
Vector4[]


---


### evaluateAt{#evaluateAt}

| 名称 | 描述 |
| --- | --- |
| evaluateAt(u) | 在指定位置评估曲线的点 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| u | 数字 | 曲线中的位置，介于 0 到 1 之间 |

 **Result:**
Vector4


---


### getEntityRendererKey{#getEntityRendererKey}

| 名称 | 描述 |
| --- | --- |
| getEntityRendererKey() | 获取在渲染器中注册的实体渲染器的键 |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| 名称 | 描述 |
| --- | --- |
| getBoundingBox() | 获取当前实体在其对象空间坐标系中的边界框。 |

 **Result:**
EntityRendererKey


---


### removeProperty{#removeProperty}

| 名称 | 描述 |
| --- | --- |
| removeProperty(property) | 移除动态属性。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| property | Property | 要移除哪个属性 |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| 名称 | 描述 |
| --- | --- |
| removeProperty(property) | 移除按名称标识的指定属性 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| propert | 字符串 | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| 名称 | 描述 |
| --- | --- |
| getProperty(property) | 获取指定属性的值 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| property | 字符串 | 属性名称 |

 **Result:**
对象


---


### setProperty{#setProperty}

| 名称 | 描述 |
| --- | --- |
| setProperty(property, value) | 设置指定属性的值 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| property | 字符串 | 属性名称 |
| 值 | 对象 | 属性的值 |

 **Result:**
对象


---


### findProperty{#findProperty}

| 名称 | 描述 |
| --- | --- |
| findProperty(propertyName) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本机属性（通过其名称标识） |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| propertyName | 字符串 | 属性名称。 |

 **Result:**
Property


---



