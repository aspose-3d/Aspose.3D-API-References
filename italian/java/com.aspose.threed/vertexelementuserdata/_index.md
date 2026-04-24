---
title: VertexElementUserData
second_title: Aspose.3D for Java API Reference
description: Definisce dati utente personalizzati per i componenti specificati.
type: docs
weight: 221
url: /it/java/com.aspose.threed/vertexelementuserdata/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.VertexElement](../../com.aspose.threed/vertexelement)
```
public class VertexElementUserData extends VertexElement
```

Definisce dati utente personalizzati per i componenti specificati. Di solito sono dati specifici dell'applicazione per scopi speciali.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [VertexElementUserData()](#VertexElementUserData--) | Inizializza una nuova istanza della classe [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clear()](#clear--) | Cancella tutti i dati da questo elemento vertice. |
| [clone(boolean withData)](#clone-boolean-) | Clona in profondità l'elemento vertex. |
| [clone(boolean withDirect, boolean withIndice)](#clone-boolean-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | I dati utente allegati a questo elemento |
| [getIndices()](#getIndices--) | Ottiene i dati degli indici. |
| [getMappingMode()](#getMappingMode--) | Restituisce come l'elemento è mappato. |
| [getName()](#getName--) | Ottiene il nome. |
| [getReferenceMode()](#getReferenceMode--) | Restituisce come l'elemento è referenziato. |
| [getVertexElementType()](#getVertexElementType--) | Ottiene il tipo del [VertexElement](../../com.aspose.threed/vertexelement) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setData(Object value)](#setData-java.lang.Object-) | I dati utente allegati a questo elemento |
| [setIndices(int[] data)](#setIndices-int---) | Carica indici |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | Imposta come l'elemento è mappato. |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | Imposta come l'elemento è referenziato. |
| [toString()](#toString--) | Rappresentazione stringa dell'elemento vertex. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexElementUserData() {#VertexElementUserData--}
```
public VertexElementUserData()
```


Inizializza una nuova istanza della classe [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata).

### clear() {#clear--}
```
public void clear()
```


Cancella tutti i dati da questo elemento vertice.

### clone(boolean withData) {#clone-boolean-}
```
public VertexElement clone(boolean withData)
```


Clona in profondità l'elemento vertex.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| withData | boolean | Clona il vertex con gli array direct e index |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
### clone(boolean withDirect, boolean withIndice) {#clone-boolean-boolean-}
```
public VertexElement clone(boolean withDirect, boolean withIndice)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| withDirect | boolean |  |
| withIndice | boolean |  |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public Object getData()
```


I dati utente allegati a questo elemento

**Returns:**
java.lang.Object - I dati utente allegati a questo elemento
### getIndices() {#getIndices--}
```
public List<Integer> getIndices()
```


Ottiene i dati degli indici.

**Returns:**
java.util.List<java.lang.Integer> - i dati degli indici
### getMappingMode() {#getMappingMode--}
```
public MappingMode getMappingMode()
```


Restituisce come l'elemento è mappato.

**Returns:**
[MappingMode](../../com.aspose.threed/mappingmode) - how the element is mapped.
### getName() {#getName--}
```
public String getName()
```


Ottiene il nome.

**Returns:**
java.lang.String - il nome.
### getReferenceMode() {#getReferenceMode--}
```
public ReferenceMode getReferenceMode()
```


Restituisce come l'elemento è referenziato.

**Returns:**
[ReferenceMode](../../com.aspose.threed/referencemode) - how the element is referenced.
### getVertexElementType() {#getVertexElementType--}
```
public VertexElementType getVertexElementType()
```


Ottiene il tipo del [VertexElement](../../com.aspose.threed/vertexelement)

**Returns:**
[VertexElementType](../../com.aspose.threed/vertexelementtype) - the type of the [VertexElement](../../com.aspose.threed/vertexelement)
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




### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```


I dati utente allegati a questo elemento

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object | Nuovo valore |

### setIndices(int[] data) {#setIndices-int---}
```
public void setIndices(int[] data)
```


Carica indici

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | int[] |  |

### setMappingMode(MappingMode value) {#setMappingMode-com.aspose.threed.MappingMode-}
```
public void setMappingMode(MappingMode value)
```


Imposta come l'elemento è mappato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [MappingMode](../../com.aspose.threed/mappingmode) | Nuovo valore |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Imposta il nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setReferenceMode(ReferenceMode value) {#setReferenceMode-com.aspose.threed.ReferenceMode-}
```
public void setReferenceMode(ReferenceMode value)
```


Imposta come l'elemento è referenziato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ReferenceMode](../../com.aspose.threed/referencemode) | Nuovo valore |

### toString() {#toString--}
```
public String toString()
```


Rappresentazione stringa dell'elemento vertex.

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

