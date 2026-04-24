---
title: इंटरपोलेशन
second_title: Aspose.3D for Java API Reference
description: की फ्रेम्स इंटरपोलेशन प्रकार।
type: docs
weight: 283
url: /hi/java/com.aspose.threed/interpolation/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Interpolation extends Enum<Interpolation>
```

की फ्रेम का इंटरपोलेशन प्रकार।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [BEZIER](#BEZIER) | एक बेज़ियर या हर्माइट स्प्लाइन। |
| [B_SPLINE](#B-SPLINE) | बेसिस स्प्लाइन्स को नियंत्रण बिंदुओं की श्रृंखला द्वारा परिभाषित किया जाता है, जिसके लिए वक्र केवल पहले और अंतिम बिंदु से होकर गुजरने की गारंटी देता है। |
| [CARDINAL_SPLINE](#CARDINAL-SPLINE) | एक कार्डिनल स्प्लाइन एक क्यूबिक हर्माइट स्प्लाइन है जिसका टैन्जेंट एंडपॉइंट्स और एक टेंशन पैरामीटर द्वारा परिभाषित होता है। |
| [CONSTANT](#CONSTANT) | मान अगले खंड तक पहले बिंदु के मान के समान स्थिर रहेगा। |
| [LINEAR](#LINEAR) | लीनियर इंटरपोलेशन दो बिंदुओं के बीच एक सीधी रेखा है। |
| [TCB_SPLINE](#TCB-SPLINE) | इसे कोकेनेक-बार्टेल्स स्प्लाइन भी कहा जाता है, टैन्जेंट का व्यवहार टेंशन/बायस/कंटिन्युटी द्वारा परिभाषित होता है। |
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
### BEZIER {#BEZIER}
```
public static final Interpolation BEZIER
```


एक बेज़ियर या हर्माइट स्प्लाइन।

### B_SPLINE {#B-SPLINE}
```
public static final Interpolation B_SPLINE
```


बेसिस स्प्लाइन्स को नियंत्रण बिंदुओं की श्रृंखला द्वारा परिभाषित किया जाता है, जिसके लिए वक्र केवल पहले और अंतिम बिंदु से होकर गुजरने की गारंटी देता है।

### CARDINAL_SPLINE {#CARDINAL-SPLINE}
```
public static final Interpolation CARDINAL_SPLINE
```


एक कार्डिनल स्प्लाइन एक क्यूबिक हर्माइट स्प्लाइन है जिसका टैन्जेंट एंडपॉइंट्स और एक टेंशन पैरामीटर द्वारा परिभाषित होता है।

### CONSTANT {#CONSTANT}
```
public static final Interpolation CONSTANT
```


मान अगले खंड तक पहले बिंदु के मान के समान स्थिर रहेगा।

### LINEAR {#LINEAR}
```
public static final Interpolation LINEAR
```


लीनियर इंटरपोलेशन दो बिंदुओं के बीच एक सीधी रेखा है।

### TCB_SPLINE {#TCB-SPLINE}
```
public static final Interpolation TCB_SPLINE
```


इसे कोकेनेक-बार्टेल्स स्प्लाइन भी कहा जाता है, टैन्जेंट का व्यवहार टेंशन/बायस/कंटिन्युटी द्वारा परिभाषित होता है।

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
public static Interpolation valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[Interpolation](../../com.aspose.threed/interpolation)
### values() {#values--}
```
public static Interpolation[] values()
```




**Returns:**
com.aspose.threed.Interpolation[]
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

