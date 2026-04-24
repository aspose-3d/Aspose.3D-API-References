---
title: Matrix4
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/matrix4/
---
## Matrix4 class

Implémentation de matrice 4x4.


## Properties

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
| m00 | Number | M00. |
| m01 | Number | M01. |
| m02 | Number | M02. |
| m03 | Number | M03. |
| m10 | Number | M10. |
| m11 | Number | M11. |
| m12 | Number | M12. |
| m13 | Number | M13. |
| m20 | Number | M20. |
| m21 | Number | M21. |
| m22 | Number | M22. |
| m23 | Number | M23. |
| m30 | Number | M30. |
| m31 | Number | M31. |
| m32 | Number | M32. |
| m33 | Number | M33. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nom | Description |
| --- | --- |
| constructor_overload3(m) | Construire Matrix4 à partir d'une instance FMatrix4 |

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
| getIdentity() | Renvoie la matrice identité. L'identité. |

 **Result:**



---


### getDeterminant{#getDeterminant}

| Nom | Description |
| --- | --- |
| getDeterminant() | Renvoie le déterminant de la matrice. Le déterminant. |

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
| setTRS(translation, rotation, scale) | Initialise la matrice avec translation/rotation/échelle |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| translation | Vector3 | Traduction. |
| rotation | Vector3 | Angles d'Euler pour la rotation, les champs sont en degrés. |
| scale | Vector3 | Échelle. |

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
| translate(t) | Crée une matrice qui translate le long des axes x, y et z |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| t | Vector3 | Translater le décalage |

 **Result:**
Matrix4


---


### translate{#translate}

| Nom | Description |
| --- | --- |
| translate(tx, ty, tz) | Crée une matrice qui translate le long des axes x, y et z |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| tx | Number | Décalage de la coordonnée X |
| ty | Number | Décalage de la coordonnée Y |
| tz | Number | Décalage de la coordonnée Z |

 **Result:**
Matrix4


---


### scale{#scale}

| Nom | Description |
| --- | --- |
| échelle(s) | Crée une matrice qui met à l'échelle le long des axes x, y et z. |

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
| échelle(s) | Crée une matrice qui met à l'échelle le long des axes x, y et z. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| s | Number | Les usines de mise à l'échelle s'appliquent à tous les axes |

 **Result:**
Matrix4


---


### scale{#scale}

| Nom | Description |
| --- | --- |
| échelle(sx, sy, sz) | Crée une matrice qui met à l'échelle le long des axes x, y et z. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| sx | Number | Les facteurs d'échelle s'appliquent à l'axe x |
| sy | Number | Les facteurs d'échelle s'appliquent à l'axe y |
| sz | Number | Les usines de mise à l'échelle s'appliquent à l'axe z |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| Nom | Description |
| --- | --- |
| rotateFromEuler(eul) | Crée une matrice de rotation à partir d'un angle d'Euler |

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
| rotateFromEuler(rx, ry, rz) | Crée une matrice de rotation à partir d'un angle d'Euler |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| rx | Number | Rotation autour de l'axe x en radian |
| ry | Number | Rotation autour de l'axe y en radian |
| rz | Number | Rotation autour de l'axe z en radians |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Nom | Description |
| --- | --- |
| rotate(angle, axis) | Crée une matrice de rotation à partir d'un angle de rotation et d'un axe |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| angle | Number | Angle de rotation en radians |
| axe | Vector3 | Axe de rotation |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Nom | Description |
| --- | --- |
| rotate(q) | Crée une matrice de rotation à partir d'un quaternion |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| q | Quaternion | Quaternion de rotation |

 **Result:**
Matrix4


---



