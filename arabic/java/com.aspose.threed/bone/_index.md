---
title: "العظم"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "العظم يحدد مجموعة نقاط التحكم في الهندسة ويحدد وزن الدمج لكل نقطة تحكم."
type: docs
weight: 20
url: /ar/java/com.aspose.threed/bone/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Bone extends A3DObject
```

العظم يحدد مجموعة نقاط التحكم في الهندسة، ويحدد وزن الدمج لكل نقطة تحكم. لا يمكن استخدام كائن [Bone](../../com.aspose.threed/bone) مباشرةً، يتم استخدام مثيل [SkinDeformer](../../com.aspose.threed/skindeformer) لتشويه الهندسة، ويأتي [SkinDeformer](../../com.aspose.threed/skindeformer) مع مجموعة من العظام، كل عظم مرتبط بعقدة. ملاحظة: يمكن ربط نقطة تحكم في الهندسة بأكثر من عظمة واحدة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Bone(String name)](#Bone-java.lang.String-) | ينشئ مثيلاً جديداً لفئة [Bone](../../com.aspose.threed/bone). |
| [Bone()](#Bone--) | ينشئ مثيلاً جديداً لفئة [Bone](../../com.aspose.threed/bone). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [get(int index)](#get-int-) | يحصل على وزن الدمج لنقطة التحكم المحددة |
| [getBoneTransform()](#getBoneTransform--) | يحصل على مصفوفة التحويل للعظم. |
| [getClass()](#getClass--) |  |
| [getLinkMode()](#getLinkMode--) | وضع ربط العظام يشير إلى الطريقة التي يتم بها ربط العظمة بعظمتها الأصلية ضمن هيكل هرمي. |
| [getName()](#getName--) | يحصل على الاسم. |
| [getNode()](#getNode--) | يحصل على العقدة. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getTransform()](#getTransform--) | يحصل على مصفوفة التحويل للعقدة التي تحتوي على العظم. |
| [getWeight(int index)](#getWeight-int-) | يحصل على الوزن لنقطة التحكم المحددة بواسطة الفهرس |
| [getWeightCount()](#getWeightCount--) | يحصل على عدد الأوزان، يتم توسيعه تلقائيًا بواسطة [setWeight](../../com.aspose.threed/bone\#setWeight) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [set(int index, double value)](#set-int-double-) | يضبط وزن الدمج لنقطة التحكم المحددة |
| [setBoneTransform(Matrix4 value)](#setBoneTransform-com.aspose.threed.Matrix4-) | يضبط مصفوفة التحويل للعظم. |
| [setLinkMode(BoneLinkMode value)](#setLinkMode-com.aspose.threed.BoneLinkMode-) | وضع ربط العظام يشير إلى الطريقة التي يتم بها ربط العظمة بعظمتها الأصلية ضمن هيكل هرمي. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | يضبط العقدة. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setTransform(Matrix4 value)](#setTransform-com.aspose.threed.Matrix4-) | يضبط مصفوفة التحويل للعقدة التي تحتوي على العظم. |
| [setWeight(int index, double weight)](#setWeight-int-double-) | يضبط الوزن لنقطة التحكم المحددة بالفهرس |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Bone(String name) {#Bone-java.lang.String-}
```
public Bone(String name)
```


ينشئ مثيلاً جديداً لفئة [Bone](../../com.aspose.threed/bone).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم. |

### Bone() {#Bone--}
```
public Bone()
```


ينشئ مثيلاً جديداً لفئة [Bone](../../com.aspose.threed/bone).

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
### get(int index) {#get-int-}
```
public double get(int index)
```


يحصل على وزن الدمج لنقطة التحكم المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الفهرس | int | فهرس الوزن |

**Returns:**
double - الوزن
### getBoneTransform() {#getBoneTransform--}
```
public Matrix4 getBoneTransform()
```


يحصل على مصفوفة التحويل للعظم.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the bone.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLinkMode() {#getLinkMode--}
```
public BoneLinkMode getLinkMode()
```


وضع ربط العظام يشير إلى الطريقة التي يتم بها ربط العظمة بعظمتها الأصلية ضمن هيكل هرمي.

**Returns:**
[BoneLinkMode](../../com.aspose.threed/bonelinkmode) - A bone's link mode refers to the way in which a bone is connected or linked to its parent bone within a hierarchical structure.
### getName() {#getName--}
```
public String getName()
```


يحصل على الاسم.

**Returns:**
java.lang.String - الاسم.
### getNode() {#getNode--}
```
public Node getNode()
```


يحصل على العقدة. عقدة العظم هي العظم الذي تُلصق به الجلد، سيستخدم [SkinDeformer](../../com.aspose.threed/skindeformer) عقدة العظم لتؤثر على إزاحة نقاط التحكم. عادةً ما تكون عقدة العظم مرتبطة بـ [Skeleton](../../com.aspose.threed/skeleton)، لكن ذلك ليس مطلوبًا. يُستخدم الـ [Skeleton](../../com.aspose.threed/skeleton) المرفق عادةً بواسطة برامج DCC لعرض الهيكل العظمي للمستخدم.

**Returns:**
[Node](../../com.aspose.threed/node) - the node. The bone node is the bone which skin attached to, the [SkinDeformer](../../com.aspose.threed/skindeformer) will use bone node to influence the displacement of the control points. Bone node usually has a [Skeleton](../../com.aspose.threed/skeleton) attached, but it's not required. Attached [Skeleton](../../com.aspose.threed/skeleton) is usually used by DCC software to show skeleton to user.
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
### getTransform() {#getTransform--}
```
public Matrix4 getTransform()
```


يحصل على مصفوفة التحويل للعقدة التي تحتوي على العظم.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the node containing the bone.
### getWeight(int index) {#getWeight-int-}
```
public double getWeight(int index)
```


يحصل على الوزن لنقطة التحكم المحددة بواسطة الفهرس

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الفهرس | int | فهرس نقطة التحكم |

**Returns:**
double - الوزن عند الفهرس المحدد، أو 0 إذا كان الفهرس غير صالح
### getWeightCount() {#getWeightCount--}
```
public int getWeightCount()
```


يحصل على عدد الأوزان، يتم توسيعه تلقائيًا بواسطة [setWeight](../../com.aspose.threed/bone\#setWeight)

**Returns:**
int - عدد الأوزان، يتم توسيعه تلقائيًا بواسطة [setWeight](../../com.aspose.threed/bone\#setWeight)
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
### set(int index, double value) {#set-int-double-}
```
public void set(int index, double value)
```


يضبط وزن الدمج لنقطة التحكم المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الفهرس | int | فهرس الوزن |
| القيمة | double | القيمة الجديدة |

### setBoneTransform(Matrix4 value) {#setBoneTransform-com.aspose.threed.Matrix4-}
```
public void setBoneTransform(Matrix4 value)
```


يضبط مصفوفة التحويل للعظم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | القيمة الجديدة |

### setLinkMode(BoneLinkMode value) {#setLinkMode-com.aspose.threed.BoneLinkMode-}
```
public void setLinkMode(BoneLinkMode value)
```


وضع ربط العظام يشير إلى الطريقة التي يتم بها ربط العظمة بعظمتها الأصلية ضمن هيكل هرمي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BoneLinkMode](../../com.aspose.threed/bonelinkmode) | القيمة الجديدة |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


يضبط الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


يضبط العقدة. عقدة العظم هي العظم الذي يُلصق به الجلد، سيستخدم [SkinDeformer](../../com.aspose.threed/skindeformer) عقدة العظم لتؤثر على إزاحة نقاط التحكم. عادةً ما تكون عقدة العظم مرتبطة بـ [Skeleton](../../com.aspose.threed/skeleton)، لكن ذلك ليس مطلوبًا. يُستخدم الـ [Skeleton](../../com.aspose.threed/skeleton) المرفق عادةً بواسطة برامج DCC لعرض الهيكل العظمي للمستخدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | القيمة الجديدة |

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

### setTransform(Matrix4 value) {#setTransform-com.aspose.threed.Matrix4-}
```
public void setTransform(Matrix4 value)
```


يضبط مصفوفة التحويل للعقدة التي تحتوي على العظم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | القيمة الجديدة |

### setWeight(int index, double weight) {#setWeight-int-double-}
```
public void setWeight(int index, double weight)
```


يضبط الوزن لنقطة التحكم المحددة بالفهرس

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الفهرس | int | فهرس نقطة التحكم |
| الوزن | double | وزن جديد |

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

