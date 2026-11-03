---
title: "Classe SkinDeformer"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Deformers.SkinDeformer. Un déformateur de peau contient plusieurs os pour fonctionner, chaque os mélange une partie de la géométrie grâce aux poids des points de contrôle."
type: docs
weight: 240
url: /fr/net/aspose.threed.deformers/skindeformer/
---
## SkinDeformer class

Un déformeur de peau contient plusieurs os pour fonctionner, chaque os mélange une partie de la géométrie selon les poids des points de contrôle.

```csharp
public class SkinDeformer : Deformer
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SkinDeformer](skindeformer/#constructor)() | Initialise une nouvelle instance de la classe `SkinDeformer`. |
| [SkinDeformer](skindeformer/#constructor_1)(string) | Initialise une nouvelle instance de la classe `SkinDeformer`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Bones](../../aspose.threed.deformers/skindeformer/bones/) { get; } | Obtient tous les os que le déformateur de peau contient |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [Owner](../../aspose.threed.deformers/deformer/owner/) { get; } | Obtient la géométrie qui possède ce déformateur |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |

## Méthodes

| Nom | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |

### Voir aussi

* class [Deformer](../deformer/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


