---
title: PhongMaterial
second_title: Aspose.3D for Java API-referens
description: Material för blinn-phong-skuggningsmodell.
type: docs
weight: 126
url: /sv/java/com.aspose.threed/phongmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material), [com.aspose.threed.LambertMaterial](../../com.aspose.threed/lambertmaterial)
```
public class PhongMaterial extends LambertMaterial
```

Material för blinn-phong-skuggningsmodell.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PhongMaterial()](#PhongMaterial--) | Initierar en ny instans av klassen [PhongMaterial](../../com.aspose.threed/phongmaterial). |
| [PhongMaterial(String name)](#PhongMaterial-java.lang.String-) | Initierar en ny instans av klassen [PhongMaterial](../../com.aspose.threed/phongmaterial). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en ambient texturkartläggning. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en diffus texturkartläggning. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en emissiv texturkartläggning. |
| [MAP_NORMAL](#MAP-NORMAL) | Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en normal texturkartläggning. |
| [MAP_SPECULAR](#MAP-SPECULAR) | Används i [setTexture](../../com.aspose.threed/material\#setTexture) för att tilldela en spekulär texturkartläggning. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Hittar egenskapen. |
| [getAmbientColor()](#getAmbientColor--) | Hämtar den ambienta färgen |
| [getClass()](#getClass--) |  |
| [getDiffuseColor()](#getDiffuseColor--) | Hämtar den diffusa färgen |
| [getEmissiveColor()](#getEmissiveColor--) | Hämtar den emissiva färgen |
| [getName()](#getName--) | Hämtar namnet. |
| [getProperties()](#getProperties--) | Hämtar samlingen av alla egenskaper. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Hämta värdet för angiven egenskap |
| [getReflectionColor()](#getReflectionColor--) | Hämtar reflektionsfärgen. |
| [getReflectionFactor()](#getReflectionFactor--) | Hämtar dämpningen av reflektionsfärgen. |
| [getShininess()](#getShininess--) | Hämtar glansnivån, detta styr storleken på den spekulära högdpunkten. |
| [getSpecularColor()](#getSpecularColor--) | Hämtar den spekulära färgen. |
| [getSpecularFactor()](#getSpecularFactor--) | Hämtar den spekulära faktorn. |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Hämtar texturen från den angivna platsen, den kan vara materialets egenskapsnamn eller shaderns parameternamn |
| [getTransparency()](#getTransparency--) | Hämtar transparensfaktorn. |
| [getTransparentColor()](#getTransparentColor--) | Hämtar den transparenta färgen. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Hämtar enumeratorn för att enumerera interna texturplatser. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Tar bort en dynamisk egenskap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Ta bort den angivna egenskapen identifierad med namn |
| [setAmbientColor(Vector3 value)](#setAmbientColor-com.aspose.threed.Vector3-) | Ställer in den ambienta färgen |
| [setDiffuseColor(Vector3 value)](#setDiffuseColor-com.aspose.threed.Vector3-) | Ställer in den diffusa färgen |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Ställer in den emissiva färgen |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ställer in värdet för angiven egenskap |
| [setReflectionColor(Vector3 value)](#setReflectionColor-com.aspose.threed.Vector3-) | Ställer in reflektionsfärgen. |
| [setReflectionFactor(double value)](#setReflectionFactor-double-) | Ställer in dämpningen av reflektionsfärgen. |
| [setShininess(double value)](#setShininess-double-) | Ställer in glansigheten, detta styr storleken på den spekulära högdpunkten. |
| [setSpecularColor(Vector3 value)](#setSpecularColor-com.aspose.threed.Vector3-) | Ställer in den spekulära färgen. |
| [setSpecularFactor(double value)](#setSpecularFactor-double-) | Ställer in den spekulära faktorn. |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Ställer in texturen till angiven plats |
| [setTransparency(double value)](#setTransparency-double-) | Ställer in transparensfaktorn. |
| [setTransparentColor(Vector3 value)](#setTransparentColor-com.aspose.threed.Vector3-) | Ställer in den transparenta färgen |
| [toString()](#toString--) | Formaterar objekt till sträng |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhongMaterial() {#PhongMaterial--}
```
public PhongMaterial()
```


Initierar en ny instans av klassen [PhongMaterial](../../com.aspose.threed/phongmaterial).

### PhongMaterial(String name) {#PhongMaterial-java.lang.String-}
```
public PhongMaterial(String name)
```


Initierar en ny instans av klassen [PhongMaterial](../../com.aspose.threed/phongmaterial).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Namn |

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
### getAmbientColor() {#getAmbientColor--}
```
public Vector3 getAmbientColor()
```


Hämtar den ambienta färgen

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


Hämtar den diffusa färgen

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Hämtar den emissiva färgen

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


Hämtar namnet.

**Returns:**
java.lang.String - namnet.
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
### getReflectionColor() {#getReflectionColor--}
```
public Vector3 getReflectionColor()
```


Hämtar reflektionsfärgen.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the reflection color.
### getReflectionFactor() {#getReflectionFactor--}
```
public double getReflectionFactor()
```


Hämtar dämpningen av reflektionsfärgen.

**Returns:**
double - dämpningen av reflektionsfärgen.
### getShininess() {#getShininess--}
```
public double getShininess()
```


Hämtar glansigheten, detta styr storleken på den spekulära högdpunkten. Formeln för spekulär: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Returns:**
double - glansigheten, detta styr storleken på den spekulära högdpunkten. Formeln för spekulär: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess
### getSpecularColor() {#getSpecularColor--}
```
public Vector3 getSpecularColor()
```


Hämtar den spekulära färgen.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color.
### getSpecularFactor() {#getSpecularFactor--}
```
public double getSpecularFactor()
```


Hämtar den spekulära faktorn. Formeln för spekulär: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Returns:**
double - den spekulära faktorn. Formeln för spekulär: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess
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
### getTransparentColor() {#getTransparentColor--}
```
public Vector3 getTransparentColor()
```


Hämtar den transparenta färgen.

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
### setAmbientColor(Vector3 value) {#setAmbientColor-com.aspose.threed.Vector3-}
```
public void setAmbientColor(Vector3 value)
```


Ställer in den ambienta färgen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde |

### setDiffuseColor(Vector3 value) {#setDiffuseColor-com.aspose.threed.Vector3-}
```
public void setDiffuseColor(Vector3 value)
```


Ställer in den diffusa färgen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Ställer in den emissiva färgen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde **Exempel:** |

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ställer in namnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

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

### setReflectionColor(Vector3 value) {#setReflectionColor-com.aspose.threed.Vector3-}
```
public void setReflectionColor(Vector3 value)
```


Ställer in reflektionsfärgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde |

### setReflectionFactor(double value) {#setReflectionFactor-double-}
```
public void setReflectionFactor(double value)
```


Ställer in dämpningen av reflektionsfärgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setShininess(double value) {#setShininess-double-}
```
public void setShininess(double value)
```


Ställer in glansigheten, detta styr storleken på den spekulära högdpunkten. Formeln för spekulär: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setSpecularColor(Vector3 value) {#setSpecularColor-com.aspose.threed.Vector3-}
```
public void setSpecularColor(Vector3 value)
```


Ställer in den spekulära färgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde |

### setSpecularFactor(double value) {#setSpecularFactor-double-}
```
public void setSpecularFactor(double value)
```


Ställer in den spekulära faktorn. Formeln för spekulär: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

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

### setTransparentColor(Vector3 value) {#setTransparentColor-com.aspose.threed.Vector3-}
```
public void setTransparentColor(Vector3 value)
```


Ställer in den transparenta färgen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde |

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

