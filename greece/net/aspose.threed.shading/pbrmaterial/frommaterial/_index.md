---
title: "PbrMaterial.FromMaterial"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος PbrMaterial. Επιτρέπει τη μετατροπή άλλου υλικού σε PbrMaterial"
type: docs
weight: 20
url: /el/net/aspose.threed.shading/pbrmaterial/frommaterial/
---
## PbrMaterial.FromMaterial method

Επιτρέπει τη μετατροπή άλλου υλικού σε PbrMaterial

```csharp
public static PbrMaterial FromMaterial(Material material)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| υλικό | Υλικό |  |

## Παραδείγματα

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
mat.DiffuseColor = new Vector3(0.3, 0.9, 0.4);
PbrMaterial pbr = PbrMaterial.FromMaterial(mat);
```

### Δείτε επίσης

* class [Material](../../material/)
* class [PbrMaterial](../)
* namespace [Aspose.ThreeD.Shading](../../pbrmaterial/)
* assembly [Aspose.3D](../../../)


