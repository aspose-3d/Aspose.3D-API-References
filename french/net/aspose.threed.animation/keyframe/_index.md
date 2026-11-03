---
title: "Classe KeyFrame"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Animation.KeyFrame class. Une image clé est principalement définie par un temps et une valeur ; pour certains types d'interpolation, la tangente/la tension/le biais/la continuité sont également utilisés pour calculer la valeur échantillonnée finale. Les valeurs échantillonnées à une position temporelle non-image-clé sont interpolées par les images clés entre les images clés précédentes et suivantes. La valeur avant/après la première/dernière image clé est calculée par la classe Extrapolation."
type: docs
weight: 90
url: /fr/net/aspose.threed.animation/keyframe/
---
## KeyFrame class

Une image clé est principalement définie par un temps et une valeur ; pour certains types d'interpolation, la tangente/la tension/le biais/la continuité sont également utilisés pour calculer la valeur échantillonnée finale. Les valeurs échantillonnées à une position temporelle non-image-clé sont interpolées par les images-clés entre les images-clés précédentes et suivantes. La valeur avant/après la première/dernière image-clé est calculée par la classe [`Extrapolation`](../extrapolation/).

```csharp
public class KeyFrame
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [KeyFrame](keyframe/)(KeyframeSequence, double) | Créer une nouvelle image clé sur la courbe spécifiée |

## Propriétés

| Nom | Description |
| --- | --- |
| [Bias](../../aspose.threed.animation/keyframe/bias/) { get; set; } | Obtient ou définit le biais utilisé dans la spline TCB |
| [Continuity](../../aspose.threed.animation/keyframe/continuity/) { get; set; } | Obtient ou définit la continuité utilisée dans la spline TCB |
| [Flat](../../aspose.threed.animation/keyframe/flat/) { get; set; } | Obtient ou définit si l'image clé est plate. L'image clé doit être plate si l'image clé suivante ou précédente a la même valeur. Une image clé plate possède des tangentes plates et une interpolation fixe. |
| [IndependentTangent](../../aspose.threed.animation/keyframe/independenttangent/) { get; set; } | Obtient ou définit que les tangentes de sortie et d'entrée suivante sont indépendantes. |
| [Interpolation](../../aspose.threed.animation/keyframe/interpolation/) { get; set; } | Obtient ou définit le type d'interpolation de l'image clé, list.data[index] définit l'algorithme de calcul de la valeur échantillonnée. |
| [NextInTangent](../../aspose.threed.animation/keyframe/nextintangent/) { get; set; } | Obtient ou définit la tangente d'entrée suivante (gauche) sur cette image clé. |
| [NextInWeight](../../aspose.threed.animation/keyframe/nextinweight/) { get; set; } | Obtient ou définit le poids d'entrée suivant (gauche) sur cette image clé. |
| [OutTangent](../../aspose.threed.animation/keyframe/outtangent/) { get; set; } | Obtient ou définit la tangente de sortie (droite) sur cette image clé. |
| [OutWeight](../../aspose.threed.animation/keyframe/outweight/) { get; set; } | Obtient ou définit le poids de sortie (droite) sur cette image clé. |
| [StepMode](../../aspose.threed.animation/keyframe/stepmode/) { get; set; } | Obtient ou définit le mode d'étape de l'image clé. Si le type d'interpolation est Constant, list.data[index] détermine quelle valeur d'image clé sera utilisée pendant l'interpolation. Une PreviousValue signifie que la valeur de l'image clé de gauche sera utilisée. Une NextValue signifie que la valeur de l'image clé de droite suivante sera utilisée. |
| [TangentWeightMode](../../aspose.threed.animation/keyframe/tangentweightmode/) { get; set; } | Obtient ou définit le mode de poids de la tangente de l'image clé. La tangente de sortie ou la tangente d'entrée suivante peuvent être personnalisées en sélectionnant le [`WeightedMode`](../weightedmode/) correct. |
| [Tension](../../aspose.threed.animation/keyframe/tension/) { get; set; } | Obtient ou définit la tension utilisée dans la spline TCB |
| [Time](../../aspose.threed.animation/keyframe/time/) { get; set; } | Obtient ou définit la position temporelle de l'image clé list.data[index], mesurée en secondes. |
| [TimeIndependentTangent](../../aspose.threed.animation/keyframe/timeindependenttangent/) { get; set; } | Obtient ou définit que la tangente est indépendante du temps |
| [Value](../../aspose.threed.animation/keyframe/value/) { get; set; } | Obtient ou définit la valeur de l'image clé. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [ToString](../../aspose.threed.animation/keyframe/tostring/)() | Obtient la représentation sous forme de chaîne de l'image clé |

### Voir aussi

* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


