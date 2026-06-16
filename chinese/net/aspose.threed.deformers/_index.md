---
title: "Aspose.ThreeD.Deformers"
second_title: "Aspose.3D for .NET API 参考"
description: "所有变形器类都定义在此命名空间中"
type: docs
weight: 30
url: /zh/net/aspose.threed.deformers/
---
所有变形器类都定义在此命名空间中

## 类

| 类 | 描述 |
| --- | --- |
| [Bone](./bone/) | 骨骼定义了几何体控制点的子集，并为每个控制点定义了混合权重。[`Bone`](../aspose.threed.deformers/bone/) 对象不能直接使用，需要使用 [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) 实例来变形几何体，且 [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) 带有一组骨骼，每个骨骼链接到一个节点。注意：几何体的一个控制点可以绑定到多个骨骼。 |
| [Deformer](./deformer/) | `[`SkinDeformer`](../aspose.threed.deformers/skindeformer/)` 和 [`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer/) 的基类 |
| [MorphTargetChannel](./morphtargetchannel/) | MorphTargetChannel 被 [`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer/) 用于组织目标几何体。某些文件格式，如 FBX，支持并行的多个通道。 |
| [MorphTargetDeformer](./morphtargetdeformer/) | MorphTargetDeformer 提供每顶点动画。MorphTargetDeformer 通过 [`MorphTargetChannel`](../aspose.threed.deformers/morphtargetchannel/) 组织所有目标，每个通道可以组织多个目标。Morph target deformer 的常见用法是为角色应用面部表情。更多细节请参阅 https://en.wikipedia.org/wiki/Morph_target_animation |
| [SkinDeformer](./skindeformer/) | Skin deformer 包含多个骨骼进行工作，每个骨骼通过控制点的权重混合几何体的一部分。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [BoneLinkMode](./bonelinkmode/) | 骨骼的链接模式指的是骨骼在层次结构中与其父骨骼连接或链接的方式。 |


