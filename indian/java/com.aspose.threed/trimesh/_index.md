---
title: TriMesh
second_title: Aspose.3D for Java API Reference
description: एक TriMesh में कच्चा डेटा होता है जिसे GPU सीधे उपयोग कर सकता है।
type: docs
weight: 194
url: /hi/java/com.aspose.threed/trimesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
java.lang.Iterable
```
public class TriMesh extends Entity implements Iterable<Vertex>
```

एक TriMesh में कच्चा डेटा होता है जिसे GPU सीधे उपयोग कर सकता है। यह क्लास एक उपयोगिता है जो केवल प्रति-शिखर डेटा वाले मेष को बनाने में मदद करती है। **Example:** निम्नलिखित कोड दिखाता है कि कैसे कस्टम मेमोरी लेआउट के साथ एक TriMesh बनाया जाए, और इसे फ़ाइल में निर्यात किया जाए।

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
## Constructors

| Constructor | विवरण |
| --- | --- |
| [TriMesh(String name, VertexDeclaration declaration)](#TriMesh-java.lang.String-com.aspose.threed.VertexDeclaration-) | एक [TriMesh](../../com.aspose.threed/trimesh) का उदाहरण आरंभ करें |
## Methods

| Method | विवरण |
| --- | --- |
| [addTriangle(int a, int b, int c)](#addTriangle-int-int-int-) | एक नया त्रिभुज जोड़ें |
| [beginVertex()](#beginVertex--) | वर्टेक्स जोड़ना शुरू करें |
| [copyFrom(TriMesh input, VertexDeclaration vd)](#copyFrom-com.aspose.threed.TriMesh-com.aspose.threed.VertexDeclaration-) | इनपुट से नया वर्टेक्स लेआउट के साथ [TriMesh](../../com.aspose.threed/trimesh) कॉपी करें |
| [endVertex()](#endVertex--) | वर्टेक्स जोड़ना समाप्त करें |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [fromMesh(Mesh mesh)](#fromMesh-com.aspose.threed.Mesh-) | दिए गए मेष ऑब्जेक्ट से एक TriMesh बनाएं, वर्टेक्स घोषणा इनपुट मेष की संरचना पर आधारित है। |
| [fromMesh(Mesh mesh, boolean useFloat)](#fromMesh-com.aspose.threed.Mesh-boolean-) | दिए गए मेष ऑब्जेक्ट से एक TriMesh बनाएं, वर्टेक्स घोषणा इनपुट मेष की संरचना पर आधारित है। |
| [fromMesh(VertexDeclaration declaration, Mesh mesh)](#fromMesh-com.aspose.threed.VertexDeclaration-com.aspose.threed.Mesh-) | दिए गए मेष ऑब्जेक्ट से दिए गए वर्टेक्स लेआउट के साथ एक TriMesh बनाएं। |
| [fromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, boolean generateVertexMapping)](#fromRawData-com.aspose.threed.VertexDeclaration-byte---int---boolean-) | कच्चे डेटा से TriMesh बनाएं |
| [getBoundingBox()](#getBoundingBox--) | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कॉर्डिनेट सिस्टम में प्राप्त करता है। |
| [getCapacity()](#getCapacity--) | पूर्व-आवंटित वर्टेक्स की क्षमता। |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [getExcluded()](#getExcluded--) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में प्राप्त करता है। |
| [getIndicesCount()](#getIndicesCount--) | इस [TriMesh](../../com.aspose.threed/trimesh) में सूचकांकों की संख्या। |
| [getIntIndices()](#getIntIndices--) | सूचकांकों को 32-बिट पूर्णांक एरे में बदलें |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getParentNode()](#getParentNode--) | पहला पैरेंट नोड प्राप्त करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [getParentNodes()](#getParentNodes--) | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जुड़ी हो सकती है |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getScene()](#getScene--) | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [getShortIndices()](#getShortIndices--) | सूचकांकों को 16-बिट पूर्णांक एरे में बदलें |
| [getUnmergedVerticesCount()](#getUnmergedVerticesCount--) | उस अनमर्ज्ड वर्टेक्स की संख्या जो [beginVertex](../../com.aspose.threed/trimesh\#beginVertex) और [endVertex](../../com.aspose.threed/trimesh\#endVertex) द्वारा पास किए गए हैं। |
| [getVertexDeclaration()](#getVertexDeclaration--) | [TriMesh](../../com.aspose.threed/trimesh) का वर्टेक्स लेआउट। |
| [getVerticesCount()](#getVerticesCount--) | इस [TriMesh](../../com.aspose.threed/trimesh) में वर्टेक्स की संख्या। |
| [getVerticesSizeInBytes()](#getVerticesSizeInBytes--) | सभी वर्टेक्स का कुल आकार बाइट्स में |
| [hashCode()](#hashCode--) |  |
| [indicesToArray(int[][] result)](#indicesToArray-int-----) | सूचकांकों को 32-बिट पूर्णांक एरे में बदलें |
| [indicesToArray(short[][] result)](#indicesToArray-short-----) | सूचकांकों को 16-बिट पूर्णांक एरे में बदलें |
| [iterator()](#iterator--) | [Vertex](../../com.aspose.threed/vertex) को क्रमबद्ध करने के लिए इनेमरेटर प्राप्त करें |
| [loadVerticesFromBytes(byte[] verticesInBytes)](#loadVerticesFromBytes-byte---) | बाइट्स से वर्टेक्स लोड करें, बाइट्स की लंबाई वर्टेक्स आकार का पूर्णांक गुणज होना चाहिए। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readDouble(int idx, VertexField field)](#readDouble-int-com.aspose.threed.VertexField-) | डबल फ़ील्ड पढ़ें |
| [readFVector2(int idx, VertexField field)](#readFVector2-int-com.aspose.threed.VertexField-) | vector2 फ़ील्ड पढ़ें |
| [readFVector3(int idx, VertexField field)](#readFVector3-int-com.aspose.threed.VertexField-) | vector3 फ़ील्ड पढ़ें |
| [readFVector4(int idx, VertexField field)](#readFVector4-int-com.aspose.threed.VertexField-) | Read the vector4 field |
| [readFloat(int idx, VertexField field)](#readFloat-int-com.aspose.threed.VertexField-) | Read the float field |
| [readVector2(int idx, VertexField field)](#readVector2-int-com.aspose.threed.VertexField-) | vector2 फ़ील्ड पढ़ें |
| [readVector3(int idx, VertexField field)](#readVector3-int-com.aspose.threed.VertexField-) | vector3 फ़ील्ड पढ़ें |
| [readVector4(int idx, VertexField field)](#readVector4-int-com.aspose.threed.VertexField-) | Read the vector4 field |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setExcluded(boolean value)](#setExcluded-boolean-) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | पहला पैरेंट नोड सेट करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [toString()](#toString--) | Gets the string representation of [TriMesh](../../com.aspose.threed/trimesh) |
| [verticesToArray()](#verticesToArray--) | Convert the vertices data to byte array |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write16bIndicesTo(Stream stream)](#write16bIndicesTo-com.aspose.threed.Stream-) | Write the indices data as 16bit integer to the stream **Example:** |
| [write16bIndicesTo(OutputStream stream)](#write16bIndicesTo-java.io.OutputStream-) | Write the indices data as 16bit integer to the stream |
| [write32bIndicesTo(Stream stream)](#write32bIndicesTo-com.aspose.threed.Stream-) | Write the indices data as 32bit integer to the stream **Example:** |
| [write32bIndicesTo(OutputStream stream)](#write32bIndicesTo-java.io.OutputStream-) | Write the indices data as 32bit integer to the stream |
| [writeVerticesTo(Stream stream)](#writeVerticesTo-com.aspose.threed.Stream-) | Write vertices data to the specified stream |
| [writeVerticesTo(OutputStream stream)](#writeVerticesTo-java.io.OutputStream-) | Write vertices data to the specified stream |
### TriMesh(String name, VertexDeclaration declaration) {#TriMesh-java.lang.String-com.aspose.threed.VertexDeclaration-}
```
public TriMesh(String name, VertexDeclaration declaration)
```


एक [TriMesh](../../com.aspose.threed/trimesh) का उदाहरण आरंभ करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | The name of this TriMesh |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | The vertex's declaration |

### addTriangle(int a, int b, int c) {#addTriangle-int-int-int-}
```
public void addTriangle(int a, int b, int c)
```


एक नया त्रिभुज जोड़ें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| a | int | The index of first vertex |
| b | int | The index of second vertex |
| c | int | The index of third vertex |

### beginVertex() {#beginVertex--}
```
public Vertex beginVertex()
```


वर्टेक्स जोड़ना शुरू करें

**Returns:**
[Vertex](../../com.aspose.threed/vertex) - The reference of internal vertex object in type [Vertex](../../com.aspose.threed/vertex)
### copyFrom(TriMesh input, VertexDeclaration vd) {#copyFrom-com.aspose.threed.TriMesh-com.aspose.threed.VertexDeclaration-}
```
public static TriMesh copyFrom(TriMesh input, VertexDeclaration vd)
```


इनपुट से नया वर्टेक्स लेआउट के साथ [TriMesh](../../com.aspose.threed/trimesh) कॉपी करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| input | [TriMesh](../../com.aspose.threed/trimesh) | The input TriMesh for copying |
| vd | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | The new vertex declaration of the output TriMesh |

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


वर्टेक्स जोड़ना समाप्त करें

**Returns:**
int
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
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


प्रॉपर्टी को खोजता है। यह एक डायनामिक प्रॉपर्टी (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या नेटिव प्रॉपर्टी (नाम द्वारा पहचानी गई) हो सकती है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| propertyName | java.lang.String | प्रॉपर्टी नाम। |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromMesh(Mesh mesh) {#fromMesh-com.aspose.threed.Mesh-}
```
public static TriMesh fromMesh(Mesh mesh)
```


दिए गए मेष ऑब्जेक्ट से एक TriMesh बनाएं, वर्टेक्स घोषणा इनपुट मेष की संरचना पर आधारित है।

**Parameters:**
| Parameter | Type | विवरण |
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


दिए गए मेष ऑब्जेक्ट से एक TriMesh बनाएं, वर्टेक्स घोषणा इनपुट मेष की संरचना पर आधारित है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |
| useFloat | boolean | Use float type instead of double type for each vertex element component. |

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


दिए गए मेष ऑब्जेक्ट से दिए गए वर्टेक्स लेआउट के साथ एक TriMesh बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | Vertex's type definition, or memory layout |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Source mesh |

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


कच्चे डेटा से TriMesh बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| vd | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | Vertex declaration, must contains at least one field. |
| vertices | byte[] | इनपुट वर्टेक्स डेटा, वर्टेक्स की न्यूनतम लंबाई वर्टेक्स घोषणा के आकार के बराबर या उससे अधिक होनी चाहिए |
| सूचकांक | int[] | त्रिभुज सूचकांक |
| generateVertexMapping | boolean | प्रत्येक वर्टेक्स के लिए [Vertex](../../com.aspose.threed/vertex) उत्पन्न करें, जो केवल सीरियलाइज़ेशन/डिसीरियलाइज़ेशन के लिए आवश्यक नहीं है। |

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


वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कॉर्डिनेट सिस्टम में प्राप्त करता है।

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


पूर्व-आवंटित वर्टेक्स की क्षमता।

**Returns:**
int - पूर्व-आवंटित वर्टेक्स की क्षमता।
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


रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में प्राप्त करता है।

**Returns:**
बूलियन - निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में।
### getIndicesCount() {#getIndicesCount--}
```
public int getIndicesCount()
```


इस [TriMesh](../../com.aspose.threed/trimesh) में सूचकांकों की संख्या।

**Returns:**
int - इस [TriMesh](../../com.aspose.threed/trimesh) में सूचकांकों की संख्या
### getIntIndices() {#getIntIndices--}
```
public int[] getIntIndices()
```


सूचकांकों को 32-बिट पूर्णांक एरे में बदलें

**Returns:**
int[]
### getName() {#getName--}
```
public String getName()
```


नाम प्राप्त करता है।

**Returns:**
java.lang.String - नाम।
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


पहला पैरेंट नोड प्राप्त करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी।

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जुड़ी हो सकती है

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - सभी पैरेंट नोड्स, एक इकाई को ज्यामिति इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है।

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी नाम |

**Returns:**
java.lang.Object - मिली हुई प्रॉपर्टी का मान
### getScene() {#getScene--}
```
public Scene getScene()
```


उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShortIndices() {#getShortIndices--}
```
public short[] getShortIndices()
```


सूचकांकों को 16-बिट पूर्णांक एरे में बदलें

**Returns:**
short[]
### getUnmergedVerticesCount() {#getUnmergedVerticesCount--}
```
public int getUnmergedVerticesCount()
```


उस अनमर्ज्ड वर्टेक्स की संख्या जो [beginVertex](../../com.aspose.threed/trimesh\#beginVertex) और [endVertex](../../com.aspose.threed/trimesh\#endVertex) द्वारा पास किए गए हैं।

**Returns:**
int - [beginVertex](../../com.aspose.threed/trimesh\#beginVertex) और [endVertex](../../com.aspose.threed/trimesh\#endVertex) द्वारा पास किए गए अनमर्ज्ड वर्टेक्स की संख्या।
### getVertexDeclaration() {#getVertexDeclaration--}
```
public VertexDeclaration getVertexDeclaration()
```


[TriMesh](../../com.aspose.threed/trimesh) का वर्टेक्स लेआउट।

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - The vertex layout of the [TriMesh](../../com.aspose.threed/trimesh).
### getVerticesCount() {#getVerticesCount--}
```
public int getVerticesCount()
```


इस [TriMesh](../../com.aspose.threed/trimesh) में वर्टेक्स की संख्या।

**Returns:**
int - इस [TriMesh](../../com.aspose.threed/trimesh) में वर्टेक्स की संख्या
### getVerticesSizeInBytes() {#getVerticesSizeInBytes--}
```
public int getVerticesSizeInBytes()
```


सभी वर्टेक्स का कुल आकार बाइट्स में

**Returns:**
int - सभी वर्टेक्स का कुल आकार बाइट्स में
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


सूचकांकों को 32-बिट पूर्णांक एरे में बदलें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| परिणाम | int[][] |  |

### indicesToArray(short[][] result) {#indicesToArray-short-----}
```
public void indicesToArray(short[][] result)
```


सूचकांकों को 16-बिट पूर्णांक एरे में बदलें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| परिणाम | short[][] |  |

### iterator() {#iterator--}
```
public Iterator<Vertex> iterator()
```


[Vertex](../../com.aspose.threed/vertex) को क्रमबद्ध करने के लिए इनेमरेटर प्राप्त करें

**Returns:**
java.util.Iterator<com.aspose.threed.Vertex>
### loadVerticesFromBytes(byte[] verticesInBytes) {#loadVerticesFromBytes-byte---}
```
public void loadVerticesFromBytes(byte[] verticesInBytes)
```


बाइट्स से वर्टेक्स लोड करें, बाइट्स की लंबाई वर्टेक्स आकार का पूर्णांक गुणज होनी चाहिए। **उदाहरण:** निम्नलिखित कोड दिखाता है कि कैसे एक खाली TriMesh बनाया जाए और मैन्युअल रूप से कच्चे बाइट्स से वर्टेक्स लोड किए जाएँ।

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
| Parameter | Type | विवरण |
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


डबल फ़ील्ड पढ़ें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| idx | int | पढ़ने के लिए वर्टेक्स का सूचकांक |
| field | [VertexField](../../com.aspose.threed/vertexfield) | फ़्लोट/डबल संगत डेटा प्रकार वाला फ़ील्ड |

**Returns:**
double - निर्दिष्ट वर्टेक्स के फ़ील्ड का डबल मान
### readFVector2(int idx, VertexField field) {#readFVector2-int-com.aspose.threed.VertexField-}
```
public FVector2 readFVector2(int idx, VertexField field)
```


vector2 फ़ील्ड पढ़ें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| idx | int | पढ़ने के लिए वर्टेक्स का सूचकांक |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector2/FVector2 डेटा प्रकार वाला फ़ील्ड |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - FVector2 of specified vertex's field
### readFVector3(int idx, VertexField field) {#readFVector3-int-com.aspose.threed.VertexField-}
```
public FVector3 readFVector3(int idx, VertexField field)
```


vector3 फ़ील्ड पढ़ें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| idx | int | पढ़ने के लिए वर्टेक्स का सूचकांक |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector3/FVector3 डेटा प्रकार वाला फ़ील्ड |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### readFVector4(int idx, VertexField field) {#readFVector4-int-com.aspose.threed.VertexField-}
```
public FVector4 readFVector4(int idx, VertexField field)
```


Read the vector4 field

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| idx | int | पढ़ने के लिए वर्टेक्स का सूचकांक |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector4/FVector4 डेटा प्रकार वाला फ़ील्ड |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### readFloat(int idx, VertexField field) {#readFloat-int-com.aspose.threed.VertexField-}
```
public float readFloat(int idx, VertexField field)
```


Read the float field

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| idx | int | पढ़ने के लिए वर्टेक्स का सूचकांक |
| field | [VertexField](../../com.aspose.threed/vertexfield) | फ़्लोट/डबल संगत डेटा प्रकार वाला फ़ील्ड |

**Returns:**
float - निर्दिष्ट वर्टेक्स के फ़ील्ड का फ़्लोट मान
### readVector2(int idx, VertexField field) {#readVector2-int-com.aspose.threed.VertexField-}
```
public Vector2 readVector2(int idx, VertexField field)
```


vector2 फ़ील्ड पढ़ें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| idx | int | पढ़ने के लिए वर्टेक्स का सूचकांक |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector2/FVector2 डेटा प्रकार वाला फ़ील्ड |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Vector2 of specified vertex's field
### readVector3(int idx, VertexField field) {#readVector3-int-com.aspose.threed.VertexField-}
```
public Vector3 readVector3(int idx, VertexField field)
```


vector3 फ़ील्ड पढ़ें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| idx | int | पढ़ने के लिए वर्टेक्स का सूचकांक |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector3/FVector3 डेटा प्रकार वाला फ़ील्ड |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### readVector4(int idx, VertexField field) {#readVector4-int-com.aspose.threed.VertexField-}
```
public Vector4 readVector4(int idx, VertexField field)
```


Read the vector4 field

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| idx | int | पढ़ने के लिए वर्टेक्स का सूचकांक |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector4/FVector4 डेटा प्रकार वाला फ़ील्ड |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


डायनामिक प्रॉपर्टी को हटाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | कौन सी प्रॉपर्टी हटानी है |

**Returns:**
boolean - यदि प्रॉपर्टी सफलतापूर्वक हटाई गई हो तो true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | कौन सी प्रॉपर्टी हटानी है |

**Returns:**
boolean - यदि प्रॉपर्टी सफलतापूर्वक हटाई गई हो तो true
### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


नाम सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


पहला पैरेंट नोड सेट करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | नया मान |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


निर्दिष्ट प्रॉपर्टी का मान सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी नाम |
| मान | java.lang.Object | प्रॉपर्टी का मान |

### toString() {#toString--}
```
public String toString()
```


Gets the string representation of [TriMesh](../../com.aspose.threed/trimesh)

**Returns:**
java.lang.String - स्ट्रिंग प्रतिनिधित्व
### verticesToArray() {#verticesToArray--}
```
public byte[] verticesToArray()
```


Convert the vertices data to byte array

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

### write16bIndicesTo(Stream stream) {#write16bIndicesTo-com.aspose.threed.Stream-}
```
public void write16bIndicesTo(Stream stream)
```


Write the indices data as 16bit integer to the stream **Example:**

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

### write16bIndicesTo(OutputStream stream) {#write16bIndicesTo-java.io.OutputStream-}
```
public void write16bIndicesTo(OutputStream stream)
```


Write the indices data as 16bit integer to the stream

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | स्ट्रीम | java.io.OutputStream | **Example:** |

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


Write the indices data as 32bit integer to the stream **Example:**

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

### write32bIndicesTo(OutputStream stream) {#write32bIndicesTo-java.io.OutputStream-}
```
public void write32bIndicesTo(OutputStream stream)
```


Write the indices data as 32bit integer to the stream

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | स्ट्रीम | java.io.OutputStream | **Example:** |

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


Write vertices data to the specified stream

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | stream | [Stream](../../com.aspose.threed/stream) | The stream that the vertices data will be written to **Example:** |

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


Write vertices data to the specified stream

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | स्ट्रीम | java.io.OutputStream | The stream that the vertices data will be written to **Example:** |

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

