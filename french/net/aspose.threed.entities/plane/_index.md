---
title: "Classe Plane"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Entities.Plane. Plan paramétré"
type: docs
weight: 590
url: /fr/net/aspose.threed.entities/plane/
---
## Plane class

Plan paramétré.

```csharp
public class Plane : Primitive
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Plane](plane/#constructor)() | Initialise une nouvelle instance de `Plane` avec la taille par défaut 1x1. |
| [Plane](plane/#constructor_1)(double, double) | Initialise une nouvelle instance de `Plane`. |
| [Plane](plane/#constructor_2)(string, double, double, int, int) | Initialise une nouvelle instance de `Plane`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Obtient ou définit si cette géométrie peut projeter une ombre |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| [Length](../../aspose.threed.entities/plane/length/) { get; set; } | Obtient ou définit la longueur du plan. |
| [LengthSegments](../../aspose.threed.entities/plane/lengthsegments/) { get; set; } | Obtient ou définit les segments de longueur. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Obtient ou définit si cette géométrie peut recevoir des ombres. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [Up](../../aspose.threed.entities/plane/up/) { get; set; } | Obtient ou définit le vecteur up du plan, la valeur par défaut est (0, 1, 0), cela affecte la génération du plan |
| [Width](../../aspose.threed.entities/plane/width/) { get; set; } | Obtient ou définit la largeur du plan. |
| [WidthSegments](../../aspose.threed.entities/plane/widthsegments/) { get; set; } | Obtient ou définit les segments de largeur. |

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
| override [ToMesh](../../aspose.threed.entities/plane/tomesh/)() | Convertir l'objet actuel en maillage |

### Voir aussi

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


