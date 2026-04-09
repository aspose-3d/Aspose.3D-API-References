---
title: Pose
second_title: Aspose.3D for Java API Reference
description: जियोमेट्री स्किन्ड होने पर ट्रांसफ़ॉर्मेशन मैट्रिक्स को स्टोर करने के लिए पोज़ का उपयोग किया जाता है।
type: docs
weight: 135
url: /hi/java/com.aspose.threed/pose/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Pose extends A3DObject
```

पोज़ का उपयोग तब परिवर्तन मैट्रिक्स संग्रहीत करने के लिए किया जाता है जब ज्यामिति स्किन की गई हो। पोज़ एक सेट है [BonePose](../../com.aspose.threed/bonepose) का, प्रत्येक [BonePose](../../com.aspose.threed/bonepose) हड्डी नोड की ठोस परिवर्तन जानकारी सहेजता है.
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Pose(String name)](#Pose-java.lang.String-) | एक नया उदाहरण प्रारंभ करता है [Pose](../../com.aspose.threed/pose) क्लास का. |
| [Pose()](#Pose--) | एक नया उदाहरण प्रारंभ करता है [Pose](../../com.aspose.threed/pose) क्लास का. |
## Methods

| Method | विवरण |
| --- | --- |
| [addBonePose(Node node, Matrix4 matrix)](#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-) | दिए गए हड्डी नोड के लिए पोज़ परिवर्तन मैट्रिक्स सहेजता है. |
| [addBonePose(Node node, Matrix4 matrix, boolean localMatrix)](#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-boolean-) | दिए गए हड्डी नोड के लिए पोज़ परिवर्तन मैट्रिक्स सहेजता है. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getBonePoses()](#getBonePoses--) | सभी [BonePose](../../com.aspose.threed/bonepose) प्राप्त करता है. |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getPoseType()](#getPoseType--) | पोज़ का प्रकार प्राप्त करता है. |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setPoseType(PoseType value)](#setPoseType-com.aspose.threed.PoseType-) | पोज़ का प्रकार सेट करता है. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pose(String name) {#Pose-java.lang.String-}
```
public Pose(String name)
```


एक नया उदाहरण प्रारंभ करता है [Pose](../../com.aspose.threed/pose) क्लास का.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | नाम |

### Pose() {#Pose--}
```
public Pose()
```


एक नया उदाहरण प्रारंभ करता है [Pose](../../com.aspose.threed/pose) क्लास का.

### addBonePose(Node node, Matrix4 matrix) {#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-}
```
public void addBonePose(Node node, Matrix4 matrix)
```


Saves pose transformation matrix for the given bone node. Global transformation matrix is implied.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Bone Node. |
| matrix | [Matrix4](../../com.aspose.threed/matrix4) | Transformation matrix. |

### addBonePose(Node node, Matrix4 matrix, boolean localMatrix) {#addBonePose-com.aspose.threed.Node-com.aspose.threed.Matrix4-boolean-}
```
public void addBonePose(Node node, Matrix4 matrix, boolean localMatrix)
```


दिए गए हड्डी नोड के लिए पोज़ परिवर्तन मैट्रिक्स सहेजता है.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Bone Node. |
| matrix | [Matrix4](../../com.aspose.threed/matrix4) | Transformation matrix. |
| localMatrix | boolean | If set to  true  means to use local matrix otherwise means global matrix. |

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
### getBonePoses() {#getBonePoses--}
```
public List<BonePose> getBonePoses()
```


सभी [BonePose](../../com.aspose.threed/bonepose) प्राप्त करता है.

**Returns:**
java.util.List<com.aspose.threed.BonePose> - all [BonePose](../../com.aspose.threed/bonepose).
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName() {#getName--}
```
public String getName()
```


नाम प्राप्त करता है।

**Returns:**
java.lang.String - नाम।
### getPoseType() {#getPoseType--}
```
public PoseType getPoseType()
```


पोज़ का प्रकार प्राप्त करता है.

**Returns:**
[PoseType](../../com.aspose.threed/posetype) - the type of the pose.
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
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


नाम सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setPoseType(PoseType value) {#setPoseType-com.aspose.threed.PoseType-}
```
public void setPoseType(PoseType value)
```


पोज़ का प्रकार सेट करता है.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [PoseType](../../com.aspose.threed/posetype) | नया मान |

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

