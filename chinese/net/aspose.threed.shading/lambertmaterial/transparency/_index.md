---
title: "LambertMaterial.Transparency"
second_title: "Aspose.3D for .NET API 参考"
description: "LambertMaterial 属性。获取或设置透明度因子。该因子应在 0.0 完全不透明和 1.0 完全透明之间取值。任何无效的因子值将被限制"
type: docs
weight: 50
url: /zh/net/aspose.threed.shading/lambertmaterial/transparency/
---
## LambertMaterial.Transparency property

获取或设置透明度因子。该因子的取值范围应在 0（0%，完全不透明）到 1（100%，完全透明）之间。任何无效的因子值都将被限制在范围内。

```csharp
public double Transparency { get; set; }
```

### Property Value

该

```csharp
var mat = new LambertMaterial();
mat.Transparency = 0.3;
```

```csharp
var mat = new LambertMaterial();
mat.setTransparency(0.3);
```

透明度因子。

### 另请参见

* class [LambertMaterial](../)
* namespace [Aspose.ThreeD.Shading](../../lambertmaterial/)
* assembly [Aspose.3D](../../../)


