---
title: "IVertexBuffer"
second_title: "Aspose.3D voor Java API-referentie"
description: "De vertexbuffer bevat de polygon-vertexgegevens die naar de renderpijplijn worden gestuurd."
type: docs
weight: 259
url: /nl/java/com.aspose.threed/ivertexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IVertexBuffer extends IBuffer
```

De vertexbuffer bevat de polygon-vertexgegevens die naar de renderpijplijn worden gestuurd.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getVertexDeclaration()](#getVertexDeclaration--) | Verkrijgt de vertexdeclaratie. |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | Laad vertexgegevens van [TriMesh](../../com.aspose.threed/trimesh) |
| [loadData(Object array)](#loadData-java.lang.Object-) | Laad gegevens van array |
| [loadData(long data, int size)](#loadData-long-int-) | Laad gegevens van gegeven positie |
### getVertexDeclaration() {#getVertexDeclaration--}
```
public abstract VertexDeclaration getVertexDeclaration()
```


Verkrijgt de vertexdeclaratie.

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - the vertex declaration
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


Laad vertexgegevens van [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(Object array) {#loadData-java.lang.Object-}
```
public abstract void loadData(Object array)
```


Laad gegevens van array

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | java.lang.Object |  |

### loadData(long data, int size) {#loadData-long-int-}
```
public abstract void loadData(long data, int size)
```


Laad gegevens van gegeven positie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gegevens | long |  |
| grootte | int |  |

