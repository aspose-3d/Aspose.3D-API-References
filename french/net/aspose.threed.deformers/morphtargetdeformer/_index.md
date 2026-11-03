---
title: "Classe MorphTargetDeformer"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Deformers.MorphTargetDeformer. MorphTargetDeformer fournit une animation par sommet. MorphTargetDeformer organise toutes les cibles via MorphTargetChannel, chaque canal pouvant organiser plusieurs cibles. Une utilisation courante du déformeur de cible de morphing est d'appliquer une expression faciale à un personnage. Plus de détails sont disponibles sur https//en.wikipedia.org/wiki/Morph_target_animation"
type: docs
weight: 230
url: /fr/net/aspose.threed.deformers/morphtargetdeformer/
---
## MorphTargetDeformer class

MorphTargetDeformer fournit une animation par sommet. MorphTargetDeformer organise toutes les cibles via [`MorphTargetChannel`](../morphtargetchannel/), chaque canal pouvant organiser plusieurs cibles. Une utilisation courante du déformeur de cible de morphing est d'appliquer une expression faciale à un personnage. Plus de détails sont disponibles sur https://en.wikipedia.org/wiki/Morph_target_animation

```csharp
public class MorphTargetDeformer : Deformer
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MorphTargetDeformer](morphtargetdeformer/#constructor)() | Initialise une nouvelle instance de la classe `MorphTargetDeformer`. |
| [MorphTargetDeformer](morphtargetdeformer/#constructor_1)(string) | Initialise une nouvelle instance de la classe `MorphTargetDeformer`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Channels](../../aspose.threed.deformers/morphtargetdeformer/channels/) { get; } | Obtient tous les canaux contenus dans ce déformeur |
| [Item](../../aspose.threed.deformers/morphtargetdeformer/item/) { get; set; } |  |
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


