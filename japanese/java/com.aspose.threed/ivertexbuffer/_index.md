---
title: IVertexBuffer
second_title: Aspose.3D for Java API リファレンス
description: 頂点バッファは、レンダリングパイプラインに送られるポリゴンの頂点データを保持します。
type: docs
weight: 259
url: /ja/java/com.aspose.threed/ivertexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IVertexBuffer extends IBuffer
```

頂点バッファは、レンダリングパイプラインに送られるポリゴンの頂点データを保持します。
## Methods

| Method | 説明 |
| --- | --- |
| [getVertexDeclaration()](#getVertexDeclaration--) | 頂点宣言を取得します。 |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | [TriMesh](../../com.aspose.threed/trimesh) から頂点データをロードします。 |
| [loadData(Object array)](#loadData-java.lang.Object-) | 配列からデータをロードします。 |
| [loadData(long data, int size)](#loadData-long-int-) | 指定された位置からデータをロードします。 |
### getVertexDeclaration() {#getVertexDeclaration--}
```
public abstract VertexDeclaration getVertexDeclaration()
```


頂点宣言を取得します。

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - the vertex declaration
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


[TriMesh](../../com.aspose.threed/trimesh) から頂点データをロードします。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(Object array) {#loadData-java.lang.Object-}
```
public abstract void loadData(Object array)
```


配列からデータをロードします。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 配列 | java.lang.Object |  |

### loadData(long data, int size) {#loadData-long-int-}
```
public abstract void loadData(long data, int size)
```


指定された位置からデータをロードします。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| データ | long |  |
| サイズ | int |  |

