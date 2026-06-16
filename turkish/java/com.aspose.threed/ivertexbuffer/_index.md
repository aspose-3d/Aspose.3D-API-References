---
title: "IVertexBuffer"
second_title: "Aspose.3D for Java API Referansı"
description: "Vertex tamponu, renderleme hattına gönderilecek çokgen vertex verilerini tutar."
type: docs
weight: 259
url: /tr/java/com.aspose.threed/ivertexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IVertexBuffer extends IBuffer
```

Vertex tamponu, renderleme hattına gönderilecek çokgen vertex verilerini tutar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVertexDeclaration()](#getVertexDeclaration--) | Köşe bildirimini alır |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | Köşe verilerini [TriMesh](../../com.aspose.threed/trimesh) üzerinden yükle |
| [loadData(Object array)](#loadData-java.lang.Object-) | Verileri dizi üzerinden yükle |
| [loadData(long data, int size)](#loadData-long-int-) | Verileri verilen konumdan yükle |
### getVertexDeclaration() {#getVertexDeclaration--}
```
public abstract VertexDeclaration getVertexDeclaration()
```


Köşe bildirimini alır

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - the vertex declaration
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


Köşe verilerini [TriMesh](../../com.aspose.threed/trimesh) üzerinden yükle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(Object array) {#loadData-java.lang.Object-}
```
public abstract void loadData(Object array)
```


Verileri dizi üzerinden yükle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dizi | java.lang.Object |  |

### loadData(long data, int size) {#loadData-long-int-}
```
public abstract void loadData(long data, int size)
```


Verileri verilen konumdan yükle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | long |  |
| boyut | int |  |

