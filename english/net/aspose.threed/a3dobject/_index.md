---
title: A3DObject
second_title: Aspose.3D for .NET API Reference
description: 
type: docs
weight: 10
url: /net/aspose.threed/a3dobject/
---
## A3DObject class

The base class of all Aspose.ThreeD objects, all sub classes will support dynamic properties.

```csharp
public class A3DObject
```

## Constructors

| Name | Description |
| --- | --- |
| [A3DObject](a3dobject)() | Initializes a new instance of the [`A3DObject`](../a3dobject) class with no name. |
| [A3DObject](a3dobject)(string) | Initializes a new instance of the [`A3DObject`](../a3dobject) class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [Name](name) { get; set; } | Gets or sets the name. |
| [Properties](properties) { get; } | Gets the collection of all properties. |

## Methods

| Name | Description |
| --- | --- |
| [FindProperty](findproperty)(string) | Finds the property. It can be a dynamic property (Created by CreateDynamicProperty/SetProperty) or native property(Identified by its name) |
| [GetProperty](getproperty)(string) | Get the value of specified property |
| [RemoveProperty](removeproperty)(Property) | Removes a dynamic property. |
| [RemoveProperty](removeproperty)(string) | Remove the specified property identified by name |
| [SetProperty](setproperty)(string, object) | Sets the value of specified property |

### See Also

* namespace [Aspose.ThreeD](../../aspose.threed)
* assembly [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->