---
title: SplitMeshPolicy
second_title: Aspose.3D for Java API Reference
description: सब-मे़श के बीच वर्टेक्स/कंट्रोल पॉइंट डेटा साझा करें या प्रत्येक सब-मे़श का अपना संकुचित डेटा हो।
type: docs
weight: 302
url: /hi/java/com.aspose.threed/splitmeshpolicy/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SplitMeshPolicy extends Enum<SplitMeshPolicy>
```

सब-मे़श के बीच वर्टेक्स/कंट्रोल पॉइंट डेटा साझा करें या प्रत्येक सब-मे़श का अपना संकुचित डेटा हो।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [CLONE_DATA](#CLONE-DATA) | नियंत्रण बिंदुओं और शीर्ष बिंदु तत्व डेटा की प्रतिलिपि बनाई जाएगी। |
| [COMPACT_DATA](#COMPACT-DATA) | केवल उपयोग किए गए नियंत्रण बिंदुओं और शीर्ष बिंदु तत्व डेटा को उप-मे़ष में कॉपी किया जाएगा। |
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
### CLONE_DATA {#CLONE-DATA}
```
public static final SplitMeshPolicy CLONE_DATA
```


नियंत्रण बिंदुओं और शीर्ष बिंदु तत्व डेटा की प्रतिलिपि बनाई जाएगी।

### COMPACT_DATA {#COMPACT-DATA}
```
public static final SplitMeshPolicy COMPACT_DATA
```


केवल उपयोग किए गए नियंत्रण बिंदुओं और शीर्ष बिंदु तत्व डेटा को उप-मे़ष में कॉपी किया जाएगा।

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
public static SplitMeshPolicy valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy)
### values() {#values--}
```
public static SplitMeshPolicy[] values()
```




**Returns:**
com.aspose.threed.SplitMeshPolicy[]
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

