---
title: HShape
second_title: Aspose.3D for Java API Reference
description: यह H या I आकार के परिभाषित पैरामीटर प्रदान करता है।
type: docs
weight: 76
url: /hi/java/com.aspose.threed/hshape/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Profile](../../com.aspose.threed/profile), [com.aspose.threed.ParameterizedProfile](../../com.aspose.threed/parameterizedprofile)
```
public class HShape extends ParameterizedProfile
```

क्लास [HShape](../../com.aspose.threed/hshape) 'H' या 'I' आकार के परिभाषित पैरामीटर प्रदान करती है।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [HShape()](#HShape--) | [HShape](../../com.aspose.threed/hshape) का कंस्ट्रक्टर |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getBottomFlangeEdgeRadius()](#getBottomFlangeEdgeRadius--) | बॉटम फ्लैंज के ऊपरी किनारों की त्रिज्या प्राप्त करता है। |
| [getBottomFlangeFilletRadius()](#getBottomFlangeFilletRadius--) | वेब और निचले फ्लैंज के बीच फ़िलेट की त्रिज्या प्राप्त करता है। |
| [getBottomFlangeThickness()](#getBottomFlangeThickness--) | एच-आकार की फ्लैंज मोटाई प्राप्त करता है। |
| [getBottomFlangeWidth()](#getBottomFlangeWidth--) | चौड़ाई की सीमा प्राप्त करता है। |
| [getBoundingBox()](#getBoundingBox--) | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कॉर्डिनेट सिस्टम में प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [getExcluded()](#getExcluded--) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में प्राप्त करता है। |
| [getExtent()](#getExtent--) | x और y आयाम में विस्तार प्राप्त करता है। |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getOverallDepth()](#getOverallDepth--) | गहराई की सीमा प्राप्त करता है। |
| [getParentNode()](#getParentNode--) | पहला पैरेंट नोड प्राप्त करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [getParentNodes()](#getParentNodes--) | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जुड़ी हो सकती है |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getScene()](#getScene--) | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [getTopFlangeEdgeRadius()](#getTopFlangeEdgeRadius--) | ऊपरी फ्लैंज के निचले किनारों की त्रिज्या प्राप्त करता है। |
| [getTopFlangeFilletRadius()](#getTopFlangeFilletRadius--) | वेब और ऊपरी फ्लैंज के बीच फ़िलेट की त्रिज्या प्राप्त करता है। |
| [getTopFlangeThickness()](#getTopFlangeThickness--) | ऊपरी फ्लैंज की मोटाई प्राप्त करता है। |
| [getTopFlangeWidth()](#getTopFlangeWidth--) | ऊपरी फ्लैंज की चौड़ाई प्राप्त करता है। |
| [getWebThickness()](#getWebThickness--) | एच-आकार के वेब की मोटाई प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setBottomFlangeEdgeRadius(double value)](#setBottomFlangeEdgeRadius-double-) | निचले फ्लैंज के ऊपरी किनारों की त्रिज्या सेट करता है। |
| [setBottomFlangeFilletRadius(double value)](#setBottomFlangeFilletRadius-double-) | वेब और निचले फ्लैंज के बीच फ़िलेट की त्रिज्या सेट करता है। |
| [setBottomFlangeThickness(double value)](#setBottomFlangeThickness-double-) | एच-आकार की फ्लैंज मोटाई सेट करता है। |
| [setBottomFlangeWidth(double value)](#setBottomFlangeWidth-double-) | चौड़ाई की सीमा सेट करता है। |
| [setExcluded(boolean value)](#setExcluded-boolean-) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setOverallDepth(double value)](#setOverallDepth-double-) | गहराई की सीमा सेट करता है। |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | पहला पैरेंट नोड सेट करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setTopFlangeEdgeRadius(double value)](#setTopFlangeEdgeRadius-double-) | ऊपरी फ्लैंज के निचले किनारों की त्रिज्या सेट करता है। |
| [setTopFlangeFilletRadius(double value)](#setTopFlangeFilletRadius-double-) | वेब और ऊपरी फ्लैंज के बीच फ़िलेट की त्रिज्या सेट करता है। |
| [setTopFlangeThickness(double value)](#setTopFlangeThickness-double-) | ऊपरी फ्लैंज की मोटाई सेट करता है। |
| [setTopFlangeWidth(double value)](#setTopFlangeWidth-double-) | ऊपरी फ्लैंज की चौड़ाई सेट करता है। |
| [setWebThickness(double value)](#setWebThickness-double-) | एच-आकार के वेब की मोटाई सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HShape() {#HShape--}
```
public HShape()
```


[HShape](../../com.aspose.threed/hshape) का कंस्ट्रक्टर

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
### getBottomFlangeEdgeRadius() {#getBottomFlangeEdgeRadius--}
```
public double getBottomFlangeEdgeRadius()
```


बॉटम फ्लैंज के ऊपरी किनारों की त्रिज्या प्राप्त करता है।

**Returns:**
डबल - निचले फ्लैंज के ऊपरी किनारों की त्रिज्या।
### getBottomFlangeFilletRadius() {#getBottomFlangeFilletRadius--}
```
public double getBottomFlangeFilletRadius()
```


वेब और निचले फ्लैंज के बीच फ़िलेट की त्रिज्या प्राप्त करता है।

**Returns:**
डबल - वेब और निचले फ्लैंज के बीच फ़िलेट की त्रिज्या।
### getBottomFlangeThickness() {#getBottomFlangeThickness--}
```
public double getBottomFlangeThickness()
```


एच-आकार की फ्लैंज मोटाई प्राप्त करता है।

**Returns:**
डबल - एच-आकार की फ्लैंज मोटाई।
### getBottomFlangeWidth() {#getBottomFlangeWidth--}
```
public double getBottomFlangeWidth()
```


चौड़ाई की सीमा प्राप्त करता है।

**Returns:**
डबल - चौड़ाई की सीमा।
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
[EntityRendererKey](../../com.aspose.threed/entityrendererkey)
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में प्राप्त करता है।

**Returns:**
बूलियन - निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में।
### getExtent() {#getExtent--}
```
public Vector2 getExtent()
```


x और y आयाम में विस्तार प्राप्त करता है।

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### getName() {#getName--}
```
public String getName()
```


नाम प्राप्त करता है।

**Returns:**
java.lang.String - नाम।
### getOverallDepth() {#getOverallDepth--}
```
public double getOverallDepth()
```


गहराई की सीमा प्राप्त करता है।

**Returns:**
डबल - गहराई की सीमा।
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
### getTopFlangeEdgeRadius() {#getTopFlangeEdgeRadius--}
```
public double getTopFlangeEdgeRadius()
```


ऊपरी फ्लैंज के निचले किनारों की त्रिज्या प्राप्त करता है।

**Returns:**
डबल - ऊपरी फ्लैंज के निचले किनारों की त्रिज्या।
### getTopFlangeFilletRadius() {#getTopFlangeFilletRadius--}
```
public double getTopFlangeFilletRadius()
```


वेब और ऊपरी फ्लैंज के बीच फ़िलेट की त्रिज्या प्राप्त करता है।

**Returns:**
double - वेब और शीर्ष फ्लैंज के बीच फ़िलेट की त्रिज्या।
### getTopFlangeThickness() {#getTopFlangeThickness--}
```
public double getTopFlangeThickness()
```


ऊपरी फ्लैंज की मोटाई प्राप्त करता है।

**Returns:**
double - शीर्ष फ्लैंज की मोटाई।
### getTopFlangeWidth() {#getTopFlangeWidth--}
```
public double getTopFlangeWidth()
```


ऊपरी फ्लैंज की चौड़ाई प्राप्त करता है।

**Returns:**
double - शीर्ष फ्लैंज की चौड़ाई।
### getWebThickness() {#getWebThickness--}
```
public double getWebThickness()
```


एच-आकार के वेब की मोटाई प्राप्त करता है।

**Returns:**
double - H-आकार के वेब की मोटाई।
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
### setBottomFlangeEdgeRadius(double value) {#setBottomFlangeEdgeRadius-double-}
```
public void setBottomFlangeEdgeRadius(double value)
```


निचले फ्लैंज के ऊपरी किनारों की त्रिज्या सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setBottomFlangeFilletRadius(double value) {#setBottomFlangeFilletRadius-double-}
```
public void setBottomFlangeFilletRadius(double value)
```


वेब और निचले फ्लैंज के बीच फ़िलेट की त्रिज्या सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setBottomFlangeThickness(double value) {#setBottomFlangeThickness-double-}
```
public void setBottomFlangeThickness(double value)
```


एच-आकार की फ्लैंज मोटाई सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setBottomFlangeWidth(double value) {#setBottomFlangeWidth-double-}
```
public void setBottomFlangeWidth(double value)
```


चौड़ाई की सीमा सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

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

### setOverallDepth(double value) {#setOverallDepth-double-}
```
public void setOverallDepth(double value)
```


गहराई की सीमा सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

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

### setTopFlangeEdgeRadius(double value) {#setTopFlangeEdgeRadius-double-}
```
public void setTopFlangeEdgeRadius(double value)
```


ऊपरी फ्लैंज के निचले किनारों की त्रिज्या सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setTopFlangeFilletRadius(double value) {#setTopFlangeFilletRadius-double-}
```
public void setTopFlangeFilletRadius(double value)
```


वेब और ऊपरी फ्लैंज के बीच फ़िलेट की त्रिज्या सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setTopFlangeThickness(double value) {#setTopFlangeThickness-double-}
```
public void setTopFlangeThickness(double value)
```


ऊपरी फ्लैंज की मोटाई सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setTopFlangeWidth(double value) {#setTopFlangeWidth-double-}
```
public void setTopFlangeWidth(double value)
```


ऊपरी फ्लैंज की चौड़ाई सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setWebThickness(double value) {#setWebThickness-double-}
```
public void setWebThickness(double value)
```


एच-आकार के वेब की मोटाई सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

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

