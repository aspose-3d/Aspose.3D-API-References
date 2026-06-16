---
title: "StructuralMetadata.Property"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "تعريف الخاصية في فئات البيانات الوصفية"
type: docs
weight: 13
url: /ar/java/com.aspose.threed/structuralmetadata.property/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.Property
```

تعريف الخاصية في فئات البيانات الوصفية
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-) | منشئ خاصية البيانات الوصفية |
| [Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) | منشئ خاصية البيانات الوصفية |
| [Property(String name, Class<?> type)](#Property-java.lang.String-java.lang.Class----) | منشئ خاصية البيانات الوصفية |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | عدد البيانات للمصفوفة ذات الحجم الثابت. |
| [getDescription()](#getDescription--) | وصف الخاصية |
| [getDisplayName()](#getDisplayName--) | اسم الخاصية، يُستخدم من قبل واجهة المستخدم للتمثيل. |
| [getEnumType()](#getEnumType--) | نوع التعداد |
| [getName()](#getName--) | الاسم الفريد للخاصية |
| [getNormalized()](#getNormalized--) | هل تم تطبيع البيانات. |
| [getType()](#getType--) | نوع بيانات الخاصية |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(Integer value)](#setCount-java.lang.Integer-) | عدد البيانات للمصفوفة ذات الحجم الثابت. |
| [setDescription(String value)](#setDescription-java.lang.String-) | وصف الخاصية |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | اسم الخاصية، يُستخدم من قبل واجهة المستخدم للتمثيل. |
| [setEnumType(StructuralMetadata.EnumType value)](#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-) | نوع التعداد |
| [setNormalized(boolean value)](#setNormalized-boolean-) | هل تم تطبيع البيانات. |
| [toString()](#toString--) | يحصل على تمثيل النصي لهذه النسخة. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)
```


منشئ خاصية البيانات الوصفية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم الفريد للخاصية |
| displayName | java.lang.String | اسم الخاصية، يُستخدم من قبل واجهة المستخدم للتمثيل. |
| description | java.lang.String | وصف الخاصية |
| type | java.lang.Class<?> | نوع بيانات الخاصية |
| normalized | boolean | هل البيانات مُطَبَّعة |
| عدد | java.lang.Integer | عدد البيانات للمصفوفة ذات الحجم الثابت |

### Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)
```


منشئ خاصية البيانات الوصفية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم الفريد للخاصية |
| displayName | java.lang.String | اسم الخاصية، يُستخدم من قبل واجهة المستخدم للتمثيل. |
| description | java.lang.String | وصف الخاصية |
| type | [EnumType](../../com.aspose.threed/enumtype) | نوع بيانات الخاصية |
| مصفوفة | boolean | هل كل قيمة خاصية هي مصفوفة أم عددية |
| عدد | java.lang.Integer | عدد البيانات للمصفوفة ذات الحجم الثابت |

### Property(String name, Class<?> type) {#Property-java.lang.String-java.lang.Class----}
```
public Property(String name, Class<?> type)
```


منشئ خاصية البيانات الوصفية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم الفريد للخاصية |
| type | java.lang.Class<?> | نوع بيانات الخاصية |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public Integer getCount()
```


عدد البيانات للمصفوفة ذات الحجم الثابت.

**Returns:**
java.lang.Integer - عدد البيانات للمصفوفة ذات الحجم الثابت.
### getDescription() {#getDescription--}
```
public String getDescription()
```


وصف الخاصية

**Returns:**
java.lang.String - وصف الخاصية
### getDisplayName() {#getDisplayName--}
```
public String getDisplayName()
```


اسم الخاصية، يُستخدم من قبل واجهة المستخدم للتمثيل.

**Returns:**
java.lang.String - اسم الخاصية، يُستخدم من قبل واجهة المستخدم للتمثيل.
### getEnumType() {#getEnumType--}
```
public StructuralMetadata.EnumType getEnumType()
```


نوع التعداد

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - The enum type
### getName() {#getName--}
```
public String getName()
```


الاسم الفريد للخاصية

**Returns:**
java.lang.String - الاسم الفريد للخاصية
### getNormalized() {#getNormalized--}
```
public boolean getNormalized()
```


هل تم تطبيع البيانات.

**Returns:**
boolean - هل البيانات مُعَدلَة.
### getType() {#getType--}
```
public Class<?> getType()
```


نوع بيانات الخاصية

**Returns:**
java.lang.Class<?> - نوع البيانات للخاصية
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




### setCount(Integer value) {#setCount-java.lang.Integer-}
```
public void setCount(Integer value)
```


عدد البيانات للمصفوفة ذات الحجم الثابت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.Integer | القيمة الجديدة |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


وصف الخاصية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public void setDisplayName(String value)
```


اسم الخاصية، يُستخدم من قبل واجهة المستخدم للتمثيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setEnumType(StructuralMetadata.EnumType value) {#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-}
```
public void setEnumType(StructuralMetadata.EnumType value)
```


نوع التعداد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EnumType](../../com.aspose.threed/enumtype) | القيمة الجديدة |

### setNormalized(boolean value) {#setNormalized-boolean-}
```
public void setNormalized(boolean value)
```


هل تم تطبيع البيانات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### toString() {#toString--}
```
public String toString()
```


يحصل على تمثيل النصي لهذه النسخة.

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

