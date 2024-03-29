---
title: Aspose.ThreeD.Deformers
second_title: Aspose.3D for .NET API Reference
description: All deformer classes are defined in this namespace
type: docs
weight: 30
url: /net/aspose.threed.deformers/
---
All deformer classes are defined in this namespace

## Classes

| Class | Description |
| --- | --- |
| [Bone](./bone/) | A bone defines the subset of the geometry's control point, and defined blend weight for each control point. The [`Bone`](../aspose.threed.deformers/bone/) object cannot be used directly, a [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) instance is used to deform the geometry, and [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) comes with a set of bones, each bone linked to a node. NOTE: A control point of a geometry can be bounded to more than one Bones. |
| [Deformer](./deformer/) | Base class for [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) and [`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer/) |
| [MorphTargetChannel](./morphtargetchannel/) | A MorphTargetChannel is used by [`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer/) to organize the target geometries. Some file formats like FBX support multiple channels in parallel. |
| [MorphTargetDeformer](./morphtargetdeformer/) | MorphTargetDeformer provides per-vertex animation. MorphTargetDeformer organize all targets via [`MorphTargetChannel`](../aspose.threed.deformers/morphtargetchannel/), each channel can organize multiple targets. A common use of morph target deformer is to apply facial expression to a character. More details can be found at https://en.wikipedia.org/wiki/Morph_target_animation |
| [SkinDeformer](./skindeformer/) | A skin deformer contains multiple bones to work, each bone blends a part of the geometry by control point's weights. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [BoneLinkMode](./bonelinkmode/) | A bone's link mode refers to the way in which a bone is connected or linked to its parent bone within a hierarchical structure. |


