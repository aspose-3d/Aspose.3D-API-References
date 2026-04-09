---
title: Quaternion
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/quaternion/
---
## Quaternion class

Le quaternion est généralement utilisé pour effectuer des rotations en infographie.


## Properties

| Nom | Description |
| --- | --- |
| w | Le composant w. |
| x | Le composant x. |
| y | Le composant y. |
| z | Le composant z. |
| IDENTITY | Le quaternion d'identité. |

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
| constructor_overload(w, x, y, z) | Initialise une nouvelle instance de la classe Quaternion. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| w | Number | composante w du quaternion |
| x | Number | composante x du quaternion |
| y | Number | composante y du quaternion |
| z | Number | composante z du quaternion |

 **Result:**



---


### getLength{#getLength}

| Nom | Description |
| --- | --- |
| getLength() | Obtient la longueur du quaternion |

 **Result:**



---


### equals{#equals}

| Nom | Description |
| --- | --- |
| equals(obj) | Vérifier si deux quaternions sont égaux |

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
| hashCode() | Obtient le code de hachage du Quaternion |

 **Result:**
Number


---


### conjugate{#conjugate}

| Nom | Description |
| --- | --- |
| conjugate() | Renvoie un quaternion conjugué du quaternion actuel |

 **Result:**
Quaternion


---


### inverse{#inverse}

| Nom | Description |
| --- | --- |
| inverse() | Renvoie un quaternion inverse du quaternion actuel |

 **Result:**
Quaternion


---


### dot{#dot}

| Nom | Description |
| --- | --- |
| dot(q) | Produit scalaire |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| q | Quaternion | Le quaternion |

 **Result:**
Number


---


### eulerAngles{#eulerAngles}

| Nom | Description |
| --- | --- |
| eulerAngles() | Convertit le quaternion en rotation représentée par des angles d'Euler. Tous les composants sont en radians. |

 **Result:**
Vector3


---


### normalize{#normalize}

| Nom | Description |
| --- | --- |
| normalize() | Normaliser le quaternion |

 **Result:**
Quaternion


---


### concat{#concat}

| Nom | Description |
| --- | --- |
| concat(rhs) | Concaténer deux quaternions |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| rh | Quaternion | null |

 **Result:**
Quaternion


---


### fromAngleAxis{#fromAngleAxis}

| Nom | Description |
| --- | --- |
| fromAngleAxis(a, axis) | Crée un quaternion autour d'un axe donné et le fait pivoter dans le sens horaire |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| a | Number | Rotation horaire en radian |
| axe | Vector3 | Axe |

 **Result:**
Quaternion


---


### fromRotation{#fromRotation}

| Nom | Description |
| --- | --- |
| fromRotation(orig, dest) | Crée un quaternion qui tourne de la direction originale à la direction de destination |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| orig | Vector3 | Direction d'origine |
| dest | Vector3 | Direction de destination |

 **Result:**
Quaternion


---


### fromEulerAngle{#fromEulerAngle}

| Nom | Description |
| --- | --- |
| fromEulerAngle(pitch, yaw, roll) | Crée un quaternion à partir d'un angle d'Euler donné |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| tangage | Number | Tangage en radian |
| lacet | Number | Lacet en radian |
| roulis | Number | Roulis en radian |

 **Result:**
Quaternion


---


### fromEulerAngle{#fromEulerAngle}

| Nom | Description |
| --- | --- |
| fromEulerAngle(eulerAngle) | Crée un quaternion à partir d'un angle d'Euler donné |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| eulerAngle | Vector3 | Angle d'Euler en radian |

 **Result:**
Quaternion


---


### toMatrix{#toMatrix}

| Nom | Description |
| --- | --- |
| toMatrix() | Convertir la rotation présentée par le quaternion en matrice de transformation. |

 **Result:**
Matrix4


---


### toString{#toString}

| Nom | Description |
| --- | --- |
| toString() | Obtient la représentation du quaternion sous forme de chaîne |

 **Result:**
String


---


### interpolate{#interpolate}

| Nom | Description |
| --- | --- |
| interpolate(t, from, to) | Remplit ce quaternion avec la valeur interpolée entre les arguments quaternion fournis pour un t compris entre le point de départ et le point d'arrivée. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| t | Number | Le coefficient à interpoler. |
| from | Quaternion | Quaternion source. |
| to | Quaternion | Quaternion cible. |

 **Result:**
Quaternion


---



