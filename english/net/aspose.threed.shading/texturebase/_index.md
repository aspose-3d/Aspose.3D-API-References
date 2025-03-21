---
title: Class TextureBase
second_title: Aspose.3D for .NET API Reference
description: Aspose.ThreeD.Shading.TextureBase class. Base class for all concrete textures. Texture defines the look and feel of a geometry surface
type: docs
weight: 2510
url: /net/aspose.threed.shading/texturebase/
---
## TextureBase class

Base class for all concrete textures. Texture defines the look and feel of a geometry surface.

```csharp
public class TextureBase : A3DObject
```

## Constructors

| Name | Description |
| --- | --- |
| [TextureBase](texturebase/)(string) | Initializes a new instance of the `TextureBase` class. |

## Properties

| Name | Description |
| --- | --- |
| [Alpha](../../aspose.threed.shading/texturebase/alpha/) { get; set; } | Gets or sets the default alpha value of the texture This is valid when the [`AlphaSource`](./alphasource/) is PixelAlpha Default value is 1.0, valid value range is between 0 and 1 |
| [AlphaSource](../../aspose.threed.shading/texturebase/alphasource/) { get; set; } | Gets or sets whether the texture defines the alpha channel. Default value is None |
| [MagFilter](../../aspose.threed.shading/texturebase/magfilter/) { get; set; } | Gets or sets the filter for magnification. |
| [MinFilter](../../aspose.threed.shading/texturebase/minfilter/) { get; set; } | Gets or sets the filter for minification. |
| [MipFilter](../../aspose.threed.shading/texturebase/mipfilter/) { get; set; } | Gets or sets the filter for mip-level sampling. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Gets or sets the name. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gets the collection of all properties. |
| [UVRotation](../../aspose.threed.shading/texturebase/uvrotation/) { get; set; } | Gets or sets the rotation of the texture |
| [UVScale](../../aspose.threed.shading/texturebase/uvscale/) { get; set; } | Gets or sets the UV scale. |
| [UVTranslation](../../aspose.threed.shading/texturebase/uvtranslation/) { get; set; } | Gets or sets the UV translation. |
| [WrapModeU](../../aspose.threed.shading/texturebase/wrapmodeu/) { get; set; } | Gets or sets the texture wrap modes in U. |
| [WrapModeV](../../aspose.threed.shading/texturebase/wrapmodev/) { get; set; } | Gets or sets the texture wrap modes in V. |
| [WrapModeW](../../aspose.threed.shading/texturebase/wrapmodew/) { get; set; } | Gets or sets the texture wrap modes in W. |

## Methods

| Name | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Finds the property. It can be a dynamic property (Created by CreateDynamicProperty/SetProperty) or native property(Identified by its name) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Get the value of specified property |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Removes a dynamic property. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Remove the specified property identified by name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Sets the value of specified property |
| [SetRotation](../../aspose.threed.shading/texturebase/setrotation/)(double, double) | Sets the UV rotation. |
| [SetScale](../../aspose.threed.shading/texturebase/setscale/)(double, double) | Sets the UV scale. |
| [SetTranslation](../../aspose.threed.shading/texturebase/settranslation/)(double, double) | Sets the UV translation. |

### See Also

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


