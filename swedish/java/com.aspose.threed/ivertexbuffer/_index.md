---
title: IVertexBuffer
second_title: Aspose.3D for Java API-referens
description: Vertexbufferten innehåller polygonens vertexdata som kommer att skickas till renderingspipeline.
type: docs
weight: 259
url: /sv/java/com.aspose.threed/ivertexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IVertexBuffer extends IBuffer
```

Vertexbufferten innehåller polygonens vertexdata som kommer att skickas till renderingspipeline.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVertexDeclaration()](#getVertexDeclaration--) | Hämtar vertexdeklarationen |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | Läs in vertexdata från [TriMesh](../../com.aspose.threed/trimesh) |
| [loadData(Object array)](#loadData-java.lang.Object-) | Läs in data från array |
| [loadData(long data, int size)](#loadData-long-int-) | Läs in data från given position |
### getVertexDeclaration() {#getVertexDeclaration--}
```
public abstract VertexDeclaration getVertexDeclaration()
```


Hämtar vertexdeklarationen

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - the vertex declaration
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


Läs in vertexdata från [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(Object array) {#loadData-java.lang.Object-}
```
public abstract void loadData(Object array)
```


Läs in data från array

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | java.lang.Object |  |

### loadData(long data, int size) {#loadData-long-int-}
```
public abstract void loadData(long data, int size)
```


Läs in data från given position

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | long |  |
| storlek | int |  |

