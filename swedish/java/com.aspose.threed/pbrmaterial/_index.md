---
title: PbrMaterial
second_title: Aspose.3D for Java API-referens
description: Material för fysiskt baserad rendering baserat på albedo-färg/metallisk/ytstruktur.
type: docs
weight: 121
url: /sv/java/com.aspose.threed/pbrmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrMaterial extends Material
```

Material för fysiskt baserad rendering baserat på albedo-färg/metallisk/ytstruktur.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PbrMaterial()](#PbrMaterial--) | Construct a default PBR material instance |
| [PbrMaterial(Vector3 albedo)](#PbrMaterial-com.aspose.threed.Vector3-) | Construct a default PBR material with specified albedo color value. |
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
| [fromMaterial(Material material)](#fromMaterial-com.aspose.threed.Material-) | Allow convert other material to PbrMaterial **Example:** |
| [getAlbedo()](#getAlbedo--) | Gets the base color of the material |
| [getAlbedoTexture()](#getAlbedoTexture--) | Gets the texture for albedo |
| [getClass()](#getClass--) |  |
| [getEmissiveColor()](#getEmissiveColor--) | Hämtar den emissiva färgen |
| [getEmissiveTexture()](#getEmissiveTexture--) | Hämtar texturen för emissiv |
| [getMetallicFactor()](#getMetallicFactor--) | Gets the metalness of the material, value of 1 means the material is a metal and value of 0 means the material is a dielectric. |
| [getMetallicRoughness()](#getMetallicRoughness--) | Gets the texture for metallic(in R channel) and roughness(in G channel) |
| [getName()](#getName--) | Hämtar namnet. |
| [getNormalTexture()](#getNormalTexture--) | Hämtar texturen för normalmappning |
| [getOcclusionFactor()](#getOcclusionFactor--) | Gets the factor of ambient occlusion |
| [getOcclusionTexture()](#getOcclusionTexture--) | Gets the texture for ambient occlusion |
| [getProperties()](#getProperties--) | Hämtar samlingen av alla egenskaper. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Hämta värdet för angiven egenskap |
| [getRoughnessFactor()](#getRoughnessFactor--) | Gets the roughness of the material, value of 1 means the material is completely rough and value of 0 means the material is completely smooth |
| [getSpecularTexture()](#getSpecularTexture--) | Gets the texture for specular color |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Hämtar texturen från den angivna platsen, den kan vara materialets egenskapsnamn eller shaderns parameternamn |
| [getTransparency()](#getTransparency--) | Hämtar transparensfaktorn. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Hämtar enumeratorn för att enumerera interna texturplatser. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Tar bort en dynamisk egenskap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Ta bort den angivna egenskapen identifierad med namn |
| [setAlbedo(Vector3 value)](#setAlbedo-com.aspose.threed.Vector3-) | Sets the base color of the material |
| [setAlbedoTexture(TextureBase value)](#setAlbedoTexture-com.aspose.threed.TextureBase-) | Ställer in texturen för albedo |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Ställer in den emissiva färgen |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | Ställer in texturen för emissiv |
| [setMetallicFactor(double value)](#setMetallicFactor-double-) | Ställer in metalligheten för materialet, ett värde på 1 betyder att materialet är en metall och ett värde på 0 betyder att materialet är ett dielektrikum. |
| [setMetallicRoughness(TextureBase value)](#setMetallicRoughness-com.aspose.threed.TextureBase-) | Ställer in texturen för metallisk (i R-kanalen) och grovhet (i G-kanalen) |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | Ställer in texturen för normalmappning |
| [setOcclusionFactor(double value)](#setOcclusionFactor-double-) | Ställer in faktorn för ambient occlusion |
| [setOcclusionTexture(TextureBase value)](#setOcclusionTexture-com.aspose.threed.TextureBase-) | Ställer in texturen för ambient occlusion |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ställer in värdet för angiven egenskap |
| [setRoughnessFactor(double value)](#setRoughnessFactor-double-) | Ställer in grovheten för materialet, ett värde på 1 betyder att materialet är helt grovt och ett värde på 0 betyder att materialet är helt slätt |
| [setSpecularTexture(TextureBase value)](#setSpecularTexture-com.aspose.threed.TextureBase-) | Ställer in texturen för spekulär färg |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Ställer in texturen till angiven plats |
| [setTransparency(double value)](#setTransparency-double-) | Ställer in transparensfaktorn. |
| [toString()](#toString--) | Formaterar objekt till sträng |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrMaterial() {#PbrMaterial--}
```
public PbrMaterial()
```


Construct a default PBR material instance

### PbrMaterial(Vector3 albedo) {#PbrMaterial-com.aspose.threed.Vector3-}
```
public PbrMaterial(Vector3 albedo)
```


Construct a default PBR material with specified albedo color value.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| albedo | [Vector3](../../com.aspose.threed/vector3) | Standardvärdet för albedo-färg |

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
### fromMaterial(Material material) {#fromMaterial-com.aspose.threed.Material-}
```
public static PbrMaterial fromMaterial(Material material)
```


Allow convert other material to PbrMaterial **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     mat.setDiffuseColor(new Vector3(0.3, 0.9, 0.4));
     PbrMaterial pbr = PbrMaterial.fromMaterial(mat);
```

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| material | [Material](../../com.aspose.threed/material) |  |

