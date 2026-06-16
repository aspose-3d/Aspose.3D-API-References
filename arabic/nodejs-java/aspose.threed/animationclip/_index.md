---
title: "AnimationClip"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/animationclip/
---
## AnimationClip class

مقطع الرسوم المتحركة هو مجموعة من الرسوم المتحركة. يمكن للمشهد أن يحتوي على مقطع رسوم متحركة واحد أو أكثر.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor() | يُنشئ مثيلاً جديدًا من الفئة AnimationClip. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload(name) | يُنشئ مثيلاً جديدًا من الفئة AnimationClip. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | الاسم |

 **Result:**



---


### getAnimations{#getAnimations}

| الاسم | الوصف |
| --- | --- |
| getAnimations() | يحصل على الرسوم المتحركة الموجودة داخل المقطع. الطبقات. |

 **Result:**



---


### getDescription{#getDescription}

| الاسم | الوصف |
| --- | --- |
| getDescription() | يحصل أو يضبط وصف هذا المقطع المتحرك |

 **Result:**



---


### setDescription{#setDescription}

| الاسم | الوصف |
| --- | --- |
| setDescription(value) | يحصل أو يضبط وصف هذا المقطع المتحرك |

 **Result:**



---


### getStart{#getStart}

| الاسم | الوصف |
| --- | --- |
| getStart() | يحصل أو يضبط الوقت بالثواني لبداية المقطع. |

 **Result:**



---


### setStart{#setStart}

| الاسم | الوصف |
| --- | --- |
| setStart(value) | يحصل أو يضبط الوقت بالثواني لبداية المقطع. |

 **Result:**



---


### getStop{#getStop}

| الاسم | الوصف |
| --- | --- |
| getStop() | يحصل أو يضبط الوقت بالثواني لنهاية المقطع. |

 **Result:**



---


### setStop{#setStop}

| الاسم | الوصف |
| --- | --- |
| setStop(value) | يحصل أو يضبط الوقت بالثواني لنهاية المقطع. |

 **Result:**



---


### getScene{#getScene}

| الاسم | الوصف |
| --- | --- |
| getScene() | يحصل على المشهد الذي ينتمي إليه هذا الكائن |

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


### createAnimationNode{#createAnimationNode}

| الاسم | الوصف |
| --- | --- |
| createAnimationNode(nodeName) | دالة مختصرة لإنشاء وتسجيل عقدة الرسوم المتحركة على المقطع الحالي. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| nodeName | String | اسم عقدة الرسوم المتحركة الجديدة |

 **Result:**
AnimationNode


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



