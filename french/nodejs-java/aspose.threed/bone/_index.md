---
title: "Bone"
second_title: "Référence d'API Aspose.3D pour Node.js via Java"
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/bone/
---
## Bone class

Un os définit le sous‑ensemble des points de contrôle de la géométrie et le poids de mélange défini pour chaque point de contrôle.  L'objet Bone ne peut pas être utilisé directement, une instance de SkinDeformer est utilisée pour déformer la géométrie, et SkinDeformer est fourni avec un ensemble d'os, chaque os étant lié à un nœud.  NOTE : Un point de contrôle d'une géométrie peut être lié à plusieurs os.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor(name) | Initialise une nouvelle instance de la classe Bone. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom. |

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
| getTransform() | Obtient ou définit la matrice de transformation du nœud contenant l'os. |

 **Result:**



---


### setTransform{#setTransform}

| Nom | Description |
| --- | --- |
| setTransform(value) | Obtient ou définit la matrice de transformation du nœud contenant l'os. |

 **Result:**



---


### getBoneTransform{#getBoneTransform}

| Nom | Description |
| --- | --- |
| getBoneTransform() | Obtient ou définit la matrice de transformation de l'os. |

 **Result:**



---


### setBoneTransform{#setBoneTransform}

| Nom | Description |
| --- | --- |
| setBoneTransform(value) | Obtient ou définit la matrice de transformation de l'os. |

 **Result:**



---


### getNode{#getNode}

| Nom | Description |
| --- | --- |
| getNode() | Obtient ou définit le nœud. Le bone node est l'os auquel la skin est attachée, le SkinDeformer utilisera le bone node pour influencer le déplacement des points de contrôle. Le bone node possède généralement un Skeleton attaché, mais ce n'est pas obligatoire. Le Skeleton attaché est généralement utilisé par les logiciels DCC pour afficher le squelette à l'utilisateur. |

 **Result:**



---


### setNode{#setNode}

| Nom | Description |
| --- | --- |
| setNode(value) | Obtient ou définit le nœud. Le bone node est l'os auquel la skin est attachée, le SkinDeformer utilisera le bone node pour influencer le déplacement des points de contrôle. Le bone node possède généralement un Skeleton attaché, mais ce n'est pas obligatoire. Le Skeleton attaché est généralement utilisé par les logiciels DCC pour afficher le squelette à l'utilisateur. |

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
| index | Nombre | Index du point de contrôle |

 **Result:**
Nombre


---


### setWeight{#setWeight}

| Nom | Description |
| --- | --- |
| setWeight(index, weight) | Définit le poids du point de contrôle spécifié par l'index |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| index | Nombre | Index du point de contrôle |
| poids | Nombre | Nouveau poids |

 **Result:**
Nombre


---


### removeProperty{#removeProperty}

| Nom | Description |
| --- | --- |
| removeProperty(property) | Supprime une propriété dynamique. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| property | Property | Quelle propriété supprimer |

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
| property | String | Nom de la propriété |

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
| property | String | Nom de la propriété |
| value | Object | La valeur de la propriété |

 **Result:**
Object


---


### findProperty{#findProperty}

| Nom | Description |
| --- | --- |
| findProperty(propertyName) | Recherche la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propertyName | String | Nom de la propriété. |

 **Result:**
Property


---