**Returns:**
[PbrMaterial](../../com.aspose.threed/pbrmaterial)
### getAlbedo() {#getAlbedo--}
```
public Vector3 getAlbedo()
```


Gets the base color of the material

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the base color of the material
### getAlbedoTexture() {#getAlbedoTexture--}
```
public TextureBase getAlbedoTexture()
```


Gets the texture for albedo

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


Hämtar den emissiva färgen

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


Hämtar texturen för emissiv

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getMetallicFactor() {#getMetallicFactor--}
```
public double getMetallicFactor()
```


Gets the metalness of the material, value of 1 means the material is a metal and value of 0 means the material is a dielectric.

**Returns:**
double – metalligheten för materialet, ett värde på 1 betyder att materialet är en metall och ett värde på 0 betyder att materialet är ett dielektrikum.
### getMetallicRoughness() {#getMetallicRoughness--}
```
public TextureBase getMetallicRoughness()
```


Gets the texture for metallic(in R channel) and roughness(in G channel)

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for metallic(in R channel) and roughness(in G channel)
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
### getOcclusionFactor() {#getOcclusionFactor--}
```
public double getOcclusionFactor()
```


Gets the factor of ambient occlusion

**Returns:**
double – faktorn för ambient occlusion
### getOcclusionTexture() {#getOcclusionTexture--}
```
public TextureBase getOcclusionTexture()
```


Gets the texture for ambient occlusion

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for ambient occlusion
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
### getRoughnessFactor() {#getRoughnessFactor--}
```
public double getRoughnessFactor()
```


Gets the roughness of the material, value of 1 means the material is completely rough and value of 0 means the material is completely smooth

**Returns:**
double – grovheten för materialet, ett värde på 1 betyder att materialet är helt grovt och ett värde på 0 betyder att materialet är helt slätt
### getSpecularTexture() {#getSpecularTexture--}
```
public TextureBase getSpecularTexture()
```


Gets the texture for specular color

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color
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
### setAlbedo(Vector3 value) {#setAlbedo-com.aspose.threed.Vector3-}
```
public void setAlbedo(Vector3 value)
```


Sets the base color of the material

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde |

### setAlbedoTexture(TextureBase value) {#setAlbedoTexture-com.aspose.threed.TextureBase-}
```
public void setAlbedoTexture(TextureBase value)
```


Ställer in texturen för albedo

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nytt värde |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Ställer in den emissiva färgen

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

### setMetallicFactor(double value) {#setMetallicFactor-double-}
```
public void setMetallicFactor(double value)
```


Ställer in metalligheten för materialet, ett värde på 1 betyder att materialet är en metall och ett värde på 0 betyder att materialet är ett dielektrikum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setMetallicRoughness(TextureBase value) {#setMetallicRoughness-com.aspose.threed.TextureBase-}
```
public void setMetallicRoughness(TextureBase value)
```


Ställer in texturen för metallisk (i R-kanalen) och grovhet (i G-kanalen)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nytt värde |

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

### setOcclusionFactor(double value) {#setOcclusionFactor-double-}
```
public void setOcclusionFactor(double value)
```


Ställer in faktorn för ambient occlusion

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setOcclusionTexture(TextureBase value) {#setOcclusionTexture-com.aspose.threed.TextureBase-}
```
public void setOcclusionTexture(TextureBase value)
```


Ställer in texturen för ambient occlusion

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

### setRoughnessFactor(double value) {#setRoughnessFactor-double-}
```
public void setRoughnessFactor(double value)
```


Ställer in grovheten för materialet, ett värde på 1 betyder att materialet är helt grovt och ett värde på 0 betyder att materialet är helt slätt

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setSpecularTexture(TextureBase value) {#setSpecularTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularTexture(TextureBase value)
```


Ställer in texturen för spekulär färg

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

