---
title: PolygonModifier
second_title: Referensi API Aspose.3D untuk Java
description: Utilitas untuk memodifikasi poligon
type: docs
weight: 134
url: /id/java/com.aspose.threed/polygonmodifier/
---

**Inheritance:**
java.lang.Object
```
public class PolygonModifier
```

Utilitas untuk memodifikasi poligon
## Metode

| Metode | Deskripsi |
| --- | --- |
| [applyTransform(Node node, Matrix4 transform)](#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-) | Terapkan matriks transformasi pada titik kontrol semua geometri |
| [buildTangentBinormal(Mesh mesh)](#buildTangentBinormal-com.aspose.threed.Mesh-) | Ini akan membuat tangent dan binormal pada mesh. Normal diperlukan, jika normal tidak ada pada mesh, maka data normal juga akan dibuat dari posisi. |
| [buildTangentBinormal(Scene scene)](#buildTangentBinormal-com.aspose.threed.Scene-) | Ini akan membuat tangent dan binormal pada semua mesh dalam adegan. Normal diperlukan, jika normal tidak ada pada mesh, maka data normal juga akan dibuat dari posisi. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateNormal(Mesh mesh)](#generateNormal-com.aspose.threed.Mesh-) | Hasilkan data normal dari definisi Mesh |
| [generateUV(Mesh mesh)](#generateUV-com.aspose.threed.Mesh-) | Hasilkan data UV dari mesh input yang diberikan |
| [generateUV(Mesh mesh, VertexElementNormal normals)](#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-) | Hasilkan data UV dari mesh input yang diberikan dan data normal yang ditentukan. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [mergeMesh(Node node)](#mergeMesh-com.aspose.threed.Node-) | Konversi seluruh node menjadi satu mesh yang ditransformasi. Elemen Vertex seperti normal/koordinat tekstur belum didukung. |
| [mergeMesh(Scene scene)](#mergeMesh-com.aspose.threed.Scene-) | Konversi seluruh scene menjadi satu mesh yang ditransformasi. Elemen Vertex seperti normal/koordinat tekstur belum didukung. |
| [mergeMesh(List<Node> nodes)](#mergeMesh-java.util.List-com.aspose.threed.Node--) | Konversi seluruh node menjadi satu mesh yang ditransformasi. Elemen Vertex seperti normal/koordinat tekstur belum didukung. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [scale(Node node, Vector3 scale)](#scale-com.aspose.threed.Node-com.aspose.threed.Vector3-) | Skala semua geometri (Skala titik kontrol, bukan matriks transformasi) pada node ini. |
| [scale(Scene scene, Vector3 scale)](#scale-com.aspose.threed.Scene-com.aspose.threed.Vector3-) | Skala semua geometri (Skala titik kontrol, bukan matriks transformasi) pada scene ini. |
| [splitMesh(Mesh mesh, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Mesh-com.aspose.threed.SplitMeshPolicy-) | Pisahkan mesh menjadi sub-meshes dengan [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Node node, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-) | Pisahkan mesh menjadi sub-meshes dengan [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-) | Pisahkan mesh menjadi sub-meshes dengan [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-boolean-) | Pisahkan mesh menjadi sub-meshes dengan [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Scene scene, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-) | Pisahkan mesh menjadi sub-meshes dengan [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-) | Pisahkan mesh menjadi sub-meshes dengan [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [toString()](#toString--) |  |
| [triangulate(Mesh mesh)](#triangulate-com.aspose.threed.Mesh-) | Konversi mesh berbasis poligon menjadi mesh segitiga penuh. |
| [triangulate(Scene scene)](#triangulate-com.aspose.threed.Scene-) | Konversi semua mesh berbasis poligon menjadi mesh segitiga penuh. |
| [triangulate(List<Vector4> controlPoints)](#triangulate-java.util.List-com.aspose.threed.Vector4--) | Konversi poligon menjadi segitiga, urutan poligon didefinisikan oleh `controlPoints`. |
| [triangulate(List<Vector4> controlPoints, int[] polygon)](#triangulate-java.util.List-com.aspose.threed.Vector4--int---) | Konversi poligon menjadi segitiga. |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----) | Konversi mesh berbasis poligon menjadi segitiga. |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons, boolean generateNormals, Vector3[][] nor_out)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----boolean-com.aspose.threed.Vector3-----) | Konversi mesh berbasis poligon menjadi mesh segitiga penuh. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### applyTransform(Node node, Matrix4 transform) {#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-}
```
public static void applyTransform(Node node, Matrix4 transform)
```


Terapkan matriks transformasi pada titik kontrol semua geometri

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Geometri node mana yang akan diterapkan dengan transformasi yang diberikan. |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | Matriks transformasi yang akan diterapkan pada titik kontrol. |

### buildTangentBinormal(Mesh mesh) {#buildTangentBinormal-com.aspose.threed.Mesh-}
```
public static void buildTangentBinormal(Mesh mesh)
```


Ini akan membuat tangent dan binormal pada mesh. Normal diperlukan; jika normal tidak ada pada mesh, data normal juga akan dibuat dari posisi. UV juga diperlukan, sebuah pengecualian akan dilempar jika tidak ada UV yang ditemukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

### buildTangentBinormal(Scene scene) {#buildTangentBinormal-com.aspose.threed.Scene-}
```
public static void buildTangentBinormal(Scene scene)
```


Ini akan membuat tangent dan binormal pada semua mesh dalam scene. Normal diperlukan; jika normal tidak ada pada mesh, data normal juga akan dibuat dari posisi. UV juga diperlukan, mesh akan diabaikan jika tidak ada UV yang didefinisikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateNormal(Mesh mesh) {#generateNormal-com.aspose.threed.Mesh-}
```
public static VertexElementNormal generateNormal(Mesh mesh)
```


Hasilkan data normal dari definisi Mesh

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

**Returns:**
[VertexElementNormal](../../com.aspose.threed/vertexelementnormal) - [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) instance with normal data.
### generateUV(Mesh mesh) {#generateUV-com.aspose.threed.Mesh-}
```
public static VertexElementUV generateUV(Mesh mesh)
```


Hasilkan data UV dari mesh input yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Mesh input |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Generated UV data
### generateUV(Mesh mesh, VertexElementNormal normals) {#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-}
```
public static VertexElementUV generateUV(Mesh mesh, VertexElementNormal normals)
```


Hasilkan data UV dari mesh input yang diberikan dan data normal yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Mesh input |
| normals | [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) | Data normal |

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


Konversi seluruh node menjadi satu mesh yang ditransformasi. Elemen Vertex seperti normal/koordinat tekstur belum didukung.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Node yang akan digabungkan |

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


Konversi seluruh scene menjadi satu mesh yang ditransformasi. Elemen Vertex seperti normal/koordinat tekstur belum didukung.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Scene yang akan digabungkan |

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


Konversi seluruh node menjadi satu mesh yang ditransformasi. Elemen Vertex seperti normal/koordinat tekstur belum didukung.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | java.util.List<com.aspose.threed.Node> | Node yang akan digabungkan |

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


Skala semua geometri (Skala titik kontrol, bukan matriks transformasi) pada node ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Node yang akan diskalakan |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | Faktor skala **Example:** Kode berikut menunjukkan cara menskalakan semua geometri dalam scene sebesar 10 kali. |

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


Skala semua geometri (Skala titik kontrol, bukan matriks transformasi) pada scene ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Scene yang akan diskalakan |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | Faktor skala **Example:** Kode berikut menunjukkan cara menskalakan semua geometri dalam scene sebesar 10 kali. |

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


Pisahkan mesh menjadi sub-meshes dengan [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Setiap sub-mesh hanya akan menggunakan satu material. Mesh asli tidak akan diubah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

**Returns:**
com.aspose.threed.Mesh[] - Mesh terpisah baru **Contoh:** Kode berikut menunjukkan cara memecah sebuah kotak menjadi sub-mesh menggunakan indeks material.

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


Pisahkan mesh menjadi sub-mesh dengan [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Setiap sub-mesh akan menggunakan hanya satu material. Lakukan pemisahan mesh pada sebuah node **Contoh:** Kode berikut menunjukkan cara memecah sebuah kotak menjadi sub-mesh menggunakan indeks material.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes) {#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)
```


Pisahkan mesh menjadi sub-mesh dengan [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Setiap sub-mesh akan menggunakan hanya satu material. Lakukan pemisahan mesh pada sebuah node

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
|  | createChildNodes | boolean | Buat node anak untuk setiap sub-mesh. **Contoh:** Kode berikut menunjukkan cara memecah sebuah kotak menjadi sub-mesh menggunakan indeks material. |

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


Pisahkan mesh menjadi sub-mesh dengan [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Setiap sub-mesh akan menggunakan hanya satu material. Lakukan pemisahan mesh pada sebuah node

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
| createChildNodes | boolean | Buat node anak untuk setiap sub-mesh. |
|  | removeOldMesh | boolean | Hapus mesh lama setelah pemisahan, jika parameter ini false, mesh lama dan baru akan eksis bersamaan. **Contoh:** Kode berikut menunjukkan cara memecah sebuah kotak menjadi sub-mesh menggunakan indeks material. |

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


Pisahkan mesh menjadi sub-mesh dengan [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Setiap sub-mesh akan menggunakan hanya satu material. Lakukan pemisahan mesh pada semua node dalam adegan. **Contoh:** Kode berikut menunjukkan cara memecah sebuah kotak menjadi sub-mesh menggunakan indeks material.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh) {#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)
```


Pisahkan mesh menjadi sub-mesh dengan [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Setiap sub-mesh akan menggunakan hanya satu material. Lakukan pemisahan mesh pada semua node dalam adegan. **Contoh:** Kode berikut menunjukkan cara memecah sebuah kotak menjadi sub-mesh menggunakan indeks material.

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
| Parameter | Tipe | Deskripsi |
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


Konversi mesh berbasis poligon menjadi mesh segitiga penuh.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Mesh asli yang bukan segitiga |

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


Konversi semua mesh berbasis poligon menjadi mesh segitiga penuh.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | scene | [Scene](../../com.aspose.threed/scene) | Adegan yang akan diproses **Contoh:** Kode berikut menunjukkan cara menggabungkan semua objek dari sebuah adegan menjadi satu mesh. |

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


Konversi poligon menjadi segitiga, urutan poligon didefinisikan oleh `controlPoints`.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Titik kontrol dari mesh |

**Returns:**
int[][] - Sekumpulan segitiga **Contoh:** Kode berikut menunjukkan cara menggabungkan semua objek dari sebuah adegan menjadi satu mesh.

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


Konversi poligon menjadi segitiga.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Titik kontrol dari mesh |
| polygon | int[] | Wajah poligon |

**Returns:**
int[][] - Sekumpulan segitiga **Contoh:** Kode berikut menunjukkan cara menggabungkan semua objek dari sebuah adegan menjadi satu mesh.

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


Konversi mesh berbasis poligon menjadi segitiga.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Titik kontrol dari mesh |
| polygons | java.util.List<int[]> | Wajah poligon |

**Returns:**
int[][] - Sekumpulan segitiga **Contoh:** Kode berikut menunjukkan cara menggabungkan semua objek dari sebuah adegan menjadi satu mesh.

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


Konversi mesh berbasis poligon menjadi mesh segitiga penuh.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Titik kontrol dari mesh |
| polygons | java.util.List<int[]> | Wajah poligon |
| generateNormals | boolean | Hasilkan normal |
| nor_out | [Vector3\[\]](../../com.aspose.threed/vector3) | Normal per-titik kontrol yang dihasilkan |

**Returns:**
int[][] - Sekumpulan segitiga **Contoh:** Kode berikut menunjukkan cara menggabungkan semua objek dari sebuah adegan menjadi satu mesh.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

