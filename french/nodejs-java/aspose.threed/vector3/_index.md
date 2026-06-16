---
title: "Vector3"
second_title: "Référence d'API Aspose.3D pour Node.js via Java"
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/vector3/
---
## Vector3 class

Un vecteur à trois composantes.


## Propriétés

| Nom | Description |
| --- | --- |
| x | Le composant x. |
| y | Le composant y. |
| z | Le composant z. |
| ORIGIN | Obtient la position d'origine. L'origine. |
| UNIT_SCALE | Obtient le vecteur d'échelle unité. |
| X_AXIS | Obtient l'axe X. L'axe X. |
| Y_AXIS | Obtient l'axe Y. L'axe Y. |
| Z_AXIS | Obtient l'axe Z. L'axe Z. |

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
| constructor_overload(x, y, z) | Initialise une nouvelle instance de la structure Vector3. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| x | Nombre | La coordonnée x. |
| y | Nombre | La coordonnée y. |
| z | Nombre | La coordonnée z. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nom | Description |
| --- | --- |
| constructor_overload2(vec) | Initialise une nouvelle instance de la structure Vector3. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| vec | FVector3 | La coordonnée x. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nom | Description |
| --- | --- |
| constructor_overload3(v) | Initialise une nouvelle instance de la structure Vector3. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| v | Nombre | V. |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Nom | Description |
| --- | --- |
| constructor_overload4(vec4) | Initialise une nouvelle instance de la structure Vector3. |

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
| equals(obj) | Vérifie si deux vector3 sont égaux |

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
| hashCode() | Obtient le code de hachage de Vector3 |

 **Result:**
Nombre


---


### dot{#dot}

| Nom | Description |
| --- | --- |
| dot(rhs) | Obtient le produit scalaire de deux vecteurs |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| rhs | Vector3 | Valeur du côté droit. |

 **Result:**
Nombre


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
| sin() | Calcule le sinus de chaque composant |

 **Result:**
Vector3


---


### cos{#cos}

| Nom | Description |
| --- | --- |
| cos() | Calcule le cosinus de chaque composant |

 **Result:**
Vector3


---


### cross{#cross}

| Nom | Description |
| --- | --- |
| cross(rhs) | Produit vectoriel de deux vecteurs |

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
| newX | Nombre | Le composant x. |
| newY | Nombre | Le composant y. |
| newZ | Nombre | Le composant z. |

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
| angleBetween(dir, up) | Calcule l'angle interne entre deux directions. Deux directions peuvent être des vecteurs non normalisés. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| dir | Vector3 | Le vecteur de direction à comparer avec |
| up | Vector3 | Le vecteur up du plan partagé des deux directions |

 **Result:**
Nombre


---


### angleBetween{#angleBetween}

| Nom | Description |
| --- | --- |
| angleBetween(dir) | Calcule l'angle interne entre deux directions. Deux directions peuvent être des vecteurs non normalisés. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| dir | Vector3 | Le vecteur de direction à comparer avec |

 **Result:**
Nombre


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
Nombre


---



