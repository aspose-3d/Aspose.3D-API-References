---
title: "Material.SetTexture"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Material. Définit la texture dans l'emplacement spécifié"
type: docs
weight: 30
url: /fr/net/aspose.threed.shading/material/settexture/
---
## Material.SetTexture method

Définit la texture au slot spécifié

```csharp
public void SetTexture(string slotName, TextureBase texture)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| slotName | String | Nom du slot. |
| texture | TextureBase | Texture. |

## Exemples

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapNormal, tex);
```

### Voir aussi

* class [TextureBase](../../texturebase/)
* class [Material](../)
* namespace [Aspose.ThreeD.Shading](../../material/)
* assembly [Aspose.3D](../../../)


