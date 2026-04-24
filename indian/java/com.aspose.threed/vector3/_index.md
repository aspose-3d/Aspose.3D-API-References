---
title: Vector3
second_title: Aspose.3D for Java API Reference
description: तीन घटकों वाला एक वेक्टर।
type: docs
weight: 202
url: /hi/java/com.aspose.threed/vector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector3 implements Comparable<Vector3>, Struct<Vector3>, Serializable
```

तीन घटकों वाला एक वेक्टर।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Vector3(double x, double y, double z)](#Vector3-double-double-double-) | एक नया उदाहरण प्रारंभ करता है [Vector3](../../com.aspose.threed/vector3) संरचना का। |
| [Vector3(FVector3 vec)](#Vector3-com.aspose.threed.FVector3-) | एक नया उदाहरण प्रारंभ करता है [Vector3](../../com.aspose.threed/vector3) संरचना का। |
| [Vector3(double v)](#Vector3-double-) | एक नया उदाहरण प्रारंभ करता है [Vector3](../../com.aspose.threed/vector3) संरचना का। |
| [Vector3(Vector4 vec4)](#Vector3-com.aspose.threed.Vector4-) | एक नया उदाहरण प्रारंभ करता है [Vector3](../../com.aspose.threed/vector3) संरचना का। |
| [Vector3()](#Vector3--) |  |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [x](#x) | The x component. |
| [y](#y) | The y component. |
| [z](#z) | The z component. |
## Methods

| Method | विवरण |
| --- | --- |
| [add(Vector3 lhs, Vector3 rhs)](#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | ऑपरेटर ओवरलोडिंग + के लिए |
| [angleBetween(Vector3 dir)](#angleBetween-com.aspose.threed.Vector3-) | दो दिशाओं के बीच का आंतरिक कोण गणना करें। दो दिशाएँ गैर-नॉर्मलाइज़्ड वेक्टर हो सकती हैं। |
| [angleBetween(Vector3 dir, Vector3 up)](#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | दो दिशाओं के बीच का आंतरिक कोण गणना करें। दो दिशाएँ गैर-नॉर्मलाइज़्ड वेक्टर हो सकती हैं। |
| [clone()](#clone--) |  |
| [compareTo(Vector3 other)](#compareTo-com.aspose.threed.Vector3-) | वर्तमान वेक्टर की तुलना किसी अन्य उदाहरण से करें। |
| [copyFrom(Vector3 src)](#copyFrom-com.aspose.threed.Vector3-) |  |
| [cos()](#cos--) | प्रत्येक घटक पर कोसाइन की गणना करता है। |
| [create(Vector3 v)](#create-com.aspose.threed.Vector3-) | Vector3 को FVector3 में कास्ट करने के लिए स्पष्ट रूपांतरण ऑपरेटर। |
| [cross(Vector3 rhs)](#cross-com.aspose.threed.Vector3-) | दो वेक्टरों का क्रॉस प्रोडक्ट। |
| [div(Vector3 lhs, Vector3 rhs)](#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | ऑपरेटर ओवरलोडिंग / के लिए। |
| [div(Vector3 lhs, double rhs)](#div-com.aspose.threed.Vector3-double-) | ऑपरेटर ओवरलोडिंग / के लिए। |
| [dot(Vector3 rhs)](#dot-com.aspose.threed.Vector3-) | दो वेक्टरों का डॉट प्रोडक्ट प्राप्त करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | जाँचें कि दो vector3 समान हैं या नहीं। |
| [get(int idx)](#get-int-) | इंडेक्स द्वारा वेक्टर का घटक प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | इस वेक्टर की लंबाई प्राप्त करता है। |
| [getLength2()](#getLength2--) | लंबाई का वर्ग प्राप्त करता है। |
| [getOne()](#getOne--) | यूनिट वेक्टर (1, 1, 1) प्राप्त करता है। |
| [getUnitX()](#getUnitX--) | यूनिट वेक्टर (1, 0, 0) प्राप्त करता है। |
| [getUnitY()](#getUnitY--) | यूनिट वेक्टर (0, 1, 0) प्राप्त करता है। |
| [getUnitZ()](#getUnitZ--) | यूनिट वेक्टर (0, 0, 1) प्राप्त करता है। |
| [getZero()](#getZero--) | यूनिट वेक्टर (0, 0, 0) प्राप्त करता है। |
| [hashCode()](#hashCode--) | Vector3 का हैश कोड प्राप्त करता है। |
| [mul(Vector3 lhs, Vector3 rhs)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | ऑपरेटर ओवरलोडिंग \* के लिए। |
| [mul(Vector3 lhs, double rhs)](#mul-com.aspose.threed.Vector3-double-) | ऑपरेटर ओवरलोडिंग \* के लिए। |
| [mul(double lhs, Vector3 rhs)](#mul-double-com.aspose.threed.Vector3-) | ऑपरेटर ओवरलोडिंग \* के लिए। |
| [negative(Vector3 v)](#negative-com.aspose.threed.Vector3-) | ऑपरेटर ओवरलोडिंग के लिए - |
| [normalize()](#normalize--) | इस उदाहरण को सामान्यीकृत करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector3 lhs, Vector3 rhs)](#op-eq-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Vector3 के लिए समान ऑपरेटर |
| [op_ne(Vector3 lhs, Vector3 rhs)](#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Vector3 के लिए असमान ऑपरेटर |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | एक कॉल में x/y/z घटक सेट करता है। |
| [set(int idx, double value)](#set-int-double-) | इंडेक्स द्वारा वेक्टर का घटक सेट करता है। |
| [sin()](#sin--) | प्रत्येक घटक पर साइन की गणना करता है। |
| [sub(Vector3 lhs, Vector3 rhs)](#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | ऑपरेटर ओवरलोडिंग के लिए - (माइनस) |
| [toString()](#toString--) | वर्तमान [Vector3](../../com.aspose.threed/vector3) को दर्शाने वाली java.lang.String लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector3(double x, double y, double z) {#Vector3-double-double-double-}
```
public Vector3(double x, double y, double z)
```


एक नया उदाहरण प्रारंभ करता है [Vector3](../../com.aspose.threed/vector3) संरचना का।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| x | double | x निर्देशांक। |
| y | double | y निर्देशांक। |
| z | double | z निर्देशांक। |

### Vector3(FVector3 vec) {#Vector3-com.aspose.threed.FVector3-}
```
public Vector3(FVector3 vec)
```


एक नया उदाहरण प्रारंभ करता है [Vector3](../../com.aspose.threed/vector3) संरचना का।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) | x निर्देशांक। |

### Vector3(double v) {#Vector3-double-}
```
public Vector3(double v)
```


एक नया उदाहरण प्रारंभ करता है [Vector3](../../com.aspose.threed/vector3) संरचना का।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| v | double | V. |

### Vector3(Vector4 vec4) {#Vector3-com.aspose.threed.Vector4-}
```
public Vector3(Vector4 vec4)
```


एक नया उदाहरण प्रारंभ करता है [Vector3](../../com.aspose.threed/vector3) संरचना का।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| vec4 | [Vector4](../../com.aspose.threed/vector4) | Vec4. |

### Vector3() {#Vector3--}
```
public Vector3()
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

