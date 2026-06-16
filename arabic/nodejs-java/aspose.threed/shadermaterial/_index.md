---
title: "ShaderMaterial"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/shadermaterial/
---
## ShaderMaterial class

مادة المُظلل تسمح بوصف المادة بواسطة محرك عرض خارجي أو لغة المُظلل. يستخدم ShaderMaterial تقنية ShaderTechnique لوصف تفاصيل العرض المحددة، وسيتم اختيار الأنسب وفقًا لمنصة العرض النهائية. على سبيل المثال، يمكن أن يحتوي كائن ShaderMaterial الخاص بك على تقنيتين، إحداهما معرفة بـ HLSL، والأخرى معرفة بـ GLSL. تحت المنصات غير النوافذية يجب استخدام GLSL بدلاً من HSL.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor() | تهيئة نسخة جديدة من الفئة ShaderMaterial. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload(name) | تهيئة نسخة جديدة من الفئة ShaderMaterial. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | الاسم |

 **Result:**



---


### getTechniques{#getTechniques}

| الاسم | الوصف |
| --- | --- |
| getTechniques() | يحصل على جميع التقنيات المتاحة المعرفة في هذه المادة. |

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


### getTexture{#getTexture}

| الاسم | الوصف |
| --- | --- |
| getTexture(slotName) | يحصل على القوام من الفتحة المحددة، يمكن أن يكون اسم خاصية المادة أو اسم معامل الـ shader |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| slotName | String | اسم الفتحة. |

 **Result:**
TextureBase


---


### setTexture{#setTexture}

| الاسم | الوصف |
| --- | --- |
| setTexture(slotName, texture) | يعيّن القوام إلى الفتحة المحددة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| slotName | String | اسم الفتحة. |
| texture | TextureBase | القوام. |

 **Result:**
TextureBase


---


### toString{#toString}

| الاسم | الوصف |
| --- | --- |
| toString() | يحوّل الكائن إلى سلسلة |

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


### iterator{#iterator}

| الاسم | الوصف |
| --- | --- |
| iterator() | محجوز للاستخدام الداخلي. |

 **Result:**
خاصية


---



