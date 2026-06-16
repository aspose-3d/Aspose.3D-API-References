---
title: "MorphTargetDeformer"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/morphtargetdeformer/
---
## MorphTargetDeformer class

MorphTargetDeformer يوفر تحريكًا لكل رأس. ينظم MorphTargetDeformer جميع الأهداف عبر MorphTargetChannel، ويمكن لكل قناة تنظيم أهداف متعددة. الاستخدام الشائع لمُحوّل الهدف التشكيلي هو تطبيق تعبيرات الوجه على شخصية. يمكن العثور على مزيد من التفاصيل في https://en.wikipedia.org/wiki/Morph_target_animation


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor(name) | ينشئ مثيلاً جديداً من الفئة MorphTargetDeformer. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | الاسم. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload() | ينشئ مثيلاً جديداً من الفئة MorphTargetDeformer. |

 **Result:**



---


### getChannels{#getChannels}

| الاسم | الوصف |
| --- | --- |
| getChannels() | يحصل على جميع القنوات الموجودة في هذا المُشَكِّل. |

 **Result:**



---


### getOwner{#getOwner}

| الاسم | الوصف |
| --- | --- |
| getOwner() | يحصل على الهندسة التي تملك هذا المشكِّل |

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



