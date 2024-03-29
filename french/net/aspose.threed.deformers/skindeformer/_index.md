---
title: SkinDeformer
second_title: Référence de l'API Aspose.3D pour .NET
description: Un déformateur de peau contient plusieurs os à travailler chaque os mélange une partie de la géométrie par les poids des points de contrôle.
type: docs
weight: 220
url: /fr/net/aspose.threed.deformers/skindeformer/
---
## SkinDeformer class

Un déformateur de peau contient plusieurs os à travailler, chaque os mélange une partie de la géométrie par les poids des points de contrôle.

```csharp
public class SkinDeformer : Deformer
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [SkinDeformer](skindeformer#constructor)() | Initialise une nouvelle instance du[`SkinDeformer`](../skindeformer) classe. |
| [SkinDeformer](skindeformer#constructor_1)(string) | Initialise une nouvelle instance du[`SkinDeformer`](../skindeformer) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Bones](../../aspose.threed.deformers/skindeformer/bones) { get; } | Obtient tous les os que le déformateur de peau contient |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Obtient ou définit le nom. |
| [Owner](../../aspose.threed.deformers/deformer/owner) { get; } | Obtient la géométrie qui possède ce déformateur |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Obtient la collection de toutes les propriétés. |

## Méthodes

| Nom | La description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Trouve la propriété. Il peut s'agir d'une propriété dynamique (créée par CreateDynamicProperty/SetProperty) ou d'une propriété native (identifiée par son nom) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Supprimer la propriété spécifiée identifiée par name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Définit la valeur de la propriété spécifiée |

### Voir également

* class [Deformer](../deformer)
* espace de noms [Aspose.ThreeD.Deformers](../../aspose.threed.deformers)
* Assemblée [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
