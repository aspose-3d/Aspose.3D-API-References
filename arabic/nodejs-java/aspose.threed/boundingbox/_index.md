---
title: "BoundingBox"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/boundingbox/
---
## BoundingBox class

مربع الحد المحاذي للمحاور


## الخصائص

| الاسم | الوصف |
| --- | --- |
| NULL | صندوق الحدود الفارغ |
| INFINITE | صندوق الحدود اللانهائي |

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
| constructor_overload(minimum, maximum) | تهيئة صندوق حدود محدود بالزاويتين الأدنى والأعلى المحددتين |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| minimum | Vector3 | الزاوية الأدنى |
| maximum | Vector3 | الزاوية العليا |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| الاسم | الوصف |
| --- | --- |
| constructor_overload2(minX, minY, minZ, maxX, maxY, maxZ) | تهيئة صندوق حدود محدود بالزاويتين الأدنى والأعلى المحددتين |

 **Result:**



---


### getExtent{#getExtent}

| الاسم | الوصف |
| --- | --- |
| getExtent() | يحصل على مدى صندوق الحدود. قيمة الخاصية هي ثابت عدد صحيح BoundingBoxExtent. |

 **Result:**



---


### getMinimum{#getMinimum}

| الاسم | الوصف |
| --- | --- |
| getMinimum() | الزاوية الأدنى لصندوق الحدود |

 **Result:**



---


### getMaximum{#getMaximum}

| الاسم | الوصف |
| --- | --- |
| getMaximum() | الزاوية العليا لصندوق الحدود |

 **Result:**



---


### getSize{#getSize}

| الاسم | الوصف |
| --- | --- |
| getSize() | حجم صندوق الحدود |

 **Result:**



---


### getCenter{#getCenter}

| الاسم | الوصف |
| --- | --- |
| getCenter() | مركز صندوق الحدود. |

 **Result:**



---


### fromGeometry{#fromGeometry}

| الاسم | الوصف |
| --- | --- |
| fromGeometry(geometry) | إنشاء صندوق حدود من الهندسة المعطاة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| geometr | الهندسة | null |

 **Result:**
BoundingBox


---


### toString{#toString}

| الاسم | الوصف |
| --- | --- |
| toString() | يحصل على تمثيل السلسلة لمربع الإحاطة. |

 **Result:**
String


---


### hashCode{#hashCode}

| الاسم | الوصف |
| --- | --- |
| hashCode() | يعيد رمز التجزئة لهذا الكائن |

 **Result:**
Number


---


### equals{#equals}

| الاسم | الوصف |
| --- | --- |
| equals(obj) | يحدد ما إذا كان كائنان متساويان |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| ob | Object | null |

 **Result:**
boolean


---



