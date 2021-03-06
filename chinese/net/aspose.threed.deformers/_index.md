---
title: Aspose.ThreeD.Deformers
second_title: Aspose.3D for .NET API 参考
description: 所有变形器类都定义在这个命名空间
type: docs
weight: 30
url: /zh/net/aspose.threed.deformers/
---
所有变形器类都定义在这个命名空间

## 课程

| 班级 | 描述 |
| --- | --- |
| [Bone](./bone) | 骨骼定义几何控制点的子集，并为每个控制点定义混合权重。 [`Bone`](../aspose.threed.deformers/bone)对象不能直接使用，一个[`SkinDeformer`](../aspose.threed.deformers/skindeformer)实例用于使几何体变形，并且[`SkinDeformer`](../aspose.threed.deformers/skindeformer)带有一组骨骼，每个骨骼都链接到一个节点。 注意:几何图形的控制点可以绑定到多个骨骼。 |
| [Deformer](./deformer) | [`SkinDeformer`](../aspose.threed.deformers/skindeformer)和MorphTargetDeformer的基类 |
| [MorphTargetChannel](./morphtargetchannel) | MorphTargetChannel 被[`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer)用于组织目标几何。 FBX 等一些文件格式支持并行的多个通道。 |
| [MorphTargetDeformer](./morphtargetdeformer) | MorphTargetDeformer 提供逐顶点动画。 MorphTargetDeformer 通过[`MorphTargetChannel`](../aspose.threed.deformers/morphtargetchannel)组织所有目标，每个通道可以组织多个目标。 变形目标变形器的一个常见用途是将面部表情应用于角色。 更多细节可以在 https://en.wikipedia.org/wiki/Morph_target_animation |
| [SkinDeformer](./skindeformer) | 皮肤变形器包含多个要工作的骨骼，每个骨骼通过控制点的权重混合几何的一部分。 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
