---
title: "MorphTargetChannel"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/morphtargetchannel/
---
## MorphTargetChannel class

يُستخدم MorphTargetChannel بواسطة MorphTargetDeformer لتنظيم الهندسات الهدفية. بعض صيغ الملفات مثل FBX تدعم قنوات متعددة بالتوازي. الوزن يتراوح بين 0 و 1.0، والوزن الافتراضي للهدف هو 0.0؛


## الخصائص

| الاسم | الوصف |
| --- | --- |
| DEFAULT_WEIGHT | الوزن الافتراضي للهدف المتحول. |

## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor(name) | ينشئ مثيلاً جديداً من فئة MorphTargetChannel. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | الاسم. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload() | ينشئ مثيلاً جديداً من فئة MorphTargetChannel. |

 **Result:**



---


### getWeights{#getWeights}

| الاسم | الوصف |
| --- | --- |
| getWeights() | يحصل على قيم الوزن الكاملة لأشكال الهدف. الأوزان الكاملة. |

 **Result:**



---


### getChannelWeight{#getChannelWeight}

| الاسم | الوصف |
| --- | --- |
| getChannelWeight() | يحصل أو يضبط وزن المُشَكِّل لهذا القناة. الوزن بين 0.0 و 1.0 |

 **Result:**



---


### setChannelWeight{#setChannelWeight}

| الاسم | الوصف |
| --- | --- |
| setChannelWeight(value) | يحصل أو يضبط وزن المُشَكِّل لهذا القناة. الوزن بين 0.0 و 1.0 |

 **Result:**



---


### getTargets{#getTargets}

| الاسم | الوصف |
| --- | --- |
| getTargets() | يحصل على جميع الأهداف المرتبطة بالقناة. |

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


### get{#get}

| الاسم | الوصف |
| --- | --- |
| get(target) |  |

 **Result:**



---


### set{#set}

| الاسم | الوصف |
| --- | --- |
| set(target, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| الاسم | الوصف |
| --- | --- |
| getWeight(target) | يحصل على الوزن للهدف المحدد، إذا كان الهدف لا ينتمي إلى هذه القناة، يتم إرجاع القيمة الافتراضية 0. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| الهدف | شكل | null |

 **Result:**
Number


---


### setWeight{#setWeight}

| الاسم | الوصف |
| --- | --- |
| setWeight(target, weight) | يضبط الوزن للهدف المحدد، القيمة الافتراضية هي 1، يجب أن يكون النطاق بين 0~1. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| الهدف | شكل | null |
| وزن | Number | null |

 **Result:**
Number


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



