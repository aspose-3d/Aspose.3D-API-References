---
title: "Bone"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/bone/
---
## Bone class

يحدد العظم (bone) مجموعة فرعية من نقاط التحكم في الهندسة، ويحدد وزن الدمج لكل نقطة تحكم. لا يمكن استخدام كائن Bone مباشرةً، يتم استخدام مثيل SkinDeformer لتشويه الهندسة، ويأتي SkinDeformer مع مجموعة من العظام، كل عظم مرتبط بعقدة. ملاحظة: يمكن ربط نقطة تحكم في الهندسة بأكثر من عظم واحد.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor(name) | ينشئ مثيلاً جديداً من الفئة Bone. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | الاسم. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload() | ينشئ مثيلاً جديداً من الفئة Bone. |

 **Result:**



---


### getWeightCount{#getWeightCount}

| الاسم | الوصف |
| --- | --- |
| getWeightCount() | يحصل على عدد الأوزان، يتم توسيعه تلقائيًا بواسطة setWeight(int, double) |

 **Result:**



---


### getTransform{#getTransform}

| الاسم | الوصف |
| --- | --- |
| getTransform() | يحصل أو يضبط مصفوفة التحويل للعقدة التي تحتوي على bone. |

 **Result:**



---


### setTransform{#setTransform}

| الاسم | الوصف |
| --- | --- |
| setTransform(value) | يحصل أو يضبط مصفوفة التحويل للعقدة التي تحتوي على bone. |

 **Result:**



---


### getBoneTransform{#getBoneTransform}

| الاسم | الوصف |
| --- | --- |
| getBoneTransform() | يحصل أو يضبط مصفوفة التحويل للـ bone. |

 **Result:**



---


### setBoneTransform{#setBoneTransform}

| الاسم | الوصف |
| --- | --- |
| setBoneTransform(value) | يحصل أو يضبط مصفوفة التحويل للـ bone. |

 **Result:**



---


### getNode{#getNode}

| الاسم | الوصف |
| --- | --- |
| getNode() | يحصل أو يضبط الـ node. الـ bone node هو الـ bone الذي يتم إرفاق الـ skin به، سيستخدم الـ SkinDeformer الـ bone node للتأثير على إزاحة نقاط التحكم. عادةً ما يكون للـ bone node Skeleton مرفق، لكنه ليس مطلوبًا. عادةً ما يُستخدم الـ Skeleton المرفق بواسطة برامج DCC لعرض الـ skeleton للمستخدم. |

 **Result:**



---


### setNode{#setNode}

| الاسم | الوصف |
| --- | --- |
| setNode(value) | يحصل أو يضبط الـ node. الـ bone node هو الـ bone الذي يتم إرفاق الـ skin به، سيستخدم الـ SkinDeformer الـ bone node للتأثير على إزاحة نقاط التحكم. عادةً ما يكون للـ bone node Skeleton مرفق، لكنه ليس مطلوبًا. عادةً ما يُستخدم الـ Skeleton المرفق بواسطة برامج DCC لعرض الـ skeleton للمستخدم. |

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
| get(index) |  |

 **Result:**



---


### set{#set}

| الاسم | الوصف |
| --- | --- |
| set(index, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| الاسم | الوصف |
| --- | --- |
| getWeight(index) | يحصل على الوزن لنقطة التحكم المحددة بالـ index |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| الفهرس | Number | فهرس نقطة التحكم |

 **Result:**
Number


---


### setWeight{#setWeight}

| الاسم | الوصف |
| --- | --- |
| setWeight(index, weight) | يضبط الوزن لنقطة التحكم المحددة بالـ index |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| الفهرس | Number | فهرس نقطة التحكم |
| الوزن | Number | وزن جديد |

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



