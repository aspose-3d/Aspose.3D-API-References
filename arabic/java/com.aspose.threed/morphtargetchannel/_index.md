---
title: "MorphTargetChannel"
second_title: "مرجع Aspose.3D لـ Java API"
description: "يُستخدم MorphTargetChannel بواسطة  لتنظيم الهندسات الهدف."
type: docs
weight: 107
url: /ar/java/com.aspose.threed/morphtargetchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class MorphTargetChannel extends A3DObject
```

يُستخدم MorphTargetChannel بواسطة [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) لتنظيم الهندسات الهدف. بعض صيغ الملفات مثل FBX تدعم قنوات متعددة بالتوازي. **Remarks:** الوزن بين 0 و 1.0، والوزن الافتراضي للهدف هو 0.0؛
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [MorphTargetChannel(String name)](#MorphTargetChannel-java.lang.String-) | ينشئ مثيلاً جديداً من الفئة [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel). |
| [MorphTargetChannel()](#MorphTargetChannel--) | ينشئ مثيلاً جديداً من الفئة [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel). |
## الحقول

| حقل | الوصف |
| --- | --- |
| [DEFAULT_WEIGHT](#DEFAULT-WEIGHT) | الوزن الافتراضي للهدف التشكيلي. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | يحصل على الوزن للهيكل المحدد |
| [getChannelWeight()](#getChannelWeight--) | يحصل على وزن المشوه لهذه القناة. |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | يحصل على الاسم. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getTargets()](#getTargets--) | يحصل على جميع الأهداف المرتبطة بالقناة. |
| [getWeight(Shape target)](#getWeight-com.aspose.threed.Shape-) | يحصل على الوزن للهدف المحدد، إذا لم يكن الهدف تابعًا لهذه القناة، يتم إرجاع القيمة الافتراضية 0. |
| [getWeights()](#getWeights--) | يحصل على القيم الكاملة للوزن لأشكال الأهداف. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | أزل الخاصية المحددة بالاسم |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | يضبط الوزن للهيكل المحدد. |
| [setChannelWeight(double value)](#setChannelWeight-double-) | يضبط وزن المشوه لهذه القناة. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setWeight(Shape target)](#setWeight-com.aspose.threed.Shape-) | يضبط الوزن للهدف المحدد، القيمة الافتراضية هي 1، يجب أن يكون النطاق بين 0~1. |
| [setWeight(Shape target, double weight)](#setWeight-com.aspose.threed.Shape-double-) | يضبط الوزن للهدف المحدد، القيمة الافتراضية هي 1، يجب أن يكون النطاق بين 0~1. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetChannel(String name) {#MorphTargetChannel-java.lang.String-}
```
public MorphTargetChannel(String name)
```


ينشئ مثيلاً جديداً من الفئة [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم. |

### MorphTargetChannel() {#MorphTargetChannel--}
```
public MorphTargetChannel()
```


ينشئ مثيلاً جديداً من الفئة [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel).

### DEFAULT_WEIGHT {#DEFAULT-WEIGHT}
```
public static final double DEFAULT_WEIGHT
```


الوزن الافتراضي للهدف التشكيلي.

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
### get(Shape target) {#get-com.aspose.threed.Shape-}
```
public double get(Shape target)
```


يحصل على الوزن للهيكل المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | الهيكل الهدف. |

**Returns:**
double - الوزن
### getChannelWeight() {#getChannelWeight--}
```
public double getChannelWeight()
```


يحصل على وزن المشوه لهذه القناة. الوزن بين 0.0 و 1.0

**Returns:**
double - وزن المشوه لهذه القناة. الوزن بين 0.0 و 1.0
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
### getTargets() {#getTargets--}
```
public List<Shape> getTargets()
```


يحصل على جميع الأهداف المرتبطة بالقناة.

**Returns:**
java.util.List<com.aspose.threed.Shape> - جميع الأهداف المرتبطة بالقناة.
### getWeight(Shape target) {#getWeight-com.aspose.threed.Shape-}
```
public double getWeight(Shape target)
```


يحصل على الوزن للهدف المحدد، إذا لم يكن الهدف تابعًا لهذه القناة، يتم إرجاع القيمة الافتراضية 0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

**Returns:**
double
### getWeights() {#getWeights--}
```
public List<Double> getWeights()
```


يحصل على القيم الكاملة للوزن لأشكال الأهداف.

**Returns:**
java.util.List<java.lang.Double> - القيم الكاملة للوزن لأشكال الأهداف.
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
### set(Shape target, double value) {#set-com.aspose.threed.Shape-double-}
```
public void set(Shape target, double value)
```


يضبط الوزن للهيكل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | الهيكل الهدف. |
| قيمة | double | قيمة جديدة |

### setChannelWeight(double value) {#setChannelWeight-double-}
```
public void setChannelWeight(double value)
```


يضبط وزن المشوه لهذه القناة. الوزن بين 0.0 و 1.0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | قيمة جديدة |

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

### setWeight(Shape target) {#setWeight-com.aspose.threed.Shape-}
```
public void setWeight(Shape target)
```


يضبط الوزن للهدف المحدد، القيمة الافتراضية هي 1، يجب أن يكون النطاق بين 0~1.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

### setWeight(Shape target, double weight) {#setWeight-com.aspose.threed.Shape-double-}
```
public void setWeight(Shape target, double weight)
```


يضبط الوزن للهدف المحدد، القيمة الافتراضية هي 1، يجب أن يكون النطاق بين 0~1.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |
| الوزن | double |  |

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

