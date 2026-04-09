---
title: MorphTargetDeformer
second_title: Aspose.3D for Java API Reference
description: MorphTargetDeformer fornisce animazione per vertice.
type: docs
weight: 108
url: /it/java/com.aspose.threed/morphtargetdeformer/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Deformer](../../com.aspose.threed/deformer)
```
public class MorphTargetDeformer extends Deformer
```

MorphTargetDeformer fornisce animazione per vertice. MorphTargetDeformer organizza tutti i target tramite [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel), ogni canale può organizzare più target. Un uso comune del deformatore di morph target è applicare espressioni facciali a un personaggio. Maggiori dettagli sono disponibili su https://en.wikipedia.org/wiki/Morph\\_target\\_animation
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MorphTargetDeformer(String name)](#MorphTargetDeformer-java.lang.String-) | Inizializza una nuova istanza della classe [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer). |
| [MorphTargetDeformer()](#MorphTargetDeformer--) | Inizializza una nuova istanza della classe [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | Ottiene il peso per la geometria fornita, questo è un modo abbreviato per modificare il peso del target senza accedere al canale. |
| [getChannels()](#getChannels--) | Ottiene tutti i canali contenuti in questo deformatore |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Ottiene il nome. |
| [getOwner()](#getOwner--) | Ottiene la geometria che possiede questo deformatore |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | Imposta il peso per la geometria fornita, questo è un modo abbreviato per modificare il peso del target senza accedere al canale. |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetDeformer(String name) {#MorphTargetDeformer-java.lang.String-}
```
public MorphTargetDeformer(String name)
```


Inizializza una nuova istanza della classe [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome. |

### MorphTargetDeformer() {#MorphTargetDeformer--}
```
public MorphTargetDeformer()
```


Inizializza una nuova istanza della classe [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer).

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
### get(Shape target) {#get-com.aspose.threed.Shape-}
```
public double get(Shape target)
```


Ottiene il peso per la geometria fornita, questo è un modo abbreviato per modificare il peso del target senza accedere al canale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Geometria di destinazione |

**Returns:**
double - Peso
### getChannels() {#getChannels--}
```
public List<MorphTargetChannel> getChannels()
```


Ottiene tutti i canali contenuti in questo deformatore

**Returns:**
java.util.List<com.aspose.threed.MorphTargetChannel> - tutti i canali contenuti in questo deformatore
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
### getOwner() {#getOwner--}
```
public Geometry getOwner()
```


Ottiene la geometria che possiede questo deformatore

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - the geometry which owns this deformer
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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
### set(Shape target, double value) {#set-com.aspose.threed.Shape-double-}
```
public void set(Shape target, double value)
```


Imposta il peso per la geometria fornita, questo è un modo abbreviato per modificare il peso del target senza accedere al canale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Geometria di destinazione |
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

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

