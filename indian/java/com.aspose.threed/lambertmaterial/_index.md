---
title: "LambertMaterial"
second_title: "Aspose.3D for Java API रेफ़रेंस"
description: "लैम्बर्ट शेडिंग मॉडल के लिए सामग्री"
type: docs
weight: 92
url: /hi/java/com.aspose.threed/lambertmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class LambertMaterial extends Material
```

लैम्बर्ट शेडिंग मॉडल के लिए सामग्री
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [LambertMaterial()](#LambertMaterial--) | नए [LambertMaterial](../../com.aspose.threed/lambertmaterial) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [LambertMaterial(String name)](#LambertMaterial-java.lang.String-) | नए [LambertMaterial](../../com.aspose.threed/lambertmaterial) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | एक ambient टेक्सचर मैपिंग असाइन करने के लिए [setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है। |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | एक diffuse टेक्सचर मैपिंग असाइन करने के लिए [setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है। |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | एक emissive टेक्सचर मैपिंग असाइन करने के लिए [setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है। |
| [MAP_NORMAL](#MAP-NORMAL) | एक normal टेक्सचर मैपिंग असाइन करने के लिए [setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है। |
| [MAP_SPECULAR](#MAP-SPECULAR) | एक specular टेक्सचर मैपिंग असाइन करने के लिए [setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getAmbientColor()](#getAmbientColor--) | ambient रंग प्राप्त करता है |
| [getClass()](#getClass--) |  |
| [getDiffuseColor()](#getDiffuseColor--) | diffuse रंग प्राप्त करता है |
| [getEmissiveColor()](#getEmissiveColor--) | emissive रंग प्राप्त करता है |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | निर्दिष्ट स्लॉट से टेक्सचर प्राप्त करता है, यह सामग्री की प्रॉपर्टी नाम या शेडर के पैरामीटर नाम हो सकता है। |
| [getTransparency()](#getTransparency--) | पारदर्शिता कारक प्राप्त करता है। |
| [getTransparentColor()](#getTransparentColor--) | पारदर्शी रंग प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | आंतरिक टेक्सचर स्लॉट्स को एने्यूमरेट करने के लिए एने्यूरेटर प्राप्त करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setAmbientColor(Vector3 value)](#setAmbientColor-com.aspose.threed.Vector3-) | ambient रंग सेट करता है |
| [setDiffuseColor(Vector3 value)](#setDiffuseColor-com.aspose.threed.Vector3-) | diffuse रंग सेट करता है |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | emissive रंग सेट करता है |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | टेक्सचर को निर्दिष्ट स्लॉट में सेट करता है |
| [setTransparency(double value)](#setTransparency-double-) | पारदर्शिता कारक सेट करता है। |
| [setTransparentColor(Vector3 value)](#setTransparentColor-com.aspose.threed.Vector3-) | पारदर्शी रंग सेट करता है। |
| [toString()](#toString--) | ऑब्जेक्ट को स्ट्रिंग में फ़ॉर्मेट करता है |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LambertMaterial() {#LambertMaterial--}
```
public LambertMaterial()
```


नए [LambertMaterial](../../com.aspose.threed/lambertmaterial) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

### LambertMaterial(String name) {#LambertMaterial-java.lang.String-}
```
public LambertMaterial(String name)
```


नए [LambertMaterial](../../com.aspose.threed/lambertmaterial) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | नाम |

### MAP_AMBIENT {#MAP-AMBIENT}
```
public static final String MAP_AMBIENT
```


एक ambient टेक्सचर मैपिंग असाइन करने के लिए [setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है।

### MAP_DIFFUSE {#MAP-DIFFUSE}
```
public static final String MAP_DIFFUSE
```


एक diffuse टेक्सचर मैपिंग असाइन करने के लिए [setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है।

### MAP_EMISSIVE {#MAP-EMISSIVE}
```
public static final String MAP_EMISSIVE
```


एक emissive टेक्सचर मैपिंग असाइन करने के लिए [setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है।

### MAP_NORMAL {#MAP-NORMAL}
```
public static final String MAP_NORMAL
```


एक normal टेक्सचर मैपिंग असाइन करने के लिए [setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है।

### MAP_SPECULAR {#MAP-SPECULAR}
```
public static final String MAP_SPECULAR
```


एक specular टेक्सचर मैपिंग असाइन करने के लिए [setTexture](../../com.aspose.threed/material\#setTexture) में उपयोग किया जाता है।

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


प्रॉपर्टी को खोजता है। यह एक डायनामिक प्रॉपर्टी (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या मूल प्रॉपर्टी (नाम द्वारा पहचानी गई) हो सकती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propertyName | java.lang.String | प्रॉपर्टी नाम। |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAmbientColor() {#getAmbientColor--}
```
public Vector3 getAmbientColor()
```


ambient रंग प्राप्त करता है

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the ambient color
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDiffuseColor() {#getDiffuseColor--}
```
public Vector3 getDiffuseColor()
```


diffuse रंग प्राप्त करता है

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


emissive रंग प्राप्त करता है

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color **Example:**

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
```
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी नाम |

