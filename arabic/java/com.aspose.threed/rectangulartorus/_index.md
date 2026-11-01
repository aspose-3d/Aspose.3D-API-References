---
title: "RectangularTorus"
second_title: "مرجع Aspose.3D لـ Java API"
description: "طوق مستطيل معلمَّ."
type: docs
weight: 146
url: /ar/java/com.aspose.threed/rectangulartorus/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class RectangularTorus extends Primitive
```

طوق مستطيل معلمَّ.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [RectangularTorus()](#RectangularTorus--) | منشئ [RectangularTorus](../../com.aspose.threed/rectangulartorus) |
| [RectangularTorus(String name)](#RectangularTorus-java.lang.String-) | منشئ [RectangularTorus](../../com.aspose.threed/rectangulartorus) |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getAngleStart()](#getAngleStart--) | زاوية البداية للقوس، مقاسة بالراديان. |
| [getArc()](#getArc--) | الزاوية الكلية للقوس، مقاسة بالراديان. |
| [getBoundingBox()](#getBoundingBox--) | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| [getCastShadows()](#getCastShadows--) | يحصل على ما إذا كان هذا الشكل يمكنه إلقاء الظل |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | يحصل على المفتاح الخاص بعارض الكيان المسجل في العارض |
| [getExcluded()](#getExcluded--) | يحصل على ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [getHeight()](#getHeight--) | ارتفاع الطارة المستطيلة. |
| [getInnerRadius()](#getInnerRadius--) | نصف القطر الداخلي للطارة المستطيلة القيمة الافتراضية هي 17 |
| [getName()](#getName--) | يحصل على الاسم. |
| [getOuterRadius()](#getOuterRadius--) | نصف القطر الخارجي للطارة المستطيلة القيمة الافتراضية هي 20 |
| [getParentNode()](#getParentNode--) | يحصل على أول عقدة أصل، إذا تم تعيين أول عقدة أصل، سيتم فصل هذا الكيان عن عقد الأصل الأخرى. |
| [getParentNodes()](#getParentNodes--) | يحصل على جميع عقد الأصل، يمكن إرفاق كيان بعدة عقد أصل لتكرار الهندسة |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getRadialSegments()](#getRadialSegments--) | الأقسام الشعاعية، القيمة الافتراضية هي 10 |
| [getReceiveShadows()](#getReceiveShadows--) | يحصل على ما إذا كان هذا الشكل يمكنه استقبال الظل. |
| [getScene()](#getScene--) | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | أزل الخاصية المحددة بالاسم |
| [setAngleStart(double value)](#setAngleStart-double-) | زاوية البداية للقوس، مقاسة بالراديان. |
| [setArc(double value)](#setArc-double-) | الزاوية الكلية للقوس، مقاسة بالراديان. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | يضبط ما إذا كان هذا الشكل يمكنه إلقاء الظل |
| [setExcluded(boolean value)](#setExcluded-boolean-) | يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [setHeight(double value)](#setHeight-double-) | ارتفاع الطارة المستطيلة. |
| [setInnerRadius(double value)](#setInnerRadius-double-) | نصف القطر الداخلي للطارة المستطيلة القيمة الافتراضية هي 17 |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setOuterRadius(double value)](#setOuterRadius-double-) | نصف القطر الخارجي للطارة المستطيلة القيمة الافتراضية هي 20 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | يضبط أول عقدة أصل، إذا تم تعيين أول عقدة أصل، سيتم فصل هذا الكيان عن عقد الأصل الأخرى. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setRadialSegments(int value)](#setRadialSegments-int-) | الأقسام الشعاعية، القيمة الافتراضية هي 10 |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | يضبط ما إذا كان هذا الشكل يمكنه استقبال الظل. |
| [toMesh()](#toMesh--) | حوّل هذا البدائي إلى [Mesh](../../com.aspose.threed/mesh) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangularTorus() {#RectangularTorus--}
```
public RectangularTorus()
```


منشئ [RectangularTorus](../../com.aspose.threed/rectangulartorus)

### RectangularTorus(String name) {#RectangularTorus-java.lang.String-}
```
public RectangularTorus(String name)
```


منشئ [RectangularTorus](../../com.aspose.threed/rectangulartorus)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

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
### getAngleStart() {#getAngleStart--}
```
public double getAngleStart()
```


زاوية البداية للقوس، مقاسة بالراديان. القيمة الافتراضية هي 0

**Returns:**
double - زاوية البداية للقوس، تُقاس بالراديان. القيمة الافتراضية هي 0
### getArc() {#getArc--}
```
public double getArc()
```


زاوية القوس الكلية، تُقاس بالراديان. القيمة الافتراضية هي PI

**Returns:**
double - زاوية القوس الكلية، تُقاس بالراديان. القيمة الافتراضية هي PI
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
### getHeight() {#getHeight--}
```
public double getHeight()
```


ارتفاع الـ torus المستطيل. القيمة الافتراضية هي 20

**Returns:**
double - ارتفاع الـ torus المستطيل. القيمة الافتراضية هي 20
### getInnerRadius() {#getInnerRadius--}
```
public double getInnerRadius()
```


نصف القطر الداخلي للطارة المستطيلة القيمة الافتراضية هي 17

**Returns:**
double - نصف القطر الداخلي للـ torus المستطيل. القيمة الافتراضية هي 17
### getName() {#getName--}
```
public String getName()
```


يحصل على الاسم.

**Returns:**
java.lang.String - الاسم.
### getOuterRadius() {#getOuterRadius--}
```
public double getOuterRadius()
```


نصف القطر الخارجي للطارة المستطيلة القيمة الافتراضية هي 20

**Returns:**
double - نصف القطر الخارجي للـ torus المستطيل. القيمة الافتراضية هي 20
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
### getRadialSegments() {#getRadialSegments--}
```
public int getRadialSegments()
```


الأقسام الشعاعية، القيمة الافتراضية هي 10

**Returns:**
int - القطاعات الشعاعية، القيمة الافتراضية هي 10
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


يحصل على ما إذا كان هذا الشكل يمكنه استقبال الظل.

**Returns:**
boolean - ما إذا كان هذا الشكل الهندسي يمكنه تلقي الظل.
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


أزل الخاصية المحددة بالاسم

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| خاصية | java.lang.String | أي خاصية تريد إزالتها |

**Returns:**
boolean - true إذا تم إزالة الخاصية بنجاح
### setAngleStart(double value) {#setAngleStart-double-}
```
public void setAngleStart(double value)
```


زاوية البداية للقوس، مقاسة بالراديان. القيمة الافتراضية هي 0

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | قيمة جديدة |

### setArc(double value) {#setArc-double-}
```
public void setArc(double value)
```


زاوية القوس الكلية، تُقاس بالراديان. القيمة الافتراضية هي PI

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | قيمة جديدة |

### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


يضبط ما إذا كان هذا الشكل يمكنه إلقاء الظل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean | قيمة جديدة |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean | قيمة جديدة |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


ارتفاع الـ torus المستطيل. القيمة الافتراضية هي 20

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | قيمة جديدة |

### setInnerRadius(double value) {#setInnerRadius-double-}
```
public void setInnerRadius(double value)
```


نصف القطر الداخلي للطارة المستطيلة القيمة الافتراضية هي 17

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double | قيمة جديدة |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


يضبط الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | قيمة جديدة |

### setOuterRadius(double value) {#setOuterRadius-double-}
```
public void setOuterRadius(double value)
```


نصف القطر الخارجي للطارة المستطيلة القيمة الافتراضية هي 20

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

### setRadialSegments(int value) {#setRadialSegments-int-}
```
public void setRadialSegments(int value)
```


الأقسام الشعاعية، القيمة الافتراضية هي 10

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int | قيمة جديدة |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


يضبط ما إذا كان هذا الشكل يمكنه استقبال الظل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean | قيمة جديدة |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


حوّل هذا البدائي إلى [Mesh](../../com.aspose.threed/mesh)

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

