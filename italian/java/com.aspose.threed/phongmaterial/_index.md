---
title: PhongMaterial
second_title: Aspose.3D for Java API Reference
description: Materiale per il modello di shading Blinn-Phong.
type: docs
weight: 126
url: /it/java/com.aspose.threed/phongmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material), [com.aspose.threed.LambertMaterial](../../com.aspose.threed/lambertmaterial)
```
public class PhongMaterial extends LambertMaterial
```

Materiale per il modello di shading Blinn-Phong.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PhongMaterial()](#PhongMaterial--) | Inizializza una nuova istanza della classe [PhongMaterial](../../com.aspose.threed/phongmaterial). |
| [PhongMaterial(String name)](#PhongMaterial-java.lang.String-) | Inizializza una nuova istanza della classe [PhongMaterial](../../com.aspose.threed/phongmaterial). |
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
| [getAmbientColor()](#getAmbientColor--) | Ottiene il colore ambientale |
| [getClass()](#getClass--) |  |
| [getDiffuseColor()](#getDiffuseColor--) | Ottiene il colore diffuso |
| [getEmissiveColor()](#getEmissiveColor--) | Ottiene il colore emissivo |
| [getName()](#getName--) | Ottiene il nome. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getReflectionColor()](#getReflectionColor--) | Ottiene il colore di riflessione. |
| [getReflectionFactor()](#getReflectionFactor--) | Ottiene l'attenuazione del colore di riflessione. |
| [getShininess()](#getShininess--) | Ottiene la lucentezza, controlla la dimensione dell'evidenziazione speculare. |
| [getSpecularColor()](#getSpecularColor--) | Ottiene il colore speculare. |
| [getSpecularFactor()](#getSpecularFactor--) | Ottiene il fattore speculare. |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Ottiene la texture dallo slot specificato, può essere il nome della proprietà del materiale o il nome del parametro dello shader |
| [getTransparency()](#getTransparency--) | Ottiene il fattore di trasparenza. |
| [getTransparentColor()](#getTransparentColor--) | Ottiene il colore trasparente. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Ottiene l'enumeratore per enumerare gli slot di texture interni. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [setAmbientColor(Vector3 value)](#setAmbientColor-com.aspose.threed.Vector3-) | Imposta il colore ambientale |
| [setDiffuseColor(Vector3 value)](#setDiffuseColor-com.aspose.threed.Vector3-) | Imposta il colore diffuso |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Imposta il colore emissivo |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [setReflectionColor(Vector3 value)](#setReflectionColor-com.aspose.threed.Vector3-) | Imposta il colore di riflessione. |
| [setReflectionFactor(double value)](#setReflectionFactor-double-) | Imposta l'attenuazione del colore di riflessione. |
| [setShininess(double value)](#setShininess-double-) | Imposta la lucentezza, controlla la dimensione dell'evidenziazione speculare. |
| [setSpecularColor(Vector3 value)](#setSpecularColor-com.aspose.threed.Vector3-) | Imposta il colore speculare. |
| [setSpecularFactor(double value)](#setSpecularFactor-double-) | Imposta il fattore speculare. |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Imposta la texture allo slot specificato |
| [setTransparency(double value)](#setTransparency-double-) | Imposta il fattore di trasparenza. |
| [setTransparentColor(Vector3 value)](#setTransparentColor-com.aspose.threed.Vector3-) | Imposta il colore trasparente. |
| [toString()](#toString--) | Formatta l'oggetto in stringa |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhongMaterial() {#PhongMaterial--}
```
public PhongMaterial()
```


Inizializza una nuova istanza della classe [PhongMaterial](../../com.aspose.threed/phongmaterial).

### PhongMaterial(String name) {#PhongMaterial-java.lang.String-}
```
public PhongMaterial(String name)
```


Inizializza una nuova istanza della classe [PhongMaterial](../../com.aspose.threed/phongmaterial).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome |

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
### getAmbientColor() {#getAmbientColor--}
```
public Vector3 getAmbientColor()
```


Ottiene il colore ambientale

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


Ottiene il colore diffuso

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Ottiene il colore emissivo

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


Ottiene il nome.

**Returns:**
java.lang.String - il nome.
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
### getReflectionColor() {#getReflectionColor--}
```
public Vector3 getReflectionColor()
```


Ottiene il colore di riflessione.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the reflection color.
### getReflectionFactor() {#getReflectionFactor--}
```
public double getReflectionFactor()
```


Ottiene l'attenuazione del colore di riflessione.

**Returns:**
double - l'attenuazione del colore di riflessione.
### getShininess() {#getShininess--}
```
public double getShininess()
```


Ottiene la lucentezza, controlla la dimensione dell'evidenziazione speculare. La formula dello speculare: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Returns:**
double - la lucentezza, controlla la dimensione dell'evidenziazione speculare. La formula dello speculare: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess
### getSpecularColor() {#getSpecularColor--}
```
public Vector3 getSpecularColor()
```


Ottiene il colore speculare.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color.
### getSpecularFactor() {#getSpecularFactor--}
```
public double getSpecularFactor()
```


Ottiene il fattore speculare. La formula dello speculare: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Returns:**
double - il fattore speculare. La formula dello speculare: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess
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
### getTransparentColor() {#getTransparentColor--}
```
public Vector3 getTransparentColor()
```


Ottiene il colore trasparente.

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
### setAmbientColor(Vector3 value) {#setAmbientColor-com.aspose.threed.Vector3-}
```
public void setAmbientColor(Vector3 value)
```


Imposta il colore ambientale

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

### setDiffuseColor(Vector3 value) {#setDiffuseColor-com.aspose.threed.Vector3-}
```
public void setDiffuseColor(Vector3 value)
```


Imposta il colore diffuso

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Imposta il colore emissivo

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore **Esempio:** |

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Imposta il nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

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

### setReflectionColor(Vector3 value) {#setReflectionColor-com.aspose.threed.Vector3-}
```
public void setReflectionColor(Vector3 value)
```


Imposta il colore di riflessione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

### setReflectionFactor(double value) {#setReflectionFactor-double-}
```
public void setReflectionFactor(double value)
```


Imposta l'attenuazione del colore di riflessione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setShininess(double value) {#setShininess-double-}
```
public void setShininess(double value)
```


Imposta la lucentezza, controlla la dimensione dell'evidenziazione speculare. La formula dello speculare: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setSpecularColor(Vector3 value) {#setSpecularColor-com.aspose.threed.Vector3-}
```
public void setSpecularColor(Vector3 value)
```


Imposta il colore speculare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

### setSpecularFactor(double value) {#setSpecularFactor-double-}
```
public void setSpecularFactor(double value)
```


Imposta il fattore speculare. La formula dello speculare: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

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

### setTransparentColor(Vector3 value) {#setTransparentColor-com.aspose.threed.Vector3-}
```
public void setTransparentColor(Vector3 value)
```


Imposta il colore trasparente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

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

