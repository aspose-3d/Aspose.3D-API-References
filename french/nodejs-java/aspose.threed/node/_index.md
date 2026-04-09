---
title: Node
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/node/
---
## Node class

Représente un élément du graphe de scène. Un graphe de scène est un arbre d'objets Node. Les services de gestion d'arbre sont autonomes dans cette classe. Notez que le SDK Aspose.3D ne teste pas la validité du graphe de scène construit. Il incombe à l'appelant de s'assurer qu'il ne génère pas de graphes cycliques dans une hiérarchie de nœuds. En plus de la gestion d'arbre, cette classe définit toutes les propriétés nécessaires pour décrire la position de l'objet dans la scène. Ces informations incluent les propriétés de base Translation, Rotation et Scaling ainsi que les options avancées pour les pivots, limites et les attributs des articulations IK tels que la rigidité et l'amortissement. Lorsqu'il est créé pour la première fois, l'objet Node est "vide" (c.-à-d. il s'agit d'un objet sans représentation graphique qui ne contient que les informations de position). Dans cet état, il peut être utilisé pour représenter des parents dans la structure d'arbre de nœuds mais pas bien plus. L'utilisation normale de ce type d'objets consiste à leur ajouter une entité qui spécialisera le nœud (voir "Entity"). L'entité est un objet à part entière et est connectée au Node. Cela signifie également que la même entité peut être partagée entre plusieurs nœuds. Camera, Light, Mesh, etc. sont toutes des entités et toutes dérivent de la classe de base Entity.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Initialise une nouvelle instance de la classe Node. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(name, entity) | Initialise une nouvelle instance de la classe Node. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Name. |
| entity | Entity | Entité par défaut. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nom | Description |
| --- | --- |
| constructor_overload2(name) | Initialise une nouvelle instance de la classe Node. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Name. |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| Nom | Description |
| --- | --- |
| getAssetInfo() | Informations d'actif par nœud |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Nom | Description |
| --- | --- |
| setAssetInfo(value) | Informations d'actif par nœud |

 **Result:**



---


### getVisible{#getVisible}

| Nom | Description |
| --- | --- |
| getVisible() | Obtient ou définit l'affichage du nœud |

 **Result:**



---


### setVisible{#setVisible}

| Nom | Description |
| --- | --- |
| setVisible(value) | Obtient ou définit l'affichage du nœud |

 **Result:**



---


### getChildNodes{#getChildNodes}

| Nom | Description |
| --- | --- |
| getChildNodes() | Obtient les nœuds enfants. Les nœuds. |

 **Result:**



---


### getEntity{#getEntity}

| Nom | Description |
| --- | --- |
| getEntity() | Obtient ou définit la première entité attachée à ce nœud, si définie, effacera les autres entités. L'entité du nœud. |

 **Result:**



---


### setEntity{#setEntity}

| Nom | Description |
| --- | --- |
| setEntity(value) | Obtient ou définit la première entité attachée à ce nœud, si définie, effacera les autres entités. L'entité du nœud. |

 **Result:**



---


### getExcluded{#getExcluded}

| Nom | Description |
| --- | --- |
| getExcluded() | Obtient ou définit si ce nœud et tous les nœuds/enfants/entités doivent être exclus lors de l'exportation. |

 **Result:**



---


### setExcluded{#setExcluded}

| Nom | Description |
| --- | --- |
| setExcluded(value) | Obtient ou définit si ce nœud et tous les nœuds/enfants/entités doivent être exclus lors de l'exportation. |

 **Result:**



---


### getEntities{#getEntities}

| Nom | Description |
| --- | --- |
| getEntities() | Obtient toutes les entités du nœud. Les entités du nœud. |

 **Result:**



---


### getMetaDatas{#getMetaDatas}

| Nom | Description |
| --- | --- |
| getMetaDatas() | Obtient les métadonnées définies dans ce nœud. Les métadonnées. |

 **Result:**



---


### getMaterials{#getMaterials}

| Nom | Description |
| --- | --- |
| getMaterials() | Obtient les matériaux associés à ce nœud. Les matériaux. |

 **Result:**



---


### getMaterial{#getMaterial}

| Nom | Description |
| --- | --- |
| getMaterial() | Obtient ou définit le premier matériau associé à ce nœud ; si défini, les autres matériaux seront supprimés. Le matériau. |

 **Result:**



---


### setMaterial{#setMaterial}

| Nom | Description |
| --- | --- |
| setMaterial(value) | Obtient ou définit le premier matériau associé à ce nœud ; si défini, les autres matériaux seront supprimés. Le matériau. |

 **Result:**



---


### getParentNode{#getParentNode}

| Nom | Description |
| --- | --- |
| getParentNode() | Obtient ou définit le nœud parent. Le nœud parent. |

 **Result:**



---


### setParentNode{#setParentNode}

| Nom | Description |
| --- | --- |
| setParentNode(value) | Obtient ou définit le nœud parent. Le nœud parent. |

 **Result:**



---


### getTransform{#getTransform}

| Nom | Description |
| --- | --- |
| getTransform() | Obtient la transformation locale. La transformation. |

 **Result:**



---


### getGlobalTransform{#getGlobalTransform}

| Nom | Description |
| --- | --- |
| getGlobalTransform() | Obtient la transformation globale. La transformation globale. |

 **Result:**



---


### getScene{#getScene}

| Nom | Description |
| --- | --- |
| getScene() | Obtient la scène à laquelle cet objet appartient |

 **Result:**



