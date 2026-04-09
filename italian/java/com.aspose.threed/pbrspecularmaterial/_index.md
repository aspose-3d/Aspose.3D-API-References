---
title: VertexElementWeight
second_title: Aspose.3D for Java API Reference
description: Materiale per rendering fisicamente basato su colore diffuso/speculare/brillantezza.
type: docs
weight: 122
url: /it/java/com.aspose.threed/pbrspecularmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrSpecularMaterial extends Material
```

Materiale per rendering fisicamente basato su colore diffuso/speculare/brillantezza.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PbrSpecularMaterial()](#PbrSpecularMaterial--) | Costruttore della [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial) |
## Campi

| Campo | Descrizione |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | Usato in [setTexture](../../com.aspose.threed/material\#setTexture) per assegnare una mappatura di texture ambientale. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | Usato in [setTexture](../../com.aspose.threed/material\#setTexture) per assegnare una mappatura di texture diffusa. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | Usato in [setTexture](../../com.aspose.threed/material\#setTexture) per assegnare una mappatura di texture emissiva. |
| [MAP_NORMAL](#MAP-NORMAL) | Usato in [setTexture](../../com.aspose.threed/material\#setTexture) per assegnare una mappatura di texture normale. |
| [MAP_SPECULAR](#MAP-SPECULAR) | Usato in [setTexture](../../com.aspose.threed/material\#setTexture) per assegnare una mappatura di texture speculare. |
| [MAP_SPECULAR_GLOSSINESS](#MAP-SPECULAR-GLOSSINESS) | La mappa di texture per la lucentezza speculare |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [getClass()](#getClass--) |  |
| [getDiffuse()](#getDiffuse--) | Ottiene il colore diffuso del materiale, il valore predefinito è (1, 1, 1) |
| [getDiffuseTexture()](#getDiffuseTexture--) | Ottiene la texture per il diffuso |
| [getEmissiveColor()](#getEmissiveColor--) | Ottiene il colore emissivo, il valore predefinito è (0, 0, 0) |
| [getEmissiveTexture()](#getEmissiveTexture--) | Ottiene la texture per l'emissivo |
| [getGlossinessFactor()](#getGlossinessFactor--) | Ottiene la lucentezza (liscità) del materiale, 1 indica perfettamente liscio e 0 indica perfettamente ruvido, il valore predefinito è 1, l'intervallo è [0, 1] |
| [getName()](#getName--) | Ottiene il nome. |
| [getNormalTexture()](#getNormalTexture--) | Ottiene la texture della mappatura normale |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getSpecular()](#getSpecular--) | Ottiene il colore speculare del materiale, il valore predefinito è (1, 1, 1). |
| [getSpecularGlossinessTexture()](#getSpecularGlossinessTexture--) | Ottiene la texture per il colore speculare, il canale RGB memorizza il colore speculare e il canale A memorizza la lucentezza. |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Ottiene la texture dallo slot specificato, può essere il nome della proprietà del materiale o il nome del parametro dello shader |
| [getTransparency()](#getTransparency--) | Ottiene il fattore di trasparenza. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Ottiene l'enumeratore per enumerare gli slot di texture interni. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [setDiffuse(Vector3 value)](#setDiffuse-com.aspose.threed.Vector3-) | Imposta il colore diffuso del materiale, il valore predefinito è (1, 1, 1) |
| [setDiffuseTexture(TextureBase value)](#setDiffuseTexture-com.aspose.threed.TextureBase-) | Imposta la texture per il diffuso |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Imposta il colore emissivo, il valore predefinito è (0, 0, 0) |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | Imposta la texture per l'emissivo |
| [setGlossinessFactor(double value)](#setGlossinessFactor-double-) | Imposta la lucentezza (levigatezza) del materiale, 1 significa perfettamente liscio e 0 significa perfettamente ruvido, il valore predefinito è 1, l'intervallo è [0, 1] |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | Imposta la texture della normal mapping |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [setSpecular(Vector3 value)](#setSpecular-com.aspose.threed.Vector3-) | Imposta il colore speculare del materiale, il valore predefinito è (1, 1, 1). |
| [setSpecularGlossinessTexture(TextureBase value)](#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-) | Imposta la texture per il colore speculare, il canale RGB memorizza il colore speculare e il canale A memorizza la lucentezza. |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Imposta la texture allo slot specificato |
| [setTransparency(double value)](#setTransparency-double-) | Imposta il fattore di trasparenza. |
| [toString()](#toString--) | Formatta l'oggetto in stringa |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrSpecularMaterial() {#PbrSpecularMaterial--}
```
public PbrSpecularMaterial()
```


Costruttore della [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial)

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

### MAP_SPECULAR_GLOSSINESS {#MAP-SPECULAR-GLOSSINESS}
```
public static final String MAP_SPECULAR_GLOSSINESS
```


La mappa di texture per la lucentezza speculare

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


Ottiene il colore diffuso del materiale, il valore predefinito è (1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color of the material, default value is (1, 1, 1)
### getDiffuseTexture() {#getDiffuseTexture--}
```
public TextureBase getDiffuseTexture()
```


Ottiene la texture per il diffuso

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for diffuse
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Ottiene il colore emissivo, il valore predefinito è (0, 0, 0)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color, default value is (0, 0, 0)
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


Ottiene la texture per l'emissivo

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getGlossinessFactor() {#getGlossinessFactor--}
```
public double getGlossinessFactor()
```


Ottiene la lucentezza (liscità) del materiale, 1 indica perfettamente liscio e 0 indica perfettamente ruvido, il valore predefinito è 1, l'intervallo è [0, 1]

**Returns:**
double - la lucentezza (levigatezza) del materiale, 1 significa perfettamente liscio e 0 significa perfettamente ruvido, il valore predefinito è 1, l'intervallo è [0, 1]
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
### getSpecular() {#getSpecular--}
```
public Vector3 getSpecular()
```


Ottiene il colore speculare del materiale, il valore predefinito è (1, 1, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color of the material, default value is (1, 1, 1).
### getSpecularGlossinessTexture() {#getSpecularGlossinessTexture--}
```
public TextureBase getSpecularGlossinessTexture()
```


Ottiene la texture per il colore speculare, il canale RGB memorizza il colore speculare e il canale A memorizza la lucentezza.

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color, channel RGB stores the specular color and channel A stores the glossiness.
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
### setDiffuse(Vector3 value) {#setDiffuse-com.aspose.threed.Vector3-}
```
public void setDiffuse(Vector3 value)
```


Imposta il colore diffuso del materiale, il valore predefinito è (1, 1, 1)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

### setDiffuseTexture(TextureBase value) {#setDiffuseTexture-com.aspose.threed.TextureBase-}
```
public void setDiffuseTexture(TextureBase value)
```


Imposta la texture per il diffuso

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Nuovo valore |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Imposta il colore emissivo, il valore predefinito è (0, 0, 0)

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

### setGlossinessFactor(double value) {#setGlossinessFactor-double-}
```
public void setGlossinessFactor(double value)
```


Imposta la lucentezza (levigatezza) del materiale, 1 significa perfettamente liscio e 0 significa perfettamente ruvido, il valore predefinito è 1, l'intervallo è [0, 1]

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

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

### setSpecular(Vector3 value) {#setSpecular-com.aspose.threed.Vector3-}
```
public void setSpecular(Vector3 value)
```


Imposta il colore speculare del materiale, il valore predefinito è (1, 1, 1).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

### setSpecularGlossinessTexture(TextureBase value) {#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularGlossinessTexture(TextureBase value)
```


Imposta la texture per il colore speculare, il canale RGB memorizza il colore speculare e il canale A memorizza la lucentezza.

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

