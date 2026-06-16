---
title: "المشهد"
second_title: "مرجع API لـ Aspose.3D for Java"
description: 
type: docs
weight: 161
url: /ar/java/com.aspose.threed/scene/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Scene extends SceneObject
```
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Scene(Entity entity)](#Scene-com.aspose.threed.Entity-) | يُنشئ مثيلاً جديداً لفئة [Scene](../../com.aspose.threed/scene) مع كيان مرفق بعقدة جديدة. |
| [Scene(Scene parentScene, String name)](#Scene-com.aspose.threed.Scene-java.lang.String-) | يُنشئ مثيلاً جديداً لفئة [Scene](../../com.aspose.threed/scene) كمشهد فرعي. |
| [Scene()](#Scene--) | يُنشئ مثيلاً جديداً لفئة [Scene](../../com.aspose.threed/scene). |
## الحقول

| حقل | الوصف |
| --- | --- |
| [VERSION](#VERSION) | يحصل على نسخة الإصدار الحالية |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [clear()](#clear--) | يمسح محتوى المشهد ويستعيد الإعدادات الافتراضية. |
| [createAnimationClip(String name)](#createAnimationClip-java.lang.String-) | دالة مختصرة لإنشاء وتسجيل [AnimationClip](../../com.aspose.threed/animationclip) سيتم تعيين أول [AnimationClip](../../com.aspose.threed/animationclip) إلى [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip) |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | يفتح المشهد من المسار المحدد |
| [fromFile(String fileName, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.Cancellation-) | يفتح المشهد من المسار المحدد |
| [fromFile(String fileName, FileFormat format)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-) | يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد. |
| [fromFile(String fileName, FileFormat format, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد. |
| [fromFile(String fileName, LoadOptions options)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-) | يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد. |
| [fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد. |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | يفتح المشهد من الدفق المحدد |
| [fromStream(Stream stream, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | يفتح المشهد من الدفق المحدد |
| [fromStream(Stream stream, FileFormat format)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | يفتح المشهد من الدفق المحدد باستخدام تنسيق الملف المحدد. |
| [fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | يفتح المشهد من الدفق المحدد باستخدام تنسيق الملف المحدد. |
| [fromStream(Stream stream, LoadOptions options)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | يفتح المشهد من الدفق المحدد باستخدام تكوين الإدخال/الإخراج المحدد. |
| [fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | يفتح المشهد من الدفق المحدد باستخدام تكوين الإدخال/الإخراج المحدد. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | يفتح المشهد من الدفق المحدد |
| [fromStream(InputStream stream, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-) | يفتح المشهد من الدفق المحدد |
| [fromStream(InputStream stream, FileFormat format)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-) | يفتح المشهد من الدفق المحدد باستخدام تنسيق الملف المحدد. |
| [fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | يفتح المشهد من الدفق المحدد باستخدام تنسيق الملف المحدد. |
| [fromStream(InputStream stream, LoadOptions options)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-) | يفتح المشهد من الدفق المحدد باستخدام تكوين الإدخال/الإخراج المحدد. |
| [fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | يفتح المشهد من الدفق المحدد باستخدام تكوين الإدخال/الإخراج المحدد. |
| [getAnimationClip(String name)](#getAnimationClip-java.lang.String-) | يحصل على [AnimationClip](../../com.aspose.threed/animationclip) مسمى |
| [getAnimationClips()](#getAnimationClips--) | يحصل على جميع [AnimationClip](../../com.aspose.threed/animationclip) المعرفة في المشهد. |
| [getAssetInfo()](#getAssetInfo--) | يحصل على معلومات الأصل من المستوى الأعلى |
| [getClass()](#getClass--) |  |
| [getCurrentAnimationClip()](#getCurrentAnimationClip--) | يحصل على [AnimationClip](../../com.aspose.threed/animationclip) النشط |
| [getLibrary()](#getLibrary--) | يمكن تعريف الكائنات التي لا تُستخدم مباشرة في هيكل المشهد في المكتبة. |
| [getName()](#getName--) | يحصل على الاسم. |
| [getPoses()](#getPoses--) | يحصل على جميع [Pose](../../com.aspose.threed/pose) المستخدمة في هذا المشهد. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getRootNode()](#getRootNode--) | يحصل على عقدة الجذر للمشهد. |
| [getScene()](#getScene--) | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [getSubScenes()](#getSubScenes--) | يحصل على جميع المشاهد الفرعية |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [open(Stream stream)](#open-com.aspose.threed.Stream-) | يفتح المشهد من الدفق المحدد |
| [open(Stream stream, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | يفتح المشهد من الدفق المحدد |
| [open(Stream stream, FileFormat format)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | يفتح المشهد من الدفق المحدد باستخدام تنسيق الملف المحدد. |
| [open(Stream stream, FileFormat format, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | يفتح المشهد من الدفق المحدد باستخدام تنسيق الملف المحدد. |
| [open(Stream stream, LoadOptions options)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | يفتح المشهد من الدفق المحدد باستخدام تكوين الإدخال/الإخراج المحدد. |
| [open(Stream stream, LoadOptions options, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | يفتح المشهد من الدفق المحدد باستخدام تكوين الإدخال/الإخراج المحدد. |
| [open(InputStream stream)](#open-java.io.InputStream-) | يفتح المشهد من الدفق المحدد |
| [open(InputStream stream, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.Cancellation-) | يفتح المشهد من الدفق المحدد |
| [open(InputStream stream, FileFormat format)](#open-java.io.InputStream-com.aspose.threed.FileFormat-) | يفتح المشهد من الدفق المحدد باستخدام تنسيق الملف المحدد. |
| [open(InputStream stream, FileFormat format, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | يفتح المشهد من الدفق المحدد باستخدام تنسيق الملف المحدد. |
| [open(InputStream stream, LoadOptions options)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-) | يفتح المشهد من الدفق المحدد باستخدام تكوين الإدخال/الإخراج المحدد. |
| [open(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | يفتح المشهد من الدفق المحدد باستخدام تكوين الإدخال/الإخراج المحدد. |
| [open(String fileName)](#open-java.lang.String-) | يفتح المشهد من المسار المحدد |
| [open(String fileName, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.Cancellation-) | يفتح المشهد من المسار المحدد |
| [open(String fileName, FileFormat format)](#open-java.lang.String-com.aspose.threed.FileFormat-) | يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد. |
| [open(String fileName, FileFormat format, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد. |
| [open(String fileName, LoadOptions options)](#open-java.lang.String-com.aspose.threed.LoadOptions-) | يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد. |
| [open(String fileName, LoadOptions options, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد. |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [render(Camera camera, TextureData bitmap)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-) | يُصوِّر المشهد إلى صورة نقطية من منظور الكاميرا المحددة. |
| [render(Camera camera, TextureData bitmap, ImageRenderOptions options)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-) | يُصوِّر المشهد إلى صورة نقطية من منظور الكاميرا المحددة. |
| [render(Camera camera, String fileName)](#render-com.aspose.threed.Camera-java.lang.String-) | يُصوِّر المشهد إلى ملف خارجي من منظور الكاميرا المحددة. |
| [render(Camera camera, String fileName, Vector2 size, String format)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-) | يُصوِّر المشهد إلى ملف خارجي من منظور الكاميرا المحددة. |
| [render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-) | يُصوِّر المشهد إلى ملف خارجي من منظور الكاميرا المحددة. |
| [save(Stream stream, FileFormat format)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | يحفظ المشهد إلى الدفق باستخدام تنسيق الملف المحدد. |
| [save(Stream stream, FileFormat format, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | يحفظ المشهد إلى الدفق باستخدام تنسيق الملف المحدد. |
| [save(Stream stream, SaveOptions options)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-) | يحفظ المشهد إلى الدفق باستخدام تنسيق الملف المحدد. |
| [save(Stream stream, SaveOptions options, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | يحفظ المشهد إلى الدفق باستخدام تنسيق الملف المحدد. |
| [save(OutputStream stream, FileFormat format)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-) | يحفظ المشهد إلى الدفق باستخدام تنسيق الملف المحدد. |
| [save(OutputStream stream, FileFormat format, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | يحفظ المشهد إلى الدفق باستخدام تنسيق الملف المحدد. |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-) | يحفظ المشهد إلى الدفق باستخدام تنسيق الملف المحدد. |
| [save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | يحفظ المشهد إلى الدفق باستخدام تنسيق الملف المحدد. |
| [save(String fileName)](#save-java.lang.String-) | يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد. |
| [save(String fileName, FileFormat format)](#save-java.lang.String-com.aspose.threed.FileFormat-) | يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد. |
| [save(String fileName, FileFormat format, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد. |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.threed.SaveOptions-) | يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد. |
| [save(String fileName, SaveOptions options, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | يضبط معلومات الأصل ذات المستوى الأعلى |
| [setCurrentAnimationClip(AnimationClip value)](#setCurrentAnimationClip-com.aspose.threed.AnimationClip-) | يضبط الـ [AnimationClip](../../com.aspose.threed/animationclip) النشط |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Scene(Entity entity) {#Scene-com.aspose.threed.Entity-}
```
public Scene(Entity entity)
```


يُنشئ مثيلاً جديداً لفئة [Scene](../../com.aspose.threed/scene) مع كيان مرفق بعقدة جديدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | entity | [Entity](../../com.aspose.threed/entity) | الكيان الأولي الذي تم ربطه بالمشهد **مثال:** الشيفرة التالية توضح كيفية إنشاء [getScene](../../com.aspose.threed/scene\#getScene) مباشرةً من [Entity](../../com.aspose.threed/entity): |

```
var scene = new Scene(new Box());
``` |

### Scene(Scene parentScene, String name) {#Scene-com.aspose.threed.Scene-java.lang.String-}
```
public Scene(Scene parentScene, String name)
```


يُنشئ مثيلاً جديداً لفئة [Scene](../../com.aspose.threed/scene) كمشهد فرعي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| parentScene | [Scene](../../com.aspose.threed/scene) | المشهد الأب. |
| الاسم | java.lang.String | اسم المشهد. |

### Scene() {#Scene--}
```
public Scene()
```


يُنشئ مثيلاً جديداً لفئة [Scene](../../com.aspose.threed/scene).

### VERSION {#VERSION}
```
public static final String VERSION
```


يحصل على نسخة الإصدار الحالية

### clear() {#clear--}
```
public void clear()
```


يمسح محتوى المشهد ويستعيد الإعدادات الافتراضية.

### createAnimationClip(String name) {#createAnimationClip-java.lang.String-}
```
public AnimationClip createAnimationClip(String name)
```


دالة مختصرة لإنشاء وتسجيل [AnimationClip](../../com.aspose.threed/animationclip) سيتم تعيين أول [AnimationClip](../../com.aspose.threed/animationclip) إلى [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم مقطع الرسوم المتحركة |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - A new animation clip instance with given name
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


يبحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (Created by CreateDynamicProperty/SetProperty) أو خاصية أصلية (Identified by its name)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| propertyName | java.lang.String | اسم الخاصية. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static Scene fromFile(String fileName)
```


