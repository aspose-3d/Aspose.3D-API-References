---
title: "Entity.GetBoundingBox"
second_title: "Aspose.3D for .NET API 参考"
description: "Entity 方法。获取当前实体在其对象空间坐标系中的边界框"
type: docs
weight: 50
url: /zh/net/aspose.threed/entity/getboundingbox/
---
## Entity.GetBoundingBox method

获取当前实体在其对象空间坐标系中的包围盒。

```csharp
public BoundingBox GetBoundingBox()
```

### 返回值

当前实体在其对象空间坐标系中的边界框。

## 示例

以下代码展示了如何计算形状的边界框

```csharp
Entity entity = new Sphere() { Radius = 10 };
var bbox = entity.GetBoundingBox();
Console.WriteLine($"The bounding box of the entity is {bbox.Minimum} ~ {bbox.Maximum}");
```

### 另请参见

* struct [BoundingBox](../../../aspose.threed.utilities/boundingbox/)
* class [Entity](../)
* namespace [Aspose.ThreeD](../../entity/)
* assembly [Aspose.3D](../../../)


