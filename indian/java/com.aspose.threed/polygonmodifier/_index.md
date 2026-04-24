---
title: PolygonModifier
second_title: Aspose.3D for Java API Reference
description: पॉलीगॉन को संशोधित करने के यूटिलिटीज़
type: docs
weight: 134
url: /hi/java/com.aspose.threed/polygonmodifier/
---

**Inheritance:**
java.lang.Object
```
public class PolygonModifier
```

पॉलीगॉन को संशोधित करने के यूटिलिटीज़
## Methods

| Method | विवरण |
| --- | --- |
| [applyTransform(Node node, Matrix4 transform)](#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-) | सभी ज्यामितियों के कंट्रोल पॉइंट्स पर ट्रांसफ़ॉर्म मैट्रिक्स लागू करें |
| [buildTangentBinormal(Mesh mesh)](#buildTangentBinormal-com.aspose.threed.Mesh-) | यह मेष पर टैन्जेंट और बिनॉर्म बनाएगा। सामान्य (Normal) आवश्यक है, यदि मेष पर सामान्य मौजूद नहीं है, तो यह स्थिति से सामान्य डेटा भी बनाएगा। |
| [buildTangentBinormal(Scene scene)](#buildTangentBinormal-com.aspose.threed.Scene-) | यह सीन के सभी मेषों पर टैन्जेंट और बिनॉर्म बनाएगा। सामान्य आवश्यक है, यदि मेष पर सामान्य मौजूद नहीं है, तो यह स्थिति से सामान्य डेटा भी बनाएगा। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateNormal(Mesh mesh)](#generateNormal-com.aspose.threed.Mesh-) | मेश परिभाषा से सामान्य डेटा उत्पन्न करें |
| [generateUV(Mesh mesh)](#generateUV-com.aspose.threed.Mesh-) | दिए गए इनपुट मेष से UV डेटा उत्पन्न करें |
| [generateUV(Mesh mesh, VertexElementNormal normals)](#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-) | दिए गए इनपुट मेष और निर्दिष्ट सामान्य डेटा से UV डेटा उत्पन्न करें। |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [mergeMesh(Node node)](#mergeMesh-com.aspose.threed.Node-) | पूरे नोड को एकल परिवर्तित मेष में बदलें। Vertex तत्व जैसे normal/texture coordinates अभी समर्थित नहीं हैं। |
| [mergeMesh(Scene scene)](#mergeMesh-com.aspose.threed.Scene-) | पूरे दृश्य को एकल परिवर्तित मेष में बदलें। Vertex तत्व जैसे normal/texture coordinates अभी समर्थित नहीं हैं। |
| [mergeMesh(List<Node> nodes)](#mergeMesh-java.util.List-com.aspose.threed.Node--) | पूरे नोड को एकल परिवर्तित मेष में बदलें। Vertex तत्व जैसे normal/texture coordinates अभी समर्थित नहीं हैं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [scale(Node node, Vector3 scale)](#scale-com.aspose.threed.Node-com.aspose.threed.Vector3-) | इस नोड में सभी ज्यामितियों को स्केल करें (ट्रांसफ़ॉर्मेशन मैट्रिक्स नहीं, कंट्रोल पॉइंट्स को स्केल करें)। |
| [scale(Scene scene, Vector3 scale)](#scale-com.aspose.threed.Scene-com.aspose.threed.Vector3-) | इस दृश्य में सभी ज्यामितियों को स्केल करें (ट्रांसफ़ॉर्मेशन मैट्रिक्स नहीं, कंट्रोल पॉइंट्स को स्केल करें)। |
| [splitMesh(Mesh mesh, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Mesh-com.aspose.threed.SplitMeshPolicy-) | मेश को [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) द्वारा उप-मेश में विभाजित करें। |
| [splitMesh(Node node, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-) | मेश को [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) द्वारा उप-मेश में विभाजित करें। |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-) | मेश को [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) द्वारा उप-मेश में विभाजित करें। |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-boolean-) | मेश को [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) द्वारा उप-मेश में विभाजित करें। |
| [splitMesh(Scene scene, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-) | मेश को [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) द्वारा उप-मेश में विभाजित करें। |
| [splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-) | मेश को [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) द्वारा उप-मेश में विभाजित करें। |
| [toString()](#toString--) |  |
| [triangulate(Mesh mesh)](#triangulate-com.aspose.threed.Mesh-) | बहुभुज-आधारित मेष को पूर्ण त्रिकोणीय मेष में बदलें। |
| [triangulate(Scene scene)](#triangulate-com.aspose.threed.Scene-) | सभी बहुभुज-आधारित मेषों को पूर्ण त्रिकोणीय मेष में बदलें। |
| [triangulate(List<Vector4> controlPoints)](#triangulate-java.util.List-com.aspose.threed.Vector4--) | बहुभुज को त्रिकोणों में बदलें, बहुभुज का क्रम `controlPoints` द्वारा परिभाषित होता है। |
| [triangulate(List<Vector4> controlPoints, int[] polygon)](#triangulate-java.util.List-com.aspose.threed.Vector4--int---) | बहुभुज को त्रिकोणों में बदलें। |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----) | बहुभुज-आधारित मेष को त्रिकोणों में बदलें। |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons, boolean generateNormals, Vector3[][] nor_out)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----boolean-com.aspose.threed.Vector3-----) | बहुभुज-आधारित मेष को पूर्ण त्रिकोणीय मेष में बदलें। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### applyTransform(Node node, Matrix4 transform) {#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-}
```
public static void applyTransform(Node node, Matrix4 transform)
```


सभी ज्यामितियों के कंट्रोल पॉइंट्स पर ट्रांसफ़ॉर्म मैट्रिक्स लागू करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | किस नोड की ज्यामितियों पर दिया गया ट्रांसफ़ॉर्म लागू होगा। |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | ट्रांसफ़ॉर्मेशन मैट्रिक्स जो कंट्रोल पॉइंट्स पर लागू होगा। |

### buildTangentBinormal(Mesh mesh) {#buildTangentBinormal-com.aspose.threed.Mesh-}
```
public static void buildTangentBinormal(Mesh mesh)
```


यह मेष पर टैंजेंट और बाइनॉर्म बनाता है। Normal आवश्यक है; यदि मेष में Normal मौजूद नहीं है, तो यह स्थिति से Normal डेटा भी बनाता है। UV भी आवश्यक है, यदि कोई UV नहीं मिला तो अपवाद उत्पन्न होगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

### buildTangentBinormal(Scene scene) {#buildTangentBinormal-com.aspose.threed.Scene-}
```
public static void buildTangentBinormal(Scene scene)
```


यह दृश्य के सभी मेषों पर टैंजेंट और बाइनॉर्म बनाता है। Normal आवश्यक है; यदि मेष में Normal मौजूद नहीं है, तो यह स्थिति से Normal डेटा भी बनाता है। UV भी आवश्यक है; यदि कोई UV परिभाषित नहीं है तो मेष को अनदेखा किया जाएगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateNormal(Mesh mesh) {#generateNormal-com.aspose.threed.Mesh-}
```
public static VertexElementNormal generateNormal(Mesh mesh)
```


मेश परिभाषा से सामान्य डेटा उत्पन्न करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

**Returns:**
[VertexElementNormal](../../com.aspose.threed/vertexelementnormal) - [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) instance with normal data.
### generateUV(Mesh mesh) {#generateUV-com.aspose.threed.Mesh-}
```
public static VertexElementUV generateUV(Mesh mesh)
```


दिए गए इनपुट मेष से UV डेटा उत्पन्न करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | इनपुट मेष |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Generated UV data
### generateUV(Mesh mesh, VertexElementNormal normals) {#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-}
```
public static VertexElementUV generateUV(Mesh mesh, VertexElementNormal normals)
```


दिए गए इनपुट मेष और निर्दिष्ट सामान्य डेटा से UV डेटा उत्पन्न करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | इनपुट मेष |
| normals | [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) | Normal डेटा |

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


पूरे नोड को एकल परिवर्तित मेष में बदलें। Vertex तत्व जैसे normal/texture coordinates अभी समर्थित नहीं हैं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | मर्ज करने के लिए नोड |

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


पूरे दृश्य को एकल परिवर्तित मेष में बदलें। Vertex तत्व जैसे normal/texture coordinates अभी समर्थित नहीं हैं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | मर्ज करने के लिए दृश्य |

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


पूरे नोड को एकल परिवर्तित मेष में बदलें। Vertex तत्व जैसे normal/texture coordinates अभी समर्थित नहीं हैं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| नोड्स | java.util.List<com.aspose.threed.Node> | मर्ज करने के नोड्स |

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


इस नोड में सभी ज्यामितियों को स्केल करें (ट्रांसफ़ॉर्मेशन मैट्रिक्स नहीं, कंट्रोल पॉइंट्स को स्केल करें)।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | स्केल करने के लिए नोड |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | स्केल फ़ैक्टर **Example:** निम्नलिखित कोड दर्शाता है कि दृश्य में सभी ज्यामितियों को 10 गुना कैसे स्केल किया जाए। |

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


इस दृश्य में सभी ज्यामितियों को स्केल करें (ट्रांसफ़ॉर्मेशन मैट्रिक्स नहीं, कंट्रोल पॉइंट्स को स्केल करें)।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | स्केल करने के लिए दृश्य |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | स्केल फ़ैक्टर **Example:** निम्नलिखित कोड दर्शाता है कि दृश्य में सभी ज्यामितियों को 10 गुना कैसे स्केल किया जाए। |

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


मेश को [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) द्वारा उप-मेश में विभाजित करें। प्रत्येक उप-मेश केवल एक सामग्री का उपयोग करेगा। मूल मेष नहीं बदलेगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

**Returns:**
com.aspose.threed.Mesh[] - नई विभाजित मेष **उदाहरण:** निम्नलिखित कोड दिखाता है कि सामग्री सूचकांकों का उपयोग करके बॉक्स को उप‑मेश में कैसे विभाजित किया जाए।

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


सबस्ट्रक्चर को [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) द्वारा विभाजित करें। प्रत्येक सब‑मेश केवल एक सामग्री का उपयोग करेगा। एक नोड पर मेष विभाजन करें **उदाहरण:** निम्नलिखित कोड दिखाता है कि सामग्री सूचकांकों का उपयोग करके बॉक्स को उप‑मेश में कैसे विभाजित किया जाए।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes) {#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)
```


सबस्ट्रक्चर को [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) द्वारा विभाजित करें। प्रत्येक सब‑मेश केवल एक सामग्री का उपयोग करेगा। एक नोड पर मेष विभाजन करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
|  | createChildNodes | boolean | प्रत्येक सब‑मेश के लिए चाइल्ड नोड बनाएं। **उदाहरण:** निम्नलिखित कोड दिखाता है कि सामग्री सूचकांकों का उपयोग करके बॉक्स को उप‑मेश में कैसे विभाजित किया जाए। |

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


सबस्ट्रक्चर को [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) द्वारा विभाजित करें। प्रत्येक सब‑मेश केवल एक सामग्री का उपयोग करेगा। एक नोड पर मेष विभाजन करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
| createChildNodes | boolean | प्रत्येक सब‑मेश के लिए चाइल्ड नोड बनाएं। |
|  | removeOldMesh | boolean | विभाजन के बाद पुराना मेष हटाएँ, यदि यह पैरामीटर false है, तो पुराना और नया मेष दोनों मौजूद रहेंगे। **उदाहरण:** निम्नलिखित कोड दिखाता है कि सामग्री सूचकांकों का उपयोग करके बॉक्स को उप‑मेश में कैसे विभाजित किया जाए। |

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


सबस्ट्रक्चर को [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) द्वारा विभाजित करें। प्रत्येक सब‑मेश केवल एक सामग्री का उपयोग करेगा। दृश्य के सभी नोड्स पर मेष विभाजन करें **उदाहरण:** निम्नलिखित कोड दिखाता है कि सामग्री सूचकांकों का उपयोग करके बॉक्स को उप‑मेश में कैसे विभाजित किया जाए।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh) {#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)
```


सबस्ट्रक्चर को [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) द्वारा विभाजित करें। प्रत्येक सब‑मेश केवल एक सामग्री का उपयोग करेगा। दृश्य के सभी नोड्स पर मेष विभाजन करें **उदाहरण:** निम्नलिखित कोड दिखाता है कि सामग्री सूचकांकों का उपयोग करके बॉक्स को उप‑मेश में कैसे विभाजित किया जाए।

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
| Parameter | Type | विवरण |
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


बहुभुज-आधारित मेष को पूर्ण त्रिकोणीय मेष में बदलें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | मूल गैर‑त्रिभुज मेष |

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


सभी बहुभुज-आधारित मेषों को पूर्ण त्रिकोणीय मेष में बदलें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | scene | [Scene](../../com.aspose.threed/scene) | प्रक्रिया करने के लिए दृश्य **उदाहरण:** निम्नलिखित कोड दिखाता है कि कैसे एक दृश्य के सभी ऑब्जेक्ट्स को एकल मेष में मिलाया जाए। |

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


बहुभुज को त्रिकोणों में बदलें, बहुभुज का क्रम `controlPoints` द्वारा परिभाषित होता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | मेश के नियंत्रण बिंदु |

**Returns:**
int[][] - त्रिभुजों का एक सेट **उदाहरण:** निम्नलिखित कोड दिखाता है कि कैसे एक दृश्य के सभी ऑब्जेक्ट्स को एकल मेष में मिलाया जाए।

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


बहुभुज को त्रिकोणों में बदलें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | मेश के नियंत्रण बिंदु |
| polygon | int[] | बहुभुज फेस |

**Returns:**
int[][] - त्रिभुजों का एक सेट **उदाहरण:** निम्नलिखित कोड दिखाता है कि कैसे एक दृश्य के सभी ऑब्जेक्ट्स को एकल मेष में मिलाया जाए।

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


बहुभुज-आधारित मेष को त्रिकोणों में बदलें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | मेश के नियंत्रण बिंदु |
| polygons | java.util.List<int[]> | बहुभुज चेहरे |

**Returns:**
int[][] - त्रिभुजों का एक सेट **उदाहरण:** निम्नलिखित कोड दिखाता है कि कैसे एक दृश्य के सभी ऑब्जेक्ट्स को एकल मेष में मिलाया जाए।

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


बहुभुज-आधारित मेष को पूर्ण त्रिकोणीय मेष में बदलें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | मेश के नियंत्रण बिंदु |
| polygons | java.util.List<int[]> | बहुभुज चेहरे |
| generateNormals | boolean | सामान्य वेक्टर उत्पन्न करें |
| nor_out | [Vector3\[\]](../../com.aspose.threed/vector3) | प्रति‑नियंत्रण बिंदु सामान्य उत्पन्न किया गया |

**Returns:**
int[][] - त्रिभुजों का एक सेट **उदाहरण:** निम्नलिखित कोड दिखाता है कि कैसे एक दृश्य के सभी ऑब्जेक्ट्स को एकल मेष में मिलाया जाए।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

