---
title: "PbrMaterial.FromMaterial"
second_title: "Riferimento API Aspose.3D per .NET"
description: "Metodo PbrMaterial. Consente di convertire altri materiali in PbrMaterial"
type: docs
weight: 20
url: /it/net/aspose.threed.shading/pbrmaterial/frommaterial/
---
## PbrMaterial.FromMaterial method

Consente di convertire altri materiali in PbrMaterial

```csharp
public static PbrMaterial FromMaterial(Material material)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| materiale | Materiale |  |

## Esempi

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
mat.DiffuseColor = new Vector3(0.3, 0.9, 0.4);
PbrMaterial pbr = PbrMaterial.FromMaterial(mat);
```

### Vedi anche

* class [Material](../../material/)
* class [PbrMaterial](../)
* namespace [Aspose.ThreeD.Shading](../../pbrmaterial/)
* assembly [Aspose.3D](../../../)