**Returns:**
java.lang.Object - मिली हुई प्रॉपर्टी का मान
### getTexture(String slotName) {#getTexture-java.lang.String-}
```
public TextureBase getTexture(String slotName)
```


निर्दिष्ट स्लॉट से टेक्सचर प्राप्त करता है, यह सामग्री की प्रॉपर्टी नाम या शेडर के पैरामीटर नाम हो सकता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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


पारदर्शिता कारक प्राप्त करता है। कारक 0 (0%, पूरी तरह अपारदर्शी) और 1 (100%, पूरी तरह पारदर्शी) के बीच होना चाहिए। कोई भी अमान्य कारक मान को सीमित कर दिया जाएगा।

**Returns:**
double - पारदर्शिता कारक। कारक 0 (0%, पूरी तरह अपारदर्शी) और 1 (100%, पूरी तरह पारदर्शी) के बीच होना चाहिए। कोई भी अमान्य कारक मान को सीमित कर दिया जाएगा।
### getTransparentColor() {#getTransparentColor--}
```
public Vector3 getTransparentColor()
```


पारदर्शी रंग प्राप्त करता है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the transparent color.
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


आंतरिक टेक्सचर स्लॉट्स को एने्यूमरेट करने के लिए एने्यूरेटर प्राप्त करता है।

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
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | कौन सी प्रॉपर्टी हटानी है |

**Returns:**
boolean - यदि प्रॉपर्टी सफलतापूर्वक हटाई गई हो तो true
### setAmbientColor(Vector3 value) {#setAmbientColor-com.aspose.threed.Vector3-}
```
public void setAmbientColor(Vector3 value)
```


ambient रंग सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setDiffuseColor(Vector3 value) {#setDiffuseColor-com.aspose.threed.Vector3-}
```
public void setDiffuseColor(Vector3 value)
```


diffuse रंग सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


emissive रंग सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | नया मान **Example:** |

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


नाम सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


निर्दिष्ट प्रॉपर्टी का मान सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी नाम |
| मान | java.lang.Object | प्रॉपर्टी का मान |

### setTexture(String slotName, TextureBase texture) {#setTexture-java.lang.String-com.aspose.threed.TextureBase-}
```
public void setTexture(String slotName, TextureBase texture)
```


टेक्सचर को निर्दिष्ट स्लॉट में सेट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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


पारदर्शिता कारक सेट करता है। कारक 0 (0%, पूरी तरह अपारदर्शी) और 1 (100%, पूरी तरह पारदर्शी) के बीच होना चाहिए। कोई भी अमान्य कारक मान को सीमित कर दिया जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setTransparentColor(Vector3 value) {#setTransparentColor-com.aspose.threed.Vector3-}
```
public void setTransparentColor(Vector3 value)
```


पारदर्शी रंग सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

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

