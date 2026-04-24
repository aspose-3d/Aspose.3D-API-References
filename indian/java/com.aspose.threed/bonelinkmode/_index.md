---
title: BoneLinkMode
second_title: Aspose.3D for Java API Reference
description: एक हड्डी लिंक मोड यह दर्शाता है कि हड्डी को पदानुक्रमित संरचना में उसके पैरेंट हड्डी से कैसे जोड़ा या लिंक किया जाता है।
type: docs
weight: 267
url: /hi/java/com.aspose.threed/bonelinkmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum BoneLinkMode extends Enum<BoneLinkMode>
```

हड्डी का लिंक मोड यह दर्शाता है कि हड्डी को पदानुक्रमित संरचना में उसके पैरेंट हड्डी से कैसे जोड़ा या लिंक किया जाता है।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [ADDITIVE](#ADDITIVE) | ऐडिटिव मोड चाइल्ड हड्डियों के ट्रांसफ़ॉर्मेशन की गणना उनके अपने लोकल ट्रांसफ़ॉर्मेशन को पैरेंट हड्डियों के ट्रांसफ़ॉर्मेशन में जोड़कर करता है। |
| [NORMALIZE](#NORMALIZE) | इस मोड में, चाइल्ड हड्डियों के ट्रांसफ़ॉर्मेशन को उनके पैरेंट हड्डी के ट्रांसफ़ॉर्मेशन के सापेक्ष सामान्यीकृत किया जाता है। |
| [TOTAL_ONE](#TOTAL-ONE) | टोटल वन सुनिश्चित करता है कि पैरेंट और चाइल्ड हड्डियों के संयुक्त ट्रांसफ़ॉर्मेशन का परिणाम एक संयुक्त ट्रांसफ़ॉर्मेशन हो जो कुल लंबाई को एक इकाई तक स्केल करता है। |
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
### ADDITIVE {#ADDITIVE}
```
public static final BoneLinkMode ADDITIVE
```


ऐडिटिव मोड चाइल्ड हड्डियों के ट्रांसफ़ॉर्मेशन की गणना उनके अपने लोकल ट्रांसफ़ॉर्मेशन को पैरेंट हड्डियों के ट्रांसफ़ॉर्मेशन में जोड़कर करता है।

### NORMALIZE {#NORMALIZE}
```
public static final BoneLinkMode NORMALIZE
```


इस मोड में, चाइल्ड हड्डियों के ट्रांसफ़ॉर्मेशन को उनके पैरेंट हड्डी के ट्रांसफ़ॉर्मेशन के सापेक्ष सामान्यीकृत किया जाता है।

### TOTAL_ONE {#TOTAL-ONE}
```
public static final BoneLinkMode TOTAL_ONE
```


टोटल वन सुनिश्चित करता है कि पैरेंट और चाइल्ड हड्डियों के संयुक्त ट्रांसफ़ॉर्मेशन का परिणाम एक संयुक्त ट्रांसफ़ॉर्मेशन हो जो कुल लंबाई को एक इकाई तक स्केल करता है।

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
public static BoneLinkMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[BoneLinkMode](../../com.aspose.threed/bonelinkmode)
### values() {#values--}
```
public static BoneLinkMode[] values()
```




**Returns:**
com.aspose.threed.BoneLinkMode[]
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

