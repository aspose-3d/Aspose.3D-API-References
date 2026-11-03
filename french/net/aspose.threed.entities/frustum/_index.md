---
title: "Classe Frustum"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Entities.Frustum. La classe de base de Camera et Light"
type: docs
weight: 400
url: /fr/net/aspose.threed.entities/frustum/
---
## Frustum class

La classe de base de [`Camera`](../camera/) et [`Light`](../light/)

```csharp
public abstract class Frustum : Entity, IOrientable
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Aspect](../../aspose.threed.entities/frustum/aspect/) { get; set; } | Obtient ou définit le rapport d'aspect du frustum |
| [Direction](../../aspose.threed.entities/frustum/direction/) { get; set; } | Obtient ou définit la direction vers laquelle la caméra regarde. Les modifications de cette propriété affecteront également les [`LookAt`](./lookat/) et [`Target`](./target/). |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| [FarPlane](../../aspose.threed.entities/frustum/farplane/) { get; set; } | Obtient ou définit la distance du plan lointain du frustum. |
| [LookAt](../../aspose.threed.entities/frustum/lookat/) { get; set; } | Obtient ou définit la position d'intérêt vers laquelle la caméra regarde. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [NearPlane](../../aspose.threed.entities/frustum/nearplane/) { get; set; } | Obtient ou définit la distance du plan proche du frustum. |
| [OrthoHeight](../../aspose.threed.entities/frustum/orthoheight/) { get; set; } | Obtient ou définit la hauteur lorsque le frustum est en projection orthographique. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [RotationMode](../../aspose.threed.entities/frustum/rotationmode/) { get; set; } | Obtient ou définit le mode d'orientation du frustum. Cette propriété ne fonctionne que lorsque le [`Target`](./target/) est nul. Si la valeur est FixedTarget, la direction est toujours calculée par la propriété [`LookAt`](./lookat/). Sinon, le [`LookAt`](./lookat/) est toujours calculé par la [`Direction`](./direction/). |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [Target](../../aspose.threed.entities/frustum/target/) { get; set; } | Obtient ou définit la cible vers laquelle la caméra regarde. Si l'utilisateur prend en charge cette propriété, elle doit précéder la propriété [`LookAt`](./lookat/). |
| [Up](../../aspose.threed.entities/frustum/up/) { get; set; } | Obtient ou définit la direction vers le haut de la caméra |

## Méthodes

| Nom | Description |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées en espace objet. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Obtient la clé du rendu d'entité enregistrée dans le moteur de rendu |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |

### Voir aussi

* class [Entity](../../aspose.threed/entity/)
* interface [IOrientable](../iorientable/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


