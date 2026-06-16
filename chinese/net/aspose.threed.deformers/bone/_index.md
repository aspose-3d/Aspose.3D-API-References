---
title: "类 Bone"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Deformers.Bone 类。骨骼定义了几何体控制点的子集，并为每个控制点定义了混合权重。Bone 对象不能直接使用，需使用 SkinDeformer 实例来变形几何体，SkinDeformer 附带一组骨骼，每个骨骼链接到一个节点。注意：几何体的控制点可以绑定到多个骨骼。"
type: docs
weight: 190
url: /zh/net/aspose.threed.deformers/bone/
---
## Bone class

骨骼定义了几何体控制点的子集，并为每个控制点定义了混合权重。`Bone` 对象不能直接使用，需使用 [`SkinDeformer`](../skindeformer/) 实例来变形几何体，且 [`SkinDeformer`](../skindeformer/) 附带一组骨骼，每个骨骼链接到一个节点。注意：几何体的控制点可以绑定到多个骨骼。

```csharp
public class Bone : A3DObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Bone](bone/#constructor)() | 初始化 `Bone` 类的新实例。 |
| [Bone](bone/#constructor_1)(string) | 初始化 `Bone` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BoneTransform](../../aspose.threed.deformers/bone/bonetransform/) { get; set; } | 获取或设置骨骼的变换矩阵。 |
| [Item](../../aspose.threed.deformers/bone/item/) { get; set; } |  |
| [LinkMode](../../aspose.threed.deformers/bone/linkmode/) { get; set; } | 骨骼的链接模式指的是骨骼在层次结构中与其父骨骼连接或链接的方式。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [Node](../../aspose.threed.deformers/bone/node/) { get; set; } | 获取或设置节点。骨骼节点是皮肤附着的骨骼，[`SkinDeformer`](../skindeformer/) 将使用骨骼节点来影响控制点的位移。骨骼节点通常附带一个 [`Skeleton`](../../aspose.threed.entities/skeleton/)，但这不是必需的。附加的 [`Skeleton`](../../aspose.threed.entities/skeleton/) 通常由 DCC 软件用于向用户显示骨架。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Transform](../../aspose.threed.deformers/bone/transform/) { get; set; } | 获取或设置包含骨骼的节点的变换矩阵。 |
| [WeightCount](../../aspose.threed.deformers/bone/weightcount/) { get; } | 获取权重计数，该计数会被 [`SetWeight`](./setweight/) 自动扩展。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [GetWeight](../../aspose.threed.deformers/bone/getweight/)(int) | 获取由索引指定的控制点的权重 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |
| [SetWeight](../../aspose.threed.deformers/bone/setweight/)(int, double) | 设置由索引指定的控制点的权重 |

### 另请参见

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


