---
title: "Pose"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/pose/
---
## Pose class

الوضعية تُستخدم لتخزين مصفوفة التحويل عندما يكون الشكل مكسوًا. الوضعية هي مجموعة من BonePose، كل BonePose يحفظ معلومات التحويل المحددة لعقدة العظم.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor(name) | ينشئ مثيلاً جديداً من الفئة Pose. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | الاسم |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload() | ينشئ مثيلاً جديداً من الفئة Pose. |

 **Result:**



---


### getPoseType{#getPoseType}

| الاسم | الوصف |
| --- | --- |
| getPoseType() | يحصل أو يعيّن نوع الوضع. قيمة الخاصية هي ثابت عدد صحيح PoseType. نوع الوضع. |

 **Result:**



---


### setPoseType{#setPoseType}

| الاسم | الوصف |
| --- | --- |
| setPoseType(value) | يحصل أو يعيّن نوع الوضع. قيمة الخاصية هي ثابت عدد صحيح PoseType. نوع الوضع. |

 **Result:**



---


### getBonePoses{#getBonePoses}

| الاسم | الوصف |
| --- | --- |
| getBonePoses() | يحصل على جميع BonePose. العقد. |

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


### addBonePose{#addBonePose}

| الاسم | الوصف |
| --- | --- |
| addBonePose(node, matrix, localMatrix) | يحفظ مصفوفة تحويل الوضع للعقدة العظمية المحددة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| عقدة | عقدة | عقدة العظم. |
| matrix | Matrix4 | مصفوفة التحويل. |
| localMatrix | boolean | إذا تم تعيينه إلى |

 **Result:**



---


### addBonePose{#addBonePose}

| الاسم | الوصف |
| --- | --- |
| addBonePose(node, matrix) | يحفظ مصفوفة تحويل الوضع للعظام المحددة. يتم افتراض مصفوفة التحويل العامة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| عقدة | عقدة | عقدة العظم. |
| matrix | Matrix4 | مصفوفة التحويل. |

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



