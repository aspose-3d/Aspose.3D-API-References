---
title: AnimationChannel
second_title: Aspose.3D for Java API Reference
description: Un canale mappa il campo componente della proprietà a un insieme di sequenze di fotogrammi chiave
type: docs
weight: 13
url: /it/java/com.aspose.threed/animationchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.KeyframeSequence](../../com.aspose.threed/keyframesequence)
```
public class AnimationChannel extends KeyframeSequence
```

Un canale mappa il campo componente della proprietà a un insieme di sequenze di fotogrammi chiave.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(double time, float value)](#add-double-float-) | Crea un nuovo fotogramma chiave con valore specificato |
| [add(double time, float value, Interpolation interpolation)](#add-double-float-com.aspose.threed.Interpolation-) | Crea un nuovo fotogramma chiave con valore specificato |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [getBindPoint()](#getBindPoint--) | Ottiene il punto di associazione della proprietà che possiede questa curva |
| [getClass()](#getClass--) |  |
| [getComponentType()](#getComponentType--) | Ottiene il tipo del campo componente |
| [getDefaultValue()](#getDefaultValue--) | Ottiene il valore Default del canale. |
| [getKeyFrames()](#getKeyFrames--) | Ottiene i fotogrammi chiave di questa curva. |
| [getKeyframeSequence()](#getKeyframeSequence--) | Ottiene la sequenza di fotogrammi chiave associata a questo canale |
| [getName()](#getName--) | Ottiene il nome. |
| [getPostBehavior()](#getPostBehavior--) | Ottiene il post behavior che indica quale dovrebbe essere il valore campionato dopo l'ultimo fotogramma chiave. |
| [getPreBehavior()](#getPreBehavior--) | Ottiene il pre behavior che indica quale dovrebbe essere il valore campionato prima del primo fotogramma chiave. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Ottiene l'enumeratore per attraversare tutti i fotogrammi chiave. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [reset()](#reset--) | Rimuove tutti i fotogrammi chiave e reimposta i comportamenti post/pre. |
| [setDefaultValue(Object value)](#setDefaultValue-java.lang.Object-) | Imposta il valore Default del canale. |
| [setKeyframeSequence(KeyframeSequence value)](#setKeyframeSequence-com.aspose.threed.KeyframeSequence-) | Ottiene la sequenza di fotogrammi chiave associata a questo canale |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(double time, float value) {#add-double-float-}
```
public void add(double time, float value)
```


Crea un nuovo fotogramma chiave con valore specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tempo | double | Posizione temporale (misurata in secondi) |
| valore | float | Il valore a questa posizione temporale |

### add(double time, float value, Interpolation interpolation) {#add-double-float-com.aspose.threed.Interpolation-}
```
public void add(double time, float value, Interpolation interpolation)
```


Crea un nuovo fotogramma chiave con valore specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tempo | double | Posizione temporale (misurata in secondi) |
| valore | float | Il valore a questa posizione temporale |
| interpolation | [Interpolation](../../com.aspose.threed/interpolation) | Il tipo di interpolazione di questo fotogramma chiave |

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
### getBindPoint() {#getBindPoint--}
```
public BindPoint getBindPoint()
```


Ottiene il punto di associazione della proprietà che possiede questa curva

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - the property bind point which owns this curve
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComponentType() {#getComponentType--}
```
public Class<?> getComponentType()
```


Ottiene il tipo del campo componente

**Returns:**
java.lang.Class<?> - il tipo del campo componente
### getDefaultValue() {#getDefaultValue--}
```
public Object getDefaultValue()
```


Ottiene il valore Default del canale. Se un canale non ha sequenze di fotogrammi chiave collegate, il valore Default verrà utilizzato durante la valutazione dell'animazione. Uno scenario reale: l'animazione anima solo la coordinata x di un nodo, le coordinate y e z non vengono modificate, quindi il valore Default verrà utilizzato durante la valutazione completa della traduzione.

**Returns:**
java.lang.Object - il valore Default del canale. Se un canale non ha sequenze di fotogrammi chiave collegate, il valore Default verrà utilizzato durante la valutazione dell'animazione. Uno scenario reale: l'animazione anima solo la coordinata x di un nodo, le coordinate y e z non vengono modificate, quindi il valore Default verrà utilizzato durante la valutazione completa della traduzione.
### getKeyFrames() {#getKeyFrames--}
```
public List<KeyFrame> getKeyFrames()
```


Ottiene i fotogrammi chiave di questa curva.

**Returns:**
java.util.List<com.aspose.threed.KeyFrame> - i fotogrammi chiave di questa curva.
### getKeyframeSequence() {#getKeyframeSequence--}
```
public KeyframeSequence getKeyframeSequence()
```


Ottiene la sequenza di fotogrammi chiave associata a questo canale

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - associated keyframe sequence inside this channel
### getName() {#getName--}
```
public String getName()
```


Ottiene il nome.

**Returns:**
java.lang.String - il nome.
### getPostBehavior() {#getPostBehavior--}
```
public Extrapolation getPostBehavior()
```


Ottiene il post behavior che indica quale dovrebbe essere il valore campionato dopo l'ultimo fotogramma chiave.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the post behavior indicates what the sampled value should be after the last key frame.
### getPreBehavior() {#getPreBehavior--}
```
public Extrapolation getPreBehavior()
```


Ottiene il pre behavior che indica quale dovrebbe essere il valore campionato prima del primo fotogramma chiave.

**Returns:**
[Extrapolation](../../com.aspose.threed/extrapolation) - the pre behavior indicates what the sampled value should be before the first key.
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
### iterator() {#iterator--}
```
public Iterator<KeyFrame> iterator()
```


Ottiene l'enumeratore per attraversare tutti i fotogrammi chiave.

**Returns:**
java.util.Iterator<com.aspose.threed.KeyFrame>
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
### reset() {#reset--}
```
public void reset()
```


Rimuove tutti i fotogrammi chiave e reimposta i comportamenti post/pre.

### setDefaultValue(Object value) {#setDefaultValue-java.lang.Object-}
```
public void setDefaultValue(Object value)
```


Imposta il valore Default del canale. Se un canale non ha sequenze di fotogrammi chiave collegate, il valore Default verrà utilizzato durante la valutazione dell'animazione. Uno scenario reale: l'animazione anima solo la coordinata x di un nodo, le coordinate y e z non vengono modificate, quindi il valore Default verrà utilizzato durante la valutazione completa della traduzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object | Nuovo valore |

### setKeyframeSequence(KeyframeSequence value) {#setKeyframeSequence-com.aspose.threed.KeyframeSequence-}
```
public void setKeyframeSequence(KeyframeSequence value)
```


Ottiene la sequenza di fotogrammi chiave associata a questo canale

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | Nuovo valore |

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

