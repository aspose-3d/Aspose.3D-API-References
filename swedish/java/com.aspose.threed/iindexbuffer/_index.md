---
title: IIndexBuffer
second_title: Aspose.3D for Java API-referens
description: Indexbufferten beskriver geometrin som används i renderingspipen.
type: docs
weight: 242
url: /sv/java/com.aspose.threed/iindexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IIndexBuffer extends IBuffer
```

Indexbufferten beskriver geometrin som används i renderingspipen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCount()](#getCount--) | Hämtar antalet index i denna buffer. |
| [getIndexDataType()](#getIndexDataType--) | Hämtar datatypen för varje element. |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | Läs in indeksdata från [TriMesh](../../com.aspose.threed/trimesh) |
| [loadData(int[] indices)](#loadData-int---) | Läs in indeksdata |
| [loadData(short[] indices)](#loadData-short---) | Läs in indeksdata |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Hämtar antalet index i denna buffer.

**Returns:**
int - antalet index i denna buffer.
### getIndexDataType() {#getIndexDataType--}
```
public abstract IndexDataType getIndexDataType()
```


Hämtar datatypen för varje element.

**Returns:**
[IndexDataType](../../com.aspose.threed/indexdatatype) - the data type of each element.
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


Läs in indeksdata från [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(int[] indices) {#loadData-int---}
```
public abstract void loadData(int[] indices)
```


Läs in indeksdata

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| indices | int[] |  |

### loadData(short[] indices) {#loadData-short---}
```
public abstract void loadData(short[] indices)
```


Läs in indeksdata

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| indices | short[] |  |

