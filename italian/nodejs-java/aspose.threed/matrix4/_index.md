---
title: "Matrix4"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/matrix4/
---
## Matrix4 class

Implementazione di matrice 4x4.


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
| constructor_overload(r0, r1, r2, r3) | Costruisce la matrice da 4 righe. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| r0 | Vector4 | R0. |
| r1 | Vector4 | R1. |
| r2 | Vector4 | R2. |
| r3 | Vector4 | R3. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nome | Descrizione |
| --- | --- |
| constructor_overload2(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Inizializza una nuova istanza della struct Matrix4. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| m00 | Numero | M00. |
| m01 | Numero | M01. |
| m02 | Numero | M02. |
| m03 | Numero | M03. |
| m10 | Numero | M10. |
| m11 | Numero | M11. |
| m12 | Numero | M12. |
| m13 | Numero | M13. |
| m20 | Numero | M20. |
| m21 | Numero | M21. |
| m22 | Numero | M22. |
| m23 | Numero | M23. |
| m30 | Numero | M30. |
| m31 | Numero | M31. |
| m32 | Numero | M32. |
| m33 | Numero | M33. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nome | Descrizione |
| --- | --- |
| constructor_overload3(m) | Costruisci Matrix4 da un'istanza di FMatrix4 |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
|  | FMatrix4 | null |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| Nome | Descrizione |
| --- | --- |
| constructor_overload4(m) | Inizializza una nuova istanza della struct Matrix4. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| m | Number[] | M. |

 **Result:**



---


### getIdentity{#getIdentity}

| Nome | Descrizione |
| --- | --- |
| getIdentity() | Restituisce la matrice identità. L'identità. |

 **Result:**



---


### getDeterminant{#getDeterminant}

| Nome | Descrizione |
| --- | --- |
| getDeterminant() | Restituisce il determinante della matrice. Il determinante. |

 **Result:**



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
Matrix4


---


### transpose{#transpose}

| Nome | Descrizione |
| --- | --- |
| transpose() | Trasponi questa istanza. |

 **Result:**
Matrix4


---


### normalize{#normalize}

| Nome | Descrizione |
| --- | --- |
| normalize() | Normalizza questa istanza. |

 **Result:**
Matrix4


---


### inverse{#inverse}

| Nome | Descrizione |
| --- | --- |
| inverse() | Inverte questa istanza. |

 **Result:**
Matrix4


---


### setTRS{#setTRS}

| Nome | Descrizione |
| --- | --- |
| setTRS(translation, rotation, scale) | Inizializza la matrice con traslazione/rotazione/scalatura |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| traslazione | Vector3 | Traslazione. |
| rotazione | Vector3 | Angoli di Eulero per la rotazione, i campi sono in gradi. |
| scala | Vector3 | Scala. |

 **Result:**
Matrix4


---


### toArray{#toArray}

| Nome | Descrizione |
| --- | --- |
| toArray() | Converte la matrice in un array. |

 **Result:**
Number[]


---


### toString{#toString}

| Nome | Descrizione |
| --- | --- |
| toString() | Restituisce una java.lang.String che rappresenta l'attuale Matrix4. |

 **Result:**
Stringa


---


### translate{#translate}

| Nome | Descrizione |
| --- | --- |
| translate(t) | Crea una matrice che trasla lungo l'asse x, l'asse y e l'asse z |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| t | Vector3 | Offset di traslazione |

 **Result:**
Matrix4


---


### translate{#translate}

| Nome | Descrizione |
| --- | --- |
| translate(tx, ty, tz) | Crea una matrice che trasla lungo l'asse x, l'asse y e l'asse z |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| tx | Numero | Offset della coordinata X |
| ty | Numero | Offset della coordinata Y |
| tz | Numero | Offset della coordinata Z |

 **Result:**
Matrix4


---


### scale{#scale}

| Nome | Descrizione |
| --- | --- |
| scale(s) | Crea una matrice che scala lungo l'asse x, l'asse y e l'asse z. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| s | Vector3 | Scaling factories si applicano all'asse x, all'asse y e all'asse z |

 **Result:**
Matrix4


---


### scale{#scale}

| Nome | Descrizione |
| --- | --- |
| scale(s) | Crea una matrice che scala lungo l'asse x, l'asse y e l'asse z. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| s | Numero | Scaling factories si applicano a tutti gli assi |

 **Result:**
Matrix4


---


### scale{#scale}

| Nome | Descrizione |
| --- | --- |
| scale(sx, sy, sz) | Crea una matrice che scala lungo l'asse x, l'asse y e l'asse z. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| sx | Numero | Scaling factories si applicano all'asse x |
| sy | Numero | Scaling factories si applicano all'asse y |
| sz | Numero | Scaling factories si applicano all'asse z |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| Nome | Descrizione |
| --- | --- |
| rotateFromEuler(eul) | Crea una matrice di rotazione da un angolo di Eulero |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| eul | Vector3 | Rotazione in radianti |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| Nome | Descrizione |
| --- | --- |
| rotateFromEuler(rx, ry, rz) | Crea una matrice di rotazione da un angolo di Eulero |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| rx | Numero | Rotazione sull'asse x in radianti |
| ry | Numero | Rotazione sull'asse y in radianti |
| rz | Numero | Rotazione sull'asse z in radianti |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Nome | Descrizione |
| --- | --- |
| rotate(angle, axis) | Crea una matrice di rotazione mediante l'angolo di rotazione e l'asse |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| angolo | Numero | Angolo di rotazione in radianti |
| asse | Vector3 | Asse di rotazione |

 **Result:**
Matrix4


---


### rotate{#rotate}

| Nome | Descrizione |
| --- | --- |
| rotate(q) | Crea una matrice di rotazione da un quaternione |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| q | Quaternione | Quaternione di rotazione |

 **Result:**
Matrix4


---



