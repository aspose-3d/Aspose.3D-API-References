---
title: "类 MorphTargetChannel"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Deformers.MorphTargetChannel 类。MorphTargetChannel 被 MorphTargetDeformer 用于组织目标几何体。某些文件格式如 FBX 支持并行的多个通道。"
type: docs
weight: 220
url: /zh/net/aspose.threed.deformers/morphtargetchannel/
---
## MorphTargetChannel class

MorphTargetChannel 被 [`MorphTargetDeformer`](../morphtargetdeformer/) 用于组织目标几何体。某些文件格式如 FBX 支持并行的多个通道。

```csharp
public class MorphTargetChannel : A3DObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MorphTargetChannel](morphtargetchannel/#constructor)() | 初始化 `MorphTargetChannel` 类的新实例。 |
| [MorphTargetChannel](morphtargetchannel/#constructor_1)(string) | 初始化 `MorphTargetChannel` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ChannelWeight](../../aspose.threed.deformers/morphtargetchannel/channelweight/) { get; set; } | 获取或设置此通道的变形器权重。权重介于 0.0 到 1.0 之间。 |
| [Item](../../aspose.threed.deformers/morphtargetchannel/item/) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Targets](../../aspose.threed.deformers/morphtargetchannel/targets/) { get; } | 获取与通道关联的所有目标。 |
| [Weights](../../aspose.threed.deformers/morphtargetchannel/weights/) { get; } | 获取目标几何体的完整权重值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [GetWeight](../../aspose.threed.deformers/morphtargetchannel/getweight/)(Shape) | 获取指定目标的权重，如果目标不属于此通道，则返回默认值 0。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |
| [SetWeight](../../aspose.threed.deformers/morphtargetchannel/setweight/)(Shape, double) | 设置指定目标的权重，默认值为 1，范围应在 0~1 之间。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [DefaultWeight](../../aspose.threed.deformers/morphtargetchannel/defaultweight/) | 形变目标的默认权重。 |

## 备注

权重在 0 到 1.0 之间，目标的默认权重为 0.0；

### 另请参见

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


