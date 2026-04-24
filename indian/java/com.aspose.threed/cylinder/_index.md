---
title: सिलिंडर
second_title: Aspose.3D for Java API Reference
description: पैरामीटरयुक्त सिलिंडर।
type: docs
weight: 40
url: /hi/java/com.aspose.threed/cylinder/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Primitive](../../com.aspose.threed/primitive)
```
public class Cylinder extends Primitive
```

पैरामीटराइज़्ड सिलिंडर। यह कोन को दर्शाने के लिए भी उपयोग किया जा सकता है जब radiusTop/radiusBottom में से कोई एक शून्य हो।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Cylinder()](#Cylinder--) | नए इंस्टेंस को इनिशियलाइज़ करता है [Cylinder](../../com.aspose.threed/cylinder) क्लास का। |
| [Cylinder(double radius, double height)](#Cylinder-double-double-) | नए इंस्टेंस को इनिशियलाइज़ करता है [Cylinder](../../com.aspose.threed/cylinder) क्लास का। |
| [Cylinder(double radiusTop, double radiusBottom, double height)](#Cylinder-double-double-double-) | नए इंस्टेंस को इनिशियलाइज़ करता है [Cylinder](../../com.aspose.threed/cylinder) क्लास का। |
| [Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)](#Cylinder-double-double-double-int-int-boolean-) | नए इंस्टेंस को इनिशियलाइज़ करता है [Cylinder](../../com.aspose.threed/cylinder) क्लास का। |
| [Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)](#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-) | नए इंस्टेंस को इनिशियलाइज़ करता है [Cylinder](../../com.aspose.threed/cylinder) क्लास का। |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getBoundingBox()](#getBoundingBox--) | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कॉर्डिनेट सिस्टम में प्राप्त करता है। |
| [getCastShadows()](#getCastShadows--) | यह जियोमेट्री छाया डाल सकती है या नहीं प्राप्त करता है |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [getExcluded()](#getExcluded--) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में प्राप्त करता है। |
| [getGenerateFanCylinder()](#getGenerateFanCylinder--) | पाता है कि ThetaLength 2\*PI से कम होने पर फैन-स्टाइल सिलिंडर जनरेट करना है या नहीं, अन्यथा मॉडल नहीं कटेगा। |
| [getHeight()](#getHeight--) | सिलिंडर की ऊँचाई प्राप्त करता है। |
| [getHeightSegments()](#getHeightSegments--) | ऊँचाई सेगमेंट प्राप्त करता है। |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getOffsetBottom()](#getOffsetBottom--) | निचले पक्ष के वर्टिसेज़ ट्रांसफ़ॉर्मेशन ऑफ़सेट प्राप्त करता है। |
| [getOffsetTop()](#getOffsetTop--) | ऊपरी पक्ष के वर्टिसेज़ ट्रांसफ़ॉर्मेशन ऑफ़सेट प्राप्त करता है। |
| [getOpenEnded()](#getOpenEnded--) | एक मान प्राप्त करता है जो दर्शाता है कि यह [Cylinder](../../com.aspose.threed/cylinder) खुला है या नहीं। |
| [getParentNode()](#getParentNode--) | पहला पैरेंट नोड प्राप्त करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [getParentNodes()](#getParentNodes--) | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जुड़ी हो सकती है |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getRadialSegments()](#getRadialSegments--) | रेडियल सेगमेंट्स प्राप्त करता है। |
| [getRadiusBottom()](#getRadiusBottom--) | सिलिंडर के निचले कैप का त्रिज्या प्राप्त करता है। |
| [getRadiusTop()](#getRadiusTop--) | सिलिंडर के शीर्ष कैप की त्रिज्या प्राप्त करता है। |
| [getReceiveShadows()](#getReceiveShadows--) | यह जियोमेट्री छाया प्राप्त कर सकती है या नहीं प्राप्त करता है। |
| [getScene()](#getScene--) | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [getShearBottom()](#getShearBottom--) | निचले पक्ष के शीयर ट्रांसफ़ॉर्म को प्राप्त करता है, वेक्टर (x-अक्ष, z-अक्ष) शीयर मान को संग्रहीत करता है जो रेडियन में मापा जाता है, डिफ़ॉल्ट मान (0, 0) है। |
| [getShearTop()](#getShearTop--) | ऊपरी पक्ष के शीयर ट्रांसफ़ॉर्म को प्राप्त करता है, वेक्टर (x-अक्ष, z-अक्ष) शीयर मान को संग्रहीत करता है जो रेडियन में मापा जाता है, डिफ़ॉल्ट मान (0, 0) है। |
| [getThetaLength()](#getThetaLength--) | थीटा की लंबाई प्राप्त करता है। |
| [getThetaStart()](#getThetaStart--) | थीटा की शुरुआत प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | यह जियोमेट्री छाया डाल सकती है या नहीं सेट करता है |
| [setExcluded(boolean value)](#setExcluded-boolean-) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में सेट करता है। |
| [setGenerateFanCylinder(boolean value)](#setGenerateFanCylinder-boolean-) | जब ThetaLength 2\*PI से कम हो तो फैन-स्टाइल सिलिंडर उत्पन्न करना है या नहीं सेट करता है, अन्यथा मॉडल नहीं कटेगा। |
| [setHeight(double value)](#setHeight-double-) | सिलिंडर की ऊँचाई सेट करता है। |
| [setHeightSegments(int value)](#setHeightSegments-int-) | ऊँचाई खंड सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setOffsetBottom(Vector3 value)](#setOffsetBottom-com.aspose.threed.Vector3-) | निचले पक्ष के वर्टिसेज़ ट्रांसफ़ॉर्मेशन ऑफ़सेट को सेट करता है। |
| [setOffsetTop(Vector3 value)](#setOffsetTop-com.aspose.threed.Vector3-) | ऊपरी पक्ष के वर्टिसेज़ ट्रांसफ़ॉर्मेशन ऑफ़सेट को सेट करता है। |
| [setOpenEnded(boolean value)](#setOpenEnded-boolean-) | यह दर्शाने के लिए मान सेट करता है कि यह [Cylinder](../../com.aspose.threed/cylinder) खुला है या नहीं। |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | पहला पैरेंट नोड सेट करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setRadialSegments(int value)](#setRadialSegments-int-) | रेडियल सेगमेंट्स सेट करता है। |
| [setRadiusBottom(double value)](#setRadiusBottom-double-) | सिलिंडर के निचले कैप की त्रिज्या सेट करता है। |
| [setRadiusTop(double value)](#setRadiusTop-double-) | सिलिंडर के शीर्ष कैप की त्रिज्या सेट करता है। |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | यह जियोमेट्री छाया प्राप्त कर सकती है या नहीं सेट करता है। |
| [setShearBottom(Vector2 value)](#setShearBottom-com.aspose.threed.Vector2-) | निचले पक्ष के शीयर ट्रांसफ़ॉर्म को सेट करता है, वेक्टर (x-अक्ष, z-अक्ष) शीयर मान को संग्रहीत करता है जो रेडियन में मापा जाता है, डिफ़ॉल्ट मान (0, 0) है। |
| [setShearTop(Vector2 value)](#setShearTop-com.aspose.threed.Vector2-) | ऊपरी पक्ष के शीयर ट्रांसफ़ॉर्म को सेट करता है, वेक्टर (x-अक्ष, z-अक्ष) शीयर मान को संग्रहीत करता है जो रेडियन में मापा जाता है, डिफ़ॉल्ट मान (0, 0) है। |
| [setThetaLength(double value)](#setThetaLength-double-) | थीटा की लंबाई सेट करता है। |
| [setThetaStart(double value)](#setThetaStart-double-) | थीटा प्रारंभ सेट करता है। |
| [toMesh()](#toMesh--) | वर्तमान ऑब्जेक्ट को मेष में परिवर्तित करें |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Cylinder() {#Cylinder--}
```
public Cylinder()
```


नए इंस्टेंस को इनिशियलाइज़ करता है [Cylinder](../../com.aspose.threed/cylinder) क्लास का।

### Cylinder(double radius, double height) {#Cylinder-double-double-}
```
public Cylinder(double radius, double height)
```


नए इंस्टेंस को इनिशियलाइज़ करता है [Cylinder](../../com.aspose.threed/cylinder) क्लास का।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| त्रिज्या | double | शीर्ष और निचले कैप की त्रिज्या। |
| ऊँचाई | double | ऊँचाई। |

### Cylinder(double radiusTop, double radiusBottom, double height) {#Cylinder-double-double-double-}
```
public Cylinder(double radiusTop, double radiusBottom, double height)
```


नए इंस्टेंस को इनिशियलाइज़ करता है [Cylinder](../../com.aspose.threed/cylinder) क्लास का।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| radiusTop | double | शीर्ष त्रिज्या। |
| radiusBottom | double | निचली त्रिज्या। |
| ऊँचाई | double | ऊँचाई। |

### Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded) {#Cylinder-double-double-double-int-int-boolean-}
```
public Cylinder(double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded)
```


नए इंस्टेंस को इनिशियलाइज़ करता है [Cylinder](../../com.aspose.threed/cylinder) क्लास का।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| radiusTop | double | सिलिंडर के शीर्ष कैप की त्रिज्या। |
| radiusBottom | double | सिलिंडर के निचले कैप की त्रिज्या। |
| ऊँचाई | double | सिलिंडर की ऊँचाई। |
| radialSegments | int | ऊपरी और निचले दोनों वृत्तों के रेडियल सेगमेंट्स.. |
| heightSegments | int | ऊँचाई खंड। |
| openEnded | boolean | यदि इसे  true  पर सेट किया जाए तो सिलेंडर में निचला/ऊपरी कैप नहीं होगा.. |

### Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength) {#Cylinder-java.lang.String-double-double-double-int-int-boolean-double-double-}
```
public Cylinder(String name, double radiusTop, double radiusBottom, double height, int radialSegments, int heightSegments, boolean openEnded, double thetaStart, double thetaLength)
```


नए इंस्टेंस को इनिशियलाइज़ करता है [Cylinder](../../com.aspose.threed/cylinder) क्लास का।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | इस ऑब्जेक्ट का नाम |
| radiusTop | double | सिलिंडर के शीर्ष कैप की त्रिज्या। |
| radiusBottom | double | सिलिंडर के निचले कैप की त्रिज्या। |
| ऊँचाई | double | सिलिंडर की ऊँचाई। |
| radialSegments | int | ऊपरी और निचले दोनों वृत्तों के रेडियल सेगमेंट्स.. |
| heightSegments | int | ऊँचाई खंड। |
| openEnded | boolean | यदि इसे  true  पर सेट किया जाए तो सिलेंडर में निचला/ऊपरी कैप नहीं होगा.. |
| thetaStart | double | थीटा प्रारंभ। |
| thetaLength | double | थीटा लंबाई। |

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
### getGenerateFanCylinder() {#getGenerateFanCylinder--}
```
public boolean getGenerateFanCylinder()
```


पाता है कि ThetaLength 2\*PI से कम होने पर फैन-स्टाइल सिलिंडर जनरेट करना है या नहीं, अन्यथा मॉडल नहीं कटेगा।

**Returns:**
बूलियन - जब ThetaLength 2\*PI से कम हो तो फैन-स्टाइल सिलेंडर बनाना है या नहीं, अन्यथा मॉडल नहीं कटेगा।
### getHeight() {#getHeight--}
```
public double getHeight()
```


सिलिंडर की ऊँचाई प्राप्त करता है।

**Returns:**
डबल - सिलेंडर की ऊँचाई।
### getHeightSegments() {#getHeightSegments--}
```
public int getHeightSegments()
```


ऊँचाई सेगमेंट प्राप्त करता है।

**Returns:**
int - ऊँचाई खंड।
### getName() {#getName--}
```
public String getName()
```


नाम प्राप्त करता है।

**Returns:**
java.lang.String - नाम।
### getOffsetBottom() {#getOffsetBottom--}
```
public Vector3 getOffsetBottom()
```


निचले पक्ष के वर्टिसेज़ ट्रांसफ़ॉर्मेशन ऑफ़सेट प्राप्त करता है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the bottom side.
### getOffsetTop() {#getOffsetTop--}
```
public Vector3 getOffsetTop()
```


ऊपरी पक्ष के वर्टिसेज़ ट्रांसफ़ॉर्मेशन ऑफ़सेट प्राप्त करता है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the vertices transformation offset of the top side.
### getOpenEnded() {#getOpenEnded--}
```
public boolean getOpenEnded()
```


एक मान प्राप्त करता है जो दर्शाता है कि यह [Cylinder](../../com.aspose.threed/cylinder) खुला है या नहीं। डिफ़ॉल्ट मान false है।

**Returns:**
बूलियन - एक मान जो दर्शाता है कि यह [Cylinder](../../com.aspose.threed/cylinder) खुला है या नहीं। डिफ़ॉल्ट मान false है।
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


रेडियल सेगमेंट्स प्राप्त करता है।

**Returns:**
इंट - रेडियल सेगमेंट।
### getRadiusBottom() {#getRadiusBottom--}
```
public double getRadiusBottom()
```


सिलिंडर के निचले कैप का त्रिज्या प्राप्त करता है।

**Returns:**
डबल - सिलेंडर के निचले कैप की त्रिज्या।
### getRadiusTop() {#getRadiusTop--}
```
public double getRadiusTop()
```


सिलिंडर के शीर्ष कैप की त्रिज्या प्राप्त करता है।

**Returns:**
डबल - सिलेंडर के ऊपरी कैप की त्रिज्या।
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
### getShearBottom() {#getShearBottom--}
```
public Vector2 getShearBottom()
```


निचले पक्ष के शीयर ट्रांसफ़ॉर्म को प्राप्त करता है, वेक्टर (x-अक्ष, z-अक्ष) शीयर मान को संग्रहीत करता है जो रेडियन में मापा जाता है, डिफ़ॉल्ट मान (0, 0) है।

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the bottom side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getShearTop() {#getShearTop--}
```
public Vector2 getShearTop()
```


ऊपरी पक्ष के शीयर ट्रांसफ़ॉर्म को प्राप्त करता है, वेक्टर (x-अक्ष, z-अक्ष) शीयर मान को संग्रहीत करता है जो रेडियन में मापा जाता है, डिफ़ॉल्ट मान (0, 0) है।

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - of the shear transform of the top side, vector stores the (x-axis, z-axis) shear value that measured in radian, default value is (0, 0)
### getThetaLength() {#getThetaLength--}
```
public double getThetaLength()
```


थेटा की लंबाई प्राप्त करता है। डिफ़ॉल्ट मान 2\\u03c0 है।

**Returns:**
डबल - थेटा की लंबाई। डिफ़ॉल्ट मान 2\\u03c0 है।
### getThetaStart() {#getThetaStart--}
```
public double getThetaStart()
```


थेटा की शुरुआत प्राप्त करता है। डिफ़ॉल्ट मान 0 है।

**Returns:**
डबल - थेटा की शुरुआत। डिफ़ॉल्ट मान 0 है।
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

### setGenerateFanCylinder(boolean value) {#setGenerateFanCylinder-boolean-}
```
public void setGenerateFanCylinder(boolean value)
```


जब ThetaLength 2\*PI से कम हो तो फैन-स्टाइल सिलिंडर उत्पन्न करना है या नहीं सेट करता है, अन्यथा मॉडल नहीं कटेगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


सिलिंडर की ऊँचाई सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setHeightSegments(int value) {#setHeightSegments-int-}
```
public void setHeightSegments(int value)
```


ऊँचाई खंड सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


नाम सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setOffsetBottom(Vector3 value) {#setOffsetBottom-com.aspose.threed.Vector3-}
```
public void setOffsetBottom(Vector3 value)
```


निचले पक्ष के वर्टिसेज़ ट्रांसफ़ॉर्मेशन ऑफ़सेट को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setOffsetTop(Vector3 value) {#setOffsetTop-com.aspose.threed.Vector3-}
```
public void setOffsetTop(Vector3 value)
```


ऊपरी पक्ष के वर्टिसेज़ ट्रांसफ़ॉर्मेशन ऑफ़सेट को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setOpenEnded(boolean value) {#setOpenEnded-boolean-}
```
public void setOpenEnded(boolean value)
```


एक मान सेट करता है जो दर्शाता है कि यह [Cylinder](../../com.aspose.threed/cylinder) खुला है या नहीं। डिफ़ॉल्ट मान false है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

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


रेडियल सेगमेंट्स सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setRadiusBottom(double value) {#setRadiusBottom-double-}
```
public void setRadiusBottom(double value)
```


सिलिंडर के निचले कैप की त्रिज्या सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setRadiusTop(double value) {#setRadiusTop-double-}
```
public void setRadiusTop(double value)
```


सिलिंडर के शीर्ष कैप की त्रिज्या सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


यह जियोमेट्री छाया प्राप्त कर सकती है या नहीं सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setShearBottom(Vector2 value) {#setShearBottom-com.aspose.threed.Vector2-}
```
public void setShearBottom(Vector2 value)
```


निचले पक्ष के शीयर ट्रांसफ़ॉर्म को सेट करता है, वेक्टर (x-अक्ष, z-अक्ष) शीयर मान को संग्रहीत करता है जो रेडियन में मापा जाता है, डिफ़ॉल्ट मान (0, 0) है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | नया मान |

### setShearTop(Vector2 value) {#setShearTop-com.aspose.threed.Vector2-}
```
public void setShearTop(Vector2 value)
```


ऊपरी पक्ष के शीयर ट्रांसफ़ॉर्म को सेट करता है, वेक्टर (x-अक्ष, z-अक्ष) शीयर मान को संग्रहीत करता है जो रेडियन में मापा जाता है, डिफ़ॉल्ट मान (0, 0) है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | नया मान |

### setThetaLength(double value) {#setThetaLength-double-}
```
public void setThetaLength(double value)
```


थेटा की लंबाई सेट करता है। डिफ़ॉल्ट मान 2\\u03c0 है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setThetaStart(double value) {#setThetaStart-double-}
```
public void setThetaStart(double value)
```


थेटा की शुरुआत सेट करता है। डिफ़ॉल्ट मान 0 है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

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

