---
title: "Material.GetTexture"
second_title: "Aspose.3D for .NET API 参考"
description: "Material 方法。从指定的槽获取纹理，它可以是材料属性名称或着色器参数名称"
type: docs
weight: 20
url: /zh/net/aspose.threed.shading/material/gettexture/
---
## Material.GetTexture method

从指定槽获取纹理，它可以是材质的属性名称或着色器的参数名称。

```csharp
public TextureBase GetTexture(string slotName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slotName | 字符串 | 槽名称。 |

### 返回值

纹理。

## 示例

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
tex = (Texture)mat.GetTexture(Material.MapDiffuse);
```

### 另请参见

* class [TextureBase](../../texturebase/)
* class [Material](../)
* namespace [Aspose.ThreeD.Shading](../../material/)
* assembly [Aspose.3D](../../../)


