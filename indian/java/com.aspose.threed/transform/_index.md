---
title: ट्रांसफ़ॉर्म
second_title: Aspose.3D for Java API Reference
description: एक ट्रांसफ़ॉर्म में ऐसी जानकारी होती है जो वस्तुओं के ट्रांसलेट/स्केल/रोटेशन या ट्रांसफ़ॉर्म मैट्रिक्स तक न्यूनतम लागत पर पहुँच प्रदान करती है। यह स्थानीय ट्रांसफ़ॉर्म द्वारा उपयोग किया जाता है।
type: docs
weight: 190
url: /hi/java/com.aspose.threed/transform/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Transform extends A3DObject
```

एक ट्रांसफ़ॉर्म में ऐसी जानकारी होती है जो ऑब्जेक्ट के ट्रांसलेट/स्केल/रोटेशन या ट्रांसफ़ॉर्म मैट्रिक्स तक न्यूनतम लागत पर पहुँच प्रदान करती है। यह स्थानीय ट्रांसफ़ॉर्म द्वारा उपयोग किया जाता है। **Example:** निम्नलिखित कोड दिखाता है कि नोड का ट्रांसफ़ॉर्म कैसे बदलें:

```
Scene scene = new Scene();
     var boxNode = scene.getRootNode().createChildNode(new Box());
     //place the box at (10, 0, 0)
     boxNode.getTransform().setTranslation(new Vector3(10, 0, 0));
