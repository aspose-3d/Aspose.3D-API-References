---
title: Quaternion
second_title: Aspose.3D for Java API Reference
description: क्वाटरनियन का उपयोग आमतौर पर कंप्यूटर ग्राफिक्स में रोटेशन करने के लिए किया जाता है।
type: docs
weight: 143
url: /hi/java/com.aspose.threed/quaternion/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Quaternion implements Struct<Quaternion>, Serializable
```

क्वाटरनियन का उपयोग आमतौर पर कंप्यूटर ग्राफिक्स में रोटेशन करने के लिए किया जाता है।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Quaternion(double w, double x, double y, double z)](#Quaternion-double-double-double-double-) | एक नया उदाहरण प्रारंभ करता है [Quaternion](../../com.aspose.threed/quaternion) वर्ग का। |
| [Quaternion()](#Quaternion--) |  |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [IDENTITY](#IDENTITY) | पहचान क्वाटरनियन। |
| [w](#w) | w घटक। |
| [x](#x) | The x component. |
| [y](#y) | The y component. |
| [z](#z) | The z component. |
## Methods

| Method | विवरण |
| --- | --- |
| [add(Quaternion lhs, Quaternion rhs)](#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | ऑपरेटर ओवरलोडिंग + के लिए |
| [clone()](#clone--) |  |
| [concat(Quaternion rhs)](#concat-com.aspose.threed.Quaternion-) | दो क्वाटरनियन को जोड़ें |
| [conjugate()](#conjugate--) | वर्तमान क्वाटरनियन का संयुग्म क्वाटरनियन लौटाता है |
| [copyFrom(Quaternion src)](#copyFrom-com.aspose.threed.Quaternion-) |  |
| [div(Quaternion lhs, double rhs)](#div-com.aspose.threed.Quaternion-double-) | ऑपरेटर ओवरलोडिंग / के लिए। |
| [dot(Quaternion q)](#dot-com.aspose.threed.Quaternion-) | डॉट उत्पाद |
| [equals(Object obj)](#equals-java.lang.Object-) | जाँचें कि दो क्वाटरनियन बराबर हैं |
| [eulerAngles()](#eulerAngles--) | क्वाटरनियन को यूलेर कोणों द्वारा दर्शाए गए घूर्णन में बदलता है सभी घटक रेडियन में हैं |
| [fromAngleAxis(double a, Vector3 axis)](#fromAngleAxis-double-com.aspose.threed.Vector3-) | दिए गए अक्ष के चारों ओर एक क्वाटरनियन बनाता है और घड़ी की दिशा में घुमाता है |
| [fromEulerAngle(Vector3 eulerAngle)](#fromEulerAngle-com.aspose.threed.Vector3-) | दिए गए यूलेर कोण से क्वाटरनियन बनाता है |
| [fromEulerAngle(double pitch, double yaw, double roll)](#fromEulerAngle-double-double-double-) | दिए गए यूलेर कोण से क्वाटरनियन बनाता है |
| [fromRotation(Vector3 orig, Vector3 dest)](#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | एक क्वाटरनियन बनाता है जो मूल दिशा से गंतव्य दिशा की ओर घुमता है |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | क्वाटरनियन की लंबाई प्राप्त करता है |
| [hashCode()](#hashCode--) | क्वाटरनियन का हैश कोड प्राप्त करता है |
| [interpolate(float t, Quaternion from, Quaternion to)](#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | दिए गए क्वाटरनियन तर्कों के बीच अंतर्वर्ती मान के साथ इस क्वाटरनियन को भरता है, जहाँ t प्रारंभ और अंत के बीच है। |
| [inverse()](#inverse--) | वर्तमान क्वाटरनियन का उलटा क्वाटरनियन लौटाता है |
| [mul(Quaternion lhs, Quaternion rhs)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | ऑपरेटर ओवरलोडिंग \* के लिए। |
| [mul(Quaternion q, Vector3 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-) | ऑपरेटर ओवरलोडिंग \* के लिए। |
| [mul(Quaternion q, Vector4 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-) | ऑपरेटर ओवरलोडिंग \* के लिए। |
| [mul(Quaternion lhs, double rhs)](#mul-com.aspose.threed.Quaternion-double-) | ऑपरेटर ओवरलोडिंग \* के लिए। |
| [mul(Vector3 v, Quaternion q)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | ऑपरेटर ओवरलोडिंग \* के लिए। |
| [normalize()](#normalize--) | क्वाटरनियन को सामान्यीकृत करें |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Quaternion lhs, Quaternion rhs)](#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | क्वाटरनियन के लिए समान ऑपरेटर |
| [op_ne(Quaternion lhs, Quaternion rhs)](#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | क्वाटरनियन के लिए असमान ऑपरेटर |
| [slerp(double t, Quaternion v1, Quaternion v2)](#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | दो मानों के बीच गोलाकार रैखिक अंतर्वर्तन करें |
| [toAngleAxis(double[] angle, Vector3 axis)](#toAngleAxis-double---com.aspose.threed.Vector3-) | क्वाटरनियन को कोण और अक्ष में विभाजित करें |
| [toMatrix()](#toMatrix--) | क्वाटरनियन द्वारा प्रस्तुत घूर्णन को रूपांतरण मैट्रिक्स में बदलें। |
| [toMatrix(Vector3 translation)](#toMatrix-com.aspose.threed.Vector3-) | क्वाटरनियन द्वारा प्रस्तुत घूर्णन को रूपांतरण मैट्रिक्स में बदलें। |
| [toString()](#toString--) | क्वाटरनियन का स्ट्रिंग में प्रतिनिधित्व प्राप्त करता है |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quaternion(double w, double x, double y, double z) {#Quaternion-double-double-double-double-}
```
public Quaternion(double w, double x, double y, double z)
```


एक नया उदाहरण प्रारंभ करता है [Quaternion](../../com.aspose.threed/quaternion) वर्ग का।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| w | double | क्वाटरनियन का w घटक |
| x | double | क्वाटरनियन का x घटक |
| y | double | क्वाटरनियन का y घटक |
| z | double | क्वाटरनियन का z घटक |

### Quaternion() {#Quaternion--}
```
public Quaternion()
```


### IDENTITY {#IDENTITY}
```
public static final Quaternion IDENTITY
```


पहचान क्वाटरनियन।

### w {#w}
```
public double w
```


w घटक।

### x {#x}
```
public double x
```


The x component.

### y {#y}
```
public double y
```


The y component.

### z {#z}
```
public double z
```


The z component.

### add(Quaternion lhs, Quaternion rhs) {#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion add(Quaternion lhs, Quaternion rhs)
```


