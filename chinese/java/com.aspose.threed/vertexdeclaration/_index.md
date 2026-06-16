---
title: "VertexDeclaration"
second_title: "Aspose.3D for Java API 参考"
description: "自定义顶点结构的声明"
type: docs
weight: 206
url: /zh/java/com.aspose.threed/vertexdeclaration/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable, java.lang.Comparable
```
public final class VertexDeclaration implements Iterable<VertexField>, Comparable<VertexDeclaration>
```

自定义顶点结构的声明
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [VertexDeclaration()](#VertexDeclaration--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addField(int dataType, VertexFieldSemantic semantic)](#addField-int-com.aspose.threed.VertexFieldSemantic-) | 添加新的顶点字段 |
| [addField(int dataType, VertexFieldSemantic semantic, int index)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-) | 添加新的顶点字段 |
| [addField(int dataType, VertexFieldSemantic semantic, int index, String alias)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-) | 添加新的顶点字段 |
| [clear()](#clear--) | 清除所有字段。 |
| [compareTo(VertexDeclaration other)](#compareTo-com.aspose.threed.VertexDeclaration-) | 将此实例与指定对象进行比较，并返回它们相对值的指示。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定此实例与指定对象（该对象也必须是 [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) 对象）是否具有相同的值。 |
| [fromGeometry(Geometry geometry, boolean useFloat)](#fromGeometry-com.aspose.threed.Geometry-boolean-) | 基于 [Geometry](../../com.aspose.threed/geometry) 的布局创建一个 [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)。 |
| [get(int index)](#get-int-) | 按索引获取 [VertexField](../../com.aspose.threed/vertexfield) |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 获取此 [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) 中定义的所有字段的计数 |
| [getSealed()](#getSealed--) | 当 [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) 被 [TriMesh](../../com.aspose.threed/trimesh) 使用后将被封闭，不再允许修改。 |
| [getSize()](#getSize--) | 顶点结构的字节大小。 |
| [hashCode()](#hashCode--) | 返回此字符串的哈希码。 |
| [iterator()](#iterator--) | 获取一个枚举器以遍历此实例中的所有顶点字段。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) 的字符串表示 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexDeclaration() {#VertexDeclaration--}
```
public VertexDeclaration()
```


### addField(int dataType, VertexFieldSemantic semantic) {#addField-int-com.aspose.threed.VertexFieldSemantic-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic)
```


添加新的顶点字段

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataType | int | 顶点字段的数据类型 |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | 此字段将用于何处 |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index)
```


添加新的顶点字段

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataType | int | 顶点字段的数据类型 |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | 此字段将用于何处 |
| 索引 | int | 相同字段语义的索引，-1 表示自动生成 |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index, String alias) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index, String alias)
```


添加新的顶点字段

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dataType | int | 顶点字段的数据类型 |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | 此字段将用于何处 |
| 索引 | int | 相同字段语义的索引，-1 表示自动生成 |
| 别名 | java.lang.String | 字段的别名 |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### clear() {#clear--}
```
public void clear()
```


清除所有字段。

### compareTo(VertexDeclaration other) {#compareTo-com.aspose.threed.VertexDeclaration-}
```
public int compareTo(VertexDeclaration other)
```


将此实例与指定对象进行比较，并返回它们相对值的指示。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定此实例与指定对象（该对象也必须是 [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) 对象）是否具有相同的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
布尔
### fromGeometry(Geometry geometry, boolean useFloat) {#fromGeometry-com.aspose.threed.Geometry-boolean-}
```
public static VertexDeclaration fromGeometry(Geometry geometry, boolean useFloat)
```


基于 [Geometry](../../com.aspose.threed/geometry) 的布局创建一个 [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) |  |
| useFloat | 布尔 | 使用 float 而不是 double 类型 |

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### get(int index) {#get-int-}
```
public VertexField get(int index)
```


按索引获取 [VertexField](../../com.aspose.threed/vertexfield)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int |  |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield) - the [VertexField](../../com.aspose.threed/vertexfield) by index
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


获取此 [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) 中定义的所有字段的计数

**Returns:**
int - 此 [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) 中定义的所有字段的计数
### getSealed() {#getSealed--}
```
public boolean getSealed()
```


当 [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) 被 [TriMesh](../../com.aspose.threed/trimesh) 使用后将被封闭，不再允许修改。

**Returns:**
boolean - 当 [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) 被 [TriMesh](../../com.aspose.threed/trimesh) 使用后将被封闭，不再允许修改。
### getSize() {#getSize--}
```
public int getSize()
```


顶点结构的字节大小。

**Returns:**
int - 顶点结构的字节大小。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此字符串的哈希码。

**Returns:**
int - 32 位有符号整数哈希码。
### iterator() {#iterator--}
```
public Iterator<VertexField> iterator()
```


获取一个枚举器以遍历此实例中的所有顶点字段。

**Returns:**
java.util.Iterator<com.aspose.threed.VertexField> - 枚举器
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) 的字符串表示

**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

