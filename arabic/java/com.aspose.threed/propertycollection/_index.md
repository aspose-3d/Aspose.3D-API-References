---
title: "مجموعة الخصائص"
second_title: "مرجع Aspose.3D لـ Java API"
description: "مجموعة الخصائص"
type: docs
weight: 140
url: /ar/java/com.aspose.threed/propertycollection/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class PropertyCollection implements Iterable<Property>
```

مجموعة الخصائص
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String property)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [get(int idx)](#get-int-) | يحصل على الخاصية حسب الفهرس. |
| [get(String property)](#get-java.lang.String-) | يحصل على قيمة الخاصية حسب اسم الخاصية. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | يرجع عدادًا يتنقل عبر المجموعة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | يزيل خاصية ديناميكية. |
| [set(String property, Object value)](#set-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية حسب اسم الخاصية. |
| [size()](#size--) | يحصل على عدد الخصائص المعلنة. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### findProperty(String property) {#findProperty-java.lang.String-}
```
public Property findProperty(String property)
```


يبحث عن الخاصية. يمكن أن تكون خاصية ديناميكية (تم إنشاؤها بواسطة CreateDynamicProperty/SetProperty) أو خاصية أصلية (محددة باسمها)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| خاصية | java.lang.String | اسم الخاصية. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### get(int idx) {#get-int-}
```
public Property get(int idx)
```


يحصل على الخاصية حسب الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| idx | int | الفهرس القائم على الصفر للخاصية |

**Returns:**
[Property](../../com.aspose.threed/property) - the property by index.
### get(String property) {#get-java.lang.String-}
```
public Object get(String property)
```


يحصل على قيمة الخاصية حسب اسم الخاصية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| خاصية | java.lang.String | اسم الخاصية |

**Returns:**
java.lang.Object - قيمة الخاصية
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public Iterator<Property> iterator()
```


يرجع عدادًا يتنقل عبر المجموعة.

**Returns:**
java.util.Iterator<com.aspose.threed.Property>
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


يزيل خاصية ديناميكية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| خاصية | java.lang.String | أي خاصية تريد إزالتها |

**Returns:**
boolean - true إذا تم إزالة الخاصية بنجاح
### set(String property, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String property, Object value)
```


يضبط قيمة الخاصية حسب اسم الخاصية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| خاصية | java.lang.String | اسم الخاصية |
| قيمة | java.lang.Object | قيمة جديدة |

### size() {#size--}
```
public int size()
```


يحصل على عدد الخصائص المعلنة.

**Returns:**
int - عدد الخصائص المعلنة.
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

