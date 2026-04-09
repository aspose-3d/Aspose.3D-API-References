---
title: WrapMode
second_title: Aspose.3D for Java API Reference
description: टेक्सचर रैप मोड।
type: docs
weight: 310
url: /hi/java/com.aspose.threed/wrapmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum WrapMode extends Enum<WrapMode>
```

टेक्सचर का रैप मोड।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [BORDER](#BORDER) | वे निर्देशांक जो सीमा [0.0, 1.0] के बाहर हैं, उन्हें निर्दिष्ट बॉर्डर रंग पर सेट किया जाता है। |
| [CLAMP](#CLAMP) | टेक्सचर को बॉर्डर पर अंतिम पिक्सेल तक क्लैंप करता है। |
| [MIRROR](#MIRROR) | टेक्सचर दोहराया जाएगा, लेकिन जब निर्देशांक का पूर्णांक भाग विषम होगा तो यह मिरर किया जाएगा। |
| [MIRROR_ONCE](#MIRROR-ONCE) | टेक्सचर एक बार मिरर किया जाएगा, और फिर अधिकतम मान तक क्लैंप किया जाएगा। |
| [WRAP](#WRAP) | मॉडल की सतह पर टेक्सचर को टाइल करता है, जिससे दोहराने वाला पैटर्न बनता है। |
## Methods

| Method | विवरण |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BORDER {#BORDER}
```
public static final WrapMode BORDER
```


वे निर्देशांक जो सीमा [0.0, 1.0] के बाहर हैं, उन्हें निर्दिष्ट बॉर्डर रंग पर सेट किया जाता है।

### CLAMP {#CLAMP}
```
public static final WrapMode CLAMP
```


टेक्सचर को बॉर्डर पर अंतिम पिक्सेल तक क्लैंप करता है।

### MIRROR {#MIRROR}
```
public static final WrapMode MIRROR
```


टेक्सचर दोहराया जाएगा, लेकिन जब निर्देशांक का पूर्णांक भाग विषम होगा तो यह मिरर किया जाएगा।

### MIRROR_ONCE {#MIRROR-ONCE}
```
public static final WrapMode MIRROR_ONCE
```


टेक्सचर एक बार मिरर किया जाएगा, और फिर अधिकतम मान तक क्लैंप किया जाएगा।

### WRAP {#WRAP}
```
public static final WrapMode WRAP
```


मॉडल की सतह पर टेक्सचर को टाइल करता है, जिससे दोहराने वाला पैटर्न बनता है।

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static WrapMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode)
### values() {#values--}
```
public static WrapMode[] values()
```




**Returns:**
com.aspose.threed.WrapMode[]
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