### z {#z}
```
public double z
```


The z component.

### add(Vector3 lhs, Vector3 rhs) {#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 add(Vector3 lhs, Vector3 rhs)
```


ऑपरेटर ओवरलोडिंग + के लिए

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | बायाँ वेक्टर |
| rhs | [Vector3](../../com.aspose.threed/vector3) | दायाँ वेक्टर |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### angleBetween(Vector3 dir) {#angleBetween-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir)
```


दो दिशाओं के बीच का आंतरिक कोण गणना करें। दो दिशाएँ गैर-नॉर्मलाइज़्ड वेक्टर हो सकती हैं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | तुलना करने के लिए दिशा वेक्टर |

**Returns:**
double - रेडियन में आंतरिक कोण
### angleBetween(Vector3 dir, Vector3 up) {#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir, Vector3 up)
```


दो दिशाओं के बीच का आंतरिक कोण गणना करें। दो दिशाएँ गैर-नॉर्मलाइज़्ड वेक्टर हो सकती हैं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | तुलना करने के लिए दिशा वेक्टर |
| up | [Vector3](../../com.aspose.threed/vector3) | दो दिशाओं के साझा तल का ऊपर की ओर वेक्टर |

**Returns:**
double - रेडियन में आंतरिक कोण
### clone() {#clone--}
```
public Vector3 clone()
```


वर्तमान उदाहरण को क्लोन करें

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### compareTo(Vector3 other) {#compareTo-com.aspose.threed.Vector3-}
```
public int compareTo(Vector3 other)
```


वर्तमान वेक्टर की तुलना किसी अन्य उदाहरण से करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| other | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
int
### copyFrom(Vector3 src) {#copyFrom-com.aspose.threed.Vector3-}
```
public void copyFrom(Vector3 src)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| src | [Vector3](../../com.aspose.threed/vector3) |  |

### cos() {#cos--}
```
public Vector3 cos()
```


प्रत्येक घटक पर कोसाइन की गणना करता है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### create(Vector3 v) {#create-com.aspose.threed.Vector3-}
```
public static FVector3 create(Vector3 v)
```


Vector3 को FVector3 में कास्ट करने के लिए स्पष्ट रूपांतरण ऑपरेटर।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### cross(Vector3 rhs) {#cross-com.aspose.threed.Vector3-}
```
public Vector3 cross(Vector3 rhs)
```


