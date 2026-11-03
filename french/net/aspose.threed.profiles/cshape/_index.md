---
title: "Classe CShape"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Profiles.CShape classe. Profil Cshape compatible IFC défini par des paramètres. La position centrale du profil se trouve au centre de la boîte englobante"
type: docs
weight: 1680
url: /fr/net/aspose.threed.profiles/cshape/
---
## CShape class

Profil en forme de C compatible IFC défini par des paramètres. La position centrale du profil se trouve au centre de la boîte englobante.

```csharp
public class CShape : ParameterizedProfile
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [CShape](cshape/)() | Constructeur de `CShape` |

## Propriétés

| Nom | Description |
| --- | --- |
| [Depth](../../aspose.threed.profiles/cshape/depth/) { get; set; } | Obtient ou définit la profondeur du profil. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| [Girth](../../aspose.threed.profiles/cshape/girth/) { get; set; } | Obtient ou définit la longueur de la circonférence. |
| [InternalFilletRadius](../../aspose.threed.profiles/cshape/internalfilletradius/) { get; set; } | Obtient ou définit le rayon du congé interne. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [WallThickness](../../aspose.threed.profiles/cshape/wallthickness/) { get; set; } | Obtient ou définit l'épaisseur du mur. |
| [Width](../../aspose.threed.profiles/cshape/width/) { get; set; } | Obtient ou définit la largeur du profil. |

## Méthodes

| Nom | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées en espace objet. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Obtient la clé du rendu d'entité enregistrée dans le moteur de rendu |
| override [GetExtent](../../aspose.threed.profiles/cshape/getextent/)() | Obtient l'étendue dans les dimensions x et y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |

### Voir aussi

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


