---
title: "Classe Node"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Node. Représente un élément du graphe de scène. Un graphe de scène est un arbre d'objets Node. Les services de gestion d'arbre sont autonomes dans cette classe. Notez que le SDK Aspose.3D ne teste pas la validité du graphe de scène construit. Il incombe à l'appelant de s'assurer qu'il ne génère pas de graphes cycliques dans la hiérarchie des nœuds. En plus de la gestion d'arbre, cette classe définit toutes les propriétés nécessaires pour décrire la position de l'objet dans la scène. Ces informations incluent les propriétés de base Translation, Rotation et Scaling ainsi que les options avancées pour les pivots, les limites et les attributs des articulations IK tels que la raideur et l'amortissement. Lorsqu'il est créé pour la première fois, l'objet Node est vide, c'est-à-dire qu'il s'agit d'un objet sans représentation graphique qui ne contient que les informations de position. Dans cet état, il peut être utilisé pour représenter des parents dans la structure arborescente des nœuds mais pas bien plus. L'utilisation normale de ce type d'objets est de leur ajouter une entité qui spécialisera le nœud, voir l'Entity. L'entité est un objet en soi et est connectée au Node. Cela signifie également que la même entité peut être partagée entre plusieurs nœuds. Camera Light Mesh etc... sont toutes des entités et elles dérivent toutes de la classe de base Entity"
type: docs
weight: 1630
url: /fr/net/aspose.threed/node/
---
## Node class

Représente un élément du graphe de scène. Un graphe de scène est un arbre d'objets Node. Les services de gestion de l'arbre sont autonomes dans cette classe. Notez que le SDK Aspose.3D ne teste pas la validité du graphe de scène construit. Il incombe à l'appelant de s'assurer qu'il ne génère pas de graphes cycliques dans la hiérarchie des nœuds. En plus de la gestion de l'arbre, cette classe définit toutes les propriétés nécessaires pour décrire la position de l'objet dans la scène. Ces informations incluent les propriétés de Translation, Rotation et Échelle de base ainsi que les options avancées pour les pivots, limites et attributs des articulations IK tels que la raideur et l'amortissement. Lorsqu'il est créé pour la première fois, l'objet Node est "empty" (c'est‑à‑dire qu'il s'agit d'un objet sans aucune représentation graphique qui ne contient que les informations de position). Dans cet état, il peut être utilisé pour représenter les parents dans la structure arborescente des nœuds mais pas bien plus. L'utilisation normale de ce type d'objets consiste à leur ajouter une entité qui spécialisera le nœud (voir "Entity"). L'entité est un objet en soi et est connectée au Node. Cela signifie également que la même entité peut être partagée entre plusieurs nœuds. Camera, Light, Mesh, etc... sont toutes des entités et toutes dérivent de la classe de base Entity.

```csharp
public class Node : SceneObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Node](node/#constructor)() | Initialise une nouvelle instance de la classe `Node`. |
| [Node](node/#constructor_1)(string) | Initialise une nouvelle instance de la classe `Node`. |
| [Node](node/#constructor_2)(string, Entity) | Initialise une nouvelle instance de la classe `Node`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AssetInfo](../../aspose.threed/node/assetinfo/) { get; set; } | Informations d'actif par nœud |
| [ChildNodes](../../aspose.threed/node/childnodes/) { get; } | Obtient les nœuds enfants. |
| [Entities](../../aspose.threed/node/entities/) { get; } | Obtient toutes les entités du nœud. |
| [Entity](../../aspose.threed/node/entity/) { get; set; } | Obtient ou définit la première entité attachée à ce nœud, si définie, les autres entités seront supprimées. |
| [Excluded](../../aspose.threed/node/excluded/) { get; set; } | Obtient ou définit s'il faut exclure ce nœud et tous les nœuds/entités enfants lors de l'exportation. |
| [GlobalTransform](../../aspose.threed/node/globaltransform/) { get; } | Obtient la transformation globale. |
| [Material](../../aspose.threed/node/material/) { get; set; } | Obtient ou définit le premier matériau associé à ce nœud, si défini, les autres matériaux seront supprimés |
| [Materials](../../aspose.threed/node/materials/) { get; } | Obtient les matériaux associés à ce nœud. |
| [MetaDatas](../../aspose.threed/node/metadatas/) { get; } | Obtient les métadonnées définies dans ce nœud. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [ParentNode](../../aspose.threed/node/parentnode/) { get; set; } | Obtient ou définit le nœud parent. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtient la scène à laquelle cet objet appartient |
| [Transform](../../aspose.threed/node/transform/) { get; } | Obtient la transformation locale. |
| [Visible](../../aspose.threed/node/visible/) { get; set; } | Obtient ou définit l'affichage du nœud |

## Méthodes

| Nom | Description |
| --- | --- |
| [Accept](../../aspose.threed/node/accept/)(NodeVisitor) | Parcourt tous les nœuds descendants (y compris le nœud actuel) et appelle le visiteur avec le nœud. Le visiteur peut interrompre le parcours en retournant false |
| [AddChildNode](../../aspose.threed/node/addchildnode/)(Node) | Ajouter un nœud enfant à ce nœud |
| [AddEntity](../../aspose.threed/node/addentity/)(Entity) | Ajouter une entité au nœud. |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode)() | Crée un nœud enfant |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_1)(Entity) | Créer un nouveau nœud enfant avec l'entité donnée attachée |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_2)(string) | Créer un nouveau nœud enfant avec le nom de nœud donné |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_3)(string, Entity) | Créer un nouveau nœud enfant avec le nom de nœud donné |
| [CreateChildNode](../../aspose.threed/node/createchildnode/#createchildnode_4)(string, Entity, Material) | Créer un nouveau nœud enfant avec le nom de nœud donné, et attacher l'entité spécifiée ainsi qu'un matériau |
| [EvaluateGlobalTransform](../../aspose.threed/node/evaluateglobaltransform/)(bool) | Évaluer la transformation globale, inclure ou non la transformation géométrique. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetBoundingBox](../../aspose.threed/node/getboundingbox/)() | Calculer la boîte englobante du nœud |
| [GetChild](../../aspose.threed/node/getchild/#getchild)(int) | Obtient le nœud enfant à l'index spécifié. |
| [GetChild](../../aspose.threed/node/getchild/#getchild_1)(string) | Obtient le nœud enfant avec le nom spécifié |
| [GetEntity&lt;T&gt;](../../aspose.threed/node/getentity/)() |  |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [Merge](../../aspose.threed/node/merge/)(Node) | Détacher tout ce qui se trouve sous le nœud et les attacher au nœud actuel. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [SelectObjects](../../aspose.threed/node/selectobjects/)(string) | Sélectionner plusieurs objets sous le nœud actuel en utilisant une syntaxe de requête de type XPath. |
| [SelectSingleObject](../../aspose.threed/node/selectsingleobject/)(string) | Sélectionner un seul objet sous le nœud actuel en utilisant une syntaxe de requête de type XPath. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |
| override [ToString](../../aspose.threed/node/tostring/)() | Obtient la représentation sous forme de chaîne de ce nœud. |

### Voir aussi

* class [SceneObject](../sceneobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


