---
title: Os
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/bone/
---
## Bone class

Un os définit le sous-ensemble des points de contrôle de la géométrie et définit le poids de mélange pour chaque point de contrôle.  L'objet Bone ne peut pas être utilisé directement, une instance de SkinDeformer est utilisée pour déformer la géométrie, et SkinDeformer est fourni avec un ensemble d'os, chaque os étant lié à un nœud.  NOTE : Un point de contrôle d'une géométrie peut être lié à plusieurs os.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor(name) | Initialise une nouvelle instance de la classe Bone. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Name. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload() | Initialise une nouvelle instance de la classe Bone. |

 **Result:**



---


### getWeightCount{#getWeightCount}

| Nom | Description |
| --- | --- |
| getWeightCount() | Obtient le nombre de poids, celui-ci est automatiquement étendu par setWeight(int, double) |

 **Result:**



---


### getTransform{#getTransform}

| Nom | Description |
| --- | --- |
| getTransform() | Obtient ou définit la matrice de transformation du nœud contenant le bone. |

 **Result:**



---


### setTransform{#setTransform}

| Nom | Description |
| --- | --- |
| setTransform(value) | Obtient ou définit la matrice de transformation du nœud contenant le bone. |

 **Result:**



---


### getBoneTransform{#getBoneTransform}

| Nom | Description |
| --- | --- |
| getBoneTransform() | Obtient ou définit la matrice de transformation du bone. |

 **Result:**



---


### setBoneTransform{#setBoneTransform}

| Nom | Description |
| --- | --- |
| setBoneTransform(value) | Obtient ou définit la matrice de transformation du bone. |

 **Result:**



---


### getNode{#getNode}

| Nom | Description |
| --- | --- |
| getNode() | Obtient ou définit le nœud. Le nœud bone est l'os auquel la peau est attachée, le SkinDeformer utilisera le nœud bone pour influencer le déplacement des points de contrôle. Le nœud bone possède généralement un Skeleton attaché, mais ce n'est pas obligatoire. Le Skeleton attaché est généralement utilisé par les logiciels DCC pour afficher le squelette à l'utilisateur. |

 **Result:**



---


### setNode{#setNode}

| Nom | Description |
| --- | --- |
| setNode(value) | Obtient ou définit le nœud. Le nœud bone est l'os auquel la peau est attachée, le SkinDeformer utilisera le nœud bone pour influencer le déplacement des points de contrôle. Le nœud bone possède généralement un Skeleton attaché, mais ce n'est pas obligatoire. Le Skeleton attaché est généralement utilisé par les logiciels DCC pour afficher le squelette à l'utilisateur. |

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


### get{#get}

| Nom | Description |
| --- | --- |
| get(index) |  |

 **Result:**



---


### set{#set}

| Nom | Description |
| --- | --- |
| set(index, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| Nom | Description |
| --- | --- |
| getWeight(index) | Obtient le poids du point de contrôle spécifié par l'index |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| indice | Number | Index du point de contrôle |

 **Result:**
Number


---


### setWeight{#setWeight}

| Nom | Description |
| --- | --- |
| setWeight(index, weight) | Définit le poids du point de contrôle spécifié par l'index |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| indice | Number | Index du point de contrôle |
| poids | Number | Nouveau poids |

 **Result:**
Number


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



