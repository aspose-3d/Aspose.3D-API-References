---
title: StencilState
second_title: Aspose.3D for Java API Reference
description: प्रति फेस स्टेंसिल स्थितियां।
type: docs
weight: 175
url: /hi/java/com.aspose.threed/stencilstate/
---

**Inheritance:**
java.lang.Object
```
public class StencilState
```

प्रति फेस स्टेंसिल स्थितियां।
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट ऑब्जेक्ट के बराबर है या नहीं। |
| [getClass()](#getClass--) |  |
| [getCompare()](#getCompare--) | स्टेंसिल टेस्ट में उपयोग किए जाने वाले तुलना फ़ंक्शन को प्राप्त करता है। |
| [getDepthFailAction()](#getDepthFailAction--) | जब स्टेंसिल टेस्ट पास हो लेकिन डेप्थ टेस्ट विफल हो, तब स्टेंसिल एक्शन को प्राप्त करता है। |
| [getFailAction()](#getFailAction--) | जब स्टेंसिल टेस्ट विफल हो, तब स्टेंसिल एक्शन को प्राप्त करता है। |
| [getPassAction()](#getPassAction--) | जब स्टेंसिल टेस्ट और डेप्थ टेस्ट दोनों पास हों, तब स्टेंसिल एक्शन को प्राप्त करता है। |
| [hashCode()](#hashCode--) | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompare(CompareFunction value)](#setCompare-com.aspose.threed.CompareFunction-) | स्टेंसिल टेस्ट में उपयोग किए जाने वाले तुलना फ़ंक्शन को सेट करता है। |
| [setDepthFailAction(StencilAction value)](#setDepthFailAction-com.aspose.threed.StencilAction-) | जब स्टेंसिल टेस्ट पास हो लेकिन डेप्थ टेस्ट विफल हो, तब स्टेंसिल एक्शन को सेट करता है। |
| [setFailAction(StencilAction value)](#setFailAction-com.aspose.threed.StencilAction-) | जब स्टेंसिल टेस्ट विफल हो, तब स्टेंसिल एक्शन को सेट करता है। |
| [setPassAction(StencilAction value)](#setPassAction-com.aspose.threed.StencilAction-) | जब स्टेंसिल टेस्ट और डेप्थ टेस्ट दोनों पास हों, तब स्टेंसिल एक्शन को सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट ऑब्जेक्ट के बराबर है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompare() {#getCompare--}
```
public CompareFunction getCompare()
```


स्टेंसिल टेस्ट में उपयोग किए जाने वाले तुलना फ़ंक्शन को प्राप्त करता है।

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in stencil test
### getDepthFailAction() {#getDepthFailAction--}
```
public StencilAction getDepthFailAction()
```


जब स्टेंसिल टेस्ट पास हो लेकिन डेप्थ टेस्ट विफल हो, तब स्टेंसिल एक्शन को प्राप्त करता है।

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test pass but depth test fails.
### getFailAction() {#getFailAction--}
```
public StencilAction getFailAction()
```


जब स्टेंसिल टेस्ट विफल हो, तब स्टेंसिल एक्शन को प्राप्त करता है।

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test fails.
### getPassAction() {#getPassAction--}
```
public StencilAction getPassAction()
```


जब स्टेंसिल टेस्ट और डेप्थ टेस्ट दोनों पास हों, तब स्टेंसिल एक्शन को प्राप्त करता है।

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when both stencil test and depth test passes.
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस इंस्टेंस के लिए हैश कोड लौटाता है।

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




### setCompare(CompareFunction value) {#setCompare-com.aspose.threed.CompareFunction-}
```
public void setCompare(CompareFunction value)
```


स्टेंसिल टेस्ट में उपयोग किए जाने वाले तुलना फ़ंक्शन को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | नया मान |

### setDepthFailAction(StencilAction value) {#setDepthFailAction-com.aspose.threed.StencilAction-}
```
public void setDepthFailAction(StencilAction value)
```


जब स्टेंसिल टेस्ट पास हो लेकिन डेप्थ टेस्ट विफल हो, तब स्टेंसिल एक्शन को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | नया मान |

### setFailAction(StencilAction value) {#setFailAction-com.aspose.threed.StencilAction-}
```
public void setFailAction(StencilAction value)
```


जब स्टेंसिल टेस्ट विफल हो, तब स्टेंसिल एक्शन को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | नया मान |

### setPassAction(StencilAction value) {#setPassAction-com.aspose.threed.StencilAction-}
```
public void setPassAction(StencilAction value)
```


जब स्टेंसिल टेस्ट और डेप्थ टेस्ट दोनों पास हों, तब स्टेंसिल एक्शन को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | नया मान |

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

