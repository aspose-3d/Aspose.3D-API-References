---
title: PbrMaterial.FromMaterial
second_title: Aspose.3D for .NET API 参考手册
description: PbrMaterial 方法。允许将其他材质转换为 PbrMaterial。
type: docs
weight: 20
url: /zh/net/aspose.threed.shading/pbrmaterial/frommaterial/
---
## PbrMaterial.FromMaterial method

允许将其他材质转换为 PbrMaterial

```csharp
public static PbrMaterial FromMaterial(Material material)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 材质 | Material |  |

## 示例

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
mat.DiffuseColor = new Vector3(0.3, 0.9, 0.4);
PbrMaterial pbr = PbrMaterial.FromMaterial(mat);
```

### 另请参见

* class [Material](../../material/)
* class [PbrMaterial](../)
* namespace [Aspose.ThreeD.Shading](../../pbrmaterial/)
* assembly [Aspose.3D](../../../)