दो वेक्टरों का क्रॉस प्रोडक्ट।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Right hand side value. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Cross product of two [Vector3](../../com.aspose.threed/vector3)s.
### div(Vector3 lhs, Vector3 rhs) {#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 div(Vector3 lhs, Vector3 rhs)
```


ऑपरेटर ओवरलोडिंग / के लिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | बायाँ वेक्टर |
| rhs | [Vector3](../../com.aspose.threed/vector3) | दायाँ वेक्टर |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### div(Vector3 lhs, double rhs) {#div-com.aspose.threed.Vector3-double-}
```
public static Vector3 div(Vector3 lhs, double rhs)
```


ऑपरेटर ओवरलोडिंग / के लिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | बायाँ वेक्टर |
| rhs | double | The right double value |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### dot(Vector3 rhs) {#dot-com.aspose.threed.Vector3-}
```
public double dot(Vector3 rhs)
```


दो वेक्टरों का डॉट प्रोडक्ट प्राप्त करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Right hand side value. |

**Returns:**
double - The dot product of the two vectors.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


जाँचें कि दो vector3 समान हैं या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | The object to check equality. |

**Returns:**
boolean - True if all components are identically equal.
### get(int idx) {#get-int-}
```
public double get(int idx)
```


इंडेक्स द्वारा वेक्टर का घटक प्राप्त करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| idx | int |  |

**Returns:**
double - vector's component by index.
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


इस वेक्टर की लंबाई प्राप्त करता है।

**Returns:**
double - the length of this vector.
### getLength2() {#getLength2--}
```
public double getLength2()
```


लंबाई का वर्ग प्राप्त करता है।

**Returns:**
double - the square of the length.
### getOne() {#getOne--}
```
public static Vector3 getOne()
```


यूनिट वेक्टर (1, 1, 1) प्राप्त करता है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 1, 1)
### getUnitX() {#getUnitX--}
```
public static Vector3 getUnitX()
```


यूनिट वेक्टर (1, 0, 0) प्राप्त करता है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 0, 0)
### getUnitY() {#getUnitY--}
```
public static Vector3 getUnitY()
```


यूनिट वेक्टर (0, 1, 0) प्राप्त करता है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 1, 0)
### getUnitZ() {#getUnitZ--}
```
public static Vector3 getUnitZ()
```


यूनिट वेक्टर (0, 0, 1) प्राप्त करता है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 1)
### getZero() {#getZero--}
```
public static Vector3 getZero()
```


यूनिट वेक्टर (0, 0, 0) प्राप्त करता है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 0)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Vector3 का हैश कोड प्राप्त करता है।

**Returns:**
int - The hash code of the [Vector3](../../com.aspose.threed/vector3)
### mul(Vector3 lhs, Vector3 rhs) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Vector3 lhs, Vector3 rhs)
```


ऑपरेटर ओवरलोडिंग \* के लिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | बायाँ वेक्टर |
| rhs | [Vector3](../../com.aspose.threed/vector3) | दायाँ वेक्टर |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(Vector3 lhs, double rhs) {#mul-com.aspose.threed.Vector3-double-}
```
public static Vector3 mul(Vector3 lhs, double rhs)
```


ऑपरेटर ओवरलोडिंग \* के लिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | बायाँ वेक्टर |
| rhs | double | The right double value |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(double lhs, Vector3 rhs) {#mul-double-com.aspose.threed.Vector3-}
```
public static Vector3 mul(double lhs, Vector3 rhs)
```


ऑपरेटर ओवरलोडिंग \* के लिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | double | The left scalar |
| rhs | [Vector3](../../com.aspose.threed/vector3) | दायाँ वेक्टर |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### negative(Vector3 v) {#negative-com.aspose.threed.Vector3-}
```
public static Vector3 negative(Vector3 v)
```


ऑपरेटर ओवरलोडिंग के लिए -

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | The origin vector |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### normalize() {#normalize--}
```
public Vector3 normalize()
```


इस उदाहरण को सामान्यीकृत करता है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Vector3 lhs, Vector3 rhs) {#op-eq-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_eq(Vector3 lhs, Vector3 rhs)
```


Vector3 के लिए समान ऑपरेटर

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Left hand side value. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Right hand side value. |

**Returns:**
boolean - True if all components are identically equal.
### op_ne(Vector3 lhs, Vector3 rhs) {#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_ne(Vector3 lhs, Vector3 rhs)
```


Vector3 के लिए असमान ऑपरेटर

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Left hand side value. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Right hand side value. |

**Returns:**
boolean - True if two vectors are not equal.
### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


एक कॉल में x/y/z घटक सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| newX | double | The x component. |
| newY | double | The y component. |
| newZ | double | The z component. |

### set(int idx, double value) {#set-int-double-}
```
public void set(int idx, double value)
```


इंडेक्स द्वारा वेक्टर का घटक सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| idx | int |  |
| मान | double | नया मान |

### sin() {#sin--}
```
public Vector3 sin()
```


प्रत्येक घटक पर साइन की गणना करता है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### sub(Vector3 lhs, Vector3 rhs) {#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 sub(Vector3 lhs, Vector3 rhs)
```


ऑपरेटर ओवरलोडिंग के लिए - (माइनस)

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | बायाँ वेक्टर |
| rhs | [Vector3](../../com.aspose.threed/vector3) | दायाँ वेक्टर |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### toString() {#toString--}
```
public String toString()
```


वर्तमान [Vector3](../../com.aspose.threed/vector3) को दर्शाने वाली java.lang.String लौटाता है।

**Returns:**
java.lang.String - A java.lang.String that represents the current [Vector3](../../com.aspose.threed/vector3).
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

