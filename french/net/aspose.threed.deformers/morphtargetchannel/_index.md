---
title: "Classe MorphTargetChannel"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Deformers.MorphTargetChannel. Un MorphTargetChannel est utilisé par MorphTargetDeformer pour organiser les géométries cibles. Certains formats de fichier comme FBX prennent en charge plusieurs canaux en parallèle."
type: docs
weight: 220
url: /fr/net/aspose.threed.deformers/morphtargetchannel/
---
## MorphTargetChannel class

Un MorphTargetChannel est utilisé par [`MorphTargetDeformer`](../morphtargetdeformer/) pour organiser les géométries cibles. Certains formats de fichier comme FBX prennent en charge plusieurs canaux en parallèle.

```csharp
public class MorphTargetChannel : A3DObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MorphTargetChannel](morphtargetchannel/#constructor)() | Initialise une nouvelle instance de la classe `MorphTargetChannel`. |
| [MorphTargetChannel](morphtargetchannel/#constructor_1)(string) | Initialise une nouvelle instance de la classe `MorphTargetChannel`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ChannelWeight](../../aspose.threed.deformers/morphtargetchannel/channelweight/) { get; set; } | Obtient ou définit le poids du déformeur de ce canal. Le poids est compris entre 0.0 et 1.0 |
| [Item](../../aspose.threed.deformers/morphtargetchannel/item/) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Targets](../../aspose.threed.deformers/morphtargetchannel/targets/) { get; } | Obtient toutes les cibles associées au canal. |
| [Weights](../../aspose.threed.deformers/morphtargetchannel/weights/) { get; } | Obtient les valeurs complètes de poids des géométries cibles. |

## Méthodes

| Nom | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [GetWeight](../../aspose.threed.deformers/morphtargetchannel/getweight/)(Shape) | Obtient le poids de la cible spécifiée ; si la cible n’appartient pas à ce canal, la valeur par défaut 0 est renvoyée. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |
| [SetWeight](../../aspose.threed.deformers/morphtargetchannel/setweight/)(Shape, double) | Définit le poids de la cible spécifiée, la valeur par défaut est 1, la plage doit être comprise entre 0 et 1. |

## Champs

| Nom | Description |
| --- | --- |
| const [DefaultWeight](../../aspose.threed.deformers/morphtargetchannel/defaultweight/) | Poids par défaut pour la cible de morphing. |

## Remarques

Le poids est compris entre 0 et 1,0, et le poids par défaut pour la cible est 0,0 ;

### Voir aussi

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


