---
title: Vertex
second_title: Aspose.3D for Java API 레퍼런스
description: 원시 정점을 액세스하는 데 사용되는 정점 참조입니다.
type: docs
weight: 205
url: /ko/java/com.aspose.threed/vertex/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class Vertex implements Comparable<Vertex>
```

정점 참조, [TriMesh](../../com.aspose.threed/trimesh)에서 원시 정점을 액세스하는 데 사용됩니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Vertex()](#Vertex--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [compareTo(Vertex other)](#compareTo-com.aspose.threed.Vertex-) | 다른 정점 인스턴스와 정점을 비교합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readDouble(VertexField field)](#readDouble-com.aspose.threed.VertexField-) | double 필드를 읽습니다. |
| [readFVector2(VertexField field)](#readFVector2-com.aspose.threed.VertexField-) | vector2 필드를 읽습니다. |
| [readFVector3(VertexField field)](#readFVector3-com.aspose.threed.VertexField-) | vector3 필드를 읽습니다. |
| [readFVector4(VertexField field)](#readFVector4-com.aspose.threed.VertexField-) | Read the vector4 field |
| [readFloat(VertexField field)](#readFloat-com.aspose.threed.VertexField-) | Read the float field |
| [readVector2(VertexField field)](#readVector2-com.aspose.threed.VertexField-) | vector2 필드를 읽습니다. |
| [readVector3(VertexField field)](#readVector3-com.aspose.threed.VertexField-) | vector3 필드를 읽습니다. |
| [readVector4(VertexField field)](#readVector4-com.aspose.threed.VertexField-) | Read the vector4 field |
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


다른 정점 인스턴스와 정점을 비교합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [Vertex](../../com.aspose.threed/vertex) |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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


double 필드를 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | float/double 호환 데이터 타입을 가진 필드 |

**Returns:**
double
### readFVector2(VertexField field) {#readFVector2-com.aspose.threed.VertexField-}
```
public FVector2 readFVector2(VertexField field)
```


vector2 필드를 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector2/FVector2 데이터 타입을 가진 필드 |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### readFVector3(VertexField field) {#readFVector3-com.aspose.threed.VertexField-}
```
public FVector3 readFVector3(VertexField field)
```


vector3 필드를 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector3/FVector3 데이터 타입을 가진 필드 |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### readFVector4(VertexField field) {#readFVector4-com.aspose.threed.VertexField-}
```
public FVector4 readFVector4(VertexField field)
```


Read the vector4 field

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector4/FVector4 데이터 타입을 가진 필드 |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### readFloat(VertexField field) {#readFloat-com.aspose.threed.VertexField-}
```
public float readFloat(VertexField field)
```


Read the float field

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | float/double 호환 데이터 타입을 가진 필드 |

**Returns:**
float
### readVector2(VertexField field) {#readVector2-com.aspose.threed.VertexField-}
```
public Vector2 readVector2(VertexField field)
```


vector2 필드를 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector2/FVector2 데이터 타입을 가진 필드 |

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### readVector3(VertexField field) {#readVector3-com.aspose.threed.VertexField-}
```
public Vector3 readVector3(VertexField field)
```


vector3 필드를 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector3/FVector3 데이터 타입을 가진 필드 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### readVector4(VertexField field) {#readVector4-com.aspose.threed.VertexField-}
```
public Vector4 readVector4(VertexField field)
```


Read the vector4 field

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector4/FVector4 데이터 타입을 가진 필드 |

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

