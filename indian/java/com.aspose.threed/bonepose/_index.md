---
title: BonePose
second_title: Aspose.3D for Java API Reference
description: यह हड्डी नोड के लिए ट्रांसफ़ॉर्मेशन मैट्रिक्स रखता है
type: docs
weight: 21
url: /hi/java/com.aspose.threed/bonepose/
---

**Inheritance:**
java.lang.Object
```
public class BonePose
```

यह [BonePose](../../com.aspose.threed/bonepose) हड्डी नोड के लिए ट्रांसफ़ॉर्मेशन मैट्रिक्स रखता है
## Constructors

| Constructor | विवरण |
| --- | --- |
| [BonePose()](#BonePose--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMatrix()](#getMatrix--) | वर्तमान पोज़ में नोड का ट्रांसफ़ॉर्म मैट्रिक्स प्राप्त करता है। |
| [getNode()](#getNode--) | सीन नोड प्राप्त करता है, जो एक स्किन्ड स्केलेटन नोड की ओर इशारा करता है। |
| [hashCode()](#hashCode--) |  |
| [isLocal()](#isLocal--) | जाँचता है कि मैट्रिक्स स्थानीय निर्देशांक में परिभाषित है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLocal(boolean value)](#setLocal-boolean-) | सेट करता है कि मैट्रिक्स स्थानीय निर्देशांक में परिभाषित है या नहीं। |
| [setMatrix(Matrix4 value)](#setMatrix-com.aspose.threed.Matrix4-) | वर्तमान पोज़ में नोड का ट्रांसफ़ॉर्म मैट्रिक्स सेट करता है। |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | सीन नोड सेट करता है, जो एक स्किन्ड स्केलेटन नोड की ओर इशारा करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BonePose() {#BonePose--}
```
public BonePose()
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMatrix() {#getMatrix--}
```
public Matrix4 getMatrix()
```


वर्तमान पोज़ में नोड का ट्रांसफ़ॉर्म मैट्रिक्स प्राप्त करता है।

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the node in current pose.
### getNode() {#getNode--}
```
public Node getNode()
```


सीन नोड प्राप्त करता है, जो एक स्किन्ड स्केलेटन नोड की ओर इशारा करता है।

**Returns:**
[Node](../../com.aspose.threed/node) - the scene node, points to a skinned skeleton node
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLocal() {#isLocal--}
```
public boolean isLocal()
```


जाँचता है कि मैट्रिक्स स्थानीय निर्देशांक में परिभाषित है या नहीं।

**Returns:**
boolean - यदि मैट्रिक्स स्थानीय निर्देशांक में परिभाषित है।
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setLocal(boolean value) {#setLocal-boolean-}
```
public void setLocal(boolean value)
```


सेट करता है कि मैट्रिक्स स्थानीय निर्देशांक में परिभाषित है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setMatrix(Matrix4 value) {#setMatrix-com.aspose.threed.Matrix4-}
```
public void setMatrix(Matrix4 value)
```


वर्तमान पोज़ में नोड का ट्रांसफ़ॉर्म मैट्रिक्स सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | नया मान |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


सीन नोड सेट करता है, जो एक स्किन्ड स्केलेटन नोड की ओर इशारा करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | नया मान |

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

