---
title: "Classe PbrSpecularMaterial"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Shading.PbrSpecularMaterial classe. Matériau pour le rendu physiquement basé sur la couleur diffuse/spéculaire/brillance"
type: docs
weight: 2560
url: /fr/net/aspose.threed.shading/pbrspecularmaterial/
---
## PbrSpecularMaterial class

Matériau pour le rendu physiquement basé sur la couleur diffuse/spéculaire/brillance

```csharp
public class PbrSpecularMaterial : Material
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PbrSpecularMaterial](pbrspecularmaterial/)() | Constructeur de `PbrSpecularMaterial` |

## Propriétés

| Nom | Description |
| --- | --- |
| [Diffuse](../../aspose.threed.shading/pbrspecularmaterial/diffuse/) { get; set; } | Obtient ou définit la couleur diffuse du matériau, la valeur par défaut est (1, 1, 1) |
| [DiffuseTexture](../../aspose.threed.shading/pbrspecularmaterial/diffusetexture/) { get; set; } | Obtient ou définit la texture diffuse |
| [EmissiveColor](../../aspose.threed.shading/pbrspecularmaterial/emissivecolor/) { get; set; } | Obtient ou définit la couleur émissive, la valeur par défaut est (0, 0, 0) |
| [EmissiveTexture](../../aspose.threed.shading/pbrspecularmaterial/emissivetexture/) { get; set; } | Obtient ou définit la texture émissive |
| [GlossinessFactor](../../aspose.threed.shading/pbrspecularmaterial/glossinessfactor/) { get; set; } | Obtient ou définit la brillance (lissage) du matériau, 1 signifie parfaitement lisse et 0 signifie parfaitement rugueux, la valeur par défaut est 1, la plage est [0, 1] |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [NormalTexture](../../aspose.threed.shading/pbrspecularmaterial/normaltexture/) { get; set; } | Obtient ou définit la texture de la cartographie des normales |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Specular](../../aspose.threed.shading/pbrspecularmaterial/specular/) { get; set; } | Obtient ou définit la couleur spéculaire du matériau, la valeur par défaut est (1, 1, 1). |
| [SpecularGlossinessTexture](../../aspose.threed.shading/pbrspecularmaterial/specularglossinesstexture/) { get; set; } | Obtient ou définit la texture pour la couleur spéculaire, le canal RGB stocke la couleur spéculaire et le canal A stocke la brillance. |
| [Transparency](../../aspose.threed.shading/pbrspecularmaterial/transparency/) { get; set; } | Obtient ou définit le facteur de transparence. Le facteur doit être compris entre 0 (0 %, totalement opaque) et 1 (100 %, totalement transparent). Toute valeur de facteur invalide sera tronquée. |

## Méthodes

| Nom | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator/)() | Obtient l'énumérateur pour énumérer les slots de texture internes. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [GetTexture](../../aspose.threed.shading/material/gettexture/)(string) | Obtient la texture du slot spécifié, cela peut être le nom de la propriété du matériau ou le nom du paramètre du shader. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |
| [SetTexture](../../aspose.threed.shading/material/settexture/)(string, TextureBase) | Définit la texture au slot spécifié |
| override [ToString](../../aspose.threed.shading/material/tostring/)() | Formate l'objet en chaîne |

## Champs

| Nom | Description |
| --- | --- |
| const [MapSpecularGlossiness](../../aspose.threed.shading/pbrspecularmaterial/mapspecularglossiness/) | La carte de texture pour la brillance spéculaire |

### Voir aussi

* class [Material](../material/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


