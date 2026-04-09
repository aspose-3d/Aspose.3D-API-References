---
title: Vector3
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/vector3/
---
## Vector3 class

Un vecteur à trois composantes.


## Properties

| Nom | Description |
| --- | --- |
| x | Le composant x. |
| y | Le composant y. |
| z | Le composant z. |
| ORIGIN | Gets the origin position. The origin. |
| UNIT_SCALE | Gets the unit scale vector. |
| X_AXIS | Gets the X axis. The X axis. |
| Y_AXIS | Gets the Y axis. The Y axis. |
| Z_AXIS | Gets the Z axis. The Z axis. |

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
| constructor_overload(x, y, z) | Initializes a new instance of the Vector3 struct. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| x | Number | La coordonnée x. |
| y | Number | La coordonnée y. |
| z | Number | La coordonnée z. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nom | Description |
| --- | --- |
| constructor_overload2(vec) | Initializes a new instance of the Vector3 struct. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| vec | FVector3 | La coordonnée x. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nom | Description |
| --- | --- |
| constructor_overload3(v) | Initializes a new instance of the Vector3 struct. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| v | Number | V. |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Nom | Description |
| --- | --- |
| constructor_overload4(vec4) | Initializes a new instance of the Vector3 struct. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| vec4 | Vector4 | Vec4. |

 **Result:**



---


### getLength2{#getLength2}

| Nom | Description |
| --- | --- |
| getLength2() | Obtient le carré de la longueur. La longueur2. |

 **Result:**



---


### getLength{#getLength}

| Nom | Description |
| --- | --- |
| getLength() | Obtient la longueur de ce vecteur. La longueur. |

 **Result:**



---


### equals{#equals}

| Nom | Description |
| --- | --- |
| equals(obj) | Vérifie si deux vector3 sont égaux. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| obj | Object | L'objet à vérifier l'égalité. |

 **Result:**
boolean


---


### hashCode{#hashCode}

| Nom | Description |
| --- | --- |
| hashCode() | Obtient le code de hachage de Vector3. |

 **Result:**
Number


---


### dot{#dot}

| Nom | Description |
| --- | --- |
| dot(rhs) | Obtient le produit scalaire de deux vecteurs. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| rhs | Vector3 | Valeur du côté droit. |

 **Result:**
Number


---


### normalize{#normalize}

| Nom | Description |
| --- | --- |
| normalize() | Normalise cette instance. |

 **Result:**
Vector3


---


### sin{#sin}

| Nom | Description |
| --- | --- |
| sin() | Calcule le sinus de chaque composante |

 **Result:**
Vector3


---


### cos{#cos}

| Nom | Description |
| --- | --- |
| cos() | Calcule le cosinus sur chaque composant. |

 **Result:**
Vector3


---


### cross{#cross}

| Nom | Description |
| --- | --- |
| cross(rhs) | Produit vectoriel de deux vecteurs. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| rhs | Vector3 | Valeur du côté droit. |

 **Result:**
Vector3


---


### set{#set}

| Nom | Description |
| --- | --- |
| set(newX, newY, newZ) | Définit les composantes x/y/z en un seul appel. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| newX | Number | Le composant x. |
| newY | Number | Le composant y. |
| newZ | Number | Le composant z. |

 **Result:**
Vector3


---


### toString{#toString}

| Nom | Description |
| --- | --- |
| toString() | Renvoie un java.lang.String qui représente le Vector3 actuel. |

 **Result:**
String


---


### angleBetween{#angleBetween}

| Nom | Description |
| --- | --- |
| angleBetween(dir, up) | Calcule l'angle interne entre deux directions. Les deux directions peuvent être des vecteurs non normalisés. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| dir | Vector3 | Le vecteur direction à comparer avec |
| up | Vector3 | Le vecteur haut du plan partagé par les deux directions |

 **Result:**
Number


---


### angleBetween{#angleBetween}

| Nom | Description |
| --- | --- |
| angleBetween(dir) | Calcule l'angle interne entre deux directions. Les deux directions peuvent être des vecteurs non normalisés. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| dir | Vector3 | Le vecteur direction à comparer avec |

 **Result:**
Number


---


### compareTo{#compareTo}

| Nom | Description |
| --- | --- |
| compareTo(other) | Compare le vecteur actuel à une autre instance. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| othe | Vector3 | null |

 **Result:**
Number


---



