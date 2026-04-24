---
title: ITextureUnit
second_title: Aspose.3D for Java API Reference
description: GPU और CPU के बीच साझा की गई मेमोरी में एक टेक्सचर को दर्शाता है और इसे shader द्वारा सैंपल किया जा सकता है जहाँ केवल एक बाहरी फ़ाइल का संदर्भ दर्शाता है।
type: docs
weight: 258
url: /hi/java/com.aspose.threed/itextureunit/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface ITextureUnit extends Closeable
```

[ITextureUnit](../../com.aspose.threed/itextureunit) represents a texture in the memory that shared between GPU and CPU and can be sampled by the shader, where the [Texture](../../com.aspose.threed/texture) only represents a reference to an external file. More details can be found https://en.wikipedia.org/wiki/Texture\_mapping\_unit
## Methods

| Method | विवरण |
| --- | --- |
| [getDepth()](#getDepth--) | इस टेक्सचर की ऊँचाई प्राप्त करता है, गैर‑3D टेक्सचर के लिए यह हमेशा 1 होता है। |
| [getHeight()](#getHeight--) | इस टेक्सचर की ऊँचाई प्राप्त करता है। |
| [getMagnification()](#getMagnification--) | वृद्धि के लिए फ़िल्टर मोड प्राप्त करता है। |
| [getMinification()](#getMinification--) | छोटा करने के लिए फ़िल्टर मोड प्राप्त करता है। |
| [getMipmap()](#getMipmap--) | मिपमैप के लिए फ़िल्टर मोड प्राप्त करता है। |
| [getScale()](#getScale--) | UV निर्देशांक का स्केल प्राप्त करता है। |
| [getScroll()](#getScroll--) | UV निर्देशांक का स्क्रॉल प्राप्त करता है। |
| [getType()](#getType--) | इस टेक्सचर यूनिट का प्रकार प्राप्त करता है। |
| [getUWrap()](#getUWrap--) | टेक्सचर के U निर्देशांक के लिए रैप मोड प्राप्त करता है। |
| [getVWrap()](#getVWrap--) | टेक्सचर के V निर्देशांक के लिए रैप मोड प्राप्त करता है। |
| [getWWrap()](#getWWrap--) | टेक्सचर के W निर्देशांक के लिए रैप मोड प्राप्त करता है। |
| [getWidth()](#getWidth--) | इस टेक्सचर की चौड़ाई प्राप्त करता है। |
| [setMagnification(TextureFilter value)](#setMagnification-com.aspose.threed.TextureFilter-) | वृद्धि के लिए फ़िल्टर मोड सेट करता है। |
| [setMinification(TextureFilter value)](#setMinification-com.aspose.threed.TextureFilter-) | छोटा करने के लिए फ़िल्टर मोड सेट करता है। |
| [setMipmap(TextureFilter value)](#setMipmap-com.aspose.threed.TextureFilter-) | मिपमैप के लिए फ़िल्टर मोड सेट करता है। |
| [setScale(Vector2 value)](#setScale-com.aspose.threed.Vector2-) | UV निर्देशांक का स्केल सेट करता है। |
| [setScroll(Vector2 value)](#setScroll-com.aspose.threed.Vector2-) | UV निर्देशांक का स्क्रॉल सेट करता है। |
| [setUWrap(WrapMode value)](#setUWrap-com.aspose.threed.WrapMode-) | टेक्सचर के U निर्देशांक के लिए रैप मोड सेट करता है। |
| [setVWrap(WrapMode value)](#setVWrap-com.aspose.threed.WrapMode-) | टेक्सचर के V निर्देशांक के लिए रैप मोड सेट करता है। |
| [setWWrap(WrapMode value)](#setWWrap-com.aspose.threed.WrapMode-) | टेक्सचर के W निर्देशांक के लिए रैप मोड सेट करता है। |
### getDepth() {#getDepth--}
```
public abstract int getDepth()
```


इस टेक्सचर की ऊँचाई प्राप्त करता है, गैर‑3D टेक्सचर के लिए यह हमेशा 1 होता है।

**Returns:**
int - इस टेक्सचर की ऊँचाई, गैर‑3D टेक्सचर के लिए यह हमेशा 1 होता है।
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


इस टेक्सचर की ऊँचाई प्राप्त करता है।

**Returns:**
int - इस टेक्सचर की ऊँचाई।
### getMagnification() {#getMagnification--}
```
public abstract TextureFilter getMagnification()
```


वृद्धि के लिए फ़िल्टर मोड प्राप्त करता है।

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for magnification.
### getMinification() {#getMinification--}
```
public abstract TextureFilter getMinification()
```


छोटा करने के लिए फ़िल्टर मोड प्राप्त करता है।

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for minification.
### getMipmap() {#getMipmap--}
```
public abstract TextureFilter getMipmap()
```


मिपमैप के लिए फ़िल्टर मोड प्राप्त करता है।

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter mode for mipmap.
### getScale() {#getScale--}
```
public abstract Vector2 getScale()
```


UV निर्देशांक का स्केल प्राप्त करता है।

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scale of the UV coordinate.
### getScroll() {#getScroll--}
```
public abstract Vector2 getScroll()
```


UV निर्देशांक का स्क्रॉल प्राप्त करता है।

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the scroll of the UV coordinate.
### getType() {#getType--}
```
public abstract TextureType getType()
```


इस टेक्सचर यूनिट का प्रकार प्राप्त करता है।

**Returns:**
[TextureType](../../com.aspose.threed/texturetype) - the type of this texture unit.
### getUWrap() {#getUWrap--}
```
public abstract WrapMode getUWrap()
```


टेक्सचर के U निर्देशांक के लिए रैप मोड प्राप्त करता है।

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's U coordinate.
### getVWrap() {#getVWrap--}
```
public abstract WrapMode getVWrap()
```


टेक्सचर के V निर्देशांक के लिए रैप मोड प्राप्त करता है।

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's V coordinate.
### getWWrap() {#getWWrap--}
```
public abstract WrapMode getWWrap()
```


टेक्सचर के W निर्देशांक के लिए रैप मोड प्राप्त करता है।

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the wrap mode for texture's W coordinate.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


इस टेक्सचर की चौड़ाई प्राप्त करता है।

**Returns:**
int - इस टेक्सचर की चौड़ाई।
### setMagnification(TextureFilter value) {#setMagnification-com.aspose.threed.TextureFilter-}
```
public abstract void setMagnification(TextureFilter value)
```


वृद्धि के लिए फ़िल्टर मोड सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | नया मान |

### setMinification(TextureFilter value) {#setMinification-com.aspose.threed.TextureFilter-}
```
public abstract void setMinification(TextureFilter value)
```


छोटा करने के लिए फ़िल्टर मोड सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | नया मान |

### setMipmap(TextureFilter value) {#setMipmap-com.aspose.threed.TextureFilter-}
```
public abstract void setMipmap(TextureFilter value)
```


मिपमैप के लिए फ़िल्टर मोड सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | नया मान |

### setScale(Vector2 value) {#setScale-com.aspose.threed.Vector2-}
```
public abstract void setScale(Vector2 value)
```


UV निर्देशांक का स्केल सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | नया मान |

### setScroll(Vector2 value) {#setScroll-com.aspose.threed.Vector2-}
```
public abstract void setScroll(Vector2 value)
```


UV निर्देशांक का स्क्रॉल सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | नया मान |

### setUWrap(WrapMode value) {#setUWrap-com.aspose.threed.WrapMode-}
```
public abstract void setUWrap(WrapMode value)
```


टेक्सचर के U निर्देशांक के लिए रैप मोड सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | नया मान |

### setVWrap(WrapMode value) {#setVWrap-com.aspose.threed.WrapMode-}
```
public abstract void setVWrap(WrapMode value)
```


टेक्सचर के V निर्देशांक के लिए रैप मोड सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | नया मान |

### setWWrap(WrapMode value) {#setWWrap-com.aspose.threed.WrapMode-}
```
public abstract void setWWrap(WrapMode value)
```


टेक्सचर के W निर्देशांक के लिए रैप मोड सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | नया मान |

