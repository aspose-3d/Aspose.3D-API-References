---
title: "PbrMaterial.FromMaterial"
second_title: "Aspose.3D för .NET API‑referens"
description: "PbrMaterial-metod. Tillåter konvertering av annat material till PbrMaterial"
type: docs
weight: 20
url: /sv/net/aspose.threed.shading/pbrmaterial/frommaterial/
---
## PbrMaterial.FromMaterial method

Tillåter konvertering av annat material till PbrMaterial

```csharp
public static PbrMaterial FromMaterial(Material material)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| material | Material |  |

## Exempel

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
mat.DiffuseColor = new Vector3(0.3, 0.9, 0.4);
PbrMaterial pbr = PbrMaterial.FromMaterial(mat);
```

### Se även

* class [Material](../../material/)
* class [PbrMaterial](../)
* namespace [Aspose.ThreeD.Shading](../../pbrmaterial/)
* assembly [Aspose.3D](../../../)


