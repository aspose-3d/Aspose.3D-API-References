---
title: "Classe Pyramid"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Entities.Pyramid. Pyramide paramétrée"
type: docs
weight: 650
url: /fr/net/aspose.threed.entities/pyramid/
---
## Pyramid class

Pyramide paramétrée.

```csharp
public class Pyramid : Primitive
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Pyramid](pyramid/#constructor)() | Construisez une nouvelle instance de pyramide avec la zone inférieure par défaut (10, 10) et la hauteur par défaut (5) |
| [Pyramid](pyramid/#constructor_1)(double, double, double) | Construisez une nouvelle instance de pyramide avec la zone inférieure spécifiée |
| [Pyramid](pyramid/#constructor_2)(double, double, double, double, double) | Construisez une nouvelle instance de pyramide avec la zone inférieure et la zone supérieure spécifiées ainsi que la hauteur. |
| [Pyramid](pyramid/#constructor_3)(string, double, double, double, double, double) | Construisez une nouvelle instance de pyramide avec la zone inférieure et la zone supérieure spécifiées ainsi que la hauteur. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BottomArea](../../aspose.threed.entities/pyramid/bottomarea/) { get; set; } | Surface du cap inférieur |
| [BottomOffset](../../aspose.threed.entities/pyramid/bottomoffset/) { get; set; } | Décalage pour les sommets inférieurs |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Obtient ou définit si cette géométrie peut projeter une ombre |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| [Height](../../aspose.threed.entities/pyramid/height/) { get; set; } | Hauteur de la pyramide |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Obtient ou définit si cette géométrie peut recevoir des ombres. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [TopArea](../../aspose.threed.entities/pyramid/toparea/) { get; set; } | Surface du cap supérieur |

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
| override [ToMesh](../../aspose.threed.entities/pyramid/tomesh/)() | Convertir l'objet actuel en maillage |

### Voir aussi

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


