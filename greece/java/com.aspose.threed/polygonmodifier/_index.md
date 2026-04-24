---
title: PolygonModifier
second_title: Aspose.3D for Java API Reference
description: Utilities to modify polygons
type: docs
weight: 134
url: /el/java/com.aspose.threed/polygonmodifier/
---

**Inheritance:**
java.lang.Object
```
public class PolygonModifier
```

Utilities to modify polygons
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [applyTransform(Node node, Matrix4 transform)](#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-) | Εφαρμόστε τον πίνακα μετασχηματισμού στα σημεία ελέγχου όλων των γεωμετριών |
| [buildTangentBinormal(Mesh mesh)](#buildTangentBinormal-com.aspose.threed.Mesh-) | Αυτό θα δημιουργήσει εφαπτόμενο και διπλό διάνυσμα στο πλέγμα. Το Normal είναι απαραίτητο· εάν το Normal δεν υπάρχει στο πλέγμα, θα δημιουργηθεί επίσης το Normal data από τη θέση. |
| [buildTangentBinormal(Scene scene)](#buildTangentBinormal-com.aspose.threed.Scene-) | Αυτό θα δημιουργήσει εφαπτόμενο και διπλό διάνυσμα σε όλα τα πλέγματα της σκηνής. Το Normal είναι απαραίτητο· εάν το Normal δεν υπάρχει στο πλέγμα, θα δημιουργηθεί επίσης το Normal data από τη θέση. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateNormal(Mesh mesh)](#generateNormal-com.aspose.threed.Mesh-) | Δημιουργήστε δεδομένα κανονικού από τον ορισμό του Mesh |
| [generateUV(Mesh mesh)](#generateUV-com.aspose.threed.Mesh-) | Δημιουργήστε δεδομένα UV από το δοσμένο πλέγμα εισόδου |
| [generateUV(Mesh mesh, VertexElementNormal normals)](#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-) | Δημιουργήστε δεδομένα UV από το δοσμένο πλέγμα εισόδου και τα καθορισμένα δεδομένα κανονικού. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [mergeMesh(Node node)](#mergeMesh-com.aspose.threed.Node-) | Μετατρέψτε ολόκληρο έναν κόμβο σε ένα ενιαίο μετασχηματισμένο πλέγμα. Τα στοιχεία Vertex όπως οι συντεταγμένες κανονικής/υφής δεν υποστηρίζονται ακόμη. |
| [mergeMesh(Scene scene)](#mergeMesh-com.aspose.threed.Scene-) | Μετατρέψτε ολόκληρη τη σκηνή σε ένα ενιαίο μετασχηματισμένο πλέγμα. Τα στοιχεία Vertex όπως οι συντεταγμένες κανονικής/υφής δεν υποστηρίζονται ακόμη. |
| [mergeMesh(List<Node> nodes)](#mergeMesh-java.util.List-com.aspose.threed.Node--) | Μετατρέψτε ολόκληρο έναν κόμβο σε ένα ενιαίο μετασχηματισμένο πλέγμα. Τα στοιχεία Vertex όπως οι συντεταγμένες κανονικής/υφής δεν υποστηρίζονται ακόμη. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [scale(Node node, Vector3 scale)](#scale-com.aspose.threed.Node-com.aspose.threed.Vector3-) | Κλιμακώστε όλα τα γεωμετρικά στοιχεία (Κλιμακώστε τα σημεία ελέγχου, όχι τον πίνακα μετασχηματισμού) σε αυτόν τον κόμβο. |
| [scale(Scene scene, Vector3 scale)](#scale-com.aspose.threed.Scene-com.aspose.threed.Vector3-) | Κλιμακώστε όλα τα γεωμετρικά στοιχεία (Κλιμακώστε τα σημεία ελέγχου, όχι τον πίνακα μετασχηματισμού) σε αυτή τη σκηνή. |
| [splitMesh(Mesh mesh, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Mesh-com.aspose.threed.SplitMeshPolicy-) | Διαιρέστε το πλέγμα σε υπο-πλέγματα με το [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Node node, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-) | Διαιρέστε το πλέγμα σε υπο-πλέγματα με το [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-) | Διαιρέστε το πλέγμα σε υπο-πλέγματα με το [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-boolean-) | Διαιρέστε το πλέγμα σε υπο-πλέγματα με το [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Scene scene, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-) | Διαιρέστε το πλέγμα σε υπο-πλέγματα με το [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-) | Διαιρέστε το πλέγμα σε υπο-πλέγματα με το [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [toString()](#toString--) |  |
| [triangulate(Mesh mesh)](#triangulate-com.aspose.threed.Mesh-) | Μετατρέψτε ένα πλέγμα βασισμένο σε πολύγωνα σε πλήρες τριγωνικό πλέγμα. |
| [triangulate(Scene scene)](#triangulate-com.aspose.threed.Scene-) | Μετατρέψτε όλα τα πλέγματα βασισμένα σε πολύγωνα σε πλήρη τριγωνικά πλέγματα. |
| [triangulate(List<Vector4> controlPoints)](#triangulate-java.util.List-com.aspose.threed.Vector4--) | Μετατρέψτε ένα πολύγωνο σε τρίγωνα, η σειρά του πολυγώνου ορίζεται από τα `controlPoints`. |
| [triangulate(List<Vector4> controlPoints, int[] polygon)](#triangulate-java.util.List-com.aspose.threed.Vector4--int---) | Μετατρέψτε ένα πολύγωνο σε τρίγωνα. |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----) | Μετατρέψτε ένα πλέγμα βασισμένο σε πολύγωνα σε τρίγωνα. |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons, boolean generateNormals, Vector3[][] nor_out)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----boolean-com.aspose.threed.Vector3-----) | Μετατρέψτε ένα πλέγμα βασισμένο σε πολύγωνα σε πλήρες τριγωνικό πλέγμα. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### applyTransform(Node node, Matrix4 transform) {#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-}
```
public static void applyTransform(Node node, Matrix4 transform)
```


Εφαρμόστε τον πίνακα μετασχηματισμού στα σημεία ελέγχου όλων των γεωμετριών

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Ποια γεωμετρία του κόμβου θα εφαρμοστεί με τον δεδομένο μετασχηματισμό. |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | Ο πίνακας μετασχηματισμού που θα εφαρμοστεί στα σημεία ελέγχου. |

### buildTangentBinormal(Mesh mesh) {#buildTangentBinormal-com.aspose.threed.Mesh-}
```
public static void buildTangentBinormal(Mesh mesh)
```


Αυτό θα δημιουργήσει tangent και binormal στο πλέγμα. Το Normal απαιτείται· εάν δεν υπάρχει στο πλέγμα, θα δημιουργηθεί επίσης το δεδομένο Normal από τη θέση. Το UV επίσης απαιτείται· θα προκληθεί εξαίρεση εάν δεν βρεθεί UV.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

### buildTangentBinormal(Scene scene) {#buildTangentBinormal-com.aspose.threed.Scene-}
```
public static void buildTangentBinormal(Scene scene)
```


Αυτό θα δημιουργήσει tangent και binormal σε όλα τα πλέγματα της σκηνής. Το Normal απαιτείται· εάν δεν υπάρχει στο πλέγμα, θα δημιουργηθεί επίσης το δεδομένο Normal από τη θέση. Το UV επίσης απαιτείται· το πλέγμα θα αγνοηθεί εάν δεν οριστεί UV.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateNormal(Mesh mesh) {#generateNormal-com.aspose.threed.Mesh-}
```
public static VertexElementNormal generateNormal(Mesh mesh)
```


Δημιουργήστε δεδομένα κανονικού από τον ορισμό του Mesh

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

**Returns:**
[VertexElementNormal](../../com.aspose.threed/vertexelementnormal) - [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) instance with normal data.
### generateUV(Mesh mesh) {#generateUV-com.aspose.threed.Mesh-}
```
public static VertexElementUV generateUV(Mesh mesh)
```


Δημιουργήστε δεδομένα UV από το δοσμένο πλέγμα εισόδου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Το εισερχόμενο πλέγμα |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Generated UV data
### generateUV(Mesh mesh, VertexElementNormal normals) {#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-}
```
public static VertexElementUV generateUV(Mesh mesh, VertexElementNormal normals)
```


Δημιουργήστε δεδομένα UV από το δοσμένο πλέγμα εισόδου και τα καθορισμένα δεδομένα κανονικού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Το εισερχόμενο πλέγμα |
| normals | [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) | Τα δεδομένα Normal |

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


Μετατρέψτε ολόκληρο έναν κόμβο σε ένα ενιαίο μετασχηματισμένο πλέγμα. Τα στοιχεία Vertex όπως οι συντεταγμένες κανονικής/υφής δεν υποστηρίζονται ακόμη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Ο κόμβος προς συγχώνευση |

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


Μετατρέψτε ολόκληρη τη σκηνή σε ένα ενιαίο μετασχηματισμένο πλέγμα. Τα στοιχεία Vertex όπως οι συντεταγμένες κανονικής/υφής δεν υποστηρίζονται ακόμη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Η σκηνή προς συγχώνευση |

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


Μετατρέψτε ολόκληρο έναν κόμβο σε ένα ενιαίο μετασχηματισμένο πλέγμα. Τα στοιχεία Vertex όπως οι συντεταγμένες κανονικής/υφής δεν υποστηρίζονται ακόμη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κόμβοι | java.util.List<com.aspose.threed.Node> | Οι κόμβοι προς συγχώνευση |

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


Κλιμακώστε όλα τα γεωμετρικά στοιχεία (Κλιμακώστε τα σημεία ελέγχου, όχι τον πίνακα μετασχηματισμού) σε αυτόν τον κόμβο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Ο κόμβος προς κλιμάκωση |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | Ο συντελεστής κλίμακας **Example:** Ο παρακάτω κώδικας δείχνει πώς να κλιμακώσετε όλα τα γεωμετρικά στοιχεία στη σκηνή κατά 10 φορές. |

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


Κλιμακώστε όλα τα γεωμετρικά στοιχεία (Κλιμακώστε τα σημεία ελέγχου, όχι τον πίνακα μετασχηματισμού) σε αυτή τη σκηνή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Η σκηνή προς κλιμάκωση |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | Ο συντελεστής κλίμακας **Example:** Ο παρακάτω κώδικας δείχνει πώς να κλιμακώσετε όλα τα γεωμετρικά στοιχεία στη σκηνή κατά 10 φορές. |

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


Διαιρέστε το πλέγμα σε υπο-πλέγματα με το [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Κάθε υπο-πλέγμα θα χρησιμοποιεί μόνο ένα υλικό. Το αρχικό πλέγμα δεν θα αλλάξει.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

**Returns:**
com.aspose.threed.Mesh[] - Νέα χωρισμένα πλέγματα **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να χωρίσετε ένα κουτί σε υπο-πλέγματα χρησιμοποιώντας δείκτες υλικού.

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


Διαχωρίστε το πλέγμα σε υπο-πλέγματα με το [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Κάθε υπο-πλέγμα θα χρησιμοποιεί μόνο ένα υλικό. Εκτελέστε το διαχωρισμό του πλέγματος σε έναν κόμβο **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να χωρίσετε ένα κουτί σε υπο-πλέγματα χρησιμοποιώντας δείκτες υλικού.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes) {#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)
```


Διαχωρίστε το πλέγμα σε υπο-πλέγματα με το [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Κάθε υπο-πλέγμα θα χρησιμοποιεί μόνο ένα υλικό. Εκτελέστε το διαχωρισμό του πλέγματος σε έναν κόμβο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
|  | createChildNodes | boolean | Δημιουργήστε κόμβους-παιδιά για κάθε υπο-πλέγμα. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να χωρίσετε ένα κουτί σε υπο-πλέγματα χρησιμοποιώντας δείκτες υλικού. |

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


Διαχωρίστε το πλέγμα σε υπο-πλέγματα με το [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Κάθε υπο-πλέγμα θα χρησιμοποιεί μόνο ένα υλικό. Εκτελέστε το διαχωρισμό του πλέγματος σε έναν κόμβο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
| createChildNodes | boolean | Δημιουργήστε κόμβους-παιδιά για κάθε υπο-πλέγμα. |
|  | removeOldMesh | boolean | Αφαιρέστε το παλιό πλέγμα μετά το διαχωρισμό· εάν αυτή η παράμετρος είναι ψευδής, τα παλιά και τα νέα πλέγματα θα συνυπάρχουν. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να χωρίσετε ένα κουτί σε υπο-πλέγματα χρησιμοποιώντας δείκτες υλικού. |

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


Διαχωρίστε το πλέγμα σε υπο-πλέγματα με το [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Κάθε υπο-πλέγμα θα χρησιμοποιεί μόνο ένα υλικό. Εκτελέστε το διαχωρισμό του πλέγματος σε όλους τους κόμβους της σκηνής. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να χωρίσετε ένα κουτί σε υπο-πλέγματα χρησιμοποιώντας δείκτες υλικού.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh) {#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)
```


Διαχωρίστε το πλέγμα σε υπο-πλέγματα με το [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Κάθε υπο-πλέγμα θα χρησιμοποιεί μόνο ένα υλικό. Εκτελέστε το διαχωρισμό του πλέγματος σε όλους τους κόμβους της σκηνής. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να χωρίσετε ένα κουτί σε υπο-πλέγματα χρησιμοποιώντας δείκτες υλικού.

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
| Παράμετρος | Τύπος | Περιγραφή |
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


Μετατρέψτε ένα πλέγμα βασισμένο σε πολύγωνα σε πλήρες τριγωνικό πλέγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Το αρχικό μη-τριγωνικό πλέγμα |

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


Μετατρέψτε όλα τα πλέγματα βασισμένα σε πολύγωνα σε πλήρη τριγωνικά πλέγματα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | scene | [Scene](../../com.aspose.threed/scene) | Η σκηνή προς επεξεργασία **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να συγχωνεύσετε όλα τα αντικείμενα από μια σκηνή σε ένα ενιαίο πλέγμα. |

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


Μετατρέψτε ένα πολύγωνο σε τρίγωνα, η σειρά του πολυγώνου ορίζεται από τα `controlPoints`.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Σημεία ελέγχου του πλέγματος |

**Returns:**
int[][] - Ένα σύνολο τριγώνων **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να συγχωνεύσετε όλα τα αντικείμενα από μια σκηνή σε ένα ενιαίο πλέγμα.

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


Μετατρέψτε ένα πολύγωνο σε τρίγωνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Σημεία ελέγχου του πλέγματος |
| πολύγωνο | int[] | Πλευρά πολύγωνου |

**Returns:**
int[][] - Ένα σύνολο τριγώνων **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να συγχωνεύσετε όλα τα αντικείμενα από μια σκηνή σε ένα ενιαίο πλέγμα.

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


Μετατρέψτε ένα πλέγμα βασισμένο σε πολύγωνα σε τρίγωνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Σημεία ελέγχου του πλέγματος |
| πολύγωνα | java.util.List<int[]> | Πλευρές πολύγωνου |

**Returns:**
int[][] - Ένα σύνολο τριγώνων **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να συγχωνεύσετε όλα τα αντικείμενα από μια σκηνή σε ένα ενιαίο πλέγμα.

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


Μετατρέψτε ένα πλέγμα βασισμένο σε πολύγωνα σε πλήρες τριγωνικό πλέγμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Σημεία ελέγχου του πλέγματος |
| πολύγωνα | java.util.List<int[]> | Πλευρές πολύγωνου |
| generateNormals | boolean | Δημιουργία κανονικών |
| nor_out | [Vector3\[\]](../../com.aspose.threed/vector3) | Δημιουργήθηκε κανονικό ανά σημείο ελέγχου |

**Returns:**
int[][] - Ένα σύνολο τριγώνων **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να συγχωνεύσετε όλα τα αντικείμενα από μια σκηνή σε ένα ενιαίο πλέγμα.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