ऑपरेटर ओवरलोडिंग + के लिए

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | बायाँ क्वाटरनियन |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | दायाँ क्वाटरनियन |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### clone() {#clone--}
```
public Quaternion clone()
```


वर्तमान उदाहरण को क्लोन करें

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### concat(Quaternion rhs) {#concat-com.aspose.threed.Quaternion-}
```
public Quaternion concat(Quaternion rhs)
```


दो क्वाटरनियन को जोड़ें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### conjugate() {#conjugate--}
```
public Quaternion conjugate()
```


वर्तमान क्वाटरनियन का संयुग्म क्वाटरनियन लौटाता है

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The conjugate quaternion.
### copyFrom(Quaternion src) {#copyFrom-com.aspose.threed.Quaternion-}
```
public void copyFrom(Quaternion src)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| src | [Quaternion](../../com.aspose.threed/quaternion) |  |

### div(Quaternion lhs, double rhs) {#div-com.aspose.threed.Quaternion-double-}
```
public static Quaternion div(Quaternion lhs, double rhs)
```


ऑपरेटर ओवरलोडिंग / के लिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | बायाँ क्वाटरनियन |
| rhs | double | दायाँ क्वाटरनियन |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### dot(Quaternion q) {#dot-com.aspose.threed.Quaternion-}
```
public double dot(Quaternion q)
```


डॉट उत्पाद

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | क्वाटरनियन |

**Returns:**
डबल - डॉट मान
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


जाँचें कि दो क्वाटरनियन बराबर हैं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | The object to check equality. |

**Returns:**
boolean - True if all components are identically equal.
### eulerAngles() {#eulerAngles--}
```
public Vector3 eulerAngles()
```


क्वाटरनियन को यूलेर कोणों द्वारा दर्शाए गए घूर्णन में बदलता है सभी घटक रेडियन में हैं

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### fromAngleAxis(double a, Vector3 axis) {#fromAngleAxis-double-com.aspose.threed.Vector3-}
```
public static Quaternion fromAngleAxis(double a, Vector3 axis)
```


दिए गए अक्ष के चारों ओर एक क्वाटरनियन बनाता है और घड़ी की दिशा में घुमाता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| a | double | रैडियन में घड़ी की दिशा में घूर्णन |
| axis | [Vector3](../../com.aspose.threed/vector3) | अक्ष |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(Vector3 eulerAngle) {#fromEulerAngle-com.aspose.threed.Vector3-}
```
public static Quaternion fromEulerAngle(Vector3 eulerAngle)
```


दिए गए यूलेर कोण से क्वाटरनियन बनाता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| eulerAngle | [Vector3](../../com.aspose.threed/vector3) | रैडियन में यूलेर कोण |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(double pitch, double yaw, double roll) {#fromEulerAngle-double-double-double-}
```
public static Quaternion fromEulerAngle(double pitch, double yaw, double roll)
```


दिए गए यूलेर कोण से क्वाटरनियन बनाता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| पिच | double | रैडियन में पिच |
| यॉ | double | रैडियन में यॉ |
| रोल | double | रैडियन में रोल |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromRotation(Vector3 orig, Vector3 dest) {#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Quaternion fromRotation(Vector3 orig, Vector3 dest)
```


