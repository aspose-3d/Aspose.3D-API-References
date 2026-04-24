---
title: Vector2
second_title: Aspose.3D for Java API Reference
description: दो घटकों वाला एक वेक्टर।
type: docs
weight: 201
url: /hi/java/com.aspose.threed/vector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector2 implements Comparable<Vector2>, Struct<Vector2>, Serializable
```

दो घटकों वाला एक वेक्टर।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Vector2(double s)](#Vector2-double-) | [Vector2](../../com.aspose.threed/vector2) स्ट्रक्चर का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Vector2(Vector3 s)](#Vector2-com.aspose.threed.Vector3-) | [Vector2](../../com.aspose.threed/vector2) स्ट्रक्चर का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Vector2(FVector2 vec)](#Vector2-com.aspose.threed.FVector2-) | [Vector2](../../com.aspose.threed/vector2) स्ट्रक्चर का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Vector2(double x, double y)](#Vector2-double-double-) | [Vector2](../../com.aspose.threed/vector2) स्ट्रक्चर का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Vector2()](#Vector2--) |  |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [x](#x) | The x component. |
| [y](#y) | The y component. |
## Methods

| Method | विवरण |
| --- | --- |
| [add(Vector2 lhs, Vector2 rhs)](#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vector2 के लिए जोड़ ऑपरेटर |
| [clone()](#clone--) |  |
| [compareTo(Vector2 other)](#compareTo-com.aspose.threed.Vector2-) | वर्तमान वेक्टर की तुलना किसी अन्य उदाहरण से करें। |
| [copyFrom(Vector2 src)](#copyFrom-com.aspose.threed.Vector2-) |  |
| [create(Vector2 v)](#create-com.aspose.threed.Vector2-) | Vector2 को FVector2 में कास्ट करने के लिए स्पष्ट रूपांतरण ऑपरेटर |
| [cross(Vector2 v)](#cross-com.aspose.threed.Vector2-) | दो वेक्टरों का क्रॉस प्रोडक्ट। |
| [div(Vector2 lhs, double rhs)](#div-com.aspose.threed.Vector2-double-) | Vector2 के लिए विभाजन ऑपरेटर |
| [dot(Vector2 rhs)](#dot-com.aspose.threed.Vector2-) | दो वेक्टरों का डॉट प्रोडक्ट प्राप्त करता है। |
| [equals(Vector2 rhs)](#equals-com.aspose.threed.Vector2-) | जाँचें कि दो vector2 बराबर हैं या नहीं |
| [equals(Object obj)](#equals-java.lang.Object-) | जाँचें कि दो vector2 बराबर हैं या नहीं |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | लंबाई प्राप्त करता है। |
| [getU()](#getU--) | यदि [Vector2](../../com.aspose.threed/vector2) को मैपिंग कोऑर्डिनेट के रूप में उपयोग किया जाता है तो U घटक प्राप्त करता है। |
| [getV()](#getV--) | यदि [Vector2](../../com.aspose.threed/vector2) को मैपिंग कोऑर्डिनेट के रूप में उपयोग किया जाता है तो V घटक प्राप्त करता है। |
| [hashCode()](#hashCode--) | Vector2 का हैश कोड प्राप्त करता है |
| [mul(Vector2 lhs, double rhs)](#mul-com.aspose.threed.Vector2-double-) | Vector2 के लिए गुणा ऑपरेटर |
| [mul(double lhs, Vector2 rhs)](#mul-double-com.aspose.threed.Vector2-) | Vector2 के लिए गुणा ऑपरेटर |
| [normalize()](#normalize--) | इस उदाहरण को सामान्यीकृत करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector2 lhs, Vector2 rhs)](#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vector2 के लिए समान ऑपरेटर |
| [op_ne(Vector2 lhs, Vector2 rhs)](#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vector2 के लिए असमान ऑपरेटर |
| [setU(double value)](#setU-double-) | यदि [Vector2](../../com.aspose.threed/vector2) को मैपिंग निर्देशांक के रूप में उपयोग किया जाता है तो U घटक सेट करता है। |
| [setV(double value)](#setV-double-) | यदि [Vector2](../../com.aspose.threed/vector2) को मैपिंग निर्देशांक के रूप में उपयोग किया जाता है तो V घटक सेट करता है। |
| [sub(Vector2 lhs, Vector2 rhs)](#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vector2 के लिए घटाव ऑपरेटर |
| [toString()](#toString--) | वर्तमान [Vector2](../../com.aspose.threed/vector2) को दर्शाने वाली java.lang.String लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector2(double s) {#Vector2-double-}
```
public Vector2(double s)
```


[Vector2](../../com.aspose.threed/vector2) स्ट्रक्चर का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| s | double | S. |

### Vector2(Vector3 s) {#Vector2-com.aspose.threed.Vector3-}
```
public Vector2(Vector3 s)
```


[Vector2](../../com.aspose.threed/vector2) स्ट्रक्चर का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) | S. |

### Vector2(FVector2 vec) {#Vector2-com.aspose.threed.FVector2-}
```
public Vector2(FVector2 vec)
```


[Vector2](../../com.aspose.threed/vector2) स्ट्रक्चर का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| vec | [FVector2](../../com.aspose.threed/fvector2) | फ़्लोट में वेक्टर। |

### Vector2(double x, double y) {#Vector2-double-double-}
```
public Vector2(double x, double y)
```


[Vector2](../../com.aspose.threed/vector2) स्ट्रक्चर का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| x | double | x निर्देशांक। |
| y | double | y निर्देशांक। |

### Vector2() {#Vector2--}
```
public Vector2()
```


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

### add(Vector2 lhs, Vector2 rhs) {#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 add(Vector2 lhs, Vector2 rhs)
```


