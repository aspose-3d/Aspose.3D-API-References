---
title: "FMatrix4"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/fmatrix4/
---
## FMatrix4 class

Tüm bileşenleri float tipinde olan 4x4 matris


## Özellikler

| Ad | Açıklama |
| --- | --- |
| m00 | m00. |
| m01 | m01. |
| m02 | m02. |
| m03 | Bu m03. |
| m10 | Bu m10. |
| m11 | Bu m11. |
| m12 | Bu m12. |
| m13 | Bu m13. |
| m20 | Bu m20. |
| m21 | Bu m21. |
| m22 | Bu m22. |
| m23 | Bu m23. |
| m30 | Bu m30. |
| m31 | Bu m31. |
| m32 | Bu m32. |
| m33 | Bu m33. |
| IDENTITY | Kimlik matrisi |

## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | FMatrix4 örneğini başlat |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| m0 | Sayı | null |
| m0 | Sayı | null |
| m0 | Sayı | null |
| m0 | Sayı | null |
| m1 | Sayı | null |
| m1 | Sayı | null |
| m1 | Sayı | null |
| m1 | Sayı | null |
| m2 | Sayı | null |
| m2 | Sayı | null |
| m2 | Sayı | null |
| m2 | Sayı | null |
| m3 | Sayı | null |
| m3 | Sayı | null |
| m3 | Sayı | null |
| m3 | Sayı | null |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Ad | Açıklama |
| --- | --- |
| constructor_overload2(mat) | FMatrix4 örneğini bir Matrix4 örneğinden başlat. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| ma | Matrix4 | null |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Ad | Açıklama |
| --- | --- |
| constructor_overload3(r0, r1, r2, r3) | Matrisi 4 satırdan oluşturur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| r0 | FVector4 | R0. |
| r1 | FVector4 | R1. |
| r2 | FVector4 | R2. |
| r3 | FVector4 | R3. |

 **Result:**



---


### concatenate{#concatenate}

| Ad | Açıklama |
| --- | --- |
| concatenate(m2) | İki matrisi birleştirir. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| m2 | FMatrix4 | M2. |

 **Result:**
FMatrix4


---


### concatenate{#concatenate}

| Ad | Açıklama |
| --- | --- |
| concatenate(m2) | İki matrisi birleştirir. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

 **Result:**
FMatrix4


---


### transpose{#transpose}

| Ad | Açıklama |
| --- | --- |
| transpose() | Bu örneği transpoze eder. |

 **Result:**
FMatrix4


---


### inverse{#inverse}

| Ad | Açıklama |
| --- | --- |
| inverse() | Mevcut örneğin ters matrisini hesaplar. |

 **Result:**
FMatrix4


---



