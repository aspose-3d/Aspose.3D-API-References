---
title: "Structure BoundingBox"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Structure Aspose.ThreeD.Utilities.BoundingBox. La boîte englobante alignée sur les axes"
type: docs
weight: 2670
url: /fr/net/aspose.threed.utilities/boundingbox/
---
## BoundingBox structure

La boîte englobante alignée sur les axes

```csharp
public struct BoundingBox
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [BoundingBox](boundingbox/#constructor)(Vector3, Vector3) | Initialisez une boîte englobante finie avec les coins minimum et maximum donnés |
| [BoundingBox](boundingbox/#constructor_1)(double, double, double, double, double, double) | Initialisez une boîte englobante finie avec les coins minimum et maximum donnés |

## Propriétés

| Nom | Description |
| --- | --- |
| static [Infinite](../../aspose.threed.utilities/boundingbox/infinite/) { get; } | La boîte englobante infinie |
| static [Null](../../aspose.threed.utilities/boundingbox/null/) { get; } | La boîte englobante nulle |
| [Center](../../aspose.threed.utilities/boundingbox/center/) { get; } | Le centre de la boîte englobante. |
| [Extent](../../aspose.threed.utilities/boundingbox/extent/) { get; } | Obtient l'étendue de la boîte englobante. |
| [Maximum](../../aspose.threed.utilities/boundingbox/maximum/) { get; } | Le coin maximum de la boîte englobante |
| [Minimum](../../aspose.threed.utilities/boundingbox/minimum/) { get; } | Le coin minimum de la boîte englobante |
| [Size](../../aspose.threed.utilities/boundingbox/size/) { get; } | La taille de la boîte englobante |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/boundingbox/fromgeometry/)(Geometry) | Construire une boîte englobante à partir de la géométrie donnée |
| [Contains](../../aspose.threed.utilities/boundingbox/contains/#contains)(BoundingBox) | La boîte englobante à vérifier si elle est à l'intérieur de la boîte englobante actuelle. |
| [Contains](../../aspose.threed.utilities/boundingbox/contains/#contains_1)(Vector3) | Vérifier si le point p est à l'intérieur de la boîte englobante |
| override [Equals](../../aspose.threed.utilities/boundingbox/equals/)(object) | Détermine si deux objets sont égaux |
| override [GetHashCode](../../aspose.threed.utilities/boundingbox/gethashcode/)() | Renvoie le code de hachage pour cette instance |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge)(BoundingBox) | Fusionne la nouvelle boîte dans la boîte englobante actuelle. |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_1)(Vector3) | Fusionner la boîte englobante actuelle avec le point donné |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_2)(Vector4) | Fusionner la boîte englobante actuelle avec le point donné |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_3)(double, double, double) | Fusionner la boîte englobante actuelle avec le point donné |
| [OverlapsWith](../../aspose.threed.utilities/boundingbox/overlapswith/)(BoundingBox) | Vérifiez si la boîte englobante actuelle chevauche la boîte englobante spécifiée. |
| [Scale](../../aspose.threed.utilities/boundingbox/scale/)() | Calcule la valeur absolue la plus grande de coordonnées de tout point contenu. |
| override [ToString](../../aspose.threed.utilities/boundingbox/tostring/)() | Obtient la représentation sous forme de chaîne de la boîte englobante. |
| [operator *](../../aspose.threed.utilities/boundingbox/op_multiply/) | Surcharge d'opérateur pour la multiplication, les coins minimum et maximum de la nouvelle boîte englobante seront transformés par la matrice. |

## Exemples

Le code suivant montre comment obtenir une boîte englobante à partir d'une instance d'Entity.

```csharp
var sphere = new Sphere();
var boundingBox = sphere.GetBoundingBox();
Console.WriteLine("Bounding box = " + boundingBox);
```

### Voir aussi

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


