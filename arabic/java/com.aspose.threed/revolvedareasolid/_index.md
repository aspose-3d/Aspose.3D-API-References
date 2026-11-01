---
title: "RevolvedAreaSolid"
second_title: "مرجع Aspose.3D لـ Java API"
description: "هذه الفئة تمثل نموذجًا صلبًا عن طريق تدوير مقطع عرضي يُقدَّم بواسطة ملف تعريف حول محور."
type: docs
weight: 155
url: /ar/java/com.aspose.threed/revolvedareasolid/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class RevolvedAreaSolid extends Entity implements IMeshConvertible
```

هذه الفئة تمثل نموذجًا صلبًا عن طريق تدوير مقطع عرضي مقدم بواسطة ملف تعريف حول محور. **Example:** يوضح الشيفرة التالية كيفية استخدام RevolvedAreaSolid لتدوير شكل إلى نموذج صلب.

```
//Create a new 3D scene
         Scene scene = new Scene();
 
         // Initialize the base profile to be extruded
         var profile = new RectangleShape();
         profile.setRoundingRadius(0.3);
 
         var revolved = new RevolvedAreaSolid();
         revolved.setShape(profile);
         revolved.setOrigin(new Vector3(1, 0, 0));
         revolved.setAngleStart(0);
         revolved.setAngleEnd(Math.PI);
         scene.getRootNode().createChildNode(revolved);
 
         scene.save("revolved.obj");
