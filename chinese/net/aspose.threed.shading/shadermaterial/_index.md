---
title: "类 ShaderMaterial"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Shading.ShaderMaterial 类。着色器材质允许通过外部渲染引擎或着色语言来描述材质。ShaderMaterial 使用 ShaderTechnique 来描述具体的渲染细节，并根据最终渲染平台选择最合适的。比如你的 ShaderMaterial 实例可以拥有两种技术，一种由 HLSL 定义，另一种由 GLSL 定义。在非 Windows 平台应使用 GLSL 而不是 HLSL。"
type: docs
weight: 2580
url: /zh/net/aspose.threed.shading/shadermaterial/
---
## ShaderMaterial class

着色器材质允许通过外部渲染引擎或着色语言来描述材质。`ShaderMaterial` 使用 [`ShaderTechnique`](../shadertechnique/) 来描述具体的渲染细节，并根据最终渲染平台选择最合适的。例如，你的 `ShaderMaterial` 实例可以拥有两种技术，一种由 HLSL 定义，另一种由 GLSL 定义。在非 Windows 平台应使用 GLSL 而不是 HLSL。

```csharp
public class ShaderMaterial : Material
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ShaderMaterial](shadermaterial/#constructor)() | 初始化 `ShaderMaterial` 类的新实例。 |
| [ShaderMaterial](shadermaterial/#constructor_1)(string) | 初始化 `ShaderMaterial` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Techniques](../../aspose.threed.shading/shadermaterial/techniques/) { get; } | 获取此材质中定义的所有可用技术。 |

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


