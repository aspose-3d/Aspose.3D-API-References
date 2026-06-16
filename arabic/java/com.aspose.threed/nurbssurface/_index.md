---
title: "NurbsSurface"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "هو سطح يُمثَّل بـ NURBS (Non-uniform rational basis spline)  A  يُعرَّف بواسطة اثنين من  و ."
type: docs
weight: 114
url: /ar/java/com.aspose.threed/nurbssurface/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class NurbsSurface extends Geometry implements IMeshConvertible
```

[NurbsSurface](../../com.aspose.threed/nurbssurface) is a surface represented by [NURBS(Non-uniform rational basis spline)][NURBS_Non-uniform rational basis spline], A [NurbsSurface](../../com.aspose.threed/nurbssurface) is defined by two [NurbsDirection](../../com.aspose.threed/nurbsdirection)[getU](../../com.aspose.threed/nurbssurface\#getU) and [getV](../../com.aspose.threed/nurbssurface\#getV). The w component in control point is used as control point's weight whatever the direction's type is a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) or [CurveDimension.THREE\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#THREE-DIMENSIONAL)


[NURBS_Non-uniform rational basis spline]: https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [NurbsSurface()](#NurbsSurface--) | يُهيئ نسخة جديدة من الفئة [NurbsSurface](../../com.aspose.threed/nurbssurface). |
| [NurbsSurface(String name)](#NurbsSurface-java.lang.String-) | يُهيئ نسخة جديدة من الفئة [NurbsSurface](../../com.aspose.threed/nurbssurface). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | يحصل على جميع المشكّلات بأنواع المشكّلات المحددة |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | يضيف عنصر رأس موجود إلى الشكل الهندسي الحالي |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | ينشئ عنصر رأس بالنوع المحدد ويضيفه إلى الشكل الهندسي. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | ينشئ عنصر رأس بالنوع المحدد ويضيفه إلى الشكل الهندسي. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | ينشئ [VertexElementUV](../../com.aspose.threed/vertexelementuv) بنوع تخطيط النسيج المحدد. |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | ينشئ [VertexElementUV](../../com.aspose.threed/vertexelementuv) بنوع تخطيط النسيج المحدد. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getBoundingBox()](#getBoundingBox--) | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| [getCastShadows()](#getCastShadows--) | يحصل على ما إذا كان هذا الشكل يمكنه إلقاء الظل |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | يحصل على جميع نقاط التحكم |
| [getDeformers()](#getDeformers--) | يحصل على جميع المشوهات المرتبطة بهذا الشكل. |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | يحصل على عنصر رأس بالنوع المحدد |
| [getEntityRendererKey()](#getEntityRendererKey--) | يحصل على المفتاح الخاص بعارض الكيان المسجل في العارض. |
| [getExcluded()](#getExcluded--) | يحصل على ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [getName()](#getName--) | يحصل على الاسم. |
| [getParentNode()](#getParentNode--) | يحصل على أول عقدة أب، إذا تم تعيين أول عقدة أب، سيُفصل هذا الكيان عن عقد الأب الأخرى. |
| [getParentNodes()](#getParentNodes--) | يحصل على جميع عقد الأب، يمكن إرفاق كيان بعدة عقد أب لتكرار الهندسة. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getReceiveShadows()](#getReceiveShadows--) | يحصل على ما إذا كان هذا الشكل يمكنه استقبال الظل. |
| [getScene()](#getScene--) | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [getU()](#getU--) | يحصل على اتجاه U لسطح NURBS |
| [getV()](#getV--) | يحصل على اتجاه V لسطح NURBS |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | يحصل على مثيل [VertexElementUV](../../com.aspose.threed/vertexelementuv) بنوع تخطيط النسيج المحدد |
| [getVertexElements()](#getVertexElements--) | يحصل على جميع عناصر الرؤوس |
| [getVisible()](#getVisible--) | يحصل على ما إذا كان الشكل مرئيًا |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | يضبط ما إذا كان هذا الشكل يمكنه إلقاء الظل |
| [setExcluded(boolean value)](#setExcluded-boolean-) | يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | يضبط أول عقدة أب، إذا تم ضبط أول عقدة أب، سيُفصل هذا الكيان عن عقد الأب الأخرى. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | يضبط ما إذا كان هذا الشكل يمكنه استقبال الظل. |
| [setVisible(boolean value)](#setVisible-boolean-) | يضبط ما إذا كان الشكل مرئيًا |
| [toMesh()](#toMesh--) | تحويل سطح NURBS إلى الشبكة |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsSurface() {#NurbsSurface--}
```
public NurbsSurface()
```


يُهيئ نسخة جديدة من الفئة [NurbsSurface](../../com.aspose.threed/nurbssurface).

### NurbsSurface(String name) {#NurbsSurface-java.lang.String-}
```
public NurbsSurface(String name)
```


يُهيئ نسخة جديدة من الفئة [NurbsSurface](../../com.aspose.threed/nurbssurface).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم. |

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


يحصل على جميع المشكّلات بأنواع المشكّلات المحددة

**Returns:**
java.util.Collection<T> - مجموعة Deformer
### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


يضيف عنصر رأس موجود إلى الشكل الهندسي الحالي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | عنصر الرأس لإضافته |

### createElement(VertexElementType type) {#createElement-com.aspose.threed.VertexElementType-}
```
public VertexElement createElement(VertexElementType type)
```


ينشئ عنصر رأس بالنوع المحدد ويضيفه إلى الشكل الهندسي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | نوع عنصر الرأس |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode) {#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElement createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)
```


