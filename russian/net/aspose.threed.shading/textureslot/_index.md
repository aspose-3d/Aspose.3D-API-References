---
title: "Класс TextureSlot"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Shading.TextureSlot. Слот текстуры в Material может быть перечислен через экземпляр материала"
type: docs
weight: 2630
url: /ru/net/aspose.threed.shading/textureslot/
---
## TextureSlot class

Слот текстуры в [`Material`](../material/), может быть перечислен через экземпляр материала.

```csharp
public class TextureSlot
```

## Свойства

| Имя | Описание |
| --- | --- |
| [SlotName](../../aspose.threed.shading/textureslot/slotname/) { get; } | Имя слота, указывающее, к чему будет привязана эта текстура. |
| [Texture](../../aspose.threed.shading/textureslot/texture/) { get; } | Текстура, которая будет привязана к материалу. |

## Примеры

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

### См. также

* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


