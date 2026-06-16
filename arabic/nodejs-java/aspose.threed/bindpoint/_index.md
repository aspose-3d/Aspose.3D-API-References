---
title: "BindPoint"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/bindpoint/
---
## BindPoint class

عادةً ما يتم إنشاء BindPoint على خاصية كائن، بعض أنواع الخصائص تحتوي على حقول مكوّن متعددة (مثل حقل Vector3)، سيولد BindPoint قناة لكل حقل مكوّن ويربط الحقل بواحد أو أكثر من مثيلات تسلسل الإطارات المفتاحية عبر القنوات.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor(scene, prop) | ينشئ مثيلاً جديداً من الفئة BindPoint. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| scene | Scene | المشهد الذي يحتوي على الرسوم المتحركة. |
| prop | خاصية | خاصية. |

 **Result:**



---


### getProperty{#getProperty}

| الاسم | الوصف |
| --- | --- |
| getProperty() | يحصل على الخاصية المرتبطة بـ CurveMapping |

 **Result:**



---


### setProperty{#setProperty}

| الاسم | الوصف |
| --- | --- |
| setProperty(value) | يحصل على الخاصية المرتبطة بـ CurveMapping |

 **Result:**



---


### getChannelsCount{#getChannelsCount}

| الاسم | الوصف |
| --- | --- |
| getChannelsCount() | يحصل على العدد الإجمالي لقنوات الخاصية المعرفة في تخطيط منحنى الرسوم المتحركة هذا. |

 **Result:**
Number


---


### getName{#getName}

| الاسم | الوصف |
| --- | --- |
| getName() | يحصل أو يضبط الاسم. الاسم. |

 **Result:**
Number


---


### setName{#setName}

| الاسم | الوصف |
| --- | --- |
| setName(value) | يحصل أو يضبط الاسم. الاسم. |

 **Result:**
Number


---


### getProperties{#getProperties}

| الاسم | الوصف |
| --- | --- |
| getProperties() | يحصل على مجموعة جميع الخصائص. |

 **Result:**
Number


---


### get{#get}

| الاسم | الوصف |
| --- | --- |
| get(channelName) |  |

 **Result:**
Number


---


### getKeyframeSequence{#getKeyframeSequence}

| الاسم | الوصف |
| --- | --- |
| getKeyframeSequence(channelName) | يحصل على أول تسلسل إطار رئيسي في القناة المحددة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| channelName | String | اسم القناة للعثور عليه |

 **Result:**
KeyframeSequence


---


### getKeyframeSequences{#getKeyframeSequences}

| الاسم | الوصف |
| --- | --- |
| getKeyframeSequences(channelName) | يحصل على جميع تسلسلات الإطارات الرئيسية في القناة المحددة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| channelName | String | اسم القناة للعثور عليه |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### createKeyframeSequence{#createKeyframeSequence}

| الاسم | الوصف |
| --- | --- |
| createKeyframeSequence(name) | ينشئ منحنى جديدًا ويربطه بالقناة الأولى لتخطيط المنحنى |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | اسم التسلسل الجديد. |

 **Result:**
KeyframeSequence


---


### bindKeyframeSequence{#bindKeyframeSequence}

| الاسم | الوصف |
| --- | --- |
| bindKeyframeSequence(channelName, sequence) | ربط تسلسل الإطار الرئيسي بالقناة المحددة |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| channelName | String | القناة التي سيُربط بها تسلسل الإطار الرئيسي |
| تسلسل | KeyframeSequence | تسلسل الإطار الرئيسي للربط |

 **Result:**
KeyframeSequence


---


### getChannel{#getChannel}

| الاسم | الوصف |
| --- | --- |
| getChannel(channelName) | يحصل على القناة بالاسم المعطى |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| channelName | String | اسم القناة للعثور عليه |

 **Result:**
AnimationChannel


---


### addChannel{#addChannel}

| الاسم | الوصف |
| --- | --- |
| addChannel(name, value) | يضيف خاصية القناة المحددة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | الاسم. |
| القيمة | Object | القيمة. |

 **Result:**
boolean


---


### addChannel{#addChannel}

| الاسم | الوصف |
| --- | --- |
| addChannel(name, type, value) | يضيف خاصية القناة المحددة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | الاسم. |
| type | الفئة | النوع. |
| القيمة | Object | القيمة. |

 **Result:**
boolean


---


### resetChannels{#resetChannels}

| الاسم | الوصف |
| --- | --- |
| resetChannels() | يفرغ قنوات الخصائص لتخطيط منحنى الرسوم المتحركة هذا. |

 **Result:**
boolean


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



