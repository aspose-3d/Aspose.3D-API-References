---
title: AnimationClip
second_title: Aspose.3D for Java API Reference
description: Il clip di animazione è una raccolta di animazioni.
type: docs
weight: 14
url: /it/java/com.aspose.threed/animationclip/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class AnimationClip extends SceneObject
```

Il clip di animazione è una raccolta di animazioni. La scena può avere uno o più clip di animazione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [AnimationClip()](#AnimationClip--) | Inizializza una nuova istanza della classe [AnimationClip](../../com.aspose.threed/animationclip). |
| [AnimationClip(String name)](#AnimationClip-java.lang.String-) | Inizializza una nuova istanza della classe [AnimationClip](../../com.aspose.threed/animationclip). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createAnimationNode(String nodeName)](#createAnimationNode-java.lang.String-) | Una funzione abbreviata per creare e registrare il nodo di animazione sul clip corrente. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [getAnimations()](#getAnimations--) | Restituisce le animazioni contenute nel clip. |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Restituisce la descrizione di questo clip di animazione |
| [getName()](#getName--) | Ottiene il nome. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getScene()](#getScene--) | Ottiene la scena a cui appartiene questo oggetto |
| [getStart()](#getStart--) | Restituisce il tempo in secondi dell'inizio del clip. |
| [getStop()](#getStop--) | Restituisce il tempo in secondi della fine del clip. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [setDescription(String value)](#setDescription-java.lang.String-) | Imposta la descrizione di questo clip di animazione |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [setStart(double value)](#setStart-double-) | Imposta il tempo in secondi dell'inizio della clip. |
| [setStop(double value)](#setStop-double-) | Imposta il tempo in secondi della fine della clip. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AnimationClip() {#AnimationClip--}
```
public AnimationClip()
```


Inizializza una nuova istanza della classe [AnimationClip](../../com.aspose.threed/animationclip).

### AnimationClip(String name) {#AnimationClip-java.lang.String-}
```
public AnimationClip(String name)
```


Inizializza una nuova istanza della classe [AnimationClip](../../com.aspose.threed/animationclip).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome |

### createAnimationNode(String nodeName) {#createAnimationNode-java.lang.String-}
```
public AnimationNode createAnimationNode(String nodeName)
```


Una funzione abbreviata per creare e registrare il nodo di animazione sul clip corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nodeName | java.lang.String | Nome del nuovo nodo di animazione |

**Returns:**
[AnimationNode](../../com.aspose.threed/animationnode) - A new instance of [AnimationNode](../../com.aspose.threed/animationnode) with given name.
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
### getAnimations() {#getAnimations--}
```
public List<AnimationNode> getAnimations()
```


Restituisce le animazioni contenute nel clip.

**Returns:**
java.util.List<com.aspose.threed.AnimationNode> - le animazioni contenute nella clip.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public String getDescription()
```


Restituisce la descrizione di questo clip di animazione

**Returns:**
java.lang.String - la descrizione di questa clip di animazione
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
### getScene() {#getScene--}
```
public Scene getScene()
```


Ottiene la scena a cui appartiene questo oggetto

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getStart() {#getStart--}
```
public double getStart()
```


Restituisce il tempo in secondi dell'inizio del clip.

**Returns:**
double - il tempo in secondi dell'inizio della clip.
### getStop() {#getStop--}
```
public double getStop()
```


Restituisce il tempo in secondi della fine del clip.

**Returns:**
double - il tempo in secondi della fine della clip.
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
### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Imposta la descrizione di questo clip di animazione

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

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

### setStart(double value) {#setStart-double-}
```
public void setStart(double value)
```


Imposta il tempo in secondi dell'inizio della clip.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setStop(double value) {#setStop-double-}
```
public void setStop(double value)
```


Imposta il tempo in secondi della fine della clip.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

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

