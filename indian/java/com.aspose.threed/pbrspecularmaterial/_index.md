---
title: PbrSpecularMaterial
second_title: Aspose.3D for Java API Reference
description: डिफ्यूज़ रंग/स्पेक्यूलर/ग्लॉसिनेस पर आधारित फिज़िकली बेस्ड रेंडरिंग के लिए सामग्री।
type: docs
weight: 122
url: /hi/java/com.aspose.threed/pbrspecularmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrSpecularMaterial extends Material
```

डिफ्यूज़ रंग/स्पेक्यूलर/ग्लॉसिनेस पर आधारित फिज़िकली बेस्ड रेंडरिंग के लिए सामग्री।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [PbrSpecularMaterial()](#PbrSpecularMaterial--) | [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial) का कंस्ट्रक्टर |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | [setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है एक पर्यावरणीय टेक्सचर मैपिंग असाइन करने के लिए। |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | [setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है एक डिफ्यूज़ टेक्सचर मैपिंग असाइन करने के लिए। |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | [setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है एक उत्सर्जक टेक्सचर मैपिंग असाइन करने के लिए। |
| [MAP_NORMAL](#MAP-NORMAL) | [setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है एक सामान्य टेक्सचर मैपिंग असाइन करने के लिए। |
| [MAP_SPECULAR](#MAP-SPECULAR) | [setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है एक स्पेक्युलर टेक्सचर मैपिंग असाइन करने के लिए। |
| [MAP_SPECULAR_GLOSSINESS](#MAP-SPECULAR-GLOSSINESS) | स्पेक्युलर ग्लॉसिनेस के लिए टेक्सचर मैप |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getClass()](#getClass--) |  |
| [getDiffuse()](#getDiffuse--) | सामग्री का डिफ्यूज़ रंग प्राप्त करता है, डिफ़ॉल्ट मान (1, 1, 1) है |
| [getDiffuseTexture()](#getDiffuseTexture--) | डिफ्यूज़ के लिए टेक्सचर प्राप्त करता है |
| [getEmissiveColor()](#getEmissiveColor--) | एमिसिव रंग प्राप्त करता है, डिफ़ॉल्ट मान (0, 0, 0) है |
| [getEmissiveTexture()](#getEmissiveTexture--) | एमिसिव के लिए टेक्सचर प्राप्त करता है |
| [getGlossinessFactor()](#getGlossinessFactor--) | सामग्री की ग्लॉसिनेस (स्मूदनेस) प्राप्त करता है, 1 का मतलब पूरी तरह स्मूद और 0 का मतलब पूरी तरह रफ़ है, डिफ़ॉल्ट मान 1 है, रेंज [0, 1] है |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getNormalTexture()](#getNormalTexture--) | नॉर्मल मैपिंग का टेक्सचर प्राप्त करता है |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getSpecular()](#getSpecular--) | सामग्री का स्पेक्युलर रंग प्राप्त करता है, डिफ़ॉल्ट मान (1, 1, 1) है। |
| [getSpecularGlossinessTexture()](#getSpecularGlossinessTexture--) | स्पेक्युलर रंग के लिए टेक्सचर प्राप्त करता है, चैनल RGB स्पेक्युलर रंग संग्रहीत करता है और चैनल A ग्लॉसिनेस संग्रहीत करता है। |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | निर्दिष्ट स्लॉट से टेक्सचर प्राप्त करता है, यह सामग्री की प्रॉपर्टी नाम या शेडर के पैरामीटर नाम हो सकता है। |
| [getTransparency()](#getTransparency--) | पारदर्शिता कारक प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | आंतरिक टेक्सचर स्लॉट्स को सूचीबद्ध करने के लिए एन्यूमरेटर प्राप्त करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setDiffuse(Vector3 value)](#setDiffuse-com.aspose.threed.Vector3-) | सामग्री का डिफ्यूज़ रंग सेट करता है, डिफ़ॉल्ट मान (1, 1, 1) है |
| [setDiffuseTexture(TextureBase value)](#setDiffuseTexture-com.aspose.threed.TextureBase-) | डिफ्यूज़ के लिए टेक्सचर सेट करता है |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | एमिसिव रंग सेट करता है, डिफ़ॉल्ट मान (0, 0, 0) है |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | इमिसिव के लिए टेक्सचर सेट करता है |
| [setGlossinessFactor(double value)](#setGlossinessFactor-double-) | सामग्री की चमक (स्मूदनेस) सेट करता है, 1 का मतलब पूरी तरह स्मूद और 0 का मतलब पूरी तरह रफ़ है, डिफ़ॉल्ट मान 1 है, रेंज [0, 1] है |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | नॉर्मल मैपिंग का टेक्सचर सेट करता है |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setSpecular(Vector3 value)](#setSpecular-com.aspose.threed.Vector3-) | सामग्री का स्पेक्युलर रंग सेट करता है, डिफ़ॉल्ट मान (1, 1, 1) है। |
| [setSpecularGlossinessTexture(TextureBase value)](#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-) | स्पेक्युलर रंग के लिए टेक्सचर सेट करता है, चैनल RGB स्पेक्युलर रंग संग्रहीत करता है और चैनल A चमक संग्रहीत करता है। |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | निर्दिष्ट स्लॉट में टेक्सचर सेट करता है |
| [setTransparency(double value)](#setTransparency-double-) | पारदर्शिता कारक सेट करता है। |
| [toString()](#toString--) | ऑब्जेक्ट को स्ट्रिंग में फ़ॉर्मेट करता है |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrSpecularMaterial() {#PbrSpecularMaterial--}
```
public PbrSpecularMaterial()
```


[PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial) का कंस्ट्रक्टर

### MAP_AMBIENT {#MAP-AMBIENT}
```
public static final String MAP_AMBIENT
```


[setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है एक पर्यावरणीय टेक्सचर मैपिंग असाइन करने के लिए।

### MAP_DIFFUSE {#MAP-DIFFUSE}
```
public static final String MAP_DIFFUSE
```


[setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है एक डिफ्यूज़ टेक्सचर मैपिंग असाइन करने के लिए।

### MAP_EMISSIVE {#MAP-EMISSIVE}
```
public static final String MAP_EMISSIVE
```


[setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है एक उत्सर्जक टेक्सचर मैपिंग असाइन करने के लिए।

### MAP_NORMAL {#MAP-NORMAL}
```
public static final String MAP_NORMAL
```


[setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है एक सामान्य टेक्सचर मैपिंग असाइन करने के लिए।

### MAP_SPECULAR {#MAP-SPECULAR}
```
public static final String MAP_SPECULAR
```


[setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है एक स्पेक्युलर टेक्सचर मैपिंग असाइन करने के लिए।

### MAP_SPECULAR_GLOSSINESS {#MAP-SPECULAR-GLOSSINESS}
```
public static final String MAP_SPECULAR_GLOSSINESS
```


स्पेक्युलर ग्लॉसिनेस के लिए टेक्सचर मैप

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDiffuse() {#getDiffuse--}
```
public Vector3 getDiffuse()
```


सामग्री का डिफ्यूज़ रंग प्राप्त करता है, डिफ़ॉल्ट मान (1, 1, 1) है

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color of the material, default value is (1, 1, 1)
### getDiffuseTexture() {#getDiffuseTexture--}
```
public TextureBase getDiffuseTexture()
```


डिफ्यूज़ के लिए टेक्सचर प्राप्त करता है

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for diffuse
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


एमिसिव रंग प्राप्त करता है, डिफ़ॉल्ट मान (0, 0, 0) है

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color, default value is (0, 0, 0)
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


एमिसिव के लिए टेक्सचर प्राप्त करता है

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getGlossinessFactor() {#getGlossinessFactor--}
```
public double getGlossinessFactor()
```


सामग्री की ग्लॉसिनेस (स्मूदनेस) प्राप्त करता है, 1 का मतलब पूरी तरह स्मूद और 0 का मतलब पूरी तरह रफ़ है, डिफ़ॉल्ट मान 1 है, रेंज [0, 1] है

**Returns:**
डबल - सामग्री की चमक (स्मूदनेस), 1 का मतलब पूरी तरह स्मूद और 0 का मतलब पूरी तरह रफ़ है, डिफ़ॉल्ट मान 1 है, रेंज [0, 1] है
### getName() {#getName--}
```
public String getName()
```


नाम प्राप्त करता है।

**Returns:**
java.lang.String - नाम।
### getNormalTexture() {#getNormalTexture--}
```
public TextureBase getNormalTexture()
```


नॉर्मल मैपिंग का टेक्सचर प्राप्त करता है

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture of normal mapping
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
### getSpecular() {#getSpecular--}
```
public Vector3 getSpecular()
```


सामग्री का स्पेक्युलर रंग प्राप्त करता है, डिफ़ॉल्ट मान (1, 1, 1) है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color of the material, default value is (1, 1, 1).
### getSpecularGlossinessTexture() {#getSpecularGlossinessTexture--}
```
public TextureBase getSpecularGlossinessTexture()
```


स्पेक्युलर रंग के लिए टेक्सचर प्राप्त करता है, चैनल RGB स्पेक्युलर रंग संग्रहीत करता है और चैनल A ग्लॉसिनेस संग्रहीत करता है।

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color, channel RGB stores the specular color and channel A stores the glossiness.
### getTexture(String slotName) {#getTexture-java.lang.String-}
```
public TextureBase getTexture(String slotName)
```


निर्दिष्ट स्लॉट से टेक्सचर प्राप्त करता है, यह सामग्री की प्रॉपर्टी नाम या शेडर के पैरामीटर नाम हो सकता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| slotName | java.lang.String | स्लॉट नाम। |

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - The texture. **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     tex = (Texture)mat.getTexture(Material.MAP_DIFFUSE);
```
### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