एक क्वाटरनियन बनाता है जो मूल दिशा से गंतव्य दिशा की ओर घुमता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| orig | [Vector3](../../com.aspose.threed/vector3) | मूल दिशा |
| dest | [Vector3](../../com.aspose.threed/vector3) | गंतव्य दिशा |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public double getLength()
```


क्वाटरनियन की लंबाई प्राप्त करता है

**Returns:**
डबल - क्वाटरनियन की लंबाई
### hashCode() {#hashCode--}
```
public int hashCode()
```


क्वाटरनियन का हैश कोड प्राप्त करता है

**Returns:**
int - [Quaternion](../../com.aspose.threed/quaternion) का हैश कोड
### interpolate(float t, Quaternion from, Quaternion to) {#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion interpolate(float t, Quaternion from, Quaternion to)
```


दिए गए क्वाटरनियन तर्कों के बीच अंतर्वर्ती मान के साथ इस क्वाटरनियन को भरता है, जहाँ t प्रारंभ और अंत के बीच है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| t | फ़्लोट | इंटरपोलेशन के लिए गुणांक। |
| from | [Quaternion](../../com.aspose.threed/quaternion) | स्रोत क्वाटरनियन। |
| to | [Quaternion](../../com.aspose.threed/quaternion) | लक्ष्य क्वाटरनियन। |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The interpolated quaternion.
### inverse() {#inverse--}
```
public Quaternion inverse()
```


वर्तमान क्वाटरनियन का उलटा क्वाटरनियन लौटाता है

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Inverse quaternion.
### mul(Quaternion lhs, Quaternion rhs) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion mul(Quaternion lhs, Quaternion rhs)
```


ऑपरेटर ओवरलोडिंग \* के लिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | बायाँ क्वाटरनियन |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | दायाँ क्वाटरनियन |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Quaternion q, Vector3 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Quaternion q, Vector3 v)
```


