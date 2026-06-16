---
title: "Material.SetTexture"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Material. يضبط النسيج في الفتحة المحددة"
type: docs
weight: 30
url: /ar/net/aspose.threed.shading/material/settexture/
---
## Material.SetTexture method

يعيّن القوام إلى الفتحة المحددة

```csharp
public void SetTexture(string slotName, TextureBase texture)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| slotName | سلسلة | اسم الفتحة. |
| نسيج | TextureBase | Texture. |

## أمثلة

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapNormal, tex);
```

### انظر أيضًا

* class [TextureBase](../../texturebase/)
* class [Material](../)
* namespace [Aspose.ThreeD.Shading](../../material/)
* assembly [Aspose.3D](../../../)


