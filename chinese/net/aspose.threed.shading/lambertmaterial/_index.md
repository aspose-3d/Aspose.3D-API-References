---
title: "类 LambertMaterial"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Shading.LambertMaterial 类。用于 Lambert 着色模型的材质。"
type: docs
weight: 2530
url: /zh/net/aspose.threed.shading/lambertmaterial/
---
## LambertMaterial class

Lambert 着色模型的材质

```csharp
public class LambertMaterial : Material
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [LambertMaterial](lambertmaterial/#constructor)() | 初始化 `LambertMaterial` 类的新实例。 |
| [LambertMaterial](lambertmaterial/#constructor_1)(string) | 初始化 `LambertMaterial` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AmbientColor](../../aspose.threed.shading/lambertmaterial/ambientcolor/) { get; set; } | 获取或设置环境光颜色 |
| [DiffuseColor](../../aspose.threed.shading/lambertmaterial/diffusecolor/) { get; set; } | 获取或设置漫反射颜色 |
| [EmissiveColor](../../aspose.threed.shading/lambertmaterial/emissivecolor/) { get; set; } | 获取或设置自发光颜色 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Transparency](../../aspose.threed.shading/lambertmaterial/transparency/) { get; set; } | 获取或设置透明度因子。该因子的取值范围应在 0（0%，完全不透明）到 1（100%，完全透明）之间。任何无效的因子值都将被限制在范围内。 |
| [TransparentColor](../../aspose.threed.shading/lambertmaterial/transparentcolor/) { get; set; } | 获取或设置透明颜色。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator/)() | 获取枚举器以枚举内部纹理槽。 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [GetTexture](../../aspose.threed.shading/material/gettexture/)(string) | 从指定槽获取纹理，它可以是材质的属性名称或着色器的参数名称。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |
| [SetTexture](../../aspose.threed.shading/material/settexture/)(string, TextureBase) | 将纹理设置到指定槽。 |
| override [ToString](../../aspose.threed.shading/material/tostring/)() | 将对象格式化为字符串。 |

### 另请参见

* class [Material](../material/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


