---
title: "Classe PbrMaterial"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Shading.PbrMaterial class. Matériau pour le rendu physiquement basé sur la couleur d’albédo/métallique/rugosité"
type: docs
weight: 2550
url: /fr/net/aspose.threed.shading/pbrmaterial/
---
## PbrMaterial class

Matériau pour le rendu physiquement basé sur la couleur d’albédo/métallique/rugosité

```csharp
public class PbrMaterial : Material
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PbrMaterial](pbrmaterial/#constructor)() | Construire une instance de matériau PBR par défaut |
| [PbrMaterial](pbrmaterial/#constructor_1)(Vector3) | Construire un matériau PBR par défaut avec la valeur de couleur d’albédo spécifiée. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Albedo](../../aspose.threed.shading/pbrmaterial/albedo/) { get; set; } | Obtient ou définit la couleur de base du matériau |
| [AlbedoTexture](../../aspose.threed.shading/pbrmaterial/albedotexture/) { get; set; } | Obtient ou définit la texture pour l’albédo |
| [EmissiveColor](../../aspose.threed.shading/pbrmaterial/emissivecolor/) { get; set; } | Obtient ou définit la couleur émissive |
| [EmissiveTexture](../../aspose.threed.shading/pbrmaterial/emissivetexture/) { get; set; } | Obtient ou définit la texture émissive |
| [MetallicFactor](../../aspose.threed.shading/pbrmaterial/metallicfactor/) { get; set; } | Obtient ou définit la metallicité du matériau, une valeur de 1 signifie que le matériau est un métal et une valeur de 0 signifie que le matériau est un diélectrique. |
| [MetallicRoughness](../../aspose.threed.shading/pbrmaterial/metallicroughness/) { get; set; } | Obtient ou définit la texture pour le métallique (dans le canal R) et la rugosité (dans le canal G) |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [NormalTexture](../../aspose.threed.shading/pbrmaterial/normaltexture/) { get; set; } | Obtient ou définit la texture de la cartographie des normales |
| [OcclusionFactor](../../aspose.threed.shading/pbrmaterial/occlusionfactor/) { get; set; } | Obtient ou définit le facteur d'occlusion ambiante |
| [OcclusionTexture](../../aspose.threed.shading/pbrmaterial/occlusiontexture/) { get; set; } | Obtient ou définit la texture pour l'occlusion ambiante |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [RoughnessFactor](../../aspose.threed.shading/pbrmaterial/roughnessfactor/) { get; set; } | Obtient ou définit la rugosité du matériau, une valeur de 1 signifie que le matériau est complètement rugueux et une valeur de 0 signifie qu'il est complètement lisse |
| [SpecularTexture](../../aspose.threed.shading/pbrmaterial/speculartexture/) { get; set; } | Obtient ou définit la texture pour la couleur spéculaire |
| [Transparency](../../aspose.threed.shading/pbrmaterial/transparency/) { get; set; } | Obtient ou définit le facteur de transparence. Le facteur doit être compris entre 0 (0 %, totalement opaque) et 1 (100 %, totalement transparent). Toute valeur de facteur invalide sera tronquée. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromMaterial](../../aspose.threed.shading/pbrmaterial/frommaterial/)(Material) | Autoriser la conversion d'un autre matériau en PbrMaterial |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator/)() | Obtient l'énumérateur pour énumérer les slots de texture internes. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [GetTexture](../../aspose.threed.shading/material/gettexture/)(string) | Obtient la texture du slot spécifié, cela peut être le nom de la propriété du matériau ou le nom du paramètre du shader. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |
| [SetTexture](../../aspose.threed.shading/material/settexture/)(string, TextureBase) | Définit la texture au slot spécifié |
| override [ToString](../../aspose.threed.shading/material/tostring/)() | Formate l'objet en chaîne |

### Voir aussi

* class [Material](../material/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


