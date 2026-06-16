---
title: "FMatrix4"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/fmatrix4/
---
## FMatrix4 class

Matrice 4x4 con tutti i componenti di tipo float


## Proprietà

| Nome | Descrizione |
| --- | --- |
| m00 | Il m00. |
| m01 | Il m01. |
| m02 | Il m02. |
| m03 | Il m03. |
| m10 | Il m10. |
| m11 | Il m11. |
| m12 | Il m12. |
| m13 | Il m13. |
| m20 | Il m20. |
| m21 | Il m21. |
| m22 | Il m22. |
| m23 | Il m23. |
| m30 | Il m30. |
| m31 | Il m31. |
| m32 | Il m32. |
| m33 | Il m33. |
| IDENTITY | La matrice identità |

## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Inizializza l'istanza di FMatrix4 |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| m0 | Numero | null |
| m0 | Numero | null |
| m0 | Numero | null |
| m0 | Numero | null |
| m1 | Numero | null |
| m1 | Numero | null |
| m1 | Numero | null |
| m1 | Numero | null |
| m2 | Numero | null |
| m2 | Numero | null |
| m2 | Numero | null |
| m2 | Numero | null |
| m3 | Numero | null |
| m3 | Numero | null |
| m3 | Numero | null |
| m3 | Numero | null |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nome | Descrizione |
| --- | --- |
| constructor_overload2(mat) | Inizializza l'istanza di FMatrix4 da un'istanza di Matrix4. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| ma | Matrix4 | null |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nome | Descrizione |
| --- | --- |
| constructor_overload3(r0, r1, r2, r3) | Costruisce la matrice da 4 righe. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| r0 | FVector4 | R0. |
| r1 | FVector4 | R1. |
| r2 | FVector4 | R2. |
| r3 | FVector4 | R3. |

 **Result:**



---


### concatenate{#concatenate}

| Nome | Descrizione |
| --- | --- |
| concatenate(m2) | Concatena le due matrici |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| m2 | FMatrix4 | M2. |

 **Result:**
FMatrix4


---


### concatenate{#concatenate}

| Nome | Descrizione |
| --- | --- |
| concatenate(m2) | Concatena le due matrici |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

 **Result:**
FMatrix4


---


### transpose{#transpose}

| Nome | Descrizione |
| --- | --- |
| transpose() | Trasponi questa istanza. |

 **Result:**
FMatrix4


---


### inverse{#inverse}

| Nome | Descrizione |
| --- | --- |
| inverse() | Calcola la matrice inversa dell'istanza corrente. |

 **Result:**
FMatrix4


---