```
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getClass()](#getClass--) |  |
| [getEulerAngles()](#getEulerAngles--) | Euler कोणों में प्रदर्शित रोटेशन प्राप्त करता है, डिग्री में मापा गया |
| [getGeometricRotation()](#getGeometricRotation--) | ज्यामितीय यूलेर घूर्णन (डिग्री में मापा) प्राप्त करता है। |
| [getGeometricScaling()](#getGeometricScaling--) | ज्यामितीय स्केलिंग प्राप्त करता है। |
| [getGeometricTranslation()](#getGeometricTranslation--) | ज्यामितीय ट्रांसलेशन प्राप्त करता है। |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getPostRotation()](#getPostRotation--) | डिग्री में दर्शाए गए पोस्ट-रोटेशन को प्राप्त करता है |
| [getPreRotation()](#getPreRotation--) | डिग्री में दर्शाए गए प्री-रोटेशन को प्राप्त करता है |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getRotation()](#getRotation--) | क्वाटरनियन में प्रदर्शित रोटेशन प्राप्त करता है। |
| [getRotationOffset()](#getRotationOffset--) | रोटेशन ऑफ़सेट प्राप्त करता है |
| [getRotationPivot()](#getRotationPivot--) | रोटेशन पिवट प्राप्त करता है |
| [getScaling()](#getScaling--) | स्केलिंग प्राप्त करता है |
| [getScalingOffset()](#getScalingOffset--) | स्केलिंग ऑफसेट प्राप्त करता है |
| [getScalingPivot()](#getScalingPivot--) | स्केलिंग पिवट प्राप्त करता है |
| [getTransformMatrix()](#getTransformMatrix--) | ट्रांसफ़ॉर्म मैट्रिक्स प्राप्त करता है। |
| [getTranslation()](#getTranslation--) | ट्रांसलेशन प्राप्त करता है |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setEulerAngles(Vector3 value)](#setEulerAngles-com.aspose.threed.Vector3-) | डिग्री में मापे गए यूलेर कोणों में दर्शाए गए रोटेशन को सेट करता है |
| [setEulerAngles(double rx, double ry, double rz)](#setEulerAngles-double-double-double-) | वर्तमान ट्रांसफ़ॉर्म के डिग्री में यूलेर कोणों को सेट करता है। |
| [setGeometricRotation(Vector3 value)](#setGeometricRotation-com.aspose.threed.Vector3-) | ज्यामितीय यूलेर रोटेशन (डिग्री में मापा गया) को सेट करता है। |
| [setGeometricRotation(double rx, double ry, double rz)](#setGeometricRotation-double-double-double-) | ज्यामितीय यूलेर रोटेशन (डिग्री में मापा गया) को सेट करता है। |
| [setGeometricScaling(Vector3 value)](#setGeometricScaling-com.aspose.threed.Vector3-) | ज्यामितीय स्केलिंग को सेट करता है। |
| [setGeometricScaling(double sx, double sy, double sz)](#setGeometricScaling-double-double-double-) | ज्यामितीय स्केलिंग को सेट करता है। |
| [setGeometricTranslation(Vector3 value)](#setGeometricTranslation-com.aspose.threed.Vector3-) | ज्यामितीय ट्रांसलेशन को सेट करता है। |
| [setGeometricTranslation(double x, double y, double z)](#setGeometricTranslation-double-double-double-) | ज्यामितीय ट्रांसलेशन को सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setPostRotation(Vector3 value)](#setPostRotation-com.aspose.threed.Vector3-) | डिग्री में दर्शाए गए पोस्ट-रोटेशन को सेट करता है |
| [setPostRotation(double rx, double ry, double rz)](#setPostRotation-double-double-double-) | डिग्री में दर्शाए गए पोस्ट-रोटेशन को सेट करता है **Example:** |
| [setPreRotation(Vector3 value)](#setPreRotation-com.aspose.threed.Vector3-) | डिग्री में दर्शाए गए प्री-रोटेशन को सेट करता है |
| [setPreRotation(double rx, double ry, double rz)](#setPreRotation-double-double-double-) | डिग्री में दर्शाए गए प्री-रोटेशन को सेट करता है **Example:** |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setRotation(Quaternion value)](#setRotation-com.aspose.threed.Quaternion-) | क्वाटरनियन में दर्शाए गए रोटेशन को सेट करता है। |
| [setRotation(double rw, double rx, double ry, double rz)](#setRotation-double-double-double-double-) | वर्तमान ट्रांसफ़ॉर्म का रोटेशन (क्वाटरनियन घटकों के रूप में) को सेट करता है। |
| [setRotationOffset(Vector3 value)](#setRotationOffset-com.aspose.threed.Vector3-) | रोटेशन ऑफसेट को सेट करता है |
| [setRotationPivot(Vector3 value)](#setRotationPivot-com.aspose.threed.Vector3-) | रोटेशन पिवट को सेट करता है |
| [setScale(double sx, double sy, double sz)](#setScale-double-double-double-) | वर्तमान ट्रांसफ़ॉर्म का स्केल सेट करता है। |
| [setScaling(Vector3 value)](#setScaling-com.aspose.threed.Vector3-) | स्केलिंग को सेट करता है |
| [setScalingOffset(Vector3 value)](#setScalingOffset-com.aspose.threed.Vector3-) | स्केलिंग ऑफसेट को सेट करता है |
| [setScalingPivot(Vector3 value)](#setScalingPivot-com.aspose.threed.Vector3-) | स्केलिंग पिवट को सेट करता है |
| [setTransformMatrix(Matrix4 value)](#setTransformMatrix-com.aspose.threed.Matrix4-) | ट्रांसफ़ॉर्म मैट्रिक्स को सेट करता है। |
| [setTranslation(Vector3 value)](#setTranslation-com.aspose.threed.Vector3-) | ट्रांसलेशन को सेट करता है |
| [setTranslation(double tx, double ty, double tz)](#setTranslation-double-double-double-) | वर्तमान ट्रांसफ़ॉर्म का ट्रांसलेशन सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEulerAngles() {#getEulerAngles--}
```
public Vector3 getEulerAngles()
```


Euler कोणों में प्रदर्शित रोटेशन प्राप्त करता है, डिग्री में मापा गया

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation represented in Euler angles, measured in degree **Example:**

```
Node node = new Node();
     node.getTransform().setEulerAngles(new Vector3(90, 0, 0));
