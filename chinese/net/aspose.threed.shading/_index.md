---
title: "Aspose.ThreeD.Shading"
second_title: "Aspose.3D for .NET API 参考"
description: "此命名空间中定义了所有与着色相关的类"
type: docs
weight: 90
url: /zh/net/aspose.threed.shading/
---
所有着色相关的类都定义在此命名空间中。

## 类

| 类 | 描述 |
| --- | --- |
| [LambertMaterial](./lambertmaterial/) | Lambert 着色模型的材质 |
| [Material](./material/) | 材质定义了几何体外观所需的参数。Aspose.3D 为 [`LambertMaterial`](../aspose.threed.shading/lambertmaterial/)、[`PhongMaterial`](../aspose.threed.shading/phongmaterial/) 和 [`ShaderMaterial`](../aspose.threed.shading/shadermaterial/) 提供着色模型。 |
| [PbrMaterial](./pbrmaterial/) | 基于反照率颜色/金属度/粗糙度的物理渲染材质 |
| [PbrSpecularMaterial](./pbrspecularmaterial/) | 基于漫反射颜色/高光/光泽度的物理渲染材质 |
| [PhongMaterial](./phongmaterial/) | Blinn-Phong 着色模型的材质。 |
| [ShaderMaterial](./shadermaterial/) | 着色器材质允许通过外部渲染引擎或着色语言来描述材质。[`ShaderMaterial`](../aspose.threed.shading/shadermaterial/) 使用 [`ShaderTechnique`](../aspose.threed.shading/shadertechnique/) 来描述具体的渲染细节，并根据最终渲染平台选择最合适的实现。例如，您的 [`ShaderMaterial`](../aspose.threed.shading/shadermaterial/) 实例可以拥有两种技术，一种由 HLSL 定义，另一种由 GLSL 定义。在非 Windows 平台下应使用 GLSL 而不是 HLSL。 |
| [ShaderTechnique](./shadertechnique/) | 着色技术代表具体的渲染实现。 |
| [Texture](./texture/) | 此类定义了来自外部文件的纹理。 |
| [TextureBase](./texturebase/) | 所有具体纹理的基类。纹理定义了几何表面的外观和质感。 |
| [TextureSlot](./textureslot/) | 纹理槽在 [`Material`](../aspose.threed.shading/material/) 中，可通过材质实例进行枚举。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [AlphaSource](./alphasource/) | 定义纹理是否包含 alpha 通道。 |
| [TextureFilter](./texturefilter/) | 纹理采样过程中的过滤选项。 |
| [WrapMode](./wrapmode/) | 纹理的环绕模式。 |


