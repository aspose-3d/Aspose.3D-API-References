---
title: IIndexBuffer
second_title: Aspose.3D for Java API リファレンス
description: インデックスバッファは、レンダリングパイプラインで使用されるジオメトリを記述します。
type: docs
weight: 242
url: /ja/java/com.aspose.threed/iindexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IIndexBuffer extends IBuffer
```

インデックスバッファは、レンダリングパイプラインで使用されるジオメトリを記述します。
## Methods

| Method | 説明 |
| --- | --- |
| [getCount()](#getCount--) | このバッファ内のインデックス数を取得します。 |
| [getIndexDataType()](#getIndexDataType--) | 各要素のデータ型を取得します。 |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | [TriMesh](../../com.aspose.threed/trimesh) からインデックスデータをロードします |
| [loadData(int[] indices)](#loadData-int---) | インデックスデータをロードします |
| [loadData(short[] indices)](#loadData-short---) | インデックスデータをロードします |
### getCount() {#getCount--}
```
public abstract int getCount()
```


このバッファ内のインデックス数を取得します。

**Returns:**
int - このバッファ内のインデックス数。
### getIndexDataType() {#getIndexDataType--}
```
public abstract IndexDataType getIndexDataType()
```


各要素のデータ型を取得します。

**Returns:**
[IndexDataType](../../com.aspose.threed/indexdatatype) - the data type of each element.
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


[TriMesh](../../com.aspose.threed/trimesh) からインデックスデータをロードします

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(int[] indices) {#loadData-int---}
```
public abstract void loadData(int[] indices)
```


インデックスデータをロードします

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| インデックス | int[] |  |

### loadData(short[] indices) {#loadData-short---}
```
public abstract void loadData(short[] indices)
```


インデックスデータをロードします

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| インデックス | short[] |  |