يفتح المشهد من المسار المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, Cancellation cancellationToken)
```


يفتح المشهد من المسار المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة التحميل |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-}
```
public static Scene fromFile(String fileName, FileFormat format)
```


يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | تنسيق الملف. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, FileFormat format, Cancellation cancellationToken)
```


يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | تنسيق الملف. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة التحميل |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-}
```
public static Scene fromFile(String fileName, LoadOptions options)
```


يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | إعدادات أكثر تفصيلاً لفتح الدفق. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)
```


يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | إعدادات أكثر تفصيلاً لفتح الدفق. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة التحميل |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static Scene fromStream(Stream stream)
```


يفتح المشهد من الدفق المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, Cancellation cancellationToken)
```


يفتح المشهد من الدفق المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة التحميل |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(Stream stream, FileFormat format)
```


يفتح المشهد من الدفق المحدد باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | تنسيق الملف. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)
```


يفتح المشهد من الدفق المحدد باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | تنسيق الملف. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة التحميل |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(Stream stream, LoadOptions options)
```


يفتح المشهد من الدفق المحدد باستخدام تكوين الإدخال/الإخراج المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | إعدادات أكثر تفصيلاً لفتح الدفق. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


يفتح المشهد من الدفق المحدد باستخدام تكوين الإدخال/الإخراج المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | إعدادات أكثر تفصيلاً لفتح الدفق. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة التحميل |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static Scene fromStream(InputStream stream)
```


يفتح المشهد من الدفق المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | تدفق | java.io.InputStream | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. **مثال:** الشيفرة التالية توضح كيفية إنشاء مشهد من دفق مع مصدر رمز إلغاء |

```
var cts = new Cancellation();    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, Cancellation cancellationToken)
```


يفتح المشهد من الدفق المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة التحميل **مثال:** الشيفرة التالية توضح كيفية إنشاء مشهد من دفق مع مصدر رمز إلغاء |

```
var cts = new Cancellation();    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, cts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, FileFormat format) {#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(InputStream stream, FileFormat format)
```


يفتح المشهد من الدفق المحدد باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | تنسيق الملف. **مثال:** الشيفرة التالية توضح كيفية إنشاء مشهد من دفق |

```
try(InputStream input = new FileInputStream("input.fbx")) {    
          Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)
```


يفتح المشهد من الدفق المحدد باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | تنسيق الملف. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة التحميل **مثال:** الشيفرة التالية توضح كيفية إنشاء مشهد من دفق |

```
try(InputStream input = new FileInputStream("input.fbx")) {    
          Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, LoadOptions options) {#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(InputStream stream, LoadOptions options)
```


يفتح المشهد من الدفق المحدد باستخدام تكوين الإدخال/الإخراج المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | إعدادات أكثر تفصيلاً لفتح الدفق. **مثال:** الشيفرة التالية توضح كيفية إنشاء مشهد من دفق مع خيارات التحميل |

```
var opts = new FbxLoadOptions();    
     opts.getLookupPaths().add("textures");    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, opts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)
```


يفتح المشهد من الدفق المحدد باستخدام تكوين الإدخال/الإخراج المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | إعدادات أكثر تفصيلاً لفتح الدفق. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة التحميل **مثال:** الشيفرة التالية توضح كيفية إنشاء مشهد من دفق مع خيارات التحميل |

```
var opts = new FbxLoadOptions();    
     opts.getLookupPaths().add("textures");    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, opts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### getAnimationClip(String name) {#getAnimationClip-java.lang.String-}
```
public AnimationClip getAnimationClip(String name)
```


يحصل على [AnimationClip](../../com.aspose.threed/animationclip) مسمى

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الـ [AnimationClip](../../com.aspose.threed/animationclip) للبحث عنه |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - Returned AnimationClip
### getAnimationClips() {#getAnimationClips--}
```
public List<AnimationClip> getAnimationClips()
```


يحصل على جميع [AnimationClip](../../com.aspose.threed/animationclip) المعرفة في المشهد.

**Returns:**
java.util.List<com.aspose.threed.AnimationClip> - جميع الـ [AnimationClip](../../com.aspose.threed/animationclip) المعرفة في المشهد.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


يحصل على معلومات الأصل من المستوى الأعلى

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - the top-level asset information **Example:** The following code shows how to read the application information from a FBX file:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The FBX file is created by %s %s",
         scene.getAssetInfo().getApplicationName(),
         scene.getAssetInfo().getApplicationVersion());
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurrentAnimationClip() {#getCurrentAnimationClip--}
```
public AnimationClip getCurrentAnimationClip()
```


يحصل على [AnimationClip](../../com.aspose.threed/animationclip) النشط

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - the active [AnimationClip](../../com.aspose.threed/animationclip)
### getLibrary() {#getLibrary--}
```
public List<A3DObject> getLibrary()
```


الكائنات التي لا تُستخدم مباشرةً في هيكلية المشهد يمكن تعريفها في المكتبة. هذا مفيد عندما تستخدم المشاهد الفرعية وتضع المكونات القابلة لإعادة الاستخدام تحت المشاهد الفرعية.

**Returns:**
java.util.List<com.aspose.threed.A3DObject> - الكائنات التي لا تُستخدم مباشرةً في هيكلية المشهد يمكن تعريفها في المكتبة. هذا مفيد عندما تستخدم المشاهد الفرعية وتضع المكونات القابلة لإعادة الاستخدام تحت المشاهد الفرعية.
### getName() {#getName--}
```
public String getName()
```


يحصل على الاسم.

**Returns:**
java.lang.String - الاسم.
### getPoses() {#getPoses--}
```
public Collection<Pose> getPoses()
```


يحصل على جميع [Pose](../../com.aspose.threed/pose) المستخدمة في هذا المشهد.

**Returns:**
java.util.Collection<com.aspose.threed.Pose> - جميع الـ [Pose](../../com.aspose.threed/pose) المستخدمة في هذا المشهد.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


يحصل على مجموعة جميع الخصائص.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


احصل على قيمة الخاصية المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| خاصية | java.lang.String | اسم الخاصية |

**Returns:**
java.lang.Object - قيمة الخاصية التي تم العثور عليها
### getRootNode() {#getRootNode--}
```
public Node getRootNode()
```


يحصل على عقدة الجذر للمشهد.

**Returns:**
[Node](../../com.aspose.threed/node) - the root node of the scene. **Example:** The following code shows how to create a node with Box entity attached to the root node.

```
Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box());
     scene.save("box.stl");
```
### getScene() {#getScene--}
```
public Scene getScene()
```


يحصل على المشهد الذي ينتمي إليه هذا الكائن

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getSubScenes() {#getSubScenes--}
```
public List<Scene> getSubScenes()
```


يحصل على جميع المشاهد الفرعية

**Returns:**
java.util.List<com.aspose.threed.Scene> - جميع المشاهد الفرعية
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### open(Stream stream) {#open-com.aspose.threed.Stream-}
```
public void open(Stream stream)
```


يفتح المشهد من الدفق المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |

### open(Stream stream, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, Cancellation cancellationToken)
```


يفتح المشهد من الدفق المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة التحميل |

### open(Stream stream, FileFormat format) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void open(Stream stream, FileFormat format)
```


يفتح المشهد من الدفق المحدد باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | تنسيق الملف. |

### open(Stream stream, FileFormat format, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, FileFormat format, Cancellation cancellationToken)
```


يفتح المشهد من الدفق المحدد باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | تنسيق الملف. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة التحميل |

### open(Stream stream, LoadOptions options) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public void open(Stream stream, LoadOptions options)
```


يفتح المشهد من الدفق المحدد باستخدام تكوين الإدخال/الإخراج المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | إعدادات أكثر تفصيلاً لفتح الدفق. |

### open(Stream stream, LoadOptions options, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


يفتح المشهد من الدفق المحدد باستخدام تكوين الإدخال/الإخراج المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | إعدادات أكثر تفصيلاً لفتح الدفق. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة التحميل |

### open(InputStream stream) {#open-java.io.InputStream-}
```
public void open(InputStream stream)
```


يفتح المشهد من الدفق المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | تدفق | java.io.InputStream | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. **مثال:** الشيفرة التالية توضح كيفية فتح مشهد من دفق |

```
var scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs);    
     }
``` |

### open(InputStream stream, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, Cancellation cancellationToken)
```


يفتح المشهد من الدفق المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة التحميل **مثال:** يوضح الكود التالي كيفية فتح مشهد من تدفق باستخدام رمز الإلغاء |

```
var scene = new Scene();    
     Cancellation cts = new Cancellation();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, cts);    
     }
