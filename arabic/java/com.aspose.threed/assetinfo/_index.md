---
title: "AssetInfo"
second_title: "مرجع Aspose.3D لـ Java API"
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

معلومات الأصل. يمكن إرفاق معلومات الأصل إلى [Scene](../../com.aspose.threed/scene). يمكن للـ [Scene](../../com.aspose.threed/scene) الفرعي أن يمتلك [AssetInfo](../../com.aspose.threed/assetinfo) الخاص به لتجاوز تعريف الأصل الأصلي. **Example:** يوضح الكود التالي كيفية قراءة معلومات الأصل من ملف fbx:

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
| [AssetInfo()](#AssetInfo--) | يُنشئ مثيلًا جديدًا من الفئة [AssetInfo](../../com.aspose.threed/assetinfo). |
| [AssetInfo(String name)](#AssetInfo-java.lang.String-) | يُنشئ مثيلًا جديدًا من الفئة [AssetInfo](../../com.aspose.threed/assetinfo). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getAmbient()](#getAmbient--) | يحصل أو يضبط اللون المحيطي الافتراضي لهذا الأصل |
| [getApplicationName()](#getApplicationName--) | يحصل على التطبيق الذي أنشأ هذا الأصل |
| [getApplicationVendor()](#getApplicationVendor--) | يحصل على اسم بائع التطبيق |
| [getApplicationVersion()](#getApplicationVersion--) | يحصل على إصدار التطبيق الذي أنشأ هذا الأصل. |
| [getAuthor()](#getAuthor--) | يحصل على مؤلف هذا الأصل |
| [getAxisSystem()](#getAxisSystem--) | يحصل على نظام الإحداثيات/متجه الارتفاع/متجه الأمام لمعلومات الأصل. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | يحصل على تعليق هذا الأصل. |
| [getCoordinateSystem()](#getCoordinateSystem--) | يحصل على نظام الإحداثيات المستخدم في هذا الأصل. |
| [getCopyright()](#getCopyright--) | يحصل على حقوق النشر للوثيقة |
| [getCreationTime()](#getCreationTime--) | يحصل أو يضبط وقت الإنشاء لهذا الأصل |
| [getFrontVector()](#getFrontVector--) | يحصل على المتجه الأمامي المستخدم في هذا الأصل. |
| [getKeywords()](#getKeywords--) | يحصل على الكلمات المفتاحية لهذا الأصل |
| [getModificationTime()](#getModificationTime--) | يحصل أو يضبط وقت التعديل لهذا الأصل |
| [getName()](#getName--) | يحصل على الاسم. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getRevision()](#getRevision--) | يحصل على رقم المراجعة لهذا الأصل، يُستخدم عادةً في نظام التحكم بالإصدارات. |
| [getSubject()](#getSubject--) | يحصل على موضوع هذا الأصل |
| [getTitle()](#getTitle--) | يحصل على عنوان هذا الأصل |
| [getUnitName()](#getUnitName--) | يحصل على وحدة الطول المستخدمة في هذا الأصل. |
| [getUnitScaleFactor()](#getUnitScaleFactor--) | يحصل على معامل التحجيم إلى المتر في العالم الحقيقي. |
| [getUpVector()](#getUpVector--) | يحصل على المتجه العلوي المستخدم في هذا الأصل. |
| [getUrl()](#getUrl--) | يحصل أو يضبط عنوان URL لهذا الأصل. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | أزل الخاصية المحددة بالاسم |
| [setAmbient(Vector4 value)](#setAmbient-com.aspose.threed.Vector4-) | يحصل أو يضبط اللون المحيطي الافتراضي لهذا الأصل |
| [setApplicationName(String value)](#setApplicationName-java.lang.String-) | يضبط التطبيق الذي أنشأ هذا الأصل |
| [setApplicationVendor(String value)](#setApplicationVendor-java.lang.String-) | يضبط اسم بائع التطبيق |
| [setApplicationVersion(String value)](#setApplicationVersion-java.lang.String-) | يضبط نسخة التطبيق الذي أنشأ هذا الأصل. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | يضبط مؤلف هذا الأصل |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | يضبط نظام الإحداثيات/المتجه العلوي/المتجه الأمامي لمعلومات الأصل. |
| [setComment(String value)](#setComment-java.lang.String-) | يضبط تعليق هذا الأصل. |
| [setCoordinateSystem(CoordinateSystem value)](#setCoordinateSystem-com.aspose.threed.CoordinateSystem-) | يضبط نظام الإحداثيات المستخدم في هذا الأصل. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | يضبط حقوق النشر للوثيقة |
| [setCreationTime(Calendar value)](#setCreationTime-java.util.Calendar-) | يحصل أو يضبط وقت الإنشاء لهذا الأصل |
| [setFrontVector(Axis value)](#setFrontVector-com.aspose.threed.Axis-) | يضبط المتجه الأمامي المستخدم في هذا الأصل. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | يضبط الكلمات المفتاحية لهذا الأصل |
| [setModificationTime(Calendar value)](#setModificationTime-java.util.Calendar-) | يحصل أو يضبط وقت التعديل لهذا الأصل |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setRevision(String value)](#setRevision-java.lang.String-) | يضبط رقم المراجعة لهذا الأصل، يُستخدم عادةً في نظام التحكم بالإصدارات. |
| [setSubject(String value)](#setSubject-java.lang.String-) | يضبط موضوع هذا الأصل |
| [setTitle(String value)](#setTitle-java.lang.String-) | يضبط عنوان هذا الأصل |
| [setUnitName(String value)](#setUnitName-java.lang.String-) | يضبط وحدة الطول المستخدمة في هذا الأصل. |
| [setUnitScaleFactor(double value)](#setUnitScaleFactor-double-) | يضبط معامل المقياس إلى المتر في العالم الحقيقي. |
| [setUpVector(Axis value)](#setUpVector-com.aspose.threed.Axis-) | يضبط المتجه العلوي المستخدم في هذا الأصل. |
| [setUrl(String value)](#setUrl-java.lang.String-) | يحصل أو يضبط عنوان URL لهذا الأصل. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AssetInfo() {#AssetInfo--}
```
public AssetInfo()
```


يُنشئ مثيلًا جديدًا من الفئة [AssetInfo](../../com.aspose.threed/assetinfo).

### AssetInfo(String name) {#AssetInfo-java.lang.String-}
```
public AssetInfo(String name)
```


يُنشئ مثيلًا جديدًا من الفئة [AssetInfo](../../com.aspose.threed/assetinfo).

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


يبحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (تم إنشاؤها بواسطة CreateDynamicProperty/SetProperty) أو خاصية أصلية (محددة باسمها)

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


يحصل على إصدار التطبيق الذي أنشأ هذا الأصل.

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


يحصل أو يضبط وقت الإنشاء لهذا الأصل

**Returns:**
java.util.Calendar - أو يضبط وقت إنشاء هذا الأصل
### getFrontVector() {#getFrontVector--}
```
public Axis getFrontVector()
```


يحصل على المتجه الأمامي المستخدم في هذا الأصل.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front-vector used in this asset.
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


يحصل على الكلمات المفتاحية لهذا الأصل

**Returns:**
java.lang.String - الكلمات المفتاحية لهذا الأصل
### getModificationTime() {#getModificationTime--}
```
public Calendar getModificationTime()
```


يحصل أو يضبط وقت التعديل لهذا الأصل

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


يحصل على رقم المراجعة لهذا الأصل، يُستخدم عادةً في نظام التحكم بالإصدارات.

**Returns:**
java.lang.String - رقم المراجعة لهذا الأصل، يُستخدم عادةً في نظام التحكم بالإصدارات.
### getSubject() {#getSubject--}
```
public String getSubject()
```


يحصل على موضوع هذا الأصل

**Returns:**
java.lang.String - موضوع هذا الأصل
### getTitle() {#getTitle--}
```
public String getTitle()
```


يحصل على عنوان هذا الأصل

**Returns:**
java.lang.String - عنوان هذا الأصل
### getUnitName() {#getUnitName--}
```
public String getUnitName()
```


يسترجع وحدة الطول المستخدمة في هذا الأصل. مثال: سم/م/كم/إنش/قدم

**Returns:**
java.lang.String - وحدة الطول المستخدمة في هذا الأصل. مثال: سم/م/كم/إنش/قدم
### getUnitScaleFactor() {#getUnitScaleFactor--}
```
public double getUnitScaleFactor()
```


يحصل على معامل التحجيم إلى المتر في العالم الحقيقي.

**Returns:**
double - معامل المقياس إلى المتر في العالم الحقيقي. **Remarks:** يتم تجاهل هذا أثناء التسلسل إذا كان اسم الوحدة فارغًا.
### getUpVector() {#getUpVector--}
```
public Axis getUpVector()
```


يحصل على المتجه العلوي المستخدم في هذا الأصل.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the up-vector used in this asset.
### getUrl() {#getUrl--}
```
public String getUrl()
```


يحصل أو يضبط عنوان URL لهذا الأصل.

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


أزل الخاصية المحددة بالاسم

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
| value | [Vector4](../../com.aspose.threed/vector4) | قيمة جديدة |

### setApplicationName(String value) {#setApplicationName-java.lang.String-}
```
public void setApplicationName(String value)
```


يضبط التطبيق الذي أنشأ هذا الأصل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | قيمة جديدة |

### setApplicationVendor(String value) {#setApplicationVendor-java.lang.String-}
```
public void setApplicationVendor(String value)
```


يضبط اسم بائع التطبيق

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | قيمة جديدة |

### setApplicationVersion(String value) {#setApplicationVersion-java.lang.String-}
```
public void setApplicationVersion(String value)
```


يضبط نسخة التطبيق الذي أنشأ هذا الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | قيمة جديدة |

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


يضبط مؤلف هذا الأصل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | قيمة جديدة |

### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


يضبط نظام الإحداثيات/المتجه العلوي/المتجه الأمامي لمعلومات الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | قيمة جديدة |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


يضبط تعليق هذا الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | قيمة جديدة |

### setCoordinateSystem(CoordinateSystem value) {#setCoordinateSystem-com.aspose.threed.CoordinateSystem-}
```
public void setCoordinateSystem(CoordinateSystem value)
```


يضبط نظام الإحداثيات المستخدم في هذا الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | قيمة جديدة |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


يضبط حقوق النشر للوثيقة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | قيمة جديدة |

### setCreationTime(Calendar value) {#setCreationTime-java.util.Calendar-}
```
public void setCreationTime(Calendar value)
```


يحصل أو يضبط وقت الإنشاء لهذا الأصل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.Calendar | قيمة جديدة |

### setFrontVector(Axis value) {#setFrontVector-com.aspose.threed.Axis-}
```
public void setFrontVector(Axis value)
```


يضبط المتجه الأمامي المستخدم في هذا الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | قيمة جديدة |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


يضبط الكلمات المفتاحية لهذا الأصل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | قيمة جديدة |

### setModificationTime(Calendar value) {#setModificationTime-java.util.Calendar-}
```
public void setModificationTime(Calendar value)
```


يحصل أو يضبط وقت التعديل لهذا الأصل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.Calendar | قيمة جديدة |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


يضبط الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | قيمة جديدة |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


يضبط قيمة الخاصية المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| خاصية | java.lang.String | اسم الخاصية |
| قيمة | java.lang.Object | قيمة الخاصية |

### setRevision(String value) {#setRevision-java.lang.String-}
```
public void setRevision(String value)
```


يضبط رقم المراجعة لهذا الأصل، يُستخدم عادةً في نظام التحكم بالإصدارات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | قيمة جديدة |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


يضبط موضوع هذا الأصل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | قيمة جديدة |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


يضبط عنوان هذا الأصل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | قيمة جديدة |

### setUnitName(String value) {#setUnitName-java.lang.String-}
```
public void setUnitName(String value)
```


يضبط وحدة الطول المستخدمة في هذا الأصل. مثال: سم/م/كم/إنش/قدم

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | قيمة جديدة |

### setUnitScaleFactor(double value) {#setUnitScaleFactor-double-}
```
public void setUnitScaleFactor(double value)
```


يضبط معامل المقياس إلى المتر في العالم الحقيقي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | القيمة الجديدة **Remarks:** يتم تجاهل هذا أثناء التسلسل إذا كان اسم الوحدة فارغًا. |

### setUpVector(Axis value) {#setUpVector-com.aspose.threed.Axis-}
```
public void setUpVector(Axis value)
```


يضبط المتجه العلوي المستخدم في هذا الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | قيمة جديدة |

### setUrl(String value) {#setUrl-java.lang.String-}
```
public void setUrl(String value)
```


يحصل أو يضبط عنوان URL لهذا الأصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | قيمة جديدة |

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

