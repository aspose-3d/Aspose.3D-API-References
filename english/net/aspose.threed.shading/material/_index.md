---
title: Material
second_title: Aspose.3D for .NET API Reference
description: 
type: docs
weight: 2280
url: /net/aspose.threed.shading/material/
---
## Material class

Material defines the parameters necessary for visual appearance of geometry. Aspose.3D provides shading model for [`LambertMaterial`](../lambertmaterial), [`PhongMaterial`](../phongmaterial) and [`ShaderMaterial`](../shadermaterial)

```csharp
public abstract class Material : A3DObject, IEnumerable<TextureSlot>
```

## Methods

| Name | Description |
| --- | --- |
| [GetEnumerator](getenumerator)() | Gets the enumerator to enumerate internal texture slots. |
| [GetTexture](gettexture)(string) | Gets the texture from the specified slot, it can be material's property name or shader's parameter name |
| [SetTexture](settexture)(string, TextureBase) | Sets the texture to specified slot |
| override [ToString](tostring)() | Formats object to string |

## Other Members

| Name | Description |
| --- | --- |
| const [MapAmbient](mapambient) | Used in [`SetTexture`](./settexture) to assign a ambient texture mapping. |
| const [MapDiffuse](mapdiffuse) | Used in [`SetTexture`](./settexture) to assign a diffuse texture mapping. |
| const [MapEmissive](mapemissive) | Used in [`SetTexture`](./settexture) to assign a emissive texture mapping. |
| const [MapNormal](mapnormal) | Used in [`SetTexture`](./settexture) to assign a normal texture mapping. |
| const [MapSpecular](mapspecular) | Used in [`SetTexture`](./settexture) to assign a specular texture mapping. |

### See Also

* class [A3DObject](../../aspose.threed/a3dobject)
* class [TextureSlot](../textureslot)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading)
* assembly [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->