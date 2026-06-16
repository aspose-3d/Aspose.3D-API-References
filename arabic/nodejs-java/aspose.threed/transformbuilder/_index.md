---
title: "TransformBuilder"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/transformbuilder/
---
## TransformBuilder class

يُستخدم TransformBuilder لبناء مصفوفة التحويل عبر سلسلة من التحويلات.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor(initial, order) | أنشئ TransformBuilder بمصفوفة تحويل أولية وترتيب تجميع محدد |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| initia | Matrix4 | null |
| ترتيب | ComposeOrder | ComposeOrder |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload(order) | أنشئ TransformBuilder بمصفوفة تحويل هوية أولية وترتيب تجميع محدد |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| ترتيب | ComposeOrder | ComposeOrder |

 **Result:**



---


### getMatrix{#getMatrix}

| الاسم | الوصف |
| --- | --- |
| getMatrix() | يسترجع أو يضبط قيمة المصفوفة الحالية |

 **Result:**



---


### setMatrix{#setMatrix}

| الاسم | الوصف |
| --- | --- |
| setMatrix(value) | يسترجع أو يضبط قيمة المصفوفة الحالية |

 **Result:**



---


### getComposeOrder{#getComposeOrder}

| الاسم | الوصف |
| --- | --- |
| getComposeOrder() | يسترجع أو يضبط ترتيب تجميع السلسلة. قيمة الخاصية هي ثابت عدد صحيح ComposeOrder. |

 **Result:**



---


### setComposeOrder{#setComposeOrder}

| الاسم | الوصف |
| --- | --- |
| setComposeOrder(value) | يسترجع أو يضبط ترتيب تجميع السلسلة. قيمة الخاصية هي ثابت عدد صحيح ComposeOrder. |

 **Result:**



---


### compose{#compose}

| الاسم | الوصف |
| --- | --- |
| compose(m) | أضف أو أدرج الوسيط إلى المصفوفة الداخلية. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### append{#append}

| الاسم | الوصف |
| --- | --- |
| append(m) | أضف مصفوفة التحويل الجديدة إلى سلسلة التحويل. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### prepend{#prepend}

| الاسم | الوصف |
| --- | --- |
| prepend(m) | أضف مصفوفة التحويل الجديدة إلى سلسلة التحويل. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
|  | Matrix4 | null |

 **Result:**



---


### rearrange{#rearrange}

| الاسم | الوصف |
| --- | --- |
| rearrange(newX, newY, newZ) | أعد ترتيب تخطيط المحور. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| newX | محور | محور |
| newY | محور | محور |
| newZ | محور | محور |

 **Result:**



---


### scale{#scale}

| الاسم | الوصف |
| --- | --- |
| scale(s) | ربط مصفوفة تحويل قياس بمكوّن مُقاس بـ s |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
|  | Number | null |

 **Result:**



---


### scale{#scale}

| الاسم | الوصف |
| --- | --- |
| scale(x, y, z) | ربط مصفوفة تحويل قياس |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
|  | Number | null |
|  | Number | null |
|  | Number | null |

 **Result:**



---


### scale{#scale}

| الاسم | الوصف |
| --- | --- |
| scale(s) | ربط تحويل قياس |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### rotateDegree{#rotateDegree}

| الاسم | الوصف |
| --- | --- |
| rotateDegree(angle, axis) | ربط تحويل دوران بالدرجات |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| زاوية | Number | الزاوية للدوران بالدرجات |
| محور | Vector3 | المحور للدوران |

 **Result:**



---


### rotateRadian{#rotateRadian}

| الاسم | الوصف |
| --- | --- |
| rotateRadian(angle, axis) | ربط تحويل دوران بالراديان |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| زاوية | Number | الزاوية للدوران بالراديان |
| محور | Vector3 | المحور للدوران |

 **Result:**



---


### rotate{#rotate}

| الاسم | الوصف |
| --- | --- |
| rotate(q) | ربط دوران بواسطة رباعية |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
|  | كواترنيون | null |

 **Result:**



---


### rotateEulerDegree{#rotateEulerDegree}

| الاسم | الوصف |
| --- | --- |
| rotateEulerDegree(degX, degY, degZ) | ربط دوران بواسطة زوايا أويلر بالدرجات |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| deg | Number | null |
| deg | Number | null |
| deg | Number | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| الاسم | الوصف |
| --- | --- |
| rotateEulerRadian(x, y, z) | ربط دوران بواسطة زوايا أويلر بالراديان |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
|  | Number | null |
|  | Number | null |
|  | Number | null |

 **Result:**



---


### rotateEulerRadian{#rotateEulerRadian}

| الاسم | الوصف |
| --- | --- |
| rotateEulerRadian(r) | ربط دوران بواسطة زوايا أويلر بالراديان |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### translate{#translate}

| الاسم | الوصف |
| --- | --- |
| translate(tx, ty, tz) | ربط تحويل إزاحة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| t | Number | null |
| t | Number | null |
| t | Number | null |

 **Result:**



---


### translate{#translate}

| الاسم | الوصف |
| --- | --- |
| translate(v) | ربط تحويل إزاحة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
|  | Vector3 | null |

 **Result:**



---


### reset{#reset}

| الاسم | الوصف |
| --- | --- |
| reset() | إعادة تعيين التحويل إلى مصفوفة الهوية |

 **Result:**



---


### rotateDegree{#rotateDegree}

| الاسم | الوصف |
| --- | --- |
| rotateDegree(rot, order) | إضافة دوران بالترتيب المحدد |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| rot | Vector3 | الدوران بالدرجات |
| ترتيب | RotationOrder | RotationOrder |

 **Result:**



---


### rotateRadian{#rotateRadian}

| الاسم | الوصف |
| --- | --- |
| rotateRadian(rot, order) | إضافة دوران بالترتيب المحدد |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| rot | Vector3 | الدوران بالراديان |
| ترتيب | RotationOrder | RotationOrder |

 **Result:**



---



