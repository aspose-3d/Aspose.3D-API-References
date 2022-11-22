---
title: Aspose.ThreeD.Shading
second_title: Riferimento API Aspose.3D per .NET
description: Tutte le classi relative allombreggiatura sono definite in questo spazio dei nomi.
type: docs
weight: 80
url: /it/net/aspose.threed.shading/
---
Tutte le classi relative all'ombreggiatura sono definite in questo spazio dei nomi.

## Classi

| Classe | Descrizione |
| --- | --- |
| [LambertMaterial](./lambertmaterial) | Materiale per ombreggiatura Lambert modello |
| [Material](./material) | Il materiale definisce i parametri necessari per l'aspetto visivo della geometria. Aspose.3D fornisce un modello di ombreggiatura per[`LambertMaterial`](../aspose.threed.shading/lambertmaterial) ,[`PhongMaterial`](../aspose.threed.shading/phongmaterial) e[`ShaderMaterial`](../aspose.threed.shading/shadermaterial) |
| [PbrMaterial](./pbrmaterial) | Materiale per rendering a base fisica basato su albedo color/metallic/roughness |
| [PbrSpecularMaterial](./pbrspecularmaterial) | Materiale per rendering a base fisica basato su colore diffuso/speculare/lucentezza |
| [PhongMaterial](./phongmaterial) | Materiale per il modello di ombreggiatura blinn-phong. |
| [ShaderMaterial](./shadermaterial) | Un materiale shader consente di descrivere il materiale tramite un motore di rendering esterno o un linguaggio shader. [`ShaderMaterial`](../aspose.threed.shading/shadermaterial) usi[`ShaderTechnique`](../aspose.threed.shading/shadertechnique)per descrivere i dettagli concreti del rendering, e quello più adatto verranno utilizzati in base alla piattaforma di rendering finale. Ad esempio, il tuo[`ShaderMaterial`](../aspose.threed.shading/shadermaterial) l'istanza può avere due tecniche, una è definita da HLSL e un'altra è definita da GLSL In una piattaforma non finestra, è necessario utilizzare GLSL invece di HLSL |
| [ShaderTechnique](./shadertechnique) | Una tecnica shader rappresenta un'implementazione concreta del rendering. |
| [Texture](./texture) | Questa classe definisce la trama da un file esterno. |
| [TextureBase](./texturebase) | Classe base per tutte le strutture in calcestruzzo. Texture definisce l'aspetto grafico di una superficie geometrica. |
| [TextureSlot](./textureslot) | Slot per texture[`Material`](../aspose.threed.shading/material) , può essere enumerato tramite material instance. |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [AlphaSource](./alphasource) | Definisce se la texture contiene il canale alfa. |
| [TextureFilter](./texturefilter) | Opzioni di filtro durante il campionamento delle texture. |
| [WrapMode](./wrapmode) | Modalità di avvolgimento della trama. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->