``` |

### open(InputStream stream, FileFormat format) {#open-java.io.InputStream-com.aspose.threed.FileFormat-}
```
public void open(InputStream stream, FileFormat format)
```


يفتح المشهد من الدفق المحدد باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | تنسيق الملف. **مثال:** يوضح الكود التالي كيفية فتح مشهد من تدفق |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, FileFormat.GLTF2);    
     }
``` |

### open(InputStream stream, FileFormat format, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, FileFormat format, Cancellation cancellationToken)
```


يفتح المشهد من الدفق المحدد باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | تنسيق الملف. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة التحميل **مثال:** يوضح الكود التالي كيفية فتح مشهد من تدفق |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, FileFormat.GLTF2);    
     }
``` |

### open(InputStream stream, LoadOptions options) {#open-java.io.InputStream-com.aspose.threed.LoadOptions-}
```
public void open(InputStream stream, LoadOptions options)
```


يفتح المشهد من الدفق المحدد باستخدام تكوين الإدخال/الإخراج المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | إعدادات أكثر تفصيلاً لفتح التدفق. **مثال:** يوضح الكود التالي كيفية فتح مشهد من تدفق مع خيارات تحميل إضافية |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         var opt = new FbxLoadOptions();    
         opt.getLookupPaths().add("textures");    
         scene.open(fs, opt);    
     }
