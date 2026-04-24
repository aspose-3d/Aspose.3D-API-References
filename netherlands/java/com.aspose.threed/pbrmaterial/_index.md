---
title: PbrMaterial
second_title: Aspose.3D for Java API-referentie
description: Materiaal voor fysiek gebaseerd renderen op basis van albedo-kleur/metaal/ruwheid
type: docs
weight: 121
url: /nl/java/com.aspose.threed/pbrmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrMaterial extends Material
```

Materiaal voor fysiek gebaseerd renderen op basis van albedo-kleur/metaal/ruwheid
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PbrMaterial()](#PbrMaterial--) | Construeer een standaard PBR-materiaalinstantie |
| [PbrMaterial(Vector3 albedo)](#PbrMaterial-com.aspose.threed.Vector3-) | Construeer een standaard PBR-materiaal met een opgegeven albedo-kleurwaarde. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | Gebruikt in [setTexture](../../com.aspose.threed/material\#setTexture) om een ambient textuurmapping toe te wijzen. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | Gebruikt in [setTexture](../../com.aspose.threed/material\#setTexture) om een diffuse textuurmapping toe te wijzen. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | Gebruikt in [setTexture](../../com.aspose.threed/material\#setTexture) om een emissieve textuurmapping toe te wijzen. |
| [MAP_NORMAL](#MAP-NORMAL) | Gebruikt in [setTexture](../../com.aspose.threed/material\#setTexture) om een normale textuurmapping toe te wijzen. |
| [MAP_SPECULAR](#MAP-SPECULAR) | Gebruikt in [setTexture](../../com.aspose.threed/material\#setTexture) om een speculaire textuurmapping toe te wijzen. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [fromMaterial(Material material)](#fromMaterial-com.aspose.threed.Material-) | Sta toe om ander materiaal te converteren naar PbrMaterial **Voorbeeld:** |
| [getAlbedo()](#getAlbedo--) | Haalt de basiskleur van het materiaal op |
| [getAlbedoTexture()](#getAlbedoTexture--) | Haalt de textuur voor albedo op |
| [getClass()](#getClass--) |  |
| [getEmissiveColor()](#getEmissiveColor--) | Haalt de emissieve kleur op |
| [getEmissiveTexture()](#getEmissiveTexture--) | Haalt de textuur voor emissief op |
| [getMetallicFactor()](#getMetallicFactor--) | Haalt de metalness van het materiaal op, waarde van 1 betekent dat het materiaal een metaal is en waarde van 0 betekent dat het materiaal een diëlectrisch materiaal is. |
| [getMetallicRoughness()](#getMetallicRoughness--) | Haalt de textuur voor metallic (in R-kanaal) en roughness (in G-kanaal) op |
| [getName()](#getName--) | Haalt de naam op. |
| [getNormalTexture()](#getNormalTexture--) | Haalt de textuur van normale mapping op |
| [getOcclusionFactor()](#getOcclusionFactor--) | Haalt de factor van ambient occlusion op |
| [getOcclusionTexture()](#getOcclusionTexture--) | Haalt de textuur voor ambient occlusion op |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [getRoughnessFactor()](#getRoughnessFactor--) | Haalt de roughness van het materiaal op, een waarde van 1 betekent dat het materiaal volledig ruw is en een waarde van 0 betekent dat het materiaal volledig glad is |
| [getSpecularTexture()](#getSpecularTexture--) | Haalt de textuur voor specular color op |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Haalt de textuur op uit de opgegeven slot; dit kan de naam van een materiaaleigenschap of de naam van een shaderparameter zijn. |
| [getTransparency()](#getTransparency--) | Haalt de transparantiefactor op. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Haalt de enumerator op om interne textuurslots te enumereren. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [setAlbedo(Vector3 value)](#setAlbedo-com.aspose.threed.Vector3-) | Stelt de basiskleur van het materiaal in |
| [setAlbedoTexture(TextureBase value)](#setAlbedoTexture-com.aspose.threed.TextureBase-) | Stelt de textuur voor albedo in |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Stelt de emissieve kleur in |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | Stelt de textuur in voor emissief |
| [setMetallicFactor(double value)](#setMetallicFactor-double-) | Stelt de metaalheid van het materiaal in, een waarde van 1 betekent dat het materiaal een metaal is en een waarde van 0 betekent dat het materiaal een diëlektrisch is. |
| [setMetallicRoughness(TextureBase value)](#setMetallicRoughness-com.aspose.threed.TextureBase-) | Stelt de textuur in voor metallic (in R-kanaal) en roughness (in G-kanaal) |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | Stelt de textuur van normale mapping in |
| [setOcclusionFactor(double value)](#setOcclusionFactor-double-) | Stelt de factor van ambient occlusion in |
| [setOcclusionTexture(TextureBase value)](#setOcclusionTexture-com.aspose.threed.TextureBase-) | Stelt de textuur in voor ambient occlusion |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [setRoughnessFactor(double value)](#setRoughnessFactor-double-) | Stelt de ruwheid van het materiaal in, een waarde van 1 betekent dat het materiaal volledig ruw is en een waarde van 0 betekent dat het materiaal volledig glad is. |
| [setSpecularTexture(TextureBase value)](#setSpecularTexture-com.aspose.threed.TextureBase-) | Stelt de textuur in voor speculaire kleur |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Stelt de textuur in op de opgegeven slot |
| [setTransparency(double value)](#setTransparency-double-) | Stelt de transparantiefactor in. |
| [toString()](#toString--) | Formatteert object naar string |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrMaterial() {#PbrMaterial--}
```
public PbrMaterial()
```


Construeer een standaard PBR-materiaalinstantie

### PbrMaterial(Vector3 albedo) {#PbrMaterial-com.aspose.threed.Vector3-}
```
public PbrMaterial(Vector3 albedo)
```


Construeer een standaard PBR-materiaal met een opgegeven albedo-kleurwaarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| albedo | [Vector3](../../com.aspose.threed/vector3) | De standaard albedo-kleurwaarde |

### MAP_AMBIENT {#MAP-AMBIENT}
```
public static final String MAP_AMBIENT
```


Gebruikt in [setTexture](../../com.aspose.threed/material\#setTexture) om een ambient textuurmapping toe te wijzen.

### MAP_DIFFUSE {#MAP-DIFFUSE}
```
public static final String MAP_DIFFUSE
```


Gebruikt in [setTexture](../../com.aspose.threed/material\#setTexture) om een diffuse textuurmapping toe te wijzen.

### MAP_EMISSIVE {#MAP-EMISSIVE}
```
public static final String MAP_EMISSIVE
```


Gebruikt in [setTexture](../../com.aspose.threed/material\#setTexture) om een emissieve textuurmapping toe te wijzen.

### MAP_NORMAL {#MAP-NORMAL}
```
public static final String MAP_NORMAL
```


Gebruikt in [setTexture](../../com.aspose.threed/material\#setTexture) om een normale textuurmapping toe te wijzen.

### MAP_SPECULAR {#MAP-SPECULAR}
```
public static final String MAP_SPECULAR
```


Gebruikt in [setTexture](../../com.aspose.threed/material\#setTexture) om een speculaire textuurmapping toe te wijzen.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Zoekt de eigenschap. Het kan een dynamische eigenschap zijn (gemaakt door CreateDynamicProperty/SetProperty) of een native eigenschap (geïdentificeerd op naam).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propertyName | java.lang.String | Eigenschapnaam. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromMaterial(Material material) {#fromMaterial-com.aspose.threed.Material-}
```
public static PbrMaterial fromMaterial(Material material)
```


Sta toe om ander materiaal te converteren naar PbrMaterial **Voorbeeld:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     mat.setDiffuseColor(new Vector3(0.3, 0.9, 0.4));
     PbrMaterial pbr = PbrMaterial.fromMaterial(mat);
```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| material | [Material](../../com.aspose.threed/material) |  |

