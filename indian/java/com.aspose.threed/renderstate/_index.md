---
title: "RenderState"
second_title: "Aspose.3D for Java API रेफ़रेंस"
description: "पाइपलाइन बनाने के लिए रेंडर स्थिति। रेंडर स्थिति में किए गए परिवर्तन निर्मित पाइपलाइन इंस्टेंस को प्रभावित नहीं करेंगे।"
type: docs
weight: 151
url: /hi/java/com.aspose.threed/renderstate/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable, java.lang.Comparable
```
public class RenderState implements Closeable, Comparable<RenderState>
```

पाइपलाइन बनाने के लिए रेंडर स्टेट। रेंडर स्टेट पर किए गए बदलाव बनाए गए पाइपलाइन इंस्टेंसेज़ को प्रभावित नहीं करेंगे।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [RenderState()](#RenderState--) | का कंस्ट्रक्टर [RenderState](../../com.aspose.threed/renderstate) |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [close()](#close--) | डिस्पोज़ करें [RenderState](../../com.aspose.threed/renderstate) और सभी आंतरिक संसाधनों को रिलीज़ करें। |
| [compareTo(RenderState other)](#compareTo-com.aspose.threed.RenderState-) | रेंडर स्टेट की तुलना दूसरे इंस्टेंस से करें |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट ऑब्जेक्ट के बराबर है या नहीं। |
| [getBlend()](#getBlend--) | फ़्रैगमेंट ब्लेंडिंग को सक्षम या अक्षम करें। |
| [getBlendColor()](#getBlendColor--) | ब्लेंड रंग प्राप्त करता है जहाँ उपयोग किया जाता है [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [getClass()](#getClass--) |  |
| [getCullFace()](#getCullFace--) | कुल फेस को सक्षम या अक्षम करें |
| [getCullFaceMode()](#getCullFaceMode--) | कुल किया जाने वाला फेस प्राप्त करता है। |
| [getDepthFunction()](#getDepthFunction--) | डेप्थ टेस्ट में उपयोग किए जाने वाले तुलना फ़ंक्शन को प्राप्त करता है। |
| [getDepthMask()](#getDepthMask--) | डेप्थ राइटिंग को सक्षम या अक्षम करें। |
| [getDepthTest()](#getDepthTest--) | डेप्थ टेस्ट को सक्षम या अक्षम करें। |
| [getDestinationBlendFactor()](#getDestinationBlendFactor--) | रंग कैसे ब्लेंड किया जाता है, प्राप्त करता है। |
| [getFrontFace()](#getFrontFace--) | कौन सा क्रम फ्रंट फेस है, प्राप्त करता है। |
| [getPolygonMode()](#getPolygonMode--) | पॉलीगॉन का रेंडर मोड प्राप्त करता है। |
| [getScissorTest()](#getScissorTest--) | सिज़र टेस्ट को सक्षम या अक्षम करें |
| [getSourceBlendFactor()](#getSourceBlendFactor--) | रंग कैसे ब्लेंड किया जाता है, प्राप्त करता है। |
| [getStencilBackFace()](#getStencilBackFace--) | बैक फेस के लिए स्टेंसिल स्टेट प्राप्त करता है। |
| [getStencilFrontFace()](#getStencilFrontFace--) | फ्रंट फेस के लिए स्टेंसिल स्टेट प्राप्त करता है। |
| [getStencilMask()](#getStencilMask--) | टेस्ट समाप्त होने पर रेफ़रेंस और संग्रहीत स्टेंसिल वैल्यू दोनों के साथ AND किया गया मास्क प्राप्त करता है। |
| [getStencilReference()](#getStencilReference--) | स्टेंसिल टेस्ट के लिए रेफ़रेंस वैल्यू प्राप्त करता है। |
| [getStencilTest()](#getStencilTest--) | स्टेंसिल टेस्ट को सक्षम या अक्षम करें। |
| [hashCode()](#hashCode--) | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlend(boolean value)](#setBlend-boolean-) | फ़्रैगमेंट ब्लेंडिंग को सक्षम या अक्षम करें। |
| [setBlendColor(FVector4 value)](#setBlendColor-com.aspose.threed.FVector4-) | ब्लेंड रंग सेट करता है जहाँ उपयोग किया जाता है [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [setCullFace(boolean value)](#setCullFace-boolean-) | कुल फेस को सक्षम या अक्षम करें |
| [setCullFaceMode(int value)](#setCullFaceMode-int-) | कौन सा फेस कूल्ड किया जाएगा, सेट करता है। |
| [setDepthFunction(CompareFunction value)](#setDepthFunction-com.aspose.threed.CompareFunction-) | डेप्थ टेस्ट में उपयोग किए जाने वाले तुलना फ़ंक्शन को सेट करता है। |
| [setDepthMask(boolean value)](#setDepthMask-boolean-) | डेप्थ राइटिंग को सक्षम या अक्षम करें। |
| [setDepthTest(boolean value)](#setDepthTest-boolean-) | डेप्थ टेस्ट को सक्षम या अक्षम करें। |
| [setDestinationBlendFactor(BlendFactor value)](#setDestinationBlendFactor-com.aspose.threed.BlendFactor-) | रंग कैसे ब्लेंड किया जाता है, सेट करता है। |
| [setFrontFace(FrontFace value)](#setFrontFace-com.aspose.threed.FrontFace-) | कौन सा क्रम फ्रंट फेस है, सेट करता है। |
| [setPolygonMode(PolygonMode value)](#setPolygonMode-com.aspose.threed.PolygonMode-) | बहुभुज का रेंडर मोड सेट करता है। |
| [setScissorTest(boolean value)](#setScissorTest-boolean-) | सिज़र टेस्ट को सक्षम या अक्षम करें |
| [setSourceBlendFactor(BlendFactor value)](#setSourceBlendFactor-com.aspose.threed.BlendFactor-) | रंग कैसे ब्लेंड किया जाता है, सेट करता है। |
| [setStencilMask(int value)](#setStencilMask-int-) | टेस्ट पूरा होने पर रेफ़रेंस और संग्रहीत स्टेंसिल मान दोनों के साथ AND किया गया मास्क सेट करता है। |
| [setStencilReference(int value)](#setStencilReference-int-) | स्टेंसिल टेस्ट के लिए रेफ़रेंस मान सेट करता है। |
| [setStencilTest(boolean value)](#setStencilTest-boolean-) | स्टेंसिल टेस्ट को सक्षम या अक्षम करें। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderState() {#RenderState--}
```
public RenderState()
```


का कंस्ट्रक्टर [RenderState](../../com.aspose.threed/renderstate)

### close() {#close--}
```
public void close()
```


डिस्पोज़ करें [RenderState](../../com.aspose.threed/renderstate) और सभी आंतरिक संसाधनों को रिलीज़ करें।

### compareTo(RenderState other) {#compareTo-com.aspose.threed.RenderState-}
```
public int compareTo(RenderState other)
```


रेंडर स्टेट की तुलना दूसरे इंस्टेंस से करें

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [RenderState](../../com.aspose.threed/renderstate) | तुलना के लिए एक अन्य रेंडर स्टेट |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट ऑब्जेक्ट के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getBlend() {#getBlend--}
```
public boolean getBlend()
```


फ़्रैगमेंट ब्लेंडिंग को सक्षम या अक्षम करें।

**Returns:**
boolean - फ्रैगमेंट ब्लेंडिंग को सक्षम या अक्षम करें।
### getBlendColor() {#getBlendColor--}
```
public FVector4 getBlendColor()
```


ब्लेंड रंग प्राप्त करता है जहाँ उपयोग किया जाता है [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCullFace() {#getCullFace--}
```
public boolean getCullFace()
```


कुल फेस को सक्षम या अक्षम करें

**Returns:**
boolean - कूल फेस को सक्षम या अक्षम करें
### getCullFaceMode() {#getCullFaceMode--}
```
public int getCullFaceMode()
```


कुल किया जाने वाला फेस प्राप्त करता है।

**Returns:**
int - कौन सा फेस कूल किया जाएगा।
### getDepthFunction() {#getDepthFunction--}
```
public CompareFunction getDepthFunction()
```


डेप्थ टेस्ट में उपयोग किए जाने वाले तुलना फ़ंक्शन को प्राप्त करता है।

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in depth test
### getDepthMask() {#getDepthMask--}
```
public boolean getDepthMask()
```


डेप्थ राइटिंग को सक्षम या अक्षम करें।

**Returns:**
boolean - डेप्थ राइटिंग को सक्षम या अक्षम करें।
### getDepthTest() {#getDepthTest--}
```
public boolean getDepthTest()
```


डेप्थ टेस्ट को सक्षम या अक्षम करें।

**Returns:**
boolean - डेप्थ टेस्ट को सक्षम या अक्षम करें।
### getDestinationBlendFactor() {#getDestinationBlendFactor--}
```
public BlendFactor getDestinationBlendFactor()
```


रंग कैसे ब्लेंड किया जाता है, प्राप्त करता है।

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getFrontFace() {#getFrontFace--}
```
public FrontFace getFrontFace()
```


कौन सा क्रम फ्रंट फेस है, प्राप्त करता है।

**Returns:**
[FrontFace](../../com.aspose.threed/frontface) - which order is front face.
### getPolygonMode() {#getPolygonMode--}
```
public PolygonMode getPolygonMode()
```


पॉलीगॉन का रेंडर मोड प्राप्त करता है।

**Returns:**
[PolygonMode](../../com.aspose.threed/polygonmode) - the polygon's render mode.
### getScissorTest() {#getScissorTest--}
```
public boolean getScissorTest()
```


सिज़र टेस्ट को सक्षम या अक्षम करें

**Returns:**
boolean - सिज़र टेस्ट को सक्षम या अक्षम करें
### getSourceBlendFactor() {#getSourceBlendFactor--}
```
public BlendFactor getSourceBlendFactor()
```


रंग कैसे ब्लेंड किया जाता है, प्राप्त करता है।

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getStencilBackFace() {#getStencilBackFace--}
```
public StencilState getStencilBackFace()
```


बैक फेस के लिए स्टेंसिल स्टेट प्राप्त करता है।

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for back face.
### getStencilFrontFace() {#getStencilFrontFace--}
```
public StencilState getStencilFrontFace()
```


फ्रंट फेस के लिए स्टेंसिल स्टेट प्राप्त करता है।

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for front face.
### getStencilMask() {#getStencilMask--}
```
public int getStencilMask()
```


टेस्ट समाप्त होने पर रेफ़रेंस और संग्रहीत स्टेंसिल वैल्यू दोनों के साथ AND किया गया मास्क प्राप्त करता है।

**Returns:**
int - टेस्ट पूरा होने पर रेफ़रेंस और संग्रहीत स्टेंसिल मान दोनों के साथ AND किया गया मास्क।
### getStencilReference() {#getStencilReference--}
```
public int getStencilReference()
```


स्टेंसिल टेस्ट के लिए रेफ़रेंस वैल्यू प्राप्त करता है।

**Returns:**
int - स्टेंसिल टेस्ट के लिए रेफ़रेंस मान।
### getStencilTest() {#getStencilTest--}
```
public boolean getStencilTest()
```


स्टेंसिल टेस्ट को सक्षम या अक्षम करें।

**Returns:**
boolean - स्टेंसिल टेस्ट को सक्षम या अक्षम करें।
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




### setBlend(boolean value) {#setBlend-boolean-}
```
public void setBlend(boolean value)
```


फ़्रैगमेंट ब्लेंडिंग को सक्षम या अक्षम करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setBlendColor(FVector4 value) {#setBlendColor-com.aspose.threed.FVector4-}
```
public void setBlendColor(FVector4 value)
```


ब्लेंड रंग सेट करता है जहाँ उपयोग किया जाता है [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [FVector4](../../com.aspose.threed/fvector4) | नया मान |

### setCullFace(boolean value) {#setCullFace-boolean-}
```
public void setCullFace(boolean value)
```


कुल फेस को सक्षम या अक्षम करें

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setCullFaceMode(int value) {#setCullFaceMode-int-}
```
public void setCullFaceMode(int value)
```


कौन सा फेस कूल्ड किया जाएगा, सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setDepthFunction(CompareFunction value) {#setDepthFunction-com.aspose.threed.CompareFunction-}
```
public void setDepthFunction(CompareFunction value)
```


डेप्थ टेस्ट में उपयोग किए जाने वाले तुलना फ़ंक्शन को सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | नया मान |

### setDepthMask(boolean value) {#setDepthMask-boolean-}
```
public void setDepthMask(boolean value)
```


डेप्थ राइटिंग को सक्षम या अक्षम करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setDepthTest(boolean value) {#setDepthTest-boolean-}
```
public void setDepthTest(boolean value)
```


डेप्थ टेस्ट को सक्षम या अक्षम करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setDestinationBlendFactor(BlendFactor value) {#setDestinationBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setDestinationBlendFactor(BlendFactor value)
```


रंग कैसे ब्लेंड किया जाता है, सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | नया मान |

### setFrontFace(FrontFace value) {#setFrontFace-com.aspose.threed.FrontFace-}
```
public void setFrontFace(FrontFace value)
```


कौन सा क्रम फ्रंट फेस है, सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [FrontFace](../../com.aspose.threed/frontface) | नया मान |

### setPolygonMode(PolygonMode value) {#setPolygonMode-com.aspose.threed.PolygonMode-}
```
public void setPolygonMode(PolygonMode value)
```


बहुभुज का रेंडर मोड सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PolygonMode](../../com.aspose.threed/polygonmode) | नया मान |

### setScissorTest(boolean value) {#setScissorTest-boolean-}
```
public void setScissorTest(boolean value)
```


सिज़र टेस्ट को सक्षम या अक्षम करें

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setSourceBlendFactor(BlendFactor value) {#setSourceBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setSourceBlendFactor(BlendFactor value)
```


रंग कैसे ब्लेंड किया जाता है, सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | नया मान |

### setStencilMask(int value) {#setStencilMask-int-}
```
public void setStencilMask(int value)
```


टेस्ट पूरा होने पर रेफ़रेंस और संग्रहीत स्टेंसिल मान दोनों के साथ AND किया गया मास्क सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setStencilReference(int value) {#setStencilReference-int-}
```
public void setStencilReference(int value)
```


स्टेंसिल टेस्ट के लिए रेफ़रेंस मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setStencilTest(boolean value) {#setStencilTest-boolean-}
```
public void setStencilTest(boolean value)
```


स्टेंसिल टेस्ट को सक्षम या अक्षम करें।

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

