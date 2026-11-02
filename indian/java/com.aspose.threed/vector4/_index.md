---
title: "Vector4"
second_title: "Aspose.3D for Java API रेफ़रेंस"
description: "चार घटकों वाला वेक्टर।"
type: docs
weight: 203
url: /hi/java/com.aspose.threed/vector4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector4 implements Comparable<Vector4>, Struct<Vector4>, Serializable
```

चार घटकों वाला वेक्टर।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [Vector4(Vector3 vec, double w)](#Vector4-com.aspose.threed.Vector3-double-) | नया [Vector4](../../com.aspose.threed/vector4) स्ट्रक्चर का एक नया उदाहरण प्रारंभ करता है। |
| [Vector4(Vector3 vec)](#Vector4-com.aspose.threed.Vector3-) | नया [Vector4](../../com.aspose.threed/vector4) स्ट्रक्चर का एक नया उदाहरण प्रारंभ करता है। |
| [Vector4(FVector4 vec)](#Vector4-com.aspose.threed.FVector4-) | नया [Vector4](../../com.aspose.threed/vector4) स्ट्रक्चर का एक नया उदाहरण प्रारंभ करता है। |
| [Vector4(double x, double y, double z)](#Vector4-double-double-double-) | नया [Vector4](../../com.aspose.threed/vector4) स्ट्रक्चर का एक नया उदाहरण प्रारंभ करता है। |
| [Vector4(double x, double y, double z, double w)](#Vector4-double-double-double-double-) | नया [Vector4](../../com.aspose.threed/vector4) स्ट्रक्चर का एक नया उदाहरण प्रारंभ करता है। |
| [Vector4()](#Vector4--) |  |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [w](#w) | w घटक। |
| [x](#x) | x घटक। |
| [y](#y) | y घटक। |
| [z](#z) | z घटक। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [add(Vector4 lhs, Vector4 rhs)](#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | ऑपरेटर ओवरलोडिंग + के लिए |
| [clone()](#clone--) |  |
| [compareTo(Vector4 other)](#compareTo-com.aspose.threed.Vector4-) | वर्तमान वेक्टर की तुलना किसी अन्य उदाहरण से करें। |
| [copyFrom(Vector4 src)](#copyFrom-com.aspose.threed.Vector4-) |  |
| [create(Vector4 v)](#create-com.aspose.threed.Vector4-) | Vector4 को FVector4 में कास्ट करने के लिए स्पष्ट रूपांतरण ऑपरेटर |
| [equals(Object obj)](#equals-java.lang.Object-) | जाँचें कि दो वेक्टर बराबर हैं |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | इस वेक्टर का हैश कोड प्राप्त करता है |
| [mul(Vector4 lhs, Vector4 rhs)](#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | ऑपरेटर ओवरलोडिंग \* के लिए |
| [mul(Vector4 lhs, double rhs)](#mul-com.aspose.threed.Vector4-double-) | ऑपरेटर ओवरलोडिंग \* के लिए |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | वेक्टर के xyz घटकों को एक साथ सेट करता है, w को 1 पर सेट किया जाएगा |
| [set(double newX, double newY, double newZ, double newW)](#set-double-double-double-double-) | वेक्टर के सभी घटकों को एक साथ सेट करता है |
| [sub(Vector4 lhs, Vector4 rhs)](#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | ऑपरेटर ओवरलोडिंग के लिए - (माइनस) |
| [toString()](#toString--) | वर्तमान [Vector4](../../com.aspose.threed/vector4) को दर्शाने वाली java.lang.String लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector4(Vector3 vec, double w) {#Vector4-com.aspose.threed.Vector3-double-}
```
public Vector4(Vector3 vec, double w)
```


नया [Vector4](../../com.aspose.threed/vector4) स्ट्रक्चर का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | वेक्त। |
| w | double | चौड़ाई। |

### Vector4(Vector3 vec) {#Vector4-com.aspose.threed.Vector3-}
```
public Vector4(Vector3 vec)
```


नया [Vector4](../../com.aspose.threed/vector4) स्ट्रक्चर का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | वेक्त। |

### Vector4(FVector4 vec) {#Vector4-com.aspose.threed.FVector4-}
```
public Vector4(FVector4 vec)
```


नया [Vector4](../../com.aspose.threed/vector4) स्ट्रक्चर का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) | वेक्त। |

### Vector4(double x, double y, double z) {#Vector4-double-double-double-}
```
public Vector4(double x, double y, double z)
```


नया [Vector4](../../com.aspose.threed/vector4) स्ट्रक्चर का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | double | x निर्देशांक। |
| y | double | y निर्देशांक। |
| z | double | z निर्देशांक। |

### Vector4(double x, double y, double z, double w) {#Vector4-double-double-double-double-}
```
public Vector4(double x, double y, double z, double w)
```


नया [Vector4](../../com.aspose.threed/vector4) स्ट्रक्चर का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | double | x निर्देशांक। |
| y | double | y निर्देशांक। |
| z | double | z निर्देशांक। |
| w | double | चौड़ाई। |

### Vector4() {#Vector4--}
```
public Vector4()
```


### w {#w}
```
public double w
```


w घटक।

### x {#x}
```
public double x
```


x घटक।

### y {#y}
```
public double y
```


y घटक।

### z {#z}
```
public double z
```


z घटक।

### add(Vector4 lhs, Vector4 rhs) {#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 add(Vector4 lhs, Vector4 rhs)
```


