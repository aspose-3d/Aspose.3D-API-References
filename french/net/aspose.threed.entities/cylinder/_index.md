---
title: "Classe Cylinder"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Entities.Cylinder. Cylindre paramétré. Il peut également être utilisé pour représenter le cône lorsqu'un des rayons radiusTop/radiusBottom est nul"
type: docs
weight: 360
url: /fr/net/aspose.threed.entities/cylinder/
---
## Cylinder class

Cylindre paramétré. Il peut également être utilisé pour représenter le cône lorsque l'un des rayons radiusTop/radiusBottom est nul.

```csharp
public class Cylinder : Primitive
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Cylinder](cylinder/#constructor)() | Initialise une nouvelle instance de la classe `Cylinder`. |
| [Cylinder](cylinder/#constructor_1)(double, double) | Initialise une nouvelle instance de la classe `Cylinder`. |
| [Cylinder](cylinder/#constructor_2)(double, double, double) | Initialise une nouvelle instance de la classe `Cylinder`. |
| [Cylinder](cylinder/#constructor_3)(double, double, double, int, int, bool) | Initialise une nouvelle instance de la classe `Cylinder`. |
| [Cylinder](cylinder/#constructor_4)(string, double, double, double, int, int, bool, double, double) | Initialise une nouvelle instance de la classe `Cylinder`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Obtient ou définit si cette géométrie peut projeter une ombre |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| [GenerateFanCylinder](../../aspose.threed.entities/cylinder/generatefancylinder/) { get; set; } | Obtient ou définit s'il faut générer le cylindre de type évent lorsque ThetaLength est inférieur à 2*PI, sinon le modèle ne sera pas découpé. |
| [Height](../../aspose.threed.entities/cylinder/height/) { get; set; } | Obtient ou définit la hauteur du cylindre. |
| [HeightSegments](../../aspose.threed.entities/cylinder/heightsegments/) { get; set; } | Obtient ou définit les segments de hauteur. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [OffsetBottom](../../aspose.threed.entities/cylinder/offsetbottom/) { get; set; } | Obtient ou définit le décalage de transformation des sommets du côté inférieur. |
| [OffsetTop](../../aspose.threed.entities/cylinder/offsettop/) { get; set; } | Obtient ou définit le décalage de transformation des sommets du côté supérieur. |
| [OpenEnded](../../aspose.threed.entities/cylinder/openended/) { get; set; } | Obtient ou définit une valeur indiquant si ce `Cylinder` est ouvert à une extrémité. La valeur par défaut est false. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [RadialSegments](../../aspose.threed.entities/cylinder/radialsegments/) { get; set; } | Obtient ou définit les segments radiaux. |
| [RadiusBottom](../../aspose.threed.entities/cylinder/radiusbottom/) { get; set; } | Obtient ou définit le rayon du couvercle inférieur du cylindre. |
| [RadiusTop](../../aspose.threed.entities/cylinder/radiustop/) { get; set; } | Obtient ou définit le rayon du couvercle supérieur du cylindre. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Obtient ou définit si cette géométrie peut recevoir des ombres. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [ShearBottom](../../aspose.threed.entities/cylinder/shearbottom/) { get; set; } | Obtient ou définit la transformation de cisaillement du côté inférieur, le vecteur stocke la valeur de cisaillement (axe x, axe z) mesurée en radians, la valeur par défaut est (0, 0). |
| [ShearTop](../../aspose.threed.entities/cylinder/sheartop/) { get; set; } | Obtient ou définit la transformation de cisaillement du côté supérieur, le vecteur stocke la valeur de cisaillement (axe x, axe z) mesurée en radians, la valeur par défaut est (0, 0). |
| [ThetaLength](../../aspose.threed.entities/cylinder/thetalength/) { get; set; } | Obtient ou définit la longueur de theta. La valeur par défaut est 2π. |
| [ThetaStart](../../aspose.threed.entities/cylinder/thetastart/) { get; set; } | Obtient ou définit le départ de theta. La valeur par défaut est 0. |

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
| override [ToMesh](../../aspose.threed.entities/cylinder/tomesh/)() | Convertir l'objet actuel en maillage |

### Voir aussi

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


