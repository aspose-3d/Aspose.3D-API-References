---
title: FVector3
second_title: Aspose.3D for Java API Reference
description: तीन घटकों वाला फ़्लोट वेक्टर।
type: docs
weight: 60
url: /hi/java/com.aspose.threed/fvector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector3 implements Struct<FVector3>, Serializable
```

तीन घटकों वाला फ़्लोट वेक्टर।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [FVector3(float x, float y, float z)](#FVector3-float-float-float-) | नए [FVector3](../../com.aspose.threed/fvector3) का एक नया उदाहरण प्रारंभ करता है। |
| [FVector3(Vector3 vec)](#FVector3-com.aspose.threed.Vector3-) | नए [FVector3](../../com.aspose.threed/fvector3) का एक नया उदाहरण प्रारंभ करता है। |
| [FVector3(Vector4 vec)](#FVector3-com.aspose.threed.Vector4-) | नया उदाहरण प्रारंभ करता है [FVector4](../../com.aspose.threed/fvector4) का। |
| [FVector3()](#FVector3--) |  |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [x](#x) | The x component. |
| [y](#y) | The y component. |
| [z](#z) | The y component. |
## Methods

| Method | विवरण |
| --- | --- |
| [add(FVector3 a, FVector3 b)](#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \+ ऑपरेटर ओवरलोडिंग |
| [clone()](#clone--) |  |
| [copyFrom(FVector3 src)](#copyFrom-com.aspose.threed.FVector3-) |  |
| [create(FVector3 v)](#create-com.aspose.threed.FVector3-) | FVector3 को Vector3 में कास्ट करने के लिए स्पष्ट रूपांतरण ऑपरेटर |
| [cross(FVector3 rhs)](#cross-com.aspose.threed.FVector3-) | दो वेक्टरों का क्रॉस प्रोडक्ट। |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOne()](#getOne--) | सभी घटकों के साथ इकाई स्केल वेक्टर सभी 1 हैं |
| [getZero()](#getZero--) | शून्य वेक्टर। |
| [hashCode()](#hashCode--) |  |
| [mul(FVector3 a, float b)](#mul-com.aspose.threed.FVector3-float-) | \* ऑपरेटर ओवरलोडिंग |
| [negative(FVector3 a)](#negative-com.aspose.threed.FVector3-) | \- ऑपरेटर ओवरलोडिंग |
| [normalize()](#normalize--) | इस उदाहरण को सामान्यीकृत करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sub(FVector3 a, FVector3 b)](#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \- ऑपरेटर ओवरलोडिंग |
| [toString()](#toString--) | एक स्ट्रिंग लौटाता है जो [FVector3](../../com.aspose.threed/fvector3) को दर्शाती है |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector3(float x, float y, float z) {#FVector3-float-float-float-}
```
public FVector3(float x, float y, float z)
```


नए [FVector3](../../com.aspose.threed/fvector3) का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| x | फ़्लोट | वेक्टर का X घटक |
| y | फ़्लोट | वेक्टर का Y घटक |
| z | फ़्लोट | वेक्टर का Z घटक |

### FVector3(Vector3 vec) {#FVector3-com.aspose.threed.Vector3-}
```
public FVector3(Vector3 vec)
```


नए [FVector3](../../com.aspose.threed/fvector3) का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vector3 डबल प्रकार में |

### FVector3(Vector4 vec) {#FVector3-com.aspose.threed.Vector4-}
```
public FVector3(Vector4 vec)
```


नया उदाहरण प्रारंभ करता है [FVector4](../../com.aspose.threed/fvector4) का।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| vec | [Vector4](../../com.aspose.threed/vector4) | Vector4 डबल प्रकार में |

### FVector3() {#FVector3--}
```
public FVector3()
```


### x {#x}
```
public float x
```


The x component.

### y {#y}
```
public float y
```


The y component.

### z {#z}
```
public float z
```


The y component.

### add(FVector3 a, FVector3 b) {#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 add(FVector3 a, FVector3 b)
```


\+ ऑपरेटर ओवरलोडिंग

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | पहला वेक्टर |
| b | [FVector3](../../com.aspose.threed/fvector3) | दूसरा वेक्टर |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### clone() {#clone--}
```
public FVector3 clone()
```


वर्तमान उदाहरण को क्लोन करें

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### copyFrom(FVector3 src) {#copyFrom-com.aspose.threed.FVector3-}
```
public void copyFrom(FVector3 src)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| src | [FVector3](../../com.aspose.threed/fvector3) |  |

### create(FVector3 v) {#create-com.aspose.threed.FVector3-}
```
public static Vector3 create(FVector3 v)
```


FVector3 को Vector3 में कास्ट करने के लिए स्पष्ट रूपांतरण ऑपरेटर

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| v | [FVector3](../../com.aspose.threed/fvector3) | Vector3 फ़्लोट प्रकार में |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### cross(FVector3 rhs) {#cross-com.aspose.threed.FVector3-}
```
public FVector3 cross(FVector3 rhs)
```


दो वेक्टरों का क्रॉस प्रोडक्ट।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| rhs | [FVector3](../../com.aspose.threed/fvector3) | Right hand side value. |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Cross product of two [FVector3](../../com.aspose.threed/fvector3)s.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOne() {#getOne--}
```
public static FVector3 getOne()
```


सभी घटकों के साथ इकाई स्केल वेक्टर सभी 1 हैं

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The unit scale vector with all components are all 1
### getZero() {#getZero--}
```
public static FVector3 getZero()
```


शून्य वेक्टर।

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The Zero vector.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### mul(FVector3 a, float b) {#mul-com.aspose.threed.FVector3-float-}
```
public static FVector3 mul(FVector3 a, float b)
```


\* ऑपरेटर ओवरलोडिंग

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | पहला वेक्टर |
| b | फ़्लोट | दूसरा वेक्टर |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The product of two vectors
### negative(FVector3 a) {#negative-com.aspose.threed.FVector3-}
```
public static FVector3 negative(FVector3 a)
```


\- ऑपरेटर ओवरलोडिंग

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | इनपुट वेक्टर |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The negative vector
### normalize() {#normalize--}
```
public FVector3 normalize()
```


इस उदाहरण को सामान्यीकृत करता है।

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### sub(FVector3 a, FVector3 b) {#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 sub(FVector3 a, FVector3 b)
```


\- ऑपरेटर ओवरलोडिंग

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | पहला वेक्टर |
| b | [FVector3](../../com.aspose.threed/fvector3) | दूसरा वेक्टर |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The difference of two vectors
### toString() {#toString--}
```
public String toString()
```


एक स्ट्रिंग लौटाता है जो [FVector3](../../com.aspose.threed/fvector3) को दर्शाती है

**Returns:**
java.lang.String - इस वेक्टर का स्ट्रिंग प्रतिनिधित्व।
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

