---
title: "Structure RelativeRectangle"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Structure Aspose.ThreeD.Utilities.RelativeRectangle. Rectangle relatif La formule entre le composant relatif et la valeur absolue est Échelle  Référence Largeur  décalage Ainsi, si nous voulons qu'il représente une valeur absolue, laissez tous les champs d'échelle à zéro et utilisez les champs de décalage à la place."
type: docs
weight: 2830
url: /fr/net/aspose.threed.utilities/relativerectangle/
---
## RelativeRectangle structure

Rectangle relatif La formule entre le composant relatif et la valeur absolue est : Échelle * (Largeur de référence) + décalage. Ainsi, si nous voulons qu'il représente une valeur absolue, laissez tous les champs d'échelle à zéro et utilisez les champs de décalage à la place.

```csharp
public struct RelativeRectangle
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [RelativeRectangle](relativerectangle/)(int, int, int, int) | Construire un `RelativeRectangle` |

## Propriétés

| Nom | Description |
| --- | --- |
| [OffsetHeight](../../aspose.threed.utilities/relativerectangle/offsetheight/) { get; set; } | Obtient ou définit le décalage pour la hauteur |
| [OffsetWidth](../../aspose.threed.utilities/relativerectangle/offsetwidth/) { get; set; } | Obtient ou définit le décalage pour la largeur |
| [OffsetX](../../aspose.threed.utilities/relativerectangle/offsetx/) { get; set; } | Obtient ou définit le décalage pour la coordonnée X |
| [OffsetY](../../aspose.threed.utilities/relativerectangle/offsety/) { get; set; } | Obtient ou définit le décalage pour la coordonnée Y |
| [ScaleHeight](../../aspose.threed.utilities/relativerectangle/scaleheight/) { get; set; } | Hauteur relative |
| [ScaleWidth](../../aspose.threed.utilities/relativerectangle/scalewidth/) { get; set; } | Largeur relative |
| [ScaleX](../../aspose.threed.utilities/relativerectangle/scalex/) { get; set; } | Coordonnée relative X |
| [ScaleY](../../aspose.threed.utilities/relativerectangle/scaley/) { get; set; } | Coordonnée relative Y |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromScale](../../aspose.threed.utilities/relativerectangle/fromscale/)(float, float, float, float) | Construire un `RelativeRectangle` avec tous les champs de décalage à zéro et les champs d'échelle à partir des paramètres fournis. |
| [ToAbsolute](../../aspose.threed.utilities/relativerectangle/toabsolute/)(int, int, int, int) | Convertir le rectangle relatif en rectangle absolu |
| override [ToString](../../aspose.threed.utilities/relativerectangle/tostring/)() | Convertit la valeur de cette instance en une chaîne. |

### Voir aussi

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


