---
title: PbrMaterial.FromMaterial
second_title: مرجع API Aspose.3D لـ .NET
description: طريقة PbrMaterial. تسمح بتحويل مادة أخرى إلى PbrMaterial
type: docs
weight: 20
url: /ar/net/aspose.threed.shading/pbrmaterial/frommaterial/
---
## PbrMaterial.FromMaterial method

السماح بتحويل مادة أخرى إلى PbrMaterial

```csharp
public static PbrMaterial FromMaterial(Material material)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| مادة | Material |  |

## Examples

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
mat.DiffuseColor = new Vector3(0.3, 0.9, 0.4);
PbrMaterial pbr = PbrMaterial.FromMaterial(mat);
```

### انظر أيضًا

* class [Material](../../material/)
* class [PbrMaterial](../)
* namespace [Aspose.ThreeD.Shading](../../pbrmaterial/)
* assembly [Aspose.3D](../../../)


