---
title: VertexDeclaration
second_title: Aspose.3D for Java API-referentie
description: De declaratie van een aangepaste vertexstructuur.
type: docs
weight: 206
url: /nl/java/com.aspose.threed/vertexdeclaration/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable, java.lang.Comparable
```
public final class VertexDeclaration implements Iterable<VertexField>, Comparable<VertexDeclaration>
```

De declaratie van een aangepaste vertexstructuur
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [VertexDeclaration()](#VertexDeclaration--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addField(int dataType, VertexFieldSemantic semantic)](#addField-int-com.aspose.threed.VertexFieldSemantic-) | Voeg een nieuw vertexveld toe. |
| [addField(int dataType, VertexFieldSemantic semantic, int index)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-) | Voeg een nieuw vertexveld toe. |
| [addField(int dataType, VertexFieldSemantic semantic, int index, String alias)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-) | Voeg een nieuw vertexveld toe. |
| [clear()](#clear--) | Wis alle velden. |
| [compareTo(VertexDeclaration other)](#compareTo-com.aspose.threed.VertexDeclaration-) | Vergelijkt deze instantie met een opgegeven object en geeft een indicatie van hun relatieve waarden terug. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of deze instantie en een opgegeven object, dat ook een [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)-object moet zijn, dezelfde waarde hebben. |
| [fromGeometry(Geometry geometry, boolean useFloat)](#fromGeometry-com.aspose.threed.Geometry-boolean-) | Maak een [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) op basis van de lay-out van een [Geometry](../../com.aspose.threed/geometry). |
| [get(int index)](#get-int-) | Haalt het [VertexField](../../com.aspose.threed/vertexfield) op op index. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Haalt het aantal van alle velden op die zijn gedefinieerd in deze [VertexDeclaration](../../com.aspose.threed/vertexdeclaration). |
| [getSealed()](#getSealed--) | Een [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) wordt verzegeld wanneer deze is gebruikt door [TriMesh](../../com.aspose.threed/trimesg), verdere wijzigingen zijn niet toegestaan. |
| [getSize()](#getSize--) | De grootte in bytes van de vertexstructuur. |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze string. |
| [iterator()](#iterator--) | Haalt een enumerator op om door alle vertexvelden in deze instantie te lopen. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Stringrepresentatie van [VertexDeclaration](../../com.aspose.threed/vertexdeclaration). |
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


Voeg een nieuw vertexveld toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataType | int | Het gegevenstype van het vertexveld. |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Hoe zal dit veld worden gebruikt |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index)
```


Voeg een nieuw vertexveld toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataType | int | Het gegevenstype van het vertexveld. |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Hoe zal dit veld worden gebruikt |
| index | int | De index voor dezelfde veldsemantiek, -1 voor automatische generatie |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index, String alias) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index, String alias)
```


Voeg een nieuw vertexveld toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataType | int | Het gegevenstype van het vertexveld. |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Hoe zal dit veld worden gebruikt |
| index | int | De index voor dezelfde veldsemantiek, -1 voor automatische generatie |
| alias | java.lang.String | De aliasnaam van het veld |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### clear() {#clear--}
```
public void clear()
```


Wis alle velden.

### compareTo(VertexDeclaration other) {#compareTo-com.aspose.threed.VertexDeclaration-}
```
public int compareTo(VertexDeclaration other)
```


Vergelijkt deze instantie met een opgegeven object en geeft een indicatie van hun relatieve waarden terug.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of deze instantie en een opgegeven object, dat ook een [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)-object moet zijn, dezelfde waarde hebben.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromGeometry(Geometry geometry, boolean useFloat) {#fromGeometry-com.aspose.threed.Geometry-boolean-}
```
public static VertexDeclaration fromGeometry(Geometry geometry, boolean useFloat)
```


Maak een [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) op basis van de lay-out van een [Geometry](../../com.aspose.threed/geometry).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) |  |
| useFloat | boolean | Gebruik float in plaats van double type |

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### get(int index) {#get-int-}
```
public VertexField get(int index)
```


Haalt het [VertexField](../../com.aspose.threed/vertexfield) op op index.

**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt het aantal van alle velden op die zijn gedefinieerd in deze [VertexDeclaration](../../com.aspose.threed/vertexdeclaration).

**Returns:**
int - het aantal van alle velden gedefinieerd in deze [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### getSealed() {#getSealed--}
```
public boolean getSealed()
```


Een [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) wordt verzegeld wanneer deze is gebruikt door [TriMesh](../../com.aspose.threed/trimesg), verdere wijzigingen zijn niet toegestaan.

**Returns:**
boolean - Een [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) wordt verzegeld wanneer deze is gebruikt door [TriMesh](../../com.aspose.threed/trimesh), verdere wijzigingen zijn niet toegestaan.
### getSize() {#getSize--}
```
public int getSize()
```


De grootte in bytes van de vertexstructuur.

**Returns:**
int - De grootte in bytes van de vertexstructuur.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor deze string.

**Returns:**
int - Een 32-bit ondertekende integer hashcode.
### iterator() {#iterator--}
```
public Iterator<VertexField> iterator()
```


Haalt een enumerator op om door alle vertexvelden in deze instantie te lopen.

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


Stringrepresentatie van [VertexDeclaration](../../com.aspose.threed/vertexdeclaration).

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

