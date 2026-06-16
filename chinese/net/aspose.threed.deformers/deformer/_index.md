---
title: "类 Deformer"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Deformers.Deformer 类。SkinDeformer 和 MorphTargetDeformer 的基类"
type: docs
weight: 210
url: /zh/net/aspose.threed.deformers/deformer/
---
## Deformer class

[`SkinDeformer`](../skindeformer/) 和 [`MorphTargetDeformer`](../morphtargetdeformer/) 的基类

```csharp
public abstract class Deformer : A3DObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Deformer](deformer/)(string) | 初始化 `Deformer` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
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

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


