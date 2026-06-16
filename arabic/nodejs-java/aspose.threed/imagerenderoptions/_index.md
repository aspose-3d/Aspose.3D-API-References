---
title: "ImageRenderOptions"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/imagerenderoptions/
---
## ImageRenderOptions class

خيارات لـ Scene.render(com.aspose.threed.Camera, java.lang.String, com.aspose.threed.Vector2, java.lang.String, com.aspose.threed.ImageRenderOptions) و Scene.render(com.aspose.threed.Camera, com.aspose.threed.TextureData, com.aspose.threed.ImageRenderOptions)


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor() | تهيئة نسخة من ImageRenderOptions |

 **Result:**



---


### getBackgroundColor{#getBackgroundColor}

| الاسم | الوصف |
| --- | --- |
| getBackgroundColor() | لون الخلفية لنتيجة العرض. |

 **Result:**



---


### setBackgroundColor{#setBackgroundColor}

| الاسم | الوصف |
| --- | --- |
| setBackgroundColor(value) | لون الخلفية لنتيجة العرض. |

 **Result:**



---


### getAssetDirectories{#getAssetDirectories}

| الاسم | الوصف |
| --- | --- |
| getAssetDirectories() | الدلائل التي تخزن الأصول الخارجية (مثل القوام) |

 **Result:**



---


### getEnableShadows{#getEnableShadows}

| الاسم | الوصف |
| --- | --- |
| getEnableShadows() | يحصل أو يضبط ما إذا كان يجب عرض الظلال. |

 **Result:**



---


### setEnableShadows{#setEnableShadows}

| الاسم | الوصف |
| --- | --- |
| setEnableShadows(value) | يحصل أو يضبط ما إذا كان يجب عرض الظلال. |

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



