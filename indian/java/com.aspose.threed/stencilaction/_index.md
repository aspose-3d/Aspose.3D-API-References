---
title: StencilAction
second_title: Aspose.3D for Java API Reference
description: स्टेंसिल टेस्ट क्रियाएँ
type: docs
weight: 303
url: /hi/java/com.aspose.threed/stencilaction/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum StencilAction extends Enum<StencilAction>
```

स्टेंसिल टेस्ट क्रियाएँ
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [DECREMENT](#DECREMENT) | वर्तमान स्टेंसिल बफ़र मान को बढ़ाता है, 0 पर क्लैंप करता है। |
| [DECREMENT_WRAP](#DECREMENT-WRAP) | वर्तमान स्टेंसिल बफ़र मान को घटाता है और जब यह शून्य तक पहुँचता है तो इसे अधिकतम मान पर रैप करता है। |
| [INCREMENT](#INCREMENT) | वर्तमान स्टेंसिल बफ़र मान को बढ़ाता है, अधिकतम मान पर क्लैंप करता है। |
| [INCREMENT_WRAP](#INCREMENT-WRAP) | वर्तमान स्टेंसिल बफ़र मान को बढ़ाता है और जब यह अधिकतम मान तक पहुँचता है तो इसे शून्य पर रैप करता है। |
| [INVERT](#INVERT) | बिट-वार वर्तमान स्टेंसिल बफ़र मान को उलटता है। |
| [KEEP](#KEEP) | वर्तमान मान को रखें |
| [REPLACE](#REPLACE) | स्टेंसिल बफ़र को ref पर सेट करता है जहाँ यह [RenderState.getStencilReference](../../com.aspose.threed/renderstate\#getStencilReference) में परिभाषित है। |
| [ZERO](#ZERO) | स्टेंसिल बफ़र मान को 0 पर सेट करता है |
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
### DECREMENT {#DECREMENT}
```
public static final StencilAction DECREMENT
```


वर्तमान स्टेंसिल बफ़र मान को बढ़ाता है, 0 पर क्लैंप करता है।

### DECREMENT_WRAP {#DECREMENT-WRAP}
```
public static final StencilAction DECREMENT_WRAP
```


वर्तमान स्टेंसिल बफ़र मान को घटाता है और जब यह शून्य तक पहुँचता है तो इसे अधिकतम मान पर रैप करता है।

### INCREMENT {#INCREMENT}
```
public static final StencilAction INCREMENT
```


वर्तमान स्टेंसिल बफ़र मान को बढ़ाता है, अधिकतम मान पर क्लैंप करता है।

### INCREMENT_WRAP {#INCREMENT-WRAP}
```
public static final StencilAction INCREMENT_WRAP
```


वर्तमान स्टेंसिल बफ़र मान को बढ़ाता है और जब यह अधिकतम मान तक पहुँचता है तो इसे शून्य पर रैप करता है।

### INVERT {#INVERT}
```
public static final StencilAction INVERT
```


बिट-वार वर्तमान स्टेंसिल बफ़र मान को उलटता है।

### KEEP {#KEEP}
```
public static final StencilAction KEEP
```


वर्तमान मान को रखें

### REPLACE {#REPLACE}
```
public static final StencilAction REPLACE
```


स्टेंसिल बफ़र को ref पर सेट करता है जहाँ यह [RenderState.getStencilReference](../../com.aspose.threed/renderstate\#getStencilReference) में परिभाषित है।

### ZERO {#ZERO}
```
public static final StencilAction ZERO
```


स्टेंसिल बफ़र मान को 0 पर सेट करता है

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
public static StencilAction valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction)
### values() {#values--}
```
public static StencilAction[] values()
```




**Returns:**
com.aspose.threed.StencilAction[]
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

