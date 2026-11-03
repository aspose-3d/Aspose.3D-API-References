---
title: "Classe RevolvedAreaSolid"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Entities.RevolvedAreaSolid. Cette classe représente un modèle solide en faisant pivoter une section transversale fournie par un profil autour d'un axe"
type: docs
weight: 680
url: /fr/net/aspose.threed.entities/revolvedareasolid/
---
## RevolvedAreaSolid class

Cette classe représente un modèle solide en faisant tourner une section transversale fournie par un profil autour d'un axe.

```csharp
public class RevolvedAreaSolid : Entity, IMeshConvertible
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [RevolvedAreaSolid](revolvedareasolid/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AngleEnd](../../aspose.threed.entities/revolvedareasolid/angleend/) { get; set; } | Obtient ou définit l'angle final de la procédure de rotation, mesuré en radians, la valeur par défaut est pi. |
| [AngleStart](../../aspose.threed.entities/revolvedareasolid/anglestart/) { get; set; } | Obtient ou définit l'angle de départ de la procédure de rotation, mesuré en radians, la valeur par défaut est 0. |
| [Axis](../../aspose.threed.entities/revolvedareasolid/axis/) { get; set; } | Obtient ou définit la direction de l'axe, la valeur par défaut est (0, 1, 0). |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [Origin](../../aspose.threed.entities/revolvedareasolid/origin/) { get; set; } | Obtient ou définit le point d'origine de la rotation, la valeur par défaut est (0, 0, 0). |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [Shape](../../aspose.threed.entities/revolvedareasolid/shape/) { get; set; } | Obtient ou définit le profil de base utilisé pour la révolution. |

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
| [ToMesh](../../aspose.threed.entities/revolvedareasolid/tomesh/)() | Convertir le `RevolvedAreaSolid` en maillage. |

## Exemples

Le code suivant montre comment utiliser RevolvedAreaSolid pour faire pivoter une forme en un modèle solide.

```csharp
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Profiles;

//Créer une nouvelle scène 3D
Scene scene = new Scene();

// Initialiser le profil de base à faire pivoter
var profile = new RectangleShape()
{
    RoundingRadius = 0.3
};
//créer une instance de RevolvedAreaSolid 
var revolved = new RevolvedAreaSolid()
{
  Shape = profile,
  Origin = new Vector3(1, 0, 0),
  AngleStart = 0,
  AngleEnd = Math.PI
};
scene.RootNode.CreateChildNode(revolved);

scene.Save("revolved.obj");
```

```csharp
//Créer une nouvelle scène 3D
Scene scene = new Scene();

// Initialiser le profil de base à extruder
var profile = new RectangleShape();
profile.setRoundingRadius(0.3);

var revolved = new RevolvedAreaSolid();
revolved.setShape(profile);
revolved.setOrigin(new Vector3(1, 0, 0));
revolved.setAngleStart(0);
revolved.setAngleEnd(Math.PI);
scene.getRootNode().createChildNode(revolved);

scene.save("revolved.obj");
```

### Voir aussi

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


