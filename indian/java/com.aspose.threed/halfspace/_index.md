---
title: HalfSpace
second_title: Aspose.3D for Java API Reference
description: एक अनंत स्थान का प्रतिनिधित्व करता है जिसे एक तल द्वारा विभाजित किया जाता है, इसे साथ में उपयोग किया जा सकता है।
type: docs
weight: 77
url: /hi/java/com.aspose.threed/halfspace/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)
```
public class HalfSpace extends Entity
```

[HalfSpace](../../com.aspose.threed/halfspace) represents a infinity space which is split by a plane, this can be used with [BooleanOperator](../../com.aspose.threed/booleanoperator)
## Constructors

| Constructor | विवरण |
| --- | --- |
| [HalfSpace()](#HalfSpace--) | एक नया उदाहरण बनाता है [HalfSpace](../../com.aspose.threed/halfspace) का |
| [HalfSpace(Vector3 normal, Vector3 position)](#HalfSpace-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | दिए गए सामान्य वेक्टर और कटर तल पर स्थिति के साथ [HalfSpace](../../com.aspose.threed/halfspace) का नया उदाहरण बनाता है; |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getBoundingBox()](#getBoundingBox--) | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कॉर्डिनेट सिस्टम में प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [getExcluded()](#getExcluded--) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में प्राप्त करता है। |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getNormal()](#getNormal--) | विभाजित तल का सामान्य, तल को N \* P + D = 0 के रूप में परिभाषित किया गया है जहाँ N सामान्य है और P तल पर कोई भी बिंदु है। |
| [getParentNode()](#getParentNode--) | पहला पैरेंट नोड प्राप्त करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [getParentNodes()](#getParentNodes--) | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जुड़ी हो सकती है |
| [getPosition()](#getPosition--) | विभाजित तल पर कोई भी बिंदु, तल को N \* P + D = 0 के रूप में परिभाषित किया गया है जहाँ N सामान्य है और P तल पर कोई भी बिंदु है। |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getScene()](#getScene--) | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setExcluded(boolean value)](#setExcluded-boolean-) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setNormal(Vector3 value)](#setNormal-com.aspose.threed.Vector3-) | विभाजित तल का सामान्य, तल को N \* P + D = 0 के रूप में परिभाषित किया गया है जहाँ N सामान्य है और P तल पर कोई भी बिंदु है। |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | पहला पैरेंट नोड सेट करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [setPosition(Vector3 value)](#setPosition-com.aspose.threed.Vector3-) | विभाजित तल पर कोई भी बिंदु, तल को N \* P + D = 0 के रूप में परिभाषित किया गया है जहाँ N सामान्य है और P तल पर कोई भी बिंदु है। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HalfSpace() {#HalfSpace--}
```
public HalfSpace()
```


एक नया उदाहरण बनाता है [HalfSpace](../../com.aspose.threed/halfspace) का

### HalfSpace(Vector3 normal, Vector3 position) {#HalfSpace-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public HalfSpace(Vector3 normal, Vector3 position)
```


दिए गए सामान्य वेक्टर और कटर तल पर स्थिति के साथ [HalfSpace](../../com.aspose.threed/halfspace) का नया उदाहरण बनाता है;

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| normal | [Vector3](../../com.aspose.threed/vector3) |  |
| position | [Vector3](../../com.aspose.threed/vector3) |  |

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
### getName() {#getName--}
```
public String getName()
```


नाम प्राप्त करता है।

**Returns:**
java.lang.String - नाम।
### getNormal() {#getNormal--}
```
public Vector3 getNormal()
```


विभाजित तल का सामान्य, तल को N \* P + D = 0 के रूप में परिभाषित किया गया है जहाँ N सामान्य है और P तल पर कोई भी बिंदु है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The normal of the split plane, the plane is defined as N \* P + D = 0 where N is Normal and P is any point on the plane.
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
### getPosition() {#getPosition--}
```
public Vector3 getPosition()
```


विभाजित तल पर कोई भी बिंदु, तल को N \* P + D = 0 के रूप में परिभाषित किया गया है जहाँ N सामान्य है और P तल पर कोई भी बिंदु है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The any point on the split plane, the plane is defined as N \* P + D = 0 where N is Normal and P is any point on the plane.
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

### setNormal(Vector3 value) {#setNormal-com.aspose.threed.Vector3-}
```
public void setNormal(Vector3 value)
```


विभाजित तल का सामान्य, तल को N \* P + D = 0 के रूप में परिभाषित किया गया है जहाँ N सामान्य है और P तल पर कोई भी बिंदु है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


पहला पैरेंट नोड सेट करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | नया मान |

### setPosition(Vector3 value) {#setPosition-com.aspose.threed.Vector3-}
```
public void setPosition(Vector3 value)
```


विभाजित तल पर कोई भी बिंदु, तल को N \* P + D = 0 के रूप में परिभाषित किया गया है जहाँ N सामान्य है और P तल पर कोई भी बिंदु है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

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

