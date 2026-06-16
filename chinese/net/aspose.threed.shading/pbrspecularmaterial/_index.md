---
title: "类 PbrSpecularMaterial"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Shading.PbrSpecularMaterial 类。基于漫反射颜色/高光/光泽的物理渲染材质"
type: docs
weight: 2560
url: /zh/net/aspose.threed.shading/pbrspecularmaterial/
---
## PbrSpecularMaterial class

基于漫反射颜色/高光/光泽度的物理渲染材质

```csharp
public class PbrSpecularMaterial : Material
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PbrSpecularMaterial](pbrspecularmaterial/)() | `PbrSpecularMaterial` 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Diffuse](../../aspose.threed.shading/pbrspecularmaterial/diffuse/) { get; set; } | 获取或设置材质的漫反射颜色，默认值为 (1, 1, 1) |
| [DiffuseTexture](../../aspose.threed.shading/pbrspecularmaterial/diffusetexture/) { get; set; } | 获取或设置漫反射纹理 |
| [EmissiveColor](../../aspose.threed.shading/pbrspecularmaterial/emissivecolor/) { get; set; } | 获取或设置自发光颜色，默认值为 (0, 0, 0) |
| [EmissiveTexture](../../aspose.threed.shading/pbrspecularmaterial/emissivetexture/) { get; set; } | 获取或设置自发光纹理 |
| [GlossinessFactor](../../aspose.threed.shading/pbrspecularmaterial/glossinessfactor/) { get; set; } | 获取或设置材质的光泽度（光滑度），1 表示完全光滑，0 表示完全粗糙，默认值为 1，范围为 [0, 1] |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [NormalTexture](../../aspose.threed.shading/pbrspecularmaterial/normaltexture/) { get; set; } | 获取或设置法线映射纹理 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Specular](../../aspose.threed.shading/pbrspecularmaterial/specular/) { get; set; } | 获取或设置材质的高光颜色，默认值为 (1, 1, 1)。 |
| [SpecularGlossinessTexture](../../aspose.threed.shading/pbrspecularmaterial/specularglossinesstexture/) { get; set; } | 获取或设置高光颜色纹理，RGB 通道存储高光颜色，A 通道存储光泽度。 |
| [Transparency](../../aspose.threed.shading/pbrspecularmaterial/transparency/) { get; set; } | 获取或设置透明度因子。该因子的取值范围应在 0（0%，完全不透明）到 1（100%，完全透明）之间。任何无效的因子值都将被限制在范围内。 |

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

## 字段

| 名称 | 描述 |
| --- | --- |
| const [MapSpecularGlossiness](../../aspose.threed.shading/pbrspecularmaterial/mapspecularglossiness/) | 用于高光光泽度的纹理贴图 |

### 另请参见

* class [Material](../material/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


