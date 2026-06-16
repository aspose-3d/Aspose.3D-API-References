---
title: "AssetInfo"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "معلومات الأصل."
type: docs
weight: 17
url: /ar/java/com.aspose.threed/assetinfo/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AssetInfo extends A3DObject
```

معلومات الأصل. يمكن إرفاق معلومات الأصل بـ [Scene](../../com.aspose.threed/scene). يمكن للـ [Scene](../../com.aspose.threed/scene) الفرعي أن يحتوي على [AssetInfo](../../com.aspose.threed/assetinfo) الخاص به لتجاوز تعريف الأصل للأب. **مثال:** يوضح الكود التالي كيفية قراءة معلومات الأصل من ملف fbx:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The file is created at %s by %s %s",
          scene.getAssetInfo().getCreationTime(),
          scene.getAssetInfo().getApplicationName(),
          scene.getAssetInfo().getApplicationVersion());
```
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [AssetInfo()](#AssetInfo--) | يُنشئ مثيلاً جديداً من الفئة [AssetInfo](../../com.aspose.threed/assetinfo). |
| [AssetInfo(String name)](#AssetInfo-java.lang.String-) | يُنشئ مثيلاً جديداً من الفئة [AssetInfo](../../com.aspose.threed/assetinfo). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getAmbient()](#getAmbient--) | يحصل أو يضبط اللون المحيطي الافتراضي لهذا الأصل |
| [getApplicationName()](#getApplicationName--) | يحصل على التطبيق الذي أنشأ هذا الأصل |
| [getApplicationVendor()](#getApplicationVendor--) | يحصل على اسم بائع التطبيق |
| [getApplicationVersion()](#getApplicationVersion--) | يحصل على نسخة التطبيق الذي أنشأ هذا الأصل. |
| [getAuthor()](#getAuthor--) | يحصل على مؤلف هذا الأصل |
| [getAxisSystem()](#getAxisSystem--) | يحصل على نظام الإحداثيات/متجه الارتفاع/متجه الأمام لمعلومات الأصل. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | يحصل على تعليق هذا الأصل. |
| [getCoordinateSystem()](#getCoordinateSystem--) | يحصل على نظام الإحداثيات المستخدم في هذا الأصل. |
| [getCopyright()](#getCopyright--) | يحصل على حقوق النشر للوثيقة |
| [getCreationTime()](#getCreationTime--) | الحصول على أو تعيين وقت إنشاء هذا الأصل |
| [getFrontVector()](#getFrontVector--) | الحصول على المتجه الأمامي المستخدم في هذا الأصل. |
| [getKeywords()](#getKeywords--) | الحصول على الكلمات المفتاحية لهذا الأصل |
| [getModificationTime()](#getModificationTime--) | الحصول على أو تعيين وقت التعديل لهذا الأصل |
| [getName()](#getName--) | يحصل على الاسم. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getRevision()](#getRevision--) | الحصول على رقم المراجعة لهذا الأصل، يُستخدم عادةً في نظام التحكم بالإصدارات. |
| [getSubject()](#getSubject--) | الحصول على موضوع هذا الأصل |
| [getTitle()](#getTitle--) | الحصول على عنوان هذا الأصل |
| [getUnitName()](#getUnitName--) | الحصول على وحدة الطول المستخدمة في هذا الأصل. |
| [getUnitScaleFactor()](#getUnitScaleFactor--) | الحصول على معامل التحويل إلى المتر في العالم الحقيقي. |
| [getUpVector()](#getUpVector--) | الحصول على المتجه العلوي المستخدم في هذا الأصل. |
| [getUrl()](#getUrl--) | الحصول على أو تعيين عنوان URL لهذا الأصل. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [setAmbient(Vector4 value)](#setAmbient-com.aspose.threed.Vector4-) | يحصل أو يضبط اللون المحيطي الافتراضي لهذا الأصل |
| [setApplicationName(String value)](#setApplicationName-java.lang.String-) | تعيين التطبيق الذي أنشأ هذا الأصل |
| [setApplicationVendor(String value)](#setApplicationVendor-java.lang.String-) | تعيين اسم بائع التطبيق |
| [setApplicationVersion(String value)](#setApplicationVersion-java.lang.String-) | تعيين نسخة التطبيق الذي أنشأ هذا الأصل. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | تعيين مؤلف هذا الأصل |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | تعيين نظام الإحداثيات/المتجه العلوي/المتجه الأمامي لمعلومات الأصل. |
| [setComment(String value)](#setComment-java.lang.String-) | تعيين تعليق هذا الأصل. |
| [setCoordinateSystem(CoordinateSystem value)](#setCoordinateSystem-com.aspose.threed.CoordinateSystem-) | تعيين نظام الإحداثيات المستخدم في هذا الأصل. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | تعيين حقوق النشر للوثيقة |
| [setCreationTime(Calendar value)](#setCreationTime-java.util.Calendar-) | الحصول على أو تعيين وقت إنشاء هذا الأصل |
| [setFrontVector(Axis value)](#setFrontVector-com.aspose.threed.Axis-) | تعيين المتجه الأمامي المستخدم في هذا الأصل. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | تعيين الكلمات المفتاحية لهذا الأصل |
| [setModificationTime(Calendar value)](#setModificationTime-java.util.Calendar-) | الحصول على أو تعيين وقت التعديل لهذا الأصل |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setRevision(String value)](#setRevision-java.lang.String-) | تعيين رقم المراجعة لهذا الأصل، يُستخدم عادةً في نظام التحكم بالإصدارات. |
| [setSubject(String value)](#setSubject-java.lang.String-) | تعيين موضوع هذا الأصل |
| [setTitle(String value)](#setTitle-java.lang.String-) | تعيين عنوان هذا الأصل |
| [setUnitName(String value)](#setUnitName-java.lang.String-) | تعيين وحدة الطول المستخدمة في هذا الأصل. |
| [setUnitScaleFactor(double value)](#setUnitScaleFactor-double-) | يضبط عامل المقياس إلى المتر في العالم الحقيقي. |
| [setUpVector(Axis value)](#setUpVector-com.aspose.threed.Axis-) | يضبط المتجه العلوي المستخدم في هذا الأصل. |
| [setUrl(String value)](#setUrl-java.lang.String-) | الحصول على أو تعيين عنوان URL لهذا الأصل. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AssetInfo() {#AssetInfo--}
```
public AssetInfo()
```


يُنشئ مثيلاً جديداً من الفئة [AssetInfo](../../com.aspose.threed/assetinfo).

### AssetInfo(String name) {#AssetInfo-java.lang.String-}
```
public AssetInfo(String name)
```


يُنشئ مثيلاً جديداً من الفئة [AssetInfo](../../com.aspose.threed/assetinfo).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم |

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
### getAmbient() {#getAmbient--}
```
public Vector4 getAmbient()
```


يحصل أو يضبط اللون المحيطي الافتراضي لهذا الأصل

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - or Sets the default ambient color of this asset
### getApplicationName() {#getApplicationName--}
```
public String getApplicationName()
```


يحصل على التطبيق الذي أنشأ هذا الأصل

**Returns:**
java.lang.String - التطبيق الذي أنشأ هذا الأصل
### getApplicationVendor() {#getApplicationVendor--}
```
public String getApplicationVendor()
```


يحصل على اسم بائع التطبيق

**Returns:**
java.lang.String - اسم بائع التطبيق
### getApplicationVersion() {#getApplicationVersion--}
```
public String getApplicationVersion()
```


يحصل على نسخة التطبيق الذي أنشأ هذا الأصل.

**Returns:**
java.lang.String - إصدار التطبيق الذي أنشأ هذا الأصل.
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


يحصل على مؤلف هذا الأصل

**Returns:**
java.lang.String - مؤلف هذا الأصل
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


يحصل على نظام الإحداثيات/متجه الارتفاع/متجه الأمام لمعلومات الأصل.

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - the coordinate system/up vector/front vector of the asset info.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComment() {#getComment--}
```
public String getComment()
```


يحصل على تعليق هذا الأصل.

**Returns:**
java.lang.String - تعليق هذا الأصل.
### getCoordinateSystem() {#getCoordinateSystem--}
```
public CoordinateSystem getCoordinateSystem()
```


يحصل على نظام الإحداثيات المستخدم في هذا الأصل.

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system used in this asset.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


يحصل على حقوق النشر للوثيقة

**Returns:**
java.lang.String - حقوق النشر للوثيقة
### getCreationTime() {#getCreationTime--}
```
public Calendar getCreationTime()
```


الحصول على أو تعيين وقت إنشاء هذا الأصل

**Returns:**
java.util.Calendar - أو يضبط وقت إنشاء هذا الأصل
### getFrontVector() {#getFrontVector--}
```
public Axis getFrontVector()
```


الحصول على المتجه الأمامي المستخدم في هذا الأصل.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front-vector used in this asset.
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


الحصول على الكلمات المفتاحية لهذا الأصل

**Returns:**
java.lang.String - الكلمات المفتاحية لهذا الأصل
### getModificationTime() {#getModificationTime--}
```
public Calendar getModificationTime()
```


الحصول على أو تعيين وقت التعديل لهذا الأصل

**Returns:**
java.util.Calendar - أو يضبط وقت تعديل هذا الأصل
### getName() {#getName--}
```
public String getName()
```


يحصل على الاسم.

**Returns:**
java.lang.String - الاسم.
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
### getRevision() {#getRevision--}
```
public String getRevision()
```


الحصول على رقم المراجعة لهذا الأصل، يُستخدم عادةً في نظام التحكم بالإصدارات.

**Returns:**
java.lang.String - رقم المراجعة لهذا الأصل، يُستخدم عادةً في نظام التحكم بالإصدارات.
### getSubject() {#getSubject--}
```
public String getSubject()
```


الحصول على موضوع هذا الأصل

**Returns:**
java.lang.String - موضوع هذا الأصل
### getTitle() {#getTitle--}
```
public String getTitle()
```


الحصول على عنوان هذا الأصل

**Returns:**
java.lang.String - عنوان هذا الأصل
### getUnitName() {#getUnitName--}
```
public String getUnitName()
```


يحصل على وحدة الطول المستخدمة في هذا الأصل. مثال: سم/م/كم/بوصة/قدم

**Returns:**
java.lang.String - وحدة الطول المستخدمة في هذا الأصل. مثال: سم/م/كم/بوصة/قدم
### getUnitScaleFactor() {#getUnitScaleFactor--}
```
public double getUnitScaleFactor()
```


الحصول على معامل التحويل إلى المتر في العالم الحقيقي.

**Returns:**
double - عامل المقياس إلى المتر في العالم الحقيقي. **Remarks:** يتم تجاهل هذا أثناء التسلسل إذا كان اسم الوحدة فارغًا.
### getUpVector() {#getUpVector--}
```
public Axis getUpVector()
```


الحصول على المتجه العلوي المستخدم في هذا الأصل.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the up-vector used in this asset.
### getUrl() {#getUrl--}
```
public String getUrl()
```


الحصول على أو تعيين عنوان URL لهذا الأصل.

**Returns:**
java.lang.String - أو يضبط عنوان URL لهذا الأصل.
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
### setAmbient(Vector4 value) {#setAmbient-com.aspose.threed.Vector4-}
```
public void setAmbient(Vector4 value)
```


يحصل أو يضبط اللون المحيطي الافتراضي لهذا الأصل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector4](../../com.aspose.threed/vector4) | القيمة الجديدة |

### setApplicationName(String value) {#setApplicationName-java.lang.String-}
```
public void setApplicationName(String value)
```


تعيين التطبيق الذي أنشأ هذا الأصل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setApplicationVendor(String value) {#setApplicationVendor-java.lang.String-}
```
public void setApplicationVendor(String value)
```


تعيين اسم بائع التطبيق

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setApplicationVersion(String value) {#setApplicationVersion-java.lang.String-}
```
public void setApplicationVersion(String value)
```


تعيين نسخة التطبيق الذي أنشأ هذا الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


تعيين مؤلف هذا الأصل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


تعيين نظام الإحداثيات/المتجه العلوي/المتجه الأمامي لمعلومات الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | القيمة الجديدة |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


تعيين تعليق هذا الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setCoordinateSystem(CoordinateSystem value) {#setCoordinateSystem-com.aspose.threed.CoordinateSystem-}
```
public void setCoordinateSystem(CoordinateSystem value)
```


تعيين نظام الإحداثيات المستخدم في هذا الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | القيمة الجديدة |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


تعيين حقوق النشر للوثيقة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setCreationTime(Calendar value) {#setCreationTime-java.util.Calendar-}
```
public void setCreationTime(Calendar value)
```


الحصول على أو تعيين وقت إنشاء هذا الأصل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.Calendar | القيمة الجديدة |

### setFrontVector(Axis value) {#setFrontVector-com.aspose.threed.Axis-}
```
public void setFrontVector(Axis value)
```


تعيين المتجه الأمامي المستخدم في هذا الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | القيمة الجديدة |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


تعيين الكلمات المفتاحية لهذا الأصل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setModificationTime(Calendar value) {#setModificationTime-java.util.Calendar-}
```
public void setModificationTime(Calendar value)
```


الحصول على أو تعيين وقت التعديل لهذا الأصل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.Calendar | القيمة الجديدة |

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

### setRevision(String value) {#setRevision-java.lang.String-}
```
public void setRevision(String value)
```


تعيين رقم المراجعة لهذا الأصل، يُستخدم عادةً في نظام التحكم بالإصدارات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


تعيين موضوع هذا الأصل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


تعيين عنوان هذا الأصل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setUnitName(String value) {#setUnitName-java.lang.String-}
```
public void setUnitName(String value)
```


يضبط وحدة الطول المستخدمة في هذا الأصل. مثال: سم/م/كم/بوصة/قدم

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setUnitScaleFactor(double value) {#setUnitScaleFactor-double-}
```
public void setUnitScaleFactor(double value)
```


يضبط عامل المقياس إلى المتر في العالم الحقيقي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة **Remarks:** يتم تجاهل هذا أثناء التسلسل إذا كان اسم الوحدة فارغًا. |

### setUpVector(Axis value) {#setUpVector-com.aspose.threed.Axis-}
```
public void setUpVector(Axis value)
```


يضبط المتجه العلوي المستخدم في هذا الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | القيمة الجديدة |

### setUrl(String value) {#setUrl-java.lang.String-}
```
public void setUrl(String value)
```


الحصول على أو تعيين عنوان URL لهذا الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

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

