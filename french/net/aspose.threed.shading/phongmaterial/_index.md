---
title: "Classe PhongMaterial"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Shading.PhongMaterial. Matériau pour le modèle d'éclairage Blinn‑Phong."
type: docs
weight: 2570
url: /fr/net/aspose.threed.shading/phongmaterial/
---
## PhongMaterial class

Matériau pour le modèle d’ombrage Blinn-Phong.

```csharp
public class PhongMaterial : LambertMaterial
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PhongMaterial](phongmaterial/#constructor)() | Initialise une nouvelle instance de la classe `PhongMaterial`. |
| [PhongMaterial](phongmaterial/#constructor_1)(string) | Initialise une nouvelle instance de la classe `PhongMaterial`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AmbientColor](../../aspose.threed.shading/lambertmaterial/ambientcolor/) { get; set; } | Obtient ou définit la couleur ambiante |
| [DiffuseColor](../../aspose.threed.shading/lambertmaterial/diffusecolor/) { get; set; } | Obtient ou définit la couleur diffuse |
| [EmissiveColor](../../aspose.threed.shading/lambertmaterial/emissivecolor/) { get; set; } | Obtient ou définit la couleur émissive |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [ReflectionColor](../../aspose.threed.shading/phongmaterial/reflectioncolor/) { get; set; } | Obtient ou définit la couleur de réflexion. |
| [ReflectionFactor](../../aspose.threed.shading/phongmaterial/reflectionfactor/) { get; set; } | Obtient ou définit l'atténuation de la couleur de réflexion. |
| [Shininess](../../aspose.threed.shading/phongmaterial/shininess/) { get; set; } | Obtient ou définit la brillance, cela contrôle la taille du point lumineux spéculaire. La formule du spéculaire : SpecularColor * SpecularFactor * (N dot H) ^ Shininess |
| [SpecularColor](../../aspose.threed.shading/phongmaterial/specularcolor/) { get; set; } | Obtient ou définit la couleur spéculaire. |
| [SpecularFactor](../../aspose.threed.shading/phongmaterial/specularfactor/) { get; set; } | Obtient ou définit le facteur spéculaire. La formule du spéculaire : SpecularColor * SpecularFactor * (N dot H) ^ Shininess |
| [Transparency](../../aspose.threed.shading/lambertmaterial/transparency/) { get; set; } | Obtient ou définit le facteur de transparence. Le facteur doit être compris entre 0 (0 %, totalement opaque) et 1 (100 %, totalement transparent). Toute valeur de facteur invalide sera tronquée. |
| [TransparentColor](../../aspose.threed.shading/lambertmaterial/transparentcolor/) { get; set; } | Obtient ou définit la couleur transparente. |

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

### Voir aussi

* class [LambertMaterial](../lambertmaterial/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


