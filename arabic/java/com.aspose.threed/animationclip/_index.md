---
title: "AnimationClip"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "مقطع الرسوم المتحركة هو مجموعة من الرسوم المتحركة."
type: docs
weight: 14
url: /ar/java/com.aspose.threed/animationclip/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class AnimationClip extends SceneObject
```

مقاطع الرسوم المتحركة هي مجموعة من الرسوم المتحركة. يمكن للمشهد أن يحتوي على مقطع أو أكثر من مقاطع الرسوم المتحركة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [AnimationClip()](#AnimationClip--) | ينشئ مثيلاً جديداً من الفئة [AnimationClip](../../com.aspose.threed/animationclip). |
| [AnimationClip(String name)](#AnimationClip-java.lang.String-) | ينشئ مثيلاً جديداً من الفئة [AnimationClip](../../com.aspose.threed/animationclip). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [createAnimationNode(String nodeName)](#createAnimationNode-java.lang.String-) | دالة مختصرة لإنشاء وتسجيل عقدة الرسوم المتحركة على المقطع الحالي. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getAnimations()](#getAnimations--) | يحصل على الرسوم المتحركة الموجودة داخل المقطع. |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | يحصل على وصف هذا المقطع المتحرك |
| [getName()](#getName--) | يحصل على الاسم. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getScene()](#getScene--) | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [getStart()](#getStart--) | يحصل على الوقت بالثواني لبداية المقطع. |
| [getStop()](#getStop--) | يحصل على الوقت بالثواني لنهاية المقطع. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [setDescription(String value)](#setDescription-java.lang.String-) | يضبط وصف هذا المقطع المتحرك |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setStart(double value)](#setStart-double-) | يضبط الوقت بالثواني لبداية المقطع. |
| [setStop(double value)](#setStop-double-) | يضبط الوقت بالثواني لنهاية المقطع. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationClip() {#AnimationClip--}
```
public AnimationClip()
```


ينشئ مثيلاً جديداً من الفئة [AnimationClip](../../com.aspose.threed/animationclip).

### AnimationClip(String name) {#AnimationClip-java.lang.String-}
```
public AnimationClip(String name)
```


ينشئ مثيلاً جديداً من الفئة [AnimationClip](../../com.aspose.threed/animationclip).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم |

### createAnimationNode(String nodeName) {#createAnimationNode-java.lang.String-}
```
public AnimationNode createAnimationNode(String nodeName)
```


دالة مختصرة لإنشاء وتسجيل عقدة الرسوم المتحركة على المقطع الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| nodeName | java.lang.String | اسم عقدة الرسوم المتحركة الجديدة |

**Returns:**
[AnimationNode](../../com.aspose.threed/animationnode) - A new instance of [AnimationNode](../../com.aspose.threed/animationnode) with given name.
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
### getAnimations() {#getAnimations--}
```
public List<AnimationNode> getAnimations()
```


يحصل على الرسوم المتحركة الموجودة داخل المقطع.

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> - الرسوم المتحركة المحتواة داخل المقطع.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public String getDescription()
```


يحصل على وصف هذا المقطع المتحرك

**Returns:**
java.lang.String - وصف هذا المقطع المتحرك
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
### getScene() {#getScene--}
```
public Scene getScene()
```


يحصل على المشهد الذي ينتمي إليه هذا الكائن

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getStart() {#getStart--}
```
public double getStart()
```


يحصل على الوقت بالثواني لبداية المقطع.

**Returns:**
double - الوقت بالثواني لبداية المقطع.
### getStop() {#getStop--}
```
public double getStop()
```


يحصل على الوقت بالثواني لنهاية المقطع.

**Returns:**
double - الوقت بالثواني لنهاية المقطع.
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
### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


يضبط وصف هذا المقطع المتحرك

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

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

### setStart(double value) {#setStart-double-}
```
public void setStart(double value)
```


يضبط الوقت بالثواني لبداية المقطع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setStop(double value) {#setStop-double-}
```
public void setStop(double value)
```


يضبط الوقت بالثواني لنهاية المقطع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

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

