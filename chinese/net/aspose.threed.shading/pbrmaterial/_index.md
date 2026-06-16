---
title: "类 PbrMaterial"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Shading.PbrMaterial 类。基于反照率颜色/金属度/粗糙度的物理渲染材质"
type: docs
weight: 2550
url: /zh/net/aspose.threed.shading/pbrmaterial/
---
## PbrMaterial class

基于反照率颜色/金属度/粗糙度的物理渲染材质

```csharp
public class PbrMaterial : Material
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PbrMaterial](pbrmaterial/#constructor)() | 构造默认的 PBR 材质实例 |
| [PbrMaterial](pbrmaterial/#constructor_1)(Vector3) | 使用指定的反照率颜色值构造默认的 PBR 材质。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Albedo](../../aspose.threed.shading/pbrmaterial/albedo/) { get; set; } | 获取或设置材质的基础颜色 |
| [AlbedoTexture](../../aspose.threed.shading/pbrmaterial/albedotexture/) { get; set; } | 获取或设置反照率纹理 |
| [EmissiveColor](../../aspose.threed.shading/pbrmaterial/emissivecolor/) { get; set; } | 获取或设置自发光颜色 |
| [EmissiveTexture](../../aspose.threed.shading/pbrmaterial/emissivetexture/) { get; set; } | 获取或设置自发光纹理 |
| [MetallicFactor](../../aspose.threed.shading/pbrmaterial/metallicfactor/) { get; set; } | 获取或设置材质的金属度，值为 1 表示材质为金属，值为 0 表示材质为介电体。 |
| [MetallicRoughness](../../aspose.threed.shading/pbrmaterial/metallicroughness/) { get; set; } | 获取或设置金属度（R 通道）和粗糙度（G 通道）的纹理 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [NormalTexture](../../aspose.threed.shading/pbrmaterial/normaltexture/) { get; set; } | 获取或设置法线映射纹理 |
| [OcclusionFactor](../../aspose.threed.shading/pbrmaterial/occlusionfactor/) { get; set; } | 获取或设置环境遮蔽因子 |
| [OcclusionTexture](../../aspose.threed.shading/pbrmaterial/occlusiontexture/) { get; set; } | 获取或设置环境遮蔽纹理 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [RoughnessFactor](../../aspose.threed.shading/pbrmaterial/roughnessfactor/) { get; set; } | 获取或设置材质的粗糙度，值为 1 表示材质完全粗糙，值为 0 表示材质完全光滑 |
| [SpecularTexture](../../aspose.threed.shading/pbrmaterial/speculartexture/) { get; set; } | 获取或设置高光颜色纹理 |
| [Transparency](../../aspose.threed.shading/pbrmaterial/transparency/) { get; set; } | 获取或设置透明度因子。该因子的取值范围应在 0（0%，完全不透明）到 1（100%，完全透明）之间。任何无效的因子值都将被限制在范围内。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromMaterial](../../aspose.threed.shading/pbrmaterial/frommaterial/)(Material) | 允许将其他材质转换为 PbrMaterial |
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


