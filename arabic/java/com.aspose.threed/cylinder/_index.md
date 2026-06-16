---
title: "Cylinder"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "اسطوانة معلمة."
type: docs
weight: 40
url: /ar/java/com.aspose.threed/cylinder/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Cylinder extends Primitive
```

أسطوانة معلمة. يمكن استخدامها أيضاً لتمثيل المخروط عندما يكون أحد القيم radiusTop/radiusBottom صفرًا.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Cylinder()](#Cylinder--) | ينشئ مثيلاً جديداً من الفئة [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(double radius, double height)](#Cylinder-double-double-) | ينشئ مثيلاً جديداً من الفئة [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(double radiusTop, double radiusBottom, double height)](#Cylinder-double-double-double-) | ينشئ مثيلاً جديداً من الفئة [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)](#Cylinder-double-double-double-int-int-boolean-) | ينشئ مثيلاً جديداً من الفئة [Cylinder](../../com.aspose.threed/cylinder). |
| [Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)](#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-) | ينشئ مثيلاً جديداً من الفئة [Cylinder](../../com.aspose.threed/cylinder). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getBoundingBox()](#getBoundingBox--) | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| [getCastShadows()](#getCastShadows--) | يحصل على ما إذا كان هذا الشكل يمكنه إلقاء الظل |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | يحصل على المفتاح الخاص بعارض الكيان المسجل في العارض. |
| [getExcluded()](#getExcluded--) | يحصل على ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [getGenerateFanCylinder()](#getGenerateFanCylinder--) | يُحصل على ما إذا كان سيتم إنشاء أسطوانة بنمط المروحة عندما تكون ThetaLength أقل من 2\*PI، وإلا لن يتم قطع النموذج. |
| [getHeight()](#getHeight--) | يُحصل على ارتفاع الأسطوانة. |
| [getHeightSegments()](#getHeightSegments--) | يحصل على شرائح الارتفاع. |
| [getName()](#getName--) | يحصل على الاسم. |
| [getOffsetBottom()](#getOffsetBottom--) | يُحصل على إزاحة تحويل الرؤوس للجانب السفلي. |
| [getOffsetTop()](#getOffsetTop--) | يُحصل على إزاحة تحويل الرؤوس للجانب العلوي. |
| [getOpenEnded()](#getOpenEnded--) | يُحصل على قيمة تشير إلى ما إذا كانت هذه [Cylinder](../../com.aspose.threed/cylinder) مفتوحة من الطرف. |
| [getParentNode()](#getParentNode--) | يحصل على أول عقدة أب، إذا تم تعيين أول عقدة أب، سيُفصل هذا الكيان عن عقد الأب الأخرى. |
| [getParentNodes()](#getParentNodes--) | يحصل على جميع عقد الأب، يمكن إرفاق كيان بعدة عقد أب لتكرار الهندسة. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getRadialSegments()](#getRadialSegments--) | يُحصل على القطاعات الشعاعية. |
| [getRadiusBottom()](#getRadiusBottom--) | يُحصل على نصف قطر الغطاء السفلي للأسطوانة. |
| [getRadiusTop()](#getRadiusTop--) | يحصل على نصف قطر غطاء أعلى الأسطوانة. |
| [getReceiveShadows()](#getReceiveShadows--) | يحصل على ما إذا كان هذا الشكل يمكنه استقبال الظل. |
| [getScene()](#getScene--) | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [getShearBottom()](#getShearBottom--) | يحصل على تحويل القص للجانب السفلي، المتجه يخزن قيم قص (محور x، محور z) المقاسة بالراديان، القيمة الافتراضية هي (0, 0) |
| [getShearTop()](#getShearTop--) | يحصل على تحويل القص للجانب العلوي، المتجه يخزن قيم قص (محور x، محور z) المقاسة بالراديان، القيمة الافتراضية هي (0, 0) |
| [getThetaLength()](#getThetaLength--) | يحصل على طول الثيتا. |
| [getThetaStart()](#getThetaStart--) | يحصل على بداية الثيتا. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | يضبط ما إذا كان هذا الشكل يمكنه إلقاء الظل |
| [setExcluded(boolean value)](#setExcluded-boolean-) | يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [setGenerateFanCylinder(boolean value)](#setGenerateFanCylinder-boolean-) | يضبط ما إذا كان سيتم إنشاء أسطوانة بنمط المروحة عندما يكون ThetaLength أقل من 2\*PI، وإلا لن يتم قطع النموذج. |
| [setHeight(double value)](#setHeight-double-) | يضبط ارتفاع الأسطوانة. |
| [setHeightSegments(int value)](#setHeightSegments-int-) | يضبط مقاطع الارتفاع. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setOffsetBottom(Vector3 value)](#setOffsetBottom-com.aspose.threed.Vector3-) | يضبط إزاحة تحويل الرؤوس للجانب السفلي. |
| [setOffsetTop(Vector3 value)](#setOffsetTop-com.aspose.threed.Vector3-) | يضبط إزاحة تحويل الرؤوس للجانب العلوي. |
| [setOpenEnded(boolean value)](#setOpenEnded-boolean-) | يضبط قيمة تشير إلى ما إذا كانت هذه [Cylinder](../../com.aspose.threed/cylinder) مفتوحة من الطرف. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | يضبط أول عقدة أب، إذا تم ضبط أول عقدة أب، سيُفصل هذا الكيان عن عقد الأب الأخرى. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setRadialSegments(int value)](#setRadialSegments-int-) | يضبط القطاعات الشعاعية. |
| [setRadiusBottom(double value)](#setRadiusBottom-double-) | يضبط نصف قطر غطاء أسفل الأسطوانة. |
| [setRadiusTop(double value)](#setRadiusTop-double-) | يضبط نصف قطر غطاء أعلى الأسطوانة. |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | يضبط ما إذا كان هذا الشكل يمكنه استقبال الظل. |
| [setShearBottom(Vector2 value)](#setShearBottom-com.aspose.threed.Vector2-) | يضبط تحويل القص للجانب السفلي، المتجه يخزن قيم قص (محور x، محور z) المقاسة بالراديان، القيمة الافتراضية هي (0, 0) |
| [setShearTop(Vector2 value)](#setShearTop-com.aspose.threed.Vector2-) | يضبط تحويل القص للجانب العلوي، المتجه يخزن قيم قص (محور x، محور z) المقاسة بالراديان، القيمة الافتراضية هي (0, 0) |
| [setThetaLength(double value)](#setThetaLength-double-) | يضبط طول theta. |
| [setThetaStart(double value)](#setThetaStart-double-) | يضبط بداية theta. |
| [toMesh()](#toMesh--) | تحويل الكائن الحالي إلى شبكة |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Cylinder() {#Cylinder--}
```
public Cylinder()
```


ينشئ مثيلاً جديداً من الفئة [Cylinder](../../com.aspose.threed/cylinder).

### Cylinder(double radius, double height) {#Cylinder-double-double-}
```
public Cylinder(double radius, double height)
```


ينشئ مثيلاً جديداً من الفئة [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| radius | double | نصف قطر الغطاء العلوي والسفلي. |
| الارتفاع | double | الارتفاع. |

### Cylinder(double radiusTop, double radiusBottom, double height) {#Cylinder-double-double-double-}
```
public Cylinder(double radiusTop, double radiusBottom, double height)
```


ينشئ مثيلاً جديداً من الفئة [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| radiusTop | double | نصف القطر العلوي. |
| radiusBottom | double | نصف القطر السفلي. |
| الارتفاع | double | الارتفاع. |

### Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded) {#Cylinder-double-double-double-int-int-boolean-}
```
public Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)
```


ينشئ مثيلاً جديداً من الفئة [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| radiusTop | double | نصف قطر غطاء أعلى الأسطوانة. |
| radiusBottom | double | نصف قطر غطاء أسفل الأسطوانة. |
| الارتفاع | double | ارتفاع الأسطوانة. |
| radialSegments | int | القطاعات الشعاعية لكل من الدوائر العلوية والسفلية.. |
| heightSegments | int | مقاطع الارتفاع. |
| openEnded | boolean | إذا تم تعيينه إلى  true  فإن الأسطوانة لن تحتوي على أغطية سفلية/عليا.. |

### Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength) {#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-}
```
public Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)
```


ينشئ مثيلاً جديداً من الفئة [Cylinder](../../com.aspose.threed/cylinder).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم هذا الكائن |
| radiusTop | double | نصف قطر غطاء أعلى الأسطوانة. |
| radiusBottom | double | نصف قطر غطاء أسفل الأسطوانة. |
| الارتفاع | double | ارتفاع الأسطوانة. |
| radialSegments | int | القطاعات الشعاعية لكل من الدوائر العلوية والسفلية.. |
| heightSegments | int | مقاطع الارتفاع. |
| openEnded | boolean | إذا تم تعيينه إلى  true  فإن الأسطوانة لن تحتوي على أغطية سفلية/عليا.. |
| thetaStart | double | بداية Theta. |
| thetaLength | double | طول Theta. |

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
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


يحصل على ما إذا كان هذا الشكل يمكنه إلقاء الظل

**Returns:**
boolean - ما إذا كان هذا الشكل الهندسي يمكنه إلقاء الظل
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
### getGenerateFanCylinder() {#getGenerateFanCylinder--}
```
public boolean getGenerateFanCylinder()
```


يُحصل على ما إذا كان سيتم إنشاء أسطوانة بنمط المروحة عندما تكون ThetaLength أقل من 2\*PI، وإلا لن يتم قطع النموذج.

**Returns:**
منطقي - ما إذا كان سيتم إنشاء أسطوانة بنمط مروحة عندما تكون ThetaLength أقل من 2\*PI، وإلا لن يتم قطع النموذج.
### getHeight() {#getHeight--}
```
public double getHeight()
```


يُحصل على ارتفاع الأسطوانة.

**Returns:**
مضاعف - ارتفاع الأسطوانة.
### getHeightSegments() {#getHeightSegments--}
```
public int getHeightSegments()
```


يحصل على شرائح الارتفاع.

**Returns:**
int - مقاطع الارتفاع.
### getName() {#getName--}
```
public String getName()
```


يحصل على الاسم.

**Returns:**
java.lang.String - الاسم.
### getOffsetBottom() {#getOffsetBottom--}
```
public Vector3 getOffsetBottom()
```


يُحصل على إزاحة تحويل الرؤوس للجانب السفلي.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the bottom side.
### getOffsetTop() {#getOffsetTop--}
```
public Vector3 getOffsetTop()
```


يُحصل على إزاحة تحويل الرؤوس للجانب العلوي.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the top side.
### getOpenEnded() {#getOpenEnded--}
```
public boolean getOpenEnded()
```


يحصل على قيمة تشير إلى ما إذا كانت هذه [Cylinder](../../com.aspose.threed/cylinder) مفتوحة النهاية. القيمة الافتراضية هي false.

**Returns:**
منطقي - قيمة تشير إلى ما إذا كانت هذه [Cylinder](../../com.aspose.threed/cylinder) مفتوحة النهاية. القيمة الافتراضية هي false.
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
### getRadialSegments() {#getRadialSegments--}
```
public int getRadialSegments()
```


يُحصل على القطاعات الشعاعية.

**Returns:**
عدد صحيح - القطاعات الشعاعية.
### getRadiusBottom() {#getRadiusBottom--}
```
public double getRadiusBottom()
```


يُحصل على نصف قطر الغطاء السفلي للأسطوانة.

**Returns:**
مضاعف - نصف قطر غطاء أسفل الأسطوانة.
### getRadiusTop() {#getRadiusTop--}
```
public double getRadiusTop()
```


يحصل على نصف قطر غطاء أعلى الأسطوانة.

**Returns:**
مضاعف - نصف قطر غطاء أعلى الأسطوانة.
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


يحصل على ما إذا كان هذا الشكل يمكنه استقبال الظل.

**Returns:**
boolean - ما إذا كان هذا الشكل الهندسي يمكنه استقبال الظل.
### getScene() {#getScene--}
```
public Scene getScene()
```


يحصل على المشهد الذي ينتمي إليه هذا الكائن

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShearBottom() {#getShearBottom--}
```
public Vector2 getShearBottom()
```


يحصل على تحويل القص للجانب السفلي، المتجه يخزن قيم قص (محور x، محور z) المقاسة بالراديان، القيمة الافتراضية هي (0, 0)

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the bottom side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getShearTop() {#getShearTop--}
```
public Vector2 getShearTop()
```


يحصل على تحويل القص للجانب العلوي، المتجه يخزن قيم قص (محور x، محور z) المقاسة بالراديان، القيمة الافتراضية هي (0, 0)

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the top side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getThetaLength() {#getThetaLength--}
```
public double getThetaLength()
```


يحصل على طول الثيتا. القيمة الافتراضية هي 2\\u03c0.

**Returns:**
مضاعف - طول الثيتا. القيمة الافتراضية هي 2\\u03c0.
### getThetaStart() {#getThetaStart--}
```
public double getThetaStart()
```


يحصل على بداية الثيتا. القيمة الافتراضية هي 0.

**Returns:**
مضاعف - بداية الثيتا. القيمة الافتراضية هي 0.
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
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


يضبط ما إذا كان هذا الشكل يمكنه إلقاء الظل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setGenerateFanCylinder(boolean value) {#setGenerateFanCylinder-boolean-}
```
public void setGenerateFanCylinder(boolean value)
```


يضبط ما إذا كان سيتم إنشاء أسطوانة بنمط المروحة عندما يكون ThetaLength أقل من 2\*PI، وإلا لن يتم قطع النموذج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


يضبط ارتفاع الأسطوانة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setHeightSegments(int value) {#setHeightSegments-int-}
```
public void setHeightSegments(int value)
```


يضبط مقاطع الارتفاع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


يضبط الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setOffsetBottom(Vector3 value) {#setOffsetBottom-com.aspose.threed.Vector3-}
```
public void setOffsetBottom(Vector3 value)
```


يضبط إزاحة تحويل الرؤوس للجانب السفلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setOffsetTop(Vector3 value) {#setOffsetTop-com.aspose.threed.Vector3-}
```
public void setOffsetTop(Vector3 value)
```


يضبط إزاحة تحويل الرؤوس للجانب العلوي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setOpenEnded(boolean value) {#setOpenEnded-boolean-}
```
public void setOpenEnded(boolean value)
```


يضبط قيمة تشير إلى ما إذا كانت هذه [Cylinder](../../com.aspose.threed/cylinder) مفتوحة النهاية. القيمة الافتراضية هي false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

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

### setRadialSegments(int value) {#setRadialSegments-int-}
```
public void setRadialSegments(int value)
```


يضبط القطاعات الشعاعية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setRadiusBottom(double value) {#setRadiusBottom-double-}
```
public void setRadiusBottom(double value)
```


يضبط نصف قطر غطاء أسفل الأسطوانة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setRadiusTop(double value) {#setRadiusTop-double-}
```
public void setRadiusTop(double value)
```


يضبط نصف قطر غطاء أعلى الأسطوانة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


يضبط ما إذا كان هذا الشكل يمكنه استقبال الظل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setShearBottom(Vector2 value) {#setShearBottom-com.aspose.threed.Vector2-}
```
public void setShearBottom(Vector2 value)
```


يضبط تحويل القص للجانب السفلي، المتجه يخزن قيم قص (محور x، محور z) المقاسة بالراديان، القيمة الافتراضية هي (0, 0)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | القيمة الجديدة |

### setShearTop(Vector2 value) {#setShearTop-com.aspose.threed.Vector2-}
```
public void setShearTop(Vector2 value)
```


يضبط تحويل القص للجانب العلوي، المتجه يخزن قيم قص (محور x، محور z) المقاسة بالراديان، القيمة الافتراضية هي (0, 0)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | القيمة الجديدة |

### setThetaLength(double value) {#setThetaLength-double-}
```
public void setThetaLength(double value)
```


يضبط طول الثيتا. القيمة الافتراضية هي 2\\u03c0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setThetaStart(double value) {#setThetaStart-double-}
```
public void setThetaStart(double value)
```


يضبط بداية الثيتا. القيمة الافتراضية هي 0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


تحويل الكائن الحالي إلى شبكة

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The mesh.
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

