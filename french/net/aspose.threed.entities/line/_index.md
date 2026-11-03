---
title: "Classe Line"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Entities.Line. Une polyline est un chemin défini par un ensemble de points avec ControlPoints et relié par Segments, ce qui signifie qu'elle peut également être un ensemble de segments de ligne connectés. La ligne est généralement un objet linéaire, ce qui signifie qu'elle ne peut pas être utilisée pour représenter une courbe ; pour représenter une courbe, utilisez NurbsCurve."
type: docs
weight: 480
url: /fr/net/aspose.threed.entities/line/
---
## Line class

Une polyline est un chemin défini par un ensemble de points avec [`ControlPoints`](../geometry/controlpoints/), et relié par [`Segments`](./segments/), ce qui signifie qu'elle peut également être un ensemble de segments de ligne connectés. La ligne est généralement un objet linéaire, ce qui signifie qu'elle ne peut pas être utilisée pour représenter une courbe ; pour représenter une courbe, utilisez [`NurbsCurve`](../nurbscurve/).

```csharp
public class Line : Curve
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Line](line/#constructor)() | Initialise une nouvelle instance de la classe `Line`. |
| [Line](line/#constructor_1)(string) | Initialise une nouvelle instance de la classe `Line`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | Obtient ou définit la couleur de la ligne, la valeur par défaut est blanc(1, 1, 1) |
| [ControlPoints](../../aspose.threed.entities/line/controlpoints/) { get; } | Obtient tous les points de contrôle |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [Segments](../../aspose.threed.entities/line/segments/) { get; } | Obtient les segments de la ligne |
| [Visible](../../aspose.threed.entities/line/visible/) { get; set; } | Obtient ou définit si la géométrie est visible |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromPoints](../../aspose.threed.entities/line/frompoints/)(params Vector3[]) | Construisez une instance de `Line` à partir d'un ensemble de points. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées en espace objet. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | Obtient la clé du rendu d'entité enregistrée dans le moteur de rendu |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [MakeDefaultIndices](../../aspose.threed.entities/line/makedefaultindices/)() | Générez la séquence 0,1,2,3....[`ControlPoints`](../geometry/controlpoints/).Length-1 vers [`Segments`](./segments/) afin que les ControlPoints puissent être utilisés comme une seule ligne |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |

### Voir aussi

* class [Curve](../curve/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


