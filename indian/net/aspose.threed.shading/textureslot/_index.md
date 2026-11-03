---
title: "क्लास TextureSlot"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Shading.TextureSlot क्लास। मैटेरियल में टेक्सचर स्लॉट को मैटेरियल इंस्टेंस के माध्यम से सूचीबद्ध किया जा सकता है"
type: docs
weight: 2630
url: /hi/net/aspose.threed.shading/textureslot/
---
## TextureSlot class

टेक्सचर स्लॉट [`Material`](../material/) में, मैटेरियल इंस्टेंस के माध्यम से सूचीबद्ध किया जा सकता है।

```csharp
public class TextureSlot
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [SlotName](../../aspose.threed.shading/textureslot/slotname/) { get; } | स्लॉट का नाम जो दर्शाता है कि यह टेक्सचर कहाँ बंधेगा। |
| [Texture](../../aspose.threed.shading/textureslot/texture/) { get; } | टेक्सचर जो मैटेरियल से बंधेगा। |

## उदाहरण

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

### देखें भी

* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


