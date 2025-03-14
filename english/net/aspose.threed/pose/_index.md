---
title: Class Pose
second_title: Aspose.3D for .NET API Reference
description: Aspose.ThreeD.Pose class. The pose is used to store transformation matrix when the geometry is skinned. The pose is a set of BonePose each BonePose saves the concrete transformation information of the bone node
type: docs
weight: 1550
url: /net/aspose.threed/pose/
---
## Pose class

The pose is used to store transformation matrix when the geometry is skinned. The pose is a set of [`BonePose`](../bonepose/), each [`BonePose`](../bonepose/) saves the concrete transformation information of the bone node.

```csharp
public class Pose : A3DObject
```

## Constructors

| Name | Description |
| --- | --- |
| [Pose](pose/#constructor)() | Initializes a new instance of the `Pose` class. |
| [Pose](pose/#constructor_1)(string) | Initializes a new instance of the `Pose` class. |

## Properties

| Name | Description |
| --- | --- |
| [BonePoses](../../aspose.threed/pose/boneposes/) { get; } | Gets all [`BonePose`](../bonepose/). |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Gets or sets the name. |
| [PoseType](../../aspose.threed/pose/posetype/) { get; set; } | Gets or sets the type of the pose. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gets the collection of all properties. |

## Methods

| Name | Description |
| --- | --- |
| [AddBonePose](../../aspose.threed/pose/addbonepose/#addbonepose)(Node, Matrix4) | Saves pose transformation matrix for the given bone node. Global transformation matrix is implied. |
| [AddBonePose](../../aspose.threed/pose/addbonepose/#addbonepose_1)(Node, Matrix4, bool) | Saves pose transformation matrix for the given bone node. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Finds the property. It can be a dynamic property (Created by CreateDynamicProperty/SetProperty) or native property(Identified by its name) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Get the value of specified property |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Removes a dynamic property. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Remove the specified property identified by name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Sets the value of specified property |

### See Also

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