ينشئ عنصر رأس بالنوع المحدد ويضيفه إلى الشكل الهندسي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | نوع عنصر الرأس |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | نمط التخطيط الافتراضي |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | نمط الإشارة الافتراضي |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElementUV(TextureMapping uvMapping) {#createElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping)
```


ينشئ [VertexElementUV](../../com.aspose.threed/vertexelementuv) بنوع تخطيط النسيج المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | نوع تخطيط القوام لإنشائه |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode) {#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)
```


ينشئ [VertexElementUV](../../com.aspose.threed/vertexelementuv) بنوع تخطيط النسيج المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | نوع تخطيط القوام لإنشائه |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | نمط التخطيط الافتراضي |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | نمط الإشارة الافتراضي |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
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
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


يحصل على جميع نقاط التحكم

**Returns:**
java.util.List<com.aspose.threed.Vector4> - جميع نقاط التحكم
### getDeformers() {#getDeformers--}
```
public List<Deformer> getDeformers()
```


يحصل على جميع المشوهات المرتبطة بهذا الشكل.

**Returns:**
java.util.List<com.aspose.threed.Deformer> - جميع المشوهات المرتبطة بهذا الشكل الهندسي.
### getElement(VertexElementType type) {#getElement-com.aspose.threed.VertexElementType-}
```
public VertexElement getElement(VertexElementType type)
```


يحصل على عنصر رأس بالنوع المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | ما هو نوع عنصر الرأس للعثور عليه |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - [VertexElement](../../com.aspose.threed/vertexelement) instance if found, otherwise null will be returned.
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
### getU() {#getU--}
```
public NurbsDirection getU()
```


يحصل على اتجاه U لسطح NURBS

**Returns:**
[NurbsDirection](../../com.aspose.threed/nurbsdirection) - the NURBS surface's U direction
### getV() {#getV--}
```
public NurbsDirection getV()
```


يحصل على اتجاه V لسطح NURBS

**Returns:**
[NurbsDirection](../../com.aspose.threed/nurbsdirection) - the NURBS surface's V direction
### getVertexElementOfUV(TextureMapping textureMapping) {#getVertexElementOfUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV getVertexElementOfUV(TextureMapping textureMapping)
```


يحصل على مثيل [VertexElementUV](../../com.aspose.threed/vertexelementuv) بنوع تخطيط النسيج المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) |  |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - VertexElementUV with the texture mapping type
### getVertexElements() {#getVertexElements--}
```
public List<VertexElement> getVertexElements()
```


يحصل على جميع عناصر الرؤوس

**Returns:**
java.util.List<com.aspose.threed.VertexElement> - جميع عناصر الرأس
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


يحصل على ما إذا كان الشكل مرئيًا

**Returns:**
boolean - إذا كان الشكل الهندسي مرئياً
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

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


يضبط ما إذا كان هذا الشكل يمكنه استقبال الظل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


يضبط ما إذا كان الشكل مرئيًا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


تحويل سطح NURBS إلى الشبكة

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

