---
title: "Material.SetTexture"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Material. Ορίζει την υφή στη συγκεκριμένη θέση"
type: docs
weight: 30
url: /el/net/aspose.threed.shading/material/settexture/
---
## Material.SetTexture method

Ορίζει τη texture στην καθορισμένη θέση.

```csharp
public void SetTexture(string slotName, TextureBase texture)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slotName | String | Όνομα slot. |
| υφή | TextureBase | Texture. |

## Παραδείγματα

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapNormal, tex);
```

### Δείτε επίσης

* class [TextureBase](../../texturebase/)
* class [Material](../)
* namespace [Aspose.ThreeD.Shading](../../material/)
* assembly [Aspose.3D](../../../)


