---
title: "Classe UShape"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Profiles.UShape. Ushape compatible IFC défini par des paramètres"
type: docs
weight: 1840
url: /fr/net/aspose.threed.profiles/ushape/
---
## UShape class

Forme en U compatible IFC définie par des paramètres.

```csharp
public class UShape : ParameterizedProfile
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [UShape](ushape/)() | Constructeur de `UShape` |

## Propriétés

| Nom | Description |
| --- | --- |
| [Depth](../../aspose.threed.profiles/ushape/depth/) { get; set; } | Obtient ou définit la longueur de l'âme. |
| [EdgeRadius](../../aspose.threed.profiles/ushape/edgeradius/) { get; set; } | Obtient ou définit le rayon du bord dans le bord de la bride. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| [FilletRadius](../../aspose.threed.profiles/ushape/filletradius/) { get; set; } | Obtient ou définit le rayon du congé entre la bride et l'âme. |
| [FlangeThickness](../../aspose.threed.profiles/ushape/flangethickness/) { get; set; } | Obtient ou définit l'épaisseur de la bride. |
| [FlangeWidth](../../aspose.threed.profiles/ushape/flangewidth/) { get; set; } | Obtient ou définit la longueur de la bride. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [WebThickness](../../aspose.threed.profiles/ushape/webthickness/) { get; set; } | Obtient ou définit l'épaisseur de la traverse. |

## Méthodes

| Nom | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées en espace objet. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Obtient la clé du rendu d'entité enregistrée dans le moteur de rendu |
| override [GetExtent](../../aspose.threed.profiles/ushape/getextent/)() | Obtient l'étendue dans les dimensions x et y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |

### Voir aussi

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


