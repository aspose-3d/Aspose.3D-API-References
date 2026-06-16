---
title: "BindPoint"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "عادةً ما يتم إنشاء A على خاصية كائن؛ بعض أنواع الخصائص تحتوي على حقول مكوّنات متعددة مثل حقل Vector3، سيُنشئ قناة لكل حقل مكوّن ويربط الحقل بواحدة أو أكثر من حالات تسلسل الإطارات المفتاحية عبر القنوات."
type: docs
weight: 19
url: /ar/java/com.aspose.threed/bindpoint/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class BindPoint extends A3DObject
```

عادةً ما يتم إنشاء [BindPoint](../../com.aspose.threed/bindpoint) على خاصية كائن؛ بعض أنواع الخصائص تحتوي على حقول مكوّنات متعددة (مثل حقل Vector3)، سيُنشئ [BindPoint](../../com.aspose.threed/bindpoint) قناة لكل حقل مكوّن ويربط الحقل بواحدة أو أكثر من حالات تسلسل الإطارات المفتاحية عبر القنوات.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [BindPoint(Scene scene, Property prop)](#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-) | يُهيئ نسخة جديدة من الفئة [BindPoint](../../com.aspose.threed/bindpoint). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addChannel(String name, Class<?> type, Object value)](#addChannel-java.lang.String-java.lang.Class----java.lang.Object-) | يضيف خاصية القناة المحددة. |
| [addChannel(String name, Object value)](#addChannel-java.lang.String-java.lang.Object-) | يضيف خاصية القناة المحددة. |
| [bindKeyframeSequence(String channelName, KeyframeSequence sequence)](#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-) | ربط تسلسل الإطارات المفتاحية بالقناة المحددة |
| [createKeyframeSequence(String name)](#createKeyframeSequence-java.lang.String-) | ينشئ منحنىً جديدًا ويربطه بالقناة الأولى لتخطيط المنحنى |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [get(String channelName)](#get-java.lang.String-) | يحصل على القناة بالاسم المعطى |
| [getChannel(String channelName)](#getChannel-java.lang.String-) | يحصل على القناة بالاسم المعطى |
| [getChannelsCount()](#getChannelsCount--) | يحصل على العدد الإجمالي لقنوات الخصائص المعرفة في تخطيط منحنى الرسوم المتحركة هذا. |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(String channelName)](#getKeyframeSequence-java.lang.String-) | يحصل على أول تسلسل إطارات مفتاحية في القناة المحددة |
| [getName()](#getName--) | يحصل على الاسم. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty()](#getProperty--) | يحصل على الخاصية المرتبطة بـ CurveMapping |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [resetChannels()](#resetChannels--) | يفرغ قنوات الخصائص في تخطيط منحنى الرسوم المتحركة هذا. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setProperty(Property value)](#setProperty-com.aspose.threed.Property-) | يحصل على الخاصية المرتبطة بـ CurveMapping |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [toString()](#toString--) | يقوم بتنسيق الكائن إلى سلسلة |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BindPoint(Scene scene, Property prop) {#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-}
```
public BindPoint(Scene scene, Property prop)
```


يُهيئ نسخة جديدة من الفئة [BindPoint](../../com.aspose.threed/bindpoint).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | المشهد الذي يحتوي على الرسوم المتحركة. |
| prop | [Property](../../com.aspose.threed/property) | خاصية. |

### addChannel(String name, Class<?> type, Object value) {#addChannel-java.lang.String-java.lang.Class----java.lang.Object-}
```
public boolean addChannel(String name, Class<?> type, Object value)
```


يضيف خاصية القناة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم. |
| type | java.lang.Class<?> | نوع. |
| القيمة | java.lang.Object | قيمة. |

**Returns:**
منطقي - true إذا تم إضافة القناة، false خلاف ذلك.
### addChannel(String name, Object value) {#addChannel-java.lang.String-java.lang.Object-}
```
public boolean addChannel(String name, Object value)
```


يضيف خاصية القناة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم. |
| القيمة | java.lang.Object | قيمة. |

**Returns:**
منطقي - true إذا تم إضافة القناة، false خلاف ذلك.
### bindKeyframeSequence(String channelName, KeyframeSequence sequence) {#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-}
```
public void bindKeyframeSequence(String channelName, KeyframeSequence sequence)
```


ربط تسلسل الإطارات المفتاحية بالقناة المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| channelName | java.lang.String | القناة التي سيُربط بها تسلسل الإطارات المفتاحية |
| sequence | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | تسلسل الإطارات المفتاحية للربط |

### createKeyframeSequence(String name) {#createKeyframeSequence-java.lang.String-}
```
public KeyframeSequence createKeyframeSequence(String name)
```


ينشئ منحنىً جديدًا ويربطه بالقناة الأولى لتخطيط المنحنى

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم التسلسل الجديد. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
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
### get(String channelName) {#get-java.lang.String-}
```
public AnimationChannel get(String channelName)
```


يحصل على القناة بالاسم المعطى

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| channelName | java.lang.String | اسم القناة |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Animation channel
### getChannel(String channelName) {#getChannel-java.lang.String-}
```
public AnimationChannel getChannel(String channelName)
```


يحصل على القناة بالاسم المعطى

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| channelName | java.lang.String | اسم القناة للبحث عنه |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Channel with the name
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


يحصل على العدد الإجمالي لقنوات الخصائص المعرفة في تخطيط منحنى الرسوم المتحركة هذا.

**Returns:**
int - عدد القنوات.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(String channelName) {#getKeyframeSequence-java.lang.String-}
```
public KeyframeSequence getKeyframeSequence(String channelName)
```


يحصل على أول تسلسل إطارات مفتاحية في القناة المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| channelName | java.lang.String | اسم القناة للبحث عنه |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - First keyframe sequence with the channel name
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
### getProperty() {#getProperty--}
```
public Property getProperty()
```


يحصل على الخاصية المرتبطة بـ CurveMapping

**Returns:**
[Property](../../com.aspose.threed/property) - the property associated with the CurveMapping
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
### resetChannels() {#resetChannels--}
```
public void resetChannels()
```


يفرغ قنوات الخصائص في تخطيط منحنى الرسوم المتحركة هذا.

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


يضبط الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setProperty(Property value) {#setProperty-com.aspose.threed.Property-}
```
public void setProperty(Property value)
```


يحصل على الخاصية المرتبطة بـ CurveMapping

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Property](../../com.aspose.threed/property) | القيمة الجديدة |

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


يقوم بتنسيق الكائن إلى سلسلة

**Returns:**
java.lang.String - سلسلة الكائن
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

