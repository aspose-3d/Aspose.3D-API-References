---
title: "Classe Pose"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Pose. La pose est utilisée pour stocker la matrice de transformation lorsque la géométrie est skinée. La pose est un ensemble de BonePose, chaque BonePose enregistre les informations de transformation concrètes du nœud osseux"
type: docs
weight: 1650
url: /fr/net/aspose.threed/pose/
---
## Pose class

La pose est utilisée pour stocker la matrice de transformation lorsque la géométrie est skinée. La pose est un ensemble de [`BonePose`](../bonepose/), chaque [`BonePose`](../bonepose/) enregistre les informations de transformation concrètes du nœud osseux.

```csharp
public class Pose : A3DObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Pose](pose/#constructor)() | Initialise une nouvelle instance de la classe `Pose`. |
| [Pose](pose/#constructor_1)(string) | Initialise une nouvelle instance de la classe `Pose`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BonePoses](../../aspose.threed/pose/boneposes/) { get; } | Obtient tous les [`BonePose`](../bonepose/). |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [PoseType](../../aspose.threed/pose/posetype/) { get; set; } | Obtient ou définit le type de la pose. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddBonePose](../../aspose.threed/pose/addbonepose/#addbonepose)(Node, Matrix4) | Enregistre la matrice de transformation de la pose pour le nœud osseux donné. La matrice de transformation globale est implicite. |
| [AddBonePose](../../aspose.threed/pose/addbonepose/#addbonepose_1)(Node, Matrix4, bool) | Enregistre la matrice de transformation de la pose pour le nœud osseux donné. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |

### Voir aussi

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


