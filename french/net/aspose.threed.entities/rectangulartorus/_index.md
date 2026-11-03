---
title: "Classe RectangularTorus"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Entities.RectangularTorus. Tore rectangulaire paramétré"
type: docs
weight: 660
url: /fr/net/aspose.threed.entities/rectangulartorus/
---
## RectangularTorus class

Tore rectangulaire paramétré.

```csharp
public class RectangularTorus : Primitive
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [RectangularTorus](rectangulartorus/#constructor)() | Constructeur de `RectangularTorus` |
| [RectangularTorus](rectangulartorus/#constructor_1)(string) | Constructeur de `RectangularTorus` |

## Propriétés

| Nom | Description |
| --- | --- |
| [AngleStart](../../aspose.threed.entities/rectangulartorus/anglestart/) { get; set; } | L'angle de départ de l'arc, mesuré en radians. La valeur par défaut est 0 |
| [Arc](../../aspose.threed.entities/rectangulartorus/arc/) { get; set; } | L'angle total de l'arc, mesuré en radians. La valeur par défaut est PI |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Obtient ou définit si cette géométrie peut projeter une ombre |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| [Height](../../aspose.threed.entities/rectangulartorus/height/) { get; set; } | La hauteur du tore rectangulaire. La valeur par défaut est 20 |
| [InnerRadius](../../aspose.threed.entities/rectangulartorus/innerradius/) { get; set; } | Le rayon intérieur du tore rectangulaire. La valeur par défaut est 17 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [OuterRadius](../../aspose.threed.entities/rectangulartorus/outerradius/) { get; set; } | Le rayon extérieur du tore rectangulaire. La valeur par défaut est 20 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [RadialSegments](../../aspose.threed.entities/rectangulartorus/radialsegments/) { get; set; } | Les segments radiaux, la valeur par défaut est 10 |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Obtient ou définit si cette géométrie peut recevoir des ombres. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |

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
| override [ToMesh](../../aspose.threed.entities/rectangulartorus/tomesh/)() | Convertir cette primitive en [`Mesh`](../mesh/) |

### Voir aussi

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


