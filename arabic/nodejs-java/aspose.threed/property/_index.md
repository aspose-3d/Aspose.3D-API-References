---
title: "خاصية"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/property/
---
## Property class

فئة لحفظ الخصائص المعرفة من قبل المستخدم.  @hideconstructor


## الطرق

### getValue{#getValue}

| الاسم | الوصف |
| --- | --- |
| getValue() | يحصل أو يضبط القيمة. القيمة. |

 **Result:**



---


### setValue{#setValue}

| الاسم | الوصف |
| --- | --- |
| setValue(value) | يحصل أو يضبط القيمة. القيمة. |

 **Result:**



---


### setName{#setName}

| الاسم | الوصف |
| --- | --- |
| setName(value) |  |

 **Result:**



---


### getValueType{#getValueType}

| الاسم | الوصف |
| --- | --- |
| getValueType() | يحصل على نوع قيمة الخاصية. نوع القيمة. |

 **Result:**



---


### getProperties{#getProperties}

| الاسم | الوصف |
| --- | --- |
| getProperties() | يحصل على مجموعة جميع الخصائص. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| الاسم | الوصف |
| --- | --- |
| getBindPoint(anim, create) | يحصل على نقطة ربط الخاصية في نسخة الرسوم المتحركة المحددة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| anim | AnimationNode | على أي رسوم متحركة لإنشاء نقطة الربط. |
| إنشاء | boolean | إنشاء نقطة ربط الخاصية إذا لم يتم العثور عليها. |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| الاسم | الوصف |
| --- | --- |
| getKeyframeSequence(anim, create) | يحصل على تسلسل الإطارات المفتاحية في نسخة الرسوم المتحركة المحددة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| anim | AnimationNode | على أي رسوم متحركة لإنشاء تسلسل الإطارات المفتاحية. |
| إنشاء | boolean | إنشاء تسلسل الإطارات المفتاحية إذا لم يتم العثور عليه. |

 **Result:**
KeyframeSequence


---


### toString{#toString}

| الاسم | الوصف |
| --- | --- |
| toString() | يرجع سلسلة تمثل الخاصية الحالية. |

 **Result:**
String


---


### removeProperty{#removeProperty}

| الاسم | الوصف |
| --- | --- |
| removeProperty(property) | يزيل خاصية ديناميكية. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| خاصية | خاصية | أي خاصية لإزالتها |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| الاسم | الوصف |
| --- | --- |
| removeProperty(property) | إزالة الخاصية المحددة بالاسم |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| خاصية | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| الاسم | الوصف |
| --- | --- |
| getProperty(property) | احصل على قيمة الخاصية المحددة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| خاصية | String | اسم الخاصية |

 **Result:**
Object


---


### setProperty{#setProperty}

| الاسم | الوصف |
| --- | --- |
| setProperty(property, value) | يضبط قيمة الخاصية المحددة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| خاصية | String | اسم الخاصية |
| القيمة | Object | قيمة الخاصية |

 **Result:**
Object


---


### findProperty{#findProperty}

| الاسم | الوصف |
| --- | --- |
| findProperty(propertyName) | يبحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (تم إنشاؤها بواسطة CreateDynamicProperty/SetProperty) أو خاصية أصلية (تم التعرف عليها باسمها) |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| propertyName | String | اسم الخاصية. |

 **Result:**
خاصية


---



