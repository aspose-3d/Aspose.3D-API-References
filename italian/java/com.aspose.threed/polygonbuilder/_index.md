---
title: PolygonBuilder
second_title: Aspose.3D for Java API Reference
description: Una classe di supporto per costruire poligoni per  Example
type: docs
weight: 133
url: /it/java/com.aspose.threed/polygonbuilder/
---

**Inheritance:**
java.lang.Object
```
public final class PolygonBuilder
```

Una classe di supporto per costruire poligoni per [Mesh](../../com.aspose.threed/mesh) **Esempio:**

```
Mesh mesh = new Mesh();
  PolygonBuilder builder = new PolygonBuilder(mesh);
  builder.begin();
  builder.addVertex(0);
  builder.addVertex(1);
  builder.addVertex(2);
  builder.end();
```

Uguale a :

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

Se tutti gli indici sono pronti per l'uso, [Mesh](../../com.aspose.threed/mesh) è preferito, altrimenti [PolygonBuilder](../../com.aspose.threed/polygonbuilder) sarebbe una scelta migliore.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PolygonBuilder(Mesh mesh)](#PolygonBuilder-com.aspose.threed.Mesh-) | Inizializza una nuova istanza della classe [PolygonBuilder](../../com.aspose.threed/polygonbuilder). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addVertex(int index)](#addVertex-int-) | Aggiunge un indice di vertice al poligono |
| [begin()](#begin--) | Inizia ad aggiungere un nuovo poligono |
| [end()](#end--) | Completa la creazione del poligono |
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


Inizializza una nuova istanza della classe [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Su quale mesh costruire il poligono. |

### addVertex(int index) {#addVertex-int-}
```
public void addVertex(int index)
```


Aggiunge un indice di vertice al poligono

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int |  |

### begin() {#begin--}
```
public void begin()
```


Inizia ad aggiungere un nuovo poligono

### end() {#end--}
```
public void end()
```


Completa la creazione del poligono

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

