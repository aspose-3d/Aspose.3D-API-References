---
title: "Classe MirroredProfile"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Profiles.MirroredProfile. Profil miroir compatible IFC. Ce profil définit un nouveau profil en miroir du profil de base par rapport à l'axe y."
type: docs
weight: 1770
url: /fr/net/aspose.threed.profiles/mirroredprofile/
---
## MirroredProfile class

Profil miroir compatible IFC. Ce profil définit un nouveau profil en reflétant le profil de base autour de l'axe y.

```csharp
public class MirroredProfile : Profile
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MirroredProfile](mirroredprofile/)(Profile) | Construisez un nouveau `MirroredProfile` à partir d'un profil existant. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BaseProfile](../../aspose.threed.profiles/mirroredprofile/baseprofile/) { get; } | Le profil de base à refléter. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |

## Méthodes

| Nom | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées en espace objet. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Obtient la clé du rendu d'entité enregistrée dans le moteur de rendu |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |

### Voir aussi

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)


