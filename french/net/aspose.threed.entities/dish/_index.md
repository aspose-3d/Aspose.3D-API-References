---
title: "Classe Dish"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Entities.Dish. Dish paramétré"
type: docs
weight: 370
url: /fr/net/aspose.threed.entities/dish/
---
## Dish class

Plat paramétré.

```csharp
public class Dish : Primitive
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Dish](dish/#constructor)() | Créez une nouvelle instance de dish avec un rayon par défaut (10) et une hauteur par défaut (5) |
| [Dish](dish/#constructor_1)(double, double) | Créez une nouvelle instance de dish avec le rayon et la hauteur spécifiés |
| [Dish](dish/#constructor_2)(string, double, double, int, int) | Créez une nouvelle instance de dish avec le rayon et la hauteur spécifiés |

## Propriétés

| Nom | Description |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Obtient ou définit si cette géométrie peut projeter une ombre |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| [Height](../../aspose.threed.entities/dish/height/) { get; set; } | Hauteur du dish |
| [HeightSegments](../../aspose.threed.entities/dish/heightsegments/) { get; set; } | Obtient ou définit les segments de hauteur |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Radius](../../aspose.threed.entities/dish/radius/) { get; set; } | Rayon du dish |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Obtient ou définit si cette géométrie peut recevoir des ombres. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [WidthSegments](../../aspose.threed.entities/dish/widthsegments/) { get; set; } | Obtient ou définit les segments de largeur |

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
| override [ToMesh](../../aspose.threed.entities/dish/tomesh/)() | Convertir l'objet actuel en maillage |

### Voir aussi

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


