---
title: BoundingBox2D
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/boundingbox2d/
---
## BoundingBox2D class

La boîte englobante alignée sur les axes pour Vector2


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
| minimum | Vector2 | Le coin minimum |
| maximum | Vector2 | Le coin maximum |

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


### merge{#merge}

| Nom | Description |
| --- | --- |
| merge(pt) | Fusionne la nouvelle boîte dans la boîte englobante actuelle. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| p | Vector2 | null |

 **Result:**



---


### merge{#merge}

| Nom | Description |
| --- | --- |
| merge(bb) | Fusionne la nouvelle boîte dans la boîte englobante actuelle. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| b | BoundingBox2D | null |

 **Result:**



---


### toString{#toString}

| Nom | Description |
| --- | --- |
| toString() | Obtient la représentation sous forme de chaîne de la boîte englobante. |

 **Result:**
String


---



