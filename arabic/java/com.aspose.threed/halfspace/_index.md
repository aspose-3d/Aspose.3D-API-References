---
title: "HalfSpace"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "يمثل مساحة لا نهائية يتم تقسيمها بواسطة سطح، ويمكن استخدامها مع"
type: docs
weight: 77
url: /ar/java/com.aspose.threed/halfspace/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)
```
public class HalfSpace extends Entity
```

[HalfSpace](../../com.aspose.threed/halfspace) represents a infinity space which is split by a plane, this can be used with [BooleanOperator](../../com.aspose.threed/booleanoperator)
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [HalfSpace()](#HalfSpace--) | ينشئ نسخة جديدة من [HalfSpace](../../com.aspose.threed/halfspace) |
| [HalfSpace(Vector3 normal, Vector3 position)](#HalfSpace-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | ينشئ نسخة جديدة من [HalfSpace](../../com.aspose.threed/halfspace) باستخدام متجه العمودي المعطى وموقع على سطح القطع؛ |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getBoundingBox()](#getBoundingBox--) | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | يحصل على المفتاح الخاص بعارض الكيان المسجل في العارض. |
| [getExcluded()](#getExcluded--) | يحصل على ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [getName()](#getName--) | يحصل على الاسم. |
| [getNormal()](#getNormal--) | المتجه العمودي للسطح المقسّم، يُعرّف السطح بالمعادلة N \* P + D = 0 حيث N هو المتجه العمودي وP هو أي نقطة على السطح. |
| [getParentNode()](#getParentNode--) | يحصل على أول عقدة أب، إذا تم تعيين أول عقدة أب، سيُفصل هذا الكيان عن عقد الأب الأخرى. |
| [getParentNodes()](#getParentNodes--) | يحصل على جميع عقد الأب، يمكن إرفاق كيان بعدة عقد أب لتكرار الهندسة. |
| [getPosition()](#getPosition--) | أي نقطة على السطح المقسّم، يُعرّف السطح بالمعادلة N \* P + D = 0 حيث N هو المتجه العمودي وP هو أي نقطة على السطح. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getScene()](#getScene--) | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setNormal(Vector3 value)](#setNormal-com.aspose.threed.Vector3-) | المتجه العمودي للسطح المقسّم، يُعرّف السطح بالمعادلة N \* P + D = 0 حيث N هو المتجه العمودي وP هو أي نقطة على السطح. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | يضبط أول عقدة أب، إذا تم ضبط أول عقدة أب، سيُفصل هذا الكيان عن عقد الأب الأخرى. |
| [setPosition(Vector3 value)](#setPosition-com.aspose.threed.Vector3-) | أي نقطة على السطح المقسّم، يُعرّف السطح بالمعادلة N \* P + D = 0 حيث N هو المتجه العمودي وP هو أي نقطة على السطح. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HalfSpace() {#HalfSpace--}
```
public HalfSpace()
```


ينشئ نسخة جديدة من [HalfSpace](../../com.aspose.threed/halfspace)

### HalfSpace(Vector3 normal, Vector3 position) {#HalfSpace-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public HalfSpace(Vector3 normal, Vector3 position)
```


ينشئ نسخة جديدة من [HalfSpace](../../com.aspose.threed/halfspace) باستخدام متجه العمودي المعطى وموقع على سطح القطع؛

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| normal | [Vector3](../../com.aspose.threed/vector3) |  |
| position | [Vector3](../../com.aspose.threed/vector3) |  |

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
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به.

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - the bounding box of current entity in its object space coordinate system. **Example:** The following code shows how to calculate the bounding box of a shape

```
Entity entity = new Sphere();
     entity.setRadius(10);
     var bbox = entity.getBoundingBox();
     System.out.printf("The bounding box of the entity is %s ~ %s", bbox.getMinimum(), bbox.getMaximum());
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


يحصل على المفتاح الخاص بعارض الكيان المسجل في العارض.

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


يحصل على ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير.

**Returns:**
منطقي - ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير.
### getName() {#getName--}
```
public String getName()
```


يحصل على الاسم.

**Returns:**
java.lang.String - الاسم.
### getNormal() {#getNormal--}
```
public Vector3 getNormal()
```


المتجه العمودي للسطح المقسّم، يُعرّف السطح بالمعادلة N \* P + D = 0 حيث N هو المتجه العمودي وP هو أي نقطة على السطح.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The normal of the split plane, the plane is defined as N \* P + D = 0 where N is Normal and P is any point on the plane.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


يحصل على أول عقدة أب، إذا تم تعيين أول عقدة أب، سيُفصل هذا الكيان عن عقد الأب الأخرى.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


يحصل على جميع عقد الأب، يمكن إرفاق كيان بعدة عقد أب لتكرار الهندسة.

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - جميع العقد الأصلية، يمكن إرفاق كيان بعدة عقد أصلية لتجسيد الهندسة
### getPosition() {#getPosition--}
```
public Vector3 getPosition()
```


أي نقطة على السطح المقسّم، يُعرّف السطح بالمعادلة N \* P + D = 0 حيث N هو المتجه العمودي وP هو أي نقطة على السطح.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The any point on the split plane, the plane is defined as N \* P + D = 0 where N is Normal and P is any point on the plane.
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
### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


يضبط الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setNormal(Vector3 value) {#setNormal-com.aspose.threed.Vector3-}
```
public void setNormal(Vector3 value)
```


المتجه العمودي للسطح المقسّم، يُعرّف السطح بالمعادلة N \* P + D = 0 حيث N هو المتجه العمودي وP هو أي نقطة على السطح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


يضبط أول عقدة أب، إذا تم ضبط أول عقدة أب، سيُفصل هذا الكيان عن عقد الأب الأخرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | القيمة الجديدة |

### setPosition(Vector3 value) {#setPosition-com.aspose.threed.Vector3-}
```
public void setPosition(Vector3 value)
```


أي نقطة على السطح المقسّم، يُعرّف السطح بالمعادلة N \* P + D = 0 حيث N هو المتجه العمودي وP هو أي نقطة على السطح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

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

