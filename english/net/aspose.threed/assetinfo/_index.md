---
title: Class AssetInfo
second_title: Aspose.3D for .NET API Reference
description: Aspose.ThreeD.AssetInfo class. Information of asset. Asset information can be attached to a Scene. Child Scene can have its own AssetInfo to override parents definition
type: docs
weight: 130
url: /net/aspose.threed/assetinfo/
---
## AssetInfo class

Information of asset. Asset information can be attached to a [`Scene`](../scene/). Child [`Scene`](../scene/) can have its own `AssetInfo` to override parent's definition.

```csharp
public class AssetInfo : A3DObject
```

## Constructors

| Name | Description |
| --- | --- |
| [AssetInfo](assetinfo/#constructor)() | Initializes a new instance of the `AssetInfo` class. |
| [AssetInfo](assetinfo/#constructor_1)(string) | Initializes a new instance of the `AssetInfo` class. |

## Properties

| Name | Description |
| --- | --- |
| [Ambient](../../aspose.threed/assetinfo/ambient/) { get; set; } | Gets or Sets the default ambient color of this asset |
| [ApplicationName](../../aspose.threed/assetinfo/applicationname/) { get; set; } | Gets or sets the application that created this asset |
| [ApplicationVendor](../../aspose.threed/assetinfo/applicationvendor/) { get; set; } | Gets or sets the application vendor's name |
| [ApplicationVersion](../../aspose.threed/assetinfo/applicationversion/) { get; set; } | Gets or sets the version of the application that created this asset. |
| [Author](../../aspose.threed/assetinfo/author/) { get; set; } | Gets or sets the author of this asset |
| [AxisSystem](../../aspose.threed/assetinfo/axissystem/) { get; set; } | Gets or sets the coordinate system/up vector/front vector of the asset info. |
| [Comment](../../aspose.threed/assetinfo/comment/) { get; set; } | Gets or sets the comment of this asset. |
| [CoordinateSystem](../../aspose.threed/assetinfo/coordinatesystem/) { get; set; } | Gets or sets the coordinate system used in this asset. |
| [Copyright](../../aspose.threed/assetinfo/copyright/) { get; set; } | Gets or sets the document's copyright |
| [CreationTime](../../aspose.threed/assetinfo/creationtime/) { get; set; } | Gets or Sets the creation time of this asset |
| [FrontVector](../../aspose.threed/assetinfo/frontvector/) { get; set; } | Gets or sets the front-vector used in this asset. |
| [Keywords](../../aspose.threed/assetinfo/keywords/) { get; set; } | Gets or sets the keywords of this asset |
| [ModificationTime](../../aspose.threed/assetinfo/modificationtime/) { get; set; } | Gets or Sets the modification time of this asset |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Gets or sets the name. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gets the collection of all properties. |
| [Revision](../../aspose.threed/assetinfo/revision/) { get; set; } | Gets or sets the revision number of this asset, usually used in version control system. |
| [Subject](../../aspose.threed/assetinfo/subject/) { get; set; } | Gets or sets the subject of this asset |
| [Title](../../aspose.threed/assetinfo/title/) { get; set; } | Gets or sets the title of this asset |
| [UnitName](../../aspose.threed/assetinfo/unitname/) { get; set; } | Gets or sets the unit of length used in this asset. e.g. cm/m/km/inch/feet |
| [UnitScaleFactor](../../aspose.threed/assetinfo/unitscalefactor/) { get; set; } | Gets or sets the scale factor to real-world meter. |
| [UpVector](../../aspose.threed/assetinfo/upvector/) { get; set; } | Gets or sets the up-vector used in this asset. |
| [Url](../../aspose.threed/assetinfo/url/) { get; set; } | Gets or Sets the URL of this asset. |

## Methods

| Name | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Finds the property. It can be a dynamic property (Created by CreateDynamicProperty/SetProperty) or native property(Identified by its name) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Get the value of specified property |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Removes a dynamic property. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Remove the specified property identified by name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Sets the value of specified property |

## Examples

The following code shows how to read asset info from a fbx file:

```csharp
Scene scene = Scene.FromFile("test.fbx");
Console.WriteLine($"The file is created at {scene.AssetInfo.CreationTime} by {scene.AssetInfo.ApplicationName} {scene.AssetInfo.ApplicationVersion} ");
```

### See Also

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


