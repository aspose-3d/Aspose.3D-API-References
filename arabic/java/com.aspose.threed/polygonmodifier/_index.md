---
title: "PolygonModifier"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "أدوات لتعديل المضلعات"
type: docs
weight: 134
url: /ar/java/com.aspose.threed/polygonmodifier/
---

**Inheritance:**
java.lang.Object
```
public class PolygonModifier
```

أدوات لتعديل المضلعات
## الطرق

| طريقة | الوصف |
| --- | --- |
| [applyTransform(Node node, Matrix4 transform)](#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-) | تطبيق مصفوفة التحويل على نقاط التحكم في جميع الأشكال الهندسية |
| [buildTangentBinormal(Mesh mesh)](#buildTangentBinormal-com.aspose.threed.Mesh-) | سيتم إنشاء المتجه المماس والبينورمال على الشبكة. يتطلب وجود العادي، إذا لم يكن العادي موجودًا على الشبكة، سيتم أيضًا إنشاء بيانات العادي من الموضع. |
| [buildTangentBinormal(Scene scene)](#buildTangentBinormal-com.aspose.threed.Scene-) | سيتم إنشاء المتجه المماس والبينورمال على جميع الشبكات في المشهد. يتطلب وجود العادي، إذا لم يكن العادي موجودًا على الشبكة، سيتم أيضًا إنشاء بيانات العادي من الموضع. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateNormal(Mesh mesh)](#generateNormal-com.aspose.threed.Mesh-) | إنشاء بيانات العادي من تعريف الشبكة |
| [generateUV(Mesh mesh)](#generateUV-com.aspose.threed.Mesh-) | إنشاء بيانات UV من الشبكة المدخلة المعطاة |
| [generateUV(Mesh mesh, VertexElementNormal normals)](#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-) | إنشاء بيانات UV من الشبكة المدخلة المعطاة وبيانات العادي المحددة. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [mergeMesh(Node node)](#mergeMesh-com.aspose.threed.Node-) | تحويل عقدة كاملة إلى شبكة محوّلة واحدة. عناصر Vertex مثل الإحداثيات العادية/الملمسية غير مدعومة بعد |
| [mergeMesh(Scene scene)](#mergeMesh-com.aspose.threed.Scene-) | تحويل مشهد كامل إلى شبكة محوّلة واحدة. عناصر Vertex مثل الإحداثيات العادية/الملمسية غير مدعومة بعد |
| [mergeMesh(List<Node> nodes)](#mergeMesh-java.util.List-com.aspose.threed.Node--) | تحويل عقدة كاملة إلى شبكة محوّلة واحدة. عناصر Vertex مثل الإحداثيات العادية/الملمسية غير مدعومة بعد |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [scale(Node node, Vector3 scale)](#scale-com.aspose.threed.Node-com.aspose.threed.Vector3-) | تحجيم جميع الهندسات (تحجيم نقاط التحكم وليس مصفوفة التحويل) في هذه العقدة |
| [scale(Scene scene, Vector3 scale)](#scale-com.aspose.threed.Scene-com.aspose.threed.Vector3-) | تحجيم جميع الهندسات (تحجيم نقاط التحكم وليس مصفوفة التحويل) في هذا المشهد |
| [splitMesh(Mesh mesh, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Mesh-com.aspose.threed.SplitMeshPolicy-) | تقسيم الشبكة إلى شبكات فرعية بواسطة [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Node node, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-) | تقسيم الشبكة إلى شبكات فرعية بواسطة [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-) | تقسيم الشبكة إلى شبكات فرعية بواسطة [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-boolean-) | تقسيم الشبكة إلى شبكات فرعية بواسطة [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Scene scene, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-) | تقسيم الشبكة إلى شبكات فرعية بواسطة [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-) | تقسيم الشبكة إلى شبكات فرعية بواسطة [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [toString()](#toString--) |  |
| [triangulate(Mesh mesh)](#triangulate-com.aspose.threed.Mesh-) | تحويل شبكة قائمة على المضلع إلى شبكة مثلثية كاملة |
| [triangulate(Scene scene)](#triangulate-com.aspose.threed.Scene-) | تحويل جميع الشبكات القائمة على المضلع إلى شبكة مثلثية كاملة |
| [triangulate(List<Vector4> controlPoints)](#triangulate-java.util.List-com.aspose.threed.Vector4--) | تحويل مضلع إلى مثلثات، ترتيب المضلع يُحدَّد بواسطة `controlPoints` |
| [triangulate(List<Vector4> controlPoints, int[] polygon)](#triangulate-java.util.List-com.aspose.threed.Vector4--int---) | تحويل مضلع إلى مثلثات |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----) | تحويل شبكة قائمة على المضلع إلى مثلثات |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons, boolean generateNormals, Vector3[][] nor_out)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----boolean-com.aspose.threed.Vector3-----) | تحويل شبكة قائمة على المضلع إلى شبكة مثلثية كاملة |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### applyTransform(Node node, Matrix4 transform) {#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-}
```
public static void applyTransform(Node node, Matrix4 transform)
```


تطبيق مصفوفة التحويل على نقاط التحكم في جميع الأشكال الهندسية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | أي هندسات العقدة سيتم تطبيق التحويل المعطى عليها |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | مصفوفة التحويل التي سيتم تطبيقها على نقاط التحكم. |

### buildTangentBinormal(Mesh mesh) {#buildTangentBinormal-com.aspose.threed.Mesh-}
```
public static void buildTangentBinormal(Mesh mesh)
```


سيتم إنشاء المتجه المماس والبينورمال على الشبكة. الـ Normal مطلوب؛ إذا لم يكن الـ Normal موجودًا على الشبكة، سيتم أيضًا إنشاء بيانات الـ Normal من الموضع. الـ UV مطلوب أيضًا، وسيتم رفع استثناء إذا لم يُعثر على أي UV.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

### buildTangentBinormal(Scene scene) {#buildTangentBinormal-com.aspose.threed.Scene-}
```
public static void buildTangentBinormal(Scene scene)
```


سيتم إنشاء المتجه المماس والبينورمال على جميع الشبكات في المشهد. الـ Normal مطلوب؛ إذا لم يكن الـ Normal موجودًا على الشبكة، سيتم أيضًا إنشاء بيانات الـ Normal من الموضع. الـ UV مطلوب أيضًا، وسيتم تجاهل الشبكة إذا لم يُحدَّد أي UV.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

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
### generateNormal(Mesh mesh) {#generateNormal-com.aspose.threed.Mesh-}
```
public static VertexElementNormal generateNormal(Mesh mesh)
```


إنشاء بيانات العادي من تعريف الشبكة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

**Returns:**
[VertexElementNormal](../../com.aspose.threed/vertexelementnormal) - [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) instance with normal data.
### generateUV(Mesh mesh) {#generateUV-com.aspose.threed.Mesh-}
```
public static VertexElementUV generateUV(Mesh mesh)
```


إنشاء بيانات UV من الشبكة المدخلة المعطاة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | الشبكة المدخلة |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Generated UV data
### generateUV(Mesh mesh, VertexElementNormal normals) {#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-}
```
public static VertexElementUV generateUV(Mesh mesh, VertexElementNormal normals)
```


إنشاء بيانات UV من الشبكة المدخلة المعطاة وبيانات العادي المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | الشبكة المدخلة |
| normals | [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) | بيانات الـ Normal |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Generated UV data
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### mergeMesh(Node node) {#mergeMesh-com.aspose.threed.Node-}
```
public static Mesh mergeMesh(Node node)
```


تحويل عقدة كاملة إلى شبكة محوّلة واحدة. عناصر Vertex مثل الإحداثيات العادية/الملمسية غير مدعومة بعد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | العقدة المراد دمجها |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Merged mesh **Example:** The following code shows how to merge all objects from nodes into a single mesh.

```
//Input file may contains multiple objects
          var scene = Scene.fromFile("input.fbx");
          //now merge them into a single mesh
          Mesh merged = PolygonModifier.mergeMesh(scene.getRootNode());
          //then we save it to a file with only one mesh
          var newScene = new Scene(merged);
          newScene.save("test.obj");
```
### mergeMesh(Scene scene) {#mergeMesh-com.aspose.threed.Scene-}
```
public static Mesh mergeMesh(Scene scene)
```


تحويل مشهد كامل إلى شبكة محوّلة واحدة. عناصر Vertex مثل الإحداثيات العادية/الملمسية غير مدعومة بعد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | المشهد المراد دمجه |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The merged mesh **Example:** The following code shows how to merge all objects from a scene into a single mesh.

```
//Input file may contains multiple objects
         var scene = Scene.fromFile("input.fbx");
         //now merge them into a single mesh
         Mesh merged = PolygonModifier.mergeMesh(scene);
         //then we save it to a file with only one mesh
         var newScene = new Scene(merged);
         newScene.save("test.obj");
```
### mergeMesh(List<Node> nodes) {#mergeMesh-java.util.List-com.aspose.threed.Node--}
```
public static Mesh mergeMesh(List<Node> nodes)
```


تحويل عقدة كاملة إلى شبكة محوّلة واحدة. عناصر Vertex مثل الإحداثيات العادية/الملمسية غير مدعومة بعد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العقد | java.util.List<com.aspose.threed.Node> | العقد المراد دمجها |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Merged mesh **Example:** The following code shows how to merge all objects from nodes into a single mesh.

```
//Input file may contains multiple objects
         var scene = Scene.fromFile("input.fbx");
         //now merge them into a single mesh
         Mesh merged = PolygonModifier.mergeMesh(scene.getRootNode().getChildNodes());
         //then we save it to a file with only one mesh
         var newScene = new Scene(merged);
         newScene.save("test.obj");
```
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### scale(Node node, Vector3 scale) {#scale-com.aspose.threed.Node-com.aspose.threed.Vector3-}
```
public static void scale(Node node, Vector3 scale)
```


تحجيم جميع الهندسات (تحجيم نقاط التحكم وليس مصفوفة التحويل) في هذه العقدة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | العقدة المراد تحجيمها |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | عامل التحجيم **Example:** يوضح الكود التالي كيفية تحجيم جميع الهندسات في المشهد بمقدار 10 مرات. |

```
//Load a test file for scaling
 		 var scene = Scene.fromFile("input.fbx");
 		 //scale all geometries 10 times.
 		 PolygonModifier.scale(scene.getRootNode(), new Vector3(10, 10, 10));
 		 scene.save("test.obj");
``` |

### scale(Scene scene, Vector3 scale) {#scale-com.aspose.threed.Scene-com.aspose.threed.Vector3-}
```
public static Scene scale(Scene scene, Vector3 scale)
```


تحجيم جميع الهندسات (تحجيم نقاط التحكم وليس مصفوفة التحويل) في هذا المشهد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | المشهد المراد تحجيمه |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | عامل التحجيم **Example:** يوضح الكود التالي كيفية تحجيم جميع الهندسات في المشهد بمقدار 10 مرات. |

```
//Load a test file for scaling
 		var scene = Scene.fromFile("input.fbx");
 		//scale all geometries 10 times.
 		PolygonModifier.scale(scene, new Vector3(10, 10, 10));
 		scene.save("test.obj");
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### splitMesh(Mesh mesh, SplitMeshPolicy policy) {#splitMesh-com.aspose.threed.Mesh-com.aspose.threed.SplitMeshPolicy-}
```
public static Mesh[] splitMesh(Mesh mesh, SplitMeshPolicy policy)
```


تقسيم الشبكة إلى شبكات فرعية بواسطة [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). كل شبكة فرعية ستستخدم مادة واحدة فقط. الشبكة الأصلية لن تتغير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

**Returns:**
com.aspose.threed.Mesh[] - شبكات مقسمة جديدة **مثال:** يوضح الكود التالي كيفية تقسيم صندوق إلى شبكات فرعية باستخدام مؤشرات المواد.

```
// Create a mesh of box(A box is composed by 6 planes)
 			Mesh box = (new Box()).toMesh();
 			// Create a material element on this mesh
 			VertexElementMaterial mat = (VertexElementMaterial)box.createElement(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX);
 			// And specify different material index for each plane
 			mat.setIndices(new int[] { 0, 1, 2, 3, 4, 5 });
 			// Now split it into 6 sub meshes, we specified 6 different materials on each plane, each plane will become a sub mesh.
 			// We used the CloneData policy, each plane will has the same control point information or control point-based vertex element information.
 			Mesh[] planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.CLONE_DATA);
 
 			// Now split it into 2 sub meshes, first mesh will contains 0/1/2 planes, and second mesh will contains the 3/4/5th planes.
 			mat.setIndices(new int[] { 0, 0, 0, 1, 1, 1 });
 			// We used the CompactData policy, each plane will has its own control point information or control point-based vertex element information.
 			planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.COMPACT_DATA);
```
### splitMesh(Node node, SplitMeshPolicy policy) {#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-}
```
public static void splitMesh(Node node, SplitMeshPolicy policy)
```


قسّم الشبكة إلى شبكات فرعية باستخدام [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). كل شبكة فرعية ستستخدم مادة واحدة فقط. نفّذ تقسيم الشبكة على عقدة **مثال:** يوضح الكود التالي كيفية تقسيم صندوق إلى شبكات فرعية باستخدام مؤشرات المواد.

```
// Create a mesh of box(A box is composed by 6 planes)
 			Mesh box = (new Box()).toMesh();
 			// Create a material element on this mesh
 			VertexElementMaterial mat = (VertexElementMaterial)box.createElement(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX);
 			// And specify different material index for each plane
 			mat.setIndices(new int[] { 0, 1, 2, 3, 4, 5 });
 			// Now split it into 6 sub meshes, we specified 6 different materials on each plane, each plane will become a sub mesh.
 			// We used the CloneData policy, each plane will has the same control point information or control point-based vertex element information.
 			Mesh[] planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.CLONE_DATA);
 
 			// Now split it into 2 sub meshes, first mesh will contains 0/1/2 planes, and second mesh will contains the 3/4/5th planes.
 			mat.setIndices(new int[] { 0, 0, 0, 1, 1, 1 });
 			// We used the CompactData policy, each plane will has its own control point information or control point-based vertex element information.
 			planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.COMPACT_DATA);
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes) {#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)
```


قسّم الشبكة إلى شبكات فرعية باستخدام [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). كل شبكة فرعية ستستخدم مادة واحدة فقط. نفّذ تقسيم الشبكة على عقدة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
|  | createChildNodes | boolean | أنشئ عقدًا فرعية لكل شبكة فرعية. **مثال:** يوضح الكود التالي كيفية تقسيم صندوق إلى شبكات فرعية باستخدام مؤشرات المواد. |

```
// Create a mesh of box(A box is composed by 6 planes)
 			Mesh box = (new Box()).toMesh();
 			// Create a material element on this mesh
 			VertexElementMaterial mat = (VertexElementMaterial)box.createElement(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX);
 			// And specify different material index for each plane
 			mat.setIndices(new int[] { 0, 1, 2, 3, 4, 5 });
 			// Now split it into 6 sub meshes, we specified 6 different materials on each plane, each plane will become a sub mesh.
 			// We used the CloneData policy, each plane will has the same control point information or control point-based vertex element information.
 			Mesh[] planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.CLONE_DATA);
 
 			// Now split it into 2 sub meshes, first mesh will contains 0/1/2 planes, and second mesh will contains the 3/4/5th planes.
 			mat.setIndices(new int[] { 0, 0, 0, 1, 1, 1 });
 			// We used the CompactData policy, each plane will has its own control point information or control point-based vertex element information.
 			planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.COMPACT_DATA);
``` |

### splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes, boolean removeOldMesh) {#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-boolean-}
```
public static void splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes, boolean removeOldMesh)
```


قسّم الشبكة إلى شبكات فرعية باستخدام [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). كل شبكة فرعية ستستخدم مادة واحدة فقط. نفّذ تقسيم الشبكة على عقدة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
| createChildNodes | boolean | أنشئ عقدًا فرعية لكل شبكة فرعية. |
|  | removeOldMesh | boolean | أزل الشبكة القديمة بعد التقسيم، إذا كان هذا المعامل false، فإن الشبكتين القديمة والجديدة ستتواجدان معًا. **مثال:** يوضح الكود التالي كيفية تقسيم صندوق إلى شبكات فرعية باستخدام مؤشرات المواد. |

```
// Create a mesh of box(A box is composed by 6 planes)
 			Mesh box = (new Box()).toMesh();
 			// Create a material element on this mesh
 			VertexElementMaterial mat = (VertexElementMaterial)box.createElement(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX);
 			// And specify different material index for each plane
 			mat.setIndices(new int[] { 0, 1, 2, 3, 4, 5 });
 			// Now split it into 6 sub meshes, we specified 6 different materials on each plane, each plane will become a sub mesh.
 			// We used the CloneData policy, each plane will has the same control point information or control point-based vertex element information.
 			Mesh[] planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.CLONE_DATA);
 
 			// Now split it into 2 sub meshes, first mesh will contains 0/1/2 planes, and second mesh will contains the 3/4/5th planes.
 			mat.setIndices(new int[] { 0, 0, 0, 1, 1, 1 });
 			// We used the CompactData policy, each plane will has its own control point information or control point-based vertex element information.
 			planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.COMPACT_DATA);
``` |

### splitMesh(Scene scene, SplitMeshPolicy policy) {#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-}
```
public static void splitMesh(Scene scene, SplitMeshPolicy policy)
```


قسّم الشبكة إلى شبكات فرعية باستخدام [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). كل شبكة فرعية ستستخدم مادة واحدة فقط. نفّذ تقسيم الشبكة على جميع عقد المشهد. **مثال:** يوضح الكود التالي كيفية تقسيم صندوق إلى شبكات فرعية باستخدام مؤشرات المواد.

```
// Create a mesh of box(A box is composed by 6 planes)
 			Mesh box = (new Box()).toMesh();
 			// Create a material element on this mesh
 			VertexElementMaterial mat = (VertexElementMaterial)box.createElement(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX);
 			// And specify different material index for each plane
 			mat.setIndices(new int[] { 0, 1, 2, 3, 4, 5 });
 			// Now split it into 6 sub meshes, we specified 6 different materials on each plane, each plane will become a sub mesh.
 			// We used the CloneData policy, each plane will has the same control point information or control point-based vertex element information.
 			Mesh[] planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.CLONE_DATA);
 
 			// Now split it into 2 sub meshes, first mesh will contains 0/1/2 planes, and second mesh will contains the 3/4/5th planes.
 			mat.setIndices(new int[] { 0, 0, 0, 1, 1, 1 });
 			// We used the CompactData policy, each plane will has its own control point information or control point-based vertex element information.
 			planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.COMPACT_DATA);
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh) {#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)
```


قسّم الشبكة إلى شبكات فرعية باستخدام [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). كل شبكة فرعية ستستخدم مادة واحدة فقط. نفّذ تقسيم الشبكة على جميع عقد المشهد. **مثال:** يوضح الكود التالي كيفية تقسيم صندوق إلى شبكات فرعية باستخدام مؤشرات المواد.

```
// Create a mesh of box(A box is composed by 6 planes)
 			Mesh box = (new Box()).toMesh();
 			// Create a material element on this mesh
 			VertexElementMaterial mat = (VertexElementMaterial)box.createElement(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX);
 			// And specify different material index for each plane
 			mat.setIndices(new int[] { 0, 1, 2, 3, 4, 5 });
 			// Now split it into 6 sub meshes, we specified 6 different materials on each plane, each plane will become a sub mesh.
 			// We used the CloneData policy, each plane will has the same control point information or control point-based vertex element information.
 			Mesh[] planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.CLONE_DATA);
 
 			// Now split it into 2 sub meshes, first mesh will contains 0/1/2 planes, and second mesh will contains the 3/4/5th planes.
 			mat.setIndices(new int[] { 0, 0, 0, 1, 1, 1 });
 			// We used the CompactData policy, each plane will has its own control point information or control point-based vertex element information.
 			planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.COMPACT_DATA);
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
| removeOldMesh | boolean |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### triangulate(Mesh mesh) {#triangulate-com.aspose.threed.Mesh-}
```
public static Mesh triangulate(Mesh mesh)
```


تحويل شبكة قائمة على المضلع إلى شبكة مثلثية كاملة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | الشبكة الأصلية غير المثلثية |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The generated new triangle mesh **Example:** The following code shows how to merge all objects from a scene into a single mesh.

```
var mesh = new Cylinder().toMesh();
 
 		//Triangulate this quadrangle-based mesh to triangle-based
 		mesh = PolygonModifier.triangulate(mesh);
 
 		var scene = new Scene(mesh);
 
         scene.save("test.obj");
```
### triangulate(Scene scene) {#triangulate-com.aspose.threed.Scene-}
```
public static void triangulate(Scene scene)
```


تحويل جميع الشبكات القائمة على المضلع إلى شبكة مثلثية كاملة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | scene | [Scene](../../com.aspose.threed/scene) | المشهد المراد معالجته **مثال:** يوضح الكود التالي كيفية دمج جميع الكائنات من مشهد إلى شبكة واحدة. |

```
var mesh = new Cylinder().toMesh();
 
 		//Triangulate this quadrangle-based mesh to triangle-based
 		mesh = PolygonModifier.triangulate(mesh);
 
 		var scene = new Scene(mesh);
 
         scene.save("test.obj");
``` |

### triangulate(List<Vector4> controlPoints) {#triangulate-java.util.List-com.aspose.threed.Vector4--}
```
public static int[][] triangulate(List<Vector4> controlPoints)
```


تحويل مضلع إلى مثلثات، ترتيب المضلع يُحدَّد بواسطة `controlPoints`

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | نقاط التحكم في الشبكة |

**Returns:**
int[][] - مجموعة من المثلثات **مثال:** يوضح الكود التالي كيفية دمج جميع الكائنات من مشهد إلى شبكة واحدة.

```
var mesh = new Cylinder().toMesh();
 
 		//Triangulate this quadrangle-based mesh to triangle-based
 		mesh = PolygonModifier.triangulate(mesh);
 
 		var scene = new Scene(mesh);
 
         scene.save("test.obj");
```
### triangulate(List<Vector4> controlPoints, int[] polygon) {#triangulate-java.util.List-com.aspose.threed.Vector4--int---}
```
public static int[][] triangulate(List<Vector4> controlPoints, int[] polygon)
```


تحويل مضلع إلى مثلثات

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | نقاط التحكم في الشبكة |
| مضلع | int[] | وجه المضلع |

**Returns:**
int[][] - مجموعة من المثلثات **مثال:** يوضح الكود التالي كيفية دمج جميع الكائنات من مشهد إلى شبكة واحدة.

```
var mesh = new Cylinder().toMesh();
 
 		//Triangulate this quadrangle-based mesh to triangle-based
 		mesh = PolygonModifier.triangulate(mesh);
 
 		var scene = new Scene(mesh);
 
         scene.save("test.obj");
```
### triangulate(List<Vector4> controlPoints, List<int[]> polygons) {#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----}
```
public static int[][] triangulate(List<Vector4> controlPoints, List<int[]> polygons)
```


تحويل شبكة قائمة على المضلع إلى مثلثات

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | نقاط التحكم في الشبكة |
| مضلعات | java.util.List<int[]> | وجوه المضلعات |

**Returns:**
int[][] - مجموعة من المثلثات **مثال:** يوضح الكود التالي كيفية دمج جميع الكائنات من مشهد إلى شبكة واحدة.

```
var mesh = new Cylinder().toMesh();
 
 		//Triangulate this quadrangle-based mesh to triangle-based
 		mesh = PolygonModifier.triangulate(mesh);
 
 		var scene = new Scene(mesh);
 
         scene.save("test.obj");
```
### triangulate(List<Vector4> controlPoints, List<int[]> polygons, boolean generateNormals, Vector3[][] nor_out) {#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----boolean-com.aspose.threed.Vector3-----}
```
public static int[][] triangulate(List<Vector4> controlPoints, List<int[]> polygons, boolean generateNormals, Vector3[][] nor_out)
```


تحويل شبكة قائمة على المضلع إلى شبكة مثلثية كاملة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | نقاط التحكم في الشبكة |
| مضلعات | java.util.List<int[]> | وجوه المضلعات |
| generateNormals | boolean | إنشاء المتجهات العمودية |
| nor_out | [Vector3\[\]](../../com.aspose.threed/vector3) | المتجه العمودي المولد لكل نقطة تحكم |

**Returns:**
int[][] - مجموعة من المثلثات **مثال:** يوضح الكود التالي كيفية دمج جميع الكائنات من مشهد إلى شبكة واحدة.

```
var mesh = new Cylinder().toMesh();
 
 		//Triangulate this quadrangle-based mesh to triangle-based
 		mesh = PolygonModifier.triangulate(mesh);
 
 		var scene = new Scene(mesh);
 
         scene.save("test.obj");
```
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

