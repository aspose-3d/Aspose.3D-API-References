---
title: AnimationNode
second_title: Aspose.3D for Java API Reference
description: Aspose.3Ds supporta la gerarchia di animazione, ogni animazione può essere composta da diverse animazioni e dalla definizione dei fotogrammi chiave dell'animazione.
type: docs
weight: 15
url: /it/java/com.aspose.threed/animationnode/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AnimationNode extends A3DObject
```

Aspose.3D supporta la gerarchia di animazione, ogni animazione può essere composta da diverse animazioni e dalla definizione dei fotogrammi chiave dell'animazione. [AnimationNode](../../com.aspose.threed/animationnode) definisce la trasformazione di un valore di proprietà nel tempo, ad esempio, il nodo di animazione può essere usato per controllare la trasformazione di un nodo o le proprietà numeriche di altri oggetti [A3DObject](../../com.aspose.threed/a3dobject).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [AnimationNode(String name)](#AnimationNode-java.lang.String-) | Inizializza una nuova istanza della classe [AnimationNode](../../com.aspose.threed/animationnode). |
| [AnimationNode()](#AnimationNode--) | Inizializza una nuova istanza della classe [AnimationNode](../../com.aspose.threed/animationnode). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createBindPoint(A3DObject obj, String propName)](#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | Crea un BindPoint basato sul tipo di dati della proprietà. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findBindPoint(A3DObject target, String name)](#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-) | Trova il bind point per target e nome. |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [getBindPoint(A3DObject target, String propName, boolean create)](#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-) | Restituisce il bind point di animazione sulla proprietà specificata. |
| [getBindPoints()](#getBindPoints--) | Restituisce i bind point delle proprietà correnti. |
| [getClass()](#getClass--) |  |
| [getKeyframeSequence(A3DObject target, String propName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-) | Restituisce la sequenza di fotogrammi chiave sulla proprietà specificata. |
| [getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)](#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-) | Ottiene la sequenza di fotogrammi chiave sulla proprietà e sul canale specificati. |
| [getName()](#getName--) | Ottiene il nome. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getSubAnimations()](#getSubAnimations--) | Ottiene i nodi di sotto-animazione sotto le animazioni correnti |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationNode(String name) {#AnimationNode-java.lang.String-}
```
public AnimationNode(String name)
```


Inizializza una nuova istanza della classe [AnimationNode](../../com.aspose.threed/animationnode).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome |

### AnimationNode() {#AnimationNode--}
```
public AnimationNode()
```


Inizializza una nuova istanza della classe [AnimationNode](../../com.aspose.threed/animationnode).

### createBindPoint(A3DObject obj, String propName) {#createBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint createBindPoint(A3DObject obj, String propName)
```


Crea un BindPoint basato sul tipo di dati della proprietà.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [A3DObject](../../com.aspose.threed/a3dobject) | Oggetto. |
| propName | java.lang.String | Nome della proprietà. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point instance or null if the property is not defined.
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
### findBindPoint(A3DObject target, String name) {#findBindPoint-com.aspose.threed.A3DObject-java.lang.String-}
```
public BindPoint findBindPoint(A3DObject target, String name)
```


Trova il bind point per target e nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Obiettivo del punto di collegamento da trovare. |
| nome | java.lang.String | Nome del punto di collegamento da trovare. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
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
### getBindPoint(A3DObject target, String propName, boolean create) {#getBindPoint-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public BindPoint getBindPoint(A3DObject target, String propName, boolean create)
```


Restituisce il bind point di animazione sulla proprietà specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Su quale oggetto creare il punto di collegamento. |
| propName | java.lang.String | Il nome della proprietà. |
| crea | boolean | Se impostato su  true  crea il punto di collegamento se non esiste. |

**Returns:**
[BindPoint](../../com.aspose.threed/bindpoint) - The bind point.
### getBindPoints() {#getBindPoints--}
```
public List<BindPoint> getBindPoints()
```


Restituisce i bind point delle proprietà correnti.

**Returns:**
java.util.List<com.aspose.threed.BindPoint> - i punti di collegamento della proprietà corrente
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeyframeSequence(A3DObject target, String propName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, boolean create)
```


Restituisce la sequenza di fotogrammi chiave sulla proprietà specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Su quale istanza creare la sequenza di fotogrammi chiave. |
| propName | java.lang.String | Il nome della proprietà. |
| crea | boolean | Se impostato su  true , crea la sequenza se non esiste. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
### getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create) {#getKeyframeSequence-com.aspose.threed.A3DObject-java.lang.String-java.lang.String-boolean-}
```
public KeyframeSequence getKeyframeSequence(A3DObject target, String propName, String channelName, boolean create)
```


Ottiene la sequenza di fotogrammi chiave sulla proprietà e sul canale specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| target | [A3DObject](../../com.aspose.threed/a3dobject) | Su quale istanza creare la sequenza di fotogrammi chiave. |
| propName | java.lang.String | Il nome della proprietà. |
| channelName | java.lang.String | Il nome del canale. |
| crea | boolean | Se impostato su  true  crea la sequenza di animazione se non esiste. |

**Returns:**
[KeyframeSequence](../../com.aspose.threed/keyframesequence) - The keyframe sequence.
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
### getSubAnimations() {#getSubAnimations--}
```
public List<AnimationNode> getSubAnimations()
```


Ottiene i nodi di sotto-animazione sotto le animazioni correnti

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> - i nodi di sotto-animazione sotto le animazioni correnti
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

