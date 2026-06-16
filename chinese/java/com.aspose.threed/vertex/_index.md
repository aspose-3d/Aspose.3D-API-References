---
title: "顶点"
second_title: "Aspose.3D for Java API 参考"
description: "用于访问原始顶点的顶点引用。"
type: docs
weight: 205
url: /zh/java/com.aspose.threed/vertex/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class Vertex implements Comparable<Vertex>
```

顶点引用，用于访问 [TriMesh](../../com.aspose.threed/trimesh) 中的原始顶点。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Vertex()](#Vertex--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [compareTo(Vertex other)](#compareTo-com.aspose.threed.Vertex-) | 将该顶点与另一个顶点实例进行比较 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readDouble(VertexField field)](#readDouble-com.aspose.threed.VertexField-) | 读取 double 字段 |
| [readFVector2(VertexField field)](#readFVector2-com.aspose.threed.VertexField-) | 读取 vector2 字段 |
| [readFVector3(VertexField field)](#readFVector3-com.aspose.threed.VertexField-) | 读取 vector3 字段 |
| [readFVector4(VertexField field)](#readFVector4-com.aspose.threed.VertexField-) | 读取 vector4 字段 |
| [readFloat(VertexField field)](#readFloat-com.aspose.threed.VertexField-) | 读取 float 字段 |
| [readVector2(VertexField field)](#readVector2-com.aspose.threed.VertexField-) | 读取 vector2 字段 |
| [readVector3(VertexField field)](#readVector3-com.aspose.threed.VertexField-) | 读取 vector3 字段 |
| [readVector4(VertexField field)](#readVector4-com.aspose.threed.VertexField-) | 读取 vector4 字段 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vertex() {#Vertex--}
```
public Vertex()
```


### compareTo(Vertex other) {#compareTo-com.aspose.threed.Vertex-}
```
public abstract int compareTo(Vertex other)
```


将该顶点与另一个顶点实例进行比较

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [Vertex](../../com.aspose.threed/vertex) |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readDouble(VertexField field) {#readDouble-com.aspose.threed.VertexField-}
```
public double readDouble(VertexField field)
```


读取 double 字段

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | 具有 float/double 兼容数据类型的字段 |

**Returns:**
double
### readFVector2(VertexField field) {#readFVector2-com.aspose.threed.VertexField-}
```
public FVector2 readFVector2(VertexField field)
```


读取 vector2 字段

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | 具有 Vector2/FVector2 数据类型的字段 |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### readFVector3(VertexField field) {#readFVector3-com.aspose.threed.VertexField-}
```
public FVector3 readFVector3(VertexField field)
```


读取 vector3 字段

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | 具有 Vector3/FVector3 数据类型的字段 |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### readFVector4(VertexField field) {#readFVector4-com.aspose.threed.VertexField-}
```
public FVector4 readFVector4(VertexField field)
```


读取 vector4 字段

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | 具有 Vector4/FVector4 数据类型的字段 |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### readFloat(VertexField field) {#readFloat-com.aspose.threed.VertexField-}
```
public float readFloat(VertexField field)
```


读取 float 字段

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | 具有 float/double 兼容数据类型的字段 |

**Returns:**
float
### readVector2(VertexField field) {#readVector2-com.aspose.threed.VertexField-}
```
public Vector2 readVector2(VertexField field)
```


读取 vector2 字段

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | 具有 Vector2/FVector2 数据类型的字段 |

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### readVector3(VertexField field) {#readVector3-com.aspose.threed.VertexField-}
```
public Vector3 readVector3(VertexField field)
```


读取 vector3 字段

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | 具有 Vector3/FVector3 数据类型的字段 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### readVector4(VertexField field) {#readVector4-com.aspose.threed.VertexField-}
```
public Vector4 readVector4(VertexField field)
```


读取 vector4 字段

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | 具有 Vector4/FVector4 数据类型的字段 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### toString() {#toString--}
```
public String toString()
```




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

