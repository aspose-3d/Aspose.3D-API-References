---
title: पिरामिड
second_title: Aspose.3D for Java API Reference
description: पैरामीटराइज़्ड पिरामिड।
type: docs
weight: 142
url: /hi/java/com.aspose.threed/pyramid/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Pyramid extends Primitive
```

पैरामीटराइज़्ड पिरामिड।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Pyramid()](#Pyramid--) | डिफ़ॉल्ट नीचे के क्षेत्र (10, 10) और डिफ़ॉल्ट ऊँचाई (5) के साथ एक नया पिरामिड इंस्टेंस बनाएं |
| [Pyramid(double xbottom, double ybottom, double height)](#Pyramid-double-double-double-) | निर्दिष्ट नीचे के क्षेत्र के साथ एक नया पिरामिड इंस्टेंस बनाएं |
| [Pyramid(double xbottom, double ybottom, double xtop, double ytop, double height)](#Pyramid-double-double-double-double-double-) | निर्दिष्ट नीचे के क्षेत्र, ऊपर के क्षेत्र और ऊँचाई के साथ एक नया पिरामिड इंस्टेंस बनाएं। |
| [Pyramid(String name, double xbottom, double ybottom, double xtop, double ytop, double height)](#Pyramid-java.lang.String-double-double-double-double-double-) | निर्दिष्ट नीचे के क्षेत्र, ऊपर के क्षेत्र और ऊँचाई के साथ एक नया पिरामिड इंस्टेंस बनाएं। |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getBottomArea()](#getBottomArea--) | नीचे के कैप का क्षेत्रफल |
| [getBottomOffset()](#getBottomOffset--) | नीचे के शीर्ष बिंदुओं के लिए ऑफ़सेट |
| [getBoundingBox()](#getBoundingBox--) | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कॉर्डिनेट सिस्टम में प्राप्त करता है। |
| [getCastShadows()](#getCastShadows--) | यह जियोमेट्री छाया डाल सकती है या नहीं प्राप्त करता है |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [getExcluded()](#getExcluded--) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में प्राप्त करता है। |
| [getHeight()](#getHeight--) | पिरामिड की ऊँचाई |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getParentNode()](#getParentNode--) | पहला पैरेंट नोड प्राप्त करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [getParentNodes()](#getParentNodes--) | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जुड़ी हो सकती है |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getReceiveShadows()](#getReceiveShadows--) | यह जियोमेट्री छाया प्राप्त कर सकती है या नहीं प्राप्त करता है। |
| [getScene()](#getScene--) | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [getTopArea()](#getTopArea--) | ऊपर के कैप का क्षेत्रफल |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setBottomArea(Vector2 value)](#setBottomArea-com.aspose.threed.Vector2-) | नीचे के कैप का क्षेत्रफल |
| [setBottomOffset(Vector3 value)](#setBottomOffset-com.aspose.threed.Vector3-) | नीचे के शीर्ष बिंदुओं के लिए ऑफ़सेट |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | यह जियोमेट्री छाया डाल सकती है या नहीं सेट करता है |
| [setExcluded(boolean value)](#setExcluded-boolean-) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में सेट करता है। |
| [setHeight(double value)](#setHeight-double-) | पिरामिड की ऊँचाई |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | पहला पैरेंट नोड सेट करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | यह जियोमेट्री छाया प्राप्त कर सकती है या नहीं सेट करता है। |
| [setTopArea(Vector2 value)](#setTopArea-com.aspose.threed.Vector2-) | ऊपर के कैप का क्षेत्रफल |
| [toMesh()](#toMesh--) | वर्तमान ऑब्जेक्ट को मेष में परिवर्तित करें |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pyramid() {#Pyramid--}
```
public Pyramid()
```


डिफ़ॉल्ट नीचे के क्षेत्र (10, 10) और डिफ़ॉल्ट ऊँचाई (5) के साथ एक नया पिरामिड इंस्टेंस बनाएं

### Pyramid(double xbottom, double ybottom, double height) {#Pyramid-double-double-double-}
```
public Pyramid(double xbottom, double ybottom, double height)
```


निर्दिष्ट नीचे के क्षेत्र के साथ एक नया पिरामिड इंस्टेंस बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| xbottom | double | नीचे की x-दिशा लंबाई |
| ybottom | double | नीचे की y-दिशा लंबाई |
| ऊँचाई | double | पिरामिड की ऊँचाई |

### Pyramid(double xbottom, double ybottom, double xtop, double ytop, double height) {#Pyramid-double-double-double-double-double-}
```
public Pyramid(double xbottom, double ybottom, double xtop, double ytop, double height)
```


निर्दिष्ट नीचे के क्षेत्र, ऊपर के क्षेत्र और ऊँचाई के साथ एक नया पिरामिड इंस्टेंस बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| xbottom | double | नीचे के क्षेत्र की x-दिशा लंबाई |
| ybottom | double | नीचे के क्षेत्र की y-दिशा लंबाई |
| xtop | double | ऊपर के क्षेत्र की x-दिशा लंबाई |
| ytop | double | ऊपर के क्षेत्र की y-दिशा लंबाई |
| ऊँचाई | double | पिरामिड की ऊँचाई |

### Pyramid(String name, double xbottom, double ybottom, double xtop, double ytop, double height) {#Pyramid-java.lang.String-double-double-double-double-double-}
```
public Pyramid(String name, double xbottom, double ybottom, double xtop, double ytop, double height)
```


निर्दिष्ट नीचे के क्षेत्र, ऊपर के क्षेत्र और ऊँचाई के साथ एक नया पिरामिड इंस्टेंस बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | पिरामिड का नाम |
| xbottom | double | नीचे के क्षेत्र की x-दिशा लंबाई |
| ybottom | double | नीचे के क्षेत्र की y-दिशा लंबाई |
| xtop | double | ऊपर के क्षेत्र की x-दिशा लंबाई |
| ytop | double | ऊपर के क्षेत्र की y-दिशा लंबाई |
| ऊँचाई | double | पिरामिड की ऊँचाई |

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
### getBottomArea() {#getBottomArea--}
```
public Vector2 getBottomArea()
```


नीचे के कैप का क्षेत्रफल

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Area of the bottom cap
### getBottomOffset() {#getBottomOffset--}
```
public Vector3 getBottomOffset()
```


नीचे के शीर्ष बिंदुओं के लिए ऑफ़सेट

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Offset for bottom vertices
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
### getHeight() {#getHeight--}
```
public double getHeight()
```


पिरामिड की ऊँचाई

**Returns:**
double - पिरामिड की ऊँचाई
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
### getTopArea() {#getTopArea--}
```
public Vector2 getTopArea()
```


ऊपर के कैप का क्षेत्रफल

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Area of the top cap
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
### setBottomArea(Vector2 value) {#setBottomArea-com.aspose.threed.Vector2-}
```
public void setBottomArea(Vector2 value)
```


नीचे के कैप का क्षेत्रफल

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | नया मान |

### setBottomOffset(Vector3 value) {#setBottomOffset-com.aspose.threed.Vector3-}
```
public void setBottomOffset(Vector3 value)
```


नीचे के शीर्ष बिंदुओं के लिए ऑफ़सेट

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

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

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


पिरामिड की ऊँचाई

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

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

### setTopArea(Vector2 value) {#setTopArea-com.aspose.threed.Vector2-}
```
public void setTopArea(Vector2 value)
```


ऊपर के कैप का क्षेत्रफल

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | नया मान |

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

