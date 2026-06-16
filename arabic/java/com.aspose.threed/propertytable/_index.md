---
title: "StructuralMetadata.PropertyTable"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "جدول الخصائص."
type: docs
weight: 14
url: /ar/java/com.aspose.threed/structuralmetadata.propertytable/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.PropertyTable
```

جدول الخصائص.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PropertyTable(String name, StructuralMetadata.ClassType mclass)](#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | منشئ جدول الخصائص. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addValue(StructuralMetadata.Property prop, Object value)](#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-) | أضف خاصية جديدة إلى جدول الخصائص. |
| [addValue(String propName, Object value)](#addValue-java.lang.String-java.lang.Object-) | أضف خاصية جديدة إلى جدول الخصائص. |
| [attach(VertexElementUserData userData)](#attach-com.aspose.threed.VertexElementUserData-) | إرفاق جدول الخصائص الحالي ببيانات المستخدم المحددة |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(VertexElementUserData userData)](#from-com.aspose.threed.VertexElementUserData-) | استخراج جدول الخصائص المرفق من بيانات المستخدم المحددة |
| [getClass()](#getClass--) |  |
| [getMetaClass()](#getMetaClass--) | فئة الميتا لهذا جدول الخصائص. |
| [getName()](#getName--) | اسم جدول الخصائص. |
| [getValue(String name)](#getValue-java.lang.String-) | يحصل على قيمة اسم الخاصية المحدد |
| [getValues()](#getValues--) | قيم جدول الخصائص. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PropertyTable(String name, StructuralMetadata.ClassType mclass) {#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-}
```
public PropertyTable(String name, StructuralMetadata.ClassType mclass)
```


منشئ جدول الخصائص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم نسخة هذا الجدول. |
| mclass | [ClassType](../../com.aspose.threed/classtype) | تعريف فئة الميتا لهذا جدول الخصائص |

### addValue(StructuralMetadata.Property prop, Object value) {#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-}
```
public void addValue(StructuralMetadata.Property prop, Object value)
```


أضف خاصية جديدة إلى جدول الخصائص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| prop | [Property](../../com.aspose.threed/property) | أي خاصية لإضافتها مع القيمة |
| القيمة | java.lang.Object | مصفوفة القيم |

### addValue(String propName, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String propName, Object value)
```


أضف خاصية جديدة إلى جدول الخصائص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| propName | java.lang.String | أي خاصية لإضافتها مع القيمة |
| القيمة | java.lang.Object | مصفوفة القيم |

### attach(VertexElementUserData userData) {#attach-com.aspose.threed.VertexElementUserData-}
```
public void attach(VertexElementUserData userData)
```


إرفاق جدول الخصائص الحالي ببيانات المستخدم المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) |  |

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
### from(VertexElementUserData userData) {#from-com.aspose.threed.VertexElementUserData-}
```
public static StructuralMetadata.PropertyTable from(VertexElementUserData userData)
```


استخراج جدول الخصائص المرفق من بيانات المستخدم المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) | بيانات المستخدم المرتبطة بجدول الخصائص |

**Returns:**
[PropertyTable](../../com.aspose.threed/propertytable) - The associated property table instance
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMetaClass() {#getMetaClass--}
```
public StructuralMetadata.ClassType getMetaClass()
```


فئة الميتا لهذا جدول الخصائص.

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - The meta class of this property table.
### getName() {#getName--}
```
public String getName()
```


اسم جدول الخصائص.

**Returns:**
java.lang.String - اسم جدول الخصائص.
### getValue(String name) {#getValue-java.lang.String-}
```
public Object getValue(String name)
```


يحصل على قيمة اسم الخاصية المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم الخاصية |

**Returns:**
java.lang.Object - قيمة الخاصية أو null إذا لم تُوجد
### getValues() {#getValues--}
```
public HashMap<String,Object> getValues()
```


قيم جدول الخصائص.

**Returns:**
java.util.HashMap<java.lang.String,java.lang.Object> - قيم جدول الخصائص.
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

