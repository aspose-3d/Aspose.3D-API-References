---
title: VertexElementNormal
second_title: Aspose.3D for Java API Reference
description: Definisce i vettori normali per i componenti specificati.
type: docs
weight: 214
url: /it/java/com.aspose.threed/vertexelementnormal/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.VertexElement](../../com.aspose.threed/vertexelement), [com.aspose.threed.VertexElementVector4](../../com.aspose.threed/vertexelementvector4)
```
public class VertexElementNormal extends VertexElementVector4
```

Definisce i vettori normali per i componenti specificati.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [VertexElementNormal()](#VertexElementNormal--) | Inizializza una nuova istanza della classe [VertexElementNormal](../../com.aspose.threed/vertexelementnormal). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clear()](#clear--) | Rimuove tutti gli elementi dagli array direct e index. |
| [clone(boolean withData)](#clone-boolean-) | Clona in profondità l'elemento vertex. |
| [clone(boolean withDirect, boolean withIndice)](#clone-boolean-boolean-) |  |
| [copyTo(VertexElementVector4 target)](#copyTo-com.aspose.threed.VertexElementVector4-) | Copia i dati nell'elemento specificato. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Ottiene i dati vertex. |
| [getIndices()](#getIndices--) | Ottiene i dati degli indici. |
| [getMappingMode()](#getMappingMode--) | Restituisce come l'elemento è mappato. |
| [getName()](#getName--) | Ottiene il nome. |
| [getReferenceMode()](#getReferenceMode--) | Restituisce come l'elemento è referenziato. |
| [getVertexElementType()](#getVertexElementType--) | Ottiene il tipo del [VertexElement](../../com.aspose.threed/vertexelement) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setData(Vector4[] data)](#setData-com.aspose.threed.Vector4---) | Carica dati |
| [setIndices(int[] data)](#setIndices-int---) | Carica indici |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | Imposta come l'elemento è mappato. |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | Imposta come l'elemento è referenziato. |
| [toString()](#toString--) | Rappresentazione stringa dell'elemento vertex. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexElementNormal() {#VertexElementNormal--}
```
public VertexElementNormal()
```


Inizializza una nuova istanza della classe [VertexElementNormal](../../com.aspose.threed/vertexelementnormal).

### clear() {#clear--}
```
public void clear()
```


Rimuove tutti gli elementi dagli array direct e index.

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
### copyTo(VertexElementVector4 target) {#copyTo-com.aspose.threed.VertexElementVector4-}
```
public void copyTo(VertexElementVector4 target)
```


Copia i dati nell'elemento specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| target | [VertexElementVector4](../../com.aspose.threed/vertexelementvector4) | Obiettivo. |

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
public List<Vector4> getData()
```


Ottiene i dati vertex.

**Returns:**
java.util.List<com.aspose.threed.Vector4> - i dati del vertice
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




### setData(Vector4[] data) {#setData-com.aspose.threed.Vector4---}
```
public void setData(Vector4[] data)
```


Carica dati

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | [Vector4\[\]](../../com.aspose.threed/vector4) |  |

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

