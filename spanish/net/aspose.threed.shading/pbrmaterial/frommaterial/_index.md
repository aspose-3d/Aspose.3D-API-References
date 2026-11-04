---
title: "PbrMaterial.FromMaterial"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método PbrMaterial. Permite convertir otro material a PbrMaterial"
type: docs
weight: 20
url: /es/net/aspose.threed.shading/pbrmaterial/frommaterial/
---
## PbrMaterial.FromMaterial method

Permite convertir otro material a PbrMaterial.

```csharp
public static PbrMaterial FromMaterial(Material material)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| material | Material |  |

## Ejemplos

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
mat.DiffuseColor = new Vector3(0.3, 0.9, 0.4);
PbrMaterial pbr = PbrMaterial.FromMaterial(mat);
```

### Ver también

* class [Material](../../material/)
* class [PbrMaterial](../)
* namespace [Aspose.ThreeD.Shading](../../pbrmaterial/)
* assembly [Aspose.3D](../../../)


