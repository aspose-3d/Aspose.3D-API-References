---
title: IIndexBuffer
second_title: Aspose.3D for Java API-referentie
description: De indexbuffer beschrijft de geometrie die wordt gebruikt in de renderpipeline.
type: docs
weight: 242
url: /nl/java/com.aspose.threed/iindexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IIndexBuffer extends IBuffer
```

De indexbuffer beschrijft de geometrie die wordt gebruikt in de renderpipeline.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCount()](#getCount--) | Haalt het aantal indexen in deze buffer op. |
| [getIndexDataType()](#getIndexDataType--) | Haalt het gegevenstype van elk element op. |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | Laad indice-gegevens van [TriMesh](../../com.aspose.threed/trimesh) |
| [loadData(int[] indices)](#loadData-int---) | Laad indice-gegevens |
| [loadData(short[] indices)](#loadData-short---) | Laad indice-gegevens |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Haalt het aantal indexen in deze buffer op.

**Returns:**
int - het aantal indexen in deze buffer.
### getIndexDataType() {#getIndexDataType--}
```
public abstract IndexDataType getIndexDataType()
```


Haalt het gegevenstype van elk element op.

**Returns:**
[IndexDataType](../../com.aspose.threed/indexdatatype) - the data type of each element.
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


Laad indice-gegevens van [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(int[] indices) {#loadData-int---}
```
public abstract void loadData(int[] indices)
```


Laad indice-gegevens

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| indices | int[] |  |

### loadData(short[] indices) {#loadData-short---}
```
public abstract void loadData(short[] indices)
```


Laad indice-gegevens

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| indices | short[] |  |

