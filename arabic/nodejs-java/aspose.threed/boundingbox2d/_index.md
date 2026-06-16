---
title: "BoundingBox2D"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/boundingbox2d/
---
## BoundingBox2D class

مربع الحد المحاذي للمحاور لـ Vector2


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
| minimum | Vector2 | الزاوية الأدنى |
| maximum | Vector2 | الزاوية العليا |

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


### merge{#merge}

| الاسم | الوصف |
| --- | --- |
| merge(pt) | يدمج الصندوق الجديد في صندوق الحدود الحالي. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| p | Vector2 | null |

 **Result:**



---


### merge{#merge}

| الاسم | الوصف |
| --- | --- |
| merge(bb) | يدمج الصندوق الجديد في صندوق الحدود الحالي. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| b | BoundingBox2D | null |

 **Result:**



---


### toString{#toString}

| الاسم | الوصف |
| --- | --- |
| toString() | يحصل على تمثيل السلسلة لمربع الإحاطة. |

 **Result:**
String


---



