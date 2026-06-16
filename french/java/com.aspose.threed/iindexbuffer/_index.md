---
title: "IIndexBuffer"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Le tampon d'index décrit la géométrie utilisée dans le pipeline de rendu."
type: docs
weight: 242
url: /fr/java/com.aspose.threed/iindexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IIndexBuffer extends IBuffer
```

Le tampon d'index décrit la géométrie utilisée dans le pipeline de rendu.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCount()](#getCount--) | Obtient le nombre d'indices dans ce tampon. |
| [getIndexDataType()](#getIndexDataType--) | Obtient le type de données de chaque élément. |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | Charge les données d'indices depuis [TriMesh](../../com.aspose.threed/trimesh) |
| [loadData(int[] indices)](#loadData-int---) | Charge les données d'indices |
| [loadData(short[] indices)](#loadData-short---) | Charge les données d'indices |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Obtient le nombre d'indices dans ce tampon.

**Returns:**
int - le nombre d'indices dans ce tampon.
### getIndexDataType() {#getIndexDataType--}
```
public abstract IndexDataType getIndexDataType()
```


Obtient le type de données de chaque élément.

**Returns:**
[IndexDataType](../../com.aspose.threed/indexdatatype) - the data type of each element.
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


Charge les données d'indices depuis [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(int[] indices) {#loadData-int---}
```
public abstract void loadData(int[] indices)
```


Charge les données d'indices

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indices | int[] |  |

### loadData(short[] indices) {#loadData-short---}
```
public abstract void loadData(short[] indices)
```


Charge les données d'indices

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indices | short[] |  |

