---
title: "Material.GetTexture"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Material. Получает текстуру из указанного слота; это может быть имя свойства материала или имя параметра шейдера"
type: docs
weight: 20
url: /ru/net/aspose.threed.shading/material/gettexture/
---
## Material.GetTexture method

Получает текстуру из указанного слота; это может быть имя свойства материала или имя параметра шейдера.

```csharp
public TextureBase GetTexture(string slotName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| slotName | String | Имя слота. |

### Возвращаемое значение

Текстура.

## Примеры

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
tex = (Texture)mat.GetTexture(Material.MapDiffuse);
```

### См. также

* class [TextureBase](../../texturebase/)
* class [Material](../)
* namespace [Aspose.ThreeD.Shading](../../material/)
* assembly [Aspose.3D](../../../)


