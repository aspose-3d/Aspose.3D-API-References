---
title: PolygonBuilder
second_title: Aspose.3D for Java API-referentie
description: Een helperklasse om een polygoon te bouwen voor  Example
type: docs
weight: 133
url: /nl/java/com.aspose.threed/polygonbuilder/
---

**Inheritance:**
java.lang.Object
```
public final class PolygonBuilder
```

Een hulpprogrammaklasse om een polygoon te bouwen voor [Mesh](../../com.aspose.threed/mesh) **Voorbeeld:**

```
Mesh mesh = new Mesh();
  PolygonBuilder builder = new PolygonBuilder(mesh);
  builder.begin();
  builder.addVertex(0);
  builder.addVertex(1);
  builder.addVertex(2);
  builder.end();
```

Gelijk aan :

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

Als alle indices klaar zijn voor gebruik, heeft [Mesh](../../com.aspose.threed/mesh) de voorkeur, anders zou [PolygonBuilder](../../com.aspose.threed/polygonbuilder) een betere keuze zijn.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PolygonBuilder(Mesh mesh)](#PolygonBuilder-com.aspose.threed.Mesh-) | Initialiseert een nieuw exemplaar van de [PolygonBuilder](../../com.aspose.threed/polygonbuilder) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addVertex(int index)](#addVertex-int-) | Voegt een vertex-index toe aan de polygoon |
| [begin()](#begin--) | Begint met het toevoegen van een nieuwe polygoon |
| [end()](#end--) | Rondt de creatie van de polygoon af |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PolygonBuilder(Mesh mesh) {#PolygonBuilder-com.aspose.threed.Mesh-}
```
public PolygonBuilder(Mesh mesh)
```


Initialiseert een nieuw exemplaar van de [PolygonBuilder](../../com.aspose.threed/polygonbuilder) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Op welke mesh de polygoon moet worden gebouwd. |

### addVertex(int index) {#addVertex-int-}
```
public void addVertex(int index)
```


Voegt een vertex-index toe aan de polygoon

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

### begin() {#begin--}
```
public void begin()
```


Begint met het toevoegen van een nieuwe polygoon

### end() {#end--}
```
public void end()
```


Rondt de creatie van de polygoon af

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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

