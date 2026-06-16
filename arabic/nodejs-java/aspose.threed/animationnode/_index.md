---
title: "AnimationNode"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/animationnode/
---
## AnimationNode class

يدعم Aspose.3D هيكلية الرسوم المتحركة، حيث يمكن تكوين كل رسم متحرك من عدة رسوم متحركة وتعريف الإطار المفتاحي للرسوم المتحركة. يحدد AnimationNode تحويل قيمة الخاصية مع مرور الوقت، على سبيل المثال، يمكن استخدام عقدة الرسوم المتحركة للتحكم في تحويل عقدة أو الخصائص العددية لكائنات A3DObject الأخرى.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor(name) | ينشئ مثيلاً جديداً من الفئة AnimationNode. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | الاسم |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload() | ينشئ مثيلاً جديداً من الفئة AnimationNode. |

 **Result:**



---


### getBindPoints{#getBindPoints}

| الاسم | الوصف |
| --- | --- |
| getBindPoints() | يحصل على نقاط ربط الخاصية الحالية |

 **Result:**



---


### getSubAnimations{#getSubAnimations}

| الاسم | الوصف |
| --- | --- |
| getSubAnimations() | يحصل على عقد الرسوم المتحركة الفرعية تحت الرسوم المتحركة الحالية. |

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


### findBindPoint{#findBindPoint}

| الاسم | الوصف |
| --- | --- |
| findBindPoint(name) | يبحث عن نقطة الربط بالاسم. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | اسم نقطة الربط للبحث عنها. |

 **Result:**
BindPoint


---


### getBindPoint{#getBindPoint}

| الاسم | الوصف |
| --- | --- |
| getBindPoint(target, propName, create) | يحصل على نقطة ربط الرسوم المتحركة في الخاصية المحددة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| target | A3DObject | على أي كائن يتم إنشاء نقطة الربط. |
| propName | String | اسم الخاصية. |
| إنشاء | boolean | إذا تم تعيينه إلى |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| الاسم | الوصف |
| --- | --- |
| getKeyframeSequence(target, propName, channelName, create) | يحصل على تسلسل الإطارات المفتاحية في الخاصية والقناة المحددة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| target | A3DObject | على أي نسخة يتم إنشاء تسلسل الإطارات المفتاحية. |
| propName | String | اسم الخاصية. |
| channelName | String | اسم القناة. |
| إنشاء | boolean | إذا تم تعيينه إلى |

 **Result:**
KeyframeSequence


---


### getKeyframeSequence{#getKeyframeSequence}

| الاسم | الوصف |
| --- | --- |
| getKeyframeSequence(target, propName, create) | يحصل على تسلسل الإطارات المفتاحية في الخاصية المحددة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| target | A3DObject | على أي نسخة يتم إنشاء تسلسل الإطارات المفتاحية. |
| propName | String | اسم الخاصية. |
| إنشاء | boolean | إذا تم تعيينه إلى |

 **Result:**
KeyframeSequence


---


### createBindPoint{#createBindPoint}

| الاسم | الوصف |
| --- | --- |
| createBindPoint(obj, propName) | ينشئ BindPoint بناءً على نوع بيانات الخاصية. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| obj | A3DObject | كائن. |
| propName | String | اسم الخاصية. |

 **Result:**
BindPoint


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



