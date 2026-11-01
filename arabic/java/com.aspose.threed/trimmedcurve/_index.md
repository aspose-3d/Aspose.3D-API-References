---
title: "TrimmedCurve"
second_title: "مرجع Aspose.3D لـ Java API"
description: "منحنى محدود يقتطع المنحنى الأساسي عند الطرفين."
type: docs
weight: 196
url: /ar/java/com.aspose.threed/trimmedcurve/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Curve](../../com.aspose.threed/curve)
```
public class TrimmedCurve extends Curve
```

منحنى محدود يقتطع المنحنى الأساسي عند الطرفين.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TrimmedCurve()](#TrimmedCurve--) | منشئ [TrimmedCurve](../../com.aspose.threed/trimmedcurve) |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getBasisCurve()](#getBasisCurve--) | منحنى الأساس الذي سيتم تقصيره. |
| [getBoundingBox()](#getBoundingBox--) | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | يسترجع لون الخط، القيمة الافتراضية هي الأبيض (1, 1, 1) |
| [getEntityRendererKey()](#getEntityRendererKey--) | يحصل على المفتاح الخاص بعارض الكيان المسجل في العارض |
| [getExcluded()](#getExcluded--) | يحصل على ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [getFirst()](#getFirst--) | نقطة النهاية الأولى للقص، يمكن أن تكون نقطة ديكارتية أو معلمة حقيقية. |
| [getName()](#getName--) | يحصل على الاسم. |
| [getParentNode()](#getParentNode--) | يحصل على أول عقدة أصل، إذا تم تعيين أول عقدة أصل، سيتم فصل هذا الكيان عن عقد الأصل الأخرى. |
| [getParentNodes()](#getParentNodes--) | يحصل على جميع عقد الأصل، يمكن إرفاق كيان بعدة عقد أصل لتكرار الهندسة |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getSameDirection()](#getSameDirection--) | يحصل على ما إذا كانت النتيجة المقصوصة تستخدم نفس اتجاه المنحنى الأساسي. |
| [getScene()](#getScene--) | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [getSecond()](#getSecond--) | نقطة النهاية الثانية للقص، يمكن أن تكون نقطة ديكارتية أو معلمة حقيقية. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | أزل الخاصية المحددة بالاسم |
| [setBasisCurve(Curve value)](#setBasisCurve-com.aspose.threed.Curve-) | منحنى الأساس الذي سيتم تقصيره. |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | يضبط لون الخط، القيمة الافتراضية هي الأبيض (1, 1, 1) |
| [setExcluded(boolean value)](#setExcluded-boolean-) | يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [setFirst(EndPoint value)](#setFirst-com.aspose.threed.EndPoint-) | نقطة النهاية الأولى للقص، يمكن أن تكون نقطة ديكارتية أو معلمة حقيقية. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | يضبط أول عقدة أصل، إذا تم تعيين أول عقدة أصل، سيتم فصل هذا الكيان عن عقد الأصل الأخرى. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setSameDirection(boolean value)](#setSameDirection-boolean-) | يضبط ما إذا كانت النتيجة المقصوصة تستخدم نفس اتجاه المنحنى الأساسي. |
| [setSecond(EndPoint value)](#setSecond-com.aspose.threed.EndPoint-) | نقطة النهاية الثانية للقص، يمكن أن تكون نقطة ديكارتية أو معلمة حقيقية. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TrimmedCurve() {#TrimmedCurve--}
```
public TrimmedCurve()
```


منشئ [TrimmedCurve](../../com.aspose.threed/trimmedcurve)

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
### getBasisCurve() {#getBasisCurve--}
```
public Curve getBasisCurve()
```


منحنى الأساس الذي سيتم تقصيره.

**Returns:**
[Curve](../../com.aspose.threed/curve) - The basis curve to be trimmed.
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


يسترجع لون الخط، القيمة الافتراضية هي الأبيض (1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the color of the line, default value is white(1, 1, 1)
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


يحصل على المفتاح الخاص بعارض الكيان المسجل في العارض

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


يحصل على ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير.

**Returns:**
منطقي - ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير.
### getFirst() {#getFirst--}
```
public EndPoint getFirst()
```


نقطة النهاية الأولى للقص، يمكن أن تكون نقطة ديكارتية أو معلمة حقيقية.

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - The first end point to trim, can be a Cartesian point or a real parameter.
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
### getSameDirection() {#getSameDirection--}
```
public boolean getSameDirection()
```


يحصل على ما إذا كانت النتيجة المقصوصة تستخدم نفس اتجاه المنحنى الأساسي.

**Returns:**
منطقي - ما إذا كانت النتيجة المقصوصة تستخدم نفس اتجاه المنحنى الأساسي.
### getScene() {#getScene--}
```
public Scene getScene()
```


يحصل على المشهد الذي ينتمي إليه هذا الكائن

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getSecond() {#getSecond--}
```
public EndPoint getSecond()
```


نقطة النهاية الثانية للقص، يمكن أن تكون نقطة ديكارتية أو معلمة حقيقية.

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - The second end point to trim, can be a Cartesian point or a real parameter.
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
### setBasisCurve(Curve value) {#setBasisCurve-com.aspose.threed.Curve-}
```
public void setBasisCurve(Curve value)
```


منحنى الأساس الذي سيتم تقصيره.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Curve](../../com.aspose.threed/curve) | قيمة جديدة |

### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


يضبط لون الخط، القيمة الافتراضية هي الأبيض (1, 1, 1)

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

### setFirst(EndPoint value) {#setFirst-com.aspose.threed.EndPoint-}
```
public void setFirst(EndPoint value)
```


نقطة النهاية الأولى للقص، يمكن أن تكون نقطة ديكارتية أو معلمة حقيقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EndPoint](../../com.aspose.threed/endpoint) | قيمة جديدة |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


يضبط الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String | قيمة جديدة |

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

### setSameDirection(boolean value) {#setSameDirection-boolean-}
```
public void setSameDirection(boolean value)
```


يضبط ما إذا كانت النتيجة المقصوصة تستخدم نفس اتجاه المنحنى الأساسي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean | قيمة جديدة |

### setSecond(EndPoint value) {#setSecond-com.aspose.threed.EndPoint-}
```
public void setSecond(EndPoint value)
```


نقطة النهاية الثانية للقص، يمكن أن تكون نقطة ديكارتية أو معلمة حقيقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EndPoint](../../com.aspose.threed/endpoint) | قيمة جديدة |

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

