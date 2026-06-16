---
title: "PolygonModifier"
second_title: "Aspose.3D for Java API Referansı"
description: "Poligonları değiştirmek için araçlar"
type: docs
weight: 134
url: /tr/java/com.aspose.threed/polygonmodifier/
---

**Inheritance:**
java.lang.Object
```
public class PolygonModifier
```

Poligonları değiştirmek için araçlar
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [applyTransform(Node node, Matrix4 transform)](#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-) | Tüm geometrilerin kontrol noktalarına dönüşüm matrisini uygula |
| [buildTangentBinormal(Mesh mesh)](#buildTangentBinormal-com.aspose.threed.Mesh-) | Bu, ağ üzerinde teğet ve binormal oluşturur. Normal gereklidir, eğer ağda normal yoksa, konumdan normal verisini de oluşturur. |
| [buildTangentBinormal(Scene scene)](#buildTangentBinormal-com.aspose.threed.Scene-) | Bu, sahnedeki tüm ağlar üzerinde teğet ve binormal oluşturur. Normal gereklidir, eğer ağda normal yoksa, konumdan normal verisini de oluşturur. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateNormal(Mesh mesh)](#generateNormal-com.aspose.threed.Mesh-) | Ağ tanımından normal verisi oluştur |
| [generateUV(Mesh mesh)](#generateUV-com.aspose.threed.Mesh-) | Verilen giriş ağından UV verisi oluştur |
| [generateUV(Mesh mesh, VertexElementNormal normals)](#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-) | Verilen giriş ağından ve belirtilen normal verisinden UV verisi oluştur. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [mergeMesh(Node node)](#mergeMesh-com.aspose.threed.Node-) | Bir bütün düğümü tek bir dönüştürülmüş ağaca dönüştürün; normal/doku koordinatları gibi Vertex öğeleri henüz desteklenmiyor. |
| [mergeMesh(Scene scene)](#mergeMesh-com.aspose.threed.Scene-) | Bir bütün sahneyi tek bir dönüştürülmüş ağaca dönüştürün; normal/doku koordinatları gibi Vertex öğeleri henüz desteklenmiyor. |
| [mergeMesh(List<Node> nodes)](#mergeMesh-java.util.List-com.aspose.threed.Node--) | Bir bütün düğümü tek bir dönüştürülmüş ağaca dönüştürün; normal/doku koordinatları gibi Vertex öğeleri henüz desteklenmiyor. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [scale(Node node, Vector3 scale)](#scale-com.aspose.threed.Node-com.aspose.threed.Vector3-) | Bu düğümdeki tüm geometrileri ölçeklendirin (Kontrol noktalarını ölçeklendirin, dönüşüm matrisini değil). |
| [scale(Scene scene, Vector3 scale)](#scale-com.aspose.threed.Scene-com.aspose.threed.Vector3-) | Bu sahnedeki tüm geometrileri ölçeklendirin (Kontrol noktalarını ölçeklendirin, dönüşüm matrisini değil). |
| [splitMesh(Mesh mesh, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Mesh-com.aspose.threed.SplitMeshPolicy-) | Ağacı [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) ile alt-ağaclara bölün. |
| [splitMesh(Node node, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-) | Ağacı [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) ile alt-ağaclara bölün. |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-) | Ağacı [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) ile alt-ağaclara bölün. |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-boolean-) | Ağacı [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) ile alt-ağaclara bölün. |
| [splitMesh(Scene scene, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-) | Ağacı [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) ile alt-ağaclara bölün. |
| [splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-) | Ağacı [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) ile alt-ağaclara bölün. |
| [toString()](#toString--) |  |
| [triangulate(Mesh mesh)](#triangulate-com.aspose.threed.Mesh-) | Poligon tabanlı bir ağı tam üçgen ağına dönüştürün. |
| [triangulate(Scene scene)](#triangulate-com.aspose.threed.Scene-) | Tüm poligon tabanlı ağları tam üçgen ağına dönüştürün. |
| [triangulate(List<Vector4> controlPoints)](#triangulate-java.util.List-com.aspose.threed.Vector4--) | Bir poligonu üçgenlere dönüştürün, poligonun sırası `controlPoints` tarafından tanımlanır. |
| [triangulate(List<Vector4> controlPoints, int[] polygon)](#triangulate-java.util.List-com.aspose.threed.Vector4--int---) | Bir poligonu üçgenlere dönüştürün. |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----) | Poligon tabanlı bir ağı üçgenlere dönüştürün. |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons, boolean generateNormals, Vector3[][] nor_out)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----boolean-com.aspose.threed.Vector3-----) | Poligon tabanlı bir ağı tam üçgen ağına dönüştürün. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### applyTransform(Node node, Matrix4 transform) {#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-}
```
public static void applyTransform(Node node, Matrix4 transform)
```


Tüm geometrilerin kontrol noktalarına dönüşüm matrisini uygula

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Verilen dönüşümle hangi düğümün geometrileri uygulanacak? |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | Kontrol noktalarına uygulanacak dönüşüm matrisi. |

### buildTangentBinormal(Mesh mesh) {#buildTangentBinormal-com.aspose.threed.Mesh-}
```
public static void buildTangentBinormal(Mesh mesh)
```


Bu, mesh üzerinde teğet ve binormal oluşturur. Normal gereklidir, eğer mesh üzerinde normal yoksa, konumdan normal verisi de oluşturulur. UV de gereklidir, UV bulunamazsa bir istisna yükseltilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

### buildTangentBinormal(Scene scene) {#buildTangentBinormal-com.aspose.threed.Scene-}
```
public static void buildTangentBinormal(Scene scene)
```


Bu, sahnedeki tüm mesh'lerde teğet ve binormal oluşturur. Normal gereklidir, eğer mesh üzerinde normal yoksa, konumdan normal verisi de oluşturulur. UV de gereklidir, UV tanımlı değilse mesh yok sayılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateNormal(Mesh mesh) {#generateNormal-com.aspose.threed.Mesh-}
```
public static VertexElementNormal generateNormal(Mesh mesh)
```


Ağ tanımından normal verisi oluştur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

**Returns:**
[VertexElementNormal](../../com.aspose.threed/vertexelementnormal) - [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) instance with normal data.
### generateUV(Mesh mesh) {#generateUV-com.aspose.threed.Mesh-}
```
public static VertexElementUV generateUV(Mesh mesh)
```


Verilen giriş ağından UV verisi oluştur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Giriş mesh'i |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Generated UV data
### generateUV(Mesh mesh, VertexElementNormal normals) {#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-}
```
public static VertexElementUV generateUV(Mesh mesh, VertexElementNormal normals)
```


Verilen giriş ağından ve belirtilen normal verisinden UV verisi oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Giriş mesh'i |
| normals | [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) | Normal verisi |

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


Bir bütün düğümü tek bir dönüştürülmüş ağaca dönüştürün; normal/doku koordinatları gibi Vertex öğeleri henüz desteklenmiyor.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Birleştirilecek düğüm |

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


Bir bütün sahneyi tek bir dönüştürülmüş ağaca dönüştürün; normal/doku koordinatları gibi Vertex öğeleri henüz desteklenmiyor.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Birleştirilecek sahne |

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


Bir bütün düğümü tek bir dönüştürülmüş ağaca dönüştürün; normal/doku koordinatları gibi Vertex öğeleri henüz desteklenmiyor.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| düğümler | java.util.List<com.aspose.threed.Node> | Birleştirilecek düğümler |

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


Bu düğümdeki tüm geometrileri ölçeklendirin (Kontrol noktalarını ölçeklendirin, dönüşüm matrisini değil).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Ölçeklendirilecek düğüm |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | Ölçek faktörü **Örnek:** Aşağıdaki kod, sahnedeki tüm geometrileri 10 kat ölçeklendirmeyi gösterir. |

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


Bu sahnedeki tüm geometrileri ölçeklendirin (Kontrol noktalarını ölçeklendirin, dönüşüm matrisini değil).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Ölçeklendirilecek sahne |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | Ölçek faktörü **Örnek:** Aşağıdaki kod, sahnedeki tüm geometrileri 10 kat ölçeklendirmeyi gösterir. |

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


Ağacı [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) ile alt-ağaclara bölün. Her alt-ağac sadece bir materyal kullanacak. Orijinal ağacın değiştirilmeyecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

**Returns:**
com.aspose.threed.Mesh[] - Yeni bölünmüş ağlar **Örnek:** Aşağıdaki kod, bir kutuyu malzeme indekslerini kullanarak alt ağlara nasıl böleceğinizi gösterir.

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


Ağları [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) ile alt-ağlara bölün. Her alt-ağ yalnızca bir malzeme kullanacaktır. Bir düğümde ağ bölme işlemini gerçekleştirin **Örnek:** Aşağıdaki kod, bir kutuyu malzeme indekslerini kullanarak alt ağlara nasıl böleceğinizi gösterir.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes) {#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)
```


Ağları [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) ile alt-ağlara bölün. Her alt-ağ yalnızca bir malzeme kullanacaktır. Bir düğümde ağ bölme işlemini gerçekleştirin

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
|  | createChildNodes | boolean | Her alt-ağ için çocuk düğümler oluşturun. **Örnek:** Aşağıdaki kod, bir kutuyu malzeme indekslerini kullanarak alt ağlara nasıl böleceğinizi gösterir. |

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


Ağları [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) ile alt-ağlara bölün. Her alt-ağ yalnızca bir malzeme kullanacaktır. Bir düğümde ağ bölme işlemini gerçekleştirin

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
| createChildNodes | boolean | Her alt-ağ için çocuk düğümler oluşturun. |
|  | removeOldMesh | boolean | Bölme işleminden sonra eski ağı kaldırın, bu parametre false ise eski ve yeni ağlar birlikte var olacaktır. **Örnek:** Aşağıdaki kod, bir kutuyu malzeme indekslerini kullanarak alt ağlara nasıl böleceğinizi gösterir. |

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


Ağları [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) ile alt-ağlara bölün. Her alt-ağ yalnızca bir malzeme kullanacaktır. Sahnedeki tüm düğümlerde ağ bölme işlemini gerçekleştirin. **Örnek:** Aşağıdaki kod, bir kutuyu malzeme indekslerini kullanarak alt ağlara nasıl böleceğinizi gösterir.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh) {#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)
```


Ağları [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) ile alt-ağlara bölün. Her alt-ağ yalnızca bir malzeme kullanacaktır. Sahnedeki tüm düğümlerde ağ bölme işlemini gerçekleştirin. **Örnek:** Aşağıdaki kod, bir kutuyu malzeme indekslerini kullanarak alt ağlara nasıl böleceğinizi gösterir.

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
| Parametre | Tür | Açıklama |
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


Poligon tabanlı bir ağı tam üçgen ağına dönüştürün.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Orijinal üçgen olmayan ağ |

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


Tüm poligon tabanlı ağları tam üçgen ağına dönüştürün.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | scene | [Scene](../../com.aspose.threed/scene) | İşlenecek sahne **Örnek:** Aşağıdaki kod, bir sahnedeki tüm nesneleri tek bir ağda birleştirmenin nasıl yapılacağını gösterir. |

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


Bir poligonu üçgenlere dönüştürün, poligonun sırası `controlPoints` tarafından tanımlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Ağın kontrol noktaları |

**Returns:**
int[][] - Üçgenler kümesi **Örnek:** Aşağıdaki kod, bir sahnedeki tüm nesneleri tek bir ağda birleştirmenin nasıl yapılacağını gösterir.

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


Bir poligonu üçgenlere dönüştürün.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Ağın kontrol noktaları |
| polygon | int[] | Poligon yüzü |

**Returns:**
int[][] - Üçgenler kümesi **Örnek:** Aşağıdaki kod, bir sahnedeki tüm nesneleri tek bir ağda birleştirmenin nasıl yapılacağını gösterir.

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


Poligon tabanlı bir ağı üçgenlere dönüştürün.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Ağın kontrol noktaları |
| poligonlar | java.util.List<int[]> | Poligon yüzleri |

**Returns:**
int[][] - Üçgenler kümesi **Örnek:** Aşağıdaki kod, bir sahnedeki tüm nesneleri tek bir ağda birleştirmenin nasıl yapılacağını gösterir.

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


Poligon tabanlı bir ağı tam üçgen ağına dönüştürün.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Ağın kontrol noktaları |
| poligonlar | java.util.List<int[]> | Poligon yüzleri |
| generateNormals | boolean | Normal vektörleri oluştur |
| nor_out | [Vector3\[\]](../../com.aspose.threed/vector3) | Kontrol noktası başına oluşturulan normal |

**Returns:**
int[][] - Üçgenler kümesi **Örnek:** Aşağıdaki kod, bir sahnedeki tüm nesneleri tek bir ağda birleştirmenin nasıl yapılacağını gösterir.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

