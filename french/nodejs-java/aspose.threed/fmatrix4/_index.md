---
title: FMatrix4
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/fmatrix4/
---
## FMatrix4 class

Matrice 4x4 avec tous les composants de type flottant


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
| IDENTITY | La matrice identité |

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
| constructor_overload(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Initialiser l'instance de FMatrix4 |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| m0 | Number | null |
| m0 | Number | null |
| m0 | Number | null |
| m0 | Number | null |
| m1 | Number | null |
| m1 | Number | null |
| m1 | Number | null |
| m1 | Number | null |
| m2 | Number | null |
| m2 | Number | null |
| m2 | Number | null |
| m2 | Number | null |
| m3 | Number | null |
| m3 | Number | null |
| m3 | Number | null |
| m3 | Number | null |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nom | Description |
| --- | --- |
| constructor_overload2(mat) | Initialiser l'instance de FMatrix4 à partir d'une instance de Matrix4. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| ma | Matrix4 | null |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nom | Description |
| --- | --- |
| constructor_overload3(r0, r1, r2, r3) | Construit la matrice à partir de 4 lignes. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| r0 | FVector4 | R0. |
| r1 | FVector4 | R1. |
| r2 | FVector4 | R2. |
| r3 | FVector4 | R3. |

 **Result:**



---


### concatenate{#concatenate}

| Nom | Description |
| --- | --- |
| concatenate(m2) | Concatène les deux matrices |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| m2 | FMatrix4 | M2. |

 **Result:**
FMatrix4


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
FMatrix4


---


### transpose{#transpose}

| Nom | Description |
| --- | --- |
| transpose() | Transpose cette instance. |

 **Result:**
FMatrix4


---


### inverse{#inverse}

| Nom | Description |
| --- | --- |
| inverse() | Calcule la matrice inverse de l'instance actuelle. |

 **Result:**
FMatrix4


---



