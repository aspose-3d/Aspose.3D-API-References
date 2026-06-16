---
title: "دائرة"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/circle/
---
## Circle class

يتكون منحنى الدائرة من مجموعة من النقاط على حافة الشكل الدائري.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor() | منشئ الدائرة |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload(radius) | منشئ الدائرة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| نصف القطر | Number | نصف قطر منحنى الدائرة. |

 **Result:**



---


### getRadius{#getRadius}

| الاسم | الوصف |
| --- | --- |
| getRadius() | نصف قطر منحنى الدائرة، القيمة الافتراضية هي 10 |

 **Result:**



---


### setRadius{#setRadius}

| الاسم | الوصف |
| --- | --- |
| setRadius(value) | نصف قطر منحنى الدائرة، القيمة الافتراضية هي 10 |

 **Result:**



---


### getColor{#getColor}

| الاسم | الوصف |
| --- | --- |
| getColor() | يحصل أو يضبط لون الخط، القيمة الافتراضية هي أبيض(1, 1, 1) |

 **Result:**



---


### setColor{#setColor}

| الاسم | الوصف |
| --- | --- |
| setColor(value) | يحصل أو يضبط لون الخط، القيمة الافتراضية هي أبيض(1, 1, 1) |

 **Result:**



---


### getParentNodes{#getParentNodes}

| الاسم | الوصف |
| --- | --- |
| getParentNodes() | يحصل على جميع العقد الأصلية، يمكن ربط كيان بعدة عقد أصلية لتكرار الهندسة. العقد. |

 **Result:**



---


### getExcluded{#getExcluded}

| الاسم | الوصف |
| --- | --- |
| getExcluded() | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |

 **Result:**



---


### setExcluded{#setExcluded}

| الاسم | الوصف |
| --- | --- |
| setExcluded(value) | يحصل أو يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |

 **Result:**



---


### getParentNode{#getParentNode}

| الاسم | الوصف |
| --- | --- |
| getParentNode() | يحصل أو يضبط العقدة الأصلية الأولى، إذا تم ضبط العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. العقدة الأصلية. |

 **Result:**



---


### setParentNode{#setParentNode}

| الاسم | الوصف |
| --- | --- |
| setParentNode(value) | يحصل أو يضبط العقدة الأصلية الأولى، إذا تم ضبط العقدة الأصلية الأولى، سيتم فصل هذا الكيان عن العقد الأصلية الأخرى. العقدة الأصلية. |

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


### getEntityRendererKey{#getEntityRendererKey}

| الاسم | الوصف |
| --- | --- |
| getEntityRendererKey() | يحصل على مفتاح مُعالج الكيان المسجل في المُعالج |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| الاسم | الوصف |
| --- | --- |
| getBoundingBox() | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |

 **Result:**
EntityRendererKey


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



