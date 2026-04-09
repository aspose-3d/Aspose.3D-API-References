---
title: IVertexBuffer
second_title: Aspose.3D for Java API Reference
description: Il buffer dei vertici contiene i dati dei vertici del poligono che saranno inviati alla pipeline di rendering
type: docs
weight: 259
url: /it/java/com.aspose.threed/ivertexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IVertexBuffer extends IBuffer
```

Il buffer dei vertici contiene i dati dei vertici del poligono che saranno inviati alla pipeline di rendering
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVertexDeclaration()](#getVertexDeclaration--) | Ottiene la dichiarazione del vertice |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | Carica i dati dei vertici da [TriMesh](../../com.aspose.threed/trimesh) |
| [loadData(Object array)](#loadData-java.lang.Object-) | Carica i dati da un array |
| [loadData(long data, int size)](#loadData-long-int-) | Carica i dati dalla posizione specificata |
### getVertexDeclaration() {#getVertexDeclaration--}
```
public abstract VertexDeclaration getVertexDeclaration()
```


Ottiene la dichiarazione del vertice

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - the vertex declaration
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


Carica i dati dei vertici da [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(Object array) {#loadData-java.lang.Object-}
```
public abstract void loadData(Object array)
```


Carica i dati da un array

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | java.lang.Object |  |

### loadData(long data, int size) {#loadData-long-int-}
```
public abstract void loadData(long data, int size)
```


Carica i dati dalla posizione specificata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | long |  |
| dimensione | int |  |