```
### getGeometricRotation() {#getGeometricRotation--}
```
public Vector3 getGeometricRotation()
```


ज्यामितीय यूलेर रोटेशन (डिग्री में मापा गया) प्राप्त करता है। ज्यामितीय ट्रांसफ़ॉर्मेशन केवल जुड़े हुए एंटिटीज़ को प्रभावित करता है और चाइल्ड नोड्स को अपरिवर्तित छोड़ता है। जब आप ज्यामितीय ट्रांसफ़ॉर्मेशन को उन फ़ाइल प्रकारों में निर्यात करते हैं जो इसे समर्थन नहीं करते, तो यह स्थानीय ट्रांसफ़ॉर्मेशन के रूप में मर्ज हो जाएगा।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric Euler rotation(measured in degree). Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it.
### getGeometricScaling() {#getGeometricScaling--}
```
public Vector3 getGeometricScaling()
```


जियोमेट्रिक स्केलिंग प्राप्त करता है। जियोमेट्रिक ट्रांसफ़ॉर्मेशन केवल संलग्न इकाइयों को प्रभावित करता है और चाइल्ड नोड्स को अपरिवर्तित छोड़ता है। जब आप जियोमेट्रिक ट्रांसफ़ॉर्मेशन को उन फ़ाइल प्रकारों में निर्यात करते हैं जो इसे समर्थन नहीं करते, तो यह स्थानीय ट्रांसफ़ॉर्मेशन के रूप में मिलाया जाएगा।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric scaling. Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it. **Example:**

```
Node node = new Node();
     node.getTransform.setGeometricScaling(new Vector3(2, 2, 2));
```
### getGeometricTranslation() {#getGeometricTranslation--}
```
public Vector3 getGeometricTranslation()
```


जियोमेट्रिक ट्रांसलेशन प्राप्त करता है। जियोमेट्रिक ट्रांसफ़ॉर्मेशन केवल संलग्न इकाइयों को प्रभावित करता है और चाइल्ड नोड्स को अपरिवर्तित छोड़ता है। जब आप जियोमेट्रिक ट्रांसफ़ॉर्मेशन को उन फ़ाइल प्रकारों में निर्यात करते हैं जो इसे समर्थन नहीं करते, तो यह स्थानीय ट्रांसफ़ॉर्मेशन के रूप में मिलाया जाएगा।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the geometric translation. Geometric transformation only affects the entities attached and leave the child nodes unaffected. It will be merged as local transformation when you export the geometric transformation to file types that does not support it. **Example:**

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(new Vector3(10, 0, 0));
```
### getName() {#getName--}
```
public String getName()
```


नाम प्राप्त करता है।

**Returns:**
java.lang.String - नाम।
### getPostRotation() {#getPostRotation--}
```
public Vector3 getPostRotation()
```


डिग्री में दर्शाए गए पोस्ट-रोटेशन को प्राप्त करता है

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the post-rotation represented in degree **Example:**

```
Node node = new Node();
     node.getTransform().setPostRotation(new Vector3(90, 0, 0));
```
### getPreRotation() {#getPreRotation--}
```
public Vector3 getPreRotation()
```


डिग्री में दर्शाए गए प्री-रोटेशन को प्राप्त करता है

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the pre-rotation represented in degree **Example:**

```
Node node = new Node();
     node.getTransform().setPreRotation(new Vector3(90, 0, 0));
```
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
### getRotation() {#getRotation--}
```
public Quaternion getRotation()
```


क्वाटरनियन में प्रदर्शित रोटेशन प्राप्त करता है।

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - the rotation represented in quaternion. **Example:**

```
Node node = new Node();
     node.getTransform().setRotation(new Quaternion(1, 0, 0, 0));
```
### getRotationOffset() {#getRotationOffset--}
```
public Vector3 getRotationOffset()
```


रोटेशन ऑफ़सेट प्राप्त करता है

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation offset
### getRotationPivot() {#getRotationPivot--}
```
public Vector3 getRotationPivot()
```


रोटेशन पिवट प्राप्त करता है

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation pivot
### getScaling() {#getScaling--}
```
public Vector3 getScaling()
```


स्केलिंग प्राप्त करता है

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling **Example:**

```
Node node = new Node();
     node.getTransform().setScaling(new Vector3(2, 2, 2));
```
### getScalingOffset() {#getScalingOffset--}
```
public Vector3 getScalingOffset()
```


स्केलिंग ऑफसेट प्राप्त करता है

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling offset
### getScalingPivot() {#getScalingPivot--}
```
public Vector3 getScalingPivot()
```


