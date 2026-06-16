---
title: IVertexBuffer
second_title: Referencia de API de Aspose.3D para Java
description: El búfer de vértices contiene los datos de vértices del polígono que se enviarán a la canalización de renderizado.
type: docs
weight: 259
url: /es/java/com.aspose.threed/ivertexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IVertexBuffer extends IBuffer
```

El búfer de vértices contiene los datos de vértices del polígono que se enviarán a la canalización de renderizado.
## Métodos

| Método | Descripción |
| --- | --- |
| [getVertexDeclaration()](#getVertexDeclaration--) | Obtiene la declaración del vértice |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | Carga datos de vértice desde [TriMesh](../../com.aspose.threed/trimesh) |
| [loadData(Object array)](#loadData-java.lang.Object-) | Carga datos desde una matriz |
| [loadData(long data, int size)](#loadData-long-int-) | Carga datos desde la posición dada |
### getVertexDeclaration() {#getVertexDeclaration--}
```
public abstract VertexDeclaration getVertexDeclaration()
```


Obtiene la declaración del vértice

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - the vertex declaration
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


Carga datos de vértice desde [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(Object array) {#loadData-java.lang.Object-}
```
public abstract void loadData(Object array)
```


Carga datos desde una matriz

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matriz | java.lang.Object |  |

### loadData(long data, int size) {#loadData-long-int-}
```
public abstract void loadData(long data, int size)
```


Carga datos desde la posición dada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | long |  |
| tamaño | int |  |

