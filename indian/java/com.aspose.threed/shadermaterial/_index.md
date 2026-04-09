---
title: ShaderMaterial
second_title: Aspose.3D for Java API Reference
description: एक शेडर मैटेरियल बाहरी रेंडरिंग इंजन या शेडर भाषा द्वारा सामग्री का वर्णन करने की अनुमति देता है।
type: docs
weight: 164
url: /hi/java/com.aspose.threed/shadermaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class ShaderMaterial extends Material
```

एक शेडर सामग्री बाहरी रेंडरिंग इंजन या शेडर भाषा द्वारा सामग्री का वर्णन करने की अनुमति देती है। [ShaderMaterial](../../com.aspose.threed/shadermaterial) का उपयोग [ShaderTechnique](../../com.aspose.threed/shadertechnique) के द्वारा ठोस रेंडरिंग विवरण का वर्णन करने के लिए करता है, और सबसे उपयुक्त को अंतिम रेंडरिंग प्लेटफ़ॉर्म के अनुसार उपयोग किया जाएगा। उदाहरण के लिए, आपका [ShaderMaterial](../../com.aspose.threed/shadermaterial) उदाहरण दो तकनीकों रख सकता है, एक HLSL द्वारा परिभाषित, और दूसरा GLSL द्वारा परिभाषित। गैर-विंडो प्लेटफ़ॉर्म पर GLSL को HLSL के बजाय उपयोग किया जाना चाहिए।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [ShaderMaterial()](#ShaderMaterial--) | क्लास [ShaderMaterial](../../com.aspose.threed/shadermaterial) का एक नया उदाहरण प्रारंभ करता है। |
| [ShaderMaterial(String name)](#ShaderMaterial-java.lang.String-) | क्लास [ShaderMaterial](../../com.aspose.threed/shadermaterial) का एक नया उदाहरण प्रारंभ करता है। |
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
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getTechniques()](#getTechniques--) | इस सामग्री में परिभाषित सभी उपलब्ध तकनीकों को प्राप्त करता है। |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | निर्दिष्ट स्लॉट से टेक्सचर प्राप्त करता है, यह सामग्री की प्रॉपर्टी नाम या शेडर के पैरामीटर नाम हो सकता है। |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | आंतरिक टेक्सचर स्लॉट्स को सूचीबद्ध करने के लिए एन्यूमरेटर प्राप्त करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | निर्दिष्ट स्लॉट में टेक्सचर सेट करता है |
| [toString()](#toString--) | ऑब्जेक्ट को स्ट्रिंग में फ़ॉर्मेट करता है |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderMaterial() {#ShaderMaterial--}
```
public ShaderMaterial()
```


क्लास [ShaderMaterial](../../com.aspose.threed/shadermaterial) का एक नया उदाहरण प्रारंभ करता है।

### ShaderMaterial(String name) {#ShaderMaterial-java.lang.String-}
```
public ShaderMaterial(String name)
```


क्लास [ShaderMaterial](../../com.aspose.threed/shadermaterial) का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | नाम |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getTechniques() {#getTechniques--}
```
public List<ShaderTechnique> getTechniques()
```


इस सामग्री में परिभाषित सभी उपलब्ध तकनीकों को प्राप्त करता है।

**Returns:**
java.util.List<com.aspose.threed.ShaderTechnique> - इस सामग्री में परिभाषित सभी उपलब्ध तकनीकें।
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

