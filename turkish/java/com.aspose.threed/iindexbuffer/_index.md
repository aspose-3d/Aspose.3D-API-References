---
title: "IIndexBuffer"
second_title: "Aspose.3D for Java API Referansı"
description: "İndeks tamponu, render boru hattında kullanılan geometrileri tanımlar."
type: docs
weight: 242
url: /tr/java/com.aspose.threed/iindexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IIndexBuffer extends IBuffer
```

İndeks tamponu, render boru hattında kullanılan geometrileri tanımlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCount()](#getCount--) | Bu tampondaki indeks sayısını alır. |
| [getIndexDataType()](#getIndexDataType--) | Her öğenin veri tipini alır. |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | İndeks verisini [TriMesh](../../com.aspose.threed/trimesh) adresinden yükle |
| [loadData(int[] indices)](#loadData-int---) | İndeks verisini yükle |
| [loadData(short[] indices)](#loadData-short---) | İndeks verisini yükle |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Bu tampondaki indeks sayısını alır.

**Returns:**
int - bu tampondaki indeks sayısı.
### getIndexDataType() {#getIndexDataType--}
```
public abstract IndexDataType getIndexDataType()
```


Her öğenin veri tipini alır.

**Returns:**
[IndexDataType](../../com.aspose.threed/indexdatatype) - the data type of each element.
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


İndeks verisini [TriMesh](../../com.aspose.threed/trimesh) adresinden yükle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(int[] indices) {#loadData-int---}
```
public abstract void loadData(int[] indices)
```


İndeks verisini yükle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeksler | int[] |  |

### loadData(short[] indices) {#loadData-short---}
```
public abstract void loadData(short[] indices)
```


İndeks verisini yükle

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeksler | short[] |  |

