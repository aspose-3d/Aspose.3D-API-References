---
title: LambertMaterial
second_title: Aspose.3D for Java API-referens
description: Material för Lambert-skuggningsmodell
type: docs
weight: 92
url: /sv/java/com.aspose.threed/lambertmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class LambertMaterial extends Material
```

Material för Lambert-skuggningsmodell
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [LambertMaterial()](#LambertMaterial--) | Initierar en ny instans av klassen [LambertMaterial](../../com.aspose.threed/lambertmaterial). |
| [LambertMaterial(String name)](#LambertMaterial-java.lang.String-) | Initierar en ny instans av klassen [LambertMaterial](../../com.aspose.threed/lambertmaterial). |
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
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Ställer in texturen till angiven plats |
| [setTransparency(double value)](#setTransparency-double-) | Ställer in transparensfaktorn. |
| [setTransparentColor(Vector3 value)](#setTransparentColor-com.aspose.threed.Vector3-) | Ställer in den transparenta färgen |
| [toString()](#toString--) | Formaterar objekt till sträng |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LambertMaterial() {#LambertMaterial--}
```
public LambertMaterial()
```


Initierar en ny instans av klassen [LambertMaterial](../../com.aspose.threed/lambertmaterial).

### LambertMaterial(String name) {#LambertMaterial-java.lang.String-}
```
public LambertMaterial(String name)
```


Initierar en ny instans av klassen [LambertMaterial](../../com.aspose.threed/lambertmaterial).

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

