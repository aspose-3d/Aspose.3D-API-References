---
title: "Clase TextureSlot"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Shading.TextureSlot. La ranura de textura en Material puede enumerarse a través de la instancia del material"
type: docs
weight: 2630
url: /es/net/aspose.threed.shading/textureslot/
---
## TextureSlot class

Ranura de textura en [`Material`](../material/), puede enumerarse a través de la instancia del material.

```csharp
public class TextureSlot
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [SlotName](../../aspose.threed.shading/textureslot/slotname/) { get; } | El nombre de la ranura que indica a dónde se vinculará esta textura. |
| [Texture](../../aspose.threed.shading/textureslot/texture/) { get; } | La textura que se vinculará al material. |

## Ejemplos

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

### Ver también

* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


