---
title: Class Skeleton
second_title: Aspose.3D for .NET API Reference
description: Aspose.ThreeD.Entities.Skeleton class. The Skeleton is mainly used by CAD software to help designer to manipulate the transformation of skeletal structure its usually useless outside the CAD softwares. To make the skeleton hierarchy acts like one object in CAD software its necessary to mark the top Skeleton node as the root one by setting Type to Skeleton and all children set to Bone
type: docs
weight: 680
url: /net/aspose.threed.entities/skeleton/
---
## Skeleton class

The `Skeleton` is mainly used by CAD software to help designer to manipulate the transformation of skeletal structure, it's usually useless outside the CAD softwares. To make the skeleton hierarchy acts like one object in CAD software, it's necessary to mark the top `Skeleton` node as the root one by setting [`Type`](./type/) to Skeleton, and all children set to Bone

```csharp
public class Skeleton : Entity
```

## Constructors

| Name | Description |
| --- | --- |
| [Skeleton](skeleton/#constructor)() | Initializes a new instance of the `Skeleton` class. |
| [Skeleton](skeleton/#constructor_1)(string) | Initializes a new instance of the `Skeleton` class. |
| [Skeleton](skeleton/#constructor_2)(string, SkeletonType) | Initializes a new instance of the `Skeleton` class. |

## Properties

| Name | Description |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Gets or sets whether to exclude this entity during exporting. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Gets or sets the name. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Gets or sets the first parent node, if set the first parent node, this entity will be detached from other parent nodes. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Gets all parent nodes, an entity can be attached to multiple parent nodes for geometry instancing |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gets the collection of all properties. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Gets the scene that this object belongs to |
| [Size](../../aspose.threed.entities/skeleton/size/) { get; set; } | Gets or sets the limb node size that used in CAD software to represent the size of the bone. |
| [Type](../../aspose.threed.entities/skeleton/type/) { get; set; } | Gets or sets the type of the skeleton. |

## Methods

| Name | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Finds the property. It can be a dynamic property (Created by CreateDynamicProperty/SetProperty) or native property(Identified by its name) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Gets the bounding box of current entity in its object space coordinate system. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Gets the key of the entity renderer registered in the renderer |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Get the value of specified property |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Removes a dynamic property. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Remove the specified property identified by name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Sets the value of specified property |

### See Also

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


