---
title: MorphTargetChannel
second_title: Aspose.3D for Java API Reference
description: Un MorphTargetChannel è usato da  per organizzare le geometrie target.
type: docs
weight: 107
url: /it/java/com.aspose.threed/morphtargetchannel/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class MorphTargetChannel extends A3DObject
```

Un MorphTargetChannel è usato da [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer) per organizzare le geometrie target. Alcuni formati di file come FBX supportano più canali in parallelo. **Remarks:** Il peso è compreso tra 0 e 1.0, e il peso predefinito per il target è 0.0;
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MorphTargetChannel(String name)](#MorphTargetChannel-java.lang.String-) | Inizializza una nuova istanza della classe [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel). |
| [MorphTargetChannel()](#MorphTargetChannel--) | Inizializza una nuova istanza della classe [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel). |
## Campi

| Campo | Descrizione |
| --- | --- |
| [DEFAULT_WEIGHT](#DEFAULT-WEIGHT) | Peso predefinito per il morph target. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | Restituisce il peso per la geometria specificata |
| [getChannelWeight()](#getChannelWeight--) | Restituisce il peso del deformatore di questo canale. |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Ottiene il nome. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getTargets()](#getTargets--) | Restituisce tutti i target associati al canale. |
| [getWeight(Shape target)](#getWeight-com.aspose.threed.Shape-) | Restituisce il peso per il target specificato; se il target non appartiene a questo canale, viene restituito il valore predefinito 0. |
| [getWeights()](#getWeights--) | Restituisce i valori completi di peso delle geometrie target. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | Imposta il peso per la geometria specificata. |
| [setChannelWeight(double value)](#setChannelWeight-double-) | Imposta il peso del deformatore di questo canale. |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [setWeight(Shape target)](#setWeight-com.aspose.threed.Shape-) | Imposta il peso per il target specificato, il valore predefinito è 1, l'intervallo deve essere tra 0 e 1. |
| [setWeight(Shape target, double weight)](#setWeight-com.aspose.threed.Shape-double-) | Imposta il peso per il target specificato, il valore predefinito è 1, l'intervallo deve essere tra 0 e 1. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetChannel(String name) {#MorphTargetChannel-java.lang.String-}
```
public MorphTargetChannel(String name)
```


Inizializza una nuova istanza della classe [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome. |

### MorphTargetChannel() {#MorphTargetChannel--}
```
public MorphTargetChannel()
```


Inizializza una nuova istanza della classe [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel).

### DEFAULT_WEIGHT {#DEFAULT-WEIGHT}
```
public static final double DEFAULT_WEIGHT
```


Peso predefinito per il morph target.

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


Restituisce il peso per la geometria specificata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Geometria target. |

**Returns:**
double - Peso
### getChannelWeight() {#getChannelWeight--}
```
public double getChannelWeight()
```


Restituisce il peso del deformatore di questo canale. Il peso è compreso tra 0,0 e 1,0.

**Returns:**
double - il peso del deformatore di questo canale. Il peso è compreso tra 0,0 e 1,0.
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
### getTargets() {#getTargets--}
```
public List<Shape> getTargets()
```


Restituisce tutti i target associati al canale.

**Returns:**
java.util.List<com.aspose.threed.Shape> - tutti i target associati al canale.
### getWeight(Shape target) {#getWeight-com.aspose.threed.Shape-}
```
public double getWeight(Shape target)
```


Restituisce il peso per il target specificato; se il target non appartiene a questo canale, viene restituito il valore predefinito 0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

**Returns:**
double
### getWeights() {#getWeights--}
```
public List<Double> getWeights()
```


Restituisce i valori completi di peso delle geometrie target.

**Returns:**
java.util.List<java.lang.Double> - i valori completi di peso delle geometrie target.
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


Imposta il peso per la geometria specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Geometria target. |
| valore | double | Nuovo valore |

### setChannelWeight(double value) {#setChannelWeight-double-}
```
public void setChannelWeight(double value)
```


Imposta il peso del deformatore di questo canale. Il peso è compreso tra 0,0 e 1,0.

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

### setWeight(Shape target) {#setWeight-com.aspose.threed.Shape-}
```
public void setWeight(Shape target)
```


Imposta il peso per il target specificato, il valore predefinito è 1, l'intervallo deve essere tra 0 e 1.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |

### setWeight(Shape target, double weight) {#setWeight-com.aspose.threed.Shape-double-}
```
public void setWeight(Shape target, double weight)
```


Imposta il peso per il target specificato, il valore predefinito è 1, l'intervallo deve essere tra 0 e 1.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) |  |
| peso | double |  |

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

