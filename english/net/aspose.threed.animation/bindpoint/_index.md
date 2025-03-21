---
title: Class BindPoint
second_title: Aspose.3D for .NET API Reference
description: Aspose.ThreeD.Animation.BindPoint class. A BindPoint is usually created on an objects property some property types contains multiple component fieldslike a Vector3 field BindPoint will generate channel for each component field and connects the field to one or more keyframe sequence instances through the channels
type: docs
weight: 50
url: /net/aspose.threed.animation/bindpoint/
---
## BindPoint class

A `BindPoint` is usually created on an object's property, some property types contains multiple component fields(like a Vector3 field), `BindPoint` will generate channel for each component field and connects the field to one or more keyframe sequence instance(s) through the channels.

```csharp
public class BindPoint : A3DObject
```

## Constructors

| Name | Description |
| --- | --- |
| [BindPoint](bindpoint/)(Scene, Property) | Initializes a new instance of the `BindPoint` class. |

## Properties

| Name | Description |
| --- | --- |
| [ChannelsCount](../../aspose.threed.animation/bindpoint/channelscount/) { get; } | Gets the total number of property channels defined in this animation curve mapping. |
| [Item](../../aspose.threed.animation/bindpoint/item/) { get; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Gets or sets the name. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gets the collection of all properties. |
| [Property](../../aspose.threed.animation/bindpoint/property/) { get; } | Gets the property associated with the CurveMapping |

## Methods

| Name | Description |
| --- | --- |
| [AddChannel](../../aspose.threed.animation/bindpoint/addchannel/#addchannel)(string, object) | Adds the specified channel property. |
| [AddChannel](../../aspose.threed.animation/bindpoint/addchannel/#addchannel_1)(string, Type, object) | Adds the specified channel property. |
| [AddChannel&lt;T&gt;](../../aspose.threed.animation/bindpoint/addchannel/#addchannel_2)(string, T) |  |
| [BindKeyframeSequence](../../aspose.threed.animation/bindpoint/bindkeyframesequence/)(string, KeyframeSequence) | Bind the keyframe sequence to specified channel |
| [CreateKeyframeSequence](../../aspose.threed.animation/bindpoint/createkeyframesequence/)(string) | Creates a new curve and connects it to the first channel of the curve mapping |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Finds the property. It can be a dynamic property (Created by CreateDynamicProperty/SetProperty) or native property(Identified by its name) |
| [GetChannel](../../aspose.threed.animation/bindpoint/getchannel/)(string) | Gets channel by given name |
| [GetKeyframeSequence](../../aspose.threed.animation/bindpoint/getkeyframesequence/)(string) | Gets the first keyframe sequence in specified channel |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Get the value of specified property |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Removes a dynamic property. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Remove the specified property identified by name |
| [ResetChannels](../../aspose.threed.animation/bindpoint/resetchannels/)() | Empties the property channels of this animation curve mapping. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Sets the value of specified property |
| override [ToString](../../aspose.threed.animation/bindpoint/tostring/)() | Formats object to string |

### See Also

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


