---
title: Struct
second_title: Aspose.3D for Java API Reference
description: Creato da lexchou il 13/11/2017.
type: docs
weight: 262
url: /it/java/com.aspose.threed/struct/
---

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public interface Struct<T> extends Cloneable, Serializable
```

Creato da lexchou il 13/11/2017.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [<T>byVal(T value)](#-T-byVal-T-) | Prova a copiare il valore di input se è una Struct |
| [clone()](#clone--) | Clone current instance |
| [copyFrom(T t)](#copyFrom-T-) | Copia lo stato interno dall'argomento t |
### <T>byVal(T value) {#-T-byVal-T-}
```
public static T <T>byVal(T value)
```


Prova a copiare il valore di input se è una Struct

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | T | valore di input da clonare |

**Returns:**
T - null se l'input è null o l'istanza clonata
### clone() {#clone--}
```
public abstract T clone()
```


Clone current instance

**Returns:**
T - istanza clonata
### copyFrom(T t) {#copyFrom-T-}
```
public abstract void copyFrom(T t)
```


Copia lo stato interno dall'argomento t

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| t | T | istanza sorgente da copiare |

