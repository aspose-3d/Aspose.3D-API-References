---
title: "Pose"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "الوضعية تُستخدم لتخزين مصفوفة التحويل عندما يكون الشكل مُغطى."
type: docs
weight: 135
url: /ar/java/com.aspose.threed/pose/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Pose extends A3DObject
```

يُستخدم الـ Pose لتخزين مصفوفة التحويل عندما يتم تجليد الهندسة. الـ Pose هو مجموعة من [BonePose](../../com.aspose.threed/bonepose)، كل [BonePose](../../com.aspose.threed/bonepose) يحفظ معلومات التحويل الدقيقة لعقدة العظم.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Pose(String name)](#Pose-java.lang.String-) | ينشئ مثيلاً جديداً من الفئة [Pose](../../com.aspose.threed/pose). |
| [Pose()](#Pose--) | ينشئ مثيلاً جديداً من الفئة [Pose](../../com.aspose.threed/pose). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addBonePose(Node node, Matrix4 matrix)](#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-) | يحفظ مصفوفة تحويل الـ Pose للعقدة العظمية المحددة. |
| [addBonePose(Node node, Matrix4 matrix, boolean localMatrix)](#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-boolean-) | يحفظ مصفوفة تحويل الـ Pose للعقدة العظمية المحددة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getBonePoses()](#getBonePoses--) | يحصل على جميع [BonePose](../../com.aspose.threed/bonepose). |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | يحصل على الاسم. |
| [getPoseType()](#getPoseType--) | يحصل على نوع الـ Pose. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setPoseType(PoseType value)](#setPoseType-com.aspose.threed.PoseType-) | يضبط نوع الـ Pose. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pose(String name) {#Pose-java.lang.String-}
```
public Pose(String name)
```


ينشئ مثيلاً جديداً من الفئة [Pose](../../com.aspose.threed/pose).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم |

### Pose() {#Pose--}
```
public Pose()
```


ينشئ مثيلاً جديداً من الفئة [Pose](../../com.aspose.threed/pose).

### addBonePose(Node node, Matrix4 matrix) {#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-}
```
public void addBonePose(Node node, Matrix4 matrix)
```


يحفظ مصفوفة تحويل الوضع للعظام المحددة. تُفترض مصفوفة التحويل العامة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | عقدة العظم. |
| matrix | [Matrix4](../../com.aspose.threed/matrix4) | مصفوفة التحويل. |

### addBonePose(Node node, Matrix4 matrix, boolean localMatrix) {#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-boolean-}
```
public void addBonePose(Node node, Matrix4 matrix, boolean localMatrix)
```


يحفظ مصفوفة تحويل الـ Pose للعقدة العظمية المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | عقدة العظم. |
| matrix | [Matrix4](../../com.aspose.threed/matrix4) | مصفوفة التحويل. |
| localMatrix | boolean | إذا تم تعيينه إلى  true  يعني استخدام المصفوفة المحلية وإلا يعني المصفوفة العامة. |

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
### getBonePoses() {#getBonePoses--}
```
public List<BonePose> getBonePoses()
```


يحصل على جميع [BonePose](../../com.aspose.threed/bonepose).

**Returns:**
java.util.List<com.aspose.threed.BonePose> - جميع [BonePose](../../com.aspose.threed/bonepose).
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
### getPoseType() {#getPoseType--}
```
public PoseType getPoseType()
```


يحصل على نوع الـ Pose.

**Returns:**
[PoseType](../../com.aspose.threed/posetype) - the type of the pose.
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

### setPoseType(PoseType value) {#setPoseType-com.aspose.threed.PoseType-}
```
public void setPoseType(PoseType value)
```


يضبط نوع الـ Pose.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PoseType](../../com.aspose.threed/posetype) | القيمة الجديدة |

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