```
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [RevolvedAreaSolid()](#RevolvedAreaSolid--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getAngleEnd()](#getAngleEnd--) | يحصل على زاوية النهاية لعملية التدوير، مقاسة بالراديان، القيمة الافتراضية هي π. |
| [getAngleStart()](#getAngleStart--) | يحصل على الزاوية الابتدائية لإجراء الدوران، مقاسة بالراديان، القيمة الافتراضية هي 0. |
| [getAxis()](#getAxis--) | يحصل على اتجاه المحور، القيمة الافتراضية هي (0, 1, 0). |
| [getBoundingBox()](#getBoundingBox--) | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | يحصل على المفتاح الخاص بعارض الكيان المسجل في العارض |
| [getExcluded()](#getExcluded--) | يحصل على ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [getName()](#getName--) | يحصل على الاسم. |
| [getOrigin()](#getOrigin--) | يحصل على نقطة الأصل للدوران، القيمة الافتراضية هي (0, 0, 0). |
| [getParentNode()](#getParentNode--) | يحصل على أول عقدة أصل، إذا تم تعيين أول عقدة أصل، سيتم فصل هذا الكيان عن عقد الأصل الأخرى. |
| [getParentNodes()](#getParentNodes--) | يحصل على جميع عقد الأصل، يمكن إرفاق كيان بعدة عقد أصل لتكرار الهندسة |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getScene()](#getScene--) | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [getShape()](#getShape--) | يحصل على الملف الأساسي المستخدم للدوران. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | أزل الخاصية المحددة بالاسم |
| [setAngleEnd(double value)](#setAngleEnd-double-) | يضبط الزاوية النهائية لإجراء الدوران، مقاسة بالراديان، القيمة الافتراضية هي π. |
| [setAngleStart(double value)](#setAngleStart-double-) | يضبط الزاوية الابتدائية لإجراء الدوران، مقاسة بالراديان، القيمة الافتراضية هي 0. |
| [setAxis(Vector3 value)](#setAxis-com.aspose.threed.Vector3-) | يضبط اتجاه المحور، القيمة الافتراضية هي (0, 1, 0). |
| [setExcluded(boolean value)](#setExcluded-boolean-) | يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setOrigin(Vector3 value)](#setOrigin-com.aspose.threed.Vector3-) | يضبط نقطة الأصل للدوران، القيمة الافتراضية هي (0, 0, 0). |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | يضبط أول عقدة أصل، إذا تم تعيين أول عقدة أصل، سيتم فصل هذا الكيان عن عقد الأصل الأخرى. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setShape(Profile value)](#setShape-com.aspose.threed.Profile-) | يضبط الملف الأساسي المستخدم للدوران. |
| [toMesh()](#toMesh--) | تحويل الـ [RevolvedAreaSolid](../../com.aspose.threed/revolvedareasolid) إلى شبكة. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RevolvedAreaSolid() {#RevolvedAreaSolid--}
```
public RevolvedAreaSolid()
```


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
### getAngleEnd() {#getAngleEnd--}
```
public double getAngleEnd()
```


يحصل على زاوية النهاية لعملية التدوير، مقاسة بالراديان، القيمة الافتراضية هي π.

**Returns:**
double - الزاوية النهائية لإجراء الدوران، مقاسة بالراديان، القيمة الافتراضية هي π.
### getAngleStart() {#getAngleStart--}
```
public double getAngleStart()
```


يحصل على الزاوية الابتدائية لإجراء الدوران، مقاسة بالراديان، القيمة الافتراضية هي 0.

**Returns:**
double - الزاوية الابتدائية لإجراء الدوران، مقاسة بالراديان، القيمة الافتراضية هي 0.
### getAxis() {#getAxis--}
```
public Vector3 getAxis()
```


يحصل على اتجاه المحور، القيمة الافتراضية هي (0, 1, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the axis direction, default value is (0, 1, 0).
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


يحصل على المفتاح الخاص بعارض الكيان المسجل في العارض

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
### getOrigin() {#getOrigin--}
```
public Vector3 getOrigin()
```


يحصل على نقطة الأصل للدوران، القيمة الافتراضية هي (0, 0, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the origin point of the revolving, default value is (0, 0, 0).
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


يحصل على أول عقدة أصل، إذا تم تعيين أول عقدة أصل، سيتم فصل هذا الكيان عن عقد الأصل الأخرى.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


يحصل على جميع عقد الأصل، يمكن إرفاق كيان بعدة عقد أصل لتكرار الهندسة

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - جميع العقد الأصلية، يمكن ربط كيان بعدة عقد أصلية لتكرار الهندسة
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
### getShape() {#getShape--}
```
public Profile getShape()
```


يحصل على الملف الأساسي المستخدم للدوران.

**Returns:**
[Profile](../../com.aspose.threed/profile) - the base profile used to revolve.
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
### setAngleEnd(double value) {#setAngleEnd-double-}
```
public void setAngleEnd(double value)
```


يضبط الزاوية النهائية لإجراء الدوران، مقاسة بالراديان، القيمة الافتراضية هي π.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | قيمة جديدة |

### setAngleStart(double value) {#setAngleStart-double-}
```
public void setAngleStart(double value)
```


يضبط الزاوية الابتدائية لإجراء الدوران، مقاسة بالراديان، القيمة الافتراضية هي 0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | قيمة جديدة |

### setAxis(Vector3 value) {#setAxis-com.aspose.threed.Vector3-}
```
public void setAxis(Vector3 value)
```


يضبط اتجاه المحور، القيمة الافتراضية هي (0, 1, 0).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | قيمة جديدة |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean | قيمة جديدة |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


يضبط الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | قيمة جديدة |

### setOrigin(Vector3 value) {#setOrigin-com.aspose.threed.Vector3-}
```
public void setOrigin(Vector3 value)
```


يضبط نقطة الأصل للدوران، القيمة الافتراضية هي (0, 0, 0).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | قيمة جديدة |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


يضبط أول عقدة أصل، إذا تم تعيين أول عقدة أصل، سيتم فصل هذا الكيان عن عقد الأصل الأخرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | قيمة جديدة |

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

### setShape(Profile value) {#setShape-com.aspose.threed.Profile-}
```
public void setShape(Profile value)
```


يضبط الملف الأساسي المستخدم للدوران.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Profile](../../com.aspose.threed/profile) | قيمة جديدة |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


تحويل الـ [RevolvedAreaSolid](../../com.aspose.threed/revolvedareasolid) إلى شبكة.

**Returns:**
[Mesh](../../com.aspose.threed/mesh)
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