ऑपरेटर ओवरलोडिंग + के लिए

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | बायाँ वेक्टर |
| rhs | [Vector4](../../com.aspose.threed/vector4) | दायाँ वेक्टर |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### clone() {#clone--}
```
public Vector4 clone()
```


वर्तमान उदाहरण को क्लोन करें

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### compareTo(Vector4 other) {#compareTo-com.aspose.threed.Vector4-}
```
public int compareTo(Vector4 other)
```


वर्तमान वेक्टर की तुलना किसी अन्य उदाहरण से करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
int
### copyFrom(Vector4 src) {#copyFrom-com.aspose.threed.Vector4-}
```
public void copyFrom(Vector4 src)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| src | [Vector4](../../com.aspose.threed/vector4) |  |

### create(Vector4 v) {#create-com.aspose.threed.Vector4-}
```
public static FVector4 create(Vector4 v)
```


Vector4 को FVector4 में कास्ट करने के लिए स्पष्ट रूपांतरण ऑपरेटर

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| v | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


जाँचें कि दो वेक्टर बराबर हैं

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस वेक्टर का हैश कोड प्राप्त करता है

**Returns:**
int
### mul(Vector4 lhs, Vector4 rhs) {#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Vector4 lhs, Vector4 rhs)
```


ऑपरेटर ओवरलोडिंग \* के लिए

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | बायाँ वेक्टर |
| rhs | [Vector4](../../com.aspose.threed/vector4) | दायाँ वेक्टर |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### mul(Vector4 lhs, double rhs) {#mul-com.aspose.threed.Vector4-double-}
```
public static Vector4 mul(Vector4 lhs, double rhs)
```


ऑपरेटर ओवरलोडिंग \* के लिए

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | बायाँ वेक्टर |
| rhs | double | दाएँ डबल मान |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


वेक्टर के xyz घटकों को एक साथ सेट करता है, w को 1 पर सेट किया जाएगा

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newX | double | नया X घटक। |
| newY | double | नया Y घटक। |
| newZ | double | नया Z घटक। |

### set(double newX, double newY, double newZ, double newW) {#set-double-double-double-double-}
```
public void set(double newX, double newY, double newZ, double newW)
```


वेक्टर के सभी घटकों को एक साथ सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newX | double | नया X घटक। |
| newY | double | नया Y घटक। |
| newZ | double | नया Z घटक। |
| newW | double | नया W घटक। |

### sub(Vector4 lhs, Vector4 rhs) {#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 sub(Vector4 lhs, Vector4 rhs)
```


ऑपरेटर ओवरलोडिंग के लिए - (माइनस)

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | बायाँ वेक्टर |
| rhs | [Vector4](../../com.aspose.threed/vector4) | दायाँ वेक्टर |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### toString() {#toString--}
```
public String toString()
```


वर्तमान [Vector4](../../com.aspose.threed/vector4) को दर्शाने वाली java.lang.String लौटाता है।

**Returns:**
java.lang.String - एक java.lang.String जो वर्तमान [Vector4](../../com.aspose.threed/vector4) को दर्शाता है।
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

