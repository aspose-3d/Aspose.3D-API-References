---
title: PolygonBuilder
second_title: Aspose.3D for Java API-referens
description: En hjälparklass för att bygga polygon för  Example
type: docs
weight: 133
url: /sv/java/com.aspose.threed/polygonbuilder/
---

**Inheritance:**
java.lang.Object
```
public final class PolygonBuilder
```

En hjälparklass för att bygga polygon för [Mesh](../../com.aspose.threed/mesh) **Exempel:**

```
Mesh mesh = new Mesh();
  PolygonBuilder builder = new PolygonBuilder(mesh);
  builder.begin();
  builder.addVertex(0);
  builder.addVertex(1);
  builder.addVertex(2);
  builder.end();
```

Motsvarar :

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

Om alla index är redo att användas, föredras [Mesh](../../com.aspose.threed/mesh), annars skulle [PolygonBuilder](../../com.aspose.threed/polygonbuilder) vara ett bättre val.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PolygonBuilder(Mesh mesh)](#PolygonBuilder-com.aspose.threed.Mesh-) | Initierar en ny instans av klassen [PolygonBuilder](../../com.aspose.threed/polygonbuilder). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addVertex(int index)](#addVertex-int-) | Lägger till ett vertex-index till polygonen |
| [begin()](#begin--) | Börjar lägga till en ny polygon |
| [end()](#end--) | Avslutar skapandet av polygonen |
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


Initierar en ny instans av klassen [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Vilken mesh polygonen ska byggas på. |

### addVertex(int index) {#addVertex-int-}
```
public void addVertex(int index)
```


Lägger till ett vertex-index till polygonen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

### begin() {#begin--}
```
public void begin()
```


Börjar lägga till en ny polygon

### end() {#end--}
```
public void end()
```


Avslutar skapandet av polygonen

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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

