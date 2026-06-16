---
title: "TriMesh"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/trimesh/
---
## TriMesh class

TriMesh包含可直接由GPU使用的原始数据。此类是一个实用工具，帮助构建仅包含每顶点数据的网格。


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor(name, declaration) | 初始化 TriMesh 实例 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | 字符串 | 此 TriMesh 的名称 |
| 声明 | VertexDeclaration | 顶点的声明 |

 **Result:**



---


### getVertexDeclaration{#getVertexDeclaration}

| 名称 | 描述 |
| --- | --- |
| getVertexDeclaration() | TriMesh 的顶点布局。 |

 **Result:**



---


### getVerticesCount{#getVerticesCount}

| 名称 | 描述 |
| --- | --- |
| getVerticesCount() | 此 TriMesh 中顶点的数量 |

 **Result:**



---


### getIndicesCount{#getIndicesCount}

| 名称 | 描述 |
| --- | --- |
| getIndicesCount() | 此 TriMesh 中的索引计数 |

 **Result:**



---


### getUnmergedVerticesCount{#getUnmergedVerticesCount}

| 名称 | 描述 |
| --- | --- |
| getUnmergedVerticesCount() | 通过 beginVertex() 和 endVertex() 传入的未合并顶点数量 |

 **Result:**



---


### getCapacity{#getCapacity}

| 名称 | 描述 |
| --- | --- |
| getCapacity() | 预分配顶点的容量 |

 **Result:**



---


### getVerticesSizeInBytes{#getVerticesSizeInBytes}

| 名称 | 描述 |
| --- | --- |
| getVerticesSizeInBytes() | 所有顶点的总大小（字节） |

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


### fromMesh{#fromMesh}

| 名称 | 描述 |
| --- | --- |
| fromMesh(declaration, mesh) | 使用给定的顶点布局从指定的网格对象创建 TriMesh |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 声明 | VertexDeclaration | null |
| 网格 | Mesh | null |

 **Result:**
TriMesh


---


### copyFrom{#copyFrom}

| 名称 | 描述 |
| --- | --- |
| copyFrom(input, vd) | 使用新的顶点布局从 input 复制 TriMesh |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| input | TriMesh | 用于复制的输入 TriMesh |
| vd | VertexDeclaration | 输出 TriMesh 的新顶点声明 |

 **Result:**
TriMesh


---


### fromMesh{#fromMesh}

| 名称 | 描述 |
| --- | --- |
| fromMesh(mesh, useFloat) | 从给定的网格对象创建 TriMesh，顶点声明基于输入网格的结构 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| 网格 | Mesh | null |
| useFloat | boolean | 对每个顶点元素组件使用 float 类型而不是 double 类型 |

 **Result:**
TriMesh


---


### beginVertex{#beginVertex}

| 名称 | 描述 |
| --- | --- |
| beginVertex() | 开始添加顶点 |

 **Result:**
顶点


---


### endVertex{#endVertex}

| 名称 | 描述 |
| --- | --- |
| endVertex() | 结束添加顶点 |

 **Result:**
顶点


---


### verticesToArray{#verticesToArray}

| 名称 | 描述 |
| --- | --- |
| verticesToArray() | 将顶点数据转换为字节数组 |

 **Result:**
byte[]


---


### toString{#toString}

| 名称 | 描述 |
| --- | --- |
| toString() |  |

 **Result:**
字符串


---


### fromRawData{#fromRawData}

| 名称 | 描述 |
| --- | --- |
| fromRawData(vd, vertices, indices, generateVertexMapping) | 从原始数据创建 TriMesh。返回的 TriMesh 为了性能不会复制输入的字节数组，对数组的外部更改将反映到此实例中。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| vd | VertexDeclaration | 顶点声明，必须至少包含一个字段。 |
| 顶点 | byte[] | 输入的顶点数据，顶点的最小长度必须大于或等于顶点声明的大小 |
| indices | Number[] | 三角形索引 |
| generateVertexMapping | boolean | 生成 |

 **Result:**
TriMesh


---


### loadVerticesFromBytes{#loadVerticesFromBytes}

| 名称 | 描述 |
| --- | --- |
| loadVerticesFromBytes(verticesInBytes) | 从字节加载顶点，字节长度必须是顶点大小的整数倍。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| verticesInByte | byte[] | null |

 **Result:**
TriMesh


---


### readVector4{#readVector4}

| 名称 | 描述 |
| --- | --- |
| readVector4(idx, field) | 读取 vector4 字段 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| idx | 数字 | 要读取的顶点索引 |
| field | VertexField | 具有 Vector4/FVector4 数据类型的字段 |

 **Result:**
Vector4


---


### readFVector4{#readFVector4}

| 名称 | 描述 |
| --- | --- |
| readFVector4(idx, field) | 读取 vector4 字段 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| idx | 数字 | 要读取的顶点索引 |
| field | VertexField | 具有 Vector4/FVector4 数据类型的字段 |

 **Result:**
FVector4


---


### readVector3{#readVector3}

| 名称 | 描述 |
| --- | --- |
| readVector3(idx, field) | 读取 vector3 字段 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| idx | 数字 | 要读取的顶点索引 |
| field | VertexField | 具有 Vector3/FVector3 数据类型的字段 |

 **Result:**
Vector3


---


### readFVector3{#readFVector3}

| 名称 | 描述 |
| --- | --- |
| readFVector3(idx, field) | 读取 vector3 字段 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| idx | 数字 | 要读取的顶点索引 |
| field | VertexField | 具有 Vector3/FVector3 数据类型的字段 |

 **Result:**
FVector3


---


### readVector2{#readVector2}

| 名称 | 描述 |
| --- | --- |
| readVector2(idx, field) | 读取 vector2 字段 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| idx | 数字 | 要读取的顶点索引 |
| field | VertexField | 具有 Vector2/FVector2 数据类型的字段 |

 **Result:**
Vector2


---


### readFVector2{#readFVector2}

| 名称 | 描述 |
| --- | --- |
| readFVector2(idx, field) | 读取 vector2 字段 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| idx | 数字 | 要读取的顶点索引 |
| field | VertexField | 具有 Vector2/FVector2 数据类型的字段 |

 **Result:**
FVector2


---


### readDouble{#readDouble}

| 名称 | 描述 |
| --- | --- |
| readDouble(idx, field) | 读取 double 字段 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| idx | 数字 | 要读取的顶点索引 |
| field | VertexField | 具有 float/double 兼容数据类型的字段 |

 **Result:**
数字


---


### readFloat{#readFloat}

| 名称 | 描述 |
| --- | --- |
| readFloat(idx, field) | 读取 float 字段 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| idx | 数字 | 要读取的顶点索引 |
| field | VertexField | 具有 float/double 兼容数据类型的字段 |

 **Result:**
数字


---


### getBoundingBox{#getBoundingBox}

| 名称 | 描述 |
| --- | --- |
| getBoundingBox() | 获取当前实体在其对象空间坐标系中的边界框。 |

 **Result:**
数字


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


### iterator{#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator() | 保留供内部使用。 |

 **Result:**
Property


---



