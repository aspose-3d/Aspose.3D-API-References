---
title: PbrMaterial
second_title: Aspose.3D for Java API Reference
description: Materiale per rendering fisicamente basato su colore albedo/metallo/ruvidità.
type: docs
weight: 121
url: /it/java/com.aspose.threed/pbrmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrMaterial extends Material
```

Materiale per rendering fisicamente basato su colore albedo/metallo/ruvidità.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PbrMaterial()](#PbrMaterial--) | Crea un'istanza predefinita del materiale PBR |
| [PbrMaterial(Vector3 albedo)](#PbrMaterial-com.aspose.threed.Vector3-) | Crea un materiale PBR predefinito con il valore di colore albedo specificato. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | Usato in [setTexture](../../com.aspose.threed/material\#setTexture) per assegnare una mappatura di texture ambientale. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | Usato in [setTexture](../../com.aspose.threed/material\#setTexture) per assegnare una mappatura di texture diffusa. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | Usato in [setTexture](../../com.aspose.threed/material\#setTexture) per assegnare una mappatura di texture emissiva. |
| [MAP_NORMAL](#MAP-NORMAL) | Usato in [setTexture](../../com.aspose.threed/material\#setTexture) per assegnare una mappatura di texture normale. |
| [MAP_SPECULAR](#MAP-SPECULAR) | Usato in [setTexture](../../com.aspose.threed/material\#setTexture) per assegnare una mappatura di texture speculare. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [fromMaterial(Material material)](#fromMaterial-com.aspose.threed.Material-) | Consenti di convertire altri materiali in **PbrMaterial** **Example:** |
| [getAlbedo()](#getAlbedo--) | Ottiene il colore base del materiale |
| [getAlbedoTexture()](#getAlbedoTexture--) | Ottiene la texture per l'albedo |
| [getClass()](#getClass--) |  |
| [getEmissiveColor()](#getEmissiveColor--) | Ottiene il colore emissivo |
| [getEmissiveTexture()](#getEmissiveTexture--) | Ottiene la texture per l'emissivo |
| [getMetallicFactor()](#getMetallicFactor--) | Ottiene la metallicità del materiale, un valore di 1 indica che il materiale è un metallo e un valore di 0 indica che il materiale è un dielettrico. |
| [getMetallicRoughness()](#getMetallicRoughness--) | Ottiene la texture per metallic (nel canale R) e roughness (nel canale G) |
| [getName()](#getName--) | Ottiene il nome. |
| [getNormalTexture()](#getNormalTexture--) | Ottiene la texture della mappatura normale |
| [getOcclusionFactor()](#getOcclusionFactor--) | Ottiene il fattore di occlusione ambientale |
| [getOcclusionTexture()](#getOcclusionTexture--) | Ottiene la texture per l'occlusione ambientale |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getRoughnessFactor()](#getRoughnessFactor--) | Ottiene la rugosità del materiale, un valore di 1 indica che il materiale è completamente ruvido e un valore di 0 indica che il materiale è completamente liscio |
| [getSpecularTexture()](#getSpecularTexture--) | Ottiene la texture per il colore speculare |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Ottiene la texture dallo slot specificato, può essere il nome della proprietà del materiale o il nome del parametro dello shader |
| [getTransparency()](#getTransparency--) | Ottiene il fattore di trasparenza. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Ottiene l'enumeratore per enumerare gli slot di texture interni. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [setAlbedo(Vector3 value)](#setAlbedo-com.aspose.threed.Vector3-) | Imposta il colore base del materiale |
| [setAlbedoTexture(TextureBase value)](#setAlbedoTexture-com.aspose.threed.TextureBase-) | Imposta la texture per l'albedo |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Imposta il colore emissivo |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | Imposta la texture per l'emissivo |
| [setMetallicFactor(double value)](#setMetallicFactor-double-) | Imposta la metallicità del materiale, un valore di 1 indica che il materiale è un metallo e un valore di 0 indica che il materiale è un dielettrico. |
| [setMetallicRoughness(TextureBase value)](#setMetallicRoughness-com.aspose.threed.TextureBase-) | Imposta la texture per metallic (nel canale R) e roughness (nel canale G) |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | Imposta la texture della normal mapping |
| [setOcclusionFactor(double value)](#setOcclusionFactor-double-) | Imposta il fattore di occlusione ambientale |
| [setOcclusionTexture(TextureBase value)](#setOcclusionTexture-com.aspose.threed.TextureBase-) | Imposta la texture per l'occlusione ambientale |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [setRoughnessFactor(double value)](#setRoughnessFactor-double-) | Imposta la rugosità del materiale, un valore di 1 indica che il materiale è completamente ruvido e un valore di 0 indica che il materiale è completamente liscio. |
| [setSpecularTexture(TextureBase value)](#setSpecularTexture-com.aspose.threed.TextureBase-) | Imposta la texture per il colore speculare |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Imposta la texture allo slot specificato |
| [setTransparency(double value)](#setTransparency-double-) | Imposta il fattore di trasparenza. |
| [toString()](#toString--) | Formatta l'oggetto in stringa |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrMaterial() {#PbrMaterial--}
```
public PbrMaterial()
```


Crea un'istanza predefinita del materiale PBR

### PbrMaterial(Vector3 albedo) {#PbrMaterial-com.aspose.threed.Vector3-}
```
public PbrMaterial(Vector3 albedo)
```


Crea un materiale PBR predefinito con il valore di colore albedo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| albedo | [Vector3](../../com.aspose.threed/vector3) | Il valore predefinito del colore albedo |

### MAP_AMBIENT {#MAP-AMBIENT}
```
public static final String MAP_AMBIENT
```


Usato in [setTexture](../../com.aspose.threed/material\#setTexture) per assegnare una mappatura di texture ambientale.

### MAP_DIFFUSE {#MAP-DIFFUSE}
```
public static final String MAP_DIFFUSE
```


Usato in [setTexture](../../com.aspose.threed/material\#setTexture) per assegnare una mappatura di texture diffusa.

### MAP_EMISSIVE {#MAP-EMISSIVE}
```
public static final String MAP_EMISSIVE
```


Usato in [setTexture](../../com.aspose.threed/material\#setTexture) per assegnare una mappatura di texture emissiva.

### MAP_NORMAL {#MAP-NORMAL}
```
public static final String MAP_NORMAL
```


Usato in [setTexture](../../com.aspose.threed/material\#setTexture) per assegnare una mappatura di texture normale.

### MAP_SPECULAR {#MAP-SPECULAR}
```
public static final String MAP_SPECULAR
```


Usato in [setTexture](../../com.aspose.threed/material\#setTexture) per assegnare una mappatura di texture speculare.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Trova la proprietà. Può essere una proprietà dinamica (creata con CreateDynamicProperty/SetProperty) o una proprietà nativa (identificata per nome).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propertyName | java.lang.String | Nome della proprietà. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromMaterial(Material material) {#fromMaterial-com.aspose.threed.Material-}
```
public static PbrMaterial fromMaterial(Material material)
```


Consenti di convertire altri materiali in **PbrMaterial** **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     mat.setDiffuseColor(new Vector3(0.3, 0.9, 0.4));
     PbrMaterial pbr = PbrMaterial.fromMaterial(mat);
```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| material | [Material](../../com.aspose.threed/material) |  |

