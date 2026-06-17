---
title: "FMatrix4"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/fmatrix4/
---
## FMatrix4 class

Matrix 4x4 met alle componenten van het type float


## Properties

| Naam | Beschrijving |
| --- | --- |
| m00 | De m00. |
| m01 | De m01. |
| m02 | De m02. |
| m03 | De m03. |
| m10 | De m10. |
| m11 | De m11. |
| m12 | De m12. |
| m13 | De m13. |
| m20 | De m20. |
| m21 | De m21. |
| m22 | De m22. |
| m23 | De m23. |
| m30 | De m30. |
| m31 | De m31. |
| m32 | De m32. |
| m33 | De m33. |
| IDENTITY | De identiteitsmatrix |

## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Initialiseer de instantie van FMatrix4 |

 **Parameters:**

| Naam | Type | Beschrijving |
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

| Naam | Beschrijving |
| --- | --- |
| constructor_overload2(mat) | Initialiseer de instantie van FMatrix4 vanuit een Matrix4-instantie. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| ma | Matrix4 | null |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload3(r0, r1, r2, r3) | Construeert matrix uit 4 rijen. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| r0 | FVector4 | R0. |
| r1 | FVector4 | R1. |
| r2 | FVector4 | R2. |
| r3 | FVector4 | R3. |

 **Result:**



---


### concatenate{#concatenate}

| Naam | Beschrijving |
| --- | --- |
| concatenate(m2) | Concateneert de twee matrices. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| m2 | FMatrix4 | M2. |

 **Result:**
FMatrix4


---


### concatenate{#concatenate}

| Naam | Beschrijving |
| --- | --- |
| concatenate(m2) | Concateneert de twee matrices. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

 **Result:**
FMatrix4


---


### transpose{#transpose}

| Naam | Beschrijving |
| --- | --- |
| transpose() | Transponeert deze instantie. |

 **Result:**
FMatrix4


---


### inverse{#inverse}

| Naam | Beschrijving |
| --- | --- |
| inverse() | Bereken de inverse matrix van de huidige instantie. |

 **Result:**
FMatrix4


---



