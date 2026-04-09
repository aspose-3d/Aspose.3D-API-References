---
title: Shape
second_title: Aspose.3D for Java API Reference
description: Shape सेट ऑफ कंट्रोल पॉइंट्स पर विकृति का वर्णन करता है, जो Maya में क्लस्टर डिफॉर्मर के समान है।
type: docs
weight: 171
url: /hi/java/com.aspose.threed/shape/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)
```
public class Shape extends Geometry
```

Shape सेट ऑफ कंट्रोल पॉइंट्स पर विकृति का वर्णन करता है, जो Maya में क्लस्टर डिफॉर्मर के समान है। उदाहरण के लिए, हम एक निर्मित ज्योमेट्री में एक shape जोड़ सकते हैं। और shape और ज्योमेट्री के पास समान टोपोलॉजिकल जानकारी है लेकिन कंट्रोल पॉइंट्स की स्थिति अलग है। विभिन्न प्रभाव मात्रा के साथ, ज्योमेट्री एक विकृति प्रभाव उत्पन्न करती है।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Shape()](#Shape--) | एक नई [Shape](../../com.aspose.threed/shape) क्लास की इंस्टेंस को इनिशियलाइज़ करता है। |
| [Shape(String name)](#Shape-java.lang.String-) | एक नई [Shape](../../com.aspose.threed/shape) क्लास की इंस्टेंस को इनिशियलाइज़ करता है। |
## Methods

| Method | विवरण |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Gets all deformers with specified deformer types |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Adds an existing vertex element to current geometry |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Creates a vertex element with specified type and add it to the geometry. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Creates a vertex element with specified type and add it to the geometry. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | दिए गए टेक्सचर मैपिंग प्रकार के साथ एक [VertexElementUV](../../com.aspose.threed/vertexelementuv) बनाता है। |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | दिए गए टेक्सचर मैपिंग प्रकार के साथ एक [VertexElementUV](../../com.aspose.threed/vertexelementuv) बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [fromControlPoints(Vector3[] controlPoints)](#fromControlPoints-com.aspose.threed.Vector3...-) | डिफ़ॉल्ट इंडिसेज़ के साथ निर्दिष्ट कंट्रोल पॉइंट्स के साथ एक shape बनाएं। |
| [getBoundingBox()](#getBoundingBox--) | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कॉर्डिनेट सिस्टम में प्राप्त करता है। |
| [getCastShadows()](#getCastShadows--) | यह जियोमेट्री छाया डाल सकती है या नहीं प्राप्त करता है |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | सभी नियंत्रण बिंदु प्राप्त करता है |
| [getDeformers()](#getDeformers--) | इस जियोमेट्री से जुड़े सभी डिफॉर्मर प्राप्त करता है। |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | निर्दिष्ट प्रकार के साथ एक वर्टेक्स तत्व प्राप्त करता है |
| [getEntityRendererKey()](#getEntityRendererKey--) | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [getExcluded()](#getExcluded--) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में प्राप्त करता है। |
| [getIndices()](#getIndices--) | इंडिसेज़ प्राप्त करता है। |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getParentNode()](#getParentNode--) | पहला पैरेंट नोड प्राप्त करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [getParentNodes()](#getParentNodes--) | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जुड़ी हो सकती है |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getReceiveShadows()](#getReceiveShadows--) | यह जियोमेट्री छाया प्राप्त कर सकती है या नहीं प्राप्त करता है। |
| [getScene()](#getScene--) | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | दिए गए टेक्सचर मैपिंग प्रकार के साथ एक [VertexElementUV](../../com.aspose.threed/vertexelementuv) इंस्टेंस प्राप्त करता है |
| [getVertexElements()](#getVertexElements--) | सभी वर्टेक्स तत्व प्राप्त करता है |
| [getVisible()](#getVisible--) | जियोमेट्री दृश्यमान है या नहीं प्राप्त करता है |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | यह जियोमेट्री छाया डाल सकती है या नहीं सेट करता है |
| [setExcluded(boolean value)](#setExcluded-boolean-) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | पहला पैरेंट नोड सेट करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | यह जियोमेट्री छाया प्राप्त कर सकती है या नहीं सेट करता है। |
| [setVisible(boolean value)](#setVisible-boolean-) | जियोमेट्री दृश्यमान है या नहीं सेट करता है |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Shape() {#Shape--}
```
public Shape()
```


एक नई [Shape](../../com.aspose.threed/shape) क्लास की इंस्टेंस को इनिशियलाइज़ करता है।

### Shape(String name) {#Shape-java.lang.String-}
```
public Shape(String name)
```


एक नई [Shape](../../com.aspose.threed/shape) क्लास की इंस्टेंस को इनिशियलाइज़ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | नाम |

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


Gets all deformers with specified deformer types

**Returns:**
java.util.Collection<T> - Deformer संग्रह
### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Adds an existing vertex element to current geometry

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | जोड़ने के लिए वर्टेक्स तत्व |

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
### fromControlPoints(Vector3[] controlPoints) {#fromControlPoints-com.aspose.threed.Vector3...-}
```
public static Shape fromControlPoints(Vector3[] controlPoints)
```


डिफ़ॉल्ट इंडिसेज़ के साथ निर्दिष्ट कंट्रोल पॉइंट्स के साथ एक shape बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| controlPoints | [Vector3\[\]](../../com.aspose.threed/vector3) |  |

**Returns:**
[Shape](../../com.aspose.threed/shape)
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
### getIndices() {#getIndices--}
```
public List<Integer> getIndices()
```


इंडिसेज़ प्राप्त करता है।

**Returns:**
java.util.List<java.lang.Integer> - इंडिसेज़।
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

