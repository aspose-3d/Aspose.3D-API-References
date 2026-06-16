---
title: "MorphTargetDeformer"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "يوفر MorphTargetDeformer رسومًا متحركة لكل رأس."
type: docs
weight: 108
url: /ar/java/com.aspose.threed/morphtargetdeformer/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Deformer](../../com.aspose.threed/deformer)
```
public class MorphTargetDeformer extends Deformer
```

MorphTargetDeformer يوفر تحريكًا لكل رأس. MorphTargetDeformer ينظم جميع الأهداف عبر [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel)، كل قناة يمكنها تنظيم أهداف متعددة. الاستخدام الشائع لمشغل الهدف المتحول هو تطبيق تعبيرات الوجه على شخصية. يمكن العثور على مزيد من التفاصيل في https://en.wikipedia.org/wiki/Morph\_target\_animation
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [MorphTargetDeformer(String name)](#MorphTargetDeformer-java.lang.String-) | ينشئ مثيلًا جديدًا من الفئة [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer). |
| [MorphTargetDeformer()](#MorphTargetDeformer--) | ينشئ مثيلًا جديدًا من الفئة [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | يحصل على الوزن للهيكلية المعطاة، هذه طريقة مختصرة لتعديل الوزن للهدف دون الوصول إلى القناة. |
| [getChannels()](#getChannels--) | يحصل على جميع القنوات الموجودة في هذا المشغل |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | يحصل على الاسم. |
| [getOwner()](#getOwner--) | يرجع الهندسة التي تملك هذا deformer |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | يضبط الوزن للهيكلية المعطاة، هذه طريقة مختصرة لتعديل الوزن للهدف دون الوصول إلى القناة. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetDeformer(String name) {#MorphTargetDeformer-java.lang.String-}
```
public MorphTargetDeformer(String name)
```


ينشئ مثيلًا جديدًا من الفئة [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم. |

### MorphTargetDeformer() {#MorphTargetDeformer--}
```
public MorphTargetDeformer()
```


ينشئ مثيلًا جديدًا من الفئة [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer).

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
### get(Shape target) {#get-com.aspose.threed.Shape-}
```
public double get(Shape target)
```


يحصل على الوزن للهيكلية المعطاة، هذه طريقة مختصرة لتعديل الوزن للهدف دون الوصول إلى القناة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | الهندسة المستهدفة |

**Returns:**
double - الوزن
### getChannels() {#getChannels--}
```
public List<MorphTargetChannel> getChannels()
```


يحصل على جميع القنوات الموجودة في هذا المشغل

**Returns:**
java.util.List<com.aspose.threed.MorphTargetChannel> - جميع القنوات الموجودة في هذا المشوه
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName() {#getName--}
```
public String getName()
```


يحصل على الاسم.

**Returns:**
java.lang.String - الاسم.
### getOwner() {#getOwner--}
```
public Geometry getOwner()
```


يرجع الهندسة التي تملك هذا deformer

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - the geometry which owns this deformer
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
### set(Shape target, double value) {#set-com.aspose.threed.Shape-double-}
```
public void set(Shape target, double value)
```


يضبط الوزن للهيكلية المعطاة، هذه طريقة مختصرة لتعديل الوزن للهدف دون الوصول إلى القناة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | الهندسة المستهدفة |
| القيمة | double | القيمة الجديدة |

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

