---
title: "Frustum"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "الفئة الأساسية لـ  و"
type: docs
weight: 69
url: /ar/java/com.aspose.threed/frustum/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IOrientable](../../com.aspose.threed/iorientable)
```
public abstract class Frustum extends Entity implements IOrientable
```

الفئة الأساسية لـ [Camera](../../com.aspose.threed/camera) و [Light](../../com.aspose.threed/light)
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getAspect()](#getAspect--) | يحصل على نسبة العرض إلى الارتفاع للـ frustum |
| [getBoundingBox()](#getBoundingBox--) | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | يحصل على الاتجاه الذي تنظر إليه الكاميرا. |
| [getEntityRendererKey()](#getEntityRendererKey--) | يحصل على المفتاح الخاص بعارض الكيان المسجل في العارض. |
| [getExcluded()](#getExcluded--) | يحصل على ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [getFarPlane()](#getFarPlane--) | يحصل على مسافة المستوى البعيد للـ frustum. |
| [getLookAt()](#getLookAt--) | يحصل على الموضع المهتم الذي تنظر إليه الكاميرا. |
| [getName()](#getName--) | يحصل على الاسم. |
| [getNearPlane()](#getNearPlane--) | يحصل على مسافة المستوى القريب للمخروط. |
| [getOrthoHeight()](#getOrthoHeight--) | يحصل على الارتفاع عندما يكون المخروط في الإسقاط المتعامد. |
| [getParentNode()](#getParentNode--) | يحصل على أول عقدة أب، إذا تم تعيين أول عقدة أب، سيُفصل هذا الكيان عن عقد الأب الأخرى. |
| [getParentNodes()](#getParentNodes--) | يحصل على جميع عقد الأب، يمكن إرفاق كيان بعدة عقد أب لتكرار الهندسة. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getRotationMode()](#getRotationMode--) | يحصل على وضعية توجيه المخروط. هذه الخاصية تعمل فقط عندما يكون [getTarget](../../com.aspose.threed/frustum\#getTarget) فارغًا. |
| [getScene()](#getScene--) | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [getTarget()](#getTarget--) | يحصل على الهدف الذي تنظر إليه الكاميرا. |
| [getUp()](#getUp--) | يحصل على اتجاه الأعلى للكاميرا |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [setAspect(double value)](#setAspect-double-) | يضبط نسبة العرض إلى الارتفاع للمخروط |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | يضبط الاتجاه الذي تنظر إليه الكاميرا. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [setFarPlane(double value)](#setFarPlane-double-) | يضبط مسافة المستوى البعيد للمخروط. |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | يضبط الموضع المهتم الذي تنظر إليه الكاميرا. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setNearPlane(double value)](#setNearPlane-double-) | يضبط مسافة المستوى القريب للمخروط. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | يضبط الارتفاع عندما يكون المخروط في الإسقاط المتعامد. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | يضبط أول عقدة أب، إذا تم ضبط أول عقدة أب، سيُفصل هذا الكيان عن عقد الأب الأخرى. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | يضبط وضع توجيه المخروط. هذه الخاصية تعمل فقط عندما يكون [getTarget](../../com.aspose.threed/frustum\#getTarget) فارغًا. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | يضبط الهدف الذي تنظر إليه الكاميرا. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | يضبط اتجاه الأعلى للكاميرا |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAspect() {#getAspect--}
```
public double getAspect()
```


يحصل على نسبة العرض إلى الارتفاع للـ frustum

**Returns:**
double - نسبة العرض إلى الارتفاع للمخروط
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
### getDirection() {#getDirection--}
```
public Vector3 getDirection()
```


يحصل على الاتجاه الذي تنظر إليه الكاميرا. التغييرات على هذه الخاصية ستؤثر أيضًا على [getLookAt](../../com.aspose.threed/frustum\#getLookAt) و [getTarget](../../com.aspose.threed/frustum\#getTarget).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the camera is looking at. Changes on this property will also affects the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) and [getTarget](../../com.aspose.threed/frustum\#getTarget).
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
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


يحصل على مسافة المستوى البعيد للـ frustum.

**Returns:**
double - مسافة المستوى البعيد للمخروط.
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


يحصل على الموضع المهتم الذي تنظر إليه الكاميرا.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getName() {#getName--}
```
public String getName()
```


يحصل على الاسم.

**Returns:**
java.lang.String - الاسم.
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


يحصل على مسافة المستوى القريب للمخروط.

**Returns:**
double - مسافة المستوى القريب للمخروط.
### getOrthoHeight() {#getOrthoHeight--}
```
public double getOrthoHeight()
```


يحصل على الارتفاع عندما يكون المخروط في الإسقاط المتعامد.

**Returns:**
double - الارتفاع عندما يكون المخروط في الإسقاط المتعامد.
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
### getRotationMode() {#getRotationMode--}
```
public RotationMode getRotationMode()
```


يحصل على وضع توجيه المخروط. هذه الخاصية تعمل فقط عندما يكون [getTarget](../../com.aspose.threed/frustum\#getTarget) فارغًا. إذا كانت القيمة هي [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET)، يتم دائمًا حساب الاتجاه بواسطة الخاصية [getLookAt](../../com.aspose.threed/frustum\#getLookAt). وإلا فإن [getLookAt](../../com.aspose.threed/frustum\#getLookAt) يتم دائمًا حسابه بواسطة [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Returns:**
[RotationMode](../../com.aspose.threed/rotationmode) - the frustum's orientation mode This property only works when the [getTarget](../../com.aspose.threed/frustum\#getTarget) is null. If the value is [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), the direction is always calculated by the property [getLookAt](../../com.aspose.threed/frustum\#getLookAt) Otherwise the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) is always calculated by the [getDirection](../../com.aspose.threed/frustum\#getDirection)
### getScene() {#getScene--}
```
public Scene getScene()
```


يحصل على المشهد الذي ينتمي إليه هذا الكائن

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTarget() {#getTarget--}
```
public Node getTarget()
```


يحصل على الهدف الذي تنظر إليه الكاميرا. إذا كان المستخدم يدعم هذه الخاصية، يجب أن تكون قبل خاصية [getLookAt](../../com.aspose.threed/frustum\#getLookAt).

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the camera is looking at. If the user supports this property, it should be prior to [getLookAt](../../com.aspose.threed/frustum\#getLookAt) property.
### getUp() {#getUp--}
```
public Vector3 getUp()
```


يحصل على اتجاه الأعلى للكاميرا

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the up direction of the camera
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
### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


يضبط نسبة العرض إلى الارتفاع للمخروط

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


يضبط الاتجاه الذي تنظر إليه الكاميرا. التغييرات على هذه الخاصية ستؤثر أيضًا على [getLookAt](../../com.aspose.threed/frustum\#getLookAt) و [getTarget](../../com.aspose.threed/frustum\#getTarget).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


يضبط مسافة المستوى البعيد للمخروط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


يضبط الموضع المهتم الذي تنظر إليه الكاميرا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


يضبط الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


يضبط مسافة المستوى القريب للمخروط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setOrthoHeight(double value) {#setOrthoHeight-double-}
```
public void setOrthoHeight(double value)
```


يضبط الارتفاع عندما يكون المخروط في الإسقاط المتعامد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


يضبط أول عقدة أب، إذا تم ضبط أول عقدة أب، سيُفصل هذا الكيان عن عقد الأب الأخرى.

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

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


يضبط وضع توجيه المخروط. هذه الخاصية تعمل فقط عندما يكون [getTarget](../../com.aspose.threed/frustum\#getTarget) فارغًا. إذا كانت القيمة هي [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET)، يتم دائمًا حساب الاتجاه بواسطة الخاصية [getLookAt](../../com.aspose.threed/frustum\#getLookAt). وإلا فإن [getLookAt](../../com.aspose.threed/frustum\#getLookAt) يتم دائمًا حسابه بواسطة [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | القيمة الجديدة |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public void setTarget(Node value)
```


يضبط الهدف الذي تنظر إليه الكاميرا. إذا كان المستخدم يدعم هذه الخاصية، يجب أن تكون قبل خاصية [getLookAt](../../com.aspose.threed/frustum\#getLookAt).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | القيمة الجديدة |

### setUp(Vector3 value) {#setUp-com.aspose.threed.Vector3-}
```
public void setUp(Vector3 value)
```


يضبط اتجاه الأعلى للكاميرا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

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

