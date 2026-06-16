---
title: "NurbsCurve"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "منحنى NURBS هو منحنى يُمثَّل بـ NURBS Non-uniform rational basis spline. يتم تعريف منحنى NURBS بواسطة مجموعة من النقاط المرجحة ومكوّن آخر. يُستخدم المكوّن w في نقطة التحكم كوزن لنقطة التحكم بغض النظر عما إذا كان ..."
type: docs
weight: 112
url: /ar/java/com.aspose.threed/nurbscurve/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Curve](../../com.aspose.threed/curve)
```
public class NurbsCurve extends Curve
```

[NURBS curve][] is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [getOrder](../../com.aspose.threed/nurbscurve\#getOrder), a set of weighted [Geometry.getControlPoints](../../com.aspose.threed/geometry\#getControlPoints) and a [getKnotVectors](../../com.aspose.threed/nurbscurve\#getKnotVectors) The w component in control point is used as control point's weight, whatever it is a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) or [CurveDimension.THREE\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#THREE-DIMENSIONAL)


[NURBS curve]: https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [NurbsCurve()](#NurbsCurve--) | يُنشئ مثلاً جديدًا من الفئة [NurbsCurve](../../com.aspose.threed/nurbscurve) class. |
| [NurbsCurve(String name)](#NurbsCurve-java.lang.String-) | يُنشئ مثلاً جديدًا من الفئة [NurbsCurve](../../com.aspose.threed/nurbscurve) class. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [evaluate()](#evaluate--) | تقييم منحنى NURBS |
| [evaluate(int steps)](#evaluate-int-) | تقييم منحنى NURBS |
| [evaluateAt(double u)](#evaluateAt-double-) | تقييم نقطة المنحنى في الموضع المحدد |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getBoundingBox()](#getBoundingBox--) | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | يحصل على لون الخط، القيمة الافتراضية هي الأبيض(1, 1, 1) |
| [getControlPoints()](#getControlPoints--) | يحصل على جميع نقاط التحكم |
| [getCurveType()](#getCurveType--) | يحصل على نوع المنحنى. |
| [getDegree()](#getDegree--) | يحصل على درجة منحنى NURBS، حيث تُعرّف الدرجة بأنها الترتيب - 1 |
| [getDimension()](#getDimension--) | يحصل على أبعاد المنحنى. |
| [getEntityRendererKey()](#getEntityRendererKey--) | يحصل على المفتاح الخاص بعارض الكيان المسجل في العارض. |
| [getExcluded()](#getExcluded--) | يحصل على ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [getKnotVectors()](#getKnotVectors--) | يحصل على متجه العقد، وهو تسلسل من قيم المعامل التي تحدد أين وكيف تؤثر نقاط التحكم على منحنى NURBS. |
| [getMultiplicity()](#getMultiplicity--) | يحصل على التعددية. |
| [getName()](#getName--) | يحصل على الاسم. |
| [getOrder()](#getOrder--) | يحصل على ترتيب منحنى NURBS، وهو يحدد عدد نقاط التحكم القريبة التي تؤثر على أي نقطة معينة في المنحنى. |
| [getParentNode()](#getParentNode--) | يحصل على أول عقدة أب، إذا تم تعيين أول عقدة أب، سيُفصل هذا الكيان عن عقد الأب الأخرى. |
| [getParentNodes()](#getParentNodes--) | يحصل على جميع عقد الأب، يمكن إرفاق كيان بعدة عقد أب لتكرار الهندسة. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getRational()](#getRational--) | يحصل على ما إذا كان ذلك عقلانيًا، هذه القيمة تشير إلى ما إذا كان [NurbsCurve](../../com.aspose.threed/nurbscurve) منحنىًا عقلانيًا أم غير عقلاني. |
| [getScene()](#getScene--) | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | يضبط لون الخط، القيمة الافتراضية هي الأبيض(1, 1, 1) |
| [setCurveType(NurbsType value)](#setCurveType-com.aspose.threed.NurbsType-) | يضبط نوع المنحنى. |
| [setDegree(int value)](#setDegree-int-) | يضبط درجة منحنى NURBS، حيث تُعرّف الدرجة بأنها الترتيب - 1 |
| [setDimension(CurveDimension value)](#setDimension-com.aspose.threed.CurveDimension-) | يضبط أبعاد المنحنى. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setOrder(int value)](#setOrder-int-) | يضبط ترتيب منحنى NURBS، وهو يحدد عدد نقاط التحكم القريبة التي تؤثر على أي نقطة معينة في المنحنى. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | يضبط أول عقدة أب، إذا تم ضبط أول عقدة أب، سيُفصل هذا الكيان عن عقد الأب الأخرى. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setRational(boolean value)](#setRational-boolean-) | يضبط ما إذا كان ذلك عقلانيًا، هذه القيمة تشير إلى ما إذا كان [NurbsCurve](../../com.aspose.threed/nurbscurve) منحنىًا عقلانيًا أم غير عقلاني. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsCurve() {#NurbsCurve--}
```
public NurbsCurve()
```


يُنشئ مثلاً جديدًا من الفئة [NurbsCurve](../../com.aspose.threed/nurbscurve) class.

### NurbsCurve(String name) {#NurbsCurve-java.lang.String-}
```
public NurbsCurve(String name)
```


يُنشئ مثلاً جديدًا من الفئة [NurbsCurve](../../com.aspose.threed/nurbscurve) class.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم |

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
### evaluate() {#evaluate--}
```
public Vector4[] evaluate()
```


تقييم منحنى NURBS

**Returns:**
com.aspose.threed.Vector4[] - نقاط في المنحنى
### evaluate(int steps) {#evaluate-int-}
```
public Vector4[] evaluate(int steps)
```


تقييم منحنى NURBS

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| خطوات | int | تردد التقييم بين عقدتين متجاورتين، القيمة الافتراضية هي 20 |

**Returns:**
com.aspose.threed.Vector4[] - نقاط في المنحنى
### evaluateAt(double u) {#evaluateAt-double-}
```
public Vector4 evaluateAt(double u)
```


تقييم نقطة المنحنى في الموضع المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| u | double | الموضع في المنحنى، بين 0 و 1 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
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
### getColor() {#getColor--}
```
public Vector3 getColor()
```


يحصل على لون الخط، القيمة الافتراضية هي الأبيض(1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the color of the line, default value is white(1, 1, 1)
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


يحصل على جميع نقاط التحكم

**Returns:**
java.util.List<com.aspose.threed.Vector4> - جميع نقاط التحكم
### getCurveType() {#getCurveType--}
```
public NurbsType getCurveType()
```


يحصل على نوع المنحنى.

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the curve.
### getDegree() {#getDegree--}
```
public int getDegree()
```


يحصل على درجة منحنى NURBS، حيث تُعرّف الدرجة بأنها الترتيب - 1

**Returns:**
int - درجة منحنى NURBS، حيث تُعرّف الدرجة بأنها الترتيب - 1
### getDimension() {#getDimension--}
```
public CurveDimension getDimension()
```


يحصل على أبعاد المنحنى.

**Returns:**
[CurveDimension](../../com.aspose.threed/curvedimension) - the curve's dimension. **Remarks:** For a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) curve, the z component in control point is unused.
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
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


يحصل على متجه العقد، وهو تسلسل من قيم المعامل التي تحدد أين وكيف تؤثر نقاط التحكم على منحنى NURBS.

**Returns:**
java.util.List<java.lang.Double> - متجه العقد، وهو تسلسل من قيم المعامل التي تحدد أين وكيف تؤثر نقاط التحكم على منحنى NURBS.
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


يحصل على التعددية.

**Returns:**
java.util.List<java.lang.Integer> - التعددية.
### getName() {#getName--}
```
public String getName()
```


يحصل على الاسم.

**Returns:**
java.lang.String - الاسم.
### getOrder() {#getOrder--}
```
public int getOrder()
```


يحصل على ترتيب منحنى NURBS، وهو يحدد عدد نقاط التحكم القريبة التي تؤثر على أي نقطة معينة في المنحنى.

**Returns:**
int - رتبة منحنى NURBS، تُحدد عدد نقاط التحكم القريبة التي تؤثر على أي نقطة معينة على المنحنى.
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
### getRational() {#getRational--}
```
public boolean getRational()
```


يحصل على ما إذا كان منطقيًا، هذه القيمة تشير إلى ما إذا كان هذا [NurbsCurve](../../com.aspose.threed/nurbscurve) منحنىًا منطقيًا أم غير منطقي. الـ B-spline غير المنطقي هو حالة خاصة من الـ B-splines المنطقية.

**Returns:**
boolean - ما إذا كان منطقيًا، هذه القيمة تشير إلى ما إذا كان هذا [NurbsCurve](../../com.aspose.threed/nurbscurve) منحنىًا منطقيًا أم غير منطقي. الـ B-spline غير المنطقي هو حالة خاصة من الـ B-splines المنطقية.
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
### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


يضبط لون الخط، القيمة الافتراضية هي الأبيض(1, 1, 1)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setCurveType(NurbsType value) {#setCurveType-com.aspose.threed.NurbsType-}
```
public void setCurveType(NurbsType value)
```


يضبط نوع المنحنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | القيمة الجديدة |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


يضبط درجة منحنى NURBS، حيث تُعرّف الدرجة بأنها الترتيب - 1

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setDimension(CurveDimension value) {#setDimension-com.aspose.threed.CurveDimension-}
```
public void setDimension(CurveDimension value)
```


يضبط أبعاد المنحنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [CurveDimension](../../com.aspose.threed/curvedimension) | قيمة جديدة **ملاحظات:** بالنسبة لمنحنى [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL)، مكوّن z في نقطة التحكم غير مستخدم. |

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

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


يضبط ترتيب منحنى NURBS، وهو يحدد عدد نقاط التحكم القريبة التي تؤثر على أي نقطة معينة في المنحنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

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

### setRational(boolean value) {#setRational-boolean-}
```
public void setRational(boolean value)
```


يضبط ما إذا كان منطقيًا، هذه القيمة تشير إلى ما إذا كان هذا [NurbsCurve](../../com.aspose.threed/nurbscurve) منحنىًا منطقيًا أم غير منطقي. الـ B-spline غير المنطقي هو حالة خاصة من الـ B-splines المنطقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

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

