---
title: मापी गई
second_title: Aspose.3D for Java API Reference
description: मेटर्ड कुंजी सेट करने के लिए विधियाँ प्रदान करता है।
type: docs
weight: 103
url: /hi/java/com.aspose.threed/metered/
---

**Inheritance:**
java.lang.Object
```
public class Metered
```

मेटर्ड कुंजी सेट करने के लिए विधियाँ प्रदान करता है।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Metered()](#Metered--) | इस वर्ग की नई इंस्टेंस को प्रारंभ करता है। |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConsumptionCredit()](#getConsumptionCredit--) | उपभोग क्रेडिट प्राप्त करता है |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | उपभोग फ़ाइल आकार प्राप्त करता है |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | मापी गई सार्वजनिक और निजी कुंजी सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Metered() {#Metered--}
```
public Metered()
```


इस वर्ग की नई इंस्टेंस को प्रारंभ करता है।

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
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
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


उपभोग क्रेडिट प्राप्त करता है

**Returns:**
डबल - उपभोग मात्रा
### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


उपभोग फ़ाइल आकार प्राप्त करता है

**Returns:**
डबल - उपभोग मात्रा
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


मापी गई सार्वजनिक और निजी कुंजी सेट करता है। यदि आप मेटर्ड लाइसेंस खरीदते हैं, तो एप्लिकेशन शुरू करने पर इस API को कॉल किया जाना चाहिए, सामान्यतः यह पर्याप्त है। हालांकि, यदि उपभोग डेटा अपलोड करने में लगातार विफलता होती है और 24 घंटे से अधिक हो जाता है, तो लाइसेंस को मूल्यांकन स्थिति में सेट किया जाएगा; ऐसी स्थिति से बचने के लिए, आपको नियमित रूप से लाइसेंस स्थिति जाँचनी चाहिए, यदि यह मूल्यांकन स्थिति है, तो इस API को फिर से कॉल करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| publicKey | java.lang.String | सार्वजनिक कुंजी |
| privateKey | java.lang.String | निजी कुंजी |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

