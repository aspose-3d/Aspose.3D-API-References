---
title: "Material.SetTexture"
second_title: "Aspose.3D for .NET API 参考"
description: "Material 方法。将纹理设置到指定槽位"
type: docs
weight: 30
url: /zh/net/aspose.threed.shading/material/settexture/
---
## Material.SetTexture method

将纹理设置到指定槽。

```csharp
public void SetTexture(string slotName, TextureBase texture)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slotName | 字符串 | 槽名称。 |
| 纹理 | TextureBase | Texture. |

## 示例

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapNormal, tex);
```

### 另请参见

* class [TextureBase](../../texturebase/)
* class [Material](../)
* namespace [Aspose.ThreeD.Shading](../../material/)
* assembly [Aspose.3D](../../../)


