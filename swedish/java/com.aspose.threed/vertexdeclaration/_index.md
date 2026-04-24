---
title: VertexDeclaration
second_title: Aspose.3D for Java API-referens
description: Deklarationen av en anpassad definierad vertexstruktur
type: docs
weight: 206
url: /sv/java/com.aspose.threed/vertexdeclaration/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable, java.lang.Comparable
```
public final class VertexDeclaration implements Iterable<VertexField>, Comparable<VertexDeclaration>
```

Deklarationen av en anpassad definierad vertexstruktur
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [VertexDeclaration()](#VertexDeclaration--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addField(int dataType, VertexFieldSemantic semantic)](#addField-int-com.aspose.threed.VertexFieldSemantic-) | Lägg till ett nytt vertexfält |
| [addField(int dataType, VertexFieldSemantic semantic, int index)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-) | Lägg till ett nytt vertexfält |
| [addField(int dataType, VertexFieldSemantic semantic, int index, String alias)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-) | Lägg till ett nytt vertexfält |
| [clear()](#clear--) | Rensa alla fält. |
| [compareTo(VertexDeclaration other)](#compareTo-com.aspose.threed.VertexDeclaration-) | Jämför den här instansen med ett specificerat objekt och returnerar en indikation på deras relativa värden. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om denna instans och ett angivet objekt, som också måste vara ett [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)-objekt, har samma värde. |
| [fromGeometry(Geometry geometry, boolean useFloat)](#fromGeometry-com.aspose.threed.Geometry-boolean-) | Skapa en [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) baserad på en [Geometry](../../com.aspose.threed/geometry)s layout. |
| [get(int index)](#get-int-) | Hämtar [VertexField](../../com.aspose.threed/vertexfield) efter index |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Hämtar antalet av alla fält som definierats i denna [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |
| [getSealed()](#getSealed--) | En [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) kommer att förseglas när den har använts av [TriMesh](../../com.aspose.threed/trimesh), inga fler ändringar tillåts. |
| [getSize()](#getSize--) | Storleken i byte för vertexstrukturen. |
| [hashCode()](#hashCode--) | Returnerar hashkoden för den här strängen. |
| [iterator()](#iterator--) | Hämtar en enumerator för att gå igenom alla vertexfält i denna instans. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Strängrepresentation av [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |
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


Lägg till ett nytt vertexfält

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataType | int | Datatypen för vertexfältet |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Hur kommer detta fält att användas för |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index)
```


Lägg till ett nytt vertexfält

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataType | int | Datatypen för vertexfältet |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Hur kommer detta fält att användas för |
| index | int | Indexet för samma fälts semantik, -1 för automatisk generering |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index, String alias) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index, String alias)
```


Lägg till ett nytt vertexfält

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataType | int | Datatypen för vertexfältet |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Hur kommer detta fält att användas för |
| index | int | Indexet för samma fälts semantik, -1 för automatisk generering |
| alias | java.lang.String | Aliasnamnet för fältet |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### clear() {#clear--}
```
public void clear()
```


Rensa alla fält.

### compareTo(VertexDeclaration other) {#compareTo-com.aspose.threed.VertexDeclaration-}
```
public int compareTo(VertexDeclaration other)
```


Jämför den här instansen med ett specificerat objekt och returnerar en indikation på deras relativa värden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om denna instans och ett angivet objekt, som också måste vara ett [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)-objekt, har samma värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromGeometry(Geometry geometry, boolean useFloat) {#fromGeometry-com.aspose.threed.Geometry-boolean-}
```
public static VertexDeclaration fromGeometry(Geometry geometry, boolean useFloat)
```


Skapa en [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) baserad på en [Geometry](../../com.aspose.threed/geometry)s layout.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) |  |
| useFloat | boolean | Använd float istället för dubbeltyp |

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### get(int index) {#get-int-}
```
public VertexField get(int index)
```


Hämtar [VertexField](../../com.aspose.threed/vertexfield) efter index

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

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


Hämtar antalet av alla fält som definierats i denna [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)

**Returns:**
int - antalet alla fält som definierats i denna [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### getSealed() {#getSealed--}
```
public boolean getSealed()
```


En [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) kommer att förseglas när den har använts av [TriMesh](../../com.aspose.threed/trimesh), inga fler ändringar tillåts.

**Returns:**
boolean - En [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) kommer att förseglas när den har använts av [TriMesh](../../com.aspose.threed/trimesh), inga fler ändringar tillåts.
### getSize() {#getSize--}
```
public int getSize()
```


Storleken i byte för vertexstrukturen.

**Returns:**
int - Storleken i byte för vertexstrukturen.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hashkoden för den här strängen.

**Returns:**
int - En 32-bitars signerad heltals-hashkod.
### iterator() {#iterator--}
```
public Iterator<VertexField> iterator()
```


Hämtar en enumerator för att gå igenom alla vertexfält i denna instans.

**Returns:**
java.util.Iterator<com.aspose.threed.VertexField> - Enumerator
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


Strängrepresentation av [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