ऑपरेटर ओवरलोडिंग \* के लिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | घूर्णन क्वाटरनियन |
| v | [Vector3](../../com.aspose.threed/vector3) | घुमाने के लिए वेक्टर |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### mul(Quaternion q, Vector4 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Quaternion q, Vector4 v)
```


ऑपरेटर ओवरलोडिंग \* के लिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | घूर्णन क्वाटरनियन |
| v | [Vector4](../../com.aspose.threed/vector4) | घुमाने के लिए वेक्टर |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Rotated vector
### mul(Quaternion lhs, double rhs) {#mul-com.aspose.threed.Quaternion-double-}
```
public static Quaternion mul(Quaternion lhs, double rhs)
```


ऑपरेटर ओवरलोडिंग \* के लिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | बायाँ क्वाटरनियन |
| rhs | double | दायाँ क्वाटरनियन |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Vector3 v, Quaternion q) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public static Vector3 mul(Vector3 v, Quaternion q)
```


ऑपरेटर ओवरलोडिंग \* के लिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | घूर्णन क्वाटरनियन |
| q | [Quaternion](../../com.aspose.threed/quaternion) | घुमाने के लिए वेक्टर |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### normalize() {#normalize--}
```
public Quaternion normalize()
```


क्वाटरनियन को सामान्यीकृत करें

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Normalized quaternion.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Quaternion lhs, Quaternion rhs) {#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_eq(Quaternion lhs, Quaternion rhs)
```


क्वाटरनियन के लिए समान ऑपरेटर

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Left hand side value. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Right hand side value. |

**Returns:**
boolean - True if all components are identically equal.
### op_ne(Quaternion lhs, Quaternion rhs) {#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_ne(Quaternion lhs, Quaternion rhs)
```


क्वाटरनियन के लिए असमान ऑपरेटर

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Left hand side value. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Right hand side value. |

**Returns:**
बूलियन - सत्य यदि दो क्वाटरनियन समान नहीं हैं।
### slerp(double t, Quaternion v1, Quaternion v2) {#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion slerp(double t, Quaternion v1, Quaternion v2)
```


दो मानों के बीच गोलाकार रैखिक अंतर्वर्तन करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| t | double | t 0 से 1 के बीच है |
| v1 | [Quaternion](../../com.aspose.threed/quaternion) | पहला मान |
| v2 | [Quaternion](../../com.aspose.threed/quaternion) | दूसरा मान |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### toAngleAxis(double[] angle, Vector3 axis) {#toAngleAxis-double---com.aspose.threed.Vector3-}
```
public void toAngleAxis(double[] angle, Vector3 axis)
```


क्वाटरनियन को कोण और अक्ष में विभाजित करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| angle | double[] | घुमाने के लिए कोण, रेडियन में। |
| axis | [Vector3](../../com.aspose.threed/vector3) | धुरी जिसके चारों ओर घुमाव होता है। |

### toMatrix() {#toMatrix--}
```
public Matrix4 toMatrix()
```


क्वाटरनियन द्वारा प्रस्तुत घूर्णन को रूपांतरण मैट्रिक्स में बदलें।

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toMatrix(Vector3 translation) {#toMatrix-com.aspose.threed.Vector3-}
```
public Matrix4 toMatrix(Vector3 translation)
```


क्वाटरनियन द्वारा प्रस्तुत घूर्णन को रूपांतरण मैट्रिक्स में बदलें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | मैट्रिक्स का अनुवाद भाग। |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toString() {#toString--}
```
public String toString()
```


क्वाटरनियन का स्ट्रिंग में प्रतिनिधित्व प्राप्त करता है

**Returns:**
java.lang.String - ऑब्जेक्ट स्ट्रिंग
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

