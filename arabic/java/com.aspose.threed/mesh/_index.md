---
title: "شبكة"
second_title: "مرجع Aspose.3D لـ Java API"
description: "الشبكة تتكوّن من العديد من المضلعات ذات n أضلاع."
type: docs
weight: 102
url: /ar/java/com.aspose.threed/mesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)

**All Implemented Interfaces:**
java.lang.Iterable, [com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class Mesh extends Geometry implements Iterable<int[]>, IMeshConvertible
```

شبكة مكوّنة من العديد من المضلعات ذات n أضلاع. **Example:** لإضافة مضلع في الشبكة:

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

التنقل عبر جميع المضلعات في الشبكة:

```
Mesh mesh = new Mesh();
  for(int[] polygon : mesh)
  {
      //deal with polygon
  }
```
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Mesh()](#Mesh--) | ينشئ نسخة جديدة من الفئة [Mesh](../../com.aspose.threed/mesh). |
| [Mesh(String name)](#Mesh-java.lang.String-) | ينشئ نسخة جديدة من الفئة [Mesh](../../com.aspose.threed/mesh). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | يحصل على جميع المشوهات بأنواع المشوه المحددة |
| [addControlPoint(double x, double y, double z)](#addControlPoint-double-double-double-) | أضف نقطة تحكم جديدة إلى الشبكة، هذا أكثر كفاءة. |
| [addControlPoint(double x, double y, double z, double w)](#addControlPoint-double-double-double-double-) | أضف نقطة تحكم جديدة إلى الشبكة، هذا أكثر كفاءة. |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | يضيف عنصر رأس موجود إلى الهندسة الحالية |
| [clone()](#clone--) |  |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | ينشئ عنصر رأس بالنوع المحدد ويضيفه إلى الهندسة. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | ينشئ عنصر رأس بالنوع المحدد ويضيفه إلى الهندسة. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | ينشئ [VertexElementUV](../../com.aspose.threed/vertexelementuv) بنوع تخطيط النسيج المحدد. |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | ينشئ [VertexElementUV](../../com.aspose.threed/vertexelementuv) بنوع تخطيط النسيج المحدد. |
| [createPolygon(int v1, int v2, int v3)](#createPolygon-int-int-int-) | إنشاء مضلع بـ 3 رؤوس(مثلث) |
| [createPolygon(int v1, int v2, int v3, int v4)](#createPolygon-int-int-int-int-) | إنشاء مضلع بـ 4 رؤوس(رباعي) |
| [createPolygon(int[] indices)](#createPolygon-int---) | ينشئ مضلعًا جديدًا بجميع الرؤوس المعرفة في `indices`. |
| [createPolygon(int[] indices, int offset, int length)](#createPolygon-int---int-int-) | ينشئ مضلعًا جديدًا بجميع الرؤوس المعرفة في `indices`. |
| [difference(Mesh a, Mesh b)](#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | احسب الفرق بين شبكتين |
| [doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)](#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-) | نفّذ عملية بوليانية على شبكتين |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [getBoundingBox()](#getBoundingBox--) | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| [getCastShadows()](#getCastShadows--) | يحصل على ما إذا كان هذا الشكل يمكنه إلقاء الظل |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | يحصل على جميع نقاط التحكم |
| [getDeformers()](#getDeformers--) | يحصل على جميع المُشوهات المرتبطة بهذا الشكل. |
| [getEdges()](#getEdges--) | يحصل على حواف الشبكة. |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | يحصل على عنصر رأس بالنوع المحدد |
| [getEntityRendererKey()](#getEntityRendererKey--) | يحصل على المفتاح الخاص بعارض الكيان المسجل في العارض |
| [getExcluded()](#getExcluded--) | يحصل على ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [getName()](#getName--) | يحصل على الاسم. |
| [getParentNode()](#getParentNode--) | يحصل على أول عقدة أصل، إذا تم تعيين أول عقدة أصل، سيتم فصل هذا الكيان عن عقد الأصل الأخرى. |
| [getParentNodes()](#getParentNodes--) | يحصل على جميع عقد الأصل، يمكن إرفاق كيان بعدة عقد أصل لتكرار الهندسة |
| [getPolygonCount()](#getPolygonCount--) | يحصل على عدد المضلعات |
| [getPolygonSize(int index)](#getPolygonSize-int-) | يحصل على عدد الرؤوس للمضلع المحدد. |
| [getPolygons()](#getPolygons--) | يحصل على تعريف المضلعات للشبكة |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getReceiveShadows()](#getReceiveShadows--) | يحصل على ما إذا كان هذا الشكل يمكنه استقبال الظل. |
| [getScene()](#getScene--) | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | يحصل على نسخة من [VertexElementUV](../../com.aspose.threed/vertexelementuv) بنوع تخطيط النسيج المحدد |
| [getVertexElements()](#getVertexElements--) | يحصل على جميع عناصر الرؤوس |
| [getVisible()](#getVisible--) | يحصل على ما إذا كان الشكل مرئيًا |
| [hashCode()](#hashCode--) |  |
| [intersect(Mesh a, Mesh b)](#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | احسب تقاطع شبكتين |
| [isManifold()](#isManifold--) | تحقق مما إذا كانت الشبكة الحالية شبكة متعددة الأوجه. |
| [iterator()](#iterator--) | يحصل على المكرّر لكل مضلع داخلي. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [optimize(boolean vertexElements)](#optimize-boolean-) | حسّن استخدام الذاكرة للشبكة عن طريق إزالة نقاط التحكم المكررة |
| [optimize(boolean vertexElements, float toleranceControlPoint)](#optimize-boolean-float-) | حسّن استخدام الذاكرة للشبكة عن طريق إزالة نقاط التحكم المكررة |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)](#optimize-boolean-float-float-) | حسّن استخدام الذاكرة للشبكة عن طريق إزالة نقاط التحكم المكررة |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)](#optimize-boolean-float-float-float-) | حسّن استخدام الذاكرة للشبكة عن طريق إزالة نقاط التحكم المكررة |
| [optimize2(boolean vertexElements)](#optimize2-boolean-) | حسّن استخدام الذاكرة للشبكة عن طريق إزالة نقاط التحكم المكررة |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | أزل الخاصية المحددة بالاسم |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | يضبط ما إذا كان هذا الشكل يمكنه إلقاء الظل |
| [setExcluded(boolean value)](#setExcluded-boolean-) | يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | يضبط أول عقدة أصل، إذا تم تعيين أول عقدة أصل، سيتم فصل هذا الكيان عن عقد الأصل الأخرى. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | يضبط ما إذا كان هذا الشكل يمكنه استقبال الظل. |
| [setVisible(boolean value)](#setVisible-boolean-) | يضبط ما إذا كان الشكل مرئيًا |
| [toMesh()](#toMesh--) | يحصل على نسخة Mesh من الكيان الحالي. |
| [toString()](#toString--) |  |
| [triangulate()](#triangulate--) | إرجاع mesh مثلثي |
| [union(Mesh a, Mesh b)](#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | احسب اتحاد meshes |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mesh() {#Mesh--}
```
public Mesh()
```


ينشئ نسخة جديدة من الفئة [Mesh](../../com.aspose.threed/mesh).

### Mesh(String name) {#Mesh-java.lang.String-}
```
public Mesh(String name)
```


ينشئ نسخة جديدة من الفئة [Mesh](../../com.aspose.threed/mesh).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم. |

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


يحصل على جميع المشوهات بأنواع المشوه المحددة

**Returns:**
java.util.Collection<T> - مجموعة Deformer
### addControlPoint(double x, double y, double z) {#addControlPoint-double-double-double-}
```
public void addControlPoint(double x, double y, double z)
```


أضف نقطة تحكم جديدة إلى الشبكة، هذا أكثر كفاءة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | double | المكوّن x لنقطة التحكم |
| y | double | المكوّن y لنقطة التحكم |
| z | double | المكوّن z لنقطة التحكم |

### addControlPoint(double x, double y, double z, double w) {#addControlPoint-double-double-double-double-}
```
public void addControlPoint(double x, double y, double z, double w)
```


أضف نقطة تحكم جديدة إلى الشبكة، هذا أكثر كفاءة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | double | المكوّن x لنقطة التحكم |
| y | double | المكوّن y لنقطة التحكم |
| z | double | المكوّن z لنقطة التحكم |
| w | double | المكوّن w لنقطة التحكم |

### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


يضيف عنصر رأس موجود إلى الهندسة الحالية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | عنصر الرأس لإضافته |

### clone() {#clone--}
```
public Mesh clone()
```




**Returns:**
[Mesh](../../com.aspose.threed/mesh)
### createElement(VertexElementType type) {#createElement-com.aspose.threed.VertexElementType-}
```
public VertexElement createElement(VertexElementType type)
```


ينشئ عنصر رأس بالنوع المحدد ويضيفه إلى الهندسة.

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


ينشئ عنصر رأس بالنوع المحدد ويضيفه إلى الهندسة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | نوع عنصر الرأس |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | وضع التخطيط الافتراضي |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | وضع الإشارة الافتراضي |

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
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | نوع تخطيط النسيج الذي سيتم إنشاؤه |

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
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | نوع تخطيط النسيج الذي سيتم إنشاؤه |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | وضع التخطيط الافتراضي |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | وضع الإشارة الافتراضي |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createPolygon(int v1, int v2, int v3) {#createPolygon-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3)
```


إنشاء مضلع بـ 3 رؤوس(مثلث)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| v1 | int | فهرس الرأس الأول |
| v2 | int | فهرس الرأس الثاني |
|  | v3 | int | فهرس الرأس الثالث **مثال:** يوضح الشيفرة التالية كيفية إنشاء مضلع جديد باستخدام فهارس نقاط التحكم. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2);
``` |

### createPolygon(int v1, int v2, int v3, int v4) {#createPolygon-int-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3, int v4)
```