``` |

### open(InputStream stream, LoadOptions options, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, LoadOptions options, Cancellation cancellationToken)
```


يفتح المشهد من الدفق المحدد باستخدام تكوين الإدخال/الإخراج المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | إعدادات أكثر تفصيلاً لفتح الدفق. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة التحميل **مثال:** يوضح الكود التالي كيفية فتح مشهد من تدفق مع خيارات تحميل إضافية |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         var opt = new FbxLoadOptions();    
         opt.getLookupPaths().add("textures");    
         scene.open(fs, opt);    
     }
``` |

### open(String fileName) {#open-java.lang.String-}
```
public void open(String fileName)
```


يفتح المشهد من المسار المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف. |

### open(String fileName, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.Cancellation-}
```
public void open(String fileName, Cancellation cancellationToken)
```


يفتح المشهد من المسار المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة التحميل |

### open(String fileName, FileFormat format) {#open-java.lang.String-com.aspose.threed.FileFormat-}
```
public void open(String fileName, FileFormat format)
```


يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | تنسيق الملف. |

### open(String fileName, FileFormat format, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(String fileName, FileFormat format, Cancellation cancellationToken)
```


يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | تنسيق الملف. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة التحميل |

### open(String fileName, LoadOptions options) {#open-java.lang.String-com.aspose.threed.LoadOptions-}
```
public void open(String fileName, LoadOptions options)
```


يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | إعدادات أكثر تفصيلاً لفتح الدفق. |

### open(String fileName, LoadOptions options, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(String fileName, LoadOptions options, Cancellation cancellationToken)
```


يفتح المشهد من المسار المحدد باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | إعدادات أكثر تفصيلاً لفتح الدفق. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة التحميل |

### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


يزيل خاصية ديناميكية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | أي خاصية تريد إزالتها |

**Returns:**
boolean - true إذا تم إزالة الخاصية بنجاح
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


إزالة الخاصية المحددة التي تم التعرف عليها بالاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| خاصية | java.lang.String | أي خاصية تريد إزالتها |

**Returns:**
boolean - true إذا تم إزالة الخاصية بنجاح
### render(Camera camera, TextureData bitmap) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-}
```
public void render(Camera camera, TextureData bitmap)
```


يُصوِّر المشهد إلى صورة نقطية من منظور الكاميرا المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | من أي منظور للكاميرا يتم عرض المشهد |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | هدف النتيجة المعروضة |

### render(Camera camera, TextureData bitmap, ImageRenderOptions options) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```


يُصوِّر المشهد إلى صورة نقطية من منظور الكاميرا المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | من أي منظور للكاميرا يتم عرض المشهد |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | هدف النتيجة المعروضة |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | الخيار لتخصيص بعض الإعدادات الداخلية. |

