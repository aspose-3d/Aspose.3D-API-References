---
title: Class CustomObject
second_title: Aspose.3D for .NET API Reference
description: Aspose.ThreeD.CustomObject class. Meta data or custom objects used in 3D files are managed by this class. All custom properties are saved as dynamic properties
type: docs
weight: 180
url: /net/aspose.threed/customobject/
---
## CustomObject class

Meta data or custom objects used in 3D files are managed by this class. All custom properties are saved as dynamic properties.

```csharp
public class CustomObject : A3DObject
```

## Constructors

| Name | Description |
| --- | --- |
| [CustomObject](customobject/#constructor)() | Initializes a new instance of the `CustomObject` class. |
| [CustomObject](customobject/#constructor_1)(string) | Initializes a new instance of the `CustomObject` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Gets or sets the name. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gets the collection of all properties. |

## Methods

| Name | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Finds the property. It can be a dynamic property (Created by CreateDynamicProperty/SetProperty) or native property(Identified by its name) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Get the value of specified property |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Removes a dynamic property. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Remove the specified property identified by name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Sets the value of specified property |

### See Also

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


