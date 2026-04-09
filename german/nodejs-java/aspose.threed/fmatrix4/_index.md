---
title: FMatrix4
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/fmatrix4/
---
## FMatrix4 class

4x4-Matrix mit allen Komponenten vom Typ float.


## Properties

| Name | Beschreibung |
| --- | --- |
| m00 | Das m00. |
| m01 | Das m01. |
| m02 | Das m02. |
| m03 | Das m03. |
| m10 | Das m10. |
| m11 | Das m11. |
| m12 | Das m12. |
| m13 | Das m13. |
| m20 | Das m20. |
| m21 | Das m21. |
| m22 | Das m22. |
| m23 | Das m23. |
| m30 | Das m30. |
| m31 | Das m31. |
| m32 | Das m32. |
| m33 | Das m33. |
| IDENTITY | Die Einheitsmatrix |

## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | Initialisiere die Instanz von FMatrix4 |

 **Parameters:**

| Name | Typ | Beschreibung |
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

| Name | Beschreibung |
| --- | --- |
| constructor_overload2(mat) | Initialisiere die Instanz von FMatrix4 aus einer Matrix4-Instanz. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| ma | Matrix4 | null |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Name | Beschreibung |
| --- | --- |
| constructor_overload3(r0, r1, r2, r3) | Konstruiert die Matrix aus 4 Zeilen. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| r0 | FVector4 | R0. |
| r1 | FVector4 | R1. |
| r2 | FVector4 | R2. |
| r3 | FVector4 | R3. |

 **Result:**



---


### concatenate{#concatenate}

| Name | Beschreibung |
| --- | --- |
| concatenate(m2) | Verkettet die beiden Matrizen |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| m2 | FMatrix4 | M2. |

 **Result:**
FMatrix4


---


### concatenate{#concatenate}

| Name | Beschreibung |
| --- | --- |
| concatenate(m2) | Verkettet die beiden Matrizen |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

 **Result:**
FMatrix4


---


### transpose{#transpose}

| Name | Beschreibung |
| --- | --- |
| transpose() | Transponiert diese Instanz. |

 **Result:**
FMatrix4


---


### inverse{#inverse}

| Name | Beschreibung |
| --- | --- |
| inverse() | Berechnet die Inversmatrix der aktuellen Instanz. |

 **Result:**
FMatrix4


---



