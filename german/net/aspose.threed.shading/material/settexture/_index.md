---
title: "Material.SetTexture"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Material-Methode. Setzt die Textur in den angegebenen Slot."
type: docs
weight: 30
url: /de/net/aspose.threed.shading/material/settexture/
---
## Material.SetTexture method

Setzt die Textur in den angegebenen Slot.

```csharp
public void SetTexture(string slotName, TextureBase texture)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| slotName | String | Slot-Name. |
| texture | TextureBase | Textur. |

## Beispiele

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapNormal, tex);
```

### Siehe auch

* class [TextureBase](../../texturebase/)
* class [Material](../)
* namespace [Aspose.ThreeD.Shading](../../material/)
* assembly [Aspose.3D](../../../)


