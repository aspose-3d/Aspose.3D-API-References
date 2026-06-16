---
title: "Scene"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/scene/
---
## Scene class

المشهد هو كائن من المستوى الأعلى يحتوي على العقد، والهياكل، والمواد، والملمس، والرسوم المتحركة، والوضعيات، والمشاهد الفرعية، وما إلى ذلك.  يمكن للمشهد أن يحتوي على مشاهد فرعية، ويعمل كدعم متعدد المستندات في ملفات مثل collada/blender/fbx.  يمكن الوصول إلى تسلسل العقد من خلال RootNodeLibrary الذي يُستخدم للحفاظ على مرجع للكائنات غير المرتبطة أثناء التسلسل (مثل البيانات الوصفية أو الكائنات المخصصة) بحيث يمكن استخدامه كمكتبة.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor() | ينشئ مثيلاً جديداً لفئة Scene. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload(entity) | ينشئ مثيلاً جديداً لفئة Scene مع entity مرفق إلى عقدة جديدة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| كيان | كيان | الكيان الأولي الذي تم ربطه بالمشهد |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| الاسم | الوصف |
| --- | --- |
| constructor_overload2(parentScene, name) | ينشئ مثيلاً جديدًا من الفئة Scene كـ sub-scene. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| parentScene | Scene | المشهد الأب. |
| name | String | اسم Scene. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| الاسم | الوصف |
| --- | --- |
| constructor_overload3(fileName) | ينشئ مثيلاً جديدًا من الفئة Scene ويفتح الملف فورًا. هذا مُنشىء قديم، يرجى استخدام #Error Cref: M:Aspose.ThreeD.Scene.FromFile(System.String,System.Threading.CancellationToken). |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف للفتح. |

 **Result:**



---


### getSubScenes{#getSubScenes}

| الاسم | الوصف |
| --- | --- |
| getSubScenes() | يحصل على جميع sub-scenes |

 **Result:**



---


### getLibrary{#getLibrary}

| الاسم | الوصف |
| --- | --- |
| getLibrary() | الكائنات التي لا تُستخدم مباشرةً في تسلسل المشهد يمكن تعريفها في Library. هذا مفيد عندما تستخدم sub-scenes وتضع المكونات القابلة لإعادة الاستخدام تحت sub-scenes. |

 **Result:**



---


### getAnimationClips{#getAnimationClips}

| الاسم | الوصف |
| --- | --- |
| getAnimationClips() | يحصل على جميع AnimationClip المعرفة في المشهد. |

 **Result:**



---


### getCurrentAnimationClip{#getCurrentAnimationClip}

| الاسم | الوصف |
| --- | --- |
| getCurrentAnimationClip() | يحصل أو يضبط AnimationClip النشط |

 **Result:**



---


### setCurrentAnimationClip{#setCurrentAnimationClip}

| الاسم | الوصف |
| --- | --- |
| setCurrentAnimationClip(value) | يحصل أو يضبط AnimationClip النشط |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| الاسم | الوصف |
| --- | --- |
| getAssetInfo() | يحصل أو يضبط معلومات الأصول ذات المستوى الأعلى. معلومات المستند. |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| الاسم | الوصف |
| --- | --- |
| setAssetInfo(value) | يحصل أو يضبط معلومات الأصول ذات المستوى الأعلى. معلومات المستند. |

 **Result:**



---


### getPoses{#getPoses}

| الاسم | الوصف |
| --- | --- |
| getPoses() | يحصل على جميع Pose المستخدمة في هذا المشهد. Pose. |

 **Result:**



---


### getRootNode{#getRootNode}

| الاسم | الوصف |
| --- | --- |
| getRootNode() | يحصل على عقدة الجذر للمشهد. عقدة الجذر. |

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


### getAnimationClip{#getAnimationClip}

| الاسم | الوصف |
| --- | --- |
| getAnimationClip(name) | يحصل على AnimationClip مسمى |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | ال |

 **Result:**
AnimationClip


---


### clear{#clear}

| الاسم | الوصف |
| --- | --- |
| clear() | يمسح محتوى المشهد ويعيد الإعدادات الافتراضية. |

 **Result:**
