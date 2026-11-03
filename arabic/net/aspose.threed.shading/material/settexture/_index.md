---
title: "Material.SetTexture"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة Material. يعيّن النسيج إلى الفتحة المحددة"
type: docs
weight: 30
url: /ar/net/aspose.threed.shading/material/settexture/
---
## Material.SetTexture method

يعيّن النسيج إلى الفتحة المحددة

```csharp
public void SetTexture(string slotName, TextureBase texture)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| slotName | String | اسم الفتحة. |
| نسيج | TextureBase | نسيج. |

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


