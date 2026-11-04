---
title: "Material.SetTexture"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Material. Устанавливает текстуру в указанный слот"
type: docs
weight: 30
url: /ru/net/aspose.threed.shading/material/settexture/
---
## Material.SetTexture method

Устанавливает текстуру в указанный слот

```csharp
public void SetTexture(string slotName, TextureBase texture)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| slotName | String | Имя слота. |
| текстура | TextureBase | Texture. |

## Примеры

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapNormal, tex);
```

### См. также

* class [TextureBase](../../texturebase/)
* class [Material](../)
* namespace [Aspose.ThreeD.Shading](../../material/)
* assembly [Aspose.3D](../../../)


