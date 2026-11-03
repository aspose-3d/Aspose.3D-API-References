---
title: "Classe NurbsCurve"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Entities.NurbsCurve classe. Une courbe NURBS est une courbe représentée par NURBSNonuniform rational basis spline. Une courbe NURBS est définie par son Order, un ensemble de ControlPoints pondérés et des KnotVectors. Le composant w dans le point de contrôle est utilisé comme poids du point de contrôle, qu'il soit TwoDimensional ou ThreeDimensional."
type: docs
weight: 520
url: /fr/net/aspose.threed.entities/nurbscurve/
---
## NurbsCurve class

[NURBS curve](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline) is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [`Order`](./order/), a set of weighted [`ControlPoints`](../geometry/controlpoints/) and a [`KnotVectors`](./knotvectors/) The w component in control point is used as control point's weight, whatever it is a TwoDimensional or ThreeDimensional

```csharp
public class NurbsCurve : Curve
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [NurbsCurve](nurbscurve/#constructor)() | Initialise une nouvelle instance de la classe `NurbsCurve`. |
| [NurbsCurve](nurbscurve/#constructor_1)(string) | Initialise une nouvelle instance de la classe `NurbsCurve`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | Obtient ou définit la couleur de la ligne, la valeur par défaut est blanc(1, 1, 1) |
| [ControlPoints](../../aspose.threed.entities/nurbscurve/controlpoints/) { get; } | Obtient tous les points de contrôle |
| [CurveType](../../aspose.threed.entities/nurbscurve/curvetype/) { get; set; } | Obtient ou définit le type de la courbe. |
| [Degree](../../aspose.threed.entities/nurbscurve/degree/) { get; set; } | Obtient ou définit le degré d'une courbe NURBS, le degré est défini comme Ordre - 1 |
| [Dimension](../../aspose.threed.entities/nurbscurve/dimension/) { get; set; } | Obtient ou définit la dimension de la courbe. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| [KnotVectors](../../aspose.threed.entities/nurbscurve/knotvectors/) { get; } | Obtient le vecteur de nœuds, c'est une séquence de valeurs de paramètres qui détermine où et comment les points de contrôle affectent la courbe NURBS. |
| [Multiplicity](../../aspose.threed.entities/nurbscurve/multiplicity/) { get; } | Obtient la multiplicité. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [Order](../../aspose.threed.entities/nurbscurve/order/) { get; set; } | Obtient ou définit l'ordre d'une courbe NURBS, il définit le nombre de points de contrôle proches qui influencent tout point donné de la courbe. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Rational](../../aspose.threed.entities/nurbscurve/rational/) { get; set; } | Obtient ou définit s'il est rationnel, cette valeur indique si ce `NurbsCurve` est une spline rationnelle ou non rationnelle. La B-spline non rationnelle est un cas particulier des B-splines rationnelles. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |

## Méthodes

| Nom | Description |
| --- | --- |
| [Evaluate](../../aspose.threed.entities/nurbscurve/evaluate/)(int) | Évaluer la courbe NURBS |
| [EvaluateAt](../../aspose.threed.entities/nurbscurve/evaluateat/)(double) | Évaluer le point de la courbe à la position spécifiée |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées en espace objet. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | Obtient la clé du rendu d'entité enregistrée dans le moteur de rendu |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |

### Voir aussi

* class [Curve](../curve/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


