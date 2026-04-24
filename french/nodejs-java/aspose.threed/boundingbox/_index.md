---
title: BoundingBox
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/boundingbox/
---
## BoundingBox class

La boîte englobante alignée sur les axes


## Properties

| Nom | Description |
| --- | --- |
| NULL | La boîte englobante nulle |
| INFINITE | La boîte englobante infinie |

## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(minimum, maximum) | Initialiser une boîte englobante finie avec les coins minimum et maximum donnés |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| minimum | Vector3 | Le coin minimum |
| maximum | Vector3 | Le coin maximum |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nom | Description |
| --- | --- |
| constructor_overload2(minX, minY, minZ, maxX, maxY, maxZ) | Initialiser une boîte englobante finie avec les coins minimum et maximum donnés |

 **Result:**



---


### getExtent{#getExtent}

| Nom | Description |
| --- | --- |
| getExtent() | Obtient l'étendue de la boîte englobante. La valeur de la propriété est la constante entière BoundingBoxExtent. |

 **Result:**



---


### getMinimum{#getMinimum}

| Nom | Description |
| --- | --- |
| getMinimum() | Le coin minimum de la boîte englobante |

 **Result:**



---


### getMaximum{#getMaximum}

| Nom | Description |
| --- | --- |
| getMaximum() | Le coin maximum de la boîte englobante |

 **Result:**



---


### getSize{#getSize}

| Nom | Description |
| --- | --- |
| getSize() | La taille du boîtier englobant |

 **Result:**



---


### getCenter{#getCenter}

| Nom | Description |
| --- | --- |
| getCenter() | Le centre du boîtier englobant. |

 **Result:**



---


### fromGeometry{#fromGeometry}

| Nom | Description |
| --- | --- |
| fromGeometry(geometry) | Construire un boîtier englobant à partir de la géométrie donnée |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| géométrie | Geometry | null |

 **Result:**
BoundingBox


---


### toString{#toString}

| Nom | Description |
| --- | --- |
| toString() | Obtient la représentation sous forme de chaîne de la boîte englobante. |

 **Result:**
String


---


### hashCode{#hashCode}

| Nom | Description |
| --- | --- |
| hashCode() | Renvoie le code de hachage pour cette instance |

 **Result:**
Number


---


### equals{#equals}

| Nom | Description |
| --- | --- |
| equals(obj) | Détermine si deux objets sont égaux |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| ob | Object | null |

 **Result:**
boolean


---