AnimationClip


---


### createAnimationClip{#createAnimationClip}

| الاسم | الوصف |
| --- | --- |
| createAnimationClip(name) | دالة مختصرة لإنشاء وتسجيل الـAnimationClip. سيتم تعيين أول AnimationClip إلى CurrentAnimationClip |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| name | String | اسم مقطع الرسوم المتحركة |

 **Result:**
AnimationClip


---


### open{#open}

| الاسم | الوصف |
| --- | --- |
| open(fileName, options) | يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف. |
| الخيارات | LoadOptions | إعدادات تفصيلية أكثر لفتح الدفق. |

 **Result:**
AnimationClip


---


### open{#open}

| الاسم | الوصف |
| --- | --- |
| open(fileName) | يفتح المشهد من المسار المحدد |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف. |

 **Result:**
AnimationClip


---


### fromFile{#fromFile}

| الاسم | الوصف |
| --- | --- |
| fromFile(fileName) | يفتح المشهد من المسار المحدد |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف. |

 **Result:**
AnimationClip


---


### save{#save}

| الاسم | الوصف |
| --- | --- |
| save(fileName) | يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف. |

 **Result:**
AnimationClip


---


### save{#save}

| الاسم | الوصف |
| --- | --- |
| save(fileName, format) | يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف. |
| format | FileFormat | التنسيق. |

 **Result:**
AnimationClip


---


### save{#save}

| الاسم | الوصف |
| --- | --- |
| save(fileName, options) | يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف. |
| الخيارات | SaveOptions | إعدادات تفصيلية أكثر لحفظ الدفق. |

 **Result:**
AnimationClip


---


### render{#render}

| الاسم | الوصف |
| --- | --- |
| render(camera, fileName) | يتم تصيير المشهد إلى ملف خارجي من منظور الكاميرا المحددة. حجم الإخراج الافتراضي هو 1024x768 وتنسيق الإخراج هو png |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| الكاميرا | الكاميرا | من منظور أي كاميرا لتصوير المشهد |
| fileName | String | اسم ملف الإخراج |

 **Result:**
AnimationClip


---


### render{#render}

| الاسم | الوصف |
| --- | --- |
| render(camera, fileName, size, format) | يتم تصيير المشهد إلى ملف خارجي من منظور الكاميرا المحددة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| الكاميرا | الكاميرا | من منظور أي كاميرا لتصوير المشهد |
| fileName | String | اسم ملف الإخراج |
| الحجم | Vector2 | حجم الصورة المصورة النهائية |
| format | String | تنسيق الصورة لملف الإخراج |

 **Result:**
AnimationClip


---


### render{#render}

| الاسم | الوصف |
| --- | --- |
| render(camera, fileName, size, format, options) | يتم تصيير المشهد إلى ملف خارجي من منظور الكاميرا المحددة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| الكاميرا | الكاميرا | من منظور أي كاميرا لتصوير المشهد |
| fileName | String | اسم ملف الإخراج |
| الحجم | Vector2 | حجم الصورة المصورة النهائية |
| format | String | تنسيق الصورة لملف الإخراج |
| الخيارات | ImageRenderOptions | الخيار لتخصيص بعض الإعدادات الداخلية. |

 **Result:**
AnimationClip


---


### render{#render}

| الاسم | الوصف |
| --- | --- |
| render(camera, bitmap) | قم بتصوير المشهد إلى bitmap من منظور الكاميرا المعطاة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| الكاميرا | الكاميرا | من منظور أي كاميرا لتصوير المشهد |
| bitmap | TextureData | الهدف من النتيجة المرسومة |

 **Result:**
AnimationClip


---


### render{#render}

| الاسم | الوصف |
| --- | --- |
| render(camera, bitmap, options) | قم بتصوير المشهد إلى bitmap من منظور الكاميرا المعطاة. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| الكاميرا | الكاميرا | من منظور أي كاميرا لتصوير المشهد |
| bitmap | TextureData | الهدف من النتيجة المرسومة |
| الخيارات | ImageRenderOptions | الخيار لتخصيص بعض الإعدادات الداخلية. |

 **Result:**
AnimationClip


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



