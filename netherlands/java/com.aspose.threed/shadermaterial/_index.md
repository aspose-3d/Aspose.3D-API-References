---
title: ShaderMaterial
second_title: Aspose.3D for Java API-referentie
description: Een shader-materiaal maakt het mogelijk het materiaal te beschrijven met een externe renderengine of shader-taal.
type: docs
weight: 164
url: /nl/java/com.aspose.threed/shadermaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class ShaderMaterial extends Material
```

Een shader‑materiaal maakt het mogelijk het materiaal te beschrijven met een externe renderengine of shader‑taal. [ShaderMaterial](../../com.aspose.threed/shadermaterial) gebruikt [ShaderTechnique](../../com.aspose.threed/shadertechnique) om de concrete renderdetails te beschrijven, en de meest geschikte wordt gebruikt op basis van het uiteindelijke renderplatform. Bijvoorbeeld, uw [ShaderMaterial](../../com.aspose.threed/shadermaterial)‑instantie kan twee technieken hebben, één gedefinieerd door HLSL en een andere gedefinieerd door GLSL. Op niet‑window‑platforms moet de GLSL in plaats van de HLSL worden gebruikt.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ShaderMaterial()](#ShaderMaterial--) | Initialiseert een nieuwe instantie van de [ShaderMaterial](../../com.aspose.threed/shadermaterial) klasse. |
| [ShaderMaterial(String name)](#ShaderMaterial-java.lang.String-) | Initialiseert een nieuwe instantie van de [ShaderMaterial](../../com.aspose.threed/shadermaterial) klasse. |
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
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Haalt de naam op. |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [getTechniques()](#getTechniques--) | Haalt alle beschikbare technieken op die in dit materiaal zijn gedefinieerd. |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Haalt de textuur op uit de opgegeven slot; dit kan de naam van een materiaaleigenschap of de naam van een shaderparameter zijn. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Haalt de enumerator op om interne textuurslots te enumereren. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Stelt de textuur in op de opgegeven slot |
| [toString()](#toString--) | Formatteert object naar string |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderMaterial() {#ShaderMaterial--}
```
public ShaderMaterial()
```


Initialiseert een nieuwe instantie van de [ShaderMaterial](../../com.aspose.threed/shadermaterial) klasse.

### ShaderMaterial(String name) {#ShaderMaterial-java.lang.String-}
```
public ShaderMaterial(String name)
```


Initialiseert een nieuwe instantie van de [ShaderMaterial](../../com.aspose.threed/shadermaterial) klasse.

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
### getTechniques() {#getTechniques--}
```
public List<ShaderTechnique> getTechniques()
```


Haalt alle beschikbare technieken op die in dit materiaal zijn gedefinieerd.

**Returns:**
java.util.List<com.aspose.threed.ShaderTechnique> - alle beschikbare technieken die in dit materiaal zijn gedefinieerd.
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