### render(Camera camera, String fileName) {#render-com.aspose.threed.Camera-java.lang.String-}
```
public void render(Camera camera, String fileName)
```


اعرض المشهد في ملف خارجي من منظور الكاميرا المحددة. حجم الإخراج الافتراضي هو 1024x768 وتنسيق الإخراج هو png

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | من أي منظور للكاميرا يتم عرض المشهد |
| fileName | java.lang.String | اسم ملف الإخراج |

### render(Camera camera, String fileName, Vector2 size, String format) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-}
```
public void render(Camera camera, String fileName, Vector2 size, String format)
```


يُصوِّر المشهد إلى ملف خارجي من منظور الكاميرا المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | من أي منظور للكاميرا يتم عرض المشهد |
| fileName | java.lang.String | اسم ملف الإخراج |
| size | [Vector2](../../com.aspose.threed/vector2) | حجم الصورة المعروضة النهائية |
| تنسيق | java.lang.String | تنسيق صورة ملف الإخراج |

### render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)
```


يُصوِّر المشهد إلى ملف خارجي من منظور الكاميرا المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | من أي منظور للكاميرا يتم عرض المشهد |
| fileName | java.lang.String | اسم ملف الإخراج |
| size | [Vector2](../../com.aspose.threed/vector2) | حجم الصورة المعروضة النهائية |
| تنسيق | java.lang.String | تنسيق صورة ملف الإخراج |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | الخيار لتخصيص بعض الإعدادات الداخلية. |

### save(Stream stream, FileFormat format) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void save(Stream stream, FileFormat format)
```


يحفظ المشهد إلى الدفق باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | التنسيق. |

