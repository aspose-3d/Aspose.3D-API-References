---
title: Κορυφή
second_title: Aspose.3D for Java API Reference
description: Αναφορά κορυφής που χρησιμοποιείται για πρόσβαση στην ακατέργαστη κορυφή στο .
type: docs
weight: 205
url: /el/java/com.aspose.threed/vertex/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class Vertex implements Comparable<Vertex>
```

Αναφορά κορυφής, που χρησιμοποιείται για πρόσβαση στην ακατέργαστη κορυφή στο [TriMesh](../../com.aspose.threed/trimesh).
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Vertex()](#Vertex--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [compareTo(Vertex other)](#compareTo-com.aspose.threed.Vertex-) | Συγκρίνετε την κορυφή με ένα άλλο στιγμιότυπο κορυφής |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readDouble(VertexField field)](#readDouble-com.aspose.threed.VertexField-) | Διαβάστε το πεδίο double |
| [readFVector2(VertexField field)](#readFVector2-com.aspose.threed.VertexField-) | Διαβάστε το πεδίο vector2 |
| [readFVector3(VertexField field)](#readFVector3-com.aspose.threed.VertexField-) | Διαβάστε το πεδίο vector3 |
| [readFVector4(VertexField field)](#readFVector4-com.aspose.threed.VertexField-) | Διαβάστε το πεδίο vector4 |
| [readFloat(VertexField field)](#readFloat-com.aspose.threed.VertexField-) | Διαβάστε το πεδίο float |
| [readVector2(VertexField field)](#readVector2-com.aspose.threed.VertexField-) | Διαβάστε το πεδίο vector2 |
| [readVector3(VertexField field)](#readVector3-com.aspose.threed.VertexField-) | Διαβάστε το πεδίο vector3 |
| [readVector4(VertexField field)](#readVector4-com.aspose.threed.VertexField-) | Διαβάστε το πεδίο vector4 |
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


Συγκρίνετε την κορυφή με ένα άλλο στιγμιότυπο κορυφής

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [Vertex](../../com.aspose.threed/vertex) |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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


Διαβάστε το πεδίο double

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Το πεδίο με συμβατό τύπο δεδομένων float/double |

**Returns:**
double
### readFVector2(VertexField field) {#readFVector2-com.aspose.threed.VertexField-}
```
public FVector2 readFVector2(VertexField field)
```


Διαβάστε το πεδίο vector2

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Το πεδίο με τύπο δεδομένων Vector2/FVector2 |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### readFVector3(VertexField field) {#readFVector3-com.aspose.threed.VertexField-}
```
public FVector3 readFVector3(VertexField field)
```


Διαβάστε το πεδίο vector3

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Το πεδίο με τύπο δεδομένων Vector3/FVector3 |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### readFVector4(VertexField field) {#readFVector4-com.aspose.threed.VertexField-}
```
public FVector4 readFVector4(VertexField field)
```


Διαβάστε το πεδίο vector4

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Το πεδίο με τύπο δεδομένων Vector4/FVector4 |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### readFloat(VertexField field) {#readFloat-com.aspose.threed.VertexField-}
```
public float readFloat(VertexField field)
```


Διαβάστε το πεδίο float

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Το πεδίο με συμβατό τύπο δεδομένων float/double |

**Returns:**
float
### readVector2(VertexField field) {#readVector2-com.aspose.threed.VertexField-}
```
public Vector2 readVector2(VertexField field)
```


Διαβάστε το πεδίο vector2

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Το πεδίο με τύπο δεδομένων Vector2/FVector2 |

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### readVector3(VertexField field) {#readVector3-com.aspose.threed.VertexField-}
```
public Vector3 readVector3(VertexField field)
```


Διαβάστε το πεδίο vector3

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Το πεδίο με τύπο δεδομένων Vector3/FVector3 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### readVector4(VertexField field) {#readVector4-com.aspose.threed.VertexField-}
```
public Vector4 readVector4(VertexField field)
```


Διαβάστε το πεδίο vector4

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Το πεδίο με τύπο δεδομένων Vector4/FVector4 |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

