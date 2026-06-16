---
title: "Matrix4"
second_title: "Référence d'API Aspose.3D pour Node.js via Java"
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/matrix4/
---
## Matrix4 class

Implémentation d’une matrice 4x4.


## Propriétés

| Nom | Description |
| --- | --- |
| m00 | Le m00. |
| m01 | Le m01. |
| m02 | Le m02. |
| m03 | Le m03. |
| m10 | Le m10. |
| m11 | Le m11. |
| m12 | Le m12. |
| m13 | Le m13. |
| m20 | Le m20. |
| m21 | Le m21. |
| m22 | Le m22. |
| m23 | Le m23. |
| m30 | Le m30. |
| m31 | Le m31. |
| m32 | Le m32. |
| m33 | Le m33. |

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
| constructor_overload(r0, r1, r2, r3) | Construit la matrice à partir de 4 lignes. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| r0 | Vector4 | R0. |
| r1 | Vector4 | R1. |
| r2 | Vector4 | R2. |
| r3 | Vector4 | R3. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nom | Description |
| --- | --- |
| constructor_overload2(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Initialise une nouvelle instance de la structure Matrix4. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| m00 | Nombre | M00. |
| m01 | Nombre | M01. |
| m02 | Nombre | M02. |
| m03 | Nombre | M03. |
| m10 | Nombre | M10. |
| m11 | Nombre | M11. |
| m12 | Nombre | M12. |
| m13 | Nombre | M13. |
| m20 | Nombre | M20. |
| m21 | Nombre | M21. |
| m22 | Nombre | M22. |
| m23 | Nombre | M23. |
| m30 | Nombre | M30. |
| m31 | Nombre | M31. |
| m32 | Nombre | M32. |
| m33 | Nombre | M33. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nom | Description |
| --- | --- |
| constructor_overload3(m) | Construit Matrix4 à partir d'une instance FMatrix4 |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
|  | FMatrix4 | null |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Nom | Description |
| --- | --- |
| constructor_overload4(m) | Initialise une nouvelle instance de la structure Matrix4. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| m | Number[] | M. |

 **Result:**



---


### getIdentity{#getIdentity}

| Nom | Description |
| --- | --- |
| getIdentity() | Obtient la matrice identité. L'identité. |

 **Result:**



---


### getDeterminant{#getDeterminant}

| Nom | Description |
| --- | --- |
| getDeterminant() | Obtient le déterminant de la matrice. Le déterminant. |

 **Result:**



---


### concatenate{#concatenate}

| Nom | Description |
| --- | --- |
| concatenate(m2) | Concatène les deux matrices |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

 **Result:**
Matrix4


---


### transpose{#transpose}

| Nom | Description |
| --- | --- |
| transpose() | Transpose cette instance. |

 **Result:**
Matrix4


---


### normalize{#normalize}

| Nom | Description |
| --- | --- |
| normalize() | Normalise cette instance. |

 **Result:**
Matrix4


---


### inverse{#inverse}

| Nom | Description |
| --- | --- |
| inverse() | Inverse cette instance. |

 **Result:**
Matrix4


---


### setTRS{#setTRS}

| Nom | Description |
| --- | --- |
| setTRS(translation, rotation, scale) | Initialise la matrice avec translation/rotation/scale |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| translation | Vector3 | Translation. |
| rotation | Vector3 | Angles d'Euler pour la rotation, les champs sont en degrés. |
| scale | Vector3 | Scale. |

 **Result:**
Matrix4


---


### toArray{#toArray}

| Nom | Description |
| --- | --- |
| toArray() | Convertit la matrice en tableau. |

 **Result:**
Number[]


---


### toString{#toString}

| Nom | Description |
| --- | --- |
| toString() | Renvoie un java.lang.String qui représente le Matrix4 actuel. |

 **Result:**
String


---


### translate{#translate}

| Nom | Description |
| --- | --- |
| translate(t) | Crée une matrice qui translate le long de l'axe x, de l'axe y et de l'axe z |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| t | Vector3 | Décalage de translation |

 **Result:**
Matrix4


---


### translate{#translate}

| Nom | Description |
| --- | --- |
| translate(tx, ty, tz) | Crée une matrice qui translate le long de l'axe x, de l'axe y et de l'axe z |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| tx | Nombre | Décalage de la coordonnée X |
| ty | Nombre | Décalage de la coordonnée Y |
| tz | Nombre | Décalage de la coordonnée Z |

 **Result:**
Matrix4


---


### scale{#scale}

| Nom | Description |
| --- | --- |
| scale(s) | Crée une matrice qui met à l'échelle le long de l'axe x, de l'axe y et de l'axe z. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| s | Vector3 | Les usines de mise à l'échelle s'appliquent à l'axe x, à l'axe y et à l'axe z |

 **Result:**
Matrix4


---


### scale{#scale}

| Nom | Description |
| --- | --- |
| scale(s) | Crée une matrice qui met à l'échelle le long de l'axe x, de l'axe y et de l'axe z. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| s | Nombre | Les usines de mise à l'échelle s'appliquent à tous les axes |

 **Result:**
Matrix4


---


### scale{#scale}

| Nom | Description |
| --- | --- |
| scale(sx, sy, sz) | Crée une matrice qui met à l'échelle le long de l'axe x, de l'axe y et de l'axe z. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| sx | Nombre | Les usines de mise à l'échelle s'appliquent à l'axe x |
| sy | Nombre | Les usines de mise à l'échelle s'appliquent à l'axe y |
| sz | Nombre | Les usines de mise à l'échelle s'appliquent à l'axe z |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| Nom | Description |
| --- | --- |
| rotateFromEuler(eul) | Créer une matrice de rotation à partir d'un angle d'Euler |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| eul | Vector3 | Rotation en radians |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| Nom | Description |
| --- | --- |
| rotateFromEuler(rx, ry, rz) | Créer une matrice de rotation à partir d'un angle d'Euler |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| rx | Nombre | Rotation sur l'axe x en radians |
| ry | Nombre | Rotation sur l'axe y en radians |
| rz | Nombre | Rotation autour de l'axe z en radian |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Nom | Description |
| --- | --- |
| rotate(angle, axis) | Créer une matrice de rotation à partir de l'angle de rotation et de l'axe |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| angle | Nombre | Angle de rotation en radian |
| axe | Vector3 | Axe de rotation |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Nom | Description |
| --- | --- |
| rotate(q) | Créer une matrice de rotation à partir d'un quaternion |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| q | Quaternion | Quaternion de rotation |

 **Result:**
Matrix4


---



