---
title: "类 TextureData"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Render.TextureData 类。此类包含纹理的原始数据和格式定义。"
type: docs
weight: 2460
url: /zh/net/aspose.threed.render/texturedata/
---
## TextureData class

此类包含纹理的原始数据和格式定义。

```csharp
public class TextureData : A3DObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextureData](texturedata/#constructor)() | `TextureData` 的构造函数 |
| [TextureData](texturedata/#constructor_1)(int, int, PixelFormat) | 构造一个新的 `TextureData` 并分配像素数据。 |
| [TextureData](texturedata/#constructor_2)(int, int, int, int, PixelFormat, byte[]) | `TextureData` 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BytesPerPixel](../../aspose.threed.render/texturedata/bytesperpixel/) { get; } | 每个像素的字节数 |
| [Data](../../aspose.threed.render/texturedata/data/) { get; } | 像素数据的原始字节 |
| [Height](../../aspose.threed.render/texturedata/height/) { get; } | 垂直像素数量 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [PixelFormat](../../aspose.threed.render/texturedata/pixelformat/) { get; } | 像素的格式 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |
| [Stride](../../aspose.threed.render/texturedata/stride/) { get; } | 扫描线的字节数。 |
| [Width](../../aspose.threed.render/texturedata/width/) { get; } | 水平像素数量 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromFile](../../aspose.threed.render/texturedata/fromfile/)(string) | 从文件加载纹理 |
| static [FromStream](../../aspose.threed.render/texturedata/fromstream/)(Stream) | 从流加载纹理 |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels)(PixelMapMode) | 映射所有像素以进行读/写 |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels_1)(PixelMapMode, PixelFormat) | 在给定像素格式下映射所有像素以进行读/写 |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels_2)(Rect, PixelMapMode, PixelFormat) | 在给定像素格式下映射由矩形指定的像素以进行读取/写入 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [Save](../../aspose.threed.render/texturedata/save/#save_1)(string) | 将纹理数据保存为图像文件 |
| [Save](../../aspose.threed.render/texturedata/save/#save)(Stream, string) | 将纹理数据保存为指定的图像格式 |
| [Save](../../aspose.threed.render/texturedata/save/#save_2)(string, string) | 将纹理数据保存为图像文件 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |
| [TransformPixelFormat](../../aspose.threed.render/texturedata/transformpixelformat/)(PixelFormat) | 将像素的布局转换为新的像素格式。 |

### 另请参见

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


