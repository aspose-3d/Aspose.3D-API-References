---
title: LinearExtrusion
second_title: Aspose.3D for Java API Reference
description: लीनियर एक्सट्रूज़न 2D आकार को इनपुट के रूप में लेता है और आकार को तीसरे आयाम में विस्तारित करता है।
type: docs
weight: 96
url: /hi/java/com.aspose.threed/linearextrusion/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class LinearExtrusion extends Entity implements IMeshConvertible
```

Linear extrusion takes a 2D shape as input and extends the shape in the 3rd dimension. **उदाहरण:** निम्नलिखित कोड दिखाता है कि LinearExtrusion का उपयोग करके किसी आकार को ठोस मॉडल में कैसे एक्सट्रूड किया जाए।

```
//Create a new 3D scene
 		Scene scene = new Scene();
 
 		// Initialize the base profile to be extruded
 		var profile = new RectangleShape();
 		profile.setRoundingRadius(0.3);
 
 		// Create left node
 		var left = scene.getRootNode().createChildNode();
 		left.createChildNode(new Box(0.01, 3, 3));
 
 		// Create right node
 		var right = scene.getRootNode().createChildNode();
 		right.createChildNode(new Box(0.01, 3, 3));
 		right.getTransform().setTranslation(new Vector3(5, 0, 0));
 
 		//Perform linear extrusion on left node using center and slices property
 		var l = new LinearExtrusion(profile, 10);
 		l.setCenter(false);
 		l.setSlices(3);
 		l.setTwist(20);
 		left.createChildNode(l);
 
 		// Perform linear extrusion on left node using center and slices property
 		var r = new LinearExtrusion(profile, 10);
 		r.setCenter(true);
 		r.setSlices(3);
 		r.setTwist(90);
 		right.createChildNode(r);
