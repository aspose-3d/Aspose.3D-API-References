---
title: ShaderSet
second_title: Aspose.3D for Java API Reference
description: प्रत्येक प्रकार की सामग्री के लिए शेडर प्रोग्राम।
type: docs
weight: 166
url: /hi/java/com.aspose.threed/shaderset/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class ShaderSet implements Closeable
```

प्रत्येक प्रकार की सामग्री के लिए शेडर प्रोग्राम।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [ShaderSet()](#ShaderSet--) | [ShaderSet](../../com.aspose.threed/shaderset) का इंस्टेंस बनाएं |
## Methods

| Method | विवरण |
| --- | --- |
| [close()](#close--) | इस इंस्टेंस को डिस्पोज करें और सभी शेडर प्रोग्राम रिलीज़ करें। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | जब आवश्यक शेडर उपलब्ध नहीं हो तो फॉलबैक शेडर प्राप्त करता है |
| [getLambert()](#getLambert--) | लैम्बर्ट सामग्री को रेंडर करने के लिए उपयोग किए जाने वाले शेडर को प्राप्त करता है |
| [getPbr()](#getPbr--) | PBR सामग्री को रेंडर करने के लिए उपयोग किए जाने वाले शेडर को प्राप्त करता है |
| [getPhong()](#getPhong--) | फॉन्ग सामग्री को रेंडर करने के लिए उपयोग किए जाने वाले शेडर को प्राप्त करता है |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFallback(ShaderProgram value)](#setFallback-com.aspose.threed.ShaderProgram-) | जब आवश्यक शेडर उपलब्ध नहीं हो तो फॉलबैक शेडर सेट करता है |
| [setLambert(ShaderProgram value)](#setLambert-com.aspose.threed.ShaderProgram-) | लैम्बर्ट सामग्री को रेंडर करने के लिए उपयोग किए जाने वाले शेडर को सेट करता है |
| [setPbr(ShaderProgram value)](#setPbr-com.aspose.threed.ShaderProgram-) | PBR सामग्री को रेंडर करने के लिए उपयोग किए जाने वाले शेडर को सेट करता है |
| [setPhong(ShaderProgram value)](#setPhong-com.aspose.threed.ShaderProgram-) | फॉन्ग सामग्री को रेंडर करने के लिए उपयोग किए जाने वाले शेडर को सेट करता है |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderSet() {#ShaderSet--}
```
public ShaderSet()
```


[ShaderSet](../../com.aspose.threed/shaderset) का इंस्टेंस बनाएं

### close() {#close--}
```
public void close()
```


इस इंस्टेंस को डिस्पोज करें और सभी शेडर प्रोग्राम रिलीज़ करें।

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
### getFallback() {#getFallback--}
```
public ShaderProgram getFallback()
```


जब आवश्यक शेडर उपलब्ध नहीं हो तो फॉलबैक शेडर प्राप्त करता है

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the fallback shader when required shader is unavailable
### getLambert() {#getLambert--}
```
public ShaderProgram getLambert()
```


लैम्बर्ट सामग्री को रेंडर करने के लिए उपयोग किए जाने वाले शेडर को प्राप्त करता है

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the lambert material
### getPbr() {#getPbr--}
```
public ShaderProgram getPbr()
```


PBR सामग्री को रेंडर करने के लिए उपयोग किए जाने वाले शेडर को प्राप्त करता है

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the PBR material
### getPhong() {#getPhong--}
```
public ShaderProgram getPhong()
```


फॉन्ग सामग्री को रेंडर करने के लिए उपयोग किए जाने वाले शेडर को प्राप्त करता है

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the phong material
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




### setFallback(ShaderProgram value) {#setFallback-com.aspose.threed.ShaderProgram-}
```
public void setFallback(ShaderProgram value)
```


जब आवश्यक शेडर उपलब्ध नहीं हो तो फॉलबैक शेडर सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | नया मान |

### setLambert(ShaderProgram value) {#setLambert-com.aspose.threed.ShaderProgram-}
```
public void setLambert(ShaderProgram value)
```


लैम्बर्ट सामग्री को रेंडर करने के लिए उपयोग किए जाने वाले शेडर को सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | नया मान |

### setPbr(ShaderProgram value) {#setPbr-com.aspose.threed.ShaderProgram-}
```
public void setPbr(ShaderProgram value)
```


PBR सामग्री को रेंडर करने के लिए उपयोग किए जाने वाले शेडर को सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | नया मान |

### setPhong(ShaderProgram value) {#setPhong-com.aspose.threed.ShaderProgram-}
```
public void setPhong(ShaderProgram value)
```


फॉन्ग सामग्री को रेंडर करने के लिए उपयोग किए जाने वाले शेडर को सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | नया मान |

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

