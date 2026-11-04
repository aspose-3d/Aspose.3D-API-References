---
title: "Material.GetTexture"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Material. Obtiene la textura del slot especificado; puede ser el nombre de una propiedad de materiales o el nombre de un parámetro de shaders"
type: docs
weight: 20
url: /es/net/aspose.threed.shading/material/gettexture/
---
## Material.GetTexture method

Obtiene la textura de la ranura especificada, puede ser el nombre de una propiedad del material o el nombre de un parámetro del shader.

```csharp
public TextureBase GetTexture(string slotName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slotName | String | Nombre del slot. |

### Valor de retorno

La textura.

## Ejemplos

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
tex = (Texture)mat.GetTexture(Material.MapDiffuse);
```

### Ver también

* class [TextureBase](../../texturebase/)
* class [Material](../)
* namespace [Aspose.ThreeD.Shading](../../material/)
* assembly [Aspose.3D](../../../)


