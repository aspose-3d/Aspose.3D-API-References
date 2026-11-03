---
title: "Material.GetTexture"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Material. Λαμβάνει την υφή από το καθορισμένο slot· μπορεί να είναι όνομα ιδιότητας υλικού ή όνομα παραμέτρου shader"
type: docs
weight: 20
url: /el/net/aspose.threed.shading/material/gettexture/
---
## Material.GetTexture method

Λαμβάνει τη texture από την καθορισμένη θέση, μπορεί να είναι το όνομα ιδιότητας του material ή το όνομα παραμέτρου του shader.

```csharp
public TextureBase GetTexture(string slotName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slotName | String | Όνομα slot. |

### Τιμή επιστροφής

Η υφή.

## Παραδείγματα

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
tex = (Texture)mat.GetTexture(Material.MapDiffuse);
```

### Δείτε επίσης

* class [TextureBase](../../texturebase/)
* class [Material](../)
* namespace [Aspose.ThreeD.Shading](../../material/)
* assembly [Aspose.3D](../../../)


