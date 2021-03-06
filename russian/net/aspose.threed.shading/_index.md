---
title: Aspose.ThreeD.Shading
second_title: Справочник по Aspose.3D для .NET API
description: Все классы связанные с затенением определены в этом пространстве имен.
type: docs
weight: 80
url: /ru/net/aspose.threed.shading/
---
Все классы, связанные с затенением, определены в этом пространстве имен.

## Классы

| Учебный класс | Описание |
| --- | --- |
| [LambertMaterial](./lambertmaterial) | Материал для модели затенения Ламберта |
| [Material](./material) | Материал определяет параметры, необходимые для визуального отображения геометрии. Aspose.3D предоставляет модель затенения для[`LambertMaterial`](../aspose.threed.shading/lambertmaterial),[`PhongMaterial`](../aspose.threed.shading/phongmaterial)и[`ShaderMaterial`](../aspose.threed.shading/shadermaterial) |
| [PbrMaterial](./pbrmaterial) | Материал для физического рендеринга на основе цвета альбедо/металлика/шероховатости |
| [PbrSpecularMaterial](./pbrspecularmaterial) | Материал для физического рендеринга на основе диффузного цвета/зеркальности/глянцевости |
| [PhongMaterial](./phongmaterial) | Материал для модели затенения blinn-phong. |
| [ShaderMaterial](./shadermaterial) | Материал шейдера позволяет описывать материал с помощью внешнего механизма рендеринга или языка шейдера. [`ShaderMaterial`](../aspose.threed.shading/shadermaterial)использует[`ShaderTechnique`](../aspose.threed.shading/shadertechnique)для описания конкретных деталей рендеринга и наиболее подходящий будет использоваться в соответствии с конечной платформой рендеринга. Например, ваш экземпляр[`ShaderMaterial`](../aspose.threed.shading/shadermaterial)может иметь два метода, один определяется HLSL, а другой определяется GLSL Под не-Window платформой следует использовать GLSL вместо HLSL |
| [ShaderTechnique](./shadertechnique) | Техника шейдера представляет конкретную реализацию рендеринга. |
| [Texture](./texture) | Этот класс определяет текстуру из внешнего файла. |
| [TextureBase](./texturebase) | Базовый класс для всех текстур бетона. Текстура определяет внешний вид геометрической поверхности. |
| [TextureSlot](./textureslot) | Слот текстуры в[`Material`](../aspose.threed.shading/material), может быть пронумерован через экземпляр материала. |
## перечисление

| перечисление | Описание |
| --- | --- |
| [AlphaSource](./alphasource) | Определяет, содержит ли текстура альфа-канал. |
| [RenderingAPI](./renderingapi) | Часто используемые API рендеринга |
| [ShadingLanguage](./shadinglanguage) | Часто используемые языки затенения |
| [TextureFilter](./texturefilter) | Параметры фильтра при выборке текстуры. |
| [WrapMode](./wrapmode) | Режим наложения текстуры. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
