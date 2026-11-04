---
title: "PbrMaterial.FromMaterial"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод PbrMaterial. Позволяет преобразовать другой материал в PbrMaterial"
type: docs
weight: 20
url: /ru/net/aspose.threed.shading/pbrmaterial/frommaterial/
---
## PbrMaterial.FromMaterial method

Разрешить преобразование другого материала в PbrMaterial

```csharp
public static PbrMaterial FromMaterial(Material material)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| материал | Материал |  |

## Примеры

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
mat.DiffuseColor = new Vector3(0.3, 0.9, 0.4);
PbrMaterial pbr = PbrMaterial.FromMaterial(mat);
```

### См. также

* class [Material](../../material/)
* class [PbrMaterial](../)
* namespace [Aspose.ThreeD.Shading](../../pbrmaterial/)
* assembly [Aspose.3D](../../../)