Vector2 के लिए जोड़ ऑपरेटर

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of addition.
### clone() {#clone--}
```
public Vector2 clone()
```


वर्तमान उदाहरण को क्लोन करें

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### compareTo(Vector2 other) {#compareTo-com.aspose.threed.Vector2-}
```
public int compareTo(Vector2 other)
```


वर्तमान वेक्टर की तुलना किसी अन्य उदाहरण से करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| other | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
int
### copyFrom(Vector2 src) {#copyFrom-com.aspose.threed.Vector2-}
```
public void copyFrom(Vector2 src)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| src | [Vector2](../../com.aspose.threed/vector2) |  |

### create(Vector2 v) {#create-com.aspose.threed.Vector2-}
```
public static FVector2 create(Vector2 v)
```


Vector2 को FVector2 में कास्ट करने के लिए स्पष्ट रूपांतरण ऑपरेटर

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### cross(Vector2 v) {#cross-com.aspose.threed.Vector2-}
```
public double cross(Vector2 v)
```


दो वेक्टरों का क्रॉस प्रोडक्ट।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
double
### div(Vector2 lhs, double rhs) {#div-com.aspose.threed.Vector2-double-}
```
public static Vector2 div(Vector2 lhs, double rhs)
```


Vector2 के लिए विभाजन ऑपरेटर

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | double | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of division.
### dot(Vector2 rhs) {#dot-com.aspose.threed.Vector2-}
```
public double dot(Vector2 rhs)
```


दो वेक्टरों का डॉट प्रोडक्ट प्राप्त करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
double - The dot product of the two vectors.
### equals(Vector2 rhs) {#equals-com.aspose.threed.Vector2-}
```
public boolean equals(Vector2 rhs)
```


जाँचें कि दो vector2 बराबर हैं या नहीं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | दाएँ हाथ की मान। |

**Returns:**
boolean - True if all components are identically equal.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


जाँचें कि दो vector2 बराबर हैं या नहीं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए वस्तु। |

**Returns:**
boolean - True if all components are identically equal.
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


लंबाई प्राप्त करता है।

**Returns:**
double - लंबाई।
### getU() {#getU--}
```
public double getU()
```


यदि [Vector2](../../com.aspose.threed/vector2) को मैपिंग निर्देशांक के रूप में उपयोग किया जाता है तो U घटक प्राप्त करता है। यह x घटक का उपनाम है।

**Returns:**
double - U घटक यदि [Vector2](../../com.aspose.threed/vector2) को मैपिंग निर्देशांक के रूप में उपयोग किया जाता है। यह x घटक का उपनाम है।
### getV() {#getV--}
```
public double getV()
```


यदि [Vector2](../../com.aspose.threed/vector2) को मैपिंग निर्देशांक के रूप में उपयोग किया जाता है तो V घटक प्राप्त करता है। यह y घटक का उपनाम है।

**Returns:**
double - V घटक यदि [Vector2](../../com.aspose.threed/vector2) को मैपिंग निर्देशांक के रूप में उपयोग किया जाता है। यह y घटक का उपनाम है।
### hashCode() {#hashCode--}
```
public int hashCode()
```


Vector2 का हैश कोड प्राप्त करता है

**Returns:**
int - [Vector2](../../com.aspose.threed/vector2) का हैश कोड
### mul(Vector2 lhs, double rhs) {#mul-com.aspose.threed.Vector2-double-}
```
public static Vector2 mul(Vector2 lhs, double rhs)
```


Vector2 के लिए गुणा ऑपरेटर

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | double | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### mul(double lhs, Vector2 rhs) {#mul-double-com.aspose.threed.Vector2-}
```
public static Vector2 mul(double lhs, Vector2 rhs)
```


Vector2 के लिए गुणा ऑपरेटर

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | double | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### normalize() {#normalize--}
```
public Vector2 normalize()
```


इस उदाहरण को सामान्यीकृत करता है।

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Vector2 lhs, Vector2 rhs) {#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_eq(Vector2 lhs, Vector2 rhs)
```


Vector2 के लिए समान ऑपरेटर

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
boolean - True if all components are identically equal.
### op_ne(Vector2 lhs, Vector2 rhs) {#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_ne(Vector2 lhs, Vector2 rhs)
```


Vector2 के लिए असमान ऑपरेटर

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
boolean - True if two vectors are not equal.
### setU(double value) {#setU-double-}
```
public void setU(double value)
```


यदि [Vector2](../../com.aspose.threed/vector2) को मैपिंग निर्देशांक के रूप में उपयोग किया जाता है तो U घटक सेट करता है। यह x घटक का उपनाम है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setV(double value) {#setV-double-}
```
public void setV(double value)
```


यदि [Vector2](../../com.aspose.threed/vector2) को मैपिंग निर्देशांक के रूप में उपयोग किया जाता है तो V घटक सेट करता है। यह y घटक का उपनाम है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### sub(Vector2 lhs, Vector2 rhs) {#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 sub(Vector2 lhs, Vector2 rhs)
```


Vector2 के लिए घटाव ऑपरेटर

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of substraction.
### toString() {#toString--}
```
public String toString()
```


वर्तमान [Vector2](../../com.aspose.threed/vector2) को दर्शाने वाली java.lang.String लौटाता है।

**Returns:**
java.lang.String - एक java.lang.String जो वर्तमान [Vector2](../../com.aspose.threed/vector2) को दर्शाता है।
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