إنشاء مضلع بـ 4 رؤوس(رباعي)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| v1 | int | فهرس الرأس الأول |
| v2 | int | فهرس الرأس الثاني |
| v3 | int | فهرس الرأس الثالث |
|  | v4 | int | فهرس الرأس الرابع **مثال:** يوضح الشيفرة التالية كيفية إنشاء مضلع جديد باستخدام فهارس نقاط التحكم. |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2, 3);
``` |

### createPolygon(int[] indices) {#createPolygon-int---}
```
public void createPolygon(int[] indices)
```


ينشئ مضلعًا جديدًا بجميع الرؤوس المعرفة في `indices`. لإنشاء المضلع رأسًا برأس، يرجى استخدام [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المؤشرات | int[] | مصفوفة مؤشرات المضلع، كل مؤشر يشير إلى نقطة تحكم تُكوّن المضلع. **مثال:** |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### createPolygon(int[] indices, int offset, int length) {#createPolygon-int---int-int-}
```
public void createPolygon(int[] indices, int offset, int length)
```


ينشئ مضلعًا جديدًا بجميع الرؤوس المعرفة في `indices`. لإنشاء المضلع رأسًا برأس، يرجى استخدام [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المؤشرات | int[] | مصفوفة مؤشرات المضلع، كل مؤشر يشير إلى نقطة تحكم تُكوّن المضلع. |
| الإزاحة | int | الإزاحة لمؤشر المضلع الأول |
|  | الطول | int | طول المؤشرات **مثال:** يوضح الشيفرة التالية كيفية إنشاء مضلع جديد باستخدام مؤشرات نقطة التحكم. |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### difference(Mesh a, Mesh b) {#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh difference(Mesh a, Mesh b)
```


