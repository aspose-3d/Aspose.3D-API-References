---
title: "类 TextureSlot"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Shading.TextureSlot 类。Material 中的纹理槽可以通过材质实例进行枚举。"
type: docs
weight: 2630
url: /zh/net/aspose.threed.shading/textureslot/
---
## TextureSlot class

Material 中的纹理槽（[`Material`](../material/)），可以通过材质实例进行枚举。

```csharp
public class TextureSlot
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [SlotName](../../aspose.threed.shading/textureslot/slotname/) { get; } | 指示此纹理将绑定到的槽名称。 |
| [Texture](../../aspose.threed.shading/textureslot/texture/) { get; } | 将绑定到材质的纹理。 |

## 示例

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
foreach(var slot in mat)
{
    Console.WriteLine($"Texture slot {slot.SlotName} = {slot.Texture}");
}
```

### 另请参见

* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


