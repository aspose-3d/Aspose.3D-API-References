---
title: "Pyramid"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/pyramid/
---
## Pyramid class

参数化金字塔。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() | 使用默认底部面积 (10, 10) 和默认高度 (5) 构造一个新的 pyramid 实例。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload(xbottom, ybottom, height) | 使用指定的底部面积构造一个新的 pyramid 实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xbottom | 数字 | 底部的 x 方向长度 |
| ybottom | 数字 | 底部的 y 方向长度 |
| height | 数字 | pyramid 的高度 |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名称 | 描述 |
| --- | --- |
| constructor_overload2(xbottom, ybottom, xtop, ytop, height) | 使用指定的底部面积、顶部面积和高度构造一个新的 pyramid 实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| xbottom | 数字 | 底部区域的 x 方向长度 |
| ybottom | 数字 | 底部区域的 y 方向长度 |
| xtop | 数字 | 顶部区域的 x 方向长度 |
| ytop | 数字 | 顶部区域的 y 方向长度 |
| height | 数字 | pyramid 的高度 |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| 名称 | 描述 |
| --- | --- |
| constructor_overload3(name, xbottom, ybottom, xtop, ytop, height) | 使用指定的底部面积、顶部面积和高度构造一个新的 pyramid 实例。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 金字塔的名称 |
| xbottom | 数字 | 底部区域的 x 方向长度 |
| ybottom | 数字 | 底部区域的 y 方向长度 |
| xtop | 数字 | 顶部区域的 x 方向长度 |
| ytop | 数字 | 顶部区域的 y 方向长度 |
| height | 数字 | pyramid 的高度 |

 **Result:**



---


### getBottomArea{#getBottomArea}

| 名称 | 描述 |
| --- | --- |
| getBottomArea() | 底部帽面的面积 |

 **Result:**



---


### setBottomArea{#setBottomArea}

| 名称 | 描述 |
| --- | --- |
| setBottomArea(value) | 底部帽面的面积 |

 **Result:**



---


### getTopArea{#getTopArea}

| 名称 | 描述 |
| --- | --- |
| getTopArea() | 顶部帽面的面积 |

 **Result:**



---


### setTopArea{#setTopArea}

| 名称 | 描述 |
| --- | --- |
| setTopArea(value) | 顶部帽面的面积 |

 **Result:**



---


### getBottomOffset{#getBottomOffset}

| 名称 | 描述 |
| --- | --- |
| getBottomOffset() | 底部顶点的偏移量 |

 **Result:**



---


### setBottomOffset{#setBottomOffset}

| 名称 | 描述 |
| --- | --- |
| setBottomOffset(value) | 底部顶点的偏移量 |

 **Result:**



---


### getHeight{#getHeight}

| 名称 | 描述 |
| --- | --- |
| getHeight() | 金字塔的高度 |

 **Result:**



---


### setHeight{#setHeight}

| 名称 | 描述 |
| --- | --- |
| setHeight(value) | 金字塔的高度 |

 **Result:**



---


### getCastShadows{#getCastShadows}

| 名称 | 描述 |
| --- | --- |
| getCastShadows() | 获取或设置此几何体是否可以投射阴影。 |

 **Result:**



---


### setCastShadows{#setCastShadows}

| 名称 | 描述 |
| --- | --- |
| setCastShadows(value) | 获取或设置此几何体是否可以投射阴影。 |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| 名称 | 描述 |
| --- | --- |
| getReceiveShadows() | 获取或设置此几何体是否可以接收阴影。 |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| 名称 | 描述 |
| --- | --- |
| setReceiveShadows(value) | 获取或设置此几何体是否可以接收阴影。 |

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
| toMesh() | 将当前对象转换为网格 |

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



