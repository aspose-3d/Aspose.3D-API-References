---
title: "Classe TextureSlot"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Shading.TextureSlot. Le slot de texture dans Material peut être énuméré via l'instance du matériau"
type: docs
weight: 2630
url: /fr/net/aspose.threed.shading/textureslot/
---
## TextureSlot class

Slot de texture dans [`Material`](../material/), peut être énuméré via l'instance du matériau.

```csharp
public class TextureSlot
```

## Propriétés

| Nom | Description |
| --- | --- |
| [SlotName](../../aspose.threed.shading/textureslot/slotname/) { get; } | Le nom du slot qui indique où cette texture sera liée. |
| [Texture](../../aspose.threed.shading/textureslot/texture/) { get; } | La texture qui sera liée au matériau. |

## Exemples

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
foreach(var slot in mat)
{
    Console.WriteLine($"Texture slot {slot.SlotName} = {slot.Texture}");
}
```

### Voir aussi

* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


