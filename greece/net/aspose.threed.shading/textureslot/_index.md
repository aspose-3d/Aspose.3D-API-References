---
title: "Κλάση TextureSlot"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Shading.TextureSlot κλάση. Η θέση υφής στο Material μπορεί να απαριθμηθεί μέσω του στιγμιότυπου του υλικού."
type: docs
weight: 2630
url: /el/net/aspose.threed.shading/textureslot/
---
## TextureSlot class

Θέση υφής στο [`Material`](../material/), μπορεί να απαριθμηθεί μέσω του στιγμιότυπου του υλικού.

```csharp
public class TextureSlot
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [SlotName](../../aspose.threed.shading/textureslot/slotname/) { get; } | Το όνομα της θέσης που υποδεικνύει πού θα δεσμευτεί αυτή η texture. |
| [Texture](../../aspose.threed.shading/textureslot/texture/) { get; } | Η texture που θα δεσμευτεί στο material. |

## Παραδείγματα

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

### Δείτε επίσης

* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


