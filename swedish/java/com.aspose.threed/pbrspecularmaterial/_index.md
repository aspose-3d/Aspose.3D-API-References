---
title: PbrSpecularMaterial
second_title: Aspose.3D for Java API-referens
description: Material för fysiskt baserad rendering baserat på diffus färg/specular/glans.
type: docs
weight: 122
url: /sv/java/com.aspose.threed/pbrspecularmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrSpecularMaterial extends Material
```

Material för fysiskt baserad rendering baserat på diffus färg/specular/glans.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PbrSpecularMaterial()](#PbrSpecularMaterial--) | Konstruktor för [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial) |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en ambient texturkartläggning. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en diffus texturkartläggning. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en emissiv texturkartläggning. |
| [MAP_NORMAL](#MAP-NORMAL) | Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en normal texturkartläggning. |
| [MAP_SPECULAR](#MAP-SPECULAR) | Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en spekulär texturkartläggning. |
| [MAP_SPECULAR_GLOSSINESS](#MAP-SPECULAR-GLOSSINESS) | Texturkartan för spekulär glans |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Hittar egenskapen. |
| [getClass()](#getClass--) |  |
| [getDiffuse()](#getDiffuse--) | Hämtar det diffusa färgvärdet för materialet, standardvärdet är (1, 1, 1) |
| [getDiffuseTexture()](#getDiffuseTexture--) | Hämtar texturen för diffus |
| [getEmissiveColor()](#getEmissiveColor--) | Hämtar den emissiva färgen, standardvärdet är (0, 0, 0) |
| [getEmissiveTexture()](#getEmissiveTexture--) | Hämtar texturen för emissiv |
| [getGlossinessFactor()](#getGlossinessFactor--) | Hämtar glansen (slätheten) för materialet, 1 betyder helt slät och 0 betyder helt grov, standardvärdet är 1, intervallet är [0, 1] |
| [getName()](#getName--) | Hämtar namnet. |
| [getNormalTexture()](#getNormalTexture--) | Hämtar texturen för normalmappning |
| [getProperties()](#getProperties--) | Hämtar samlingen av alla egenskaper. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Hämta värdet för angiven egenskap |
| [getSpecular()](#getSpecular--) | Hämtar den spekulära färgen för materialet, standardvärdet är (1, 1, 1). |
| [getSpecularGlossinessTexture()](#getSpecularGlossinessTexture--) | Hämtar texturen för spekulär färg, kanalen RGB lagrar den spekulära färgen och kanalen A lagrar glansen. |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Hämtar texturen från den angivna platsen, den kan vara materialets egenskapsnamn eller shaderns parameternamn |
| [getTransparency()](#getTransparency--) | Hämtar transparensfaktorn. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Hämtar enumeratorn för att enumerera interna texturplatser. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Tar bort en dynamisk egenskap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Ta bort den angivna egenskapen identifierad med namn |
| [setDiffuse(Vector3 value)](#setDiffuse-com.aspose.threed.Vector3-) | Ställer in den diffusa färgen för materialet, standardvärdet är (1, 1, 1) |
| [setDiffuseTexture(TextureBase value)](#setDiffuseTexture-com.aspose.threed.TextureBase-) | Ställer in texturen för diffus |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Ställer in den emissiva färgen, standardvärdet är (0, 0, 0) |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | Ställer in texturen för emissiv |
| [setGlossinessFactor(double value)](#setGlossinessFactor-double-) | Ställer in glansigheten (slätheten) för materialet, 1 betyder helt slät och 0 betyder helt grov, standardvärdet är 1, intervallet är [0, 1] |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | Ställer in texturen för normalmappning |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ställer in värdet för angiven egenskap |
| [setSpecular(Vector3 value)](#setSpecular-com.aspose.threed.Vector3-) | Ställer in den spekulära färgen för materialet, standardvärdet är (1, 1, 1). |
| [setSpecularGlossinessTexture(TextureBase value)](#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-) | Ställer in texturen för spekulär färg, kanalen RGB lagrar den spekulära färgen och kanalen A lagrar glansigheten. |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Ställer in texturen till angiven plats |
| [setTransparency(double value)](#setTransparency-double-) | Ställer in transparensfaktorn. |
| [toString()](#toString--) | Formaterar objekt till sträng |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrSpecularMaterial() {#PbrSpecularMaterial--}
```
public PbrSpecularMaterial()
```


Konstruktor för [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial)

### MAP_AMBIENT {#MAP-AMBIENT}
```
public static final String MAP_AMBIENT
```


Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en ambient texturkartläggning.

### MAP_DIFFUSE {#MAP-DIFFUSE}
```
public static final String MAP_DIFFUSE
```


Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en diffus texturkartläggning.

### MAP_EMISSIVE {#MAP-EMISSIVE}
```
public static final String MAP_EMISSIVE
```


Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en emissiv texturkartläggning.

### MAP_NORMAL {#MAP-NORMAL}
```
public static final String MAP_NORMAL
```


Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en normal texturkartläggning.

### MAP_SPECULAR {#MAP-SPECULAR}
```
public static final String MAP_SPECULAR
```


Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en spekulär texturkartläggning.

### MAP_SPECULAR_GLOSSINESS {#MAP-SPECULAR-GLOSSINESS}
```
public static final String MAP_SPECULAR_GLOSSINESS
```


Texturkartan för spekulär glans

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Hittar egenskapen. Den kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller en inbyggd egenskap (Identifierad med dess namn)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propertyName | java.lang.String | Egenskapsnamn. |

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


Hämtar det diffusa färgvärdet för materialet, standardvärdet är (1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color of the material, default value is (1, 1, 1)
### getDiffuseTexture() {#getDiffuseTexture--}
```
public TextureBase getDiffuseTexture()
```


Hämtar texturen för diffus

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for diffuse
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Hämtar den emissiva färgen, standardvärdet är (0, 0, 0)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color, default value is (0, 0, 0)
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


Hämtar texturen för emissiv

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getGlossinessFactor() {#getGlossinessFactor--}
```
public double getGlossinessFactor()
```


Hämtar glansen (slätheten) för materialet, 1 betyder helt slät och 0 betyder helt grov, standardvärdet är 1, intervallet är [0, 1]

**Returns:**
double - glansigheten (slätheten) för materialet, 1 betyder helt slät och 0 betyder helt grov, standardvärdet är 1, intervallet är [0, 1]
### getName() {#getName--}
```
public String getName()
```


Hämtar namnet.

**Returns:**
java.lang.String - namnet.
### getNormalTexture() {#getNormalTexture--}
```
public TextureBase getNormalTexture()
```


Hämtar texturen för normalmappning

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture of normal mapping
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Hämtar samlingen av alla egenskaper.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Hämta värdet för angiven egenskap

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Egenskapsnamn |

**Returns:**
java.lang.Object - Värdet på den hittade egenskapen
### getSpecular() {#getSpecular--}
```
public Vector3 getSpecular()
```


Hämtar den spekulära färgen för materialet, standardvärdet är (1, 1, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color of the material, default value is (1, 1, 1).
### getSpecularGlossinessTexture() {#getSpecularGlossinessTexture--}
```
public TextureBase getSpecularGlossinessTexture()
```


Hämtar texturen för spekulär färg, kanalen RGB lagrar den spekulära färgen och kanalen A lagrar glansen.

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color, channel RGB stores the specular color and channel A stores the glossiness.
### getTexture(String slotName) {#getTexture-java.lang.String-}
```
public TextureBase getTexture(String slotName)
```


Hämtar texturen från den angivna platsen, den kan vara materialets egenskapsnamn eller shaderns parameternamn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| slotName | java.lang.String | Slotnamn. |

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


Hämtar transparensfaktorn. Faktorn bör ligga mellan 0 (0 %, helt ogenomskinlig) och 1 (100 %, helt genomskinlig). Eventuellt ogiltigt faktorsvärde kommer att klamras.

**Returns:**
double – transparensfaktorn. Faktorn bör ligga mellan 0 (0 %, helt ogenomskinlig) och 1 (100 %, helt genomskinlig). Eventuellt ogiltigt faktorsvärde kommer att klamras.
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


Hämtar enumeratorn för att enumerera interna texturplatser.

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


Tar bort en dynamisk egenskap.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Vilken egenskap som ska tas bort |

**Returns:**
boolean - true om egenskapen har tagits bort framgångsrikt
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Ta bort den angivna egenskapen identifierad med namn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Vilken egenskap som ska tas bort |

**Returns:**
boolean - true om egenskapen har tagits bort framgångsrikt
### setDiffuse(Vector3 value) {#setDiffuse-com.aspose.threed.Vector3-}
```
public void setDiffuse(Vector3 value)
```


Ställer in den diffusa färgen för materialet, standardvärdet är (1, 1, 1)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde |

### setDiffuseTexture(TextureBase value) {#setDiffuseTexture-com.aspose.threed.TextureBase-}
```
public void setDiffuseTexture(TextureBase value)
```


Ställer in texturen för diffus

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nytt värde |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Ställer in den emissiva färgen, standardvärdet är (0, 0, 0)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde |

### setEmissiveTexture(TextureBase value) {#setEmissiveTexture-com.aspose.threed.TextureBase-}
```
public void setEmissiveTexture(TextureBase value)
```


Ställer in texturen för emissiv

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nytt värde |

### setGlossinessFactor(double value) {#setGlossinessFactor-double-}
```
public void setGlossinessFactor(double value)
```


Ställer in glansigheten (slätheten) för materialet, 1 betyder helt slät och 0 betyder helt grov, standardvärdet är 1, intervallet är [0, 1]

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ställer in namnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setNormalTexture(TextureBase value) {#setNormalTexture-com.aspose.threed.TextureBase-}
```
public void setNormalTexture(TextureBase value)
```


Ställer in texturen för normalmappning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nytt värde |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Ställer in värdet för angiven egenskap

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Egenskapsnamn |
| värde | java.lang.Object | Värdet på egenskapen |

### setSpecular(Vector3 value) {#setSpecular-com.aspose.threed.Vector3-}
```
public void setSpecular(Vector3 value)
```


Ställer in den spekulära färgen för materialet, standardvärdet är (1, 1, 1).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde |

### setSpecularGlossinessTexture(TextureBase value) {#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularGlossinessTexture(TextureBase value)
```


Ställer in texturen för spekulär färg, kanalen RGB lagrar den spekulära färgen och kanalen A lagrar glansigheten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nytt värde |

### setTexture(String slotName, TextureBase texture) {#setTexture-java.lang.String-com.aspose.threed.TextureBase-}
```
public void setTexture(String slotName, TextureBase texture)
```


Ställer in texturen till angiven plats

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| slotName | java.lang.String | Slotnamn. |
|  | texture | [TextureBase](../../com.aspose.threed/texturebase) | Textur. **Exempel:** |

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


Sätter transparensfaktorn. Faktorn bör ligga mellan 0 (0 %, helt ogenomskinlig) och 1 (100 %, helt genomskinlig). Eventuellt ogiltigt faktorsvärde kommer att klamras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### toString() {#toString--}
```
public String toString()
```


Formaterar objekt till sträng

**Returns:**
java.lang.String - Objektsträng
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