स्केलिंग पिवट प्राप्त करता है

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the scaling pivot
### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix4 getTransformMatrix()
```


ट्रांसफ़ॉर्म मैट्रिक्स प्राप्त करता है।

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix. **Remarks:** Assign on this will reset the [getTranslation](../../com.aspose.threed/transform\#getTranslation), [getScaling](../../com.aspose.threed/transform\#getScaling) and [getRotation](../../com.aspose.threed/transform\#getRotation), the [getGeometricRotation](../../com.aspose.threed/transform\#getGeometricRotation), [getGeometricScaling](../../com.aspose.threed/transform\#getGeometricScaling) and [getGeometricTranslation](../../com.aspose.threed/transform\#getGeometricTranslation) will not be affected. **Example:**

```
Node node = new Node();
     node.getTransform().setTransformMatrix(Matrix4.getIdentity());
```
### getTranslation() {#getTranslation--}
```
public Vector3 getTranslation()
```


ट्रांसलेशन प्राप्त करता है

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the translation **Example:**

```
Node node = new Node();
     node.getTransform().setTranslation(new Vector3(10, 0, 0));
```
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
### setEulerAngles(Vector3 value) {#setEulerAngles-com.aspose.threed.Vector3-}
```
public void setEulerAngles(Vector3 value)
```


डिग्री में मापे गए यूलेर कोणों में दर्शाए गए रोटेशन को सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | नई मान **Example:** |

```
Node node = new Node();
     node.getTransform().setEulerAngles(new Vector3(90, 0, 0));
