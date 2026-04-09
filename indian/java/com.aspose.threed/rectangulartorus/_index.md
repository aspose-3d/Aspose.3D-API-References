---
title: RectangularTorus
second_title: Aspose.3D for Java API Reference
description: पैरामीटराइज़्ड आयताकार टॉरस।
type: docs
weight: 146
url: /hi/java/com.aspose.threed/rectangulartorus/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class RectangularTorus extends Primitive
```

पैरामीटराइज़्ड आयताकार टॉरस।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [RectangularTorus()](#RectangularTorus--) | [RectangularTorus](../../com.aspose.threed/rectangulartorus) का कंस्ट्रक्टर |
| [RectangularTorus(String name)](#RectangularTorus-java.lang.String-) | [RectangularTorus](../../com.aspose.threed/rectangulartorus) का कंस्ट्रक्टर |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getAngleStart()](#getAngleStart--) | वृत्तांश का प्रारंभिक कोण, रेडियन में मापा गया। |
| [getArc()](#getArc--) | वृत्तांश का कुल कोण, रेडियन में मापा गया। |
| [getBoundingBox()](#getBoundingBox--) | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कॉर्डिनेट सिस्टम में प्राप्त करता है। |
| [getCastShadows()](#getCastShadows--) | यह जियोमेट्री छाया डाल सकती है या नहीं प्राप्त करता है |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [getExcluded()](#getExcluded--) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में प्राप्त करता है। |
| [getHeight()](#getHeight--) | आयताकार टॉरस की ऊँचाई। |
| [getInnerRadius()](#getInnerRadius--) | आयताकार टॉरस की आंतरिक त्रिज्या, डिफ़ॉल्ट मान 17 है। |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getOuterRadius()](#getOuterRadius--) | आयताकार टॉरस की बाहरी त्रिज्या, डिफ़ॉल्ट मान 20 है। |
| [getParentNode()](#getParentNode--) | पहला पैरेंट नोड प्राप्त करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [getParentNodes()](#getParentNodes--) | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जुड़ी हो सकती है |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getRadialSegments()](#getRadialSegments--) | रेडियल खंड, डिफ़ॉल्ट मान 10 है। |
| [getReceiveShadows()](#getReceiveShadows--) | यह जियोमेट्री छाया प्राप्त कर सकती है या नहीं प्राप्त करता है। |
| [getScene()](#getScene--) | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setAngleStart(double value)](#setAngleStart-double-) | वृत्तांश का प्रारंभिक कोण, रेडियन में मापा गया। |
| [setArc(double value)](#setArc-double-) | वृत्तांश का कुल कोण, रेडियन में मापा गया। |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | यह जियोमेट्री छाया डाल सकती है या नहीं सेट करता है |
| [setExcluded(boolean value)](#setExcluded-boolean-) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में सेट करता है। |
| [setHeight(double value)](#setHeight-double-) | आयताकार टॉरस की ऊँचाई। |
| [setInnerRadius(double value)](#setInnerRadius-double-) | आयताकार टॉरस की आंतरिक त्रिज्या, डिफ़ॉल्ट मान 17 है। |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setOuterRadius(double value)](#setOuterRadius-double-) | आयताकार टॉरस की बाहरी त्रिज्या, डिफ़ॉल्ट मान 20 है। |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | पहला पैरेंट नोड सेट करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setRadialSegments(int value)](#setRadialSegments-int-) | रेडियल खंड, डिफ़ॉल्ट मान 10 है। |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | यह जियोमेट्री छाया प्राप्त कर सकती है या नहीं सेट करता है। |
| [toMesh()](#toMesh--) | इस प्रिमिटिव को [Mesh](../../com.aspose.threed/mesh) में परिवर्तित करें। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangularTorus() {#RectangularTorus--}
```
public RectangularTorus()
```


[RectangularTorus](../../com.aspose.threed/rectangulartorus) का कंस्ट्रक्टर

### RectangularTorus(String name) {#RectangularTorus-java.lang.String-}
```
public RectangularTorus(String name)
```


[RectangularTorus](../../com.aspose.threed/rectangulartorus) का कंस्ट्रक्टर

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String |  |

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
### getAngleStart() {#getAngleStart--}
```
public double getAngleStart()
```


वृत्तांश का प्रारंभिक कोण, रेडियन में मापा गया। डिफ़ॉल्ट मान 0 है।

**Returns:**
double - आर्क का प्रारंभिक कोण, रेडियन में मापा गया। डिफ़ॉल्ट मान 0 है।
### getArc() {#getArc--}
```
public double getArc()
```


आर्क का कुल कोण, रेडियन में मापा गया। डिफ़ॉल्ट मान PI है।

**Returns:**
double - आर्क का कुल कोण, रेडियन में मापा गया। डिफ़ॉल्ट मान PI है।
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


आयताकार टोरस की ऊँचाई। डिफ़ॉल्ट मान 20 है।

**Returns:**
double - आयताकार टोरस की ऊँचाई। डिफ़ॉल्ट मान 20 है।
### getInnerRadius() {#getInnerRadius--}
```
public double getInnerRadius()
```


आयताकार टॉरस की आंतरिक त्रिज्या, डिफ़ॉल्ट मान 17 है।

**Returns:**
double - आयताकार टोरस का आंतरिक त्रिज्या। डिफ़ॉल्ट मान 17 है।
### getName() {#getName--}
```
public String getName()
```


नाम प्राप्त करता है।

**Returns:**
java.lang.String - नाम।
### getOuterRadius() {#getOuterRadius--}
```
public double getOuterRadius()
```


आयताकार टॉरस की बाहरी त्रिज्या, डिफ़ॉल्ट मान 20 है।

**Returns:**
double - आयताकार टोरस का बाहरी त्रिज्या। डिफ़ॉल्ट मान 20 है।
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
### getRadialSegments() {#getRadialSegments--}
```
public int getRadialSegments()
```


रेडियल खंड, डिफ़ॉल्ट मान 10 है।

**Returns:**
int - रेडियल सेगमेंट्स, डिफ़ॉल्ट मान 10 है।
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
### setAngleStart(double value) {#setAngleStart-double-}
```
public void setAngleStart(double value)
```


वृत्तांश का प्रारंभिक कोण, रेडियन में मापा गया। डिफ़ॉल्ट मान 0 है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setArc(double value) {#setArc-double-}
```
public void setArc(double value)
```


आर्क का कुल कोण, रेडियन में मापा गया। डिफ़ॉल्ट मान PI है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

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


आयताकार टोरस की ऊँचाई। डिफ़ॉल्ट मान 20 है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setInnerRadius(double value) {#setInnerRadius-double-}
```
public void setInnerRadius(double value)
```


आयताकार टॉरस की आंतरिक त्रिज्या, डिफ़ॉल्ट मान 17 है।

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

### setOuterRadius(double value) {#setOuterRadius-double-}
```
public void setOuterRadius(double value)
```


आयताकार टॉरस की बाहरी त्रिज्या, डिफ़ॉल्ट मान 20 है।

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

### setRadialSegments(int value) {#setRadialSegments-int-}
```
public void setRadialSegments(int value)
```


रेडियल खंड, डिफ़ॉल्ट मान 10 है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


यह जियोमेट्री छाया प्राप्त कर सकती है या नहीं सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


इस प्रिमिटिव को [Mesh](../../com.aspose.threed/mesh) में परिवर्तित करें।

**Returns:**
[Mesh](../../com.aspose.threed/mesh)
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

