---
title: TransformBuilder
second_title: Aspose.3D for Java API Reference
description: यह ट्रांसफ़ॉर्म मैट्रिक्स को एक श्रृंखला के ट्रांसफ़ॉर्मेशन द्वारा बनाने के लिए उपयोग किया जाता है।
type: docs
weight: 191
url: /hi/java/com.aspose.threed/transformbuilder/
---

**Inheritance:**
java.lang.Object
```
public class TransformBuilder
```

The [TransformBuilder](../../com.aspose.threed/transformbuilder) का उपयोग ट्रांसफ़ॉर्म मैट्रिक्स को एक श्रृंखला के ट्रांसफ़ॉर्मेशन द्वारा बनाने के लिए किया जाता है। **Example:** निम्नलिखित कोड दिखाता है कि कैसे एक सेट ऑपरेशन द्वारा मैट्रिक्स बनाया जाए

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(10, 20, 0);
     tb.scale(10, 10, 10);
     tb.rotateEulerDegree(90, 0, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [TransformBuilder(Matrix4 initial, ComposeOrder order)](#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-) | एक प्रारंभिक ट्रांसफ़ॉर्म मैट्रिक्स और निर्दिष्ट संयोजन क्रम के साथ एक [TransformBuilder](../../com.aspose.threed/transformbuilder) बनाएं |
| [TransformBuilder(ComposeOrder order)](#TransformBuilder-com.aspose.threed.ComposeOrder-) | एक प्रारंभिक आइडेंटिटी ट्रांसफ़ॉर्म मैट्रिक्स और निर्दिष्ट संयोजन क्रम के साथ एक [TransformBuilder](../../com.aspose.threed/transformbuilder) बनाएं |
| [TransformBuilder()](#TransformBuilder--) | एक प्रारंभिक आइडेंटिटी ट्रांसफ़ॉर्म मैट्रिक्स और निर्दिष्ट संयोजन क्रम के साथ एक [TransformBuilder](../../com.aspose.threed/transformbuilder) बनाएं |
## Methods

| Method | विवरण |
| --- | --- |
| [append(Matrix4 m)](#append-com.aspose.threed.Matrix4-) | नए ट्रांसफ़ॉर्म मैट्रिक्स को ट्रांसफ़ॉर्म श्रृंखला में जोड़ें। |
| [compose(Matrix4 m)](#compose-com.aspose.threed.Matrix4-) | आर्ग्यूमेंट को आंतरिक मैट्रिक्स में जोड़ें या पहले रखें। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComposeOrder()](#getComposeOrder--) | श्रृंखला के संयोजन क्रम को प्राप्त करता है। |
| [getMatrix()](#getMatrix--) | वर्तमान मैट्रिक्स मान प्राप्त करता है |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepend(Matrix4 m)](#prepend-com.aspose.threed.Matrix4-) | नए ट्रांसफ़ॉर्म मैट्रिक्स को ट्रांसफ़ॉर्म श्रृंखला की शुरुआत में रखें। |
| [rearrange(Axis newX, Axis newY, Axis newZ)](#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-) | अक्ष की लेआउट को पुनर्व्यवस्थित करें। |
| [reset()](#reset--) | ट्रांसफ़ॉर्म को आइडेंटिटी मैट्रिक्स पर रीसेट करें |
| [rotate(Quaternion q)](#rotate-com.aspose.threed.Quaternion-) | क्वाटरनियन द्वारा घूर्णन को श्रृंखलाबद्ध करें **Example:** |
| [rotateDegree(Vector3 rot, RotationOrder order)](#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | निर्दिष्ट क्रम के साथ घूर्णन जोड़ें |
| [rotateDegree(double angle, Vector3 axis)](#rotateDegree-double-com.aspose.threed.Vector3-) | डिग्री में घूर्णन रूपांतरण को श्रृंखलाबद्ध करें |
| [rotateEulerDegree(double degX, double degY, double degZ)](#rotateEulerDegree-double-double-double-) | डिग्री में यूलेर कोणों द्वारा घूर्णन को श्रृंखलाबद्ध करें **Example:** |
| [rotateEulerRadian(Vector3 r)](#rotateEulerRadian-com.aspose.threed.Vector3-) | रेडियन में यूलेर कोणों द्वारा घूर्णन को श्रृंखलाबद्ध करें **Example:** |
| [rotateEulerRadian(double x, double y, double z)](#rotateEulerRadian-double-double-double-) | रेडियन में यूलेर कोणों द्वारा घूर्णन को श्रृंखलाबद्ध करें **Example:** |
| [rotateRadian(Vector3 rot, RotationOrder order)](#rotateRadian-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-) | निर्दिष्ट क्रम के साथ घूर्णन जोड़ें |
| [rotateRadian(double angle, Vector3 axis)](#rotateRadian-double-com.aspose.threed.Vector3-) | रेडियन में घूर्णन रूपांतरण को श्रृंखलाबद्ध करें |
| [scale(Vector3 s)](#scale-com.aspose.threed.Vector3-) | स्केल रूपांतरण को श्रृंखलाबद्ध करें **Example:** |
| [scale(double s)](#scale-double-) | एक घटक को s द्वारा स्केल किए गए स्केलिंग रूपांतरण मैट्रिक्स को श्रृंखलाबद्ध करें **Example:** |
| [scale(double x, double y, double z)](#scale-double-double-double-) | स्केलिंग रूपांतरण मैट्रिक्स को श्रृंखलाबद्ध करें **Example:** |
| [setComposeOrder(ComposeOrder value)](#setComposeOrder-com.aspose.threed.ComposeOrder-) | श्रृंखला संयोजन क्रम सेट करता है। |
| [setMatrix(Matrix4 value)](#setMatrix-com.aspose.threed.Matrix4-) | वर्तमान मैट्रिक्स मान सेट करता है |
| [toString()](#toString--) |  |
| [translate(Vector3 v)](#translate-com.aspose.threed.Vector3-) | अनुवाद रूपांतरण को श्रृंखलाबद्ध करें **Example:** |
| [translate(double tx, double ty, double tz)](#translate-double-double-double-) | अनुवाद रूपांतरण को श्रृंखलाबद्ध करें **Example:** |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TransformBuilder(Matrix4 initial, ComposeOrder order) {#TransformBuilder-com.aspose.threed.Matrix4-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(Matrix4 initial, ComposeOrder order)
```


एक प्रारंभिक ट्रांसफ़ॉर्म मैट्रिक्स और निर्दिष्ट संयोजन क्रम के साथ एक [TransformBuilder](../../com.aspose.threed/transformbuilder) बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| initial | [Matrix4](../../com.aspose.threed/matrix4) |  |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder(ComposeOrder order) {#TransformBuilder-com.aspose.threed.ComposeOrder-}
```
public TransformBuilder(ComposeOrder order)
```


एक प्रारंभिक आइडेंटिटी ट्रांसफ़ॉर्म मैट्रिक्स और निर्दिष्ट संयोजन क्रम के साथ एक [TransformBuilder](../../com.aspose.threed/transformbuilder) बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| order | [ComposeOrder](../../com.aspose.threed/composeorder) |  |

### TransformBuilder() {#TransformBuilder--}
```
public TransformBuilder()
```


एक प्रारंभिक आइडेंटिटी ट्रांसफ़ॉर्म मैट्रिक्स और निर्दिष्ट संयोजन क्रम के साथ एक [TransformBuilder](../../com.aspose.threed/transformbuilder) बनाएं

### append(Matrix4 m) {#append-com.aspose.threed.Matrix4-}
```
public TransformBuilder append(Matrix4 m)
```


नए ट्रांसफ़ॉर्म मैट्रिक्स को ट्रांसफ़ॉर्म श्रृंखला में जोड़ें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### compose(Matrix4 m) {#compose-com.aspose.threed.Matrix4-}
```
public void compose(Matrix4 m)
```


आर्ग्यूमेंट को आंतरिक मैट्रिक्स में जोड़ें या पहले रखें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

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
### getComposeOrder() {#getComposeOrder--}
```
public ComposeOrder getComposeOrder()
```


श्रृंखला के संयोजन क्रम को प्राप्त करता है।

**Returns:**
[ComposeOrder](../../com.aspose.threed/composeorder) - the chain compose order.
### getMatrix() {#getMatrix--}
```
public Matrix4 getMatrix()
```


वर्तमान मैट्रिक्स मान प्राप्त करता है

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the current matrix value
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




### prepend(Matrix4 m) {#prepend-com.aspose.threed.Matrix4-}
```
public TransformBuilder prepend(Matrix4 m)
```


नए ट्रांसफ़ॉर्म मैट्रिक्स को ट्रांसफ़ॉर्म श्रृंखला की शुरुआत में रखें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| m | [Matrix4](../../com.aspose.threed/matrix4) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rearrange(Axis newX, Axis newY, Axis newZ) {#rearrange-com.aspose.threed.Axis-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public TransformBuilder rearrange(Axis newX, Axis newY, Axis newZ)
```


अक्ष की लेआउट को पुनर्व्यवस्थित करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| newX | [Axis](../../com.aspose.threed/axis) | नया x घटक स्रोत |
| newY | [Axis](../../com.aspose.threed/axis) | नया y घटक स्रोत |
| newZ | [Axis](../../com.aspose.threed/axis) | नया z घटक स्रोत |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### reset() {#reset--}
```
public void reset()
```


ट्रांसफ़ॉर्म को आइडेंटिटी मैट्रिक्स पर रीसेट करें

### rotate(Quaternion q) {#rotate-com.aspose.threed.Quaternion-}
```
public TransformBuilder rotate(Quaternion q)
```


क्वाटरनियन द्वारा घूर्णन को श्रृंखलाबद्ध करें **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotate(Quaternion.fromEulerAngle(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateDegree(Vector3 rot, RotationOrder order) {#rotateDegree-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-}
```
public void rotateDegree(Vector3 rot, RotationOrder order)
```


निर्दिष्ट क्रम के साथ घूर्णन जोड़ें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| rot | [Vector3](../../com.aspose.threed/vector3) | डिग्री में घूर्णन |
| order | [RotationOrder](../../com.aspose.threed/rotationorder) |  |

### rotateDegree(double angle, Vector3 axis) {#rotateDegree-double-com.aspose.threed.Vector3-}
```
public TransformBuilder rotateDegree(double angle, Vector3 axis)
```


डिग्री में घूर्णन रूपांतरण को श्रृंखलाबद्ध करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| angle | double | डिग्री में घुमाने का कोण |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | घुमाने के लिए अक्ष **Example:** |

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateDegree(90, Vector3.getUnitY());
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
``` |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateEulerDegree(double degX, double degY, double degZ) {#rotateEulerDegree-double-double-double-}
```
public TransformBuilder rotateEulerDegree(double degX, double degY, double degZ)
```


डिग्री में यूलेर कोणों द्वारा घूर्णन को श्रृंखलाबद्ध करें **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerDegree(0, 90, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| degX | double |  |
| degY | double |  |
| degZ | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateEulerRadian(Vector3 r) {#rotateEulerRadian-com.aspose.threed.Vector3-}
```
public TransformBuilder rotateEulerRadian(Vector3 r)
```


रेडियन में यूलेर कोणों द्वारा घूर्णन को श्रृंखलाबद्ध करें **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(new Vector3(0, Math.PI, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| r | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateEulerRadian(double x, double y, double z) {#rotateEulerRadian-double-double-double-}
```
public TransformBuilder rotateEulerRadian(double x, double y, double z)
```


रेडियन में यूलेर कोणों द्वारा घूर्णन को श्रृंखलाबद्ध करें **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateEulerRadian(0, Math.PI, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| x | double |  |
| y | double |  |
| z | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### rotateRadian(Vector3 rot, RotationOrder order) {#rotateRadian-com.aspose.threed.Vector3-com.aspose.threed.RotationOrder-}
```
public void rotateRadian(Vector3 rot, RotationOrder order)
```


निर्दिष्ट क्रम के साथ घूर्णन जोड़ें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | rot | [Vector3](../../com.aspose.threed/vector3) | रेडियन में घूर्णन **Example:** |

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateRadian(new Vector3(0.3, 0.4, 0.1), RotationOrder.YZX);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
``` |
| order | [RotationOrder](../../com.aspose.threed/rotationorder) |  |

### rotateRadian(double angle, Vector3 axis) {#rotateRadian-double-com.aspose.threed.Vector3-}
```
public TransformBuilder rotateRadian(double angle, Vector3 axis)
```


रेडियन में घूर्णन रूपांतरण को श्रृंखलाबद्ध करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| angle | double | रेडियन में घुमाने का कोण |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | घुमाने के लिए अक्ष **Example:** |

```
TransformBuilder tb = new TransformBuilder();
     tb.rotateRadian(Math.PI, Vector3.getUnitY());
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
``` |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(Vector3 s) {#scale-com.aspose.threed.Vector3-}
```
public TransformBuilder scale(Vector3 s)
```


स्केल रूपांतरण को श्रृंखलाबद्ध करें **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(new Vector3(10, 10, 10));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double s) {#scale-double-}
```
public TransformBuilder scale(double s)
```


एक घटक को s द्वारा स्केल किए गए स्केलिंग रूपांतरण मैट्रिक्स को श्रृंखलाबद्ध करें **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| s | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### scale(double x, double y, double z) {#scale-double-double-double-}
```
public TransformBuilder scale(double x, double y, double z)
```


स्केलिंग रूपांतरण मैट्रिक्स को श्रृंखलाबद्ध करें **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.scale(10, 10, 10);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| x | double |  |
| y | double |  |
| z | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### setComposeOrder(ComposeOrder value) {#setComposeOrder-com.aspose.threed.ComposeOrder-}
```
public void setComposeOrder(ComposeOrder value)
```


श्रृंखला संयोजन क्रम सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [ComposeOrder](../../com.aspose.threed/composeorder) | नया मान |

### setMatrix(Matrix4 value) {#setMatrix-com.aspose.threed.Matrix4-}
```
public void setMatrix(Matrix4 value)
```


वर्तमान मैट्रिक्स मान सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | नया मान |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translate(Vector3 v) {#translate-com.aspose.threed.Vector3-}
```
public TransformBuilder translate(Vector3 v)
```


अनुवाद रूपांतरण को श्रृंखलाबद्ध करें **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(new Vector3(0, 10, 0));
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
### translate(double tx, double ty, double tz) {#translate-double-double-double-}
```
public TransformBuilder translate(double tx, double ty, double tz)
```


अनुवाद रूपांतरण को श्रृंखलाबद्ध करें **Example:**

```
TransformBuilder tb = new TransformBuilder();
     tb.translate(0, 10, 0);
     System.out.printf("Transform Matrix: %s", tb.getMatrix());
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| tx | double |  |
| ty | double |  |
| tz | double |  |

**Returns:**
[TransformBuilder](../../com.aspose.threed/transformbuilder)
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

