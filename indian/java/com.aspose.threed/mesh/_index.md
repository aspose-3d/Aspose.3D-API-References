---
title: Mesh
second_title: Aspose.3D for Java API Reference
description: एक मेष कई n-पक्षीय बहुभुजों से बना होता है।
type: docs
weight: 102
url: /hi/java/com.aspose.threed/mesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)

**All Implemented Interfaces:**
java.lang.Iterable, [com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class Mesh extends Geometry implements Iterable<int[]>, IMeshConvertible
```

A mesh is made of many n-sided polygons. **Example:** To add a polygon in mesh:

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

Travel through all polygons in mesh:

```
Mesh mesh = new Mesh();
  for(int[] polygon : mesh)
  {
      //deal with polygon
  }
```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Mesh()](#Mesh--) | Initializes a new instance of the [Mesh](../../com.aspose.threed/mesh) class. |
| [Mesh(String name)](#Mesh-java.lang.String-) | Initializes a new instance of the [Mesh](../../com.aspose.threed/mesh) class. |
## Methods

| Method | विवरण |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Gets all deformers with specified deformer types |
| [addControlPoint(double x, double y, double z)](#addControlPoint-double-double-double-) | Add a new control point to the mesh, this is more efficient. |
| [addControlPoint(double x, double y, double z, double w)](#addControlPoint-double-double-double-double-) | Add a new control point to the mesh, this is more efficient. |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Adds an existing vertex element to current geometry |
| [clone()](#clone--) |  |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Creates a vertex element with specified type and add it to the geometry. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Creates a vertex element with specified type and add it to the geometry. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | दिए गए टेक्सचर मैपिंग प्रकार के साथ एक [VertexElementUV](../../com.aspose.threed/vertexelementuv) बनाता है। |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | दिए गए टेक्सचर मैपिंग प्रकार के साथ एक [VertexElementUV](../../com.aspose.threed/vertexelementuv) बनाता है। |
| [createPolygon(int v1, int v2, int v3)](#createPolygon-int-int-int-) | 3 शीर्ष (त्रिभुज) के साथ एक बहुभुज बनाएं |
| [createPolygon(int v1, int v2, int v3, int v4)](#createPolygon-int-int-int-int-) | 4 शीर्ष (चतुर्भुज) के साथ एक बहुभुज बनाएं |
| [createPolygon(int[] indices)](#createPolygon-int---) | `indices` में परिभाषित सभी शीर्षों के साथ एक नया बहुभुज बनाता है। |
| [createPolygon(int[] indices, int offset, int length)](#createPolygon-int---int-int-) | `indices` में परिभाषित सभी शीर्षों के साथ एक नया बहुभुज बनाता है। |
| [difference(Mesh a, Mesh b)](#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | दो मेषों का अंतर गणना करें |
| [doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)](#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-) | दो मेषों पर बूलियन ऑपरेशन करें |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getBoundingBox()](#getBoundingBox--) | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कॉर्डिनेट सिस्टम में प्राप्त करता है। |
| [getCastShadows()](#getCastShadows--) | यह जियोमेट्री छाया डाल सकती है या नहीं प्राप्त करता है |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | सभी नियंत्रण बिंदु प्राप्त करता है |
| [getDeformers()](#getDeformers--) | इस जियोमेट्री से जुड़े सभी डिफॉर्मर प्राप्त करता है। |
| [getEdges()](#getEdges--) | मेश के किनारे प्राप्त करता है। |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | निर्दिष्ट प्रकार के साथ एक वर्टेक्स तत्व प्राप्त करता है |
| [getEntityRendererKey()](#getEntityRendererKey--) | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [getExcluded()](#getExcluded--) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में प्राप्त करता है। |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getParentNode()](#getParentNode--) | पहला पैरेंट नोड प्राप्त करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [getParentNodes()](#getParentNodes--) | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जुड़ी हो सकती है |
| [getPolygonCount()](#getPolygonCount--) | बहुभुजों की संख्या प्राप्त करता है |
| [getPolygonSize(int index)](#getPolygonSize-int-) | निर्दिष्ट बहुभुज का वर्टेक्स गणना प्राप्त करता है। |
| [getPolygons()](#getPolygons--) | मेश की बहुभुज परिभाषा प्राप्त करता है |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getReceiveShadows()](#getReceiveShadows--) | यह जियोमेट्री छाया प्राप्त कर सकती है या नहीं प्राप्त करता है। |
| [getScene()](#getScene--) | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | दिए गए टेक्सचर मैपिंग प्रकार के साथ एक [VertexElementUV](../../com.aspose.threed/vertexelementuv) इंस्टेंस प्राप्त करता है |
| [getVertexElements()](#getVertexElements--) | सभी वर्टेक्स तत्व प्राप्त करता है |
| [getVisible()](#getVisible--) | जियोमेट्री दृश्यमान है या नहीं प्राप्त करता है |
| [hashCode()](#hashCode--) |  |
| [intersect(Mesh a, Mesh b)](#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | दो मेषों का प्रतिच्छेदन गणना करें |
| [isManifold()](#isManifold--) | जाँचें कि वर्तमान मेष एक मैनिफोल्ड मेष है या नहीं। |
| [iterator()](#iterator--) | प्रत्येक आंतरिक बहुभुज के लिए एन्यूमेरेटर प्राप्त करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [optimize(boolean vertexElements)](#optimize-boolean-) | डुप्लिकेट नियंत्रण बिंदुओं को हटाकर मेष की मेमोरी उपयोग को अनुकूलित करें |
| [optimize(boolean vertexElements, float toleranceControlPoint)](#optimize-boolean-float-) | डुप्लिकेट नियंत्रण बिंदुओं को हटाकर मेष की मेमोरी उपयोग को अनुकूलित करें |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)](#optimize-boolean-float-float-) | डुप्लिकेट नियंत्रण बिंदुओं को हटाकर मेष की मेमोरी उपयोग को अनुकूलित करें |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)](#optimize-boolean-float-float-float-) | डुप्लिकेट नियंत्रण बिंदुओं को हटाकर मेष की मेमोरी उपयोग को अनुकूलित करें |
| [optimize2(boolean vertexElements)](#optimize2-boolean-) | डुप्लिकेट नियंत्रण बिंदुओं को हटाकर मेष की मेमोरी उपयोग को अनुकूलित करें |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | यह जियोमेट्री छाया डाल सकती है या नहीं सेट करता है |
| [setExcluded(boolean value)](#setExcluded-boolean-) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | पहला पैरेंट नोड सेट करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | यह जियोमेट्री छाया प्राप्त कर सकती है या नहीं सेट करता है। |
| [setVisible(boolean value)](#setVisible-boolean-) | जियोमेट्री दृश्यमान है या नहीं सेट करता है |
| [toMesh()](#toMesh--) | वर्तमान इकाई से Mesh इंस्टेंस प्राप्त करता है। |
| [toString()](#toString--) |  |
| [triangulate()](#triangulate--) | त्रिकोणीय mesh लौटाएँ |
| [union(Mesh a, Mesh b)](#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | दो meshes का संघ गणना करें |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mesh() {#Mesh--}
```
public Mesh()
```


Initializes a new instance of the [Mesh](../../com.aspose.threed/mesh) class.

### Mesh(String name) {#Mesh-java.lang.String-}
```
public Mesh(String name)
```


Initializes a new instance of the [Mesh](../../com.aspose.threed/mesh) class.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | नाम। |

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


Gets all deformers with specified deformer types

**Returns:**
java.util.Collection<T> - Deformer संग्रह
### addControlPoint(double x, double y, double z) {#addControlPoint-double-double-double-}
```
public void addControlPoint(double x, double y, double z)
```


Add a new control point to the mesh, this is more efficient.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| x | double | नियंत्रण बिंदु का x घटक |
| y | double | नियंत्रण बिंदु का y घटक |
| z | double | नियंत्रण बिंदु का z घटक |

### addControlPoint(double x, double y, double z, double w) {#addControlPoint-double-double-double-double-}
```
public void addControlPoint(double x, double y, double z, double w)
```


Add a new control point to the mesh, this is more efficient.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| x | double | नियंत्रण बिंदु का x घटक |
| y | double | नियंत्रण बिंदु का y घटक |
| z | double | नियंत्रण बिंदु का z घटक |
| w | double | नियंत्रण बिंदु का w घटक |

### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Adds an existing vertex element to current geometry

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | जोड़ने के लिए वर्टेक्स तत्व |

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


Creates a vertex element with specified type and add it to the geometry.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | वर्टेक्स तत्व प्रकार |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode) {#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElement createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)
```


Creates a vertex element with specified type and add it to the geometry.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | वर्टेक्स तत्व प्रकार |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | डिफ़ॉल्ट मैपिंग मोड |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | डिफ़ॉल्ट रेफ़रेंस मोड |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElementUV(TextureMapping uvMapping) {#createElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping)
```


दिए गए टेक्सचर मैपिंग प्रकार के साथ एक [VertexElementUV](../../com.aspose.threed/vertexelementuv) बनाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | कौन सा टेक्सचर मैपिंग प्रकार बनाना है |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode) {#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)
```


दिए गए टेक्सचर मैपिंग प्रकार के साथ एक [VertexElementUV](../../com.aspose.threed/vertexelementuv) बनाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | कौन सा टेक्सचर मैपिंग प्रकार बनाना है |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | डिफ़ॉल्ट मैपिंग मोड |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | डिफ़ॉल्ट रेफ़रेंस मोड |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createPolygon(int v1, int v2, int v3) {#createPolygon-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3)
```


3 शीर्ष (त्रिभुज) के साथ एक बहुभुज बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| v1 | int | पहले वर्टेक्स का सूचकांक |
| v2 | int | दूसरे वर्टेक्स का सूचकांक |
|  | v3 | int | तीसरे वर्टेक्स का सूचकांक **Example:** निम्नलिखित कोड दर्शाता है कि नियंत्रण बिंदु के सूचकांकों के साथ नया बहुभुज कैसे बनाया जाए। |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2);
``` |

### createPolygon(int v1, int v2, int v3, int v4) {#createPolygon-int-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3, int v4)
```


4 शीर्ष (चतुर्भुज) के साथ एक बहुभुज बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| v1 | int | पहले वर्टेक्स का सूचकांक |
| v2 | int | दूसरे वर्टेक्स का सूचकांक |
| v3 | int | तीसरे वर्टेक्स का सूचकांक |
|  | v4 | int | चौथे वर्टेक्स का सूचकांक **Example:** निम्नलिखित कोड दर्शाता है कि नियंत्रण बिंदु के सूचकांकों के साथ नया बहुभुज कैसे बनाया जाए। |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2, 3);
``` |

### createPolygon(int[] indices) {#createPolygon-int---}
```
public void createPolygon(int[] indices)
```


`indices` में परिभाषित सभी वर्टेक्स के साथ नया बहुभुज बनाता है। बहुभुज को वर्टेक्स दर वर्टेक्स बनाने के लिए, कृपया [PolygonBuilder](../../com.aspose.threed/polygonbuilder) का उपयोग करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | सूचकांक | int[] | बहुभुज सूचकांकों की सरणी, प्रत्येक सूचकांक एक नियंत्रण बिंदु की ओर इंगित करता है जो बहुभुज बनाता है। **Example:** |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### createPolygon(int[] indices, int offset, int length) {#createPolygon-int---int-int-}
```
public void createPolygon(int[] indices, int offset, int length)
```


`indices` में परिभाषित सभी वर्टेक्स के साथ नया बहुभुज बनाता है। बहुभुज को वर्टेक्स दर वर्टेक्स बनाने के लिए, कृपया [PolygonBuilder](../../com.aspose.threed/polygonbuilder) का उपयोग करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| सूचकांक | int[] | बहुभुज सूचकांकों की सरणी, प्रत्येक सूचकांक एक नियंत्रण बिंदु की ओर इंगित करता है जो बहुभुज बनाता है। |
| ऑफ़सेट | int | पहले बहुभुज सूचकांक का ऑफसेट |
|  | लंबाई | int | सूचकांकों की लंबाई **Example:** निम्नलिखित कोड दिखाता है कि नियंत्रण बिंदु के सूचकांकों के साथ नया बहुभुज कैसे बनाया जाए। |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### difference(Mesh a, Mesh b) {#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh difference(Mesh a, Mesh b)
```


दो मेषों का अंतर गणना करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | पहला मेष |
| b | [Mesh](../../com.aspose.threed/mesh) | दूसरा मेष |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB) {#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-}
```
public static Mesh doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)
```


दो मेषों पर बूलियन ऑपरेशन करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| op | [BooleanOperation](../../com.aspose.threed/booleanoperation) | बूलियन ऑपरेशन प्रकार। |
| a | [Mesh](../../com.aspose.threed/mesh) | ऑपरेट करने के लिए पहला मेष। |
| transformA | [Matrix4](../../com.aspose.threed/matrix4) | पहले मेष का ट्रांसफ़ॉर्मेशन मैट्रिक्स |
| b | [Mesh](../../com.aspose.threed/mesh) | ऑपरेट करने के लिए दूसरा मेष |
| transformB | [Matrix4](../../com.aspose.threed/matrix4) | दूसरे मेष का ट्रांसफ़ॉर्मेशन मैट्रिक्स |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The result mesh **Example:** The following code shows how to calculate the union of two meshes:
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
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


यह जियोमेट्री छाया डाल सकती है या नहीं प्राप्त करता है

**Returns:**
boolean - क्या यह ज्यामिति छाया डाल सकती है
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


सभी नियंत्रण बिंदु प्राप्त करता है

**Returns:**
java.util.List<com.aspose.threed.Vector4> - सभी नियंत्रण बिंदु
### getDeformers() {#getDeformers--}
```
public List<Deformer> getDeformers()
```


इस जियोमेट्री से जुड़े सभी डिफॉर्मर प्राप्त करता है।

**Returns:**
java.util.List<com.aspose.threed.Deformer> - इस ज्यामिति से जुड़े सभी डिफॉर्मर।
### getEdges() {#getEdges--}
```
public List<Integer> getEdges()
```


मेश के किनारे प्राप्त करता है। किनारा मेश में वैकल्पिक है, इसलिए यह खाली हो सकता है।

**Returns:**
java.util.List<java.lang.Integer> - मेश के किनारे। किनारा मेश में वैकल्पिक है, इसलिए यह खाली हो सकता है।
### getElement(VertexElementType type) {#getElement-com.aspose.threed.VertexElementType-}
```
public VertexElement getElement(VertexElementType type)
```


निर्दिष्ट प्रकार के साथ एक वर्टेक्स तत्व प्राप्त करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | कौन सा वर्टेक्स तत्व प्रकार खोजें |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - [VertexElement](../../com.aspose.threed/vertexelement) instance if found, otherwise null will be returned.
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
### getPolygonCount() {#getPolygonCount--}
```
public int getPolygonCount()
```


बहुभुजों की संख्या प्राप्त करता है

**Returns:**
int - बहुभुजों की गिनती **Example:** निम्नलिखित कोड दिखाता है कि मेश के बहुभुजों की संख्या कैसे प्राप्त करें।

```
Mesh mesh = (new Sphere()).toMesh();
      System.out.println("Mesh's polygon count = " + mesh.getPolygonCount());
```
### getPolygonSize(int index) {#getPolygonSize-int-}
```
public int getPolygonSize(int index)
```


निर्दिष्ट बहुभुज का वर्टेक्स गणना प्राप्त करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| सूचकांक | int | सूचकांक। |

**Returns:**
int - बहुभुज का आकार।
### getPolygons() {#getPolygons--}
```
public List<int[]> getPolygons()
```


मेश की बहुभुज परिभाषा प्राप्त करता है

**Returns:**
java.util.List<int[]> - मेष की बहुभुज परिभाषा
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
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


यह जियोमेट्री छाया प्राप्त कर सकती है या नहीं प्राप्त करता है।

**Returns:**
boolean - क्या यह ज्यामिति छाया प्राप्त कर सकती है।
### getScene() {#getScene--}
```
public Scene getScene()
```


उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getVertexElementOfUV(TextureMapping textureMapping) {#getVertexElementOfUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV getVertexElementOfUV(TextureMapping textureMapping)
```


दिए गए टेक्सचर मैपिंग प्रकार के साथ एक [VertexElementUV](../../com.aspose.threed/vertexelementuv) इंस्टेंस प्राप्त करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) |  |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - VertexElementUV with the texture mapping type
### getVertexElements() {#getVertexElements--}
```
public List<VertexElement> getVertexElements()
```


सभी वर्टेक्स तत्व प्राप्त करता है

**Returns:**
java.util.List<com.aspose.threed.VertexElement> - सभी शीर्ष बिंदु तत्व
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


जियोमेट्री दृश्यमान है या नहीं प्राप्त करता है

**Returns:**
boolean - यदि ज्यामिति दृश्यमान है
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


दो मेषों का प्रतिच्छेदन गणना करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | पहला मेष |
| b | [Mesh](../../com.aspose.threed/mesh) | दूसरा मेष |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### isManifold() {#isManifold--}
```
public boolean isManifold()
```


जाँचें कि वर्तमान मेष एक manifold मेष है या नहीं। यह फ़ंक्शन manifold गणना परिणाम को कैश नहीं करेगा।

**Returns:**
boolean - true यदि मेष एक manifold मेष है।
### iterator() {#iterator--}
```
public Iterator<int[]> iterator()
```


प्रत्येक आंतरिक बहुभुज के लिए एन्यूमेरेटर प्राप्त करता है।

**Returns:**
java.util.Iterator<int[]> - एनीमरेटर।
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


डुप्लिकेट नियंत्रण बिंदुओं को हटाकर मेष की मेमोरी उपयोग को अनुकूलित करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| vertexElements | boolean | डुप्लिकेटेड शीर्ष बिंदु तत्व डेटा को अनुकूलित करें |

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


डुप्लिकेट नियंत्रण बिंदुओं को हटाकर मेष की मेमोरी उपयोग को अनुकूलित करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| vertexElements | boolean | डुप्लिकेटेड शीर्ष बिंदु तत्व डेटा को अनुकूलित करें |
| toleranceControlPoint | फ़्लोट | नियंत्रण बिंदु के लिए सहनशीलता, डिफ़ॉल्ट मान 1e-9 है |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal) {#optimize-boolean-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)
```


डुप्लिकेट नियंत्रण बिंदुओं को हटाकर मेष की मेमोरी उपयोग को अनुकूलित करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| vertexElements | boolean | डुप्लिकेटेड शीर्ष बिंदु तत्व डेटा को अनुकूलित करें |
| toleranceControlPoint | फ़्लोट | नियंत्रण बिंदु के लिए सहनशीलता, डिफ़ॉल्ट मान 1e-9 है |
| toleranceNormal | फ़्लोट | नॉर्मल/टैन्जेंट/बाइनॉर्मल के लिए सहनशीलता, डिफ़ॉल्ट मान 1e-9 है |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV) {#optimize-boolean-float-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)
```


डुप्लिकेट नियंत्रण बिंदुओं को हटाकर मेष की मेमोरी उपयोग को अनुकूलित करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| vertexElements | boolean | डुप्लिकेटेड शीर्ष बिंदु तत्व डेटा को अनुकूलित करें |
| toleranceControlPoint | फ़्लोट | नियंत्रण बिंदु के लिए सहनशीलता, डिफ़ॉल्ट मान 1e-9 है |
| toleranceNormal | फ़्लोट | नॉर्मल/टैन्जेंट/बाइनॉर्मल के लिए सहनशीलता, डिफ़ॉल्ट मान 1e-9 है |
| toleranceUV | फ़्लोट | UV के लिए सहनशीलता, डिफ़ॉल्ट मान 1e-9 है |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize2(boolean vertexElements) {#optimize2-boolean-}
```
public Mesh optimize2(boolean vertexElements)
```


डुप्लिकेट नियंत्रण बिंदुओं को हटाकर मेष की मेमोरी उपयोग को अनुकूलित करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| vertexElements | boolean | डुप्लिकेटेड शीर्ष बिंदु तत्व डेटा को अनुकूलित करें |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
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
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


यह जियोमेट्री छाया डाल सकती है या नहीं सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

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

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


यह जियोमेट्री छाया प्राप्त कर सकती है या नहीं सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


जियोमेट्री दृश्यमान है या नहीं सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


वर्तमान इकाई से Mesh इंस्टेंस प्राप्त करता है।

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


त्रिकोणीय mesh लौटाएँ

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


दो meshes का संघ गणना करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | पहला मेष |
| b | [Mesh](../../com.aspose.threed/mesh) | दूसरा मेष |

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

