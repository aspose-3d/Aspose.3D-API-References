---
title: "KeyframeSequence"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "تسلسل الإطارات المفتاحية يصف تحويل القيمة المأخوذة على مدار الوقت."
type: docs
weight: 90
url: /ar/java/com.aspose.threed/keyframesequence/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)

**All Implemented Interfaces:**
java.lang.Iterable
```
public class KeyframeSequence extends A3DObject implements Iterable<KeyFrame>
```

تسلسل الإطارات الرئيسية يصف تحول القيمة المعيّنة مع مرور الوقت.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [KeyframeSequence(String name)](#KeyframeSequence-java.lang.String-) | ينشئ مثيلًا جديدًا من الفئة [KeyframeSequence](../../com.aspose.threed/keyframesequence). |
| [KeyframeSequence()](#KeyframeSequence--) | ينشئ مثيلًا جديدًا من الفئة [KeyframeSequence](../../com.aspose.threed/keyframesequence). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [add(double time, float value)](#add-double-float-) | إنشاء إطار مفتاح جديد بالقيمة المحددة |
| [add(double time, float value, Interpolation interpolation)](#add-double-float-com.aspose.threed.Interpolation-) | إنشاء إطار مفتاح جديد بالقيمة المحددة |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getBindPoint()](#getBindPoint--) | يحصل على نقطة ربط الخاصية التي تمتلك هذا المنحنى |
| [getClass()](#getClass--) |  |
| [getKeyFrames()](#getKeyFrames--) | يحصل على الإطارات المفتاحية لهذا المنحنى. |
| [getName()](#getName--) | يحصل على الاسم. |
| [getPostBehavior()](#getPostBehavior--) | يحصل على سلوك ما بعد الإطار المفتاحي، والذي يحدد ما يجب أن تكون عليه القيمة المأخوذة بعد الإطار المفتاحي الأخير. |
| [getPreBehavior()](#getPreBehavior--) | يحصل على سلوك ما قبل الإطار المفتاحي، والذي يحدد ما يجب أن تكون عليه القيمة المأخوذة قبل الإطار المفتاحي الأول. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | يحصل على المُعدِّد لتصفح جميع الإطارات المفتاحية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [reset()](#reset--) | يزيل جميع الإطارات المفتاحية ويعيد تعيين سلوكيات ما بعد/ما قبل. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### KeyframeSequence(String name) {#KeyframeSequence-java.lang.String-}
```
public KeyframeSequence(String name)
```


ينشئ مثيلًا جديدًا من الفئة [KeyframeSequence](../../com.aspose.threed/keyframesequence).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم |

### KeyframeSequence() {#KeyframeSequence--}
```
public KeyframeSequence()
```


ينشئ مثيلًا جديدًا من الفئة [KeyframeSequence](../../com.aspose.threed/keyframesequence).

### add(double time, float value) {#add-double-float-}
```
public void add(double time, float value)
```


إنشاء إطار مفتاح جديد بالقيمة المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الوقت | double | موضع الوقت (مقاس بالثواني) |
| القيمة | float | القيمة عند موضع الوقت هذا |

### add(double time, float value, Interpolation interpolation) {#add-double-float-com.aspose.threed.Interpolation-}
```
public void add(double time, float value, Interpolation interpolation)
```


إنشاء إطار مفتاح جديد بالقيمة المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الوقت | double | موضع الوقت (مقاس بالثواني) |
| القيمة | float | القيمة عند موضع الوقت هذا |
| interpolation | [Interpolation](../../com.aspose.threed/interpolation) | نوع الاستيفاء لهذا الإطار المفتاحي |

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
### getBindPoint() {#getBindPoint--}
```
public BindPoint getBindPoint()
```


يحصل على نقطة ربط الخاصية التي تمتلك هذا المنحنى

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - the property bind point which owns this curve
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyFrames() {#getKeyFrames--}
```
public List<KeyFrame> getKeyFrames()
```


يحصل على الإطارات المفتاحية لهذا المنحنى.

**Returns:**
java.util.List<com.aspose.threed.KeyFrame> - إطارات المفتاح لهذا المنحنى.
### getName() {#getName--}
```
public String getName()
```


يحصل على الاسم.

**Returns:**
java.lang.String - الاسم.
### getPostBehavior() {#getPostBehavior--}
```
public Extrapolation getPostBehavior()
```


يحصل على سلوك ما بعد الإطار المفتاحي، والذي يحدد ما يجب أن تكون عليه القيمة المأخوذة بعد الإطار المفتاحي الأخير.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the post behavior indicates what the sampled value should be after the last key frame.
### getPreBehavior() {#getPreBehavior--}
```
public Extrapolation getPreBehavior()
```


يحصل على سلوك ما قبل الإطار المفتاحي، والذي يحدد ما يجب أن تكون عليه القيمة المأخوذة قبل الإطار المفتاحي الأول.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the pre behavior indicates what the sampled value should be before the first key.
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
### iterator() {#iterator--}
```
public Iterator<KeyFrame> iterator()
```


يحصل على المُعدِّد لتصفح جميع الإطارات المفتاحية.

**Returns:**
java.util.Iterator<com.aspose.threed.KeyFrame>
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
### reset() {#reset--}
```
public void reset()
```


يزيل جميع الإطارات المفتاحية ويعيد تعيين سلوكيات ما بعد/ما قبل.

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

