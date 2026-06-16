---
title: "PhongMaterial"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/phongmaterial/
---
## PhongMaterial class

مادة لنموذج التظليل بلين-فونغ.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor() | يُنشئ مثيلاً جديدًا من الفئة PhongMaterial. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload(name) | يُنشئ مثيلاً جديدًا من الفئة PhongMaterial. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | الاسم |

 **Result:**



---


### getSpecularColor{#getSpecularColor}

| الاسم | الوصف |
| --- | --- |
| getSpecularColor() | يحصل أو يعيّن اللون الانعكاسي. |

 **Result:**



---


### setSpecularColor{#setSpecularColor}

| الاسم | الوصف |
| --- | --- |
| setSpecularColor(value) | يحصل أو يعيّن اللون الانعكاسي. |

 **Result:**



---


### getSpecularFactor{#getSpecularFactor}

| الاسم | الوصف |
| --- | --- |
| getSpecularFactor() | يحصل أو يعيّن عامل الانعكاس اللامع. صيغة الانعكاس اللامع: SpecularColor SpecularFactor (N dot H) ^ Shininess |

 **Result:**



---


### setSpecularFactor{#setSpecularFactor}

| الاسم | الوصف |
| --- | --- |
| setSpecularFactor(value) | يحصل أو يعيّن عامل الانعكاس اللامع. صيغة الانعكاس اللامع: SpecularColor SpecularFactor (N dot H) ^ Shininess |

 **Result:**



---


### getShininess{#getShininess}

| الاسم | الوصف |
| --- | --- |
| getShininess() | يحصل أو يعيّن اللمعان، هذا يتحكم في حجم إبراز الانعكاس اللامع. صيغة الانعكاس اللامع: SpecularColor SpecularFactor (N dot H) ^ Shininess اللمعان. |

 **Result:**



---


### setShininess{#setShininess}

| الاسم | الوصف |
| --- | --- |
| setShininess(value) | يحصل أو يعيّن اللمعان، هذا يتحكم في حجم إبراز الانعكاس اللامع. صيغة الانعكاس اللامع: SpecularColor SpecularFactor (N dot H) ^ Shininess اللمعان. |

 **Result:**



---


### getReflectionColor{#getReflectionColor}

| الاسم | الوصف |
| --- | --- |
| getReflectionColor() | يحصل أو يعيّن لون الانعكاس. الانعكاس. |

 **Result:**



---


### setReflectionColor{#setReflectionColor}

| الاسم | الوصف |
| --- | --- |
| setReflectionColor(value) | يحصل أو يعيّن لون الانعكاس. الانعكاس. |

 **Result:**



---


### getReflectionFactor{#getReflectionFactor}

| الاسم | الوصف |
| --- | --- |
| getReflectionFactor() | يحصل أو يعيّن تخفيض لون الانعكاس. عامل الانعكاس. |

 **Result:**



---


### setReflectionFactor{#setReflectionFactor}

| الاسم | الوصف |
| --- | --- |
| setReflectionFactor(value) | يحصل أو يعيّن تخفيض لون الانعكاس. عامل الانعكاس. |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| الاسم | الوصف |
| --- | --- |
| getEmissiveColor() | يحصل أو يضبط اللون الانبعاثي |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| الاسم | الوصف |
| --- | --- |
| setEmissiveColor(value) | يحصل أو يضبط اللون الانبعاثي |

 **Result:**



---


### getAmbientColor{#getAmbientColor}

| الاسم | الوصف |
| --- | --- |
| getAmbientColor() | يحصل أو يضبط اللون المحيط. المثال: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### setAmbientColor{#setAmbientColor}

| الاسم | الوصف |
| --- | --- |
| setAmbientColor(value) | يحصل أو يضبط اللون المحيط. المثال: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### getDiffuseColor{#getDiffuseColor}

| الاسم | الوصف |
| --- | --- |
| getDiffuseColor() | يحصل أو يعيّن لون الانتشار المثال: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); الانتشار. |

 **Result:**



---


### setDiffuseColor{#setDiffuseColor}

| الاسم | الوصف |
| --- | --- |
| setDiffuseColor(value) | يحصل أو يعيّن لون الانتشار المثال: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); الانتشار. |

 **Result:**



---


### getTransparentColor{#getTransparentColor}

| الاسم | الوصف |
| --- | --- |
| getTransparentColor() | يحصل أو يعيّن اللون الشفاف. المثال: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); لون الشفاف. |

 **Result:**



---


### setTransparentColor{#setTransparentColor}

| الاسم | الوصف |
| --- | --- |
| setTransparentColor(value) | يحصل أو يعيّن اللون الشفاف. المثال: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); لون الشفاف. |

 **Result:**



---


### getTransparency{#getTransparency}

| الاسم | الوصف |
| --- | --- |
| getTransparency() | يحصل أو يعيّن عامل الشفافية. يجب أن يكون العامل ضمن النطاق بين 0(0٪، غير شفاف تمامًا) و 1(100٪، شفاف تمامًا). أي قيمة عامل غير صالحة سيتم تقليمها. المثال: var mat = new LambertMaterial(); mat.Transparency = 0.3; عامل الشفافية. |

 **Result:**



---


### setTransparency{#setTransparency}

| الاسم | الوصف |
| --- | --- |
| setTransparency(value) | يحصل أو يعيّن عامل الشفافية. يجب أن يكون العامل ضمن النطاق بين 0(0٪، غير شفاف تمامًا) و 1(100٪، شفاف تمامًا). أي قيمة عامل غير صالحة سيتم تقليمها. المثال: var mat = new LambertMaterial(); mat.Transparency = 0.3; عامل الشفافية. |

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