**Returns:**
[PbrMaterial](../../com.aspose.threed/pbrmaterial)
### getAlbedo() {#getAlbedo--}
```
public Vector3 getAlbedo()
```


Haalt de basiskleur van het materiaal op

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the base color of the material
### getAlbedoTexture() {#getAlbedoTexture--}
```
public TextureBase getAlbedoTexture()
```


Haalt de textuur voor albedo op

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


Haalt de emissieve kleur op

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


Haalt de textuur voor emissief op

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getMetallicFactor() {#getMetallicFactor--}
```
public double getMetallicFactor()
```


Haalt de metalness van het materiaal op, waarde van 1 betekent dat het materiaal een metaal is en waarde van 0 betekent dat het materiaal een diëlectrisch materiaal is.

**Returns:**
double - de metaalheid van het materiaal, een waarde van 1 betekent dat het materiaal een metaal is en een waarde van 0 betekent dat het materiaal een diëlektrisch is.
### getMetallicRoughness() {#getMetallicRoughness--}
```
public TextureBase getMetallicRoughness()
```


Haalt de textuur voor metallic (in R-kanaal) en roughness (in G-kanaal) op

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for metallic(in R channel) and roughness(in G channel)
### getName() {#getName--}
```
public String getName()
```


Haalt de naam op.

**Returns:**
java.lang.String - de naam.
### getNormalTexture() {#getNormalTexture--}
```
public TextureBase getNormalTexture()
```


Haalt de textuur van normale mapping op

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture of normal mapping
### getOcclusionFactor() {#getOcclusionFactor--}
```
public double getOcclusionFactor()
```


Haalt de factor van ambient occlusion op

**Returns:**
double - de factor van ambient occlusion
### getOcclusionTexture() {#getOcclusionTexture--}
```
public TextureBase getOcclusionTexture()
```


Haalt de textuur voor ambient occlusion op

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for ambient occlusion
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Haalt de verzameling van alle eigenschappen op.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Haalt de waarde op van de opgegeven eigenschap

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Naam van eigenschap |

**Returns:**
java.lang.Object - De waarde van de gevonden eigenschap
### getRoughnessFactor() {#getRoughnessFactor--}
```
public double getRoughnessFactor()
```


Haalt de roughness van het materiaal op, een waarde van 1 betekent dat het materiaal volledig ruw is en een waarde van 0 betekent dat het materiaal volledig glad is

**Returns:**
double - de ruwheid van het materiaal, een waarde van 1 betekent dat het materiaal volledig ruw is en een waarde van 0 betekent dat het materiaal volledig glad is.
### getSpecularTexture() {#getSpecularTexture--}
```
public TextureBase getSpecularTexture()
```


Haalt de textuur voor specular color op

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color
### getTexture(String slotName) {#getTexture-java.lang.String-}
```
public TextureBase getTexture(String slotName)
```


Haalt de textuur op uit de opgegeven slot; dit kan de naam van een materiaaleigenschap of de naam van een shaderparameter zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| slotName | java.lang.String | Slotnaam. |

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


Haalt de transparantiefactor op. De factor moet liggen tussen 0 (0%, volledig ondoorzichtig) en 1 (100%, volledig transparant). Elke ongeldige factorwaarde wordt begrensd.

**Returns:**
double - de transparantiefactor. De factor moet liggen tussen 0 (0%, volledig ondoorzichtig) en 1 (100%, volledig transparant). Elke ongeldige factorwaarde wordt begrensd.
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


Haalt de enumerator op om interne textuurslots te enumereren.

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


Verwijdert een dynamische eigenschap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Welke eigenschap moet worden verwijderd |

**Returns:**
boolean - true als de eigenschap succesvol is verwijderd
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Verwijder de opgegeven eigenschap geïdentificeerd op naam

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Welke eigenschap moet worden verwijderd |

**Returns:**
boolean - true als de eigenschap succesvol is verwijderd
### setAlbedo(Vector3 value) {#setAlbedo-com.aspose.threed.Vector3-}
```
public void setAlbedo(Vector3 value)
```


Stelt de basiskleur van het materiaal in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setAlbedoTexture(TextureBase value) {#setAlbedoTexture-com.aspose.threed.TextureBase-}
```
public void setAlbedoTexture(TextureBase value)
```


Stelt de textuur voor albedo in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nieuwe waarde |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Stelt de emissieve kleur in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setEmissiveTexture(TextureBase value) {#setEmissiveTexture-com.aspose.threed.TextureBase-}
```
public void setEmissiveTexture(TextureBase value)
```


Stelt de textuur in voor emissief

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nieuwe waarde |

### setMetallicFactor(double value) {#setMetallicFactor-double-}
```
public void setMetallicFactor(double value)
```


Stelt de metaalheid van het materiaal in, een waarde van 1 betekent dat het materiaal een metaal is en een waarde van 0 betekent dat het materiaal een diëlektrisch is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setMetallicRoughness(TextureBase value) {#setMetallicRoughness-com.aspose.threed.TextureBase-}
```
public void setMetallicRoughness(TextureBase value)
```


Stelt de textuur in voor metallic (in R-kanaal) en roughness (in G-kanaal)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nieuwe waarde |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Stelt de naam in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setNormalTexture(TextureBase value) {#setNormalTexture-com.aspose.threed.TextureBase-}
```
public void setNormalTexture(TextureBase value)
```


Stelt de textuur van normale mapping in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nieuwe waarde |

### setOcclusionFactor(double value) {#setOcclusionFactor-double-}
```
public void setOcclusionFactor(double value)
```


Stelt de factor van ambient occlusion in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setOcclusionTexture(TextureBase value) {#setOcclusionTexture-com.aspose.threed.TextureBase-}
```
public void setOcclusionTexture(TextureBase value)
```


Stelt de textuur in voor ambient occlusion

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nieuwe waarde |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Stelt de waarde in van de opgegeven eigenschap

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Naam van eigenschap |
| waarde | java.lang.Object | De waarde van de eigenschap |

### setRoughnessFactor(double value) {#setRoughnessFactor-double-}
```
public void setRoughnessFactor(double value)
```


Stelt de ruwheid van het materiaal in, een waarde van 1 betekent dat het materiaal volledig ruw is en een waarde van 0 betekent dat het materiaal volledig glad is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setSpecularTexture(TextureBase value) {#setSpecularTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularTexture(TextureBase value)
```


Stelt de textuur in voor speculaire kleur

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nieuwe waarde |

### setTexture(String slotName, TextureBase texture) {#setTexture-java.lang.String-com.aspose.threed.TextureBase-}
```
public void setTexture(String slotName, TextureBase texture)
```


Stelt de textuur in op de opgegeven slot

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| slotName | java.lang.String | Slotnaam. |
|  | texture | [TextureBase](../../com.aspose.threed/texturebase) | Textuur. **Example:** |

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


Stelt de transparantiefactor in. De factor moet liggen tussen 0 (0%, volledig ondoorzichtig) en 1 (100%, volledig transparant). Elke ongeldige factorwaarde wordt begrensd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### toString() {#toString--}
```
public String toString()
```


Formatteert object naar string

**Returns:**
java.lang.String - Objecttekenreeks
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

