---
title: "PbrMaterial.FromMaterial"
second_title: "Aspose.3D für .NET API-Referenz"
description: "PbrMaterial Methode. Ermöglicht das Konvertieren anderer Materialien zu PbrMaterial"
type: docs
weight: 20
url: /de/net/aspose.threed.shading/pbrmaterial/frommaterial/
---
## PbrMaterial.FromMaterial method

Ermöglicht die Konvertierung anderer Materialien in PbrMaterial

```csharp
public static PbrMaterial FromMaterial(Material material)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Material | Material |  |

## Beispiele

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
mat.DiffuseColor = new Vector3(0.3, 0.9, 0.4);
PbrMaterial pbr = PbrMaterial.FromMaterial(mat);
```

### Siehe auch

* class [Material](../../material/)
* class [PbrMaterial](../)
* namespace [Aspose.ThreeD.Shading](../../pbrmaterial/)
* assembly [Aspose.3D](../../../)


