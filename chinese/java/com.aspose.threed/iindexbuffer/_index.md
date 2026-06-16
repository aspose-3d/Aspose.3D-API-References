---
title: "IIndexBuffer"
second_title: "Aspose.3D for Java API 参考"
description: "索引缓冲区描述了渲染管线中使用的几何体。"
type: docs
weight: 242
url: /zh/java/com.aspose.threed/iindexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IIndexBuffer extends IBuffer
```

索引缓冲区描述了渲染管线中使用的几何体。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCount()](#getCount--) | 获取此缓冲区中的索引数量。 |
| [getIndexDataType()](#getIndexDataType--) | 获取每个元素的数据类型。 |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | 从 [TriMesh](../../com.aspose.threed/trimesh) 加载索引数据 |
| [loadData(int[] indices)](#loadData-int---) | 加载索引数据 |
| [loadData(short[] indices)](#loadData-short---) | 加载索引数据 |
### getCount() {#getCount--}
```
public abstract int getCount()
```


获取此缓冲区中的索引数量。

**Returns:**
int - 此缓冲区中的索引数量。
### getIndexDataType() {#getIndexDataType--}
```
public abstract IndexDataType getIndexDataType()
```


获取每个元素的数据类型。

**Returns:**
[IndexDataType](../../com.aspose.threed/indexdatatype) - the data type of each element.
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


从 [TriMesh](../../com.aspose.threed/trimesh) 加载索引数据

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(int[] indices) {#loadData-int---}
```
public abstract void loadData(int[] indices)
```


加载索引数据

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int[] |  |

### loadData(short[] indices) {#loadData-short---}
```
public abstract void loadData(short[] indices)
```


加载索引数据

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | short[] |  |

