---
title: Vertex
second_title: Aspose.3D for Java API Reference
description: कच्चे वर्टेक्स तक पहुँचने के लिए उपयोग किया जाने वाला वर्टेक्स रेफ़रेंस।
type: docs
weight: 205
url: /hi/java/com.aspose.threed/vertex/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class Vertex implements Comparable<Vertex>
```

वर्टेक्स रेफ़रेंस, कच्चे वर्टेक्स तक पहुँचने के लिए उपयोग किया जाता है [TriMesh](../../com.aspose.threed/trimesh) में।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Vertex()](#Vertex--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [compareTo(Vertex other)](#compareTo-com.aspose.threed.Vertex-) | वर्टेक्स की तुलना किसी अन्य वर्टेक्स इंस्टेंस से करें |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readDouble(VertexField field)](#readDouble-com.aspose.threed.VertexField-) | डबल फ़ील्ड पढ़ें |
| [readFVector2(VertexField field)](#readFVector2-com.aspose.threed.VertexField-) | vector2 फ़ील्ड पढ़ें |
| [readFVector3(VertexField field)](#readFVector3-com.aspose.threed.VertexField-) | vector3 फ़ील्ड पढ़ें |
| [readFVector4(VertexField field)](#readFVector4-com.aspose.threed.VertexField-) | Read the vector4 field |
| [readFloat(VertexField field)](#readFloat-com.aspose.threed.VertexField-) | Read the float field |
| [readVector2(VertexField field)](#readVector2-com.aspose.threed.VertexField-) | vector2 फ़ील्ड पढ़ें |
| [readVector3(VertexField field)](#readVector3-com.aspose.threed.VertexField-) | vector3 फ़ील्ड पढ़ें |
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


वर्टेक्स की तुलना किसी अन्य वर्टेक्स इंस्टेंस से करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| other | [Vertex](../../com.aspose.threed/vertex) |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
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


डबल फ़ील्ड पढ़ें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | फ़्लोट/डबल संगत डेटा प्रकार वाला फ़ील्ड |

**Returns:**
double
### readFVector2(VertexField field) {#readFVector2-com.aspose.threed.VertexField-}
```
public FVector2 readFVector2(VertexField field)
```


vector2 फ़ील्ड पढ़ें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector2/FVector2 डेटा प्रकार वाला फ़ील्ड |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### readFVector3(VertexField field) {#readFVector3-com.aspose.threed.VertexField-}
```
public FVector3 readFVector3(VertexField field)
```


vector3 फ़ील्ड पढ़ें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector3/FVector3 डेटा प्रकार वाला फ़ील्ड |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### readFVector4(VertexField field) {#readFVector4-com.aspose.threed.VertexField-}
```
public FVector4 readFVector4(VertexField field)
```


Read the vector4 field

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector4/FVector4 डेटा प्रकार वाला फ़ील्ड |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### readFloat(VertexField field) {#readFloat-com.aspose.threed.VertexField-}
```
public float readFloat(VertexField field)
```


Read the float field

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | फ़्लोट/डबल संगत डेटा प्रकार वाला फ़ील्ड |

**Returns:**
फ़्लोट
### readVector2(VertexField field) {#readVector2-com.aspose.threed.VertexField-}
```
public Vector2 readVector2(VertexField field)
```


vector2 फ़ील्ड पढ़ें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector2/FVector2 डेटा प्रकार वाला फ़ील्ड |

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### readVector3(VertexField field) {#readVector3-com.aspose.threed.VertexField-}
```
public Vector3 readVector3(VertexField field)
```


vector3 फ़ील्ड पढ़ें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector3/FVector3 डेटा प्रकार वाला फ़ील्ड |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### readVector4(VertexField field) {#readVector4-com.aspose.threed.VertexField-}
```
public Vector4 readVector4(VertexField field)
```


Read the vector4 field

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector4/FVector4 डेटा प्रकार वाला फ़ील्ड |

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

