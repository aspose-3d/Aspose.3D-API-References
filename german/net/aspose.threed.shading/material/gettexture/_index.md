---
title: "Material.GetTexture"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Material-Methode. Gibt die Textur aus dem angegebenen Slot zurück; es kann der Name einer Materialeigenschaft oder ein Shader-Parametername sein."
type: docs
weight: 20
url: /de/net/aspose.threed.shading/material/gettexture/
---
## Material.GetTexture method

Liefert die Textur aus dem angegebenen Slot, es kann der Name einer Material‑Eigenschaft oder ein Shader‑Parametername sein.

```csharp
public TextureBase GetTexture(string slotName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| slotName | String | Slot-Name. |

### Rückgabewert

Die Textur.

## Beispiele

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
tex = (Texture)mat.GetTexture(Material.MapDiffuse);
```

### Siehe auch

* class [TextureBase](../../texturebase/)
* class [Material](../)
* namespace [Aspose.ThreeD.Shading](../../material/)
* assembly [Aspose.3D](../../../)


