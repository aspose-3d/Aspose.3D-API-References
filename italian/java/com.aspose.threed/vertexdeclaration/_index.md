---
title: VertexDeclaration
second_title: Aspose.3D for Java API Reference
description: La dichiarazione di una struttura di vertici definita su misura
type: docs
weight: 206
url: /it/java/com.aspose.threed/vertexdeclaration/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable, java.lang.Comparable
```
public final class VertexDeclaration implements Iterable<VertexField>, Comparable<VertexDeclaration>
```

La dichiarazione della struttura di un vertice definito personalizzato
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [VertexDeclaration()](#VertexDeclaration--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addField(int dataType, VertexFieldSemantic semantic)](#addField-int-com.aspose.threed.VertexFieldSemantic-) | Aggiungi un nuovo campo vertice |
| [addField(int dataType, VertexFieldSemantic semantic, int index)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-) | Aggiungi un nuovo campo vertice |
| [addField(int dataType, VertexFieldSemantic semantic, int index, String alias)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-) | Aggiungi un nuovo campo vertice |
| [clear()](#clear--) | Cancella tutti i campi. |
| [compareTo(VertexDeclaration other)](#compareTo-com.aspose.threed.VertexDeclaration-) | Confronta questa istanza con un oggetto specificato e restituisce un'indicazione dei loro valori relativi. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se questa istanza e un oggetto specificato, che deve essere anche un oggetto [VertexDeclaration](../../com.aspose.threed/vertexdeclaration), hanno lo stesso valore. |
| [fromGeometry(Geometry geometry, boolean useFloat)](#fromGeometry-com.aspose.threed.Geometry-boolean-) | Crea un [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) basato sul layout di una [Geometry](../../com.aspose.threed/geometry). |
| [get(int index)](#get-int-) | Ottiene il [VertexField](../../com.aspose.threed/vertexfield) per indice |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Ottiene il conteggio di tutti i campi definiti in questo [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |
| [getSealed()](#getSealed--) | Un [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) verrà sigillato quando è stato usato da [TriMesh](../../com.aspose.threed/trimesg), non sono più consentite modifiche. |
| [getSize()](#getSize--) | La dimensione in byte della struttura del vertice. |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa stringa. |
| [iterator()](#iterator--) | Ottiene un enumeratore per attraversare tutti i campi vertice in questa istanza. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Rappresentazione stringa di [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexDeclaration() {#VertexDeclaration--}
```
public VertexDeclaration()
```


### addField(int dataType, VertexFieldSemantic semantic) {#addField-int-com.aspose.threed.VertexFieldSemantic-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic)
```


Aggiungi un nuovo campo vertice

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataType | int | Il tipo di dato del campo vertice |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Come verrà utilizzato questo campo |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index)
```


Aggiungi un nuovo campo vertice

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataType | int | Il tipo di dato del campo vertice |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Come verrà utilizzato questo campo |
| indice | int | L'indice per la stessa semantica del campo, -1 per la generazione automatica |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index, String alias) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index, String alias)
```


Aggiungi un nuovo campo vertice

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataType | int | Il tipo di dato del campo vertice |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Come verrà utilizzato questo campo |
| indice | int | L'indice per la stessa semantica del campo, -1 per la generazione automatica |
| alias | java.lang.String | Il nome alias del campo |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### clear() {#clear--}
```
public void clear()
```


Cancella tutti i campi.

### compareTo(VertexDeclaration other) {#compareTo-com.aspose.threed.VertexDeclaration-}
```
public int compareTo(VertexDeclaration other)
```


Confronta questa istanza con un oggetto specificato e restituisce un'indicazione dei loro valori relativi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se questa istanza e un oggetto specificato, che deve essere anche un oggetto [VertexDeclaration](../../com.aspose.threed/vertexdeclaration), hanno lo stesso valore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromGeometry(Geometry geometry, boolean useFloat) {#fromGeometry-com.aspose.threed.Geometry-boolean-}
```
public static VertexDeclaration fromGeometry(Geometry geometry, boolean useFloat)
```


Crea un [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) basato sul layout di una [Geometry](../../com.aspose.threed/geometry).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) |  |
| useFloat | boolean | Usa float invece del tipo double |

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### get(int index) {#get-int-}
```
public VertexField get(int index)
```


Ottiene il [VertexField](../../com.aspose.threed/vertexfield) per indice

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int |  |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield) - the [VertexField](../../com.aspose.threed/vertexfield) by index
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


Ottiene il conteggio di tutti i campi definiti in questo [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)

**Returns:**
int - il conteggio di tutti i campi definiti in questo [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### getSealed() {#getSealed--}
```
public boolean getSealed()
```


Un [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) verrà sigillato quando è stato usato da [TriMesh](../../com.aspose.threed/trimesg), non sono più consentite modifiche.

**Returns:**
boolean - Un [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) verrà sigillato quando è stato utilizzato da [TriMesh](../../com.aspose.threed/trimesh), non sono più consentite modifiche.
### getSize() {#getSize--}
```
public int getSize()
```


La dimensione in byte della struttura del vertice.

**Returns:**
int - La dimensione in byte della struttura del vertice.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash per questa stringa.

**Returns:**
int - Un codice hash intero con segno a 32 bit.
### iterator() {#iterator--}
```
public Iterator<VertexField> iterator()
```


Ottiene un enumeratore per attraversare tutti i campi vertice in questa istanza.

**Returns:**
java.util.Iterator<com.aspose.threed.VertexField> - Enumeratore
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


Rappresentazione stringa di [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)

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

