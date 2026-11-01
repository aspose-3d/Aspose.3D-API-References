---
title: "Camera"
second_title: "مرجع Aspose.3D لـ Java API"
description: "الكاميرا تصف نقطة العين للمشاهد الذي ينظر إلى المشهد."
type: docs
weight: 28
url: /ar/java/com.aspose.threed/camera/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)

**All Implemented Interfaces:**
[com.aspose.threed.IOrientable](../../com.aspose.threed/iorientable)
```
public class Camera extends Frustum implements IOrientable
```

الكاميرا تصف نقطة العين للمشاهد الذي ينظر إلى المشهد.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Camera()](#Camera--) | يُهيئ نسخة جديدة من الفئة [Camera](../../com.aspose.threed/camera). |
| [Camera(ProjectionType projectionType)](#Camera-com.aspose.threed.ProjectionType-) | يُهيئ نسخة جديدة من الفئة [Camera](../../com.aspose.threed/camera). |
| [Camera(String name)](#Camera-java.lang.String-) | يُهيئ نسخة جديدة من الفئة [Camera](../../com.aspose.threed/camera). |
| [Camera(String name, ProjectionType projectionType)](#Camera-java.lang.String-com.aspose.threed.ProjectionType-) | يُهيئ نسخة جديدة من الفئة [Camera](../../com.aspose.threed/camera). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getApertureMode()](#getApertureMode--) | يحصل على وضع فتحة الكاميرا |
| [getAspect()](#getAspect--) | يحصل على نسبة أبعاد الـ frustum |
| [getAspectRatio()](#getAspectRatio--) | يحصل على نسبة أبعاد سطح العرض. |
| [getBoundingBox()](#getBoundingBox--) | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | يحصل على الاتجاه الذي تنظر إليه الكاميرا. |
| [getEntityRendererKey()](#getEntityRendererKey--) | يحصل على المفتاح الخاص بعارض الكيان المسجل في العارض |
| [getExcluded()](#getExcluded--) | يحصل على ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [getFarPlane()](#getFarPlane--) | يحصل على مسافة المستوى البعيد للـ frustum. |
| [getFieldOfView()](#getFieldOfView--) | يحصل على مجال رؤية الكاميرا بالدرجات، تُستخدم هذه الخاصية فقط عندما يكون ApertureMode هو [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) أو [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) |
| [getFieldOfViewX()](#getFieldOfViewX--) | يحصل على مجال رؤية الكاميرا الأفقي بالدرجات، تُستخدم هذه الخاصية فقط عندما يكون ApertureMode هو [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [getFieldOfViewY()](#getFieldOfViewY--) | يحصل على مجال رؤية الكاميرا العمودي بالدرجات، تُستخدم هذه الخاصية فقط عندما يكون ApertureMode هو [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [getHeight()](#getHeight--) | يحصل على ارتفاع سطح العرض بوحدة البوصة |
| [getLookAt()](#getLookAt--) | يحصل على الموضع المهتم الذي تنظر إليه الكاميرا. |
| [getMagnification()](#getMagnification--) | يحصل على التكبير المستخدم في الكاميرا المتعامدة |
| [getName()](#getName--) | يحصل على الاسم. |
| [getNearPlane()](#getNearPlane--) | يحصل على مسافة المستوى القريب للمخروط. |
| [getOrthoHeight()](#getOrthoHeight--) | يحصل على الارتفاع عندما يكون المخروط في الإسقاط المتعامد. |
| [getParentNode()](#getParentNode--) | يحصل على أول عقدة أصل، إذا تم تعيين أول عقدة أصل، سيتم فصل هذا الكيان عن عقد الأصل الأخرى. |
| [getParentNodes()](#getParentNodes--) | يحصل على جميع عقد الأصل، يمكن إرفاق كيان بعدة عقد أصل لتكرار الهندسة |
| [getProjectionType()](#getProjectionType--) | يحصل على نوع إسقاط الكاميرا. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getRotationMode()](#getRotationMode--) | يحصل على وضعية توجيه المخروط. هذه الخاصية تعمل فقط عندما يكون [getTarget](../../com.aspose.threed/frustum\#getTarget) فارغًا. |
| [getScene()](#getScene--) | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [getTarget()](#getTarget--) | يحصل على الهدف الذي تنظر إليه الكاميرا. |
| [getUp()](#getUp--) | يحصل على اتجاه الأعلى للكاميرا |
| [getWidth()](#getWidth--) | يحصل على عرض سطح العرض بوحدة البوصة |
| [hashCode()](#hashCode--) |  |
| [moveForward(double distance)](#moveForward-double-) | حرك الكاميرا إلى الأمام باتجاه اتجاهها أو هدفها. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | أزل الخاصية المحددة بالاسم |
| [setApertureMode(ApertureMode value)](#setApertureMode-com.aspose.threed.ApertureMode-) | يضبط وضع فتحة الكاميرا |
| [setAspect(double value)](#setAspect-double-) | يضبط نسبة العرض إلى الارتفاع للمخروط |
| [setAspectRatio(double value)](#setAspectRatio-double-) | يضبط نسبة أبعاد سطح العرض. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | يضبط الاتجاه الذي تنظر إليه الكاميرا. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [setFarPlane(double value)](#setFarPlane-double-) | يضبط مسافة المستوى البعيد للمخروط. |
| [setFieldOfView(double value)](#setFieldOfView-double-) | يضبط مجال رؤية الكاميرا بالدرجات، تُستخدم هذه الخاصية فقط عندما يكون ApertureMode هو [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) أو [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) |
| [setFieldOfViewX(double value)](#setFieldOfViewX-double-) | يضبط مجال رؤية الكاميرا الأفقي بالدرجات، تُستخدم هذه الخاصية فقط عندما يكون ApertureMode هو [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [setFieldOfViewY(double value)](#setFieldOfViewY-double-) | يضبط مجال رؤية الكاميرا العمودي بالدرجات، تُستخدم هذه الخاصية فقط عندما يكون ApertureMode هو [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [setHeight(double value)](#setHeight-double-) | يضبط ارتفاع سطح العرض بوحدة البوصة |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | يضبط الموضع المهتم الذي تنظر إليه الكاميرا. |
| [setMagnification(Vector2 value)](#setMagnification-com.aspose.threed.Vector2-) | يضبط التكبير المستخدم في الكاميرا المتعامدة |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setNearPlane(double value)](#setNearPlane-double-) | يضبط مسافة المستوى القريب للمخروط. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | يضبط الارتفاع عندما يكون المخروط في الإسقاط المتعامد. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | يضبط أول عقدة أصل، إذا تم تعيين أول عقدة أصل، سيتم فصل هذا الكيان عن عقد الأصل الأخرى. |
| [setProjectionType(ProjectionType value)](#setProjectionType-com.aspose.threed.ProjectionType-) | يضبط نوع إسقاط الكاميرا. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | يضبط وضعية توجيه المخروط. هذه الخاصية تعمل فقط عندما تكون [getTarget](../../com.aspose.threed/frustum\#getTarget) فارغة. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | يضبط الهدف الذي تنظر إليه الكاميرا. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | يضبط اتجاه الأعلى للكاميرا |
| [setWidth(double value)](#setWidth-double-) | يضبط عرض سطح العرض بوحدة البوصة |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Camera() {#Camera--}
```
public Camera()
```


يُهيئ نسخة جديدة من الفئة [Camera](../../com.aspose.threed/camera).

### Camera(ProjectionType projectionType) {#Camera-com.aspose.threed.ProjectionType-}
```
public Camera(ProjectionType projectionType)
```


يُهيئ نسخة جديدة من الفئة [Camera](../../com.aspose.threed/camera).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | نوع الإسقاط. |

### Camera(String name) {#Camera-java.lang.String-}
```
public Camera(String name)
```


يُهيئ نسخة جديدة من الفئة [Camera](../../com.aspose.threed/camera).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم. |

### Camera(String name, ProjectionType projectionType) {#Camera-java.lang.String-com.aspose.threed.ProjectionType-}
```
public Camera(String name, ProjectionType projectionType)
```


يُهيئ نسخة جديدة من الفئة [Camera](../../com.aspose.threed/camera).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم. |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | نوع الإسقاط. |

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
### getApertureMode() {#getApertureMode--}
```
public ApertureMode getApertureMode()
```


يحصل على وضع فتحة الكاميرا

**Returns:**
[ApertureMode](../../com.aspose.threed/aperturemode) - the camera's aperture mode
### getAspect() {#getAspect--}
```
public double getAspect()
```


يحصل على نسبة أبعاد الـ frustum

**Returns:**
double - نسبة العرض إلى الارتفاع للمخروط
### getAspectRatio() {#getAspectRatio--}
```
public double getAspectRatio()
```


يحصل على نسبة أبعاد سطح العرض.

**Returns:**
double - نسبة أبعاد سطح العرض.
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


يحصل على الاتجاه الذي تنظر إليه الكاميرا. التغييرات في هذه الخاصية ستؤثر أيضًا على [getLookAt](../../com.aspose.threed/frustum\#getLookAt) و [getTarget](../../com.aspose.threed/frustum\#getTarget).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the camera is looking at. Changes on this property will also affects the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) and [getTarget](../../com.aspose.threed/frustum\#getTarget).
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
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


يحصل على مسافة المستوى البعيد للـ frustum.

**Returns:**
double - مسافة المستوى البعيد للمخروط.
### getFieldOfView() {#getFieldOfView--}
```
public double getFieldOfView()
```


يحصل على مجال رؤية الكاميرا بالدرجات، تُستخدم هذه الخاصية فقط عندما يكون ApertureMode هو [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) أو [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)

**Returns:**
double - مجال رؤية الكاميرا بالدرجات، تُستخدم هذه الخاصية فقط عندما يكون ApertureMode هو [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) أو [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)
### getFieldOfViewX() {#getFieldOfViewX--}
```
public double getFieldOfViewX()
```


يحصل على مجال رؤية الكاميرا الأفقي بالدرجات، تُستخدم هذه الخاصية فقط عندما يكون ApertureMode هو [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Returns:**
double - مجال رؤية الكاميرا الأفقي بالدرجات، تُستخدم هذه الخاصية فقط عندما يكون ApertureMode هو [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)
### getFieldOfViewY() {#getFieldOfViewY--}
```
public double getFieldOfViewY()
```


يحصل على مجال رؤية الكاميرا العمودي بالدرجات، تُستخدم هذه الخاصية فقط عندما يكون ApertureMode هو [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Returns:**
double - مجال رؤية الكاميرا العمودي بالدرجات، تُستخدم هذه الخاصية فقط عندما يكون ApertureMode هو [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)
### getHeight() {#getHeight--}
```
public double getHeight()
```


يحصل على ارتفاع سطح العرض بوحدة البوصة

**Returns:**
double - ارتفاع سطح العرض بوحدة البوصة
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


يحصل على الموضع المهتم الذي تنظر إليه الكاميرا.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getMagnification() {#getMagnification--}
```
public Vector2 getMagnification()
```


يحصل على التكبير المستخدم في الكاميرا المتعامدة

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the magnification used in orthographic camera
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
### getProjectionType() {#getProjectionType--}
```
public ProjectionType getProjectionType()
```


يحصل على نوع إسقاط الكاميرا. بشكل افتراضي يتم استخدام الإسقاط المنظوري.

**Returns:**
[ProjectionType](../../com.aspose.threed/projectiontype) - the camera's projection type. By default the perspective projection is used.
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


يحصل على وضعية توجيه المخروط. هذه الخاصية تعمل فقط عندما تكون [getTarget](../../com.aspose.threed/frustum\#getTarget) فارغة. إذا كانت القيمة هي [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET)، يتم دائمًا حساب الاتجاه بواسطة الخاصية [getLookAt](../../com.aspose.threed/frustum\#getLookAt). وإلا فإن [getLookAt](../../com.aspose.threed/frustum\#getLookAt) يتم دائمًا حسابه بواسطة [getDirection](../../com.aspose.threed/frustum\#getDirection).

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
### getWidth() {#getWidth--}
```
public double getWidth()
```


يحصل على عرض سطح العرض بوحدة البوصة

**Returns:**
double - عرض مستوى العرض مقاسًا بالبوصة
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### moveForward(double distance) {#moveForward-double-}
```
public void moveForward(double distance)
```


حرك الكاميرا إلى الأمام باتجاه اتجاهها أو هدفها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسافة | double | المدة التي يتحرك فيها إلى الأمام |

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
### setApertureMode(ApertureMode value) {#setApertureMode-com.aspose.threed.ApertureMode-}
```
public void setApertureMode(ApertureMode value)
```


يضبط وضع فتحة الكاميرا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ApertureMode](../../com.aspose.threed/aperturemode) | قيمة جديدة |

### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


يضبط نسبة العرض إلى الارتفاع للمخروط

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | قيمة جديدة |

### setAspectRatio(double value) {#setAspectRatio-double-}
```
public void setAspectRatio(double value)
```


يضبط نسبة أبعاد سطح العرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | قيمة جديدة |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


يضبط الاتجاه الذي تنظر إليه الكاميرا. التغييرات في هذه الخاصية ستؤثر أيضًا على [getLookAt](../../com.aspose.threed/frustum\#getLookAt) و [getTarget](../../com.aspose.threed/frustum\#getTarget).

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

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


يضبط مسافة المستوى البعيد للمخروط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | قيمة جديدة |

### setFieldOfView(double value) {#setFieldOfView-double-}
```
public void setFieldOfView(double value)
```


يضبط مجال رؤية الكاميرا بالدرجات، تُستخدم هذه الخاصية فقط عندما يكون ApertureMode هو [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) أو [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | قيمة جديدة |

### setFieldOfViewX(double value) {#setFieldOfViewX-double-}
```
public void setFieldOfViewX(double value)
```


يضبط مجال رؤية الكاميرا الأفقي بالدرجات، تُستخدم هذه الخاصية فقط عندما يكون ApertureMode هو [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | قيمة جديدة |

### setFieldOfViewY(double value) {#setFieldOfViewY-double-}
```
public void setFieldOfViewY(double value)
```


يضبط مجال رؤية الكاميرا العمودي بالدرجات، تُستخدم هذه الخاصية فقط عندما يكون ApertureMode هو [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | قيمة جديدة |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


يضبط ارتفاع سطح العرض بوحدة البوصة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | قيمة جديدة |

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


يضبط الموضع المهتم الذي تنظر إليه الكاميرا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | قيمة جديدة |

### setMagnification(Vector2 value) {#setMagnification-com.aspose.threed.Vector2-}
```
public void setMagnification(Vector2 value)
```


يضبط التكبير المستخدم في الكاميرا المتعامدة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | قيمة جديدة |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


يضبط الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | قيمة جديدة |

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


يضبط مسافة المستوى القريب للمخروط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | قيمة جديدة |

### setOrthoHeight(double value) {#setOrthoHeight-double-}
```
public void setOrthoHeight(double value)
```


يضبط الارتفاع عندما يكون المخروط في الإسقاط المتعامد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | قيمة جديدة |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


يضبط أول عقدة أصل، إذا تم تعيين أول عقدة أصل، سيتم فصل هذا الكيان عن عقد الأصل الأخرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | قيمة جديدة |

### setProjectionType(ProjectionType value) {#setProjectionType-com.aspose.threed.ProjectionType-}
```
public void setProjectionType(ProjectionType value)
```


يضبط نوع إسقاط الكاميرا. بشكل افتراضي يتم استخدام الإسقاط المنظوري.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ProjectionType](../../com.aspose.threed/projectiontype) | قيمة جديدة |

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

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


يضبط وضعية توجيه المخروط. هذه الخاصية تعمل فقط عندما تكون [getTarget](../../com.aspose.threed/frustum\#getTarget) فارغة. إذا كانت القيمة هي [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET)، يتم دائمًا حساب الاتجاه بواسطة الخاصية [getLookAt](../../com.aspose.threed/frustum\#getLookAt). وإلا فإن [getLookAt](../../com.aspose.threed/frustum\#getLookAt) يتم دائمًا حسابه بواسطة [getDirection](../../com.aspose.threed/frustum\#getDirection).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | قيمة جديدة |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public void setTarget(Node value)
```


يضبط الهدف الذي تنظر إليه الكاميرا. إذا كان المستخدم يدعم هذه الخاصية، يجب أن تكون قبل خاصية [getLookAt](../../com.aspose.threed/frustum\#getLookAt).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | قيمة جديدة |

### setUp(Vector3 value) {#setUp-com.aspose.threed.Vector3-}
```
public void setUp(Vector3 value)
```


يضبط اتجاه الأعلى للكاميرا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | قيمة جديدة |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


يضبط عرض سطح العرض بوحدة البوصة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | قيمة جديدة |

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

