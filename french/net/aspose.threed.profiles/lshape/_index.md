---
title: "Classe LShape"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Profiles.LShape. Profil Lshape compatible IFC défini par des paramètres"
type: docs
weight: 1760
url: /fr/net/aspose.threed.profiles/lshape/
---
## LShape class

Profil en forme de L compatible IFC défini par des paramètres.

```csharp
public class LShape : ParameterizedProfile
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [LShape](lshape/)() | Constructeur de `LShape` |

## Propriétés

| Nom | Description |
| --- | --- |
| [Depth](../../aspose.threed.profiles/lshape/depth/) { get; set; } | Obtient ou définit la profondeur du profil. |
| [EdgeRadius](../../aspose.threed.profiles/lshape/edgeradius/) { get; set; } | Obtient ou définit le rayon du bord. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| [FilletRadius](../../aspose.threed.profiles/lshape/filletradius/) { get; set; } | Obtient ou définit le rayon du congé. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [Thickness](../../aspose.threed.profiles/lshape/thickness/) { get; set; } | Obtient ou définit l'épaisseur du mur constant. |
| [Width](../../aspose.threed.profiles/lshape/width/) { get; set; } | Obtient ou définit la largeur du profil. |

## Méthodes

| Nom | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées en espace objet. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Obtient la clé du rendu d'entité enregistrée dans le moteur de rendu |
| override [GetExtent](../../aspose.threed.profiles/lshape/getextent/)() | Obtient l'étendue dans les dimensions x et y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |

### Voir aussi

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