**Returns:**
[PbrMaterial](../../com.aspose.threed/pbrmaterial)
### getAlbedo() {#getAlbedo--}
```
public Vector3 getAlbedo()
```


Ottiene il colore base del materiale

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the base color of the material
### getAlbedoTexture() {#getAlbedoTexture--}
```
public TextureBase getAlbedoTexture()
```


Ottiene la texture per l'albedo

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


Ottiene il colore emissivo

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


Ottiene la texture per l'emissivo

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getMetallicFactor() {#getMetallicFactor--}
```
public double getMetallicFactor()
```


Ottiene la metallicità del materiale, un valore di 1 indica che il materiale è un metallo e un valore di 0 indica che il materiale è un dielettrico.

**Returns:**
double - la metallicità del materiale, un valore di 1 indica che il materiale è un metallo e un valore di 0 indica che il materiale è un dielettrico.
### getMetallicRoughness() {#getMetallicRoughness--}
```
public TextureBase getMetallicRoughness()
```


Ottiene la texture per metallic (nel canale R) e roughness (nel canale G)

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for metallic(in R channel) and roughness(in G channel)
### getName() {#getName--}
```
public String getName()
```


Ottiene il nome.

**Returns:**
java.lang.String - il nome.
### getNormalTexture() {#getNormalTexture--}
```
public TextureBase getNormalTexture()
```


Ottiene la texture della mappatura normale

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture of normal mapping
### getOcclusionFactor() {#getOcclusionFactor--}
```
public double getOcclusionFactor()
```


Ottiene il fattore di occlusione ambientale

**Returns:**
double - il fattore di occlusione ambientale
### getOcclusionTexture() {#getOcclusionTexture--}
```
public TextureBase getOcclusionTexture()
```


Ottiene la texture per l'occlusione ambientale

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for ambient occlusion
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Ottiene la collezione di tutte le proprietà.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Ottieni il valore della proprietà specificata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | java.lang.String | Nome della proprietà |

**Returns:**
java.lang.Object - Il valore della proprietà trovata
### getRoughnessFactor() {#getRoughnessFactor--}
```
public double getRoughnessFactor()
```


Ottiene la rugosità del materiale, un valore di 1 indica che il materiale è completamente ruvido e un valore di 0 indica che il materiale è completamente liscio

**Returns:**
double - la rugosità del materiale, un valore di 1 indica che il materiale è completamente ruvido e un valore di 0 indica che il materiale è completamente liscio.
### getSpecularTexture() {#getSpecularTexture--}
```
public TextureBase getSpecularTexture()
```


Ottiene la texture per il colore speculare

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color
### getTexture(String slotName) {#getTexture-java.lang.String-}
```
public TextureBase getTexture(String slotName)
```


Ottiene la texture dallo slot specificato, può essere il nome della proprietà del materiale o il nome del parametro dello shader

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| slotName | java.lang.String | Nome slot. |

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


Ottiene il fattore di trasparenza. Il fattore deve essere compreso tra 0 (0 %, completamente opaco) e 1 (100 %, completamente trasparente). Qualsiasi valore di fattore non valido verrà limitato.

**Returns:**
double - il fattore di trasparenza. Il fattore deve essere compreso tra 0 (0 %, completamente opaco) e 1 (100 %, completamente trasparente). Qualsiasi valore di fattore non valido verrà limitato.
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


Ottiene l'enumeratore per enumerare gli slot di texture interni.

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


Rimuove una proprietà dinamica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Quale proprietà rimuovere |

**Returns:**
boolean - true se la proprietà è stata rimossa con successo
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Rimuove la proprietà specificata identificata per nome

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | java.lang.String | Quale proprietà rimuovere |

**Returns:**
boolean - true se la proprietà è stata rimossa con successo
### setAlbedo(Vector3 value) {#setAlbedo-com.aspose.threed.Vector3-}
```
public void setAlbedo(Vector3 value)
```


Imposta il colore base del materiale

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

### setAlbedoTexture(TextureBase value) {#setAlbedoTexture-com.aspose.threed.TextureBase-}
```
public void setAlbedoTexture(TextureBase value)
```


Imposta la texture per l'albedo

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nuovo valore |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Imposta il colore emissivo

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

### setEmissiveTexture(TextureBase value) {#setEmissiveTexture-com.aspose.threed.TextureBase-}
```
public void setEmissiveTexture(TextureBase value)
```


Imposta la texture per l'emissivo

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nuovo valore |

### setMetallicFactor(double value) {#setMetallicFactor-double-}
```
public void setMetallicFactor(double value)
```


Imposta la metallicità del materiale, un valore di 1 indica che il materiale è un metallo e un valore di 0 indica che il materiale è un dielettrico.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setMetallicRoughness(TextureBase value) {#setMetallicRoughness-com.aspose.threed.TextureBase-}
```
public void setMetallicRoughness(TextureBase value)
```


Imposta la texture per metallic (nel canale R) e roughness (nel canale G)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nuovo valore |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Imposta il nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setNormalTexture(TextureBase value) {#setNormalTexture-com.aspose.threed.TextureBase-}
```
public void setNormalTexture(TextureBase value)
```


Imposta la texture della normal mapping

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nuovo valore |

### setOcclusionFactor(double value) {#setOcclusionFactor-double-}
```
public void setOcclusionFactor(double value)
```


Imposta il fattore di occlusione ambientale

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setOcclusionTexture(TextureBase value) {#setOcclusionTexture-com.aspose.threed.TextureBase-}
```
public void setOcclusionTexture(TextureBase value)
```


Imposta la texture per l'occlusione ambientale

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nuovo valore |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Imposta il valore della proprietà specificata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | java.lang.String | Nome della proprietà |
| valore | java.lang.Object | Il valore della proprietà |

### setRoughnessFactor(double value) {#setRoughnessFactor-double-}
```
public void setRoughnessFactor(double value)
```


Imposta la rugosità del materiale, un valore di 1 indica che il materiale è completamente ruvido e un valore di 0 indica che il materiale è completamente liscio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setSpecularTexture(TextureBase value) {#setSpecularTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularTexture(TextureBase value)
```


Imposta la texture per il colore speculare

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nuovo valore |

### setTexture(String slotName, TextureBase texture) {#setTexture-java.lang.String-com.aspose.threed.TextureBase-}
```
public void setTexture(String slotName, TextureBase texture)
```


Imposta la texture allo slot specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| slotName | java.lang.String | Nome slot. |
|  | texture | [TextureBase](../../com.aspose.threed/texturebase) | Texture. **Esempio:** |

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


Imposta il fattore di trasparenza. Il fattore deve essere compreso tra 0 (0 %, completamente opaco) e 1 (100 %, completamente trasparente). Qualsiasi valore di fattore non valido verrà limitato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### toString() {#toString--}
```
public String toString()
```


Formatta l'oggetto in stringa

**Returns:**
java.lang.String - Stringa dell'oggetto
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

