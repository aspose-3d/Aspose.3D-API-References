---
title: "AnimationNode"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "يدعم Aspose.3Ds هيكلية الرسوم المتحركة؛ يمكن تكوين كل رسم متحرك من عدة رسومات متحركة وتعريف الإطارات المفتاحية للرسوم المتحركة."
type: docs
weight: 15
url: /ar/java/com.aspose.threed/animationnode/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AnimationNode extends A3DObject
```

يدعم Aspose.3D هيكلية الرسوم المتحركة؛ يمكن تكوين كل رسم متحرك من عدة رسومات متحركة وتعريف الإطارات المفتاحية للرسوم المتحركة. [AnimationNode](../../com.aspose.threed/animationnode) يحدد تحويل قيمة الخاصية بمرور الوقت، على سبيل المثال، يمكن استخدام عقدة الرسوم المتحركة للتحكم في تحويل العقدة أو الخصائص الرقمية لكائن آخر [A3DObject](../../com.aspose.threed/a3dobject).
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [AnimationNode(String name)](#AnimationNode-java.lang.String-) | يُنشئ مثيلاً جديداً من الفئة [AnimationNode](../../com.aspose.threed/animationnode). |
| [AnimationNode()](#AnimationNode--) | يُنشئ مثيلاً جديداً من الفئة [AnimationNode](../../com.aspose.threed/animationnode). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [createBindPoint(A3DObject obj, String propName)](#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | ينشئ BindPoint بناءً على نوع بيانات الخاصية. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findBindPoint(A3DObject target, String name)](#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | يبحث عن نقطة الربط حسب الهدف والاسم. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getBindPoint(A3DObject target, String propName, boolean create)](#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-) | يحصل على نقطة ربط الرسوم المتحركة للخاصية المعطاة. |
| [getBindPoints()](#getBindPoints--) | يحصل على نقاط ربط الخاصية الحالية |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(A3DObject target, String propName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-) | يحصل على تسلسل الإطارات المفتاحية للخاصية المعطاة. |
| [getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-) | يحصل على تسلسل الإطارات المفتاحية للخاصية والقناة المحددة. |
| [getName()](#getName--) | يحصل على الاسم. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getSubAnimations()](#getSubAnimations--) | يحصل على عقد التحريك الفرعية تحت التحريكات الحالية |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationNode(String name) {#AnimationNode-java.lang.String-}
```
public AnimationNode(String name)
```


يُنشئ مثيلاً جديداً من الفئة [AnimationNode](../../com.aspose.threed/animationnode).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم |

### AnimationNode() {#AnimationNode--}
```
public AnimationNode()
```


يُنشئ مثيلاً جديداً من الفئة [AnimationNode](../../com.aspose.threed/animationnode).

### createBindPoint(A3DObject obj, String propName) {#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint createBindPoint(A3DObject obj, String propName)
```


ينشئ BindPoint بناءً على نوع بيانات الخاصية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | [A3DObject](../../com.aspose.threed/a3dobject) | كائن. |
| propName | java.lang.String | اسم الخاصية. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point instance or null if the property is not defined.
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
### findBindPoint(A3DObject target, String name) {#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint findBindPoint(A3DObject target, String name)
```


يبحث عن نقطة الربط حسب الهدف والاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | الهدف لنقطة الربط للعثور عليه. |
| الاسم | java.lang.String | اسم نقطة الربط للعثور عليه. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
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
### getBindPoint(A3DObject target, String propName, boolean create) {#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public BindPoint getBindPoint(A3DObject target, String propName, boolean create)
```


يحصل على نقطة ربط الرسوم المتحركة للخاصية المعطاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | على أي كائن يتم إنشاء نقطة الربط. |
| propName | java.lang.String | اسم الخاصية. |
| إنشاء | boolean | إذا تم تعيينه إلى  true  إنشاء نقطة الربط إذا لم تكن موجودة. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
### getBindPoints() {#getBindPoints--}
```
public List<BindPoint> getBindPoints()
```


يحصل على نقاط ربط الخاصية الحالية

**Returns:**
java.util.List<com.aspose.threed.BindPoint> - نقاط ربط الخاصية الحالية
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(A3DObject target, String propName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, boolean create)
```


يحصل على تسلسل الإطارات المفتاحية للخاصية المعطاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | على أي نسخة يتم إنشاء تسلسل الإطارات المفتاحية. |
| propName | java.lang.String | اسم الخاصية. |
| إنشاء | boolean | إذا تم تعيينه إلى  true , إنشاء التسلسل إذا لم يكن موجودًا. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)
```


يحصل على تسلسل الإطارات المفتاحية للخاصية والقناة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | على أي نسخة يتم إنشاء تسلسل الإطارات المفتاحية. |
| propName | java.lang.String | اسم الخاصية. |
| channelName | java.lang.String | اسم القناة. |
| إنشاء | boolean | إذا تم تعيينه إلى  true  إنشاء تسلسل الرسوم المتحركة إذا لم يكن موجودًا. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
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
### getSubAnimations() {#getSubAnimations--}
```
public List<AnimationNode> getSubAnimations()
```


يحصل على عقد التحريك الفرعية تحت التحريكات الحالية

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> - عقد التحريك الفرعية تحت التحريكات الحالية
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

