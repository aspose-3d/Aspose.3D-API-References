---
title: "Material.SetTexture"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Material. Asigna la textura a la ranura especificada"
type: docs
weight: 30
url: /es/net/aspose.threed.shading/material/settexture/
---
## Material.SetTexture method

Establece la textura en la ranura especificada

```csharp
public void SetTexture(string slotName, TextureBase texture)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slotName | String | Nombre del slot. |
| textura | TextureBase | Texture. |

## Ejemplos

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapNormal, tex);
```

### Ver también

* class [TextureBase](../../texturebase/)
* class [Material](../)
* namespace [Aspose.ThreeD.Shading](../../material/)
* assembly [Aspose.3D](../../../)


