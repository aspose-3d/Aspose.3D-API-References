---
title: "الفئة TextureSlot"
second_title: "مرجع Aspose.3D for .NET API"
description: "الفئة Aspose.ThreeD.Shading.TextureSlot. يمكن تعداد فتحة القوام في المادة من خلال نسخة المادة"
type: docs
weight: 2630
url: /ar/net/aspose.threed.shading/textureslot/
---
## TextureSlot class

فتحة القوام في [`Material`](../material/)، يمكن تعدادها من خلال نسخة المادة.

```csharp
public class TextureSlot
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [SlotName](../../aspose.threed.shading/textureslot/slotname/) { get; } | اسم الفتحة الذي يحدد إلى أين سيتم ربط هذا القوام. |
| [Texture](../../aspose.threed.shading/textureslot/texture/) { get; } | القوام الذي سيتم ربطه بالمادة. |

## أمثلة

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

### انظر أيضًا

* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


