---
title: "FMatrix4"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/fmatrix4/
---
## FMatrix4 class

مصفوفة 4x4 مع جميع المكونات من نوع float


## الخصائص

| الاسم | الوصف |
| --- | --- |
| m00 | الـ m00. |
| m01 | الـ m01. |
| m02 | الـ m02. |
| m03 | الـ m03. |
| m10 | الـ m10. |
| m11 | الـ m11. |
| m12 | ال m12. |
| m13 | ال m13. |
| m20 | ال m20. |
| m21 | ال m21. |
| m22 | ال m22. |
| m23 | ال m23. |
| m30 | ال m30. |
| m31 | ال m31. |
| m32 | ال m32. |
| m33 | ال m33. |
| IDENTITY | مصفوفة الهوية |

## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor() |  |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | تهيئة مثيل FMatrix4 |

 **Parameters:**

| الاسم | النوع | الوصف |
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

| الاسم | الوصف |
| --- | --- |
| constructor_overload2(mat) | تهيئة نسخة من FMatrix4 من نسخة Matrix4. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| ma | Matrix4 | null |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| الاسم | الوصف |
| --- | --- |
| constructor_overload3(r0, r1, r2, r3) | يبني المصفوفة من 4 صفوف. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| r0 | FVector4 | R0. |
| r1 | FVector4 | R1. |
| r2 | FVector4 | R2. |
| r3 | FVector4 | R3. |

 **Result:**



---


### concatenate{#concatenate}

| الاسم | الوصف |
| --- | --- |
| concatenate(m2) | يجمع المصفوفتين |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| m2 | FMatrix4 | M2. |

 **Result:**
FMatrix4


---


### concatenate{#concatenate}

| الاسم | الوصف |
| --- | --- |
| concatenate(m2) | يجمع المصفوفتين |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| m2 | Matrix4 | M2. |

 **Result:**
FMatrix4


---


### transpose{#transpose}

| الاسم | الوصف |
| --- | --- |
| transpose() | يعكس هذا الكائن. |

 **Result:**
FMatrix4


---


### inverse{#inverse}

| الاسم | الوصف |
| --- | --- |
| inverse() | احسب مصفوفة العكس للنسخة الحالية. |

 **Result:**
FMatrix4


---



