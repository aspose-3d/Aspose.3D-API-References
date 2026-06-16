---
title: "Material.GetTexture"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Material. يحصل على النسيج من الفتحة المحددة؛ يمكن أن يكون اسم خاصية المواد أو اسم معلمة التظليل"
type: docs
weight: 20
url: /ar/net/aspose.threed.shading/material/gettexture/
---
## Material.GetTexture method

يحصل على القوام من الفتحة المحددة، يمكن أن يكون اسم خاصية المادة أو اسم معلمة المظلل

```csharp
public TextureBase GetTexture(string slotName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| slotName | سلسلة | اسم الفتحة. |

### قيمة الإرجاع

النسيج.

## أمثلة

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
tex = (Texture)mat.GetTexture(Material.MapDiffuse);
```

### انظر أيضًا

* class [TextureBase](../../texturebase/)
* class [Material](../)
* namespace [Aspose.ThreeD.Shading](../../material/)
* assembly [Aspose.3D](../../../)


