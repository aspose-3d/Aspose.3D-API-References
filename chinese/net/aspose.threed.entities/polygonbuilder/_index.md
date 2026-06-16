---
title: "类 PolygonBuilder"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Entities.PolygonBuilder 类。用于为 Mesh 构建多边形的辅助类"
type: docs
weight: 610
url: /zh/net/aspose.threed.entities/polygonbuilder/
---
## PolygonBuilder class

用于为 [`Mesh`](../mesh/) 构建多边形的辅助类。

```csharp
public sealed class PolygonBuilder
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PolygonBuilder](polygonbuilder/)(Mesh) | 初始化 `PolygonBuilder` 类的新实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddVertex](../../aspose.threed.entities/polygonbuilder/addvertex/)(int) | 向多边形添加顶点索引 |
| [Begin](../../aspose.threed.entities/polygonbuilder/begin/)() | 开始添加新多边形 |
| [End](../../aspose.threed.entities/polygonbuilder/end/)() | 完成多边形创建 |

## 示例

```csharp
Mesh mesh = new Mesh();
PolygonBuilder builder = new PolygonBuilder(mesh);
builder.Begin();
builder.AddVertex(0);
builder.AddVertex(1);
builder.AddVertex(2);
builder.End();
```

等于：

```csharp
Mesh mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

如果所有索引都已准备好使用，建议使用 [`CreatePolygon`](../mesh/createpolygon/)，否则 `PolygonBuilder` 将是更好的选择。

### 另请参见

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


