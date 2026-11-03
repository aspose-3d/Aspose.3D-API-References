---
title: "Classe Skeleton"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Entities.Skeleton. Le Skeleton est principalement utilisé par les logiciels CAD pour aider le concepteur à manipuler la transformation de la structure squelettique, il est généralement inutile en dehors des logiciels CAD. Pour que la hiérarchie du squelette se comporte comme un seul objet dans le logiciel CAD, il est nécessaire de marquer le nœud Skeleton supérieur comme racine en définissant Type sur Skeleton et tous les enfants sur Bone."
type: docs
weight: 710
url: /fr/net/aspose.threed.entities/skeleton/
---
## Skeleton class

Le `Skeleton` est principalement utilisé par les logiciels CAD pour aider le concepteur à manipuler la transformation de la structure squelettique, il est généralement inutile en dehors des logiciels CAD. Pour que la hiérarchie du squelette se comporte comme un seul objet dans le logiciel CAD, il est nécessaire de marquer le nœud `Skeleton` supérieur comme racine en définissant [`Type`](./type/) sur Skeleton, et tous les enfants sur Bone.

```csharp
public class Skeleton : Entity
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Skeleton](skeleton/#constructor)() | Initialise une nouvelle instance de la classe `Skeleton`. |
| [Skeleton](skeleton/#constructor_1)(string) | Initialise une nouvelle instance de la classe `Skeleton`. |
| [Skeleton](skeleton/#constructor_2)(string, SkeletonType) | Initialise une nouvelle instance de la classe `Skeleton`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [Size](../../aspose.threed.entities/skeleton/size/) { get; set; } | Obtient ou définit la taille du nœud de membre utilisée dans les logiciels CAD pour représenter la taille de l'os. |
| [Type](../../aspose.threed.entities/skeleton/type/) { get; set; } | Obtient ou définit le type du squelette. |

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


