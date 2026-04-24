---
title: StructuralMetadata.PropertyTable
second_title: Aspose.3D for Java API Reference
description: Tabella delle proprietà.
type: docs
weight: 14
url: /it/java/com.aspose.threed/structuralmetadata.propertytable/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.PropertyTable
```

Tabella delle proprietà.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PropertyTable(String name, StructuralMetadata.ClassType mclass)](#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | Costruttore della tabella delle proprietà. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addValue(StructuralMetadata.Property prop, Object value)](#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-) | Aggiungi una nuova proprietà alla tabella delle proprietà. |
| [addValue(String propName, Object value)](#addValue-java.lang.String-java.lang.Object-) | Aggiungi una nuova proprietà alla tabella delle proprietà. |
| [attach(VertexElementUserData userData)](#attach-com.aspose.threed.VertexElementUserData-) | Allega la tabella delle proprietà corrente ai dati utente specificati |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(VertexElementUserData userData)](#from-com.aspose.threed.VertexElementUserData-) | Estrai la tabella delle proprietà allegata dai dati utente specificati |
| [getClass()](#getClass--) |  |
| [getMetaClass()](#getMetaClass--) | La meta classe di questa tabella delle proprietà. |
| [getName()](#getName--) | Nome della tabella delle proprietà. |
| [getValue(String name)](#getValue-java.lang.String-) | Ottiene il valore del nome della proprietà specificata |
| [getValues()](#getValues--) | Valori della tabella delle proprietà. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PropertyTable(String name, StructuralMetadata.ClassType mclass) {#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-}
```
public PropertyTable(String name, StructuralMetadata.ClassType mclass)
```


Costruttore della tabella delle proprietà.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Il nome di questa istanza di tabella. |
| mclass | [ClassType](../../com.aspose.threed/classtype) | La definizione della meta classe di questa tabella delle proprietà |

### addValue(StructuralMetadata.Property prop, Object value) {#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-}
```
public void addValue(StructuralMetadata.Property prop, Object value)
```


Aggiungi una nuova proprietà alla tabella delle proprietà.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prop | [Property](../../com.aspose.threed/property) | Quale proprietà aggiungere con valore |
| valore | java.lang.Object | Array di valori |

### addValue(String propName, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String propName, Object value)
```


Aggiungi una nuova proprietà alla tabella delle proprietà.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propName | java.lang.String | Quale proprietà aggiungere con valore |
| valore | java.lang.Object | Array di valori |

### attach(VertexElementUserData userData) {#attach-com.aspose.threed.VertexElementUserData-}
```
public void attach(VertexElementUserData userData)
```


Allega la tabella delle proprietà corrente ai dati utente specificati

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) |  |

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
### from(VertexElementUserData userData) {#from-com.aspose.threed.VertexElementUserData-}
```
public static StructuralMetadata.PropertyTable from(VertexElementUserData userData)
```


Estrai la tabella delle proprietà allegata dai dati utente specificati

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) | I dati utente associati a una tabella delle proprietà |

**Returns:**
[PropertyTable](../../com.aspose.threed/propertytable) - The associated property table instance
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMetaClass() {#getMetaClass--}
```
public StructuralMetadata.ClassType getMetaClass()
```


La meta classe di questa tabella delle proprietà.

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - The meta class of this property table.
### getName() {#getName--}
```
public String getName()
```


Nome della tabella delle proprietà.

**Returns:**
java.lang.String - Nome della tabella delle proprietà.
### getValue(String name) {#getValue-java.lang.String-}
```
public Object getValue(String name)
```


Ottiene il valore del nome della proprietà specificata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome della proprietà |

**Returns:**
java.lang.Object - Valore della proprietà o null se non trovato
### getValues() {#getValues--}
```
public HashMap<String,Object> getValues()
```


Valori della tabella delle proprietà.

**Returns:**
java.util.HashMap<java.lang.String,java.lang.Object> - Valori della tabella delle proprietà.
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

