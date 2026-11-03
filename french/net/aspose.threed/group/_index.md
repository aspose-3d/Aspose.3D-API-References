---
title: "Classe Group"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Group. Un Group représente les relations logiques du Node."
type: docs
weight: 1570
url: /fr/net/aspose.threed/group/
---
## Group class

Un `Group` représente les relations logiques de [`Node`](../node/).

```csharp
public class Group : A3DObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Group](group/)(string) | Construire une nouvelle instance de `Group` |

## Propriétés

| Nom | Description |
| --- | --- |
| [Groups](../../aspose.threed/group/groups/) { get; } | Sous-groupes |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [Nodes](../../aspose.threed/group/nodes/) { get; } | Les nœuds de ce groupe |
| [Parent](../../aspose.threed/group/parent/) { get; } | Groupe parent du groupe actuel |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |

## Méthodes

| Nom | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |
| override [ToString](../../aspose.threed/group/tostring/)() | Obtient la représentation sous forme de chaîne de `Group` |

### Voir aussi

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


