---
title: Aspose.ThreeD.Shading
second_title: Aspose.3D for .NET API 参考
description: 所有与着色相关的类都在这个命名空间中定义
type: docs
weight: 80
url: /zh/net/aspose.threed.shading/
---
所有与着色相关的类都在这个命名空间中定义。

## 课程

| 班级 | 描述 |
| --- | --- |
| [LambertMaterial](./lambertmaterial) | 朗伯着色模型材质 |
| [Material](./material) | 材质定义了几何图形视觉外观所需的参数。 Aspose.3D 为[`LambertMaterial`](../aspose.threed.shading/lambertmaterial),[`PhongMaterial`](../aspose.threed.shading/phongmaterial)和[`ShaderMaterial`](../aspose.threed.shading/shadermaterial) |
| [PbrMaterial](./pbrmaterial) | 基于反照率颜色/金属/粗糙度的物理渲染材质 |
| [PbrSpecularMaterial](./pbrspecularmaterial) | 基于漫反射颜色/镜面反射/光泽度的基于物理的渲染材质 |
| [PhongMaterial](./phongmaterial) | blinn-phong 着色模型的材质。 |
| [ShaderMaterial](./shadermaterial) | 着色器材质允许通过外部渲染引擎或着色器语言来描述材质。 [`ShaderMaterial`](../aspose.threed.shading/shadermaterial)使用[`ShaderTechnique`](../aspose.threed.shading/shadertechnique)来描述具体的渲染细节， 会根据最终的渲染平台使用最合适的一个。 例如，您的[`ShaderMaterial`](../aspose.threed.shading/shadermaterial)实例可以有两种技术，一种由 HLSL 定义，另一种由 GLSL 定义 在非window平台下应该使用GLSL而不是HLSL |
| [ShaderTechnique](./shadertechnique) | 着色器技术代表具体的渲染实现。 |
| [Texture](./texture) | 此类定义来自外部文件的纹理。 |
| [TextureBase](./texturebase) | 所有具体纹理的基类。 纹理定义几何表面的外观。 |
| [TextureSlot](./textureslot) | [`Material`](../aspose.threed.shading/material)中的纹理槽，可以通过材质实例枚举。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [AlphaSource](./alphasource) | 定义纹理是否包含 alpha 通道。 |
| [RenderingAPI](./renderingapi) | 常用渲染API |
| [ShadingLanguage](./shadinglanguage) | 常用着色语言 |
| [TextureFilter](./texturefilter) | 纹理采样期间的过滤器选项。 |
| [WrapMode](./wrapmode) | 纹理的环绕模式。 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
