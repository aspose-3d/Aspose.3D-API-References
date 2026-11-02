---
title: "TrialException"
second_title: "Aspose.3D for Java API रेफ़रेंस"
description: "जब कोई लाइसेंस लागू नहीं होता है, तो यह Scene.Open/Scene.Save में उठाया जाता है।"
type: docs
weight: 195
url: /hi/java/com.aspose.threed/trialexception/
---

**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class TrialException extends RuntimeException
```

यह Scene.Open/Scene.Save में तब उठाया जाता है जब कोई लाइसेंस लागू नहीं किया गया हो। आप SuppressTrialException को true सेट करके इस अपवाद को बंद कर सकते हैं।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [TrialException(String msg)](#TrialException-java.lang.String-) | का कन्स्ट्रक्टर [TrialException](../../com.aspose.threed/trialexception) |
| [TrialException()](#TrialException--) | का कन्स्ट्रक्टर [TrialException](../../com.aspose.threed/trialexception) |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
| [getLocalizedMessage()](#getLocalizedMessage--) |  |
| [getMessage()](#getMessage--) |  |
| [getStackTrace()](#getStackTrace--) |  |
| [getSuppressTrialException()](#getSuppressTrialException--) | इसे true सेट करने से अनलाइसेंस्ड उपयोग के लिए ट्रायल अपवाद को दबाया जाता है, लेकिन प्रतिबंध नहीं हटेंगे। |
| [getSuppressed()](#getSuppressed--) |  |
| [hashCode()](#hashCode--) |  |
| [initCause(Throwable arg0)](#initCause-java.lang.Throwable-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [printStackTrace()](#printStackTrace--) |  |
| [printStackTrace(PrintStream arg0)](#printStackTrace-java.io.PrintStream-) |  |
| [printStackTrace(PrintWriter arg0)](#printStackTrace-java.io.PrintWriter-) |  |
| [setStackTrace(StackTraceElement[] arg0)](#setStackTrace-java.lang.StackTraceElement---) |  |
| [setSuppressTrialException(boolean value)](#setSuppressTrialException-boolean-) | इसे true सेट करने से अनलाइसेंस्ड उपयोग के लिए ट्रायल अपवाद को दबाया जाता है, लेकिन प्रतिबंध नहीं हटेंगे। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TrialException(String msg) {#TrialException-java.lang.String-}
```
public TrialException(String msg)
```


का कन्स्ट्रक्टर [TrialException](../../com.aspose.threed/trialexception)

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| msg | java.lang.String |  |

### TrialException() {#TrialException--}
```
public TrialException()
```


का कन्स्ट्रक्टर [TrialException](../../com.aspose.threed/trialexception)

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fillInStackTrace() {#fillInStackTrace--}
```
public synchronized Throwable fillInStackTrace()
```




**Returns:**
java.lang.Throwable
### getCause() {#getCause--}
```
public synchronized Throwable getCause()
```




**Returns:**
java.lang.Throwable
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLocalizedMessage() {#getLocalizedMessage--}
```
public String getLocalizedMessage()
```




**Returns:**
java.lang.String
### getMessage() {#getMessage--}
```
public String getMessage()
```




**Returns:**
java.lang.String
### getStackTrace() {#getStackTrace--}
```
public StackTraceElement[] getStackTrace()
```




**Returns:**
java.lang.StackTraceElement[]
### getSuppressTrialException() {#getSuppressTrialException--}
```
public static boolean getSuppressTrialException()
```


इसे true सेट करने से अनलाइसेंस्ड उपयोग के लिए ट्रायल अपवाद को दबाया जाता है, लेकिन प्रतिबंध नहीं हटेंगे। प्रतिबंध हटाने के लिए कृपया एक उचित लाइसेंस का उपयोग करें। और इसे true सेट करना यह भी दर्शाता है कि आप अनलाइसेंस्ड प्रतिबंधों से अवगत हैं।

**Returns:**
boolean - इसे true सेट करने से अनलाइसेंस्ड उपयोग के लिए ट्रायल अपवाद को दबाया जाता है, लेकिन प्रतिबंध नहीं हटेंगे। प्रतिबंध हटाने के लिए कृपया एक उचित लाइसेंस का उपयोग करें। और इसे true सेट करना यह भी दर्शाता है कि आप अनलाइसेंस्ड प्रतिबंधों से अवगत हैं।
### getSuppressed() {#getSuppressed--}
```
public final synchronized Throwable[] getSuppressed()
```




**Returns:**
java.lang.Throwable[]
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initCause(Throwable arg0) {#initCause-java.lang.Throwable-}
```
public synchronized Throwable initCause(Throwable arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

**Returns:**
java.lang.Throwable
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### printStackTrace() {#printStackTrace--}
```
public void printStackTrace()
```




### printStackTrace(PrintStream arg0) {#printStackTrace-java.io.PrintStream-}
```
public void printStackTrace(PrintStream arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.StackTraceElement[] |  |

### setSuppressTrialException(boolean value) {#setSuppressTrialException-boolean-}
```
public static void setSuppressTrialException(boolean value)
```


इसे true सेट करने से अनलाइसेंस्ड उपयोग के लिए ट्रायल अपवाद को दबाया जाता है, लेकिन प्रतिबंध नहीं हटेंगे। प्रतिबंध हटाने के लिए कृपया एक उचित लाइसेंस का उपयोग करें। और इसे true सेट करना यह भी दर्शाता है कि आप अनलाइसेंस्ड प्रतिबंधों से अवगत हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

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

