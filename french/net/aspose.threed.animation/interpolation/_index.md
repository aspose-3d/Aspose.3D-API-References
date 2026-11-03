---
title: "Énumération Interpolation"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Animation.Interpolation enum. Le type d'interpolation des images clés"
type: docs
weight: 80
url: /fr/net/aspose.threed.animation/interpolation/
---
## Interpolation enumeration

Le type d'interpolation de l'image clé.

```csharp
public enum Interpolation
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Constant | `0` | La valeur restera constante à la valeur du premier point jusqu'au segment suivant. |
| Linear | `1` | L'interpolation linéaire est une ligne droite entre deux points. |
| Bezier | `2` | Une courbe de type Bézier ou Hermite. |
| BSpline | `3` | Les splines de base sont définies par une série de points de contrôle, pour lesquels la courbe ne passe garantiment que par le premier et le dernier point. |
| CardinalSpline | `4` | Une spline cardinale est une spline cubique Hermite dont les tangentes sont définies par les points d'extrémité et un paramètre de tension. |
| TCBSpline | `5` | Également appelée spline de Kochanek-Bartels, le comportement de la tangente est défini par tension/biais/continuité. |

### Voir aussi

* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


