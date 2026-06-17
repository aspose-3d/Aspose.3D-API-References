---
title: "FMatrix4"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/fmatrix4/
---
## FMatrix4 class

4x4-matris med alla komponenter i flyttalstyp


## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| m00 | m00‑värdet. |
| m01 | m01‑värdet. |
| m02 | m02‑värdet. |
| m03 | m03‑värdet. |
| m10 | m10‑värdet. |
| m11 | m11‑värdet. |
| m12 | Den m12. |
| m13 | Den m13. |
| m20 | Den m20. |
| m21 | Den m21. |
| m22 | Den m22. |
| m23 | Den m23. |
| m30 | Den m30. |
| m31 | Den m31. |
| m32 | Den m32. |
| m33 | Den m33. |
| IDENTITY | Identitetsmatrisen |

## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Initiera instansen av FMatrix4 |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| m0 | Nummer | null |
| m0 | Nummer | null |
| m0 | Nummer | null |
| m0 | Nummer | null |
| m1 | Nummer | null |
| m1 | Nummer | null |
| m1 | Nummer | null |
| m1 | Nummer | null |
| m2 | Nummer | null |
| m2 | Nummer | null |
| m2 | Nummer | null |
| m2 | Nummer | null |
| m3 | Nummer | null |
| m3 | Nummer | null |
| m3 | Nummer | null |
| m3 | Nummer | null |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload2(mat) | Initiera instansen av FMatrix4 från en Matrix4-instans. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| ma | Matrix4 | null |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload3(r0, r1, r2, r3) | Skapar en matris från 4 rader. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| r0 | FVector4 | R0. |
| r1 | FVector4 | R1. |
| r2 | FVector4 | R2. |
| r3 | FVector4 | R3. |

 **Result:**



---


### concatenate{#concatenate}

| Namn | Beskrivning |
| --- | --- |
| concatenate(m2) | Konkatenar de två matriserna |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| m2 | FMatrix4 | M2. |

 **Result:**
FMatrix4


---


### concatenate{#concatenate}

| Namn | Beskrivning |
| --- | --- |
| concatenate(m2) | Konkatenar de två matriserna |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

 **Result:**
FMatrix4


---


### transpose{#transpose}

| Namn | Beskrivning |
| --- | --- |
| transpose() | Transponerar den här instansen. |

 **Result:**
FMatrix4


---


### inverse{#inverse}

| Namn | Beskrivning |
| --- | --- |
| inverse() | Beräkna den inversa matrisen för den aktuella instansen. |

 **Result:**
FMatrix4


---