``` |

### setEulerAngles(double rx, double ry, double rz) {#setEulerAngles-double-double-double-}
```
public Transform setEulerAngles(double rx, double ry, double rz)
```


वर्तमान ट्रांसफ़ॉर्म के डिग्री में यूलेर कोण सेट करता है। **Example:**

```
Node node = new Node();
     node.getTransform().setEulerAngles(90, 0, 0);
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setGeometricRotation(Vector3 value) {#setGeometricRotation-com.aspose.threed.Vector3-}
```
public void setGeometricRotation(Vector3 value)
```


जियोमेट्रिक यूलेर रोटेशन (डिग्री में मापा गया) सेट करता है। जियोमेट्रिक ट्रांसफ़ॉर्मेशन केवल संलग्न इकाइयों को प्रभावित करता है और चाइल्ड नोड्स को अपरिवर्तित छोड़ता है। जब आप जियोमेट्रिक ट्रांसफ़ॉर्मेशन को उन फ़ाइल प्रकारों में निर्यात करते हैं जो इसे समर्थन नहीं करते, तो यह स्थानीय ट्रांसफ़ॉर्मेशन के रूप में मिलाया जाएगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setGeometricRotation(double rx, double ry, double rz) {#setGeometricRotation-double-double-double-}
```
public Transform setGeometricRotation(double rx, double ry, double rz)
```


जियोमेट्रिक यूलेर रोटेशन (डिग्री में मापा गया) सेट करता है। जियोमेट्रिक ट्रांसफ़ॉर्मेशन केवल संलग्न इकाइयों को प्रभावित करता है और चाइल्ड नोड्स को अपरिवर्तित छोड़ता है। जब आप जियोमेट्रिक ट्रांसफ़ॉर्मेशन को उन फ़ाइल प्रकारों में निर्यात करते हैं जो इसे समर्थन नहीं करते, तो यह स्थानीय ट्रांसफ़ॉर्मेशन के रूप में मिलाया जाएगा। **Example:**

```
Node node = new Node();
     node.getTransform().setGeometricRotation(90, 0, 0);
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setGeometricScaling(Vector3 value) {#setGeometricScaling-com.aspose.threed.Vector3-}
```
public void setGeometricScaling(Vector3 value)
```


जियोमेट्रिक स्केलिंग सेट करता है। जियोमेट्रिक ट्रांसफ़ॉर्मेशन केवल संलग्न इकाइयों को प्रभावित करता है और चाइल्ड नोड्स को अपरिवर्तित छोड़ता है। जब आप जियोमेट्रिक ट्रांसफ़ॉर्मेशन को उन फ़ाइल प्रकारों में निर्यात करते हैं जो इसे समर्थन नहीं करते, तो यह स्थानीय ट्रांसफ़ॉर्मेशन के रूप में मिलाया जाएगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | नई मान **Example:** |

```
Node node = new Node();
     node.getTransform.setGeometricScaling(new Vector3(2, 2, 2));
``` |

### setGeometricScaling(double sx, double sy, double sz) {#setGeometricScaling-double-double-double-}
```
public Transform setGeometricScaling(double sx, double sy, double sz)
```


जियोमेट्रिक स्केलिंग सेट करता है। जियोमेट्रिक ट्रांसफ़ॉर्मेशन केवल संलग्न इकाइयों को प्रभावित करता है और चाइल्ड नोड्स को अपरिवर्तित छोड़ता है। जब आप जियोमेट्रिक ट्रांसफ़ॉर्मेशन को उन फ़ाइल प्रकारों में निर्यात करते हैं जो इसे समर्थन नहीं करते, तो यह स्थानीय ट्रांसफ़ॉर्मेशन के रूप में मिलाया जाएगा। **Example:**

```
Node node = new Node();
     node.getTransform().setGeometricScaling(2, 2, 2);
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| sx | double |  |
| sy | double |  |
| sz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setGeometricTranslation(Vector3 value) {#setGeometricTranslation-com.aspose.threed.Vector3-}
```
public void setGeometricTranslation(Vector3 value)
```


जियोमेट्रिक ट्रांसलेशन सेट करता है। जियोमेट्रिक ट्रांसफ़ॉर्मेशन केवल संलग्न इकाइयों को प्रभावित करता है और चाइल्ड नोड्स को अपरिवर्तित छोड़ता है। जब आप जियोमेट्रिक ट्रांसफ़ॉर्मेशन को उन फ़ाइल प्रकारों में निर्यात करते हैं जो इसे समर्थन नहीं करते, तो यह स्थानीय ट्रांसफ़ॉर्मेशन के रूप में मिलाया जाएगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | नई मान **Example:** |

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(new Vector3(10, 0, 0));
``` |

### setGeometricTranslation(double x, double y, double z) {#setGeometricTranslation-double-double-double-}
```
public Transform setGeometricTranslation(double x, double y, double z)
```


जियोमेट्रिक ट्रांसलेशन सेट करता है। जियोमेट्रिक ट्रांसफ़ॉर्मेशन केवल संलग्न इकाइयों को प्रभावित करता है और चाइल्ड नोड्स को अपरिवर्तित छोड़ता है। जब आप जियोमेट्रिक ट्रांसफ़ॉर्मेशन को उन फ़ाइल प्रकारों में निर्यात करते हैं जो इसे समर्थन नहीं करते, तो यह स्थानीय ट्रांसफ़ॉर्मेशन के रूप में मिलाया जाएगा। **Example:**

```
Node node = new Node();
     node.getTransform().setGeometricTranslation(10, 0, 0);
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| x | double |  |
| y | double |  |
| z | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


नाम सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setPostRotation(Vector3 value) {#setPostRotation-com.aspose.threed.Vector3-}
```
public void setPostRotation(Vector3 value)
```


डिग्री में दर्शाए गए पोस्ट-रोटेशन को सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | नई मान **Example:** |

```
Node node = new Node();
     node.getTransform().setPostRotation(new Vector3(90, 0, 0));
``` |

### setPostRotation(double rx, double ry, double rz) {#setPostRotation-double-double-double-}
```
public Transform setPostRotation(double rx, double ry, double rz)
```


डिग्री में दर्शाए गए पोस्ट-रोटेशन को सेट करता है **Example:**

```
Node node = new Node();
     node.getTransform().setPostRotation(90, 0, 0);
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setPreRotation(Vector3 value) {#setPreRotation-com.aspose.threed.Vector3-}
```
public void setPreRotation(Vector3 value)
```


डिग्री में दर्शाए गए प्री-रोटेशन को सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | नई मान **Example:** |

```
Node node = new Node();
     node.getTransform().setPreRotation(new Vector3(90, 0, 0));
``` |

### setPreRotation(double rx, double ry, double rz) {#setPreRotation-double-double-double-}
```
public Transform setPreRotation(double rx, double ry, double rz)
```


डिग्री में दर्शाए गए प्री-रोटेशन को सेट करता है **Example:**

```
Node node = new Node();
     node.getTransform().setPreRotation(90, 0, 0);
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
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

### setRotation(Quaternion value) {#setRotation-com.aspose.threed.Quaternion-}
```
public void setRotation(Quaternion value)
```


क्वाटरनियन में दर्शाए गए रोटेशन को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [Quaternion](../../com.aspose.threed/quaternion) | नई मान **Example:** |

```
Node node = new Node();
     node.getTransform().setRotation(new Quaternion(1, 0, 0, 0));
``` |

### setRotation(double rw, double rx, double ry, double rz) {#setRotation-double-double-double-double-}
```
public Transform setRotation(double rw, double rx, double ry, double rz)
```


वर्तमान ट्रांसफ़ॉर्म का रोटेशन (क्वाटरनियन घटकों के रूप में) सेट करता है। **Example:**

```
Node node = new Node();
     node.getTransform().setRotation(1, 0, 0, 0);
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| rw | double |  |
| rx | double |  |
| ry | double |  |
| rz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setRotationOffset(Vector3 value) {#setRotationOffset-com.aspose.threed.Vector3-}
```
public void setRotationOffset(Vector3 value)
```


रोटेशन ऑफसेट को सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setRotationPivot(Vector3 value) {#setRotationPivot-com.aspose.threed.Vector3-}
```
public void setRotationPivot(Vector3 value)
```


रोटेशन पिवट को सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setScale(double sx, double sy, double sz) {#setScale-double-double-double-}
```
public Transform setScale(double sx, double sy, double sz)
```


वर्तमान ट्रांसफ़ॉर्म का स्केल सेट करता है। **Example:**

```
Node node = new Node();
     node.getTransform().setScale(2, 2, 2);
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| sx | double |  |
| sy | double |  |
| sz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
### setScaling(Vector3 value) {#setScaling-com.aspose.threed.Vector3-}
```
public void setScaling(Vector3 value)
```


स्केलिंग को सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | नई मान **Example:** |

```
Node node = new Node();
     node.getTransform().setScaling(new Vector3(2, 2, 2));
``` |

### setScalingOffset(Vector3 value) {#setScalingOffset-com.aspose.threed.Vector3-}
```
public void setScalingOffset(Vector3 value)
```


स्केलिंग ऑफसेट को सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setScalingPivot(Vector3 value) {#setScalingPivot-com.aspose.threed.Vector3-}
```
public void setScalingPivot(Vector3 value)
```


स्केलिंग पिवट को सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setTransformMatrix(Matrix4 value) {#setTransformMatrix-com.aspose.threed.Matrix4-}
```
public void setTransformMatrix(Matrix4 value)
```


ट्रांसफ़ॉर्म मैट्रिक्स को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [Matrix4](../../com.aspose.threed/matrix4) | नया मान **Remarks:** इस पर असाइन करने से [getTranslation](../../com.aspose.threed/transform\#getTranslation), [getScaling](../../com.aspose.threed/transform\#getScaling) और [getRotation](../../com.aspose.threed/transform\#getRotation) रीसेट हो जाएंगे, जबकि [getGeometricRotation](../../com.aspose.threed/transform\#getGeometricRotation), [getGeometricScaling](../../com.aspose.threed/transform\#getGeometricScaling) और [getGeometricTranslation](../../com.aspose.threed/transform\#getGeometricTranslation) प्रभावित नहीं होंगे। **Example:** |

```
Node node = new Node();
     node.getTransform().setTransformMatrix(Matrix4.getIdentity());
``` |

### setTranslation(Vector3 value) {#setTranslation-com.aspose.threed.Vector3-}
```
public void setTranslation(Vector3 value)
```


ट्रांसलेशन को सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | नई मान **Example:** |

```
Node node = new Node();
     node.getTransform().setTranslation(new Vector3(10, 0, 0));
``` |

### setTranslation(double tx, double ty, double tz) {#setTranslation-double-double-double-}
```
public Transform setTranslation(double tx, double ty, double tz)
```


वर्तमान ट्रांसफ़ॉर्म का ट्रांसलेशन सेट करता है। **Example:**

```
Node node = new Node();
     node.getTransform().setTranslation(10, 0, 0);
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| tx | double |  |
| ty | double |  |
| tz | double |  |

**Returns:**
[Transform](../../com.aspose.threed/transform)
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

