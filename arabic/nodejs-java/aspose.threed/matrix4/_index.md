---
title: "Matrix4"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/matrix4/
---
## Matrix4 class

تنفيذ مصفوفة 4×4.


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
| constructor_overload(r0, r1, r2, r3) | يبني المصفوفة من 4 صفوف. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| r0 | Vector4 | R0. |
| r1 | Vector4 | R1. |
| r2 | Vector4 | R2. |
| r3 | Vector4 | R3. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| الاسم | الوصف |
| --- | --- |
| constructor_overload2(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33) | يُهيئ نسخة جديدة من بنية Matrix4. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| m00 | Number | M00. |
| m01 | Number | M01. |
| m02 | Number | M02. |
| m03 | Number | M03. |
| m10 | Number | M10. |
| m11 | Number | M11. |
| m12 | Number | M12. |
| m13 | Number | M13. |
| m20 | Number | M20. |
| m21 | Number | M21. |
| m22 | Number | M22. |
| m23 | Number | M23. |
| m30 | Number | M30. |
| m31 | Number | M31. |
| m32 | Number | M32. |
| m33 | Number | M33. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| الاسم | الوصف |
| --- | --- |
| constructor_overload3(m) | إنشاء Matrix4 من نسخة FMatrix4. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
|  | FMatrix4 | null |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| الاسم | الوصف |
| --- | --- |
| constructor_overload4(m) | يُهيئ نسخة جديدة من بنية Matrix4. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| m | Number[] | M. |

 **Result:**



---


### getIdentity{#getIdentity}

| الاسم | الوصف |
| --- | --- |
| getIdentity() | يسترجع مصفوفة الهوية. الهوية. |

 **Result:**



---


### getDeterminant{#getDeterminant}

| الاسم | الوصف |
| --- | --- |
| getDeterminant() | يسترجع محدد المصفوفة. المحدد. |

 **Result:**



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
Matrix4


---


### transpose{#transpose}

| الاسم | الوصف |
| --- | --- |
| transpose() | يعكس هذا الكائن. |

 **Result:**
Matrix4


---


### normalize{#normalize}

| الاسم | الوصف |
| --- | --- |
| normalize() | يقوم بتطبيع هذه الحالة. |

 **Result:**
Matrix4


---


### inverse{#inverse}

| الاسم | الوصف |
| --- | --- |
| inverse() | يعكس هذا الكائن. |

 **Result:**
Matrix4


---


### setTRS{#setTRS}

| الاسم | الوصف |
| --- | --- |
| setTRS(translation, rotation, scale) | يُهيئ المصفوفة بالترجمة/الدوران/التحجيم |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| ترجمة | Vector3 | ترجمة. |
| دوران | Vector3 | زوايا أويلر للدوران، الحقول بوحدة الدرجة. |
| تحجيم | Vector3 | تحجيم. |

 **Result:**
Matrix4


---


### toArray{#toArray}

| الاسم | الوصف |
| --- | --- |
| toArray() | يحول المصفوفة إلى مصفوفة. |

 **Result:**
Number[]


---


### toString{#toString}

| الاسم | الوصف |
| --- | --- |
| toString() | يرجع java.lang.String الذي يمثل الـ Matrix4 الحالي. |

 **Result:**
String


---


### translate{#translate}

| الاسم | الوصف |
| --- | --- |
| translate(t) | ينشئ مصفوفة تُترجم على طول المحور x، والمحور y، والمحور z |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| t | Vector3 | إزاحة الترجمة |

 **Result:**
Matrix4


---


### translate{#translate}

| الاسم | الوصف |
| --- | --- |
| translate(tx, ty, tz) | ينشئ مصفوفة تُترجم على طول المحور x، والمحور y، والمحور z |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| tx | Number | إزاحة إحداثي X |
| ty | Number | إزاحة إحداثي Y |
| tz | Number | إزاحة إحداثي Z |

 **Result:**
Matrix4


---


### scale{#scale}

| الاسم | الوصف |
| --- | --- |
| scale(s) | ينشئ مصفوفة تقوم بالتحجيم على طول المحور x، والمحور y، والمحور z. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| s | Vector3 | تنطبق مصانع التحجيم على المحور x، والمحور y، والمحور z |

 **Result:**
Matrix4


---


### scale{#scale}

| الاسم | الوصف |
| --- | --- |
| scale(s) | ينشئ مصفوفة تقوم بالتحجيم على طول المحور x، والمحور y، والمحور z. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| s | Number | تنطبق مصانع التحجيم على جميع المحاور |

 **Result:**
Matrix4


---


### scale{#scale}

| الاسم | الوصف |
| --- | --- |
| scale(sx, sy, sz) | ينشئ مصفوفة تقوم بالتحجيم على طول المحور x، والمحور y، والمحور z. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| sx | Number | تنطبق مصانع التحجيم على المحور x |
| sy | Number | تنطبق مصانع التحجيم على المحور y |
| sz | Number | تنطبق مصانع التحجيم على المحور z |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| الاسم | الوصف |
| --- | --- |
| rotateFromEuler(eul) | إنشاء مصفوفة دوران من زاوية أويلر |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| eul | Vector3 | الدوران بالراديان |

 **Result:**
Matrix4


---


### rotateFromEuler{#rotateFromEuler}

| الاسم | الوصف |
| --- | --- |
| rotateFromEuler(rx, ry, rz) | إنشاء مصفوفة دوران من زاوية أويلر |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| rx | Number | الدوران حول المحور x بالراديان |
| ry | Number | الدوران حول المحور y بالراديان |
| rz | Number | دوران حول المحور z بالراديان |

 **Result:**
Matrix4


---


### rotate{#rotate}

| الاسم | الوصف |
| --- | --- |
| rotate(angle, axis) | إنشاء مصفوفة دوران باستخدام زاوية الدوران والمحور |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| زاوية | Number | زاوية الدوران بالراديان |
| محور | Vector3 | محور الدوران |

 **Result:**
Matrix4


---


### rotate{#rotate}

| الاسم | الوصف |
| --- | --- |
| rotate(q) | إنشاء مصفوفة دوران من كواترنيون |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| q | كواترنيون | كواترنيون الدوران |

 **Result:**
Matrix4


---



