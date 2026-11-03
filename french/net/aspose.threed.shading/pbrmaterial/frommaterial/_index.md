---
title: "PbrMaterial.FromMaterial"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode PbrMaterial. Permet de convertir un autre matériau en PbrMaterial"
type: docs
weight: 20
url: /fr/net/aspose.threed.shading/pbrmaterial/frommaterial/
---
## PbrMaterial.FromMaterial method

Autoriser la conversion d'un autre matériau en PbrMaterial

```csharp
public static PbrMaterial FromMaterial(Material material)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| matériau | Matériau |  |

## Exemples

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
mat.DiffuseColor = new Vector3(0.3, 0.9, 0.4);
PbrMaterial pbr = PbrMaterial.FromMaterial(mat);
```

### Voir aussi

* class [Material](../../material/)
* class [PbrMaterial](../)
* namespace [Aspose.ThreeD.Shading](../../pbrmaterial/)
* assembly [Aspose.3D](../../../)


