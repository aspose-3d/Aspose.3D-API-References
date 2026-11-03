---
title: "Classe Sphere"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Entities.Sphere. Sphère paramétrée"
type: docs
weight: 730
url: /fr/net/aspose.threed.entities/sphere/
---
## Sphere class

Sphère paramétrée.

```csharp
public class Sphere : Primitive
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Sphere](sphere/#constructor)() | Initialise une nouvelle instance de `Sphere` avec un rayon par défaut de 1. |
| [Sphere](sphere/#constructor_1)(double) | Initialise une nouvelle instance de la classe `Sphere` avec le rayon spécifié. |
| [Sphere](sphere/#constructor_2)(double, int, int) | Initialise une nouvelle instance de la classe `Sphere` avec le rayon, les segments de largeur et les segments de hauteur spécifiés. |
| [Sphere](sphere/#constructor_3)(string, double, int, int, double, double, double, double) | Initialise une nouvelle instance de la classe `Sphere`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Obtient ou définit si cette géométrie peut projeter une ombre |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| [HeightSegments](../../aspose.threed.entities/sphere/heightsegments/) { get; set; } | Obtient ou définit les segments de hauteur. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [PhiLength](../../aspose.threed.entities/sphere/philength/) { get; set; } | Obtient ou définit la longueur du phi. |
| [PhiStart](../../aspose.threed.entities/sphere/phistart/) { get; set; } | Obtient ou définit le point de départ du phi. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Radius](../../aspose.threed.entities/sphere/radius/) { get; set; } | Obtient ou définit le rayon de la sphère. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Obtient ou définit si cette géométrie peut recevoir des ombres. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [ThetaLength](../../aspose.threed.entities/sphere/thetalength/) { get; set; } | Obtient ou définit la longueur du theta. |
| [ThetaStart](../../aspose.threed.entities/sphere/thetastart/) { get; set; } | Obtient ou définit le point de départ du theta. |
| [WidthSegments](../../aspose.threed.entities/sphere/widthsegments/) { get; set; } | Obtient ou définit les segments de largeur. |

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
| override [ToMesh](../../aspose.threed.entities/sphere/tomesh/)() | Convertir l'objet actuel en maillage |

### Voir aussi

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


