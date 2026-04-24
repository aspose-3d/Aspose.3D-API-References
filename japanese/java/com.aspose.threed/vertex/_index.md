---
title: 頂点
second_title: Aspose.3D for Java API リファレンス
description: 生の頂点にアクセスするために使用される頂点参照です。
type: docs
weight: 205
url: /ja/java/com.aspose.threed/vertex/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class Vertex implements Comparable<Vertex>
```

生の頂点にアクセスするために使用される頂点参照、[TriMesh](../../com.aspose.threed/trimesh)です。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Vertex()](#Vertex--) |  |
## Methods

| Method | 説明 |
| --- | --- |
| [compareTo(Vertex other)](#compareTo-com.aspose.threed.Vertex-) | 頂点を別の頂点インスタンスと比較する |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readDouble(VertexField field)](#readDouble-com.aspose.threed.VertexField-) | double フィールドを読み取る |
| [readFVector2(VertexField field)](#readFVector2-com.aspose.threed.VertexField-) | vector2 フィールドを読み取る |
| [readFVector3(VertexField field)](#readFVector3-com.aspose.threed.VertexField-) | vector3 フィールドを読み取る |
| [readFVector4(VertexField field)](#readFVector4-com.aspose.threed.VertexField-) | vector4 フィールドを読み取ります |
| [readFloat(VertexField field)](#readFloat-com.aspose.threed.VertexField-) | float フィールドを読み取ります |
| [readVector2(VertexField field)](#readVector2-com.aspose.threed.VertexField-) | vector2 フィールドを読み取る |
| [readVector3(VertexField field)](#readVector3-com.aspose.threed.VertexField-) | vector3 フィールドを読み取る |
| [readVector4(VertexField field)](#readVector4-com.aspose.threed.VertexField-) | vector4 フィールドを読み取ります |
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


頂点を別の頂点インスタンスと比較する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| other | [Vertex](../../com.aspose.threed/vertex) |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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


double フィールドを読み取る

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | float/double 互換のデータ型を持つフィールド |

**Returns:**
double
### readFVector2(VertexField field) {#readFVector2-com.aspose.threed.VertexField-}
```
public FVector2 readFVector2(VertexField field)
```


vector2 フィールドを読み取る

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector2/FVector2 データ型を持つフィールド |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### readFVector3(VertexField field) {#readFVector3-com.aspose.threed.VertexField-}
```
public FVector3 readFVector3(VertexField field)
```


vector3 フィールドを読み取る

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector3/FVector3 データ型を持つフィールド |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### readFVector4(VertexField field) {#readFVector4-com.aspose.threed.VertexField-}
```
public FVector4 readFVector4(VertexField field)
```


vector4 フィールドを読み取ります

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector4/FVector4 データ型を持つフィールド |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### readFloat(VertexField field) {#readFloat-com.aspose.threed.VertexField-}
```
public float readFloat(VertexField field)
```


float フィールドを読み取ります

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | float/double 互換のデータ型を持つフィールド |

**Returns:**
float
### readVector2(VertexField field) {#readVector2-com.aspose.threed.VertexField-}
```
public Vector2 readVector2(VertexField field)
```


vector2 フィールドを読み取る

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector2/FVector2 データ型を持つフィールド |

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### readVector3(VertexField field) {#readVector3-com.aspose.threed.VertexField-}
```
public Vector3 readVector3(VertexField field)
```


vector3 フィールドを読み取る

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector3/FVector3 データ型を持つフィールド |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### readVector4(VertexField field) {#readVector4-com.aspose.threed.VertexField-}
```
public Vector4 readVector4(VertexField field)
```


vector4 フィールドを読み取ります

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector4/FVector4 データ型を持つフィールド |

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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

