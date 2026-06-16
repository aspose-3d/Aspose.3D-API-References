---
title: "TriMesh"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "يحتوي TriMesh على بيانات خام يمكن للمعالج الرسومي (GPU) استخدامها مباشرة."
type: docs
weight: 194
url: /ar/java/com.aspose.threed/trimesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
java.lang.Iterable
```
public class TriMesh extends Entity implements Iterable<Vertex>
```

يحتوي TriMesh على بيانات خام يمكن للـ GPU استخدامها مباشرة. هذه الفئة أداة تساعد في إنشاء شبكة تحتوي فقط على بيانات لكل رأس. **Example:** يوضح الكود التالي كيفية إنشاء TriMesh بتخطيط ذاكرة مخصص، وتصديره إلى ملف.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TriMesh(String name, VertexDeclaration declaration)](#TriMesh-java.lang.String-com.aspose.threed.VertexDeclaration-) | تهيئة نسخة من [TriMesh](../../com.aspose.threed/trimesh) |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addTriangle(int a, int b, int c)](#addTriangle-int-int-int-) | إضافة مثلث جديد |
| [beginVertex()](#beginVertex--) | بدء إضافة رأس |
| [copyFrom(TriMesh input, VertexDeclaration vd)](#copyFrom-com.aspose.threed.TriMesh-com.aspose.threed.VertexDeclaration-) | نسخ الـ [TriMesh](../../com.aspose.threed/trimesh) من الإدخال مع تخطيط رأس جديد |
| [endVertex()](#endVertex--) | إنهاء إضافة رأس |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | يبحث عن الخاصية. |
| [fromMesh(Mesh mesh)](#fromMesh-com.aspose.threed.Mesh-) | إنشاء TriMesh من كائن شبكة مُعطى، حيث يتم بناء تعريف الرؤوس بناءً على بنية الشبكة المدخلة. |
| [fromMesh(Mesh mesh, boolean useFloat)](#fromMesh-com.aspose.threed.Mesh-boolean-) | إنشاء TriMesh من كائن شبكة مُعطى، حيث يتم بناء تعريف الرؤوس بناءً على بنية الشبكة المدخلة. |
| [fromMesh(VertexDeclaration declaration, Mesh mesh)](#fromMesh-com.aspose.threed.VertexDeclaration-com.aspose.threed.Mesh-) | إنشاء TriMesh من كائن شبكة مُعطى مع تخطيط رأس محدد. |
| [fromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, boolean generateVertexMapping)](#fromRawData-com.aspose.threed.VertexDeclaration-byte---int---boolean-) | إنشاء TriMesh من بيانات خام |
| [getBoundingBox()](#getBoundingBox--) | يحصل على صندوق الحدود للكيان الحالي في نظام إحداثيات مساحة الكائن الخاصة به. |
| [getCapacity()](#getCapacity--) | السعة المخصصة مسبقًا للرؤوس. |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | يحصل على المفتاح الخاص بعارض الكيان المسجل في العارض. |
| [getExcluded()](#getExcluded--) | يحصل على ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [getIndicesCount()](#getIndicesCount--) | عدد الفهارس في هذا [TriMesh](../../com.aspose.threed/trimesh) |
| [getIntIndices()](#getIntIndices--) | تحويل الفهارس إلى مصفوفة أعداد صحيحة 32 بت |
| [getName()](#getName--) | يحصل على الاسم. |
| [getParentNode()](#getParentNode--) | يحصل على أول عقدة أب، إذا تم تعيين أول عقدة أب، سيُفصل هذا الكيان عن عقد الأب الأخرى. |
| [getParentNodes()](#getParentNodes--) | يحصل على جميع عقد الأب، يمكن إرفاق كيان بعدة عقد أب لتكرار الهندسة. |
| [getProperties()](#getProperties--) | يحصل على مجموعة جميع الخصائص. |
| [getProperty(String property)](#getProperty-java.lang.String-) | احصل على قيمة الخاصية المحددة |
| [getScene()](#getScene--) | يحصل على المشهد الذي ينتمي إليه هذا الكائن |
| [getShortIndices()](#getShortIndices--) | تحويل الفهارس إلى مصفوفة أعداد صحيحة 16 بت |
| [getUnmergedVerticesCount()](#getUnmergedVerticesCount--) | عدد الرؤوس غير المدمجة التي تم تمريرها عبر [beginVertex](../../com.aspose.threed/trimesh\#beginVertex) و [endVertex](../../com.aspose.threed/trimesh\#endVertex). |
| [getVertexDeclaration()](#getVertexDeclaration--) | تخطيط الرؤوس للـ [TriMesh](../../com.aspose.threed/trimesh). |
| [getVerticesCount()](#getVerticesCount--) | عدد الرؤوس في هذا [TriMesh](../../com.aspose.threed/trimesh) |
| [getVerticesSizeInBytes()](#getVerticesSizeInBytes--) | الحجم الكلي لجميع الرؤوس بالبايت |
| [hashCode()](#hashCode--) |  |
| [indicesToArray(int[][] result)](#indicesToArray-int-----) | تحويل الفهارس إلى مصفوفة أعداد صحيحة 32 بت |
| [indicesToArray(short[][] result)](#indicesToArray-short-----) | تحويل الفهارس إلى مصفوفة أعداد صحيحة 16 بت |
| [iterator()](#iterator--) | احصل على المُعدِّد لتعداد [Vertex](../../com.aspose.threed/vertex) |
| [loadVerticesFromBytes(byte[] verticesInBytes)](#loadVerticesFromBytes-byte---) | تحميل الرؤوس من البايتات، يجب أن يكون طول البايتات مضاعفًا صحيحًا لحجم الرأس. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readDouble(int idx, VertexField field)](#readDouble-int-com.aspose.threed.VertexField-) | قراءة الحقل من النوع double |
| [readFVector2(int idx, VertexField field)](#readFVector2-int-com.aspose.threed.VertexField-) | قراءة الحقل من النوع vector2 |
| [readFVector3(int idx, VertexField field)](#readFVector3-int-com.aspose.threed.VertexField-) | قراءة الحقل من النوع vector3 |
| [readFVector4(int idx, VertexField field)](#readFVector4-int-com.aspose.threed.VertexField-) | قراءة حقل vector4 |
| [readFloat(int idx, VertexField field)](#readFloat-int-com.aspose.threed.VertexField-) | قراءة حقل float |
| [readVector2(int idx, VertexField field)](#readVector2-int-com.aspose.threed.VertexField-) | قراءة الحقل من النوع vector2 |
| [readVector3(int idx, VertexField field)](#readVector3-int-com.aspose.threed.VertexField-) | قراءة الحقل من النوع vector3 |
| [readVector4(int idx, VertexField field)](#readVector4-int-com.aspose.threed.VertexField-) | قراءة حقل vector4 |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | يزيل خاصية ديناميكية. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | إزالة الخاصية المحددة التي تم التعرف عليها بالاسم. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | يضبط ما إذا كان يجب استبعاد هذا الكيان أثناء التصدير. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | يضبط أول عقدة أب، إذا تم ضبط أول عقدة أب، سيُفصل هذا الكيان عن عقد الأب الأخرى. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | يضبط قيمة الخاصية المحددة |
| [toString()](#toString--) | يحصل على تمثيل النص لـ [TriMesh](../../com.aspose.threed/trimesh) |
| [verticesToArray()](#verticesToArray--) | تحويل بيانات القمم إلى مصفوفة بايت |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write16bIndicesTo(Stream stream)](#write16bIndicesTo-com.aspose.threed.Stream-) | اكتب بيانات الفهارس كعدد صحيح 16 بت إلى الدفق **Example:** |
| [write16bIndicesTo(OutputStream stream)](#write16bIndicesTo-java.io.OutputStream-) | اكتب بيانات الفهارس كعدد صحيح 16 بت إلى الدفق |
| [write32bIndicesTo(Stream stream)](#write32bIndicesTo-com.aspose.threed.Stream-) | اكتب بيانات الفهارس كعدد صحيح 32 بت إلى الدفق **Example:** |
| [write32bIndicesTo(OutputStream stream)](#write32bIndicesTo-java.io.OutputStream-) | اكتب بيانات الفهارس كعدد صحيح 32 بت إلى الدفق |
| [writeVerticesTo(Stream stream)](#writeVerticesTo-com.aspose.threed.Stream-) | اكتب بيانات القمم إلى الدفق المحدد |
| [writeVerticesTo(OutputStream stream)](#writeVerticesTo-java.io.OutputStream-) | اكتب بيانات القمم إلى الدفق المحدد |
### TriMesh(String name, VertexDeclaration declaration) {#TriMesh-java.lang.String-com.aspose.threed.VertexDeclaration-}
```
public TriMesh(String name, VertexDeclaration declaration)
```


تهيئة نسخة من [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم هذا TriMesh |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | إعلان القمة |

### addTriangle(int a, int b, int c) {#addTriangle-int-int-int-}
```
public void addTriangle(int a, int b, int c)
```


إضافة مثلث جديد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | int | فهرس القمة الأولى |
| b | int | فهرس القمة الثانية |
| c | int | فهرس القمة الثالثة |

### beginVertex() {#beginVertex--}
```
public Vertex beginVertex()
```


بدء إضافة رأس

**Returns:**
[Vertex](../../com.aspose.threed/vertex) - The reference of internal vertex object in type [Vertex](../../com.aspose.threed/vertex)
### copyFrom(TriMesh input, VertexDeclaration vd) {#copyFrom-com.aspose.threed.TriMesh-com.aspose.threed.VertexDeclaration-}
```
public static TriMesh copyFrom(TriMesh input, VertexDeclaration vd)
```


نسخ الـ [TriMesh](../../com.aspose.threed/trimesh) من الإدخال مع تخطيط رأس جديد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| input | [TriMesh](../../com.aspose.threed/trimesh) | TriMesh الإدخال للنسخ |
| vd | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | إعلان القمة الجديد لـ TriMesh الناتج |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - A new TriMesh instance with new vertex declaration. **Example:**

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
  VertexDeclaration vd = new VertexDeclaration();
  vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
  vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
  vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
  //convert a mesh to TriMesh, the layout is automatically inferred from input mesh
  var oldTriMesh = TriMesh.fromMesh((new Sphere()).toMesh());
  //now create a new TriMesh from old TriMesh, using explicit memory layout defined by vd
  var newTriMesh = TriMesh.copyFrom(oldTriMesh, vd);
```
### endVertex() {#endVertex--}
```
public int endVertex()
```


إنهاء إضافة رأس

**Returns:**
int
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
### fromMesh(Mesh mesh) {#fromMesh-com.aspose.threed.Mesh-}
```
public static TriMesh fromMesh(Mesh mesh)
```


إنشاء TriMesh من كائن شبكة مُعطى، حيث يتم بناء تعريف الرؤوس بناءً على بنية الشبكة المدخلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - The [TriMesh](../../com.aspose.threed/trimesh) generated from given [Mesh](../../com.aspose.threed/mesh) **Example:** The following code shows how to create a TriMesh with custom memory layout, and export it to file.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
### fromMesh(Mesh mesh, boolean useFloat) {#fromMesh-com.aspose.threed.Mesh-boolean-}
```
public static TriMesh fromMesh(Mesh mesh, boolean useFloat)
```


إنشاء TriMesh من كائن شبكة مُعطى، حيث يتم بناء تعريف الرؤوس بناءً على بنية الشبكة المدخلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |
| useFloat | boolean | استخدم نوع float بدلاً من نوع double لكل مكوّن عنصر القمة. |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - The [TriMesh](../../com.aspose.threed/trimesh) generated from given [Mesh](../../com.aspose.threed/mesh) **Example:** The following code shows how to create a TriMesh with custom memory layout, and export it to file.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
### fromMesh(VertexDeclaration declaration, Mesh mesh) {#fromMesh-com.aspose.threed.VertexDeclaration-com.aspose.threed.Mesh-}
```
public static TriMesh fromMesh(VertexDeclaration declaration, Mesh mesh)
```


إنشاء TriMesh من كائن شبكة مُعطى مع تخطيط رأس محدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | تعريف نوع القمة، أو تخطيط الذاكرة |
| mesh | [Mesh](../../com.aspose.threed/mesh) | شبكة المصدر |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - Instance of TriMesh converted from input mesh with specified vertex's memory layout **Example:** The following code shows how to create a TriMesh with custom memory layout, and export it to file.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
### fromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, boolean generateVertexMapping) {#fromRawData-com.aspose.threed.VertexDeclaration-byte---int---boolean-}
```
public static TriMesh fromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, boolean generateVertexMapping)
```


إنشاء TriMesh من بيانات خام

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| vd | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | إعلان القمة، يجب أن يحتوي على حقل واحد على الأقل. |
| القمم | byte[] | بيانات القمم المدخلة، يجب أن يكون الحد الأدنى لطول القمم أكبر أو مساوي لحجم تعريف القمة. |
| indices | int[] | مؤشرات المثلثات |
| generateVertexMapping | boolean | إنشاء [Vertex](../../com.aspose.threed/vertex) لكل رأس، وهو غير ضروري للاستخدام في التسلسل/إلغاء التسلسل فقط. |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - The [TriMesh](../../com.aspose.threed/trimesh) instance that encapsulated the input byte array. **Remarks:** The returned TriMesh will not copy the input byte array for performance, external changes on the array will be reflected to this instance. **Example:** The following code shows how to construct a TriMesh from raw bytes, this is useful when build your own 3D format

```
var indices = new int[] { 0,  1,  2 };
  var vertices = new byte[]{
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 191,
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 63,
      0, 0, 0, 63,
      0, 0, 0, 0The string representation,
      0, 0, 0, 63
  };
  VertexDeclaration vd = new VertexDeclaration();
  vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
  var triMesh = TriMesh.FromRawData(vd, vertices, indices, true);
```
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
### getCapacity() {#getCapacity--}
```
public int getCapacity()
```


السعة المخصصة مسبقًا للرؤوس.

**Returns:**
int - سعة الرؤوس المخصصة مسبقًا.
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
### getIndicesCount() {#getIndicesCount--}
```
public int getIndicesCount()
```


عدد الفهارس في هذا [TriMesh](../../com.aspose.threed/trimesh)

**Returns:**
int - عدد الفهارس في هذا [TriMesh](../../com.aspose.threed/trimesh)
### getIntIndices() {#getIntIndices--}
```
public int[] getIntIndices()
```


تحويل الفهارس إلى مصفوفة أعداد صحيحة 32 بت

**Returns:**
int[]
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
### getScene() {#getScene--}
```
public Scene getScene()
```


يحصل على المشهد الذي ينتمي إليه هذا الكائن

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShortIndices() {#getShortIndices--}
```
public short[] getShortIndices()
```


تحويل الفهارس إلى مصفوفة أعداد صحيحة 16 بت

**Returns:**
short[]
### getUnmergedVerticesCount() {#getUnmergedVerticesCount--}
```
public int getUnmergedVerticesCount()
```


عدد الرؤوس غير المدمجة التي تم تمريرها عبر [beginVertex](../../com.aspose.threed/trimesh\#beginVertex) و [endVertex](../../com.aspose.threed/trimesh\#endVertex).

**Returns:**
int - عدد الرؤوس غير المدمجة التي تم تمريرها عبر [beginVertex](../../com.aspose.threed/trimesh\#beginVertex) و [endVertex](../../com.aspose.threed/trimesh\#endVertex).
### getVertexDeclaration() {#getVertexDeclaration--}
```
public VertexDeclaration getVertexDeclaration()
```


تخطيط الرؤوس للـ [TriMesh](../../com.aspose.threed/trimesh).

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - The vertex layout of the [TriMesh](../../com.aspose.threed/trimesh).
### getVerticesCount() {#getVerticesCount--}
```
public int getVerticesCount()
```


عدد الرؤوس في هذا [TriMesh](../../com.aspose.threed/trimesh)

**Returns:**
int - عدد الرؤوس في هذا [TriMesh](../../com.aspose.threed/trimesh)
### getVerticesSizeInBytes() {#getVerticesSizeInBytes--}
```
public int getVerticesSizeInBytes()
```


الحجم الكلي لجميع الرؤوس بالبايت

**Returns:**
int - الحجم الكلي لجميع الرؤوس بالبايت
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indicesToArray(int[][] result) {#indicesToArray-int-----}
```
public void indicesToArray(int[][] result)
```


تحويل الفهارس إلى مصفوفة أعداد صحيحة 32 بت

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| النتيجة | int[][] |  |

### indicesToArray(short[][] result) {#indicesToArray-short-----}
```
public void indicesToArray(short[][] result)
```


تحويل الفهارس إلى مصفوفة أعداد صحيحة 16 بت

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| النتيجة | short[][] |  |

### iterator() {#iterator--}
```
public Iterator<Vertex> iterator()
```


احصل على المُعدِّد لتعداد [Vertex](../../com.aspose.threed/vertex)

**Returns:**
java.util.Iterator<com.aspose.threed.Vertex>
### loadVerticesFromBytes(byte[] verticesInBytes) {#loadVerticesFromBytes-byte---}
```
public void loadVerticesFromBytes(byte[] verticesInBytes)
```


تحميل الرؤوس من البايتات، يجب أن يكون طول البايتات مضاعفًا صحيحًا لحجم الرأس. **مثال:** يوضح الكود التالي كيفية إنشاء TriMesh فارغ وتحميل الرؤوس يدويًا من البايتات الخام.

```
var indices = new int[] { 0,  1,  2 };
  var vertices = new byte[]{
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 191,
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 63,
      0, 0, 0, 63,
      0, 0, 0, 0,
      0, 0, 0, 63
  };
  VertexDeclaration vd = new VertexDeclaration();
  vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
  //create an empty TriMesh with specified vertex declaration
  var triMesh = new TriMesh("", vd);
  //load vertices directly from bytes
  triMesh.LoadVerticesFromBytes(vertices);
  triMesh.AddTriangle(0, 1, 2);
```

```
int[] indices = new int[] { 0,  1,  2 };
  byte[] vertices = new byte[]{
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 191,
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 63,
      0, 0, 0, 63,
      0, 0, 0, 0,
      0, 0, 0, 63
  };
  VertexDeclaration vd = new VertexDeclaration();
  vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
  //create an empty TriMesh with specified vertex declaration
  var triMesh = new TriMesh("", vd);
  //load vertices directly from bytes
  triMesh.loadVerticesFromBytes(vertices);
  triMesh.addTriangle(0, 1, 2);
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| verticesInBytes | byte[] |  |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readDouble(int idx, VertexField field) {#readDouble-int-com.aspose.threed.VertexField-}
```
public double readDouble(int idx, VertexField field)
```


قراءة الحقل من النوع double

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| idx | int | مؤشر القمة للقراءة |
| field | [VertexField](../../com.aspose.threed/vertexfield) | الحقل من نوع بيانات متوافق مع float/double |

**Returns:**
double - القيمة المزدوجة لحقل الرأس المحدد
### readFVector2(int idx, VertexField field) {#readFVector2-int-com.aspose.threed.VertexField-}
```
public FVector2 readFVector2(int idx, VertexField field)
```


قراءة الحقل من النوع vector2

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| idx | int | مؤشر القمة للقراءة |
| field | [VertexField](../../com.aspose.threed/vertexfield) | الحقل من نوع بيانات Vector2/FVector2 |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - FVector2 of specified vertex's field
### readFVector3(int idx, VertexField field) {#readFVector3-int-com.aspose.threed.VertexField-}
```
public FVector3 readFVector3(int idx, VertexField field)
```


قراءة الحقل من النوع vector3

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| idx | int | مؤشر القمة للقراءة |
| field | [VertexField](../../com.aspose.threed/vertexfield) | الحقل من نوع بيانات Vector3/FVector3 |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### readFVector4(int idx, VertexField field) {#readFVector4-int-com.aspose.threed.VertexField-}
```
public FVector4 readFVector4(int idx, VertexField field)
```


قراءة حقل vector4

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| idx | int | مؤشر القمة للقراءة |
| field | [VertexField](../../com.aspose.threed/vertexfield) | الحقل من نوع بيانات Vector4/FVector4 |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### readFloat(int idx, VertexField field) {#readFloat-int-com.aspose.threed.VertexField-}
```
public float readFloat(int idx, VertexField field)
```


قراءة حقل float

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| idx | int | مؤشر القمة للقراءة |
| field | [VertexField](../../com.aspose.threed/vertexfield) | الحقل من نوع بيانات متوافق مع float/double |

**Returns:**
float - القيمة العشرية لحقل الرأس المحدد
### readVector2(int idx, VertexField field) {#readVector2-int-com.aspose.threed.VertexField-}
```
public Vector2 readVector2(int idx, VertexField field)
```


قراءة الحقل من النوع vector2

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| idx | int | مؤشر القمة للقراءة |
| field | [VertexField](../../com.aspose.threed/vertexfield) | الحقل من نوع بيانات Vector2/FVector2 |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Vector2 of specified vertex's field
### readVector3(int idx, VertexField field) {#readVector3-int-com.aspose.threed.VertexField-}
```
public Vector3 readVector3(int idx, VertexField field)
```


قراءة الحقل من النوع vector3

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| idx | int | مؤشر القمة للقراءة |
| field | [VertexField](../../com.aspose.threed/vertexfield) | الحقل من نوع بيانات Vector3/FVector3 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### readVector4(int idx, VertexField field) {#readVector4-int-com.aspose.threed.VertexField-}
```
public Vector4 readVector4(int idx, VertexField field)
```


قراءة حقل vector4

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| idx | int | مؤشر القمة للقراءة |
| field | [VertexField](../../com.aspose.threed/vertexfield) | الحقل من نوع بيانات Vector4/FVector4 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
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

### toString() {#toString--}
```
public String toString()
```


يحصل على تمثيل النص لـ [TriMesh](../../com.aspose.threed/trimesh)

**Returns:**
java.lang.String - تمثيل السلسلة النصية
### verticesToArray() {#verticesToArray--}
```
public byte[] verticesToArray()
```


تحويل بيانات القمم إلى مصفوفة بايت

**Returns:**
byte[]
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

### write16bIndicesTo(Stream stream) {#write16bIndicesTo-com.aspose.threed.Stream-}
```
public void write16bIndicesTo(Stream stream)
```


اكتب بيانات الفهارس كعدد صحيح 16 بت إلى الدفق **Example:**

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh
      var mesh = (new Sphere()).toMesh();
      var triMesh = TriMesh.fromMesh(mesh);
      //save it to a stream, 115 vertices * 32bytes per vertex
      var stream = new ByteArrayOutputStream();
      try(var s = Stream.wrap(stream)) {
          triMesh.writeVerticesTo(s);
          //save indices as ushort to stream, 504 indices * 2 bytes per index
          triMesh.write16bIndicesTo(s);
      }
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

### write16bIndicesTo(OutputStream stream) {#write16bIndicesTo-java.io.OutputStream-}
```
public void write16bIndicesTo(OutputStream stream)
```


اكتب بيانات الفهارس كعدد صحيح 16 بت إلى الدفق

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | تدفق | java.io.OutputStream | **مثال:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh    
     var mesh = (new Sphere()).toMesh();    
     var triMesh = TriMesh.fromMesh(mesh);    
     //save it to a stream, 115 vertices * 32bytes per vertex    
     var stream = new ByteArrayOutputStream();    
     triMesh.writeVerticesTo(stream);    
     //save indices as ushort to stream, 504 indices * 2 bytes per index    
     triMesh.write16bIndicesTo(stream);
``` |

### write32bIndicesTo(Stream stream) {#write32bIndicesTo-com.aspose.threed.Stream-}
```
public void write32bIndicesTo(Stream stream)
```


اكتب بيانات الفهارس كعدد صحيح 32 بت إلى الدفق **Example:**

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh
      var mesh = (new Sphere()).toMesh();
      var triMesh = TriMesh.fromMesh(mesh);
      //save it to a stream, 115 vertices * 32bytes per vertex
      var stream = new ByteArrayOutputStream();
      try(var s = Stream.wrap(stream)) {
          triMesh.writeVerticesTo(s);
          //save indices as ushort to stream, 504 indices * 2 bytes per index
          triMesh.write32bIndicesTo(s);
      }
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

### write32bIndicesTo(OutputStream stream) {#write32bIndicesTo-java.io.OutputStream-}
```
public void write32bIndicesTo(OutputStream stream)
```


اكتب بيانات الفهارس كعدد صحيح 32 بت إلى الدفق

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | تدفق | java.io.OutputStream | **مثال:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh    
      var mesh = (new Sphere()).toMesh();    
      var triMesh = TriMesh.fromMesh(mesh);    
      //save it to a stream, 115 vertices * 32bytes per vertex    
      var stream = new ByteArrayOutputStream();    
      triMesh.writeVerticesTo(stream);    
      //save indices as ushort to stream, 504 indices * 2 bytes per index    
      triMesh.write32bIndicesTo(stream);
``` |

### writeVerticesTo(Stream stream) {#writeVerticesTo-com.aspose.threed.Stream-}
```
public void writeVerticesTo(Stream stream)
```


اكتب بيانات القمم إلى الدفق المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | stream | [Stream](../../com.aspose.threed/stream) | المسار الذي سيتم كتابة بيانات الرؤوس إليه **مثال:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh
      var mesh = (new Sphere()).toMesh();
      var triMesh = TriMesh.fromMesh(mesh);
      //save it to a stream, 115 vertices * 32bytes per vertex
      var stream = new ByteArrayOutputStream();
      try(var s = Stream.wrap(stream)) {
          triMesh.writeVerticesTo(s);
          //save indices as ushort to stream, 504 indices * 2 bytes per index
          triMesh.write16bIndicesTo(s);
      }
``` |

### writeVerticesTo(OutputStream stream) {#writeVerticesTo-java.io.OutputStream-}
```
public void writeVerticesTo(OutputStream stream)
```


اكتب بيانات القمم إلى الدفق المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | تدفق | java.io.OutputStream | المسار الذي سيتم كتابة بيانات الرؤوس إليه **مثال:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh    
      var mesh = (new Sphere()).toMesh();    
      var triMesh = TriMesh.fromMesh(mesh);    
      //save it to a stream, 115 vertices * 32bytes per vertex    
      var stream = new ByteArrayOutputStream();    
      triMesh.writeVerticesTo(stream);    
      //save indices as ushort to stream, 504 indices * 2 bytes per index    
      triMesh.write16bIndicesTo(stream);
``` |

