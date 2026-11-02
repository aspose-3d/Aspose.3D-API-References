---
title: "Torus"
second_title: "Aspose.3D for Java API रेफ़रेंस"
description: "पैरामीटरयुक्त टॉरस।"
type: docs
weight: 189
url: /hi/java/com.aspose.threed/torus/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Torus extends Primitive
```

पैरामीटरयुक्त टॉरस।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [Torus()](#Torus--) | नया instance [Torus](../../com.aspose.threed/torus) क्लास का इनिशियलाइज़ करता है। |
| [Torus(double radius, double tube)](#Torus-double-double-) | नया instance [Torus](../../com.aspose.threed/torus) क्लास का इनिशियलाइज़ करता है। |
| [Torus(double radius, double tube, double arc)](#Torus-double-double-double-) | नया instance [Torus](../../com.aspose.threed/torus) क्लास का इनिशियलाइज़ करता है। |
| [Torus(String name, double radius, double tube, int radialSegments, int tubularSegments, double arc)](#Torus-java.lang.String-double-double-int-int-double-) | नया instance [Torus](../../com.aspose.threed/torus) क्लास का इनिशियलाइज़ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getArc()](#getArc--) | Arc प्राप्त करता है। |
| [getBoundingBox()](#getBoundingBox--) | वर्तमान इकाई का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में प्राप्त करता है। |
| [getCastShadows()](#getCastShadows--) | यह जाँचता है कि यह ज्यामिति छाया डाल सकती है या नहीं। |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | रेंडरर में पंजीकृत इकाई रेंडरर की कुंजी प्राप्त करता है |
| [getExcluded()](#getExcluded--) | निर्यात के दौरान इस इकाई को बाहर रखने का चयन प्राप्त करता है। |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getParentNode()](#getParentNode--) | पहला पैरेंट नोड प्राप्त करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह इकाई अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [getParentNodes()](#getParentNodes--) | सभी पैरेंट नोड्स प्राप्त करता है, एक इकाई ज्योमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जुड़ी हो सकती है |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getRadialSegments()](#getRadialSegments--) | रेडियल सेगमेंट्स प्राप्त करता है। |
| [getRadius()](#getRadius--) | Torus का त्रिज्या प्राप्त करता है। |
| [getReceiveShadows()](#getReceiveShadows--) | यह जाँचता है कि यह ज्यामिति छाया प्राप्त कर सकती है या नहीं। |
| [getScene()](#getScene--) | इस ऑब्जेक्ट से संबंधित सीन प्राप्त करता है |
| [getTube()](#getTube--) | ट्यूब की त्रिज्या प्राप्त करता है। |
| [getTubularSegments()](#getTubularSegments--) | ट्यूब्युलर सेगमेंट्स प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setArc(double value)](#setArc-double-) | Arc सेट करता है। |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | यह निर्धारित करता है कि यह ज्यामिति छाया डाल सकती है या नहीं। |
| [setExcluded(boolean value)](#setExcluded-boolean-) | निर्यात के दौरान इस इकाई को बाहर रखने का चयन सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | पहला पैरेंट नोड सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह इकाई अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setRadialSegments(int value)](#setRadialSegments-int-) | रेडियल सेगमेंट्स सेट करता है। |
| [setRadius(double value)](#setRadius-double-) | Torus की त्रिज्या सेट करता है। |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | यह निर्धारित करता है कि यह ज्यामिति छाया प्राप्त कर सकती है या नहीं। |
| [setTube(double value)](#setTube-double-) | ट्यूब की त्रिज्या सेट करता है। |
| [setTubularSegments(int value)](#setTubularSegments-int-) | ट्यूब्युलर सेगमेंट्स सेट करता है। |
| [toMesh()](#toMesh--) | वर्तमान ऑब्जेक्ट को मेष में परिवर्तित करें |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Torus() {#Torus--}
```
public Torus()
```


नया instance [Torus](../../com.aspose.threed/torus) क्लास का इनिशियलाइज़ करता है।

### Torus(double radius, double tube) {#Torus-double-double-}
```
public Torus(double radius, double tube)
```


नया instance [Torus](../../com.aspose.threed/torus) क्लास का इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| त्रिज्या | double | Torus की त्रिज्या। |
| ट्यूब | double | Torus के ट्यूब की त्रिज्या। |

### Torus(double radius, double tube, double arc) {#Torus-double-double-double-}
```
public Torus(double radius, double tube, double arc)
```


नया instance [Torus](../../com.aspose.threed/torus) क्लास का इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| त्रिज्या | double | Torus की त्रिज्या। |
| ट्यूब | double | Torus के ट्यूब की त्रिज्या। |
| आर्क | double | आर्क। |

### Torus(String name, double radius, double tube, int radialSegments, int tubularSegments, double arc) {#Torus-java.lang.String-double-double-int-int-double-}
```
public Torus(String name, double radius, double tube, int radialSegments, int tubularSegments, double arc)
```


नया instance [Torus](../../com.aspose.threed/torus) क्लास का इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | नाम। |
| त्रिज्या | double | Torus की त्रिज्या। |
| ट्यूब | double | Torus के ट्यूब की त्रिज्या। |
| radialSegments | int | त्रिज्यात्मक खंड। |
| tubularSegments | int | नली खंड। |
| आर्क | double | आर्क। |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


प्रॉपर्टी को खोजता है। यह एक डायनामिक प्रॉपर्टी (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (नाम द्वारा पहचानी गई) हो सकती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propertyName | java.lang.String | प्रॉपर्टी नाम। |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getArc() {#getArc--}
```
public double getArc()
```


Arc प्राप्त करता है।

**Returns:**
डबल - आर्क।
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


वर्तमान इकाई का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में प्राप्त करता है।

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


यह जाँचता है कि यह ज्यामिति छाया डाल सकती है या नहीं।

**Returns:**
boolean - क्या यह ज्यामिति छाया डाल सकती है
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


रेंडरर में पंजीकृत इकाई रेंडरर की कुंजी प्राप्त करता है

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


निर्यात के दौरान इस इकाई को बाहर रखने का चयन प्राप्त करता है।

**Returns:**
बूलियन - निर्यात के दौरान इस इकाई को बाहर रखने का चयन।
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


पहला पैरेंट नोड प्राप्त करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह इकाई अन्य पैरेंट नोड्स से अलग हो जाएगी।

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


सभी पैरेंट नोड्स प्राप्त करता है, एक इकाई ज्योमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जुड़ी हो सकती है

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी नाम |

**Returns:**
java.lang.Object - मिली हुई प्रॉपर्टी का मान
### getRadialSegments() {#getRadialSegments--}
```
public int getRadialSegments()
```


रेडियल सेगमेंट्स प्राप्त करता है।

**Returns:**
int - रेडियल सेगमेंट।
### getRadius() {#getRadius--}
```
public double getRadius()
```


Torus का त्रिज्या प्राप्त करता है।

**Returns:**
डबल - टॉरस की त्रिज्या।
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


यह जाँचता है कि यह ज्यामिति छाया प्राप्त कर सकती है या नहीं।

**Returns:**
boolean - क्या यह ज्यामिति छाया प्राप्त कर सकती है।
### getScene() {#getScene--}
```
public Scene getScene()
```


इस ऑब्जेक्ट से संबंधित सीन प्राप्त करता है

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTube() {#getTube--}
```
public double getTube()
```


ट्यूब की त्रिज्या प्राप्त करता है।

**Returns:**
डबल - ट्यूब की त्रिज्या।
### getTubularSegments() {#getTubularSegments--}
```
public int getTubularSegments()
```


ट्यूब्युलर सेगमेंट्स प्राप्त करता है।

**Returns:**
इंट - नली खंड।
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
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | कौन सी प्रॉपर्टी हटानी है |

**Returns:**
boolean - यदि प्रॉपर्टी सफलतापूर्वक हटाई गई हो तो true
### setArc(double value) {#setArc-double-}
```
public void setArc(double value)
```


Arc सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


यह निर्धारित करता है कि यह ज्यामिति छाया डाल सकती है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


निर्यात के दौरान इस इकाई को बाहर रखने का चयन सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


नाम सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


पहला पैरेंट नोड सेट करता है, यदि पहला पैरेंट नोड सेट किया जाता है, तो यह इकाई अन्य पैरेंट नोड्स से अलग हो जाएगी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | नया मान |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


निर्दिष्ट प्रॉपर्टी का मान सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी नाम |
| मान | java.lang.Object | प्रॉपर्टी का मान |

### setRadialSegments(int value) {#setRadialSegments-int-}
```
public void setRadialSegments(int value)
```


रेडियल सेगमेंट्स सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setRadius(double value) {#setRadius-double-}
```
public void setRadius(double value)
```


Torus की त्रिज्या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


यह निर्धारित करता है कि यह ज्यामिति छाया प्राप्त कर सकती है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setTube(double value) {#setTube-double-}
```
public void setTube(double value)
```


ट्यूब की त्रिज्या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setTubularSegments(int value) {#setTubularSegments-int-}
```
public void setTubularSegments(int value)
```


ट्यूब्युलर सेगमेंट्स सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


वर्तमान ऑब्जेक्ट को मेष में परिवर्तित करें

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The mesh.
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

