---
title: "StructuralMetadata"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "هذه الفئة توفر الدعم لـ EXT_structural_metadata المستخدمة فقط في glTF."
type: docs
weight: 180
url: /ar/java/com.aspose.threed/structuralmetadata/
---

**Inheritance:**
java.lang.Object
```
public class StructuralMetadata
```

توفر هذه الفئة دعمًا لـ EXT\_structural\_metadata، وتُستخدم فقط في glTF.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [StructuralMetadata()](#StructuralMetadata--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [attach(Scene scene)](#attach-com.aspose.threed.Scene-) | إرفاق البيانات الوصفية الحالية بالمشهد المحدد |
| [createClass(String name)](#createClass-java.lang.String-) | إنشاء نوع فئة وصفية |
| [createEnum(String name)](#createEnum-java.lang.String-) | إنشاء نوع تعداد |
| [createPropertyTable(String name, StructuralMetadata.ClassType clazz)](#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | إنشاء جدول خصائص جديد بنوع الفئة الوصفية المعطى |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(Scene scene)](#from-com.aspose.threed.Scene-) | احصل على [StructuralMetadata](../../com.aspose.threed/structuralmetadata) المرتبط بالمشهد المحدد. |
| [getClass()](#getClass--) |  |
| [getClasses()](#getClasses--) | تعريفات الفئة. |
| [getEnums()](#getEnums--) | تعريفات نوع التعداد |
| [getPropertyTables()](#getPropertyTables--) | جداول الخصائص في هذه البيانات الوصفية. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StructuralMetadata() {#StructuralMetadata--}
```
public StructuralMetadata()
```


### attach(Scene scene) {#attach-com.aspose.threed.Scene-}
```
public void attach(Scene scene)
```


إرفاق البيانات الوصفية الحالية بالمشهد المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### createClass(String name) {#createClass-java.lang.String-}
```
public StructuralMetadata.ClassType createClass(String name)
```


إنشاء نوع فئة وصفية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم الفئة |

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - Instance of the meta class
### createEnum(String name) {#createEnum-java.lang.String-}
```
public StructuralMetadata.EnumType createEnum(String name)
```


إنشاء نوع تعداد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم نوع التعداد |

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - Instance of the enum type
### createPropertyTable(String name, StructuralMetadata.ClassType clazz) {#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-}
```
public StructuralMetadata.PropertyTable createPropertyTable(String name, StructuralMetadata.ClassType clazz)
```


إنشاء جدول خصائص جديد بنوع الفئة الوصفية المعطى

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم جدول الخصائص |
| clazz | [ClassType](../../com.aspose.threed/classtype) | نوع الفئة لجدول الخصائص الجديد |

**Returns:**
[PropertyTable](../../com.aspose.threed/propertytable) - The new instance of property table
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
### from(Scene scene) {#from-com.aspose.threed.Scene-}
```
public static StructuralMetadata from(Scene scene)
```


احصل على [StructuralMetadata](../../com.aspose.threed/structuralmetadata) المرتبط بالمشهد المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | المشهد الذي يجب البحث فيه عن البيانات الوصفية الهيكلية |

**Returns:**
[StructuralMetadata](../../com.aspose.threed/structuralmetadata) - A valid instance of [StructuralMetadata](../../com.aspose.threed/structuralmetadata) if its found in the scene, otherwise null returned
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClasses() {#getClasses--}
```
public HashMap<String,StructuralMetadata.ClassType> getClasses()
```


تعريفات الفئة.

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.ClassType> - تعريفات الفئات.
### getEnums() {#getEnums--}
```
public HashMap<String,StructuralMetadata.EnumType> getEnums()
```


تعريفات نوع التعداد

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.EnumType> - تعريفات نوع التعداد
### getPropertyTables() {#getPropertyTables--}
```
public ArrayList<StructuralMetadata.PropertyTable> getPropertyTables()
```


جداول الخصائص في هذه البيانات الوصفية.

**Returns:**
java.util.ArrayList<com.aspose.threed.StructuralMetadata.PropertyTable> - جداول الخصائص في هذه البيانات الوصفية.
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

