---
title: "Classe TransformedCurve"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Entities.TransformedCurve. Un TransformedCurve attribue un placement à une courbe en utilisant une matrice de transformation. Cela permet d’effectuer une transformation à l’intérieur d’une TrimmedCurve ou d’une CompositeCurve."
type: docs
weight: 780
url: /fr/net/aspose.threed.entities/transformedcurve/
---
## TransformedCurve class

Un `TransformedCurve` attribue un placement à une courbe en utilisant une matrice de transformation. Cela permet d’effectuer une transformation à l’intérieur d’un [`TrimmedCurve`](../trimmedcurve/) ou d’un [`CompositeCurve`](../compositecurve/).

```csharp
public class TransformedCurve : Curve
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TransformedCurve](transformedcurve/#constructor)() | Le constructeur de `TransformedCurve` |
| [TransformedCurve](transformedcurve/#constructor_1)(Curve, Matrix4) | Le constructeur de `TransformedCurve` |

## Propriétés

| Nom | Description |
| --- | --- |
| [BasisCurve](../../aspose.threed.entities/transformedcurve/basiscurve/) { get; set; } | La courbe de base. |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | Obtient ou définit la couleur de la ligne, la valeur par défaut est blanc(1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [TransformMatrix](../../aspose.threed.entities/transformedcurve/transformmatrix/) { get; set; } | La matrice de transformation. |

## Méthodes

| Nom | Description |
| --- | --- |
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


