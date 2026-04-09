---
title: RevolvedAreaSolid
second_title: Aspose.3D for Java API Reference
description: यह वर्ग प्रोफ़ाइल द्वारा प्रदान किए गए क्रॉस‑सेक्शन को धुरी के चारों ओर घुमाकर एक ठोस मॉडल का प्रतिनिधित्व करता है।
type: docs
weight: 155
url: /hi/java/com.aspose.threed/revolvedareasolid/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class RevolvedAreaSolid extends Entity implements IMeshConvertible
```

यह वर्ग एक प्रोफ़ाइल द्वारा प्रदान किए गए क्रॉस‑सेक्शन को अक्ष के चारों ओर घुमाकर एक ठोस मॉडल का प्रतिनिधित्व करता है। **Example:** निम्नलिखित कोड दर्शाता है कि RevolvedAreaSolid का उपयोग करके किसी आकार को ठोस मॉडल में कैसे घुमाया जाए।

```
//Create a new 3D scene
         Scene scene = new Scene();
 
         // Initialize the base profile to be extruded
         var profile = new RectangleShape();
         profile.setRoundingRadius(0.3);
 
         var revolved = new RevolvedAreaSolid();
         revolved.setShape(profile);
         revolved.setOrigin(new Vector3(1, 0, 0));
         revolved.setAngleStart(0);
         revolved.setAngleEnd(Math.PI);
         scene.getRootNode().createChildNode(revolved);
 
         scene.save("revolved.obj");
```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [RevolvedAreaSolid()](#RevolvedAreaSolid--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getAngleEnd()](#getAngleEnd--) | घुमाव प्रक्रिया का समाप्ति कोण प्राप्त करता है, रैडियन में मापा जाता है, डिफ़ॉल्ट मान π है। |
| [getAngleStart()](#getAngleStart--) | घुमाव प्रक्रिया का प्रारंभिक कोण प्राप्त करता है, रैडियन में मापा गया, डिफ़ॉल्ट मान 0 है। |
| [getAxis()](#getAxis--) | अक्ष की दिशा प्राप्त करता है, डिफ़ॉल्ट मान (0, 1, 0) है। |
| [getBoundingBox()](#getBoundingBox--) | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कॉर्डिनेट सिस्टम में प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [getExcluded()](#getExcluded--) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में प्राप्त करता है। |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getOrigin()](#getOrigin--) | घुमाव का मूल बिंदु प्राप्त करता है, डिफ़ॉल्ट मान (0, 0, 0) है। |
| [getParentNode()](#getParentNode--) | पहला पैरेंट नोड प्राप्त करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [getParentNodes()](#getParentNodes--) | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जुड़ी हो सकती है |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getScene()](#getScene--) | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [getShape()](#getShape--) | घुमाने के लिए उपयोग किए जाने वाले बेस प्रोफ़ाइल को प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setAngleEnd(double value)](#setAngleEnd-double-) | घुमाव प्रक्रिया का समाप्ति कोण सेट करता है, रैडियन में मापा गया, डिफ़ॉल्ट मान π है। |
| [setAngleStart(double value)](#setAngleStart-double-) | घुमाव प्रक्रिया का प्रारंभिक कोण सेट करता है, रैडियन में मापा गया, डिफ़ॉल्ट मान 0 है। |
| [setAxis(Vector3 value)](#setAxis-com.aspose.threed.Vector3-) | अक्ष की दिशा सेट करता है, डिफ़ॉल्ट मान (0, 1, 0) है। |
| [setExcluded(boolean value)](#setExcluded-boolean-) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setOrigin(Vector3 value)](#setOrigin-com.aspose.threed.Vector3-) | घुमाव का मूल बिंदु सेट करता है, डिफ़ॉल्ट मान (0, 0, 0) है। |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | पहला पैरेंट नोड सेट करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setShape(Profile value)](#setShape-com.aspose.threed.Profile-) | घुमाने के लिए उपयोग किए जाने वाले बेस प्रोफ़ाइल को सेट करता है। |
| [toMesh()](#toMesh--) | [RevolvedAreaSolid](../../com.aspose.threed/revolvedareasolid) को मेष में परिवर्तित करें। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RevolvedAreaSolid() {#RevolvedAreaSolid--}
```
public RevolvedAreaSolid()
```


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
### getAngleEnd() {#getAngleEnd--}
```
public double getAngleEnd()
```


घुमाव प्रक्रिया का समाप्ति कोण प्राप्त करता है, रैडियन में मापा जाता है, डिफ़ॉल्ट मान π है।

**Returns:**
double - घुमाव प्रक्रिया का समाप्ति कोण, रैडियन में मापा गया, डिफ़ॉल्ट मान π है।
### getAngleStart() {#getAngleStart--}
```
public double getAngleStart()
```


घुमाव प्रक्रिया का प्रारंभिक कोण प्राप्त करता है, रैडियन में मापा गया, डिफ़ॉल्ट मान 0 है।

**Returns:**
double - घुमाव प्रक्रिया का प्रारंभिक कोण, रैडियन में मापा गया, डिफ़ॉल्ट मान 0 है।
### getAxis() {#getAxis--}
```
public Vector3 getAxis()
```


अक्ष की दिशा प्राप्त करता है, डिफ़ॉल्ट मान (0, 1, 0) है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the axis direction, default value is (0, 1, 0).
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
### getOrigin() {#getOrigin--}
```
public Vector3 getOrigin()
```


घुमाव का मूल बिंदु प्राप्त करता है, डिफ़ॉल्ट मान (0, 0, 0) है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the origin point of the revolving, default value is (0, 0, 0).
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
### getShape() {#getShape--}
```
public Profile getShape()
```


घुमाने के लिए उपयोग किए जाने वाले बेस प्रोफ़ाइल को प्राप्त करता है।

**Returns:**
[Profile](../../com.aspose.threed/profile) - the base profile used to revolve.
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
### setAngleEnd(double value) {#setAngleEnd-double-}
```
public void setAngleEnd(double value)
```


घुमाव प्रक्रिया का समाप्ति कोण सेट करता है, रैडियन में मापा गया, डिफ़ॉल्ट मान π है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setAngleStart(double value) {#setAngleStart-double-}
```
public void setAngleStart(double value)
```


घुमाव प्रक्रिया का प्रारंभिक कोण सेट करता है, रैडियन में मापा गया, डिफ़ॉल्ट मान 0 है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setAxis(Vector3 value) {#setAxis-com.aspose.threed.Vector3-}
```
public void setAxis(Vector3 value)
```


अक्ष की दिशा सेट करता है, डिफ़ॉल्ट मान (0, 1, 0) है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

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

### setOrigin(Vector3 value) {#setOrigin-com.aspose.threed.Vector3-}
```
public void setOrigin(Vector3 value)
```


घुमाव का मूल बिंदु सेट करता है, डिफ़ॉल्ट मान (0, 0, 0) है।

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

### setShape(Profile value) {#setShape-com.aspose.threed.Profile-}
```
public void setShape(Profile value)
```


घुमाने के लिए उपयोग किए जाने वाले बेस प्रोफ़ाइल को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Profile](../../com.aspose.threed/profile) | नया मान |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


[RevolvedAreaSolid](../../com.aspose.threed/revolvedareasolid) को मेष में परिवर्तित करें।

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

