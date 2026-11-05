---
title: "PbrMaterial.FromMaterial"
second_title: "Aspose.3D for .NET API Referansı"
description: "PbrMaterial yöntemi. Diğer materyali PbrMaterial'e dönüştürmeye izin verir"
type: docs
weight: 20
url: /tr/net/aspose.threed.shading/pbrmaterial/frommaterial/
---
## PbrMaterial.FromMaterial method

Diğer materyali PbrMaterial'e dönüştürmeye izin verir

```csharp
public static PbrMaterial FromMaterial(Material material)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| materyal | Materyal |  |

## Örnekler

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
mat.DiffuseColor = new Vector3(0.3, 0.9, 0.4);
PbrMaterial pbr = PbrMaterial.FromMaterial(mat);
```

### Ayrıca Bakınız

* class [Material](../../material/)
* class [PbrMaterial](../)
* namespace [Aspose.ThreeD.Shading](../../pbrmaterial/)
* assembly [Aspose.3D](../../../)


