---
title: Osso
second_title: Aspose.3D for Java API Reference
description: Un osso definisce il sottoinsieme dei punti di controllo della geometria e il peso di blend definito per ciascun punto di controllo.
type: docs
weight: 20
url: /it/java/com.aspose.threed/bone/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Bone extends A3DObject
```

Un osso definisce il sottoinsieme dei punti di controllo della geometria e il peso di blend definito per ciascun punto di controllo. L'oggetto [Bone](../../com.aspose.threed/bone) non può essere usato direttamente, un'istanza di [SkinDeformer](../../com.aspose.threed/skindeformer) viene utilizzata per deformare la geometria, e [SkinDeformer](../../com.aspose.threed/skindeformer) è fornito con un insieme di ossa, ciascuna osso collegata a un nodo. NOTA: Un punto di controllo di una geometria può essere associato a più di un osso.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Bone(String name)](#Bone-java.lang.String-) | Inizializza una nuova istanza della classe [Bone](../../com.aspose.threed/bone). |
| [Bone()](#Bone--) | Inizializza una nuova istanza della classe [Bone](../../com.aspose.threed/bone). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [get(int index)](#get-int-) | Ottiene il peso di blend del punto di controllo specificato |
| [getBoneTransform()](#getBoneTransform--) | Ottiene la matrice di trasformazione dell'osso. |
| [getClass()](#getClass--) |  |
| [getLinkMode()](#getLinkMode--) | La modalità di collegamento di un osso si riferisce al modo in cui un osso è connesso o collegato al suo osso genitore all'interno di una struttura gerarchica. |
| [getName()](#getName--) | Ottiene il nome. |
| [getNode()](#getNode--) | Ottiene il nodo. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getTransform()](#getTransform--) | Ottiene la matrice di trasformazione del nodo che contiene l'osso. |
| [getWeight(int index)](#getWeight-int-) | Ottiene il peso per il punto di controllo specificato per indice |
| [getWeightCount()](#getWeightCount--) | Ottiene il conteggio dei pesi, questo viene esteso automaticamente da [setWeight](../../com.aspose.threed/bone\#setWeight) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [set(int index, double value)](#set-int-double-) | Imposta il peso di fusione del punto di controllo specificato |
| [setBoneTransform(Matrix4 value)](#setBoneTransform-com.aspose.threed.Matrix4-) | Imposta la matrice di trasformazione dell'osso. |
| [setLinkMode(BoneLinkMode value)](#setLinkMode-com.aspose.threed.BoneLinkMode-) | La modalità di collegamento di un osso si riferisce al modo in cui un osso è connesso o collegato al suo osso genitore all'interno di una struttura gerarchica. |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | Imposta il nodo. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [setTransform(Matrix4 value)](#setTransform-com.aspose.threed.Matrix4-) | Imposta la matrice di trasformazione del nodo che contiene l'osso. |
| [setWeight(int index, double weight)](#setWeight-int-double-) | Imposta il peso per il punto di controllo specificato per indice |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Bone(String name) {#Bone-java.lang.String-}
```
public Bone(String name)
```


Inizializza una nuova istanza della classe [Bone](../../com.aspose.threed/bone).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome. |

### Bone() {#Bone--}
```
public Bone()
```


Inizializza una nuova istanza della classe [Bone](../../com.aspose.threed/bone).

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
### get(int index) {#get-int-}
```
public double get(int index)
```


Ottiene il peso di blend del punto di controllo specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int | Indice del peso |

**Returns:**
double - Il peso
### getBoneTransform() {#getBoneTransform--}
```
public Matrix4 getBoneTransform()
```


Ottiene la matrice di trasformazione dell'osso.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the bone.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLinkMode() {#getLinkMode--}
```
public BoneLinkMode getLinkMode()
```


La modalità di collegamento di un osso si riferisce al modo in cui un osso è connesso o collegato al suo osso genitore all'interno di una struttura gerarchica.

**Returns:**
[BoneLinkMode](../../com.aspose.threed/bonelinkmode) - A bone's link mode refers to the way in which a bone is connected or linked to its parent bone within a hierarchical structure.
### getName() {#getName--}
```
public String getName()
```


Ottiene il nome.

**Returns:**
java.lang.String - il nome.
### getNode() {#getNode--}
```
public Node getNode()
```


Ottiene il nodo. Il nodo osso è l'osso al quale è attaccata la pelle, il [SkinDeformer](../../com.aspose.threed/skindeformer) utilizzerà il nodo osso per influenzare lo spostamento dei punti di controllo. Il nodo osso di solito ha uno [Skeleton](../../com.aspose.threed/skeleton) allegato, ma non è obbligatorio. Lo [Skeleton](../../com.aspose.threed/skeleton) allegato è solitamente usato dal software DCC per mostrare lo scheletro all'utente.

**Returns:**
[Node](../../com.aspose.threed/node) - the node. The bone node is the bone which skin attached to, the [SkinDeformer](../../com.aspose.threed/skindeformer) will use bone node to influence the displacement of the control points. Bone node usually has a [Skeleton](../../com.aspose.threed/skeleton) attached, but it's not required. Attached [Skeleton](../../com.aspose.threed/skeleton) is usually used by DCC software to show skeleton to user.
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
### getTransform() {#getTransform--}
```
public Matrix4 getTransform()
```


Ottiene la matrice di trasformazione del nodo che contiene l'osso.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the transform matrix of the node containing the bone.
### getWeight(int index) {#getWeight-int-}
```
public double getWeight(int index)
```


Ottiene il peso per il punto di controllo specificato per indice

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int | Indice del punto di controllo |

**Returns:**
double - il peso all'indice specificato, o 0 se l'indice non è valido
### getWeightCount() {#getWeightCount--}
```
public int getWeightCount()
```


Ottiene il conteggio dei pesi, questo viene esteso automaticamente da [setWeight](../../com.aspose.threed/bone\#setWeight)

**Returns:**
int - il conteggio dei pesi, questo viene esteso automaticamente da [setWeight](../../com.aspose.threed/bone\#setWeight)
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
### set(int index, double value) {#set-int-double-}
```
public void set(int index, double value)
```


Imposta il peso di fusione del punto di controllo specificato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int | Indice del peso |
| valore | double | Nuovo valore |

### setBoneTransform(Matrix4 value) {#setBoneTransform-com.aspose.threed.Matrix4-}
```
public void setBoneTransform(Matrix4 value)
```


Imposta la matrice di trasformazione dell'osso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Nuovo valore |

### setLinkMode(BoneLinkMode value) {#setLinkMode-com.aspose.threed.BoneLinkMode-}
```
public void setLinkMode(BoneLinkMode value)
```


La modalità di collegamento di un osso si riferisce al modo in cui un osso è connesso o collegato al suo osso genitore all'interno di una struttura gerarchica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BoneLinkMode](../../com.aspose.threed/bonelinkmode) | Nuovo valore |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Imposta il nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


Imposta il nodo. Il nodo osso è l'osso al quale è attaccata la pelle, il [SkinDeformer](../../com.aspose.threed/skindeformer) utilizzerà il nodo osso per influenzare lo spostamento dei punti di controllo. Il nodo osso di solito ha uno [Skeleton](../../com.aspose.threed/skeleton) allegato, ma non è obbligatorio. Lo [Skeleton](../../com.aspose.threed/skeleton) allegato è solitamente usato dal software DCC per mostrare lo scheletro all'utente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nuovo valore |

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

### setTransform(Matrix4 value) {#setTransform-com.aspose.threed.Matrix4-}
```
public void setTransform(Matrix4 value)
```


Imposta la matrice di trasformazione del nodo che contiene l'osso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix4](../../com.aspose.threed/matrix4) | Nuovo valore |

### setWeight(int index, double weight) {#setWeight-int-double-}
```
public void setWeight(int index, double weight)
```


Imposta il peso per il punto di controllo specificato per indice

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int | Indice del punto di controllo |
| peso | double | Nuovo peso |

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

