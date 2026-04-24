---
title: BindPoint
second_title: Aspose.3D for Java API Reference
description: Un  è solitamente creato su una proprietà di un oggetto; alcuni tipi di proprietà contengono più campi componenti (come un campo Vector3) e genererà un canale per ogni campo componente e collega il campo a una o più istanze di sequenza di fotogrammi chiave attraverso i canali.
type: docs
weight: 19
url: /it/java/com.aspose.threed/bindpoint/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class BindPoint extends A3DObject
```

Un [BindPoint](../../com.aspose.threed/bindpoint) è solitamente creato su una proprietà di un oggetto; alcuni tipi di proprietà contengono più campi componenti (come un campo Vector3), [BindPoint](../../com.aspose.threed/bindpoint) genererà un canale per ogni campo componente e collega il campo a una o più istanze di sequenza di fotogrammi chiave attraverso i canali.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BindPoint(Scene scene, Property prop)](#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-) | Inizializza una nuova istanza della classe [BindPoint](../../com.aspose.threed/bindpoint). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addChannel(String name, Class<?> type, Object value)](#addChannel-java.lang.String-java.lang.Class----java.lang.Object-) | Aggiunge la proprietà di canale specificata. |
| [addChannel(String name, Object value)](#addChannel-java.lang.String-java.lang.Object-) | Aggiunge la proprietà di canale specificata. |
| [bindKeyframeSequence(String channelName, KeyframeSequence sequence)](#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-) | Associa la sequenza di fotogrammi chiave al canale specificato |
| [createKeyframeSequence(String name)](#createKeyframeSequence-java.lang.String-) | Crea una nuova curva e la collega al primo canale della mappatura della curva |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [get(String channelName)](#get-java.lang.String-) | Ottiene il canale per nome fornito |
| [getChannel(String channelName)](#getChannel-java.lang.String-) | Ottiene il canale per nome fornito |
| [getChannelsCount()](#getChannelsCount--) | Restituisce il numero totale di canali di proprietà definiti in questa mappatura della curva di animazione. |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(String channelName)](#getKeyframeSequence-java.lang.String-) | Ottiene la prima sequenza di fotogrammi chiave nel canale specificato |
| [getName()](#getName--) | Ottiene il nome. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty()](#getProperty--) | Ottiene la proprietà associata al CurveMapping |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [resetChannels()](#resetChannels--) | Svuota i canali di proprietà di questa mappatura della curva di animazione. |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setProperty(Property value)](#setProperty-com.aspose.threed.Property-) | Ottiene la proprietà associata al CurveMapping |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [toString()](#toString--) | Formatta l'oggetto in stringa |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BindPoint(Scene scene, Property prop) {#BindPoint-com.aspose.threed.Scene-com.aspose.threed.Property-}
```
public BindPoint(Scene scene, Property prop)
```


Inizializza una nuova istanza della classe [BindPoint](../../com.aspose.threed/bindpoint).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | La scena che contiene l'animazione. |
| prop | [Property](../../com.aspose.threed/property) | Proprietà. |

### addChannel(String name, Class<?> type, Object value) {#addChannel-java.lang.String-java.lang.Class----java.lang.Object-}
```
public boolean addChannel(String name, Class<?> type, Object value)
```


Aggiunge la proprietà di canale specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome. |
| type | java.lang.Class<?> | Tipo. |
| valore | java.lang.Object | Valore. |

**Returns:**
boolean - true, se il canale è stato aggiunto, false altrimenti.
### addChannel(String name, Object value) {#addChannel-java.lang.String-java.lang.Object-}
```
public boolean addChannel(String name, Object value)
```


Aggiunge la proprietà di canale specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome. |
| valore | java.lang.Object | Valore. |

**Returns:**
boolean - true, se il canale è stato aggiunto, false altrimenti.
### bindKeyframeSequence(String channelName, KeyframeSequence sequence) {#bindKeyframeSequence-java.lang.String-com.aspose.threed.KeyframeSequence-}
```
public void bindKeyframeSequence(String channelName, KeyframeSequence sequence)
```


Associa la sequenza di fotogrammi chiave al canale specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| channelName | java.lang.String | A quale canale sarà associata la sequenza di fotogrammi chiave |
| sequence | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | La sequenza di fotogrammi chiave da associare |

### createKeyframeSequence(String name) {#createKeyframeSequence-java.lang.String-}
```
public KeyframeSequence createKeyframeSequence(String name)
```


Crea una nuova curva e la collega al primo canale della mappatura della curva

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Il nome della nuova sequenza. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
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
### get(String channelName) {#get-java.lang.String-}
```
public AnimationChannel get(String channelName)
```


Ottiene il canale per nome fornito

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| channelName | java.lang.String | Nome del canale |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Animation channel
### getChannel(String channelName) {#getChannel-java.lang.String-}
```
public AnimationChannel getChannel(String channelName)
```


Ottiene il canale per nome fornito

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| channelName | java.lang.String | Il nome del canale da trovare |

**Returns:**
[AnimationChannel](../../com.aspose.threed/animationchannel) - Channel with the name
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Restituisce il numero totale di canali di proprietà definiti in questa mappatura della curva di animazione.

**Returns:**
int - Il conteggio dei canali.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(String channelName) {#getKeyframeSequence-java.lang.String-}
```
public KeyframeSequence getKeyframeSequence(String channelName)
```


Ottiene la prima sequenza di fotogrammi chiave nel canale specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| channelName | java.lang.String | Il nome del canale da trovare |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - First keyframe sequence with the channel name
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
### getProperty() {#getProperty--}
```
public Property getProperty()
```


Ottiene la proprietà associata al CurveMapping

**Returns:**
[Property](../../com.aspose.threed/property) - the property associated with the CurveMapping
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
### resetChannels() {#resetChannels--}
```
public void resetChannels()
```


Svuota i canali di proprietà di questa mappatura della curva di animazione.

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Imposta il nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setProperty(Property value) {#setProperty-com.aspose.threed.Property-}
```
public void setProperty(Property value)
```


Ottiene la proprietà associata al CurveMapping

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Property](../../com.aspose.threed/property) | Nuovo valore |

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

