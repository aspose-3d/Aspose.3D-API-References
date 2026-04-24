---
title: PolygonBuilder
second_title: Referencia de API de Aspose.3D para Java
description: Una clase auxiliar para construir polígonos para  Example
type: docs
weight: 133
url: /es/java/com.aspose.threed/polygonbuilder/
---

**Inheritance:**
java.lang.Object
```
public final class PolygonBuilder
```

Una clase auxiliar para construir polígonos para [Mesh](../../com.aspose.threed/mesh) **Ejemplo:**

```
Mesh mesh = new Mesh();
  PolygonBuilder builder = new PolygonBuilder(mesh);
  builder.begin();
  builder.addVertex(0);
  builder.addVertex(1);
  builder.addVertex(2);
  builder.end();
```

Igual a :

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

Si todos los índices están listos para usar, se prefiere [Mesh](../../com.aspose.threed/mesh), de lo contrario [PolygonBuilder](../../com.aspose.threed/polygonbuilder) sería una mejor opción.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PolygonBuilder(Mesh mesh)](#PolygonBuilder-com.aspose.threed.Mesh-) | Inicializa una nueva instancia de la clase [PolygonBuilder](../../com.aspose.threed/polygonbuilder). |
## Métodos

| Método | Descripción |
| --- | --- |
| [addVertex(int index)](#addVertex-int-) | Agrega un índice de vértice al polígono |
| [begin()](#begin--) | Comienza a agregar un nuevo polígono |
| [end()](#end--) | Finaliza la creación del polígono |
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


Inicializa una nueva instancia de la clase [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | En qué malla construir el polígono. |

### addVertex(int index) {#addVertex-int-}
```
public void addVertex(int index)
```


Agrega un índice de vértice al polígono

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int |  |

### begin() {#begin--}
```
public void begin()
```


Comienza a agregar un nuevo polígono

### end() {#end--}
```
public void end()
```


Finaliza la creación del polígono

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

