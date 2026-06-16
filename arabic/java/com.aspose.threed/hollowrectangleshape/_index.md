---
title: "HollowRectangleShape"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "شكل مستطيل مجوف متوافق مع IFC مع زوايا داخلية/خارجية مستديرة."
type: docs
weight: 79
url: /ar/java/com.aspose.threed/hollowrectangleshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Profile](../../com.aspose.threed/profile), [com.aspose.threed.ParameterizedProfile](../../com.aspose.threed/parameterizedprofile), [com.aspose.threed.RectangleShape](../../com.aspose.threed/rectangleshape)
```
public class HollowRectangleShape extends RectangleShape
```

شكل مستطيل مجوف متوافق مع IFC مع زوايا داخلية/خارجية مستديرة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [HollowRectangleShape()](#HollowRectangleShape--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getBoundingBox()](#getBoundingBox--) | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | يحصل على المفتاح الخاص بعارض الكيان المسجل في العارض. |
| [getExcluded()](#getExcluded--) | يحصل على ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [getExtent()](#getExtent--) | يحصل على الامتداد في بعدي x و y. |
| [getInnerFilletRadius()](#getInnerFilletRadius--) | نصف القطر الداخلي للزاوية المدورة للمستطيل الداخلي. |
| [getName()](#getName--) | يحصل على الاسم. |
| [getParentNode()](#getParentNode--) | يحصل على أول عقدة أب، إذا تم تعيين أول عقدة أب، سيُفصل هذا الكيان عن عقد الأب الأخرى. |
| [getParentNodes()](#getParentNodes--) | يحصل على جميع عقد الأب، يمكن إرفاق كيان بعدة عقد أب لتكرار الهندسة. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getRoundingRadius()](#getRoundingRadius--) | يحصل على نصف القطر للأقواس الدائرية لجميع الزوايا الأربعة، مقاسًا بالدرجات. |
| [getScene()](#getScene--) | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [getWallThickness()](#getWallThickness--) | السُمك بين حد المستطيل والفتحة الداخلية |
| [getXDim()](#getXDim--) | يحصل على امتداد المستطيل في اتجاه محور x. القيمة الافتراضية هي 2.0 |
| [getYDim()](#getYDim--) | يحصل على امتداد المستطيل في اتجاه محور y. القيمة الافتراضية هي 2.0 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [setInnerFilletRadius(double value)](#setInnerFilletRadius-double-) | نصف القطر الداخلي للزاوية المدورة للمستطيل الداخلي. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | يضبط أول عقدة أب، إذا تم ضبط أول عقدة أب، سيُفصل هذا الكيان عن عقد الأب الأخرى. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setRoundingRadius(double value)](#setRoundingRadius-double-) | يضبط نصف القطر للأقواس الدائرية لجميع الزوايا الأربعة، مقاسًا بالدرجات. |
| [setWallThickness(double value)](#setWallThickness-double-) | السُمك بين حد المستطيل والفتحة الداخلية |
| [setXDim(double value)](#setXDim-double-) | يضبط امتداد المستطيل في اتجاه محور x. القيمة الافتراضية هي 2.0 |
| [setYDim(double value)](#setYDim-double-) | يضبط امتداد المستطيل في اتجاه محور y. القيمة الافتراضية هي 2.0 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HollowRectangleShape() {#HollowRectangleShape--}
```
public HollowRectangleShape()
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
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


يحصل على ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير.

**Returns:**
منطقي - ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير.
### getExtent() {#getExtent--}
```
public Vector2 getExtent()
```


يحصل على الامتداد في بعدي x و y.

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### getInnerFilletRadius() {#getInnerFilletRadius--}
```
public double getInnerFilletRadius()
```


نصف القطر الداخلي للزاوية المدورة للمستطيل الداخلي.

**Returns:**
double - نصف القطر الداخلي للزاوية المدورة للمستطيل الداخلي.
### getName() {#getName--}
```
public String getName()
```


يحصل على الاسم.

**Returns:**
java.lang.String - الاسم.
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
### getRoundingRadius() {#getRoundingRadius--}
```
public double getRoundingRadius()
```


يحصل على نصف القطر للأقواس الدائرية لجميع الزوايا الأربعة، مقاسًا بالدرجات. القيمة الافتراضية هي 0.0

**Returns:**
double - نصف القطر للأقواس الدائرية لجميع الزوايا الأربعة، مقاسًا بالدرجات. القيمة الافتراضية هي 0.0
### getScene() {#getScene--}
```
public Scene getScene()
```


يحصل على المشهد الذي ينتمي إليه هذا الكائن

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getWallThickness() {#getWallThickness--}
```
public double getWallThickness()
```


السُمك بين حد المستطيل والفتحة الداخلية

**Returns:**
double - السُمك بين حد المستطيل والفتحة الداخلية
### getXDim() {#getXDim--}
```
public double getXDim()
```


يحصل على امتداد المستطيل في اتجاه محور x. القيمة الافتراضية هي 2.0

**Returns:**
double - امتداد المستطيل في اتجاه محور x. القيمة الافتراضية هي 2.0
### getYDim() {#getYDim--}
```
public double getYDim()
```


يحصل على امتداد المستطيل في اتجاه محور y. القيمة الافتراضية هي 2.0

**Returns:**
double - امتداد المستطيل في اتجاه محور y. القيمة الافتراضية هي 2.0
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

### setInnerFilletRadius(double value) {#setInnerFilletRadius-double-}
```
public void setInnerFilletRadius(double value)
```


نصف القطر الداخلي للزاوية المدورة للمستطيل الداخلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


يضبط الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

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

### setRoundingRadius(double value) {#setRoundingRadius-double-}
```
public void setRoundingRadius(double value)
```


يضبط نصف القطر للأقواس الدائرية لجميع الزوايا الأربعة، مقاسًا بالدرجات. القيمة الافتراضية هي 0.0

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setWallThickness(double value) {#setWallThickness-double-}
```
public void setWallThickness(double value)
```


السُمك بين حد المستطيل والفتحة الداخلية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setXDim(double value) {#setXDim-double-}
```
public void setXDim(double value)
```


يضبط امتداد المستطيل في اتجاه محور x. القيمة الافتراضية هي 2.0

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setYDim(double value) {#setYDim-double-}
```
public void setYDim(double value)
```


يضبط امتداد المستطيل في اتجاه محور y. القيمة الافتراضية هي 2.0

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

