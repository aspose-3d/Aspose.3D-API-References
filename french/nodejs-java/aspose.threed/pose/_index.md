---
title: Pose
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/pose/
---
## Pose class

La pose est utilisée pour stocker la matrice de transformation lorsque la géométrie est skinnée. La pose est un ensemble de BonePose, chaque BonePose enregistre les informations concrètes de transformation du nœud os.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor(name) | Initialise une nouvelle instance de la classe Pose. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Nom |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload() | Initialise une nouvelle instance de la classe Pose. |

 **Result:**



---


### getPoseType{#getPoseType}

| Nom | Description |
| --- | --- |
| getPoseType() | Obtient ou définit le type de la pose. La valeur de la propriété est la constante entière PoseType. Le type de la pose. |

 **Result:**



---


### setPoseType{#setPoseType}

| Nom | Description |
| --- | --- |
| setPoseType(value) | Obtient ou définit le type de la pose. La valeur de la propriété est la constante entière PoseType. Le type de la pose. |

 **Result:**



---


### getBonePoses{#getBonePoses}

| Nom | Description |
| --- | --- |
| getBonePoses() | Obtient tous les BonePose. Les nœuds. |

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


### addBonePose{#addBonePose}

| Nom | Description |
| --- | --- |
| addBonePose(node, matrix, localMatrix) | Enregistre la matrice de transformation de la pose pour le nœud os donné. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| node | Node | Nœud osseux. |
| matrice | Matrix4 | Matrice de transformation. |
| localMatrix | boolean | Si défini sur |

 **Result:**



---


### addBonePose{#addBonePose}

| Nom | Description |
| --- | --- |
| addBonePose(node, matrix) | Enregistre la matrice de transformation de pose pour le nœud osseux donné. La matrice de transformation globale est implicite. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| node | Node | Nœud osseux. |
| matrice | Matrix4 | Matrice de transformation. |

 **Result:**



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



