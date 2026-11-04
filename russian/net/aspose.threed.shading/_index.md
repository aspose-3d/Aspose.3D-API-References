---
title: "Aspose.ThreeD.Shading"
second_title: "Справочник API Aspose.3D для .NET"
description: "Все классы, связанные с затенением, определены в этом пространстве имён."
type: docs
weight: 90
url: /ru/net/aspose.threed.shading/
---
Все классы, связанные с затенением, определены в этом пространстве имён.

## Классы

| Класс | Описание |
| --- | --- |
| [LambertMaterial](./lambertmaterial/) | Материал для модели затенения Ламберта |
| [Material](./material/) | Материал определяет параметры, необходимые для визуального отображения геометрии. Aspose.3D предоставляет модели затенения для [`LambertMaterial`](../aspose.threed.shading/lambertmaterial/), [`PhongMaterial`](../aspose.threed.shading/phongmaterial/) и [`ShaderMaterial`](../aspose.threed.shading/shadermaterial/) |
| [PbrMaterial](./pbrmaterial/) | Материал для физически основанного рендеринга, основанный на альбедо‑цвете/металличности/шероховатости |
| [PbrSpecularMaterial](./pbrspecularmaterial/) | Материал для физически основанного рендеринга, основанный на диффузном цвете/спекулярности/блеске |
| [PhongMaterial](./phongmaterial/) | Материал для модели затенения Блинна-Фонга. |
| [ShaderMaterial](./shadermaterial/) | Shader-материал позволяет описать материал внешним движком рендеринга или языком шейдеров. [`ShaderMaterial`](../aspose.threed.shading/shadermaterial/) использует [`ShaderTechnique`](../aspose.threed.shading/shadertechnique/) для описания конкретных деталей рендеринга, и наиболее подходящий будет выбран в зависимости от конечной платформы рендеринга. Например, ваш экземпляр [`ShaderMaterial`](../aspose.threed.shading/shadermaterial/) может иметь две техники: одна определена с помощью HLSL, другая — с помощью GLSL. На платформе без окна следует использовать GLSL вместо HLSL |
| [ShaderTechnique](./shadertechnique/) | Техника шейдера представляет конкретную реализацию рендеринга. |
| [Texture](./texture/) | Этот класс определяет текстуру из внешнего файла. |
| [TextureBase](./texturebase/) | Базовый класс для всех конкретных текстур. Текстура определяет внешний вид поверхности геометрии. |
| [TextureSlot](./textureslot/) | Слот текстуры в [`Material`](../aspose.threed.shading/material/), может быть перечислен через экземпляр материала. |
## Перечисление

| Перечисление | Описание |
| --- | --- |
| [AlphaSource](./alphasource/) | Определяет, содержит ли текстура альфа‑канал. |
| [TextureFilter](./texturefilter/) | Параметры фильтрации при выборке текстуры. |
| [WrapMode](./wrapmode/) | Режим обёртки текстуры. |


