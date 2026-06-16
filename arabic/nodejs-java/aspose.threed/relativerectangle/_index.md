---
title: "RelativeRectangle"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/relativerectangle/
---
## RelativeRectangle class

مستطيل نسبي  الصيغة بين المكوّن النسبي والقيمة المطلقة هي:  المقياس  (عرض المرجع) + الإزاحة  لذا إذا أردنا تمثيله كقيمة مطلقة، اترك جميع حقول المقياس صفرًا، واستخدم حقول الإزاحة بدلاً من ذلك.


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
| constructor_overload(left, top, width, height) | إنشاء RelativeRectangle |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| يسار | Number | null |
| to | Number | null |
| widt | Number | null |
| heigh | Number | null |

 **Result:**



---


### getScaleX{#getScaleX}

| الاسم | الوصف |
| --- | --- |
| getScaleX() | الإحداثي النسبي X |

 **Result:**



---


### setScaleX{#setScaleX}

| الاسم | الوصف |
| --- | --- |
| setScaleX(value) | الإحداثي النسبي X |

 **Result:**



---


### getScaleY{#getScaleY}

| الاسم | الوصف |
| --- | --- |
| getScaleY() | الإحداثي النسبي Y |

 **Result:**



---


### setScaleY{#setScaleY}

| الاسم | الوصف |
| --- | --- |
| setScaleY(value) | الإحداثي النسبي Y |

 **Result:**



---


### getScaleWidth{#getScaleWidth}

| الاسم | الوصف |
| --- | --- |
| getScaleWidth() | العرض النسبي |

 **Result:**



---


### setScaleWidth{#setScaleWidth}

| الاسم | الوصف |
| --- | --- |
| setScaleWidth(value) | العرض النسبي |

 **Result:**



---


### getScaleHeight{#getScaleHeight}

| الاسم | الوصف |
| --- | --- |
| getScaleHeight() | الارتفاع النسبي |

 **Result:**



---


### setScaleHeight{#setScaleHeight}

| الاسم | الوصف |
| --- | --- |
| setScaleHeight(value) | الارتفاع النسبي |

 **Result:**



---


### getOffsetX{#getOffsetX}

| الاسم | الوصف |
| --- | --- |
| getOffsetX() | يحصل أو يضبط الإزاحة للإحداثي X |

 **Result:**



---


### setOffsetX{#setOffsetX}

| الاسم | الوصف |
| --- | --- |
| setOffsetX(value) | يحصل أو يضبط الإزاحة للإحداثي X |

 **Result:**



---


### getOffsetY{#getOffsetY}

| الاسم | الوصف |
| --- | --- |
| getOffsetY() | يحصل أو يضبط الإزاحة للإحداثي Y |

 **Result:**



---


### setOffsetY{#setOffsetY}

| الاسم | الوصف |
| --- | --- |
| setOffsetY(value) | يحصل أو يضبط الإزاحة للإحداثي Y |

 **Result:**



---


### getOffsetWidth{#getOffsetWidth}

| الاسم | الوصف |
| --- | --- |
| getOffsetWidth() | يحصل أو يضبط الإزاحة للعرض |

 **Result:**



---


### setOffsetWidth{#setOffsetWidth}

| الاسم | الوصف |
| --- | --- |
| setOffsetWidth(value) | يحصل أو يضبط الإزاحة للعرض |

 **Result:**



---


### getOffsetHeight{#getOffsetHeight}

| الاسم | الوصف |
| --- | --- |
| getOffsetHeight() | يحصل أو يضبط الإزاحة للارتفاع |

 **Result:**



---


### setOffsetHeight{#setOffsetHeight}

| الاسم | الوصف |
| --- | --- |
| setOffsetHeight(value) | يحصل أو يضبط الإزاحة للارتفاع |

 **Result:**



---


### toAbsolute{#toAbsolute}

| الاسم | الوصف |
| --- | --- |
| toAbsolute(left, top, width, height) | تحويل المستطيل النسبي إلى مستطيل مطلق |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| اليسار | Number | الجانب الأيسر للمستطيل |
| الأعلى | Number | الجزء العلوي من المستطيل |
| width | Number | عرض المستطيل |
| height | Number | ارتفاع المستطيل |

 **Result:**
Rect


---


### fromScale{#fromScale}

| الاسم | الوصف |
| --- | --- |
| fromScale(scaleX, scaleY, scaleWidth, scaleHeight) | إنشاء RelativeRectangle مع جميع حقول الإزاحة صفر وحقول المقياس من المعلمات المعطاة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| تحجيم | Number | null |
| تحجيم | Number | null |
| scaleWidt | Number | null |
| scaleHeigh | Number | null |

 **Result:**
RelativeRectangle


---


### toString{#toString}

| الاسم | الوصف |
| --- | --- |
| toString() | يقوم بتحويل قيمة هذا الكائن إلى java.lang.String. |

 **Result:**
RelativeRectangle


---



