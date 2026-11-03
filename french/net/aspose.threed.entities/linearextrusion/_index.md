---
title: "Classe LinearExtrusion"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Entities.LinearExtrusion classe. L'extrusion linéaire prend une forme 2D en entrée et étend la forme dans la troisième dimension"
type: docs
weight: 490
url: /fr/net/aspose.threed.entities/linearextrusion/
---
## LinearExtrusion class

L'extrusion linéaire prend une forme 2D en entrée et étend la forme dans la troisième dimension.

```csharp
public class LinearExtrusion : Entity, IMeshConvertible
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [LinearExtrusion](linearextrusion/#constructor)() | Constructeur de l'instance `LinearExtrusion`. |
| [LinearExtrusion](linearextrusion/#constructor_1)(Profile, double) | Constructeur de l'instance `LinearExtrusion`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Center](../../aspose.threed.entities/linearextrusion/center/) { get; set; } | Si cette valeur est fausse, la plage Z de l'extrusion linéaire va de 0 à la hauteur, sinon la plage va de -hauteur/2 à hauteur/2. |
| [Direction](../../aspose.threed.entities/linearextrusion/direction/) { get; set; } | La direction de l'extrusion, la valeur par défaut est (0, 0, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| [Height](../../aspose.threed.entities/linearextrusion/height/) { get; set; } | La hauteur de la géométrie extrudée, la valeur par défaut est 1,0 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [Shape](../../aspose.threed.entities/linearextrusion/shape/) { get; set; } | La forme de base à extruder. |
| [Slices](../../aspose.threed.entities/linearextrusion/slices/) { get; set; } | Les tranches de la géométrie extrudée torsadée, la valeur par défaut est 1. |
| [Twist](../../aspose.threed.entities/linearextrusion/twist/) { get; set; } | Le nombre de degrés à travers lesquels la forme est extrudée. |
| [TwistOffset](../../aspose.threed.entities/linearextrusion/twistoffset/) { get; set; } | Le décalage utilisé dans la torsion, la valeur par défaut est (0, 0, 0). |

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
| [ToMesh](../../aspose.threed.entities/linearextrusion/tomesh/)() | Convertir l'extrusion en maillage. |

## Exemples

Le code suivant montre comment utiliser LinearExtrusion pour extruder une forme en modèle solide.

```csharp
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Profiles;

//Créer une nouvelle scène 3D
Scene scene = new Scene();

// Initialiser le profil de base à extruder
var profile = new RectangleShape()
{
	RoundingRadius = 0.3
};

// Créer le nœud gauche
var left = scene.RootNode.CreateChildNode();
left.CreateChildNode(new Box(0.01, 3, 3));

// Créer le nœud droit
var right = scene.RootNode.CreateChildNode();
right.CreateChildNode(new Box(0.01, 3, 3));
right.Transform.Translation = new Vector3(5, 0, 0);

//Effectuer une extrusion linéaire sur le nœud gauche en utilisant les propriétés centre et tranches
left.CreateChildNode(new LinearExtrusion(profile, 10) { Center = false, Slices = 3, Twist = 20.0 });

// Effectuer une extrusion linéaire sur le nœud gauche en utilisant les propriétés centre et tranches
right.CreateChildNode(new LinearExtrusion(profile, 10) { Center = true, Slices = 3, Twist = 90.0 });

scene
```

### Voir aussi

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


