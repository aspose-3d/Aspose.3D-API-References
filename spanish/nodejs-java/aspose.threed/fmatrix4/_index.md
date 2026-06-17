---
title: "FMatrix4"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/fmatrix4/
---
## FMatrix4 class

Matriz 4x4 con todos los componentes en tipo flotante


## Propiedades

| Nombre | Descripción |
| --- | --- |
| m00 | El m00. |
| m01 | El m01. |
| m02 | El m02. |
| m03 | El m03. |
| m10 | El m10. |
| m11 | El m11. |
| m12 | El m12. |
| m13 | El m13. |
| m20 | El m20. |
| m21 | El m21. |
| m22 | El m22. |
| m23 | El m23. |
| m30 | El m30. |
| m31 | El m31. |
| m32 | El m32. |
| m33 | El m33. |
| IDENTITY | La matriz identidad |

## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Inicializar la instancia de FMatrix4 |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| m0 | Número | null |
| m0 | Número | null |
| m0 | Número | null |
| m0 | Número | null |
| m1 | Número | null |
| m1 | Número | null |
| m1 | Número | null |
| m1 | Número | null |
| m2 | Número | null |
| m2 | Número | null |
| m2 | Número | null |
| m2 | Número | null |
| m3 | Número | null |
| m3 | Número | null |
| m3 | Número | null |
| m3 | Número | null |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nombre | Descripción |
| --- | --- |
| constructor_overload2(mat) | Inicializa la instancia de FMatrix4 a partir de una instancia de Matrix4. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| ma | Matrix4 | null |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nombre | Descripción |
| --- | --- |
| constructor_overload3(r0, r1, r2, r3) | Construye la matriz a partir de 4 filas. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| r0 | FVector4 | R0. |
| r1 | FVector4 | R1. |
| r2 | FVector4 | R2. |
| r3 | FVector4 | R3. |

 **Result:**



---


### concatenate{#concatenate}

| Nombre | Descripción |
| --- | --- |
| concatenate(m2) | Concatena las dos matrices |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| m2 | FMatrix4 | M2. |

 **Result:**
FMatrix4


---


### concatenate{#concatenate}

| Nombre | Descripción |
| --- | --- |
| concatenate(m2) | Concatena las dos matrices |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

 **Result:**
FMatrix4


---


### transpose{#transpose}

| Nombre | Descripción |
| --- | --- |
| transpose() | Transpone esta instancia. |

 **Result:**
FMatrix4


---


### inverse{#inverse}

| Nombre | Descripción |
| --- | --- |
| inverse() | Calcula la matriz inversa de la instancia actual. |

 **Result:**
FMatrix4


---



