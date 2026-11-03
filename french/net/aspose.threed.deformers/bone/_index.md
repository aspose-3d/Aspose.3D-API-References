---
title: "Classe Bone"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Deformers.Bone. Un os définit le sous‑ensemble du point de contrôle de la géométrie et le poids de mélange défini pour chaque point de contrôle. L’objet Bone ne peut pas être utilisé directement ; une instance de SkinDeformer est utilisée pour déformer la géométrie et SkinDeformer fournit un ensemble d’os, chaque os étant lié à un nœud. NOTE : Un point de contrôle d’une géométrie peut être lié à plusieurs os."
type: docs
weight: 190
url: /fr/net/aspose.threed.deformers/bone/
---
## Bone class

Un os définit le sous‑ensemble du point de contrôle de la géométrie et le poids de mélange défini pour chaque point de contrôle. L’objet `Bone` ne peut pas être utilisé directement, une instance de [`SkinDeformer`](../skindeformer/) est utilisée pour déformer la géométrie, et [`SkinDeformer`](../skindeformer/) fournit un ensemble d’os, chaque os étant lié à un nœud. NOTE : Un point de contrôle d’une géométrie peut être lié à plusieurs os.

```csharp
public class Bone : A3DObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Bone](bone/#constructor)() | Initialise une nouvelle instance de la classe `Bone`. |
| [Bone](bone/#constructor_1)(string) | Initialise une nouvelle instance de la classe `Bone`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BoneTransform](../../aspose.threed.deformers/bone/bonetransform/) { get; set; } | Obtient ou définit la matrice de transformation de l'os. |
| [Item](../../aspose.threed.deformers/bone/item/) { get; set; } |  |
| [LinkMode](../../aspose.threed.deformers/bone/linkmode/) { get; set; } | Le mode de liaison d'un os fait référence à la manière dont un os est connecté ou lié à son os parent au sein d'une structure hiérarchique. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [Node](../../aspose.threed.deformers/bone/node/) { get; set; } | Obtient ou définit le nœud. Le nœud d'os est l'os auquel la peau est attachée, le [`SkinDeformer`](../skindeformer/) utilisera le nœud d'os pour influencer le déplacement des points de contrôle. Le nœud d'os possède généralement un [`Skeleton`](../../aspose.threed.entities/skeleton/) attaché, mais ce n'est pas obligatoire. Le [`Skeleton`](../../aspose.threed.entities/skeleton/) attaché est généralement utilisé par les logiciels DCC pour afficher le squelette à l'utilisateur. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Transform](../../aspose.threed.deformers/bone/transform/) { get; set; } | Obtient ou définit la matrice de transformation du nœud contenant l'os. |
| [WeightCount](../../aspose.threed.deformers/bone/weightcount/) { get; } | Obtient le nombre de poids, celui‑ci est automatiquement étendu par [`SetWeight`](./setweight/) |

## Méthodes

| Nom | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [GetWeight](../../aspose.threed.deformers/bone/getweight/)(int) | Obtient le poids du point de contrôle spécifié par l'index |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |
| [SetWeight](../../aspose.threed.deformers/bone/setweight/)(int, double) | Définit le poids du point de contrôle spécifié par l'index |

### Voir aussi

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


