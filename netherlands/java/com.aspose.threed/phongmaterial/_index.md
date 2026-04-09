---
title: PhongMaterial
second_title: Aspose.3D for Java API-referentie
description: Materiaal voor het Blinn-Phong-shademodel.
type: docs
weight: 126
url: /nl/java/com.aspose.threed/phongmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material), [com.aspose.threed.LambertMaterial](../../com.aspose.threed/lambertmaterial)
```
public class PhongMaterial extends LambertMaterial
```

Materiaal voor het Blinn-Phong-shademodel.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PhongMaterial()](#PhongMaterial--) | Initialiseert een nieuw exemplaar van de [PhongMaterial](../../com.aspose.threed/phongmaterial) klasse. |
| [PhongMaterial(String name)](#PhongMaterial-java.lang.String-) | Initialiseert een nieuw exemplaar van de [PhongMaterial](../../com.aspose.threed/phongmaterial) klasse. |
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
| [getAmbientColor()](#getAmbientColor--) | Haalt de ambientkleur op |
| [getClass()](#getClass--) |  |
| [getDiffuseColor()](#getDiffuseColor--) | Haalt de diffuse kleur op |
| [getEmissiveColor()](#getEmissiveColor--) | Haalt de emissieve kleur op |
| [getName()](#getName--) | Haalt de naam op. |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [getReflectionColor()](#getReflectionColor--) | Haalt de reflectiekleur op. |
| [getReflectionFactor()](#getReflectionFactor--) | Haalt de demping van de reflectiekleur op. |
| [getShininess()](#getShininess--) | Haalt de glans op, dit bepaalt de grootte van de speculaire highlight. |
| [getSpecularColor()](#getSpecularColor--) | Haalt de speculaire kleur op. |
| [getSpecularFactor()](#getSpecularFactor--) | Haalt de speculaire factor op. |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Haalt de textuur op uit de opgegeven slot; dit kan de naam van een materiaaleigenschap of de naam van een shaderparameter zijn. |
| [getTransparency()](#getTransparency--) | Haalt de transparantiefactor op. |
| [getTransparentColor()](#getTransparentColor--) | Haalt de transparante kleur op. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Haalt de enumerator op om interne textuurslots te enumereren. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [setAmbientColor(Vector3 value)](#setAmbientColor-com.aspose.threed.Vector3-) | Stelt de ambientkleur in |
| [setDiffuseColor(Vector3 value)](#setDiffuseColor-com.aspose.threed.Vector3-) | Stelt de diffuse kleur in |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Stelt de emissieve kleur in |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [setReflectionColor(Vector3 value)](#setReflectionColor-com.aspose.threed.Vector3-) | Stelt de reflectiekleur in. |
| [setReflectionFactor(double value)](#setReflectionFactor-double-) | Stelt de demping van de reflectiekleur in. |
| [setShininess(double value)](#setShininess-double-) | Stelt de glans in, dit bepaalt de grootte van de speculaire highlight. |
| [setSpecularColor(Vector3 value)](#setSpecularColor-com.aspose.threed.Vector3-) | Stelt de speculaire kleur in. |
| [setSpecularFactor(double value)](#setSpecularFactor-double-) | Stelt de speculaire factor in. |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Stelt de textuur in op de opgegeven slot |
| [setTransparency(double value)](#setTransparency-double-) | Stelt de transparantiefactor in. |
| [setTransparentColor(Vector3 value)](#setTransparentColor-com.aspose.threed.Vector3-) | Stelt de transparante kleur in |
| [toString()](#toString--) | Formatteert object naar string |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhongMaterial() {#PhongMaterial--}
```
public PhongMaterial()
```


Initialiseert een nieuw exemplaar van de [PhongMaterial](../../com.aspose.threed/phongmaterial) klasse.

### PhongMaterial(String name) {#PhongMaterial-java.lang.String-}
```
public PhongMaterial(String name)
```


Initialiseert een nieuw exemplaar van de [PhongMaterial](../../com.aspose.threed/phongmaterial) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam |

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
### getAmbientColor() {#getAmbientColor--}
```
public Vector3 getAmbientColor()
```


Haalt de ambientkleur op

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


Haalt de diffuse kleur op

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Haalt de emissieve kleur op

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


Haalt de naam op.

**Returns:**
java.lang.String - de naam.
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
### getReflectionColor() {#getReflectionColor--}
```
public Vector3 getReflectionColor()
```


Haalt de reflectiekleur op.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the reflection color.
### getReflectionFactor() {#getReflectionFactor--}
```
public double getReflectionFactor()
```


Haalt de demping van de reflectiekleur op.

**Returns:**
double - de demping van de reflectiekleur.
### getShininess() {#getShininess--}
```
public double getShininess()
```


Haalt de glans op, dit bepaalt de grootte van de speculaire highlight. De formule van specular: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Returns:**
double - de glans, dit bepaalt de grootte van de speculaire highlight. De formule van specular: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess
### getSpecularColor() {#getSpecularColor--}
```
public Vector3 getSpecularColor()
```


Haalt de speculaire kleur op.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color.
### getSpecularFactor() {#getSpecularFactor--}
```
public double getSpecularFactor()
```


Haalt de speculaire factor op. De formule van specular: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Returns:**
double - de speculaire factor. De formule van specular: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess
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
### getTransparentColor() {#getTransparentColor--}
```
public Vector3 getTransparentColor()
```


Haalt de transparante kleur op.

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
### setAmbientColor(Vector3 value) {#setAmbientColor-com.aspose.threed.Vector3-}
```
public void setAmbientColor(Vector3 value)
```


Stelt de ambientkleur in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setDiffuseColor(Vector3 value) {#setDiffuseColor-com.aspose.threed.Vector3-}
```
public void setDiffuseColor(Vector3 value)
```


Stelt de diffuse kleur in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Stelt de emissieve kleur in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde **Example:** |

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Stelt de naam in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

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

### setReflectionColor(Vector3 value) {#setReflectionColor-com.aspose.threed.Vector3-}
```
public void setReflectionColor(Vector3 value)
```


Stelt de reflectiekleur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setReflectionFactor(double value) {#setReflectionFactor-double-}
```
public void setReflectionFactor(double value)
```


Stelt de demping van de reflectiekleur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setShininess(double value) {#setShininess-double-}
```
public void setShininess(double value)
```


Stelt de glans in, dit bepaalt de grootte van de speculaire highlight. De formule van specular: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setSpecularColor(Vector3 value) {#setSpecularColor-com.aspose.threed.Vector3-}
```
public void setSpecularColor(Vector3 value)
```


Stelt de speculaire kleur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setSpecularFactor(double value) {#setSpecularFactor-double-}
```
public void setSpecularFactor(double value)
```


Stelt de speculaire factor in. De formule van specular: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

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

### setTransparentColor(Vector3 value) {#setTransparentColor-com.aspose.threed.Vector3-}
```
public void setTransparentColor(Vector3 value)
```


Stelt de transparante kleur in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

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

