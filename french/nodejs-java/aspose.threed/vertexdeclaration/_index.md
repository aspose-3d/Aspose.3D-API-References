---
title: VertexDeclaration
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/vertexdeclaration/
---
## VertexDeclaration class

La déclaration de la structure d'un sommet défini sur mesure


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getSealed{#getSealed}

| Nom | Description |
| --- | --- |
| getSealed() | Une VertexDeclaration sera scellée lorsqu'elle a été utilisée par com.aspose.threed.TriMesh`1 ou TriMesh, aucune modification supplémentaire n'est autorisée. |

 **Result:**



---


### getCount{#getCount}

| Nom | Description |
| --- | --- |
| getCount() | Obtient le nombre de tous les champs définis dans cette VertexDeclaration. |

 **Result:**



---


### getSize{#getSize}

| Nom | Description |
| --- | --- |
| getSize() | La taille en octets de la structure de sommet. |

 **Result:**



---


### get{#get}

| Nom | Description |
| --- | --- |
| get(index) |  |

 **Result:**



---


### clear{#clear}

| Nom | Description |
| --- | --- |
| clear() | Effacer tous les champs. |

 **Result:**



---


### addField{#addField}

| Nom | Description |
| --- | --- |
| addField(dataType, semantic, index, alias) | Ajouter un nouveau champ de sommet |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| dataType | Number | VertexFieldDataType |
| semantic | VertexFieldSemantic | VertexFieldSemantic |
| indice | Number | L'index pour la même sémantique de champ, -1 pour la génération automatique |
| alias | String | Le nom d'alias du champ |

 **Result:**



---


### fromGeometry{#fromGeometry}

| Nom | Description |
| --- | --- |
| fromGeometry(geometry, useFloat) | Crée une VertexDeclaration basée sur la disposition d'une Geometry. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| géométrie | Geometry | null |
| useFloat | boolean | Utilisez float au lieu du type double |

 **Result:**
VertexDeclaration


---


### compareTo{#compareTo}

| Nom | Description |
| --- | --- |
| compareTo(other) | Compare cette instance à un objet spécifié et renvoie une indication de leurs valeurs relatives. |

 **Result:**
VertexDeclaration


---


### toString{#toString}

| Nom | Description |
| --- | --- |
| toString() |  |

 **Result:**
String


---


### hashCode{#hashCode}

| Nom | Description |
| --- | --- |
| hashCode() |  |

 **Result:**
Number


---


### equals{#equals}

| Nom | Description |
| --- | --- |
| equals(obj) | Détermine si cette instance et un objet spécifié, qui doit également être un objet VertexDeclaration, ont la même valeur. |

 **Result:**
Number


---


### iterator{#iterator}

| Nom | Description |
| --- | --- |
| iterator() | Réservé à un usage interne. |

 **Result:**
Number


---



