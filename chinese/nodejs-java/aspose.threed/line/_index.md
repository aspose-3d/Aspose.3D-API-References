---
title: "Line"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/line/
---
## Line class

折线是由 Geometry.ControlPoints 定义的一组点构成的路径，并通过 Segments 连接，这意味着它也可以是一组相连的线段。线通常是线性对象，意味着它不能用于表示曲线，如需表示曲线，请使用 NurbsCurve。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | 初始化 Line 类的新实例。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(name) | 初始化 Line 类的新实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 名称。 |

 **Result:**



---


### getControlPoints{#getControlPoints}

| 名称 | 描述 |
| --- | --- |
| getControlPoints() | 获取所有控制点。 |

 **Result:**



---


### getVisible{#getVisible}

| 名称 | 描述 |
| --- | --- |
| getVisible() | 获取或设置几何体的可见性。 |

 **Result:**



---


### setVisible{#setVisible}

| 名称 | 描述 |
| --- | --- |
| setVisible(value) | 获取或设置几何体的可见性。 |

 **Result:**



---


### getSegments{#getSegments}

| 名称 | 描述 |
| --- | --- |
| getSegments() | 获取该线的段。 |

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


### fromPoints{#fromPoints}

| 名称 | 描述 |
| --- | --- |
| fromPoints(points) | 从一组点构造一个 Line 实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 点 | Vector3[] | null |

 **Result:**
Line


---


### makeDefaultIndices{#makeDefaultIndices}

| 名称 | 描述 |
| --- | --- |
| makeDefaultIndices() | 生成序列 0,1,2,3....Geometry.ControlPoints.Length-1 到 Segments，以便将 ControlPoints 用作单行 |

 **Result:**
Line


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



