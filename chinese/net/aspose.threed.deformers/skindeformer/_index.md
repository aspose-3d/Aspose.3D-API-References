---
title: "SkinDeformer 类"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Deformers.SkinDeformer 类。 皮肤变形器包含多个骨骼，每个骨骼通过控制点权重混合几何体的部分。"
type: docs
weight: 240
url: /zh/net/aspose.threed.deformers/skindeformer/
---
## SkinDeformer class

Skin deformer 包含多个骨骼进行工作，每个骨骼通过控制点的权重混合几何体的一部分。

```csharp
public class SkinDeformer : Deformer
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SkinDeformer](skindeformer/#constructor)() | 初始化 `SkinDeformer` 类的新实例。 |
| [SkinDeformer](skindeformer/#constructor_1)(string) | 初始化 `SkinDeformer` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bones](../../aspose.threed.deformers/skindeformer/bones/) { get; } | 获取皮肤变形器包含的所有骨骼 |
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


