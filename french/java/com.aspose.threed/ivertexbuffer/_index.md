---
title: "IVertexBuffer"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Le tampon de sommets contient les données de sommets du polygone qui seront envoyées au pipeline de rendu."
type: docs
weight: 259
url: /fr/java/com.aspose.threed/ivertexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IVertexBuffer extends IBuffer
```

Le tampon de sommets contient les données de sommets du polygone qui seront envoyées au pipeline de rendu.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getVertexDeclaration()](#getVertexDeclaration--) | Obtient la déclaration du sommet |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | Charge les données de sommet depuis [TriMesh](../../com.aspose.threed/trimesh) |
| [loadData(Object array)](#loadData-java.lang.Object-) | Charge les données depuis un tableau |
| [loadData(long data, int size)](#loadData-long-int-) | Charge les données depuis la position donnée |
### getVertexDeclaration() {#getVertexDeclaration--}
```
public abstract VertexDeclaration getVertexDeclaration()
```


Obtient la déclaration du sommet

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - the vertex declaration
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


Charge les données de sommet depuis [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(Object array) {#loadData-java.lang.Object-}
```
public abstract void loadData(Object array)
```


Charge les données depuis un tableau

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tableau | java.lang.Object |  |

### loadData(long data, int size) {#loadData-long-int-}
```
public abstract void loadData(long data, int size)
```


Charge les données depuis la position donnée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | long |  |
| taille | int |  |

