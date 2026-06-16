---
title: "PointCloud"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/pointcloud/
---
## PointCloud class

点云不包含拓扑信息，仅包含控制点和顶点元素。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor(name) | PointCloud 的构造函数 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 此实体的名称 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名称 | 描述 |
| --- | --- |
| constructor_overload() | PointCloud 的构造函数 |

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


### getDeformers{#getDeformers}

| 名称 | 描述 |
| --- | --- |
| getDeformers() | 获取与此几何体关联的所有变形器。变形器。 |

 **Result:**



---


### getControlPoints{#getControlPoints}

| 名称 | 描述 |
| --- | --- |
| getControlPoints() | 获取所有控制点。 |

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


### getVertexElements{#getVertexElements}

| 名称 | 描述 |
| --- | --- |
| getVertexElements() | 获取所有顶点元素。 |

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


### getEntityRendererKey{#getEntityRendererKey}

| 名称 | 描述 |
| --- | --- |
| getEntityRendererKey() | 获取在渲染器中注册的实体渲染器的键 |

 **Result:**
EntityRendererKey


---


### fromGeometry{#fromGeometry}

| 名称 | 描述 |
| --- | --- |
| fromGeometry(g) | 从几何对象创建一个新的 PointCloud 实例 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
|  | 几何 | null |

 **Result:**
PointCloud


---


### fromGeometry{#fromGeometry}

| 名称 | 描述 |
| --- | --- |
| fromGeometry(g, density) | 从几何对象创建一个新的点云实例。Density 是每单位三角形的点数（单位三角形是网格中表面积最大的三角形） |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| g | 几何 | 网格或其他几何实例 |
| density | 数字 | 每单位三角形的点数 |

 **Result:**
PointCloud


---


### getElement{#getElement}

| 名称 | 描述 |
| --- | --- |
| getElement(type) | 获取具有指定类型的顶点元素 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 类型 | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### getVertexElementOfUV{#getVertexElementOfUV}

| 名称 | 描述 |
| --- | --- |
| getVertexElementOfUV(textureMapping) | 获取具有给定纹理映射类型的 VertexElementUV 实例 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 纹理映射 | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElement{#createElement}

| 名称 | 描述 |
| --- | --- |
| createElement(type) | 创建具有指定类型的顶点元素并将其添加到几何体中。如果 type 为 VertexElementType.UV，则会创建一个纹理映射类型为 TextureMapping.DIFFUSE 的 VertexElementUV。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 类型 | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### addElement{#addElement}

| 名称 | 描述 |
| --- | --- |
| addElement(element) | 将现有的顶点元素添加到当前几何体 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 元素 | VertexElement | 要添加的顶点元素 |

 **Result:**
VertexElement


---


### createElement{#createElement}

| 名称 | 描述 |
| --- | --- |
| createElement(type, mappingMode, referenceMode) | 创建具有指定类型的顶点元素并将其添加到几何体中。如果 type 为 VertexElementType.UV，则会创建一个纹理映射类型为 TextureMapping.DIFFUSE 的 VertexElementUV。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 类型 | VertexElementType | VertexElementType |
| 映射模式 | MappingMode | MappingMode |
| 参考模式 | ReferenceMode | ReferenceMode |

 **Result:**
VertexElement


---


### createElementUV{#createElementUV}

| 名称 | 描述 |
| --- | --- |
| createElementUV(uvMapping) | 创建一个具有给定纹理映射类型的 VertexElementUV。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElementUV{#createElementUV}

| 名称 | 描述 |
| --- | --- |
| createElementUV(uvMapping, mappingMode, referenceMode) | 创建一个具有给定纹理映射类型的 VertexElementUV。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |
| 映射模式 | MappingMode | MappingMode |
| 参考模式 | ReferenceMode | ReferenceMode |

 **Result:**
VertexElementUV


---


### getBoundingBox{#getBoundingBox}

| 名称 | 描述 |
| --- | --- |
| getBoundingBox() | 获取当前实体在其对象空间坐标系中的边界框。 |

 **Result:**
VertexElementUV


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



