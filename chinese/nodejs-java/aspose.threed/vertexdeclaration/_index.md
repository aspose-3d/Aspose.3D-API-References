---
title: "VertexDeclaration"
second_title: "Aspose.3D 用于 Node.js 通过 Java API 参考"
description: 
type: docs

url: /zh/nodejs-java/aspose.threed/vertexdeclaration/
---
## VertexDeclaration class

自定义顶点结构的声明


## 方法

### constructor{#constructor}

| 名称 | 描述 |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getSealed{#getSealed}

| 名称 | 描述 |
| --- | --- |
| getSealed() | 当 VertexDeclaration 已被 com.aspose.threed.TriMesh`1 或 TriMesh 使用后，将被封闭，不再允许进行任何修改。 |

 **Result:**



---


### getCount{#getCount}

| 名称 | 描述 |
| --- | --- |
| getCount() | 获取此 VertexDeclaration 中定义的所有字段的计数 |

 **Result:**



---


### getSize{#getSize}

| 名称 | 描述 |
| --- | --- |
| getSize() | 顶点结构的字节大小。 |

 **Result:**



---


### get{#get}

| 名称 | 描述 |
| --- | --- |
| get(index) |  |

 **Result:**



---


### clear{#clear}

| 名称 | 描述 |
| --- | --- |
| clear() | 清除所有字段。 |

 **Result:**



---


### addField{#addField}

| 名称 | 描述 |
| --- | --- |
| addField(dataType, semantic, index, alias) | 添加一个新的顶点字段 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| dataType | 数字 | VertexFieldDataType |
| semantic | VertexFieldSemantic | VertexFieldSemantic |
| 索引 | 数字 | 相同字段语义的索引，-1 表示自动生成 |
| alias | 字符串 | 字段的别名 |

 **Result:**



---


### fromGeometry{#fromGeometry}

| 名称 | 描述 |
| --- | --- |
| fromGeometry(geometry, useFloat) | 基于 Geometry 的布局创建 VertexDeclaration。 |

 **Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| geometr | 几何 | null |
| useFloat | boolean | 使用 float 而不是 double 类型 |

 **Result:**
VertexDeclaration


---


### compareTo{#compareTo}

| 名称 | 描述 |
| --- | --- |
| compareTo(other) | 将此实例与指定对象进行比较，并返回它们相对值的指示。 |

 **Result:**
VertexDeclaration


---


### toString{#toString}

| 名称 | 描述 |
| --- | --- |
| toString() |  |

 **Result:**
字符串


---


### hashCode{#hashCode}

| 名称 | 描述 |
| --- | --- |
| hashCode() |  |

 **Result:**
数字


---


### equals{#equals}

| 名称 | 描述 |
| --- | --- |
| equals(obj) | 确定此实例与指定对象（该对象也必须是 VertexDeclaration 对象）是否具有相同的值。 |

 **Result:**
数字


---


### iterator{#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator() | 保留供内部使用。 |

 **Result:**
数字


---