```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [LinearExtrusion()](#LinearExtrusion--) | इंस्टेंस [LinearExtrusion](../../com.aspose.threed/linearextrusion) का कंस्ट्रक्टर। |
| [LinearExtrusion(Profile shape, double height)](#LinearExtrusion-com.aspose.threed.Profile-double-) | इंस्टेंस [LinearExtrusion](../../com.aspose.threed/linearextrusion) का कंस्ट्रक्टर। |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getBoundingBox()](#getBoundingBox--) | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कॉर्डिनेट सिस्टम में प्राप्त करता है। |
| [getCenter()](#getCenter--) | यदि यह मान false है, तो linear extrusion Z रेंज 0 से height तक होगी, अन्यथा रेंज -height/2 से height/2 तक होगी। |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | एक्सट्रूज़न की दिशा, डिफ़ॉल्ट मान (0, 0, 1) है। |
| [getEntityRendererKey()](#getEntityRendererKey--) | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [getExcluded()](#getExcluded--) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में प्राप्त करता है। |
| [getHeight()](#getHeight--) | एक्सट्रूडेड ज्योमेट्री की ऊँचाई, डिफ़ॉल्ट मान 1.0 है। |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getParentNode()](#getParentNode--) | पहला पैरेंट नोड प्राप्त करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [getParentNodes()](#getParentNodes--) | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जुड़ी हो सकती है |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getScene()](#getScene--) | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [getShape()](#getShape--) | एक्सट्रूड करने के लिए बेस आकार। |
| [getSlices()](#getSlices--) | ट्विस्टेड एक्सट्रूडेड ज्योमेट्री के स्लाइस, डिफ़ॉल्ट मान 1 है। |
| [getTwist()](#getTwist--) | आकार को एक्सट्रूड करने के लिए घुमाव की डिग्री संख्या। |
| [getTwistOffset()](#getTwistOffset--) | ट्विस्टिंग में उपयोग किया जाने वाला ऑफसेट, डिफ़ॉल्ट मान (0, 0, 0) है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setCenter(boolean value)](#setCenter-boolean-) | यदि यह मान false है, तो linear extrusion Z रेंज 0 से height तक होगी, अन्यथा रेंज -height/2 से height/2 तक होगी। |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | एक्सट्रूज़न की दिशा, डिफ़ॉल्ट मान (0, 0, 1) है। |
| [setExcluded(boolean value)](#setExcluded-boolean-) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में सेट करता है। |
| [setHeight(double value)](#setHeight-double-) | एक्सट्रूडेड ज्योमेट्री की ऊँचाई, डिफ़ॉल्ट मान 1.0 है। |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | पहला पैरेंट नोड सेट करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setShape(Profile value)](#setShape-com.aspose.threed.Profile-) | एक्सट्रूड करने के लिए बेस आकार। |
| [setSlices(int value)](#setSlices-int-) | ट्विस्टेड एक्सट्रूडेड ज्योमेट्री के स्लाइस, डिफ़ॉल्ट मान 1 है। |
| [setTwist(double value)](#setTwist-double-) | आकार को एक्सट्रूड करने के लिए घुमाव की डिग्री संख्या। |
| [setTwistOffset(Vector3 value)](#setTwistOffset-com.aspose.threed.Vector3-) | ट्विस्टिंग में उपयोग किया जाने वाला ऑफसेट, डिफ़ॉल्ट मान (0, 0, 0) है। |
| [toMesh()](#toMesh--) | एक्सट्रूज़न को मेष में बदलें। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearExtrusion() {#LinearExtrusion--}
```
public LinearExtrusion()
```


इंस्टेंस [LinearExtrusion](../../com.aspose.threed/linearextrusion) का कंस्ट्रक्टर।

### LinearExtrusion(Profile shape, double height) {#LinearExtrusion-com.aspose.threed.Profile-double-}
```
public LinearExtrusion(Profile shape, double height)
```


इंस्टेंस [LinearExtrusion](../../com.aspose.threed/linearextrusion) का कंस्ट्रक्टर।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| shape | [Profile](../../com.aspose.threed/profile) |  |
| ऊँचाई | double |  |

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
### getCenter() {#getCenter--}
```
public boolean getCenter()
```


यदि यह मान false है, तो linear extrusion Z रेंज 0 से height तक होगी, अन्यथा रेंज -height/2 से height/2 तक होगी।

**Returns:**
boolean - यदि यह मान false है, तो linear extrusion Z रेंज 0 से height तक होगी, अन्यथा रेंज -height/2 से height/2 तक होगी।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDirection() {#getDirection--}
```
public Vector3 getDirection()
```


एक्सट्रूज़न की दिशा, डिफ़ॉल्ट मान (0, 0, 1) है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The direction of extrusion, default value is (0, 0, 1)
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


एक्सट्रूडेड ज्योमेट्री की ऊँचाई, डिफ़ॉल्ट मान 1.0 है।

**Returns:**
double - एक्सट्रूडेड ज्योमेट्री की ऊँचाई, डिफ़ॉल्ट मान 1.0 है।
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
### getShape() {#getShape--}
```
public Profile getShape()
```


एक्सट्रूड करने के लिए बेस आकार।

**Returns:**
[Profile](../../com.aspose.threed/profile) - The base shape to be extruded.
### getSlices() {#getSlices--}
```
public int getSlices()
```


ट्विस्टेड एक्सट्रूडेड ज्योमेट्री के स्लाइस, डिफ़ॉल्ट मान 1 है।

**Returns:**
int - ट्विस्टेड एक्सट्रूडेड ज्योमेट्री के स्लाइस, डिफ़ॉल्ट मान 1 है।
### getTwist() {#getTwist--}
```
public double getTwist()
```


आकार को एक्सट्रूड करने के लिए घुमाव की डिग्री संख्या।

**Returns:**
double - आकार को एक्सट्रूड करने के लिए घुमाव की डिग्री संख्या।
### getTwistOffset() {#getTwistOffset--}
```
public Vector3 getTwistOffset()
```


ट्विस्टिंग में उपयोग किया जाने वाला ऑफसेट, डिफ़ॉल्ट मान (0, 0, 0) है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The offset that used in twisting, default value is (0, 0, 0).
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
### setCenter(boolean value) {#setCenter-boolean-}
```
public void setCenter(boolean value)
```


यदि यह मान false है, तो linear extrusion Z रेंज 0 से height तक होगी, अन्यथा रेंज -height/2 से height/2 तक होगी।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


एक्सट्रूज़न की दिशा, डिफ़ॉल्ट मान (0, 0, 1) है।

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

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


एक्सट्रूडेड ज्योमेट्री की ऊँचाई, डिफ़ॉल्ट मान 1.0 है।

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

### setShape(Profile value) {#setShape-com.aspose.threed.Profile-}
```
public void setShape(Profile value)
```


एक्सट्रूड करने के लिए बेस आकार।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Profile](../../com.aspose.threed/profile) | नया मान |

### setSlices(int value) {#setSlices-int-}
```
public void setSlices(int value)
```


ट्विस्टेड एक्सट्रूडेड ज्योमेट्री के स्लाइस, डिफ़ॉल्ट मान 1 है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setTwist(double value) {#setTwist-double-}
```
public void setTwist(double value)
```


आकार को एक्सट्रूड करने के लिए घुमाव की डिग्री संख्या।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setTwistOffset(Vector3 value) {#setTwistOffset-com.aspose.threed.Vector3-}
```
public void setTwistOffset(Vector3 value)
```


ट्विस्टिंग में उपयोग किया जाने वाला ऑफसेट, डिफ़ॉल्ट मान (0, 0, 0) है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


एक्सट्रूज़न को मेष में बदलें।

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

