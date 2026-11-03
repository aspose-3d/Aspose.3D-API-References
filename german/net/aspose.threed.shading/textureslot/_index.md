---
title: "Klasse TextureSlot"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Shading.TextureSlot Klasse. Texturslot im Material kann über die Materialinstanz enumeriert werden"
type: docs
weight: 2630
url: /de/net/aspose.threed.shading/textureslot/
---
## TextureSlot class

Texturslot in [`Material`](../material/), kann über die Materialinstanz enumeriert werden.

```csharp
public class TextureSlot
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [SlotName](../../aspose.threed.shading/textureslot/slotname/) { get; } | Der Slot-Name, der angibt, wohin diese Textur gebunden wird. |
| [Texture](../../aspose.threed.shading/textureslot/texture/) { get; } | Die Textur, die an das Material gebunden wird. |

## Beispiele

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

### Siehe auch

* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


