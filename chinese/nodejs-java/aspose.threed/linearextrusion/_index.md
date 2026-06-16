---
title: "LinearExtrusion"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/linearextrusion/
---
## LinearExtrusion class

线性拉伸以二维形状为输入，并在第三维度上扩展该形状。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | LinearExtrusion 实例的构造函数。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(shape, height) | LinearExtrusion 实例的构造函数。 |

 **Result:**



---


### getShape{#getShape}

| 名称 | 描述 |
| --- | --- |
| getShape() | 要挤出的基础形状。 |

 **Result:**



---


### setShape{#setShape}

| 名称 | 描述 |
| --- | --- |
| setShape(value) | 要挤出的基础形状。 |

 **Result:**



---


### getDirection{#getDirection}

| 名称 | 描述 |
| --- | --- |
| getDirection() | 挤出的方向，默认值为 (0, 0, 1)。 |

 **Result:**



---


### setDirection{#setDirection}

| 名称 | 描述 |
| --- | --- |
| setDirection(value) | 挤出的方向，默认值为 (0, 0, 1)。 |

 **Result:**



---


### getHeight{#getHeight}

| 名称 | 描述 |
| --- | --- |
| getHeight() | 挤出几何体的高度，默认值为 1.0。 |

 **Result:**



---


### setHeight{#setHeight}

| 名称 | 描述 |
| --- | --- |
| setHeight(value) | 挤出几何体的高度，默认值为 1.0。 |

 **Result:**



---


### getSlices{#getSlices}

| 名称 | 描述 |
| --- | --- |
| getSlices() | 扭曲挤出几何体的切片数量，默认值为 1。 |

 **Result:**



---


### setSlices{#setSlices}

| 名称 | 描述 |
| --- | --- |
| setSlices(value) | 扭曲挤出几何体的切片数量，默认值为 1。 |

 **Result:**



---


### getCenter{#getCenter}

| 名称 | 描述 |
| --- | --- |
| getCenter() | 如果此值为 false，线性挤出的 Z 范围为 0 到 height；否则范围为 -height/2 到 height/2。 |

 **Result:**



---


### setCenter{#setCenter}

| 名称 | 描述 |
| --- | --- |
| setCenter(value) | 如果此值为 false，线性挤出的 Z 范围为 0 到 height；否则范围为 -height/2 到 height/2。 |

 **Result:**



---


### getTwistOffset{#getTwistOffset}

| 名称 | 描述 |
| --- | --- |
| getTwistOffset() | 用于扭转的偏移量，默认值为 (0, 0, 0)。 |

 **Result:**



---


### setTwistOffset{#setTwistOffset}

| 名称 | 描述 |
| --- | --- |
| setTwistOffset(value) | 用于扭转的偏移量，默认值为 (0, 0, 0)。 |

 **Result:**



---


### getTwist{#getTwist}

| 名称 | 描述 |
| --- | --- |
| getTwist() | 形状被挤出的角度（度数）。 |

 **Result:**



---


### setTwist{#setTwist}

| 名称 | 描述 |
| --- | --- |
| setTwist(value) | 形状被挤出的角度（度数）。 |

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


### toMesh{#toMesh}

| 名称 | 描述 |
| --- | --- |
| toMesh() | 将挤出体转换为网格。 |

 **Result:**
Mesh


---


### getBoundingBox{#getBoundingBox}

| 名称 | 描述 |
| --- | --- |
| getBoundingBox() | 获取当前实体在其对象空间坐标系中的边界框。 |

 **Result:**
Mesh


---


### getEntityRendererKey{#getEntityRendererKey}

| 名称 | 描述 |
| --- | --- |
| getEntityRendererKey() | 获取在渲染器中注册的实体渲染器的键 |

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



