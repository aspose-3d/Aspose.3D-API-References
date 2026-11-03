---
title: "Classe HollowCircleShape"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Profiles.HollowCircleShape. Profil circulaire creux compatible IFC"
type: docs
weight: 1740
url: /fr/net/aspose.threed.profiles/hollowcircleshape/
---
## HollowCircleShape class

Profil de cercle creux compatible IFC.

```csharp
public class HollowCircleShape : CircleShape
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [HollowCircleShape](hollowcircleshape/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Radius](../../aspose.threed.profiles/circleshape/radius/) { get; set; } | Obtient ou définit le rayon du cercle. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [WallThickness](../../aspose.threed.profiles/hollowcircleshape/wallthickness/) { get; set; } | Obtient ou définit la différence entre le rayon extérieur et le rayon intérieur. |

## Méthodes

| Nom | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées en espace objet. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Obtient la clé du rendu d'entité enregistrée dans le moteur de rendu |
| override [GetExtent](../../aspose.threed.profiles/circleshape/getextent/)() | Obtient l'étendue dans les dimensions x et y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |

### Voir aussi

* class [CircleShape](../circleshape/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


