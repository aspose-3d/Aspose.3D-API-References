---
title: DescriptorSetUpdater
second_title: Aspose.3D for Java API Reference
description: यह क्लास चेन ऑपरेशन में  को अपडेट करने की अनुमति देती है।
type: docs
weight: 42
url: /hi/java/com.aspose.threed/descriptorsetupdater/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public final class DescriptorSetUpdater implements Closeable
```

यह क्लास चेन ऑपरेशन में [IDescriptorSet](../../com.aspose.threed/idescriptorset) को अपडेट करने की अनुमति देती है।
## Methods

| Method | विवरण |
| --- | --- |
| [bind(IBuffer buffer)](#bind-com.aspose.threed.IBuffer-) | पूरे बफ़र को वर्तमान डिस्क्रिप्टर से बाइंड करें |
| [bind(IBuffer buffer, int offset, int size)](#bind-com.aspose.threed.IBuffer-int-int-) | बफ़र को वर्तमान डिस्क्रिप्टर सेट से बाइंड करें |
| [bind(ITextureUnit texture)](#bind-com.aspose.threed.ITextureUnit-) | टेक्सचर यूनिट को वर्तमान डिस्क्रिप्टर सेट से बाइंड करें |
| [bind(int binding, IBuffer buffer)](#bind-int-com.aspose.threed.IBuffer-) | निर्दिष्ट बाइंडिंग स्थान पर बफ़र को वर्तमान डिस्क्रिप्टर सेट से बाइंड करें। |
| [bind(int binding, IBuffer buffer, int offset, int size)](#bind-int-com.aspose.threed.IBuffer-int-int-) | निर्दिष्ट बाइंडिंग स्थान पर बफ़र को वर्तमान डिस्क्रिप्टर सेट से बाइंड करें। |
| [bind(int binding, ITextureUnit texture)](#bind-int-com.aspose.threed.ITextureUnit-) | टेक्सचर यूनिट को वर्तमान डिस्क्रिप्टर सेट से बाइंड करें |
| [close()](#close--) | अपडेटर को डिस्पोज़ करें और परिवर्तन को हार्डवेयर डिवाइस में कमिट करें। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### bind(IBuffer buffer) {#bind-com.aspose.threed.IBuffer-}
```
public DescriptorSetUpdater bind(IBuffer buffer)
```


पूरे बफ़र को वर्तमान डिस्क्रिप्टर से बाइंड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) |  |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(IBuffer buffer, int offset, int size) {#bind-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(IBuffer buffer, int offset, int size)
```


बफ़र को वर्तमान डिस्क्रिप्टर सेट से बाइंड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | कौन सा बफ़र बाइंड करना है |
| ऑफ़सेट | int | बाइंड करने के लिए बफ़र का ऑफ़सेट |
| आकार | int | बाइंड करने के लिए बफ़र का आकार |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(ITextureUnit texture) {#bind-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(ITextureUnit texture)
```


टेक्सचर यूनिट को वर्तमान डिस्क्रिप्टर सेट से बाइंड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | बाइंड करने के लिए टेक्सचर यूनिट |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer) {#bind-int-com.aspose.threed.IBuffer-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer)
```


निर्दिष्ट बाइंडिंग स्थान पर बफ़र को वर्तमान डिस्क्रिप्टर सेट से बाइंड करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| बाइंडिंग | int | बाइंडिंग स्थान |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | बाइंड करने के लिए पूरा बफ़र |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer, int offset, int size) {#bind-int-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer, int offset, int size)
```


निर्दिष्ट बाइंडिंग स्थान पर बफ़र को वर्तमान डिस्क्रिप्टर सेट से बाइंड करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| बाइंडिंग | int | बाइंडिंग स्थान |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | बाइंड करने के बफ़र |
| ऑफ़सेट | int | बाइंड करने के लिए बफ़र का ऑफ़सेट |
| आकार | int | बाइंड करने के लिए बफ़र का आकार |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, ITextureUnit texture) {#bind-int-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(int binding, ITextureUnit texture)
```


टेक्सचर यूनिट को वर्तमान डिस्क्रिप्टर सेट से बाइंड करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| बाइंडिंग | int | बाइंडिंग स्थान |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | बाइंड करने के लिए टेक्सचर यूनिट |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### close() {#close--}
```
public void close()
```


अपडेटर को डिस्पोज़ करें और परिवर्तन को हार्डवेयर डिवाइस में कमिट करें।

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

