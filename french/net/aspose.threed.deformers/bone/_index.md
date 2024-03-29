---
title: Bone
second_title: Référence de l'API Aspose.3D pour .NET
description: Un os définit le sousensemble du point de contrôle de la géométrie et définit le poids de fusion pour chaque point de contrôle. LeBone./bone objet ne peut pas être utilisé directement unSkinDeformer./skindeformer instance est utilisée pour déformer la géométrie etSkinDeformer./skindeformerest livré avec un ensemble de bones chaque bone étant lié à un nœud. NOTE  Un point de contrôle dune géométrie peut être lié à plus dun Bones.
type: docs
weight: 180
url: /fr/net/aspose.threed.deformers/bone/
---
## Bone class

Un os définit le sous-ensemble du point de contrôle de la géométrie et définit le poids de fusion pour chaque point de contrôle. Le[`Bone`](../bone) objet ne peut pas être utilisé directement, un[`SkinDeformer`](../skindeformer) instance est utilisée pour déformer la géométrie, et[`SkinDeformer`](../skindeformer)est livré avec un ensemble de bones, chaque bone étant lié à un nœud. NOTE : Un point de contrôle d'une géométrie peut être lié à plus d'un Bones.

```csharp
public class Bone : A3DObject
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Bone](bone#constructor)() | Initialise une nouvelle instance du[`Bone`](../bone) classe. |
| [Bone](bone#constructor_1)(string) | Initialise une nouvelle instance du[`Bone`](../bone) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BoneTransform](../../aspose.threed.deformers/bone/bonetransform) { get; set; } | Obtient ou définit la matrice de transformation de l'os. |
| [Item](../../aspose.threed.deformers/bone/item) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Obtient ou définit le nom. |
| [Node](../../aspose.threed.deformers/bone/node) { get; set; } | Obtient ou définit le nœud. Le nœud osseux est l'os auquel la peau est attachée, le[`SkinDeformer`](../skindeformer) utilisera le nœud osseux pour influencer le déplacement des points de contrôle. Le nœud osseux a généralement un[`Skeleton`](../../aspose.threed.entities/skeleton)attaché, mais ce n'est pas obligatoire. Attaché[`Skeleton`](../../aspose.threed.entities/skeleton) est généralement utilisé par le logiciel DCC pour montrer le squelette à l'utilisateur. |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Obtient la collection de toutes les propriétés. |
| [Transform](../../aspose.threed.deformers/bone/transform) { get; set; } | Obtient ou définit la matrice de transformation du nœud contenant l'os. |
| [WeightCount](../../aspose.threed.deformers/bone/weightcount) { get; } | Obtient le nombre de poids, celui-ci est automatiquement prolongé de[`SetWeight`](./setweight) |

## Méthodes

| Nom | La description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Trouve la propriété. Il peut s'agir d'une propriété dynamique (créée par CreateDynamicProperty/SetProperty) ou d'une propriété native (identifiée par son nom) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Obtenir la valeur de la propriété spécifiée |
| [GetWeight](../../aspose.threed.deformers/bone/getweight)(int) | Obtient le poids du point de contrôle spécifié par index |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Supprimer la propriété spécifiée identifiée par name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Définit la valeur de la propriété spécifiée |
| [SetWeight](../../aspose.threed.deformers/bone/setweight)(int, double) | Définit le poids du point de contrôle spécifié par index |

### Voir également

* class [A3DObject](../../aspose.threed/a3dobject)
* espace de noms [Aspose.ThreeD.Deformers](../../aspose.threed.deformers)
* Assemblée [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
