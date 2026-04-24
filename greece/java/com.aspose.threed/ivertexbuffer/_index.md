---
title: IVertexBuffer
second_title: Aspose.3D for Java API Reference
description: Το buffer κορυφών διατηρεί τα δεδομένα κορυφών του πολυγώνου που θα σταλούν στην αλυσίδα απόδοσης.
type: docs
weight: 259
url: /el/java/com.aspose.threed/ivertexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IVertexBuffer extends IBuffer
```

Το buffer κορυφών διατηρεί τα δεδομένα κορυφών του πολυγώνου που θα σταλούν στην αλυσίδα απόδοσης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVertexDeclaration()](#getVertexDeclaration--) | Λαμβάνει τη δήλωση της κορυφής |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | Φορτώνει δεδομένα κορυφής από [TriMesh](../../com.aspose.threed/trimesh) |
| [loadData(Object array)](#loadData-java.lang.Object-) | Φορτώνει δεδομένα από πίνακα |
| [loadData(long data, int size)](#loadData-long-int-) | Φορτώνει δεδομένα από τη δεδομένη θέση |
### getVertexDeclaration() {#getVertexDeclaration--}
```
public abstract VertexDeclaration getVertexDeclaration()
```


Λαμβάνει τη δήλωση της κορυφής

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - the vertex declaration
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


Φορτώνει δεδομένα κορυφής από [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(Object array) {#loadData-java.lang.Object-}
```
public abstract void loadData(Object array)
```


Φορτώνει δεδομένα από πίνακα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πίνακας | java.lang.Object |  |

### loadData(long data, int size) {#loadData-long-int-}
```
public abstract void loadData(long data, int size)
```


Φορτώνει δεδομένα από τη δεδομένη θέση

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δεδομένα | long |  |
| μέγεθος | int |  |

