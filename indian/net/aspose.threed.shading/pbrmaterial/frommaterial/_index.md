---
title: "PbrMaterial.FromMaterial"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "PbrMaterial method. अन्य material को PbrMaterial में परिवर्तित करने की अनुमति देता है"
type: docs
weight: 20
url: /hi/net/aspose.threed.shading/pbrmaterial/frommaterial/
---
## PbrMaterial.FromMaterial method

अन्य सामग्री को PbrMaterial में परिवर्तित करने की अनुमति दें

```csharp
public static PbrMaterial FromMaterial(Material material)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| material | मैटेरियल |  |

## उदाहरण

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
mat.DiffuseColor = new Vector3(0.3, 0.9, 0.4);
PbrMaterial pbr = PbrMaterial.FromMaterial(mat);
```

### देखें भी

* class [Material](../../material/)
* class [PbrMaterial](../)
* namespace [Aspose.ThreeD.Shading](../../pbrmaterial/)
* assembly [Aspose.3D](../../../)


