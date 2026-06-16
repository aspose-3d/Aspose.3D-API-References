---
title: "接口 IIndexBuffer"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Render.IIndexBuffer 接口。索引缓冲区描述渲染管线中使用的几何体"
type: docs
weight: 2050
url: /zh/net/aspose.threed.render/iindexbuffer/
---
## IIndexBuffer interface

索引缓冲区描述了渲染管线中使用的几何体。

```csharp
public interface IIndexBuffer : IBuffer
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.threed.render/iindexbuffer/count/) { get; } | 获取此缓冲区中的索引数量。 |
| [IndexDataType](../../aspose.threed.render/iindexbuffer/indexdatatype/) { get; } | 获取每个元素的数据类型。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [LoadData](../../aspose.threed.render/iindexbuffer/loaddata/#loaddata_2)(int[]) | 加载索引数据 |
| [LoadData](../../aspose.threed.render/iindexbuffer/loaddata/#loaddata_1)(short[]) | 加载索引数据 |
| [LoadData](../../aspose.threed.render/iindexbuffer/loaddata/#loaddata)(TriMesh) | 从[`TriMesh`](../../aspose.threed.entities/trimesh/)加载索引数据 |
| [LoadData](../../aspose.threed.render/iindexbuffer/loaddata/#loaddata_3)(uint[]) | 加载索引数据 |

### 另请参见

* interface [IBuffer](../ibuffer/)
* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