---


### getName{#getName}

| Nom | Description |
| --- | --- |
| getName() | Obtient ou définit le nom. Le nom. |

 **Result:**



---


### setName{#setName}

| Nom | Description |
| --- | --- |
| setName(value) | Obtient ou définit le nom. Le nom. |

 **Result:**



---


### getProperties{#getProperties}

| Nom | Description |
| --- | --- |
| getProperties() | Obtient la collection de toutes les propriétés. |

 **Result:**



---


### createChildNode{#createChildNode}

| Nom | Description |
| --- | --- |
| createChildNode() | Crée un nœud enfant |

 **Result:**
Node


---


### merge{#merge}

| Nom | Description |
| --- | --- |
| merge(node) | Détache tout sous le nœud et les attache au nœud actuel. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nod | Node | null |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Nom | Description |
| --- | --- |
| createChildNode(nodeName) | Crée un nouveau nœud enfant avec le nom de nœud donné |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nodeName | String | Le nom du nouveau nœud enfant |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Nom | Description |
| --- | --- |
| createChildNode(entity) | Crée un nouveau nœud enfant avec l'entité donnée attachée |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| entity | Entity | Entité par défaut attachée au nœud |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Nom | Description |
| --- | --- |
| createChildNode(nodeName, entity) | Crée un nouveau nœud enfant avec le nom de nœud donné |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nodeName | String | Le nom du nouveau nœud enfant |
| entity | Entity | Entité par défaut attachée au nœud |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Nom | Description |
| --- | --- |
| createChildNode(nodeName, entity, material) | Crée un nouveau nœud enfant avec le nom de nœud donné, et attache l'entité spécifiée ainsi qu'un matériau |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nodeName | String | Le nom du nouveau nœud enfant |
| entity | Entity | Entité par défaut attachée au nœud |
| material | Material | Le matériau attaché au nœud |

 **Result:**
Node


---


### evaluateGlobalTransform{#evaluateGlobalTransform}

| Nom | Description |
| --- | --- |
| evaluateGlobalTransform(withGeometricTransform) | Évalue la transformation globale, inclut ou non la transformation géométrique. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| withGeometricTransform | boolean | Indique si la transformation géométrique est nécessaire. |

 **Result:**
Matrix4


---


### getChild{#getChild}

| Nom | Description |
| --- | --- |
| getChild(index) | Obtient le nœud enfant à l'index spécifié. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| indice | Number | Indice. |

 **Result:**
Node


---


### getChild{#getChild}

| Nom | Description |
| --- | --- |
| getChild(nodeName) | Obtient le nœud enfant avec le nom spécifié |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nodeName | String | Le nom de l'enfant à rechercher. |

 **Result:**
Node


---


### accept{#accept}

| Nom | Description |
| --- | --- |
| accept(visitor) | Parcourt tous les nœuds descendants (y compris le nœud actuel) et appelle le visiteur avec le nœud. Le visiteur peut interrompre le parcours en renvoyant false |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| visitor | NodeVisitor | Rappel du visiteur pour visiter le nœud |

 **Result:**
boolean


---


### toString{#toString}

| Nom | Description |
| --- | --- |
| toString() | Obtient la représentation sous forme de chaîne de ce nœud. |

 **Result:**
String


---


### getBoundingBox{#getBoundingBox}

| Nom | Description |
| --- | --- |
| getBoundingBox() | Calcule la boîte englobante du nœud |

 **Result:**
BoundingBox


---


### addEntity{#addEntity}

| Nom | Description |
| --- | --- |
| addEntity(entity) | Ajouter une Entity au nœud. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| entity | Entity | L'entité à attacher au nœud |

 **Result:**
BoundingBox


---


### addChildNode{#addChildNode}

| Nom | Description |
| --- | --- |
| addChildNode(node) | Ajouter un nœud enfant à ce nœud |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| node | Node | Le nœud enfant à attacher |

 **Result:**
BoundingBox


---


### selectSingleObject{#selectSingleObject}

| Nom | Description |
| --- | --- |
| selectSingleObject(path) | Sélectionne un seul objet sous le nœud actuel en utilisant une syntaxe de requête de type XPath. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| pat | String | null |

 **Result:**
Object


---


### selectObjects{#selectObjects}

| Nom | Description |
| --- | --- |
| selectObjects(path) | Sélectionne plusieurs objets sous le nœud actuel en utilisant une syntaxe de requête de type XPath. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| pat | String | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


---


### removeProperty{#removeProperty}

| Nom | Description |
| --- | --- |
| removeProperty(property) | Supprime une propriété dynamique. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propriété | Property | Quelle propriété supprimer |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Nom | Description |
| --- | --- |
| removeProperty(property) | Supprime la propriété spécifiée identifiée par son nom |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Nom | Description |
| --- | --- |
| getProperty(property) | Obtenir la valeur de la propriété spécifiée |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propriété | String | Nom de la propriété |

 **Result:**
Object


---


### setProperty{#setProperty}

| Nom | Description |
| --- | --- |
| setProperty(property, value) | Définit la valeur de la propriété spécifiée |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propriété | String | Nom de la propriété |
| valeur | Object | La valeur de la propriété |

 **Result:**
Object


---


### findProperty{#findProperty}

| Nom | Description |
| --- | --- |
| findProperty(propertyName) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propertyName | String | Nom de la propriété. |

 **Result:**
Property


---



