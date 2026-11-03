---
title: "Classe TransformBuilder"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Utilities.TransformBuilder. Le TransformBuilder est utilisé pour construire une matrice de transformation par une chaîne de transformations"
type: docs
weight: 2860
url: /fr/net/aspose.threed.utilities/transformbuilder/
---
## TransformBuilder class

Le `TransformBuilder` est utilisé pour construire une matrice de transformation par une chaîne de transformations.

```csharp
public class TransformBuilder
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TransformBuilder](transformbuilder/#constructor)(ComposeOrder) | Construisez un `TransformBuilder` avec une matrice de transformation identité initiale et un ordre de composition spécifié |
| [TransformBuilder](transformbuilder/#constructor_1)(Matrix4, ComposeOrder) | Construisez un `TransformBuilder` avec une matrice de transformation initiale et un ordre de composition spécifié |

## Propriétés

| Nom | Description |
| --- | --- |
| [ComposeOrder](../../aspose.threed.utilities/transformbuilder/composeorder/) { get; set; } | Obtient ou définit l'ordre de composition de la chaîne. |
| [Matrix](../../aspose.threed.utilities/transformbuilder/matrix/) { get; set; } | Obtient ou définit la valeur actuelle de la matrice |

## Méthodes

| Nom | Description |
| --- | --- |
| [Append](../../aspose.threed.utilities/transformbuilder/append/)(Matrix4) | Ajoutez la nouvelle matrice de transformation à la chaîne de transformation. |
| [Compose](../../aspose.threed.utilities/transformbuilder/compose/)(Matrix4) | Ajoutez ou préfixez l'argument à la matrice interne. |
| [Prepend](../../aspose.threed.utilities/transformbuilder/prepend/)(Matrix4) | Préfixez la nouvelle matrice de transformation à la chaîne de transformation. |
| [Rearrange](../../aspose.threed.utilities/transformbuilder/rearrange/)(Axis, Axis, Axis) | Réorganisez la disposition des axes. |
| [Reset](../../aspose.threed.utilities/transformbuilder/reset/)() | Réinitialisez la transformation à la matrice identité |
| [Rotate](../../aspose.threed.utilities/transformbuilder/rotate/)(Quaternion) | Chaînez une rotation par un quaternion |
| [RotateDegree](../../aspose.threed.utilities/transformbuilder/rotatedegree/#rotatedegree)(double, Vector3) | Chaînez une transformation de rotation en degrés |
| [RotateDegree](../../aspose.threed.utilities/transformbuilder/rotatedegree/#rotatedegree_1)(Vector3, RotationOrder) | Ajouter une rotation avec l'ordre spécifié |
| [RotateEulerDegree](../../aspose.threed.utilities/transformbuilder/rotateeulerdegree/)(double, double, double) | Enchaîner une rotation par angles d'Euler en degrés |
| [RotateEulerRadian](../../aspose.threed.utilities/transformbuilder/rotateeulerradian/#rotateeulerradian)(Vector3) | Enchaîner une rotation par angles d'Euler en radians |
| [RotateEulerRadian](../../aspose.threed.utilities/transformbuilder/rotateeulerradian/#rotateeulerradian_1)(double, double, double) | Enchaîner une rotation par angles d'Euler en radians |
| [RotateRadian](../../aspose.threed.utilities/transformbuilder/rotateradian/#rotateradian)(double, Vector3) | Enchaîner une transformation de rotation en radians |
| [RotateRadian](../../aspose.threed.utilities/transformbuilder/rotateradian/#rotateradian_1)(Vector3, RotationOrder) | Ajouter une rotation avec l'ordre spécifié |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale_1)(double) | Enchaîner une matrice de transformation d'échelle avec un composant mis à l'échelle par s |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale)(Vector3) | Enchaîner une transformation d'échelle |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale_2)(double, double, double) | Enchaîner une matrice de transformation d'échelle |
| [Translate](../../aspose.threed.utilities/transformbuilder/translate/#translate)(Vector3) | Enchaîner une transformation de translation |
| [Translate](../../aspose.threed.utilities/transformbuilder/translate/#translate_1)(double, double, double) | Enchaîner une transformation de translation |

## Exemples

Le code suivant montre comment créer une matrice à partir d'un ensemble d'opérations

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(10, 20, 0);
tb.Scale(10, 10, 10);
tb.RotateEulerDegree(90, 0, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Voir aussi

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


