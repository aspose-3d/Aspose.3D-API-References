---
title: PbrMaterial
second_title: Aspose.3D for Java API Reference
description: अल्बेडो रंग/धातुता/रफ़नेस पर आधारित फिज़िकली बेस्ड रेंडरिंग के लिए सामग्री।
type: docs
weight: 121
url: /hi/java/com.aspose.threed/pbrmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrMaterial extends Material
```

अल्बेडो रंग/धातुता/रफ़नेस पर आधारित फिज़िकली बेस्ड रेंडरिंग के लिए सामग्री।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [PbrMaterial()](#PbrMaterial--) | डिफ़ॉल्ट PBR सामग्री का इंस्टेंस बनाएं |
| [PbrMaterial(Vector3 albedo)](#PbrMaterial-com.aspose.threed.Vector3-) | निर्दिष्ट अल्बेडो रंग मान के साथ डिफ़ॉल्ट PBR सामग्री बनाएं। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | [setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है एक पर्यावरणीय टेक्सचर मैपिंग असाइन करने के लिए। |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | [setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है एक डिफ्यूज़ टेक्सचर मैपिंग असाइन करने के लिए। |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | [setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है एक उत्सर्जक टेक्सचर मैपिंग असाइन करने के लिए। |
| [MAP_NORMAL](#MAP-NORMAL) | [setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है एक सामान्य टेक्सचर मैपिंग असाइन करने के लिए। |
| [MAP_SPECULAR](#MAP-SPECULAR) | [setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है एक स्पेक्युलर टेक्सचर मैपिंग असाइन करने के लिए। |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [fromMaterial(Material material)](#fromMaterial-com.aspose.threed.Material-) | अन्य सामग्री को PbrMaterial में बदलने की अनुमति दें **Example:** |
| [getAlbedo()](#getAlbedo--) | सामग्री का बेस रंग प्राप्त करता है |
| [getAlbedoTexture()](#getAlbedoTexture--) | अल्बेडो के लिए टेक्सचर प्राप्त करता है |
| [getClass()](#getClass--) |  |
| [getEmissiveColor()](#getEmissiveColor--) | उत्सर्जक रंग प्राप्त करता है |
| [getEmissiveTexture()](#getEmissiveTexture--) | एमिसिव के लिए टेक्सचर प्राप्त करता है |
| [getMetallicFactor()](#getMetallicFactor--) | सामग्री की धातुता प्राप्त करता है, 1 का मान मतलब सामग्री धातु है और 0 का मान मतलब सामग्री डाइइलेक्ट्रिक है। |
| [getMetallicRoughness()](#getMetallicRoughness--) | धातुता (R चैनल में) और रफ़नेस (G चैनल में) के लिए टेक्सचर प्राप्त करता है |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getNormalTexture()](#getNormalTexture--) | नॉर्मल मैपिंग का टेक्सचर प्राप्त करता है |
| [getOcclusionFactor()](#getOcclusionFactor--) | एंबिएंट ऑक्लूज़न का फैक्टर प्राप्त करता है |
| [getOcclusionTexture()](#getOcclusionTexture--) | एंबिएंट ऑक्लूज़न के लिए टेक्सचर प्राप्त करता है |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getRoughnessFactor()](#getRoughnessFactor--) | सामग्री की रफ़नेस प्राप्त करता है, 1 का मान मतलब सामग्री पूरी तरह रफ़ है और 0 का मान मतलब सामग्री पूरी तरह स्मूद है। |
| [getSpecularTexture()](#getSpecularTexture--) | स्पेक्युलर रंग के लिए टेक्सचर प्राप्त करता है |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | निर्दिष्ट स्लॉट से टेक्सचर प्राप्त करता है, यह सामग्री की प्रॉपर्टी नाम या शेडर के पैरामीटर नाम हो सकता है। |
| [getTransparency()](#getTransparency--) | पारदर्शिता कारक प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | आंतरिक टेक्सचर स्लॉट्स को सूचीबद्ध करने के लिए एन्यूमरेटर प्राप्त करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setAlbedo(Vector3 value)](#setAlbedo-com.aspose.threed.Vector3-) | सामग्री का बेस रंग सेट करता है |
| [setAlbedoTexture(TextureBase value)](#setAlbedoTexture-com.aspose.threed.TextureBase-) | अल्बीडो के लिए टेक्सचर सेट करता है |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | उत्सर्जक रंग सेट करता है |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | इमिसिव के लिए टेक्सचर सेट करता है |
| [setMetallicFactor(double value)](#setMetallicFactor-double-) | सामग्री की धातुता सेट करता है, मान 1 का अर्थ है सामग्री धातु है और मान 0 का अर्थ है सामग्री डाइइलेक्ट्रिक है। |
| [setMetallicRoughness(TextureBase value)](#setMetallicRoughness-com.aspose.threed.TextureBase-) | धातुता (R चैनल में) और रफ़नेस (G चैनल में) के लिए टेक्सचर सेट करता है |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | नॉर्मल मैपिंग का टेक्सचर सेट करता है |
| [setOcclusionFactor(double value)](#setOcclusionFactor-double-) | एम्बिएंट ऑक्लूज़न का फ़ैक्टर सेट करता है |
| [setOcclusionTexture(TextureBase value)](#setOcclusionTexture-com.aspose.threed.TextureBase-) | एम्बिएंट ऑक्लूज़न के लिए टेक्सचर सेट करता है |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setRoughnessFactor(double value)](#setRoughnessFactor-double-) | सामग्री की रफ़नेस सेट करता है, मान 1 का अर्थ है सामग्री पूरी तरह रफ़ है और मान 0 का अर्थ है सामग्री पूरी तरह स्मूद है। |
| [setSpecularTexture(TextureBase value)](#setSpecularTexture-com.aspose.threed.TextureBase-) | स्पेक्यूलर रंग के लिए टेक्सचर सेट करता है |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | निर्दिष्ट स्लॉट में टेक्सचर सेट करता है |
| [setTransparency(double value)](#setTransparency-double-) | पारदर्शिता कारक सेट करता है। |
| [toString()](#toString--) | ऑब्जेक्ट को स्ट्रिंग में फ़ॉर्मेट करता है |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrMaterial() {#PbrMaterial--}
```
public PbrMaterial()
```


डिफ़ॉल्ट PBR सामग्री का इंस्टेंस बनाएं

### PbrMaterial(Vector3 albedo) {#PbrMaterial-com.aspose.threed.Vector3-}
```
public PbrMaterial(Vector3 albedo)
```


निर्दिष्ट अल्बेडो रंग मान के साथ डिफ़ॉल्ट PBR सामग्री बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| albedo | [Vector3](../../com.aspose.threed/vector3) | डिफ़ॉल्ट अल्बीडो रंग मान |

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
### fromMaterial(Material material) {#fromMaterial-com.aspose.threed.Material-}
```
public static PbrMaterial fromMaterial(Material material)
```


अन्य सामग्री को PbrMaterial में बदलने की अनुमति दें **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     mat.setDiffuseColor(new Vector3(0.3, 0.9, 0.4));
     PbrMaterial pbr = PbrMaterial.fromMaterial(mat);
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| material | [Material](../../com.aspose.threed/material) |  |

**Returns:**
[PbrMaterial](../../com.aspose.threed/pbrmaterial)
### getAlbedo() {#getAlbedo--}
```
public Vector3 getAlbedo()
```


सामग्री का बेस रंग प्राप्त करता है

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the base color of the material
### getAlbedoTexture() {#getAlbedoTexture--}
```
public TextureBase getAlbedoTexture()
```


अल्बेडो के लिए टेक्सचर प्राप्त करता है

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for albedo
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


उत्सर्जक रंग प्राप्त करता है

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


एमिसिव के लिए टेक्सचर प्राप्त करता है

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getMetallicFactor() {#getMetallicFactor--}
```
public double getMetallicFactor()
```


सामग्री की धातुता प्राप्त करता है, 1 का मान मतलब सामग्री धातु है और 0 का मान मतलब सामग्री डाइइलेक्ट्रिक है।

**Returns:**
डबल - सामग्री की धातुता, मान 1 का अर्थ है सामग्री धातु है और मान 0 का अर्थ है सामग्री डाइइलेक्ट्रिक है।
### getMetallicRoughness() {#getMetallicRoughness--}
```
public TextureBase getMetallicRoughness()
```


धातुता (R चैनल में) और रफ़नेस (G चैनल में) के लिए टेक्सचर प्राप्त करता है

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for metallic(in R channel) and roughness(in G channel)
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
### getOcclusionFactor() {#getOcclusionFactor--}
```
public double getOcclusionFactor()
```


एंबिएंट ऑक्लूज़न का फैक्टर प्राप्त करता है

**Returns:**
डबल - एंबिएंट ऑक्लूज़न का फ़ैक्टर
### getOcclusionTexture() {#getOcclusionTexture--}
```
public TextureBase getOcclusionTexture()
```


एंबिएंट ऑक्लूज़न के लिए टेक्सचर प्राप्त करता है

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for ambient occlusion
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
### getRoughnessFactor() {#getRoughnessFactor--}
```
public double getRoughnessFactor()
```


सामग्री की रफ़नेस प्राप्त करता है, 1 का मान मतलब सामग्री पूरी तरह रफ़ है और 0 का मान मतलब सामग्री पूरी तरह स्मूद है।

**Returns:**
डबल - सामग्री की रफ़नेस, मान 1 का अर्थ है सामग्री पूरी तरह रफ़ है और मान 0 का अर्थ है सामग्री पूरी तरह स्मूद है।
### getSpecularTexture() {#getSpecularTexture--}
```
public TextureBase getSpecularTexture()
```


स्पेक्युलर रंग के लिए टेक्सचर प्राप्त करता है

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color
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
### setAlbedo(Vector3 value) {#setAlbedo-com.aspose.threed.Vector3-}
```
public void setAlbedo(Vector3 value)
```


सामग्री का बेस रंग सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setAlbedoTexture(TextureBase value) {#setAlbedoTexture-com.aspose.threed.TextureBase-}
```
public void setAlbedoTexture(TextureBase value)
```


अल्बीडो के लिए टेक्सचर सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | नया मान |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


उत्सर्जक रंग सेट करता है

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

### setMetallicFactor(double value) {#setMetallicFactor-double-}
```
public void setMetallicFactor(double value)
```


सामग्री की धातुता सेट करता है, मान 1 का अर्थ है सामग्री धातु है और मान 0 का अर्थ है सामग्री डाइइलेक्ट्रिक है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setMetallicRoughness(TextureBase value) {#setMetallicRoughness-com.aspose.threed.TextureBase-}
```
public void setMetallicRoughness(TextureBase value)
```


धातुता (R चैनल में) और रफ़नेस (G चैनल में) के लिए टेक्सचर सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | नया मान |

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

### setOcclusionFactor(double value) {#setOcclusionFactor-double-}
```
public void setOcclusionFactor(double value)
```


एम्बिएंट ऑक्लूज़न का फ़ैक्टर सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setOcclusionTexture(TextureBase value) {#setOcclusionTexture-com.aspose.threed.TextureBase-}
```
public void setOcclusionTexture(TextureBase value)
```


एम्बिएंट ऑक्लूज़न के लिए टेक्सचर सेट करता है

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

### setRoughnessFactor(double value) {#setRoughnessFactor-double-}
```
public void setRoughnessFactor(double value)
```


सामग्री की रफ़नेस सेट करता है, मान 1 का अर्थ है सामग्री पूरी तरह रफ़ है और मान 0 का अर्थ है सामग्री पूरी तरह स्मूद है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setSpecularTexture(TextureBase value) {#setSpecularTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularTexture(TextureBase value)
```


स्पेक्यूलर रंग के लिए टेक्सचर सेट करता है

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

