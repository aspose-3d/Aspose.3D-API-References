---
title: "Classe Torus"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Entities.Torus. Torus paramétré"
type: docs
weight: 770
url: /fr/net/aspose.threed.entities/torus/
---
## Torus class

Tore paramétré.

```csharp
public class Torus : Primitive
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Torus](torus/#constructor)() | Initialise une nouvelle instance de la classe `Torus`. |
| [Torus](torus/#constructor_1)(double, double) | Initialise une nouvelle instance de la classe `Torus`. |
| [Torus](torus/#constructor_2)(double, double, double) | Initialise une nouvelle instance de la classe `Torus`. |
| [Torus](torus/#constructor_3)(string, double, double, int, int, double) | Initialise une nouvelle instance de la classe `Torus`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Arc](../../aspose.threed.entities/torus/arc/) { get; set; } | Obtient ou définit l'arc. |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Obtient ou définit si cette géométrie peut projeter une ombre |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [RadialSegments](../../aspose.threed.entities/torus/radialsegments/) { get; set; } | Obtient ou définit les segments radiaux. |
| [Radius](../../aspose.threed.entities/torus/radius/) { get; set; } | Obtient ou définit le rayon du torus. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Obtient ou définit si cette géométrie peut recevoir des ombres. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [Tube](../../aspose.threed.entities/torus/tube/) { get; set; } | Obtient ou définit le rayon du tube. |
| [TubularSegments](../../aspose.threed.entities/torus/tubularsegments/) { get; set; } | Obtient ou définit les segments tubulaires. |

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
| override [ToMesh](../../aspose.threed.entities/torus/tomesh/)() | Convertir l'objet actuel en maillage |

### Voir aussi

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


