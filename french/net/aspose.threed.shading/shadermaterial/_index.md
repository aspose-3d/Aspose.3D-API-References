---
title: "Classe ShaderMaterial"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Shading.ShaderMaterial. Un matériau shader permet de décrire le matériau via un moteur de rendu externe ou un langage de shader. ShaderMaterial utilise ShaderTechnique pour décrire les détails concrets du rendu et le plus approprié sera utilisé selon la plateforme de rendu finale. Par exemple, votre instance ShaderMaterial peut avoir deux techniques, l'une définie par HLSL et l'autre définie par GLSL. Sur une plateforme non‑window, le GLSL doit être utilisé à la place du HLSL."
type: docs
weight: 2580
url: /fr/net/aspose.threed.shading/shadermaterial/
---
## ShaderMaterial class

Un matériau shader permet de décrire le matériau via un moteur de rendu externe ou un langage de shader. `ShaderMaterial` utilise [`ShaderTechnique`](../shadertechnique/) pour décrire les détails concrets du rendu, et le plus approprié sera utilisé selon la plateforme de rendu finale. Par exemple, votre instance `ShaderMaterial` peut avoir deux techniques, l'une définie par HLSL, et l'autre définie par GLSL. Sur une plateforme non‑window, le GLSL doit être utilisé à la place du HLSL.

```csharp
public class ShaderMaterial : Material
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ShaderMaterial](shadermaterial/#constructor)() | Initialise une nouvelle instance de la classe `ShaderMaterial`. |
| [ShaderMaterial](shadermaterial/#constructor_1)(string) | Initialise une nouvelle instance de la classe `ShaderMaterial`. |

## Propriétés

| Nom | Description |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Techniques](../../aspose.threed.shading/shadermaterial/techniques/) { get; } | Obtient toutes les techniques disponibles définies dans ce matériau. |

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

* class [Material](../material/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


