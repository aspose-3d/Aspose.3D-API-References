---
title: TransformBuilder
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/transformbuilder/
---
## TransformBuilder class

Le TransformBuilder est utilisé pour construire une matrice de transformation à l'aide d'une chaîne de transformations.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor(initial, order) | Construit un TransformBuilder avec la matrice de transformation initiale et l'ordre de composition spécifié |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| initia | Matrix4 | null |
| ordre | ComposeOrder | ComposeOrder |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(order) | Construit un TransformBuilder avec la matrice de transformation identité initiale et l'ordre de composition spécifié |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| ordre | ComposeOrder | ComposeOrder |

 **Result:**



---


### getMatrix{#getMatrix}

| Nom | Description |
| --- | --- |
| getMatrix() | Obtient ou définit la valeur actuelle de la matrice |

 **Result:**



---


### setMatrix{#setMatrix}

| Nom | Description |
| --- | --- |
| setMatrix(value) | Obtient ou définit la valeur actuelle de la matrice |

 **Result:**



---


### getComposeOrder{#getComposeOrder}

| Nom | Description |
| --- | --- |
| getComposeOrder() | Obtient ou définit l'ordre de composition de la chaîne. La valeur de la propriété est la constante entière ComposeOrder. |

 **Result:**



---


### setComposeOrder{#setComposeOrder}

| Nom | Description |
| --- | --- |
| setComposeOrder(value) | Obtient ou définit l'ordre de composition de la chaîne. La valeur de la propriété est la constante entière ComposeOrder. |

 **Result:**



---


### compose{#compose}

| Nom | Description |
| --- | --- |
| compose(m) | Ajoute ou préfixe l'argument à la matrice interne. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### append{#append}

| Nom | Description |
| --- | --- |
| append(m) | Ajoute la nouvelle matrice de transformation à la chaîne de transformations. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### prepend{#prepend}

| Nom | Description |
| --- | --- |
| prepend(m) | Préfixe la nouvelle matrice de transformation à la chaîne de transformations. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### rearrange{#rearrange}

| Nom | Description |
| --- | --- |
| rearrange(newX, newY, newZ) | Réorganise la disposition des axes. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| newX | Axe | Axe |
| newY | Axe | Axe |
| newZ | Axe | Axe |

 **Result:**



---


### scale{#scale}

| Nom | Description |
| --- | --- |
| échelle(s) | Chaîner une matrice de transformation d'échelle avec un composant mis à l'échelle par s |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
|  | Number | null |

 **Result:**



---


### scale{#scale}

| Nom | Description |
| --- | --- |
| scale(x, y, z) | Chaîner une matrice de transformation d'échelle |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
|  | Number | null |
|  | Number | null |
|  | Number | null |

 **Result:**



---


### scale{#scale}

| Nom | Description |
| --- | --- |
| échelle(s) | Chaîner une transformation d'échelle |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### rotateDegree{#rotateDegree}

| Nom | Description |
| --- | --- |
| rotateDegree(angle, axis) | Enchaîner une transformation de rotation en degrés |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| angle | Number | L'angle à faire pivoter en degré |
| axe | Vector3 | L'axe à faire pivoter |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Nom | Description |
| --- | --- |
| rotateRadian(angle, axis) | Enchaîner une transformation de rotation en radians |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| angle | Number | L'angle à faire pivoter en radian |
| axe | Vector3 | L'axe à faire pivoter |

 **Result:**



---


### rotate{#rotate}

| Nom | Description |
| --- | --- |
| rotate(q) | Chaîner une rotation par un quaternion |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
|  | Quaternion | null |

 **Result:**



---


### rotateEulerDegree{#rotateEulerDegree}

| Nom | Description |
| --- | --- |
| rotateEulerDegree(degX, degY, degZ) | Chaîner une rotation par des angles d'Euler en degrés |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| deg | Number | null |
| deg | Number | null |
| deg | Number | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Nom | Description |
| --- | --- |
| rotateEulerRadian(x, y, z) | Chaîner une rotation par des angles d'Euler en radians |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
|  | Number | null |
|  | Number | null |
|  | Number | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| Nom | Description |
| --- | --- |
| rotateEulerRadian(r) | Chaîner une rotation par des angles d'Euler en radians |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### translate{#translate}

| Nom | Description |
| --- | --- |
| translate(tx, ty, tz) | Chaîner une transformation de translation |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| t | Number | null |
| t | Number | null |
| t | Number | null |

 **Result:**



---


### translate{#translate}

| Nom | Description |
| --- | --- |
| translate(v) | Chaîner une transformation de translation |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### reset{#reset}

| Nom | Description |
| --- | --- |
| reset() | Réinitialise la transformation à la matrice identité |

 **Result:**



---


### rotateDegree{#rotateDegree}

| Nom | Description |
| --- | --- |
| rotateDegree(rot, order) | Ajouter une rotation avec l'ordre spécifié |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| rot | Vector3 | Rotation en degrés |
| ordre | RotationOrder | RotationOrder |

 **Result:**



---


### rotateRadian{#rotateRadian}

| Nom | Description |
| --- | --- |
| rotateRadian(rot, order) | Ajouter une rotation avec l'ordre spécifié |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| rot | Vector3 | Rotation en radians |
| ordre | RotationOrder | RotationOrder |

 **Result:**



---



