---
title: "Aspose.ThreeD.Shading"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Alle schattierungsbezogenen Klassen sind in diesem Namespace definiert."
type: docs
weight: 90
url: /de/net/aspose.threed.shading/
---
Alle Schattierungs‑Klassen sind in diesem Namensraum definiert.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [LambertMaterial](./lambertmaterial/) | Material für das Lambert-Schattierungsmodell. |
| [Material](./material/) | Material definiert die für das visuelle Erscheinungsbild der Geometrie notwendigen Parameter. Aspose.3D stellt Schattierungsmodelle für [`LambertMaterial`](../aspose.threed.shading/lambertmaterial/), [`PhongMaterial`](../aspose.threed.shading/phongmaterial/) und [`ShaderMaterial`](../aspose.threed.shading/shadermaterial/) bereit. |
| [PbrMaterial](./pbrmaterial/) | Material für physikalisch basiertes Rendering basierend auf Albedo-Farbe/Metallisch/Rauheit. |
| [PbrSpecularMaterial](./pbrspecularmaterial/) | Material für physikalisch basiertes Rendering basierend auf Diffusfarbe/Specular/Glanz. |
| [PhongMaterial](./phongmaterial/) | Material für das Blinn-Phong-Schattierungsmodell. |
| [ShaderMaterial](./shadermaterial/) | Ein Shader-Material ermöglicht es, das Material durch eine externe Rendering-Engine oder Shadersprache zu beschreiben. [`ShaderMaterial`](../aspose.threed.shading/shadermaterial/) verwendet [`ShaderTechnique`](../aspose.threed.shading/shadertechnique/), um die konkreten Rendering-Details zu beschreiben, und die am besten geeignete wird je nach Ziel-Rendering-Plattform verwendet. Zum Beispiel kann Ihre [`ShaderMaterial`](../aspose.threed.shading/shadermaterial/) Instanz zwei Techniken besitzen, eine definiert durch HLSL und eine andere durch GLSL. Auf nicht‑Windows‑Plattformen sollte stattdessen GLSL verwendet werden. |
| [ShaderTechnique](./shadertechnique/) | Eine Shader-Technik stellt eine konkrete Rendering-Implementierung dar. |
| [Texture](./texture/) | Diese Klasse definiert die Textur aus einer externen Datei. |
| [TextureBase](./texturebase/) | Basisklasse für alle konkreten Texturen. Eine Textur definiert das Aussehen und das Gefühl einer geometrischen Oberfläche. |
| [TextureSlot](./textureslot/) | Textur-Slot in [`Material`](../aspose.threed.shading/material/), kann über die Materialinstanz enumeriert werden. |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [AlphaSource](./alphasource/) | Definiert, ob die Textur den Alphakanal enthält. |
| [TextureFilter](./texturefilter/) | Filteroptionen beim Textur-Sampling. |
| [WrapMode](./wrapmode/) | Wrap-Modus der Textur. |


