---
title: Material
second_title: Aspose.3D for Java API Reference
description: Il materiale definisce i parametri necessari per l'aspetto visivo della geometria.
type: docs
weight: 98
url: /it/java/com.aspose.threed/material/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)

**All Implemented Interfaces:**
java.lang.Iterable
```
public abstract class Material extends A3DObject implements Iterable<TextureSlot>
```

Material definisce i parametri necessari per l'aspetto visivo della geometria. Aspose.3D fornisce il modello di shading per [LambertMaterial](../../com.aspose.threed/lambertmaterial), [PhongMaterial](../../com.aspose.threed/phongmaterial) e [ShaderMaterial](../../com.aspose.threed/shadermaterial) **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     for(var slot : mat)
     {
         System.out.printf("Texture slot %s = %s", slot.getSlotName(), slot.getTexture());
     }
```
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
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Ottiene il nome. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Ottiene la texture dallo slot specificato, può essere il nome della proprietà del materiale o il nome del parametro dello shader |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Ottiene l'enumeratore per enumerare gli slot di texture interni. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Imposta la texture allo slot specificato |
| [toString()](#toString--) | Formatta l'oggetto in stringa |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

