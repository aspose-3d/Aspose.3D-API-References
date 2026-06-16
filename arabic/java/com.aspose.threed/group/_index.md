---
title: "مجموعة"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "A  يمثل العلاقات المنطقية لـ ."
type: docs
weight: 75
url: /ar/java/com.aspose.threed/group/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Group extends A3DObject
```

A [Group](../../com.aspose.threed/group) يمثل العلاقات المنطقية لـ [Node](../../com.aspose.threed/node).
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Group(String name)](#Group-java.lang.String-) | إنشاء نسخة جديدة من [Group](../../com.aspose.threed/group) |
| [Group()](#Group--) | إنشاء نسخة جديدة من [Group](../../com.aspose.threed/group) |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getClass()](#getClass--) |  |
| [getGroups()](#getGroups--) | المجموعات الفرعية |
| [getName()](#getName--) | يحصل على الاسم. |
| [getNodes()](#getNodes--) | العقد في هذه المجموعة |
| [getParent()](#getParent--) | المجموعة الأصلية للمجموعة الحالية |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [toString()](#toString--) | يحصل على تمثيل السلسلة النصية لـ [Group](../../com.aspose.threed/group) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Group(String name) {#Group-java.lang.String-}
```
public Group(String name)
```


إنشاء نسخة جديدة من [Group](../../com.aspose.threed/group)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم المجموعة |

### Group() {#Group--}
```
public Group()
```


إنشاء نسخة جديدة من [Group](../../com.aspose.threed/group)

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGroups() {#getGroups--}
```
public List<Group> getGroups()
```


المجموعات الفرعية

**Returns:**
java.util.List<com.aspose.threed.Group> - المجموعات الفرعية
### getName() {#getName--}
```
public String getName()
```


يحصل على الاسم.

**Returns:**
java.lang.String - الاسم.
### getNodes() {#getNodes--}
```
public List<Node> getNodes()
```


العقد في هذه المجموعة

**Returns:**
java.util.List<com.aspose.threed.Node> - العقد في هذه المجموعة
### getParent() {#getParent--}
```
public Group getParent()
```


المجموعة الأصلية للمجموعة الحالية

**Returns:**
[Group](../../com.aspose.threed/group) - Parent group of current group
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


يحصل على تمثيل السلسلة النصية لـ [Group](../../com.aspose.threed/group)

**Returns:**
java.lang.String - تمثيل السلسلة النصية للنسخة الحالية
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

