---
title: BooleanOperand
second_title: Aspose.3D for Java API Reference
description: यह क्लास परिवर्तित मेष को बूलियन ऑपरेशन्स ऑपरेण्ड के रूप में संलग्न करती है।
type: docs
weight: 22
url: /hi/java/com.aspose.threed/booleanoperand/
---

**Inheritance:**
java.lang.Object
```
public class BooleanOperand
```

यह क्लास परिवर्तित मेष को बूलियन ऑपरेशन के ऑपरेण्ड के रूप में संलग्न करती है।
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOperand()](#getOperand--) | ऑपरेण्ड प्राप्त करता है, यह [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) या [Node](../../com.aspose.threed/node) का उदाहरण हो सकता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [of(Entity mesh)](#of-com.aspose.threed.Entity-) | एक बुनियादी [IMeshConvertible](../../com.aspose.threed/imeshconvertible) इंस्टेंस से एक [BooleanOperand](../../com.aspose.threed/booleanoperand) इंस्टेंस बनाएं। |
| [of(Entity mesh, Matrix4 transform)](#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-) | एक [IMeshConvertible](../../com.aspose.threed/imeshconvertible) इंस्टेंस और निर्दिष्ट ट्रांसफ़ॉर्म से एक [BooleanOperand](../../com.aspose.threed/booleanoperand) इंस्टेंस बनाएं। |
| [of(Node node)](#of-com.aspose.threed.Node-) | एक नोड से एक [BooleanOperand](../../com.aspose.threed/booleanoperand) इंस्टेंस बनाएं, एक वैध इकाई जो [IMeshConvertible](../../com.aspose.threed/imeshconvertible) को लागू करती है, आवश्यक है। |
| [toString()](#toString--) | [BooleanOperand](../../com.aspose.threed/booleanoperand) का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है। |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOperand() {#getOperand--}
```
public A3DObject getOperand()
```


ऑपरेण्ड प्राप्त करता है, यह [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) या [Node](../../com.aspose.threed/node) का उदाहरण हो सकता है।

**Returns:**
[A3DObject](../../com.aspose.threed/a3dobject) - the operand, it can be an instance of [HalfSpace](../../com.aspose.threed/halfspace), [IMeshConvertible](../../com.aspose.threed/imeshconvertible) or [Node](../../com.aspose.threed/node).
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




### of(Entity mesh) {#of-com.aspose.threed.Entity-}
```
public static BooleanOperand of(Entity mesh)
```


एक बुनियादी [IMeshConvertible](../../com.aspose.threed/imeshconvertible) इंस्टेंस से एक [BooleanOperand](../../com.aspose.threed/booleanoperand) इंस्टेंस बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | Boolean ऑपरेशन के ऑपरेण्ड के रूप में उपयोग किया जाने वाला मेष, यह [IMeshConvertible](../../com.aspose.threed/imeshconvertible) या [HalfSpace](../../com.aspose.threed/halfspace) का इंस्टेंस हो सकता है। |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Entity mesh, Matrix4 transform) {#of-com.aspose.threed.Entity-com.aspose.threed.Matrix4-}
```
public static BooleanOperand of(Entity mesh, Matrix4 transform)
```


एक [IMeshConvertible](../../com.aspose.threed/imeshconvertible) इंस्टेंस और निर्दिष्ट ट्रांसफ़ॉर्म से एक [BooleanOperand](../../com.aspose.threed/booleanoperand) इंस्टेंस बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| mesh | [Entity](../../com.aspose.threed/entity) | Boolean ऑपरेशन के ऑपरेण्ड के रूप में उपयोग किया जाने वाला मेष, यह [IMeshConvertible](../../com.aspose.threed/imeshconvertible) या [HalfSpace](../../com.aspose.threed/halfspace) का इंस्टेंस हो सकता है। |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | मे़ष ऑब्जेक्ट का ट्रांसफ़ॉर्म। |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### of(Node node) {#of-com.aspose.threed.Node-}
```
public static BooleanOperand of(Node node)
```


एक नोड से एक [BooleanOperand](../../com.aspose.threed/booleanoperand) इंस्टेंस बनाएं, एक वैध इकाई जो [IMeshConvertible](../../com.aspose.threed/imeshconvertible) को लागू करती है, आवश्यक है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | एक वैध इकाई जो [IMeshConvertible](../../com.aspose.threed/imeshconvertible) को लागू करती है, के साथ एक [Node](../../com.aspose.threed/node) इंस्टेंस। |

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - An instance of [BooleanOperand](../../com.aspose.threed/booleanoperand)
### toString() {#toString--}
```
public String toString()
```


[BooleanOperand](../../com.aspose.threed/booleanoperand) का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है।

**Returns:**
java.lang.String - [BooleanOperand](../../com.aspose.threed/booleanoperand) का स्ट्रिंग प्रतिनिधित्व
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

