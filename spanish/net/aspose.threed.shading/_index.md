---
title: "Aspose.ThreeD.Shading"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Todas las clases relacionadas con sombreado están definidas en este espacio de nombres."
type: docs
weight: 90
url: /es/net/aspose.threed.shading/
---
Todas las clases relacionadas con el sombreado se definen en este espacio de nombres.

## Clases

| Clase | Descripción |
| --- | --- |
| [LambertMaterial](./lambertmaterial/) | Material para el modelo de sombreado Lambert. |
| [Material](./material/) | El material define los parámetros necesarios para la apariencia visual de la geometría. Aspose.3D proporciona modelos de sombreado para [`LambertMaterial`](../aspose.threed.shading/lambertmaterial/), [`PhongMaterial`](../aspose.threed.shading/phongmaterial/) y [`ShaderMaterial`](../aspose.threed.shading/shadermaterial/). |
| [PbrMaterial](./pbrmaterial/) | Material para renderizado basado en física basado en color albedo/metallic/roughness. |
| [PbrSpecularMaterial](./pbrspecularmaterial/) | Material para renderizado basado en física basado en color difuso/especular/brillo. |
| [PhongMaterial](./phongmaterial/) | Material para el modelo de sombreado Blinn-Phong. |
| [ShaderMaterial](./shadermaterial/) | Un material shader permite describir el material mediante un motor de renderizado externo o un lenguaje de shader. [`ShaderMaterial`](../aspose.threed.shading/shadermaterial/) usa [`ShaderTechnique`](../aspose.threed.shading/shadertechnique/) para describir los detalles concretos de renderizado, y el más adecuado se utilizará según la plataforma de renderizado final. Por ejemplo, su instancia de [`ShaderMaterial`](../aspose.threed.shading/shadermaterial/) puede tener dos técnicas, una definida por HLSL y otra definida por GLSL. En plataformas que no son Windows, se debe usar GLSL en lugar de HLSL. |
| [ShaderTechnique](./shadertechnique/) | Una técnica de shader representa una implementación concreta de renderizado. |
| [Texture](./texture/) | Esta clase define la textura a partir de un archivo externo. |
| [TextureBase](./texturebase/) | Clase base para todas las texturas concretas. La textura define el aspecto y la sensación de la superficie de una geometría. |
| [TextureSlot](./textureslot/) | Ranura de textura en [`Material`](../aspose.threed.shading/material/), puede enumerarse a través de la instancia del material. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [AlphaSource](./alphasource/) | Define si la textura contiene el canal alfa. |
| [TextureFilter](./texturefilter/) | Opciones de filtrado durante el muestreo de la textura. |
| [WrapMode](./wrapmode/) | Modo de envoltura de la textura. |


