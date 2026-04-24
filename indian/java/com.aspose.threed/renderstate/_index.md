---
title: RenderState
second_title: Aspose.3D for Java API Reference
description: पाइपलाइन बनाने के लिए रेंडर स्थिति। रेंडर स्थिति पर किए गए परिवर्तन निर्मित पाइपलाइन इंस्टेंस को प्रभावित नहीं करेंगे।
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

पाइपलाइन बनाने के लिए रेंडर स्टेट। रेंडर स्टेट में किए गए बदलाव बनाए गए पाइपलाइन इंस्टेंस को प्रभावित नहीं करेंगे।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [RenderState()](#RenderState--) | का कंस्ट्रक्टर [RenderState](../../com.aspose.threed/renderstate) |
## Methods

| Method | विवरण |
| --- | --- |
| [close()](#close--) | नष्ट करें [RenderState](../../com.aspose.threed/renderstate) और सभी आंतरिक संसाधनों को मुक्त करें। |
| [compareTo(RenderState other)](#compareTo-com.aspose.threed.RenderState-) | तुलना करें रेंडर स्टेट को अन्य इंस्टेंस के साथ |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट ऑब्जेक्ट के बराबर है या नहीं। |
| [getBlend()](#getBlend--) | सक्षम या अक्षम करें फ्रैगमेंट ब्लेंडिंग। |
| [getBlendColor()](#getBlendColor--) | प्राप्त करता है ब्लेंड रंग जहाँ उपयोग किया जाता है [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [getClass()](#getClass--) |  |
| [getCullFace()](#getCullFace--) | सक्षम या अक्षम करें cull face |
| [getCullFaceMode()](#getCullFaceMode--) | प्राप्त करता है कौन सा फेस कटा जाएगा। |
| [getDepthFunction()](#getDepthFunction--) | प्राप्त करता है तुलना फ़ंक्शन जो गहराई परीक्षण में उपयोग किया जाता है |
| [getDepthMask()](#getDepthMask--) | सक्षम या अक्षम करें गहराई लेखन। |
| [getDepthTest()](#getDepthTest--) | सक्षम या अक्षम करें गहराई परीक्षण। |
| [getDestinationBlendFactor()](#getDestinationBlendFactor--) | प्राप्त करता है कि रंग कैसे मिश्रित होता है। |
| [getFrontFace()](#getFrontFace--) | प्राप्त करता है कौन सा क्रम फ्रंट फेस है। |
| [getPolygonMode()](#getPolygonMode--) | प्राप्त करता है बहुभुज का रेंडर मोड। |
| [getScissorTest()](#getScissorTest--) | सक्षम या अक्षम करें scissor test |
| [getSourceBlendFactor()](#getSourceBlendFactor--) | प्राप्त करता है कि रंग कैसे मिश्रित होता है। |
| [getStencilBackFace()](#getStencilBackFace--) | प्राप्त करता है बैक फेस के लिए स्टेंसिल स्थिति। |
| [getStencilFrontFace()](#getStencilFrontFace--) | प्राप्त करता है फ्रंट फेस के लिए स्टेंसिल स्थिति। |
| [getStencilMask()](#getStencilMask--) | प्राप्त करता है वह मास्क जो परीक्षण समाप्त होने पर दोनों रेफ़रेंस और संग्रहीत स्टेंसिल मान के साथ AND किया जाता है। |
| [getStencilReference()](#getStencilReference--) | प्राप्त करता है स्टेंसिल परीक्षण के लिए रेफ़रेंस मान। |
| [getStencilTest()](#getStencilTest--) | सक्षम या अक्षम करें स्टेंसिल परीक्षण। |
| [hashCode()](#hashCode--) | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlend(boolean value)](#setBlend-boolean-) | सक्षम या अक्षम करें फ्रैगमेंट ब्लेंडिंग। |
| [setBlendColor(FVector4 value)](#setBlendColor-com.aspose.threed.FVector4-) | सेट करता है ब्लेंड रंग जहाँ उपयोग किया जाता है [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [setCullFace(boolean value)](#setCullFace-boolean-) | सक्षम या अक्षम करें cull face |
| [setCullFaceMode(int value)](#setCullFaceMode-int-) | सेट करता है कौन सा फेस कटा जाएगा। |
| [setDepthFunction(CompareFunction value)](#setDepthFunction-com.aspose.threed.CompareFunction-) | सेट करता है तुलना फ़ंक्शन जो गहराई परीक्षण में उपयोग किया जाता है |
| [setDepthMask(boolean value)](#setDepthMask-boolean-) | सक्षम या अक्षम करें गहराई लेखन। |
| [setDepthTest(boolean value)](#setDepthTest-boolean-) | सक्षम या अक्षम करें गहराई परीक्षण। |
| [setDestinationBlendFactor(BlendFactor value)](#setDestinationBlendFactor-com.aspose.threed.BlendFactor-) | सेट करता है कि रंग कैसे मिश्रित होता है। |
| [setFrontFace(FrontFace value)](#setFrontFace-com.aspose.threed.FrontFace-) | सेट करता है कौन सा क्रम फ्रंट फेस है। |
| [setPolygonMode(PolygonMode value)](#setPolygonMode-com.aspose.threed.PolygonMode-) | बहुभुज के रेंडर मोड को सेट करता है। |
| [setScissorTest(boolean value)](#setScissorTest-boolean-) | सक्षम या अक्षम करें scissor test |
| [setSourceBlendFactor(BlendFactor value)](#setSourceBlendFactor-com.aspose.threed.BlendFactor-) | सेट करता है कि रंग कैसे मिश्रित होता है। |
| [setStencilMask(int value)](#setStencilMask-int-) | परीक्षण समाप्त होने पर संदर्भ और संग्रहीत स्टेंसिल मान दोनों के साथ AND किया गया मास्क सेट करता है। |
| [setStencilReference(int value)](#setStencilReference-int-) | स्टेंसिल परीक्षण के लिए संदर्भ मान सेट करता है। |
| [setStencilTest(boolean value)](#setStencilTest-boolean-) | सक्षम या अक्षम करें स्टेंसिल परीक्षण। |
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


नष्ट करें [RenderState](../../com.aspose.threed/renderstate) और सभी आंतरिक संसाधनों को मुक्त करें।

### compareTo(RenderState other) {#compareTo-com.aspose.threed.RenderState-}
```
public int compareTo(RenderState other)
```


तुलना करें रेंडर स्टेट को अन्य इंस्टेंस के साथ

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| other | [RenderState](../../com.aspose.threed/renderstate) | तुलना के लिए एक अन्य रेंडर स्थिति |

**Returns:**
int
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
### getBlend() {#getBlend--}
```
public boolean getBlend()
```


सक्षम या अक्षम करें फ्रैगमेंट ब्लेंडिंग।

**Returns:**
boolean - फ्रैगमेंट ब्लेंडिंग को सक्षम या अक्षम करें।
### getBlendColor() {#getBlendColor--}
```
public FVector4 getBlendColor()
```


प्राप्त करता है ब्लेंड रंग जहाँ उपयोग किया जाता है [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

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


सक्षम या अक्षम करें cull face

**Returns:**
boolean - कूल फेस को सक्षम या अक्षम करें
### getCullFaceMode() {#getCullFaceMode--}
```
public int getCullFaceMode()
```


प्राप्त करता है कौन सा फेस कटा जाएगा।

**Returns:**
int - कौन सा फेस कूल किया जाएगा।
### getDepthFunction() {#getDepthFunction--}
```
public CompareFunction getDepthFunction()
```


प्राप्त करता है तुलना फ़ंक्शन जो गहराई परीक्षण में उपयोग किया जाता है

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in depth test
### getDepthMask() {#getDepthMask--}
```
public boolean getDepthMask()
```


सक्षम या अक्षम करें गहराई लेखन।

**Returns:**
boolean - डेप्थ राइटिंग को सक्षम या अक्षम करें।
### getDepthTest() {#getDepthTest--}
```
public boolean getDepthTest()
```


सक्षम या अक्षम करें गहराई परीक्षण।

**Returns:**
boolean - डेप्थ टेस्ट को सक्षम या अक्षम करें।
### getDestinationBlendFactor() {#getDestinationBlendFactor--}
```
public BlendFactor getDestinationBlendFactor()
```


प्राप्त करता है कि रंग कैसे मिश्रित होता है।

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getFrontFace() {#getFrontFace--}
```
public FrontFace getFrontFace()
```


प्राप्त करता है कौन सा क्रम फ्रंट फेस है।

**Returns:**
[FrontFace](../../com.aspose.threed/frontface) - which order is front face.
### getPolygonMode() {#getPolygonMode--}
```
public PolygonMode getPolygonMode()
```


प्राप्त करता है बहुभुज का रेंडर मोड।

**Returns:**
[PolygonMode](../../com.aspose.threed/polygonmode) - the polygon's render mode.
### getScissorTest() {#getScissorTest--}
```
public boolean getScissorTest()
```


सक्षम या अक्षम करें scissor test

**Returns:**
boolean - सिज़र टेस्ट को सक्षम या अक्षम करें
### getSourceBlendFactor() {#getSourceBlendFactor--}
```
public BlendFactor getSourceBlendFactor()
```


प्राप्त करता है कि रंग कैसे मिश्रित होता है।

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getStencilBackFace() {#getStencilBackFace--}
```
public StencilState getStencilBackFace()
```


प्राप्त करता है बैक फेस के लिए स्टेंसिल स्थिति।

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for back face.
### getStencilFrontFace() {#getStencilFrontFace--}
```
public StencilState getStencilFrontFace()
```


प्राप्त करता है फ्रंट फेस के लिए स्टेंसिल स्थिति।

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for front face.
### getStencilMask() {#getStencilMask--}
```
public int getStencilMask()
```


प्राप्त करता है वह मास्क जो परीक्षण समाप्त होने पर दोनों रेफ़रेंस और संग्रहीत स्टेंसिल मान के साथ AND किया जाता है।

**Returns:**
int - परीक्षण समाप्त होने पर संदर्भ और संग्रहीत स्टेंसिल मान दोनों के साथ AND किया गया मास्क।
### getStencilReference() {#getStencilReference--}
```
public int getStencilReference()
```


प्राप्त करता है स्टेंसिल परीक्षण के लिए रेफ़रेंस मान।

**Returns:**
int - स्टेंसिल परीक्षण के लिए संदर्भ मान।
### getStencilTest() {#getStencilTest--}
```
public boolean getStencilTest()
```


सक्षम या अक्षम करें स्टेंसिल परीक्षण।

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


सक्षम या अक्षम करें फ्रैगमेंट ब्लेंडिंग।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setBlendColor(FVector4 value) {#setBlendColor-com.aspose.threed.FVector4-}
```
public void setBlendColor(FVector4 value)
```


सेट करता है ब्लेंड रंग जहाँ उपयोग किया जाता है [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [FVector4](../../com.aspose.threed/fvector4) | नया मान |

### setCullFace(boolean value) {#setCullFace-boolean-}
```
public void setCullFace(boolean value)
```


सक्षम या अक्षम करें cull face

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setCullFaceMode(int value) {#setCullFaceMode-int-}
```
public void setCullFaceMode(int value)
```


सेट करता है कौन सा फेस कटा जाएगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setDepthFunction(CompareFunction value) {#setDepthFunction-com.aspose.threed.CompareFunction-}
```
public void setDepthFunction(CompareFunction value)
```


सेट करता है तुलना फ़ंक्शन जो गहराई परीक्षण में उपयोग किया जाता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | नया मान |

### setDepthMask(boolean value) {#setDepthMask-boolean-}
```
public void setDepthMask(boolean value)
```


सक्षम या अक्षम करें गहराई लेखन।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setDepthTest(boolean value) {#setDepthTest-boolean-}
```
public void setDepthTest(boolean value)
```


सक्षम या अक्षम करें गहराई परीक्षण।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setDestinationBlendFactor(BlendFactor value) {#setDestinationBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setDestinationBlendFactor(BlendFactor value)
```


सेट करता है कि रंग कैसे मिश्रित होता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | नया मान |

### setFrontFace(FrontFace value) {#setFrontFace-com.aspose.threed.FrontFace-}
```
public void setFrontFace(FrontFace value)
```


सेट करता है कौन सा क्रम फ्रंट फेस है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [FrontFace](../../com.aspose.threed/frontface) | नया मान |

### setPolygonMode(PolygonMode value) {#setPolygonMode-com.aspose.threed.PolygonMode-}
```
public void setPolygonMode(PolygonMode value)
```


बहुभुज के रेंडर मोड को सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [PolygonMode](../../com.aspose.threed/polygonmode) | नया मान |

### setScissorTest(boolean value) {#setScissorTest-boolean-}
```
public void setScissorTest(boolean value)
```


सक्षम या अक्षम करें scissor test

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setSourceBlendFactor(BlendFactor value) {#setSourceBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setSourceBlendFactor(BlendFactor value)
```


सेट करता है कि रंग कैसे मिश्रित होता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | नया मान |

### setStencilMask(int value) {#setStencilMask-int-}
```
public void setStencilMask(int value)
```


परीक्षण समाप्त होने पर संदर्भ और संग्रहीत स्टेंसिल मान दोनों के साथ AND किया गया मास्क सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setStencilReference(int value) {#setStencilReference-int-}
```
public void setStencilReference(int value)
```


स्टेंसिल परीक्षण के लिए संदर्भ मान सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | नया मान |

### setStencilTest(boolean value) {#setStencilTest-boolean-}
```
public void setStencilTest(boolean value)
```


सक्षम या अक्षम करें स्टेंसिल परीक्षण।

**Parameters:**
| Parameter | Type | विवरण |
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

