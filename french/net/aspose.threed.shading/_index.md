---
title: "Aspose.ThreeD.Shading"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Toutes les classes liées à l’ombrage sont définies dans cet espace de noms"
type: docs
weight: 90
url: /fr/net/aspose.threed.shading/
---
Toutes les classes liées à l’ombrage sont définies dans cet espace de noms.

## Classes

| Classe | Description |
| --- | --- |
| [LambertMaterial](./lambertmaterial/) | Matériau pour le modèle d’ombrage Lambert |
| [Material](./material/) | Le matériau définit les paramètres nécessaires à l’apparence visuelle de la géométrie. Aspose.3D fournit le modèle d’ombrage pour [`LambertMaterial`](../aspose.threed.shading/lambertmaterial/), [`PhongMaterial`](../aspose.threed.shading/phongmaterial/) et [`ShaderMaterial`](../aspose.threed.shading/shadermaterial/) |
| [PbrMaterial](./pbrmaterial/) | Matériau pour le rendu physiquement basé sur la couleur d’albédo/métallique/rugosité |
| [PbrSpecularMaterial](./pbrspecularmaterial/) | Matériau pour le rendu physiquement basé sur la couleur diffuse/spéculaire/brillance |
| [PhongMaterial](./phongmaterial/) | Matériau pour le modèle d’ombrage Blinn-Phong. |
| [ShaderMaterial](./shadermaterial/) | Un matériau de shader permet de décrire le matériau par un moteur de rendu externe ou un langage de shader. [`ShaderMaterial`](../aspose.threed.shading/shadermaterial/) utilise [`ShaderTechnique`](../aspose.threed.shading/shadertechnique/) pour décrire les détails concrets du rendu, et le plus approprié sera utilisé selon la plateforme de rendu finale. Par exemple, votre instance de [`ShaderMaterial`](../aspose.threed.shading/shadermaterial/) peut avoir deux techniques, l’une définie par HLSL et l’autre définie par GLSL. Sur les plateformes non Windows, le GLSL doit être utilisé à la place du HLSL |
| [ShaderTechnique](./shadertechnique/) | Une technique de shader représente une implémentation concrète du rendu. |
| [Texture](./texture/) | Cette classe définit la texture à partir d’un fichier externe. |
| [TextureBase](./texturebase/) | Classe de base pour toutes les textures concrètes. La texture définit l’apparence d’une surface géométrique. |
| [TextureSlot](./textureslot/) | Emplacement de texture dans [`Material`](../aspose.threed.shading/material/), peut être énuméré via l’instance du matériau. |
## Énumération

| Énumération | Description |
| --- | --- |
| [AlphaSource](./alphasource/) | Définit si la texture contient le canal alpha. |
| [TextureFilter](./texturefilter/) | Options de filtrage lors de l’échantillonnage de la texture. |
| [WrapMode](./wrapmode/) | Mode d’enroulement de la texture. |