احسب الفرق بين شبكتين

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | الشبكة الأولى |
| b | [Mesh](../../com.aspose.threed/mesh) | الشبكة الثانية |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB) {#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-}
```
public static Mesh doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)
```


نفّذ عملية بوليانية على شبكتين

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| op | [BooleanOperation](../../com.aspose.threed/booleanoperation) | نوع العملية البوليانية. |
| a | [Mesh](../../com.aspose.threed/mesh) | الشبكة الأولى للتشغيل. |
| transformA | [Matrix4](../../com.aspose.threed/matrix4) | مصفوفة التحويل للشبكة الأولى |
| b | [Mesh](../../com.aspose.threed/mesh) | الشبكة الثانية للتشغيل |
| transformB | [Matrix4](../../com.aspose.threed/matrix4) | مصفوفة التحويل للشبكة الثانية |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The result mesh **Example:** The following code shows how to calculate the union of two meshes:
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


يحصل على جميع المُشوهات المرتبطة بهذا الشكل.

**Returns:**
java.util.List<com.aspose.threed.Deformer> - جميع المشوهات المرتبطة بهذا الشكل الهندسي.
### getEdges() {#getEdges--}
```
public List<Integer> getEdges()
```


يحصل على حواف الـ Mesh. Edge اختيارية في Mesh، لذا يمكن أن تكون فارغة.

**Returns:**
java.util.List<java.lang.Integer> - حواف الـ Mesh. Edge اختيارية في Mesh، لذا يمكن أن تكون فارغة.
### getElement(VertexElementType type) {#getElement-com.aspose.threed.VertexElementType-}
```
public VertexElement getElement(VertexElementType type)
```


يحصل على عنصر رأس بالنوع المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | نوع عنصر الرأس الذي يجب العثور عليه |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - [VertexElement](../../com.aspose.threed/vertexelement) instance if found, otherwise null will be returned.
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
### getPolygonCount() {#getPolygonCount--}
```
public int getPolygonCount()
```


يحصل على عدد المضلعات

**Returns:**
int - عدد المضلعات **مثال:** يوضح الشيفرة التالية كيفية الحصول على عدد مضلعات mesh.

```
Mesh mesh = (new Sphere()).toMesh();
      System.out.println("Mesh's polygon count = " + mesh.getPolygonCount());
```
### getPolygonSize(int index) {#getPolygonSize-int-}
```
public int getPolygonSize(int index)
```


يحصل على عدد الرؤوس للمضلع المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المؤشر | int | المؤشر. |

**Returns:**
int - حجم المضلع.
### getPolygons() {#getPolygons--}
```
public List<int[]> getPolygons()
```


يحصل على تعريف المضلعات للشبكة

**Returns:**
java.util.List<int[]> - تعريف مضلعات الشبكة
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
boolean - ما إذا كان هذا الشكل الهندسي يمكنه تلقي الظل.
### getScene() {#getScene--}
```
public Scene getScene()
```


يحصل على المشهد الذي ينتمي إليه هذا الكائن

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getVertexElementOfUV(TextureMapping textureMapping) {#getVertexElementOfUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV getVertexElementOfUV(TextureMapping textureMapping)
```


يحصل على نسخة من [VertexElementUV](../../com.aspose.threed/vertexelementuv) بنوع تخطيط النسيج المحدد

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
java.util.List<com.aspose.threed.VertexElement> - جميع عناصر القمم
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
### intersect(Mesh a, Mesh b) {#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh intersect(Mesh a, Mesh b)
```


احسب تقاطع شبكتين

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | الشبكة الأولى |
| b | [Mesh](../../com.aspose.threed/mesh) | الشبكة الثانية |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### isManifold() {#isManifold--}
```
public boolean isManifold()
```


تحقق مما إذا كانت الشبكة الحالية شبكة متعددة الأوجه. هذه الدالة لن تخزن نتيجة حساب التعددية في الذاكرة المؤقتة.

**Returns:**
boolean - true إذا كانت الشبكة شبكة متعددة الأوجه.
### iterator() {#iterator--}
```
public Iterator<int[]> iterator()
```


يحصل على المكرّر لكل مضلع داخلي.

**Returns:**
java.util.Iterator<int[]> - المُعدِّد.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### optimize(boolean vertexElements) {#optimize-boolean-}
```
public Mesh optimize(boolean vertexElements)
```


حسّن استخدام الذاكرة للشبكة عن طريق إزالة نقاط التحكم المكررة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| vertexElements | boolean | تحسين بيانات عناصر الرؤوس المكررة |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage **Example:** The following code shows how to eliminate duplicated control points from an unoptimized mesh:

```
//Sphere.ToMesh generates 117 control points
  Mesh mesh = (new Sphere()).toMesh();
  //After optimized, there're only 86 control points, polygon indices are also remapped.
  Mesh optimized = mesh.optimize(true);
```
### optimize(boolean vertexElements, float toleranceControlPoint) {#optimize-boolean-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint)
```


حسّن استخدام الذاكرة للشبكة عن طريق إزالة نقاط التحكم المكررة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| vertexElements | boolean | تحسين بيانات عناصر الرؤوس المكررة |
| toleranceControlPoint | float | التحمل لنقطة التحكم، القيمة الافتراضية هي 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal) {#optimize-boolean-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)
```


حسّن استخدام الذاكرة للشبكة عن طريق إزالة نقاط التحكم المكررة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| vertexElements | boolean | تحسين بيانات عناصر الرؤوس المكررة |
| toleranceControlPoint | float | التحمل لنقطة التحكم، القيمة الافتراضية هي 1e-9 |
| toleranceNormal | float | التحمل للمتجه العادي/المماس/الثنائي، القيمة الافتراضية هي 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV) {#optimize-boolean-float-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)
```


حسّن استخدام الذاكرة للشبكة عن طريق إزالة نقاط التحكم المكررة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| vertexElements | boolean | تحسين بيانات عناصر الرؤوس المكررة |
| toleranceControlPoint | float | التحمل لنقطة التحكم، القيمة الافتراضية هي 1e-9 |
| toleranceNormal | float | التحمل للمتجه العادي/المماس/الثنائي، القيمة الافتراضية هي 1e-9 |
| toleranceUV | float | التحمل للـ uv، القيمة الافتراضية هي 1e-9 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize2(boolean vertexElements) {#optimize2-boolean-}
```
public Mesh optimize2(boolean vertexElements)
```


حسّن استخدام الذاكرة للشبكة عن طريق إزالة نقاط التحكم المكررة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| vertexElements | boolean | تحسين بيانات عناصر الرؤوس المكررة |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
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

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


يضبط ما إذا كان هذا الشكل يمكنه استقبال الظل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean | قيمة جديدة |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


يضبط ما إذا كان الشكل مرئيًا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean | قيمة جديدة |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


يحصل على نسخة Mesh من الكيان الحالي.

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Returns current instance.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### triangulate() {#triangulate--}
```
public Mesh triangulate()
```


إرجاع mesh مثلثي

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Current mesh if current mesh is already triangulated, otherwise a new triangulated mesh will be calculated and returned **Example:** The following code shows how to triangulate a mesh:

```
//The plane mesh has only one polygon with 4 control points
  var mesh = (new Plane()).ToMesh();
  //After triangulated, the new mesh's rectangle will become 2 triangles.
  var triangulated = mesh.Triangulate();
```
### union(Mesh a, Mesh b) {#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh union(Mesh a, Mesh b)
```


احسب اتحاد meshes

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | الشبكة الأولى |
| b | [Mesh](../../com.aspose.threed/mesh) | الشبكة الثانية |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to union two meshes into one mesh:
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

