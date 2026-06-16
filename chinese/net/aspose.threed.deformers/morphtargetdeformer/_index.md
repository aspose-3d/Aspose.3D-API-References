---
title: "类 MorphTargetDeformer"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Deformers.MorphTargetDeformer 类。MorphTargetDeformer 提供每顶点动画。MorphTargetDeformer 通过 MorphTargetChannel 组织所有目标，每个通道可以组织多个目标。MorphTargetDeformer 的常见用途是为角色应用面部表情。更多细节请参阅 https//en.wikipedia.org/wiki/Morph_target_animation"
type: docs
weight: 230
url: /zh/net/aspose.threed.deformers/morphtargetdeformer/
---
## MorphTargetDeformer class

MorphTargetDeformer 提供每顶点动画。MorphTargetDeformer 通过 [`MorphTargetChannel`](../morphtargetchannel/) 组织所有目标，每个通道可以组织多个目标。MorphTargetDeformer 的常见用途是为角色应用面部表情。更多细节请参阅 https://en.wikipedia.org/wiki/Morph_target_animation

```csharp
public class MorphTargetDeformer : Deformer
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MorphTargetDeformer](morphtargetdeformer/#constructor)() | 初始化 `MorphTargetDeformer` 类的新实例。 |
| [MorphTargetDeformer](morphtargetdeformer/#constructor_1)(string) | 初始化 `MorphTargetDeformer` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Channels](../../aspose.threed.deformers/morphtargetdeformer/channels/) { get; } | 获取此变形器中包含的所有通道 |
| [Item](../../aspose.threed.deformers/morphtargetdeformer/item/) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [Owner](../../aspose.threed.deformers/deformer/owner/) { get; } | 获取拥有此变形器的几何体 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |

### 另请参见

* class [Deformer](../deformer/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


