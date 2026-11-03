---
title: "Classe ZShape"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Profiles.ZShape classe. Profil Zshape compatible IFC défini par des paramètres"
type: docs
weight: 1850
url: /fr/net/aspose.threed.profiles/zshape/
---
## ZShape class

Profil en forme de Z compatible IFC défini par des paramètres.

```csharp
public class ZShape : ParameterizedProfile
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ZShape](zshape/)() | Constructeur de `ZShape` |

## Propriétés

| Nom | Description |
| --- | --- |
| [Depth](../../aspose.threed.profiles/zshape/depth/) { get; set; } | Obtient ou définit la longueur de l'âme. |
| [EdgeRadius](../../aspose.threed.profiles/zshape/edgeradius/) { get; set; } | Obtient ou définit le rayon du bord de la bride. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| [FilletRadius](../../aspose.threed.profiles/zshape/filletradius/) { get; set; } | Obtient ou définit le rayon du congé entre la bride et l'âme. |
| [FlangeThickness](../../aspose.threed.profiles/zshape/flangethickness/) { get; set; } | Obtient ou définit l'épaisseur de la bride. |
| [FlangeWidth](../../aspose.threed.profiles/zshape/flangewidth/) { get; set; } | Obtient ou définit la longueur de la bride. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [WebThickness](../../aspose.threed.profiles/zshape/webthickness/) { get; set; } | Obtient ou définit l'épaisseur du mur. |

## Méthodes

| Nom | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées en espace objet. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Obtient la clé du rendu d'entité enregistrée dans le moteur de rendu |
| override [GetExtent](../../aspose.threed.profiles/zshape/getextent/)() | Obtient l'étendue dans les dimensions x et y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |

### Voir aussi

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


