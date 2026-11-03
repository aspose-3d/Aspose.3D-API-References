---
title: "Classe HalfSpace"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Entities.HalfSpace. HalfSpace représente un espace infini qui est divisé par un plan ; cela peut être utilisé avec BooleanOperator."
type: docs
weight: 420
url: /fr/net/aspose.threed.entities/halfspace/
---
## HalfSpace class

`HalfSpace` représente un espace infini qui est divisé par un plan, cela peut être utilisé avec [`BooleanOperator`](../booleanoperator/).

```csharp
public class HalfSpace : Entity
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [HalfSpace](halfspace/#constructor)() | Construit une nouvelle instance de `HalfSpace` |
| [HalfSpace](halfspace/#constructor_1)(Vector3, Vector3) | Construit une nouvelle instance de `HalfSpace` avec le vecteur normal fourni et une position sur le plan de coupe ; |

## Propriétés

| Nom | Description |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [Normal](../../aspose.threed.entities/halfspace/normal/) { get; set; } | La normale du plan de coupe, le plan est défini par N * P + D = 0 où N est la normale et P est n'importe quel point du plan. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Position](../../aspose.threed.entities/halfspace/position/) { get; set; } | Le point quelconque sur le plan de coupe, le plan est défini par N * P + D = 0 où N est la normale et P est n'importe quel point du plan. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |

## Méthodes

| Nom | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées en espace objet. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Obtient la clé du rendu d'entité enregistrée dans le moteur de rendu |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |

### Voir aussi

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


