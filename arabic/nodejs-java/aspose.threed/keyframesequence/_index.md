---
title: "KeyframeSequence"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/keyframesequence/
---
## KeyframeSequence class

تسلسل الإطارات الرئيسية، يصف تحويل القيمة المُعينة على مر الزمن.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor(name) | ينشئ مثيلًا جديدًا من فئة KeyframeSequence. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | الاسم |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload() | ينشئ مثيلًا جديدًا من فئة KeyframeSequence. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| الاسم | الوصف |
| --- | --- |
| getBindPoint() | يحصل على نقطة ربط الخاصية التي تملك هذا المنحنى |

 **Result:**



---


### getKeyFrames{#getKeyFrames}

| الاسم | الوصف |
| --- | --- |
| getKeyFrames() | يحصل على الإطارات المفتاحية لهذا المنحنى. المفاتيح. |

 **Result:**



---


### getPostBehavior{#getPostBehavior}

| الاسم | الوصف |
| --- | --- |
| getPostBehavior() | يحصل على السلوك اللاحق الذي يحدد ما يجب أن تكون القيمة المأخوذة بعد الإطار المفتاح الأخير. |

 **Result:**



---


### getPreBehavior{#getPreBehavior}

| الاسم | الوصف |
| --- | --- |
| getPreBehavior() | يحصل على السلوك السابق الذي يحدد ما يجب أن تكون القيمة المأخوذة قبل الإطار المفتاح الأول. |

 **Result:**



---


### getName{#getName}

| الاسم | الوصف |
| --- | --- |
| getName() | يحصل أو يضبط الاسم. الاسم. |

 **Result:**



---


### setName{#setName}

| الاسم | الوصف |
| --- | --- |
| setName(value) | يحصل أو يضبط الاسم. الاسم. |

 **Result:**



---


### getProperties{#getProperties}

| الاسم | الوصف |
| --- | --- |
| getProperties() | يحصل على مجموعة جميع الخصائص. |

 **Result:**



---


### add{#add}

| الاسم | الوصف |
| --- | --- |
| add(time, value) | إنشاء إطار مفتاح جديد بالقيمة المحددة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| الوقت | Number | موضع الوقت (مقاس بالثواني) |
| القيمة | Number | القيمة في موضع الوقت هذا |

 **Result:**



---


### add{#add}

| الاسم | الوصف |
| --- | --- |
| add(time, value, interpolation) | إنشاء إطار مفتاح جديد بالقيمة المحددة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| الوقت | Number | موضع الوقت (مقاس بالثواني) |
| القيمة | Number | القيمة في موضع الوقت هذا |
| الاستيفاء | الاستيفاء | الاستيفاء |

 **Result:**



---


### reset{#reset}

| الاسم | الوصف |
| --- | --- |
| reset() | يزيل جميع إطارات المفاتيح ويعيد ضبط سلوكيات post/pre. |

 **Result:**



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


### iterator{#iterator}

| الاسم | الوصف |
| --- | --- |
| iterator() | محجوز للاستخدام الداخلي. |

 **Result:**
خاصية


---



