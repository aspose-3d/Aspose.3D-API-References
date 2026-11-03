---
title: "Classe Texture"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Shading.Texture. Cette classe définit la texture à partir d'un fichier externe"
type: docs
weight: 2600
url: /fr/net/aspose.threed.shading/texture/
---
## Texture class

Cette classe définit la texture à partir d’un fichier externe.

```csharp
public class Texture : TextureBase
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Texture](texture/#constructor)() | Initialise une nouvelle instance de la classe `Texture`. |
| [Texture](texture/#constructor_1)(string) | Initialise une nouvelle instance de la classe `Texture`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Alpha](../../aspose.threed.shading/texturebase/alpha/) { get; set; } | Obtient ou définit la valeur alpha par défaut de la texture. Ceci est valide lorsque le [`AlphaSource`](../texturebase/alphasource/) est PixelAlpha. La valeur par défaut est 1.0, la plage de valeurs valides est comprise entre 0 et 1. |
| [AlphaSource](../../aspose.threed.shading/texturebase/alphasource/) { get; set; } | Obtient ou définit si la texture définit le canal alpha. Valeur par défaut : None. |
| [Content](../../aspose.threed.shading/texture/content/) { get; set; } | Obtient ou définit le contenu binaire de la texture. Le contenu de texture intégré est facultatif, l'utilisateur doit charger la texture à partir d'un fichier externe si celui-ci est absent. |
| [EnableMipMap](../../aspose.threed.shading/texture/enablemipmap/) { get; set; } | Obtient ou définit si le mipmap est activé pour cette texture. |
| [FileName](../../aspose.threed.shading/texture/filename/) { get; set; } | Obtient ou définit le fichier de texture associé. |
| [MagFilter](../../aspose.threed.shading/texturebase/magfilter/) { get; set; } | Obtient ou définit le filtre pour le grossissement. |
| [MinFilter](../../aspose.threed.shading/texturebase/minfilter/) { get; set; } | Obtient ou définit le filtre de minification. |
| [MipFilter](../../aspose.threed.shading/texturebase/mipfilter/) { get; set; } | Obtient ou définit le filtre d'échantillonnage des niveaux de mip. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [UVRotation](../../aspose.threed.shading/texturebase/uvrotation/) { get; set; } | Obtient ou définit la rotation de la texture |
| [UVScale](../../aspose.threed.shading/texturebase/uvscale/) { get; set; } | Obtient ou définit l'échelle UV. |
| [UVTranslation](../../aspose.threed.shading/texturebase/uvtranslation/) { get; set; } | Obtient ou définit la translation UV. |
| [WrapModeU](../../aspose.threed.shading/texturebase/wrapmodeu/) { get; set; } | Obtient ou définit les modes d'enroulement de texture en U. |
| [WrapModeV](../../aspose.threed.shading/texturebase/wrapmodev/) { get; set; } | Obtient ou définit les modes d'enroulement de texture en V. |
| [WrapModeW](../../aspose.threed.shading/texturebase/wrapmodew/) { get; set; } | Obtient ou définit les modes d'enroulement de texture en W. |

## Méthodes

| Nom | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |
| [SetRotation](../../aspose.threed.shading/texturebase/setrotation/)(double, double) | Définit la rotation UV. |
| [SetScale](../../aspose.threed.shading/texturebase/setscale/)(double, double) | Définit l'échelle UV. |
| [SetTranslation](../../aspose.threed.shading/texturebase/settranslation/)(double, double) | Définit la translation UV. |

### Voir aussi

* class [TextureBase](../texturebase/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