पारदर्शिता कारक प्राप्त करता है। कारक 0 (0%, पूरी तरह अपारदर्शी) से 1 (100%, पूरी तरह पारदर्शी) के बीच होना चाहिए। कोई भी अमान्य कारक मान को सीमित कर दिया जाएगा।

**Returns:**
double - पारदर्शिता कारक। कारक 0 (0%, पूरी तरह अपारदर्शी) से 1 (100%, पूरी तरह पारदर्शी) के बीच होना चाहिए। कोई भी अमान्य कारक मान को सीमित कर दिया जाएगा।
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public Iterator<TextureSlot> iterator()
```


आंतरिक टेक्सचर स्लॉट्स को सूचीबद्ध करने के लिए एन्यूमरेटर प्राप्त करता है।

**Returns:**
java.util.Iterator<com.aspose.threed.TextureSlot>
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
### setDiffuse(Vector3 value) {#setDiffuse-com.aspose.threed.Vector3-}
```
public void setDiffuse(Vector3 value)
```


सामग्री का डिफ्यूज़ रंग सेट करता है, डिफ़ॉल्ट मान (1, 1, 1) है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setDiffuseTexture(TextureBase value) {#setDiffuseTexture-com.aspose.threed.TextureBase-}
```
public void setDiffuseTexture(TextureBase value)
```


डिफ्यूज़ के लिए टेक्सचर सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | नया मान |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


एमिसिव रंग सेट करता है, डिफ़ॉल्ट मान (0, 0, 0) है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setEmissiveTexture(TextureBase value) {#setEmissiveTexture-com.aspose.threed.TextureBase-}
```
public void setEmissiveTexture(TextureBase value)
```


इमिसिव के लिए टेक्सचर सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | नया मान |

### setGlossinessFactor(double value) {#setGlossinessFactor-double-}
```
public void setGlossinessFactor(double value)
```


सामग्री की चमक (स्मूदनेस) सेट करता है, 1 का मतलब पूरी तरह स्मूद और 0 का मतलब पूरी तरह रफ़ है, डिफ़ॉल्ट मान 1 है, रेंज [0, 1] है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


नाम सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setNormalTexture(TextureBase value) {#setNormalTexture-com.aspose.threed.TextureBase-}
```
public void setNormalTexture(TextureBase value)
```


नॉर्मल मैपिंग का टेक्सचर सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | नया मान |

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

### setSpecular(Vector3 value) {#setSpecular-com.aspose.threed.Vector3-}
```
public void setSpecular(Vector3 value)
```


सामग्री का स्पेक्युलर रंग सेट करता है, डिफ़ॉल्ट मान (1, 1, 1) है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setSpecularGlossinessTexture(TextureBase value) {#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularGlossinessTexture(TextureBase value)
```


स्पेक्युलर रंग के लिए टेक्सचर सेट करता है, चैनल RGB स्पेक्युलर रंग संग्रहीत करता है और चैनल A चमक संग्रहीत करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | नया मान |

### setTexture(String slotName, TextureBase texture) {#setTexture-java.lang.String-com.aspose.threed.TextureBase-}
```
public void setTexture(String slotName, TextureBase texture)
```


निर्दिष्ट स्लॉट में टेक्सचर सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| slotName | java.lang.String | स्लॉट नाम। |
|  | texture | [TextureBase](../../com.aspose.threed/texturebase) | टेक्सचर। **Example:** |

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_NORMAL, tex);
``` |

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


पारदर्शिता कारक सेट करता है। कारक 0 (0%, पूरी तरह अपारदर्शी) से 1 (100%, पूरी तरह पारदर्शी) के बीच होना चाहिए। कोई भी अमान्य कारक मान को सीमित कर दिया जाएगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### toString() {#toString--}
```
public String toString()
```


ऑब्जेक्ट को स्ट्रिंग में फ़ॉर्मेट करता है

**Returns:**
java.lang.String - ऑब्जेक्ट स्ट्रिंग
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

