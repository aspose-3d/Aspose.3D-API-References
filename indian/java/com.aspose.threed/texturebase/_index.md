---
title: TextureBase
second_title: Aspose.3D for Java API Reference
description: सभी ठोस टेक्सचर के लिए बेस क्लास।
type: docs
weight: 185
url: /hi/java/com.aspose.threed/texturebase/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class TextureBase extends A3DObject
```

सभी ठोस टेक्सचर के लिए बेस क्लास। टेक्सचर जियोमेट्री सतह की दिखावट और अनुभूति को परिभाषित करता है।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [TextureBase(String name)](#TextureBase-java.lang.String-) | नया इंस्टेंस प्रारंभ करता है [TextureBase](../../com.aspose.threed/texturebase) क्लास का। |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getAlpha()](#getAlpha--) | टेक्सचर का डिफ़ॉल्ट अल्फा मान प्राप्त करता है। यह तब मान्य होता है जब [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) हो। डिफ़ॉल्ट मान 1.0 है, मान्य मान सीमा 0 से 1 के बीच है। |
| [getAlphaSource()](#getAlphaSource--) | जाँचता है कि टेक्सचर अल्फा चैनल को परिभाषित करता है या नहीं। |
| [getClass()](#getClass--) |  |
| [getMagFilter()](#getMagFilter--) | वृद्धि के लिए फ़िल्टर प्राप्त करता है। |
| [getMinFilter()](#getMinFilter--) | छोटा करने के लिए फ़िल्टर प्राप्त करता है। |
| [getMipFilter()](#getMipFilter--) | मिप‑लेवल सैंपलिंग के लिए फ़िल्टर प्राप्त करता है। |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getUVRotation()](#getUVRotation--) | टेक्सचर का घूर्णन प्राप्त करता है। |
| [getUVScale()](#getUVScale--) | UV स्केल प्राप्त करता है। |
| [getUVTranslation()](#getUVTranslation--) | UV अनुवाद प्राप्त करता है। |
| [getWrapModeU()](#getWrapModeU--) | U में टेक्सचर रैप मोड प्राप्त करता है। |
| [getWrapModeV()](#getWrapModeV--) | V में टेक्सचर रैप मोड प्राप्त करता है। |
| [getWrapModeW()](#getWrapModeW--) | W में टेक्सचर रैप मोड प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setAlpha(double value)](#setAlpha-double-) | टेक्सचर का डिफ़ॉल्ट अल्फा मान सेट करता है। यह तब मान्य होता है जब [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) हो। डिफ़ॉल्ट मान 1.0 है, मान्य मान सीमा 0 से 1 के बीच है। |
| [setAlphaSource(AlphaSource value)](#setAlphaSource-com.aspose.threed.AlphaSource-) | सेट करता है कि टेक्सचर अल्फा चैनल को परिभाषित करता है या नहीं। |
| [setMagFilter(TextureFilter value)](#setMagFilter-com.aspose.threed.TextureFilter-) | वृद्धि के लिए फ़िल्टर सेट करता है। |
| [setMinFilter(TextureFilter value)](#setMinFilter-com.aspose.threed.TextureFilter-) | संकुचन के लिए फ़िल्टर सेट करता है। |
| [setMipFilter(TextureFilter value)](#setMipFilter-com.aspose.threed.TextureFilter-) | मिप-लेवल सैंपलिंग के लिए फ़िल्टर सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setRotation(double u, double v)](#setRotation-double-double-) | UV घूर्णन सेट करता है। |
| [setScale(double u, double v)](#setScale-double-double-) | UV स्केल सेट करता है। |
| [setTranslation(double u, double v)](#setTranslation-double-double-) | UV अनुवाद सेट करता है। |
| [setUVRotation(Vector3 value)](#setUVRotation-com.aspose.threed.Vector3-) | टेक्सचर का घूर्णन सेट करता है |
| [setUVScale(Vector2 value)](#setUVScale-com.aspose.threed.Vector2-) | UV स्केल सेट करता है। |
| [setUVTranslation(Vector2 value)](#setUVTranslation-com.aspose.threed.Vector2-) | UV अनुवाद सेट करता है। |
| [setWrapModeU(WrapMode value)](#setWrapModeU-com.aspose.threed.WrapMode-) | U में टेक्सचर रैप मोड सेट करता है। |
| [setWrapModeV(WrapMode value)](#setWrapModeV-com.aspose.threed.WrapMode-) | V में टेक्सचर रैप मोड सेट करता है। |
| [setWrapModeW(WrapMode value)](#setWrapModeW-com.aspose.threed.WrapMode-) | W में टेक्सचर रैप मोड सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureBase(String name) {#TextureBase-java.lang.String-}
```
public TextureBase(String name)
```


नया इंस्टेंस प्रारंभ करता है [TextureBase](../../com.aspose.threed/texturebase) क्लास का।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | नाम। |

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
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


प्रॉपर्टी को खोजता है। यह एक डायनामिक प्रॉपर्टी (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या नेटिव प्रॉपर्टी (नाम द्वारा पहचानी गई) हो सकती है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| propertyName | java.lang.String | प्रॉपर्टी नाम। |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAlpha() {#getAlpha--}
```
public double getAlpha()
```


टेक्सचर का डिफ़ॉल्ट अल्फा मान प्राप्त करता है। यह तब मान्य होता है जब [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) हो। डिफ़ॉल्ट मान 1.0 है, मान्य मान सीमा 0 से 1 के बीच है।

**Returns:**
double - टेक्सचर का डिफ़ॉल्ट अल्फा मान। यह तब मान्य है जब [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) हो। डिफ़ॉल्ट मान 1.0 है, मान्य मान सीमा 0 और 1 के बीच है।
### getAlphaSource() {#getAlphaSource--}
```
public AlphaSource getAlphaSource()
```


टेक्सचर अल्फा चैनल को परिभाषित करता है या नहीं प्राप्त करता है। डिफ़ॉल्ट मान है [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

**Returns:**
[AlphaSource](../../com.aspose.threed/alphasource) - whether the texture defines the alpha channel. Default value is [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMagFilter() {#getMagFilter--}
```
public TextureFilter getMagFilter()
```


वृद्धि के लिए फ़िल्टर प्राप्त करता है।

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for magnification.
### getMinFilter() {#getMinFilter--}
```
public TextureFilter getMinFilter()
```


छोटा करने के लिए फ़िल्टर प्राप्त करता है।

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for minification.
### getMipFilter() {#getMipFilter--}
```
public TextureFilter getMipFilter()
```


मिप‑लेवल सैंपलिंग के लिए फ़िल्टर प्राप्त करता है।

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for mip-level sampling.
### getName() {#getName--}
```
public String getName()
```


नाम प्राप्त करता है।

**Returns:**
java.lang.String - नाम।
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है।

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी नाम |

**Returns:**
java.lang.Object - मिली हुई प्रॉपर्टी का मान
### getUVRotation() {#getUVRotation--}
```
public Vector3 getUVRotation()
```


टेक्सचर का घूर्णन प्राप्त करता है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation of the texture
### getUVScale() {#getUVScale--}
```
public Vector2 getUVScale()
```


UV स्केल प्राप्त करता है।

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV scale.
### getUVTranslation() {#getUVTranslation--}
```
public Vector2 getUVTranslation()
```


UV अनुवाद प्राप्त करता है।

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV translation.
### getWrapModeU() {#getWrapModeU--}
```
public WrapMode getWrapModeU()
```


U में टेक्सचर रैप मोड प्राप्त करता है।

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in U.
### getWrapModeV() {#getWrapModeV--}
```
public WrapMode getWrapModeV()
```


V में टेक्सचर रैप मोड प्राप्त करता है।

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in V.
### getWrapModeW() {#getWrapModeW--}
```
public WrapMode getWrapModeW()
```


W में टेक्सचर रैप मोड प्राप्त करता है।

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in W.
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




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


डायनामिक प्रॉपर्टी को हटाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | कौन सी प्रॉपर्टी हटानी है |

**Returns:**
boolean - यदि प्रॉपर्टी सफलतापूर्वक हटाई गई हो तो true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | कौन सी प्रॉपर्टी हटानी है |

**Returns:**
boolean - यदि प्रॉपर्टी सफलतापूर्वक हटाई गई हो तो true
### setAlpha(double value) {#setAlpha-double-}
```
public void setAlpha(double value)
```


टेक्सचर का डिफ़ॉल्ट अल्फा मान सेट करता है। यह तब मान्य होता है जब [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA) हो। डिफ़ॉल्ट मान 1.0 है, मान्य मान सीमा 0 से 1 के बीच है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setAlphaSource(AlphaSource value) {#setAlphaSource-com.aspose.threed.AlphaSource-}
```
public void setAlphaSource(AlphaSource value)
```


टेक्सचर अल्फा चैनल को परिभाषित करता है या नहीं सेट करता है। डिफ़ॉल्ट मान है [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [AlphaSource](../../com.aspose.threed/alphasource) | नया मान |

### setMagFilter(TextureFilter value) {#setMagFilter-com.aspose.threed.TextureFilter-}
```
public void setMagFilter(TextureFilter value)
```


वृद्धि के लिए फ़िल्टर सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | नया मान |

### setMinFilter(TextureFilter value) {#setMinFilter-com.aspose.threed.TextureFilter-}
```
public void setMinFilter(TextureFilter value)
```


संकुचन के लिए फ़िल्टर सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | नया मान |

### setMipFilter(TextureFilter value) {#setMipFilter-com.aspose.threed.TextureFilter-}
```
public void setMipFilter(TextureFilter value)
```


मिप-लेवल सैंपलिंग के लिए फ़िल्टर सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | नया मान |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


नाम सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


निर्दिष्ट प्रॉपर्टी का मान सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी नाम |
| मान | java.lang.Object | प्रॉपर्टी का मान |

### setRotation(double u, double v) {#setRotation-double-double-}
```
public void setRotation(double u, double v)
```


UV घूर्णन सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setScale(double u, double v) {#setScale-double-double-}
```
public void setScale(double u, double v)
```


UV स्केल सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setTranslation(double u, double v) {#setTranslation-double-double-}
```
public void setTranslation(double u, double v)
```


UV अनुवाद सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setUVRotation(Vector3 value) {#setUVRotation-com.aspose.threed.Vector3-}
```
public void setUVRotation(Vector3 value)
```


टेक्सचर का घूर्णन सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setUVScale(Vector2 value) {#setUVScale-com.aspose.threed.Vector2-}
```
public void setUVScale(Vector2 value)
```


UV स्केल सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | नया मान |

### setUVTranslation(Vector2 value) {#setUVTranslation-com.aspose.threed.Vector2-}
```
public void setUVTranslation(Vector2 value)
```


UV अनुवाद सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | नया मान |

### setWrapModeU(WrapMode value) {#setWrapModeU-com.aspose.threed.WrapMode-}
```
public void setWrapModeU(WrapMode value)
```


U में टेक्सचर रैप मोड सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | नया मान |

### setWrapModeV(WrapMode value) {#setWrapModeV-com.aspose.threed.WrapMode-}
```
public void setWrapModeV(WrapMode value)
```


V में टेक्सचर रैप मोड सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | नया मान |

### setWrapModeW(WrapMode value) {#setWrapModeW-com.aspose.threed.WrapMode-}
```
public void setWrapModeW(WrapMode value)
```


W में टेक्सचर रैप मोड सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | नया मान |

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

