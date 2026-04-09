---
title: ShaderTechnique
second_title: Aspose.3D for Java API Reference
description: एक शेडर तकनीक एक ठोस रेंडरिंग कार्यान्वयन का प्रतिनिधित्व करती है।
type: docs
weight: 169
url: /hi/java/com.aspose.threed/shadertechnique/
---

**Inheritance:**
java.lang.Object
```
public class ShaderTechnique
```

एक शेडर तकनीक एक ठोस रेंडरिंग कार्यान्वयन का प्रतिनिधित्व करती है।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [ShaderTechnique()](#ShaderTechnique--) | एक नया उदाहरण प्रारंभ करता है [ShaderTechnique](../../com.aspose.threed/shadertechnique) क्लास। |
## Methods

| Method | विवरण |
| --- | --- |
| [addBinding(String property, String shaderParameter)](#addBinding-java.lang.String-java.lang.String-) | डायनामिक प्रॉपर्टी को शेडर पैरामीटर से बाइंड करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | इस तकनीक का विवरण प्राप्त करता है। |
| [getRenderAPI()](#getRenderAPI--) | इस तकनीक द्वारा उपयोग किए गए रेंडरिंग API को प्राप्त करता है। |
| [getRenderAPIVersion()](#getRenderAPIVersion--) | रेंडरिंग API का संस्करण प्राप्त करता है। |
| [getShaderContent()](#getShaderContent--) | एक एम्बेडेड शेडर स्क्रिप्ट की सामग्री प्राप्त करता है। |
| [getShaderEntry()](#getShaderEntry--) | शेडर का एंट्री पॉइंट प्राप्त करता है, कुछ शेडर जैसे HLSL में कस्टमाइज़्ड एंट्री हो सकती हैं। |
| [getShaderFile()](#getShaderFile--) | बाहरी शेडर फ़ाइल का फ़ाइलनाम प्राप्त करता है। |
| [getShaderLanguage()](#getShaderLanguage--) | इस तकनीक द्वारा उपयोग की गई शेडर भाषा प्राप्त करता है। |
| [getShaderParameters()](#getShaderParameters--) | शेडर पैरामीटर परिभाषा प्राप्त करता है। |
| [getShaderVersion()](#getShaderVersion--) | इस तकनीक द्वारा उपयोग किए गए शेडर संस्करण को प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDescription(String value)](#setDescription-java.lang.String-) | इस तकनीक का विवरण सेट करता है |
| [setRenderAPI(String value)](#setRenderAPI-java.lang.String-) | इस तकनीक द्वारा उपयोग किए गए रेंडरिंग API को सेट करता है |
| [setRenderAPIVersion(String value)](#setRenderAPIVersion-java.lang.String-) | रेंडरिंग API का संस्करण सेट करता है। |
| [setShaderContent(byte[] value)](#setShaderContent-byte---) | एक एम्बेडेड शेडर स्क्रिप्ट की सामग्री सेट करता है। |
| [setShaderEntry(String value)](#setShaderEntry-java.lang.String-) | शेडर का एंट्री पॉइंट सेट करता है, कुछ शेडर जैसे HLSL में कस्टमाइज़्ड एंट्री हो सकते हैं। |
| [setShaderFile(String value)](#setShaderFile-java.lang.String-) | बाहरी शेडर फ़ाइल का फ़ाइलनाम सेट करता है। |
| [setShaderLanguage(String value)](#setShaderLanguage-java.lang.String-) | इस तकनीक द्वारा उपयोग की गई शेडर भाषा सेट करता है। |
| [setShaderVersion(String value)](#setShaderVersion-java.lang.String-) | इस तकनीक द्वारा उपयोग किए गए शेडर संस्करण को सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderTechnique() {#ShaderTechnique--}
```
public ShaderTechnique()
```


एक नया उदाहरण प्रारंभ करता है [ShaderTechnique](../../com.aspose.threed/shadertechnique) क्लास।

### addBinding(String property, String shaderParameter) {#addBinding-java.lang.String-java.lang.String-}
```
public void addBinding(String property, String shaderParameter)
```


डायनामिक प्रॉपर्टी को शेडर पैरामीटर से बाइंड करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | डायनेमिक प्रॉपर्टी का नाम। |
| shaderParameter | java.lang.String | शेडर पैरामीटर का नाम। |

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
### getDescription() {#getDescription--}
```
public String getDescription()
```


इस तकनीक का विवरण प्राप्त करता है।

**Returns:**
java.lang.String - इस तकनीक का विवरण
### getRenderAPI() {#getRenderAPI--}
```
public String getRenderAPI()
```


इस तकनीक द्वारा उपयोग किए गए रेंडरिंग API को प्राप्त करता है।

**Returns:**
java.lang.String - इस तकनीक द्वारा उपयोग किया गया रेंडरिंग API
### getRenderAPIVersion() {#getRenderAPIVersion--}
```
public String getRenderAPIVersion()
```


रेंडरिंग API का संस्करण प्राप्त करता है।

**Returns:**
java.lang.String - रेंडरिंग API का संस्करण।
### getShaderContent() {#getShaderContent--}
```
public byte[] getShaderContent()
```


एक एम्बेडेड शेडर स्क्रिप्ट की सामग्री प्राप्त करता है। यह HLSL/GLSL शेडर स्रोत फ़ाइल हो सकती है।

**Returns:**
byte[] - एक एम्बेडेड शेडर स्क्रिप्ट की सामग्री। यह HLSL/GLSL शेडर स्रोत फ़ाइल हो सकती है।
### getShaderEntry() {#getShaderEntry--}
```
public String getShaderEntry()
```


शेडर का एंट्री पॉइंट प्राप्त करता है, कुछ शेडर जैसे HLSL में कस्टमाइज़्ड एंट्री हो सकती हैं।

**Returns:**
java.lang.String - शेडर का एंट्री पॉइंट, कुछ शेडर जैसे HLSL में कस्टमाइज़्ड एंट्री हो सकते हैं।
### getShaderFile() {#getShaderFile--}
```
public String getShaderFile()
```


बाहरी शेडर फ़ाइल का फ़ाइलनाम प्राप्त करता है।

**Returns:**
java.lang.String - बाहरी शेडर फ़ाइल का फ़ाइलनाम।
### getShaderLanguage() {#getShaderLanguage--}
```
public String getShaderLanguage()
```


इस तकनीक द्वारा उपयोग की गई शेडर भाषा प्राप्त करता है।

**Returns:**
java.lang.String - इस तकनीक द्वारा उपयोग की गई शेडर भाषा।
### getShaderParameters() {#getShaderParameters--}
```
public Map<String,String> getShaderParameters()
```


शेडर पैरामीटर परिभाषा प्राप्त करता है। कुंजी डायनेमिक प्रॉपर्टी का नाम है, और मान वह शेडर पैरामीटर नाम है जिससे प्रॉपर्टी जुड़ी है।

**Returns:**
java.util.Map<java.lang.String,java.lang.String> - शेडर पैरामीटर परिभाषा। कुंजी डायनेमिक प्रॉपर्टी का नाम है, और मान वह शेडर पैरामीटर नाम है जिससे प्रॉपर्टी जुड़ी है।
### getShaderVersion() {#getShaderVersion--}
```
public String getShaderVersion()
```


इस तकनीक द्वारा उपयोग किए गए शेडर संस्करण को प्राप्त करता है।

**Returns:**
java.lang.String - इस तकनीक द्वारा उपयोग किया गया शेडर संस्करण।
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




### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


इस तकनीक का विवरण सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setRenderAPI(String value) {#setRenderAPI-java.lang.String-}
```
public void setRenderAPI(String value)
```


इस तकनीक द्वारा उपयोग किए गए रेंडरिंग API को सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setRenderAPIVersion(String value) {#setRenderAPIVersion-java.lang.String-}
```
public void setRenderAPIVersion(String value)
```


रेंडरिंग API का संस्करण सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setShaderContent(byte[] value) {#setShaderContent-byte---}
```
public void setShaderContent(byte[] value)
```


एक एम्बेडेड शेडर स्क्रिप्ट की सामग्री सेट करता है। यह HLSL/GLSL शेडर स्रोत फ़ाइल हो सकती है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | byte[] | नया मान |

### setShaderEntry(String value) {#setShaderEntry-java.lang.String-}
```
public void setShaderEntry(String value)
```


शेडर का एंट्री पॉइंट सेट करता है, कुछ शेडर जैसे HLSL में कस्टमाइज़्ड एंट्री हो सकते हैं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setShaderFile(String value) {#setShaderFile-java.lang.String-}
```
public void setShaderFile(String value)
```


बाहरी शेडर फ़ाइल का फ़ाइलनाम सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setShaderLanguage(String value) {#setShaderLanguage-java.lang.String-}
```
public void setShaderLanguage(String value)
```


इस तकनीक द्वारा उपयोग की गई शेडर भाषा सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setShaderVersion(String value) {#setShaderVersion-java.lang.String-}
```
public void setShaderVersion(String value)
```


इस तकनीक द्वारा उपयोग किए गए शेडर संस्करण को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

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