### save(Stream stream, FileFormat format, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, FileFormat format, Cancellation cancellationToken)
```


يحفظ المشهد إلى الدفق باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | التنسيق. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة الحفظ |

### save(Stream stream, SaveOptions options) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-}
```
public void save(Stream stream, SaveOptions options)
```


يحفظ المشهد إلى الدفق باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | إعدادات أكثر تفصيلاً لحفظ التدفق. |

### save(Stream stream, SaveOptions options, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, SaveOptions options, Cancellation cancellationToken)
```


يحفظ المشهد إلى الدفق باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | إعدادات أكثر تفصيلاً لحفظ التدفق. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة الحفظ |

### save(OutputStream stream, FileFormat format) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-}
```
public void save(OutputStream stream, FileFormat format)
```


يحفظ المشهد إلى الدفق باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.OutputStream | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | التنسيق. **مثال:** يوضح الكود التالي كيفية حفظ المشهد |

```
Scene scene = Scene.fromFile("input.fbx");    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, FileFormat.USDZ);    
     }
``` |

### save(OutputStream stream, FileFormat format, Cancellation cancellationToken) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(OutputStream stream, FileFormat format, Cancellation cancellationToken)
```


يحفظ المشهد إلى الدفق باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.OutputStream | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | التنسيق. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة الحفظ **مثال:** يوضح الكود التالي كيفية حفظ المشهد |

```
Scene scene = Scene.fromFile("input.fbx");    
     var cts = new Cancellation();    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, FileFormat.USDZ, cts);    
     }
``` |

### save(OutputStream stream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.threed.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions options)
```


يحفظ المشهد إلى الدفق باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.OutputStream | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
|  | options | [SaveOptions](../../com.aspose.threed/saveoptions) | إعدادات أكثر تفصيلاً لحفظ التدفق. **مثال:** يوضح الكود التالي كيفية حفظ المشهد |

```
Scene scene = Scene.fromFile("input.fbx");    
     var opt = new UsdSaveOptions();    
     opt.setPrimitiveToMesh(true);    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, opt);    
     }
``` |

### save(OutputStream stream, SaveOptions options, Cancellation cancellationToken) {#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)
```


يحفظ المشهد إلى الدفق باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.OutputStream | دفق الإدخال، المستخدم مسؤول عن إغلاق الدفق. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | إعدادات أكثر تفصيلاً لحفظ التدفق. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة الحفظ **مثال:** يوضح الكود التالي كيفية حفظ المشهد |

```
Scene scene = Scene.fromFile("input.fbx");    
     var cts = new Cancellation();    
     var opt = new UsdSaveOptions();    
     opt.setPrimitiveToMesh(true);    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, opt, cts);    
     }
``` |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف. |

### save(String fileName, FileFormat format) {#save-java.lang.String-com.aspose.threed.FileFormat-}
```
public void save(String fileName, FileFormat format)
```


يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | التنسيق. |

### save(String fileName, FileFormat format, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(String fileName, FileFormat format, Cancellation cancellationToken)
```


يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | التنسيق. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة الحفظ |

### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.threed.SaveOptions-}
```
public void save(String fileName, SaveOptions options)
```


يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | إعدادات أكثر تفصيلاً لحفظ التدفق. |

### save(String fileName, SaveOptions options, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(String fileName, SaveOptions options, Cancellation cancellationToken)
```


يحفظ المشهد إلى المسار المحدد باستخدام تنسيق الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم الملف. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | إعدادات أكثر تفصيلاً لحفظ التدفق. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | رمز الإلغاء لمهمة الحفظ |

### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


يضبط معلومات الأصل ذات المستوى الأعلى

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [AssetInfo](../../com.aspose.threed/assetinfo) | قيمة جديدة **مثال:** يوضح الكود التالي كيفية قراءة معلومات التطبيق من ملف FBX: |

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The FBX file is created by %s %s",
         scene.getAssetInfo().getApplicationName(),
         scene.getAssetInfo().getApplicationVersion());
``` |

### setCurrentAnimationClip(AnimationClip value) {#setCurrentAnimationClip-com.aspose.threed.AnimationClip-}
```
public void setCurrentAnimationClip(AnimationClip value)
```


يضبط الـ [AnimationClip](../../com.aspose.threed/animationclip) النشط

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [AnimationClip](../../com.aspose.threed/animationclip) | القيمة الجديدة |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


يضبط الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


يضبط قيمة الخاصية المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| خاصية | java.lang.String | اسم الخاصية |
| القيمة | java.lang.Object | قيمة الخاصية |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

