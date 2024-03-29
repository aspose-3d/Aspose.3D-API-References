---
title: Bone
second_title: Aspose.3D for .NET API 参考
description: 骨骼定义几何控制点的子集并为每个控制点定义混合权重 Bone./bone对象不能直接使用aSkinDeformer./skindeformer实例用于使几何体变形并且SkinDeformer./skindeformer带有一组骨骼每个骨骼都链接到一个节点 注意几何图形的控制点可以绑定到多个骨骼
type: docs
weight: 180
url: /zh/net/aspose.threed.deformers/bone/
---
## Bone class

骨骼定义几何控制点的子集，并为每个控制点定义混合权重。 [`Bone`](../bone)对象不能直接使用，a[`SkinDeformer`](../skindeformer)实例用于使几何体变形，并且[`SkinDeformer`](../skindeformer)带有一组骨骼，每个骨骼都链接到一个节点。 注意：几何图形的控制点可以绑定到多个骨骼。

```csharp
public class Bone : A3DObject
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Bone](bone#constructor)() | 初始化[`Bone`](../bone)类. |
| [Bone](bone#constructor_1)(string) | 初始化[`Bone`](../bone)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BoneTransform](../../aspose.threed.deformers/bone/bonetransform) { get; set; } | 获取或设置骨骼的变换矩阵。 |
| [Item](../../aspose.threed.deformers/bone/item) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | 获取或设置名称。 |
| [Node](../../aspose.threed.deformers/bone/node) { get; set; } | 获取或设置节点。骨骼节点是皮肤附着的骨骼，[`SkinDeformer`](../skindeformer)将使用骨骼节点来影响控制点的位移。 骨骼节点通常有一个[`Skeleton`](../../aspose.threed.entities/skeleton)附加，但不是必需的。 附加[`Skeleton`](../../aspose.threed.entities/skeleton)通常由 DCC 软件用于向用户显示骨架。 |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | 获取所有属性的集合。 |
| [Transform](../../aspose.threed.deformers/bone/transform) { get; set; } | 获取或设置包含骨骼的节点的变换矩阵。 |
| [WeightCount](../../aspose.threed.deformers/bone/weightcount) { get; } | 获取重量计数，这会自动扩展[`SetWeight`](./setweight) |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | 查找属性。 可以是动态属性（由 CreateDynamicProperty/SetProperty 创建） 或原生属性（由其名称标识） |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | 获取指定属性的值 |
| [GetWeight](../../aspose.threed.deformers/bone/getweight)(int) | 获取 index 指定的控制点的权重 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | 删除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | 移除名称标识的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | 设置指定属性的值 |
| [SetWeight](../../aspose.threed.deformers/bone/setweight)(int, double) | 为 index 指定的控制点设置权重 |

### 也可以看看

* class [A3DObject](../../aspose.threed/a3dobject)
* 命名空间 [Aspose.ThreeD.Deformers](../../aspose.threed.deformers)
* 部件 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
