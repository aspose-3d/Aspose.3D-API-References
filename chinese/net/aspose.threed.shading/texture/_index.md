---
title: "Texture 类"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Shading.Texture 类。此类定义来自外部文件的纹理"
type: docs
weight: 2600
url: /zh/net/aspose.threed.shading/texture/
---
## Texture class

此类定义了来自外部文件的纹理。

```csharp
public class Texture : TextureBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Texture](texture/#constructor)() | 初始化 `Texture` 类的新实例。 |
| [Texture](texture/#constructor_1)(string) | 初始化 `Texture` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Alpha](../../aspose.threed.shading/texturebase/alpha/) { get; set; } | 获取或设置纹理的默认 alpha 值。当 [`AlphaSource`](../texturebase/alphasource/) 为 PixelAlpha 时有效。默认值为 1.0，有效值范围为 0 到 1 之间 |
| [AlphaSource](../../aspose.threed.shading/texturebase/alphasource/) { get; set; } | 获取或设置纹理是否定义 alpha 通道。默认值为 None |
| [Content](../../aspose.threed.shading/texture/content/) { get; set; } | 获取或设置纹理的二进制内容。嵌入的纹理内容是可选的，如果缺失，用户应从外部文件加载纹理。 |
| [EnableMipMap](../../aspose.threed.shading/texture/enablemipmap/) { get; set; } | 获取或设置此纹理是否启用 mipmap |
| [FileName](../../aspose.threed.shading/texture/filename/) { get; set; } | 获取或设置关联的纹理文件。 |
| [MagFilter](../../aspose.threed.shading/texturebase/magfilter/) { get; set; } | 获取或设置放大过滤器。 |
| [MinFilter](../../aspose.threed.shading/texturebase/minfilter/) { get; set; } | 获取或设置用于缩小的过滤器。 |
| [MipFilter](../../aspose.threed.shading/texturebase/mipfilter/) { get; set; } | 获取或设置用于 mip 级别采样的过滤器。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [UVRotation](../../aspose.threed.shading/texturebase/uvrotation/) { get; set; } | 获取或设置纹理的旋转 |
| [UVScale](../../aspose.threed.shading/texturebase/uvscale/) { get; set; } | 获取或设置 UV 缩放。 |
| [UVTranslation](../../aspose.threed.shading/texturebase/uvtranslation/) { get; set; } | 获取或设置 UV 平移。 |
| [WrapModeU](../../aspose.threed.shading/texturebase/wrapmodeu/) { get; set; } | 获取或设置 U 方向的纹理环绕模式。 |
| [WrapModeV](../../aspose.threed.shading/texturebase/wrapmodev/) { get; set; } | 获取或设置 V 方向的纹理环绕模式。 |
| [WrapModeW](../../aspose.threed.shading/texturebase/wrapmodew/) { get; set; } | 获取或设置 W 方向的纹理环绕模式。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |
| [SetRotation](../../aspose.threed.shading/texturebase/setrotation/)(double, double) | 设置 UV 旋转。 |
| [SetScale](../../aspose.threed.shading/texturebase/setscale/)(double, double) | 设置 UV 缩放。 |
| [SetTranslation](../../aspose.threed.shading/texturebase/settranslation/)(double, double) | 设置 UV 平移。 |

### 另请参见

* class [TextureBase](../texturebase/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


