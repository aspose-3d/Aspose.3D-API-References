---
title: PbrSpecularMaterial
second_title: Aspose.3D for Java API-referentie
description: Materiaal voor fysiek gebaseerd renderen op basis van diffuse kleur/specular/glans
type: docs
weight: 122
url: /nl/java/com.aspose.threed/pbrspecularmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrSpecularMaterial extends Material
```

Materiaal voor fysiek gebaseerd renderen op basis van diffuse kleur/specular/glans
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PbrSpecularMaterial()](#PbrSpecularMaterial--) | Constructor van de [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial) |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | Gebruikt in [setTexture](../../com.aspose.threed/material\#setTexture) om een ambient textuurmapping toe te wijzen. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | Gebruikt in [setTexture](../../com.aspose.threed/material\#setTexture) om een diffuse textuurmapping toe te wijzen. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | Gebruikt in [setTexture](../../com.aspose.threed/material\#setTexture) om een emissieve textuurmapping toe te wijzen. |
| [MAP_NORMAL](#MAP-NORMAL) | Gebruikt in [setTexture](../../com.aspose.threed/material\#setTexture) om een normale textuurmapping toe te wijzen. |
| [MAP_SPECULAR](#MAP-SPECULAR) | Gebruikt in [setTexture](../../com.aspose.threed/material\#setTexture) om een speculaire textuurmapping toe te wijzen. |
| [MAP_SPECULAR_GLOSSINESS](#MAP-SPECULAR-GLOSSINESS) | De textuurkaart voor speculaire glans |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [getClass()](#getClass--) |  |
| [getDiffuse()](#getDiffuse--) | Haalt de diffuse kleur van het materiaal op, standaardwaarde is (1, 1, 1) |
| [getDiffuseTexture()](#getDiffuseTexture--) | Haalt de textuur voor diffuse op |
| [getEmissiveColor()](#getEmissiveColor--) | Haalt de emissieve kleur op, standaardwaarde is (0, 0, 0) |
| [getEmissiveTexture()](#getEmissiveTexture--) | Haalt de textuur voor emissief op |
| [getGlossinessFactor()](#getGlossinessFactor--) | Haalt de glans (gladheid) van het materiaal op, 1 betekent perfect glad en 0 betekent perfect ruw, standaardwaarde is 1, bereik is [0, 1] |
| [getName()](#getName--) | Haalt de naam op. |
| [getNormalTexture()](#getNormalTexture--) | Haalt de textuur van normale mapping op |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [getSpecular()](#getSpecular--) | Haalt de speculaire kleur van het materiaal op, standaardwaarde is (1, 1, 1). |
| [getSpecularGlossinessTexture()](#getSpecularGlossinessTexture--) | Haalt de textuur voor speculaire kleur op, kanaal RGB slaat de speculaire kleur op en kanaal A slaat de glans op. |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Haalt de textuur op uit de opgegeven slot; dit kan de naam van een materiaaleigenschap of de naam van een shaderparameter zijn. |
| [getTransparency()](#getTransparency--) | Haalt de transparantiefactor op. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Haalt de enumerator op om interne textuurslots te enumereren. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [setDiffuse(Vector3 value)](#setDiffuse-com.aspose.threed.Vector3-) | Stelt de diffuse kleur van het materiaal in, standaardwaarde is (1, 1, 1) |
| [setDiffuseTexture(TextureBase value)](#setDiffuseTexture-com.aspose.threed.TextureBase-) | Stelt de textuur voor diffuse in |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Stelt de emissieve kleur in, standaardwaarde is (0, 0, 0) |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | Stelt de textuur in voor emissief |
| [setGlossinessFactor(double value)](#setGlossinessFactor-double-) | Stelt de glans (gladheid) van het materiaal in, 1 betekent perfect glad en 0 betekent perfect ruw, standaardwaarde is 1, bereik is [0, 1] |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | Stelt de textuur van normale mapping in |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [setSpecular(Vector3 value)](#setSpecular-com.aspose.threed.Vector3-) | Stelt de speculaire kleur van het materiaal in, standaardwaarde is (1, 1, 1). |
| [setSpecularGlossinessTexture(TextureBase value)](#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-) | Stelt de textuur voor speculaire kleur in, kanaal RGB slaat de speculaire kleur op en kanaal A slaat de glans op. |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Stelt de textuur in op de opgegeven slot |
| [setTransparency(double value)](#setTransparency-double-) | Stelt de transparantiefactor in. |
| [toString()](#toString--) | Formatteert object naar string |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrSpecularMaterial() {#PbrSpecularMaterial--}
```
public PbrSpecularMaterial()
```


Constructor van de [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial)

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

### MAP_SPECULAR_GLOSSINESS {#MAP-SPECULAR-GLOSSINESS}
```
public static final String MAP_SPECULAR_GLOSSINESS
```


De textuurkaart voor speculaire glans

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


Haalt de diffuse kleur van het materiaal op, standaardwaarde is (1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color of the material, default value is (1, 1, 1)
### getDiffuseTexture() {#getDiffuseTexture--}
```
public TextureBase getDiffuseTexture()
```


Haalt de textuur voor diffuse op

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for diffuse
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Haalt de emissieve kleur op, standaardwaarde is (0, 0, 0)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color, default value is (0, 0, 0)
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


Haalt de textuur voor emissief op

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getGlossinessFactor() {#getGlossinessFactor--}
```
public double getGlossinessFactor()
```


Haalt de glans (gladheid) van het materiaal op, 1 betekent perfect glad en 0 betekent perfect ruw, standaardwaarde is 1, bereik is [0, 1]

**Returns:**
double - de glans (gladheid) van het materiaal, 1 betekent perfect glad en 0 betekent perfect ruw, standaardwaarde is 1, bereik is [0, 1]
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
### getSpecular() {#getSpecular--}
```
public Vector3 getSpecular()
```


Haalt de speculaire kleur van het materiaal op, standaardwaarde is (1, 1, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color of the material, default value is (1, 1, 1).
### getSpecularGlossinessTexture() {#getSpecularGlossinessTexture--}
```
public TextureBase getSpecularGlossinessTexture()
```


Haalt de textuur voor speculaire kleur op, kanaal RGB slaat de speculaire kleur op en kanaal A slaat de glans op.

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color, channel RGB stores the specular color and channel A stores the glossiness.
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
### setDiffuse(Vector3 value) {#setDiffuse-com.aspose.threed.Vector3-}
```
public void setDiffuse(Vector3 value)
```


Stelt de diffuse kleur van het materiaal in, standaardwaarde is (1, 1, 1)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setDiffuseTexture(TextureBase value) {#setDiffuseTexture-com.aspose.threed.TextureBase-}
```
public void setDiffuseTexture(TextureBase value)
```


Stelt de textuur voor diffuse in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nieuwe waarde |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Stelt de emissieve kleur in, standaardwaarde is (0, 0, 0)

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

### setGlossinessFactor(double value) {#setGlossinessFactor-double-}
```
public void setGlossinessFactor(double value)
```


Stelt de glans (gladheid) van het materiaal in, 1 betekent perfect glad en 0 betekent perfect ruw, standaardwaarde is 1, bereik is [0, 1]

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

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

### setSpecular(Vector3 value) {#setSpecular-com.aspose.threed.Vector3-}
```
public void setSpecular(Vector3 value)
```


Stelt de speculaire kleur van het materiaal in, standaardwaarde is (1, 1, 1).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setSpecularGlossinessTexture(TextureBase value) {#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularGlossinessTexture(TextureBase value)
```


Stelt de textuur voor speculaire kleur in, kanaal RGB slaat de speculaire kleur op en kanaal A slaat de glans op.

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

