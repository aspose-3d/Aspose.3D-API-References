---
title: "FMatrix4"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/fmatrix4/
---
## FMatrix4 class

4x4-Matrix mit allen Komponenten im Fließkomma-Typ


## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| m00 | Der m00. |
| m01 | Der m01. |
| m02 | Der m02. |
| m03 | Der m03. |
| m10 | Der m10. |
| m11 | Der m11. |
| m12 | Der m12. |
| m13 | Der m13. |
| m20 | Die m20. |
| m21 | Die m21. |
| m22 | Die m22. |
| m23 | Die m23. |
| m30 | Die m30. |
| m31 | Die m31. |
| m32 | Die m32. |
| m33 | Die m33. |
| IDENTITY | Die Identitätsmatrix |

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
| m0 | Zahl | null |
| m0 | Zahl | null |
| m0 | Zahl | null |
| m0 | Zahl | null |
| m1 | Zahl | null |
| m1 | Zahl | null |
| m1 | Zahl | null |
| m1 | Zahl | null |
| m2 | Zahl | null |
| m2 | Zahl | null |
| m2 | Zahl | null |
| m2 | Zahl | null |
| m3 | Zahl | null |
| m3 | Zahl | null |
| m3 | Zahl | null |
| m3 | Zahl | null |

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
| constructor_overload3(r0, r1, r2, r3) | Konstruiert eine Matrix aus 4 Zeilen. |

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



