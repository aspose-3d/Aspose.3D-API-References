---
title: StructuralMetadata.Property
second_title: Aspose.3D for Java API Reference
description: La definizione della proprietà nelle classi dei metadati.
type: docs
weight: 13
url: /it/java/com.aspose.threed/structuralmetadata.property/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.Property
```

La definizione della proprietà nelle classi dei metadati
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-) | Costruttore della proprietà dei metadati. |
| [Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) | Costruttore della proprietà dei metadati. |
| [Property(String name, Class<?> type)](#Property-java.lang.String-java.lang.Class----) | Costruttore della proprietà dei metadati. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Conteggio dei dati per un array a dimensione fissa. |
| [getDescription()](#getDescription--) | La descrizione della proprietà. |
| [getDisplayName()](#getDisplayName--) | Il nome della proprietà, utilizzato dall'interfaccia utente per la rappresentazione. |
| [getEnumType()](#getEnumType--) | Il tipo enum. |
| [getName()](#getName--) | Il nome univoco della proprietà. |
| [getNormalized()](#getNormalized--) | I dati sono normalizzati. |
| [getType()](#getType--) | Il tipo di dato della proprietà. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(Integer value)](#setCount-java.lang.Integer-) | Conteggio dei dati per un array a dimensione fissa. |
| [setDescription(String value)](#setDescription-java.lang.String-) | La descrizione della proprietà. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Il nome della proprietà, utilizzato dall'interfaccia utente per la rappresentazione. |
| [setEnumType(StructuralMetadata.EnumType value)](#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-) | Il tipo enum. |
| [setNormalized(boolean value)](#setNormalized-boolean-) | I dati sono normalizzati. |
| [toString()](#toString--) | Ottiene la rappresentazione stringa di questa istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)
```


Costruttore della proprietà dei metadati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Il nome univoco della proprietà. |
| displayName | java.lang.String | Il nome della proprietà, utilizzato dall'interfaccia utente per la rappresentazione. |
| description | java.lang.String | La descrizione della proprietà. |
| type | java.lang.Class<?> | Tipo di dato della proprietà. |
| normalized | boolean | I dati sono normalizzati |
| conteggio | java.lang.Integer | Conteggio dei dati per array a dimensione fissa |

### Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)
```


Costruttore della proprietà dei metadati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Il nome univoco della proprietà. |
| displayName | java.lang.String | Il nome della proprietà, utilizzato dall'interfaccia utente per la rappresentazione. |
| description | java.lang.String | La descrizione della proprietà. |
| type | [EnumType](../../com.aspose.threed/enumtype) | Tipo di dato della proprietà. |
| array | boolean | Ogni valore della proprietà è un array o uno scalare |
| conteggio | java.lang.Integer | Conteggio dei dati per array a dimensione fissa |

### Property(String name, Class<?> type) {#Property-java.lang.String-java.lang.Class----}
```
public Property(String name, Class<?> type)
```


Costruttore della proprietà dei metadati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Il nome univoco della proprietà. |
| type | java.lang.Class<?> | Tipo di dato della proprietà. |

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
### getCount() {#getCount--}
```
public Integer getCount()
```


Conteggio dei dati per un array a dimensione fissa.

**Returns:**
java.lang.Integer - Conteggio dei dati per array a dimensione fissa.
### getDescription() {#getDescription--}
```
public String getDescription()
```


La descrizione della proprietà.

**Returns:**
java.lang.String - La descrizione della proprietà
### getDisplayName() {#getDisplayName--}
```
public String getDisplayName()
```


Il nome della proprietà, utilizzato dall'interfaccia utente per la rappresentazione.

**Returns:**
java.lang.String - Il nome della proprietà, usato dall'interfaccia utente per la rappresentazione.
### getEnumType() {#getEnumType--}
```
public StructuralMetadata.EnumType getEnumType()
```


Il tipo enum.

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - The enum type
### getName() {#getName--}
```
public String getName()
```


Il nome univoco della proprietà.

**Returns:**
java.lang.String - Il nome univoco della proprietà
### getNormalized() {#getNormalized--}
```
public boolean getNormalized()
```


I dati sono normalizzati.

**Returns:**
boolean - I dati sono normalizzati.
### getType() {#getType--}
```
public Class<?> getType()
```


Il tipo di dato della proprietà.

**Returns:**
java.lang.Class<?> - Il tipo di dato della proprietà
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




### setCount(Integer value) {#setCount-java.lang.Integer-}
```
public void setCount(Integer value)
```


Conteggio dei dati per un array a dimensione fissa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Integer | Nuovo valore |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


La descrizione della proprietà.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public void setDisplayName(String value)
```


Il nome della proprietà, utilizzato dall'interfaccia utente per la rappresentazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setEnumType(StructuralMetadata.EnumType value) {#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-}
```
public void setEnumType(StructuralMetadata.EnumType value)
```


Il tipo enum.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EnumType](../../com.aspose.threed/enumtype) | Nuovo valore |

### setNormalized(boolean value) {#setNormalized-boolean-}
```
public void setNormalized(boolean value)
```


I dati sono normalizzati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### toString() {#toString--}
```
public String toString()
```


Ottiene la rappresentazione stringa di questa istanza.

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

