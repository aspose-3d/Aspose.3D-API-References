---
title: "Class BooleanOperator"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Entities.BooleanOperator class. L'opérateur booléen vous permet d'appliquer une opération booléenne sur deux instances IMeshConvertible"
type: docs
weight: 280
url: /fr/net/aspose.threed.entities/booleanoperator/
---
## BooleanOperator class

L'opérateur booléen vous permet d'appliquer une opération booléenne sur deux instances [`IMeshConvertible`](../imeshconvertible/).

```csharp
public class BooleanOperator : Entity, IMeshConvertible
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [BooleanOperator](booleanoperator/#constructor)() | Constructeur de `BooleanOperator` |
| [BooleanOperator](booleanoperator/#constructor_1)(BooleanOperation, A3DObject, A3DObject) | Construit une nouvelle instance de `BooleanOperator` avec deux opérandes |

## Propriétés

| Nom | Description |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |
| [First](../../aspose.threed.entities/booleanoperator/first/) { get; set; } | Le premier opérande de l'opérateur booléen |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [Operator](../../aspose.threed.entities/booleanoperator/operator/) { get; set; } | L'opérateur booléen utilisé dans l'opération pour créer le maillage résultant. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [Second](../../aspose.threed.entities/booleanoperator/second/) { get; set; } | Le deuxième opérande de l'opérateur booléen |

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
| [ToMesh](../../aspose.threed.entities/booleanoperator/tomesh/)() | Effectuer l'opération booléenne sur deux opérandes |

### Voir aussi

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


