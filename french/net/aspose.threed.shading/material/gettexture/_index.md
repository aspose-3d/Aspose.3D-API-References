---
title: "Material.GetTexture"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Material. Obtient la texture du slot spécifié ; cela peut être le nom d'une propriété de matériau ou le nom d'un paramètre de shader"
type: docs
weight: 20
url: /fr/net/aspose.threed.shading/material/gettexture/
---
## Material.GetTexture method

Obtient la texture du slot spécifié, cela peut être le nom de la propriété du matériau ou le nom du paramètre du shader.

```csharp
public TextureBase GetTexture(string slotName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| slotName | String | Nom du slot. |

### Valeur de retour

La texture.

## Exemples

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
tex = (Texture)mat.GetTexture(Material.MapDiffuse);
```

### Voir aussi

* class [TextureBase](../../texturebase/)
* class [Material](../)
* namespace [Aspose.ThreeD.Shading](../../material/)
* assembly [Aspose.3D](../../../)


