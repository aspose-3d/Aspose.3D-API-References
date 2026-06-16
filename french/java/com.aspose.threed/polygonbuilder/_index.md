---
title: "PolygonBuilder"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Une classe d'aide pour construire des polygones pour  Example"
type: docs
weight: 133
url: /fr/java/com.aspose.threed/polygonbuilder/
---

**Inheritance:**
java.lang.Object
```
public final class PolygonBuilder
```

Une classe d'assistance pour construire un polygone pour [Mesh](../../com.aspose.threed/mesh) **Exemple:**

```
Mesh mesh = new Mesh();
  PolygonBuilder builder = new PolygonBuilder(mesh);
  builder.begin();
  builder.addVertex(0);
  builder.addVertex(1);
  builder.addVertex(2);
  builder.end();
```

Égal à :

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

Si tous les indices sont prêts à être utilisés, [Mesh](../../com.aspose.threed/mesh) est préféré, sinon [PolygonBuilder](../../com.aspose.threed/polygonbuilder) serait un meilleur choix.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PolygonBuilder(Mesh mesh)](#PolygonBuilder-com.aspose.threed.Mesh-) | Initialise une nouvelle instance de la classe [PolygonBuilder](../../com.aspose.threed/polygonbuilder). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addVertex(int index)](#addVertex-int-) | Ajoute un indice de sommet au polygone |
| [begin()](#begin--) | Commence à ajouter un nouveau polygone |
| [end()](#end--) | Termine la création du polygone |
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


Initialise une nouvelle instance de la classe [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Sur quel mesh construire le polygone. |

### addVertex(int index) {#addVertex-int-}
```
public void addVertex(int index)
```


Ajoute un indice de sommet au polygone

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indice | int |  |

### begin() {#begin--}
```
public void begin()
```


Commence à ajouter un nouveau polygone

### end() {#end--}
```
public void end()
```


Termine la création du polygone

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

