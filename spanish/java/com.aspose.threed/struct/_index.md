---
title: Estructura
second_title: Referencia de API de Aspose.3D para Java
description: Creado por lexchou el 13/11/2017.
type: docs
weight: 262
url: /es/java/com.aspose.threed/struct/
---

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public interface Struct<T> extends Cloneable, Serializable
```

Creado por lexchou el 13/11/2017.
## Métodos

| Método | Descripción |
| --- | --- |
| [<T>byVal(T value)](#-T-byVal-T-) | Intentar copiar el valor de entrada si es una Estructura |
| [clone()](#clone--) | Clonar la instancia actual |
| [copyFrom(T t)](#copyFrom-T-) | Copiar el estado interno del argumento t |
### <T>byVal(T value) {#-T-byVal-T-}
```
public static T <T>byVal(T value)
```


Intentar copiar el valor de entrada si es una Estructura

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | T | valor de entrada a clonar |

**Returns:**
T - nulo si la entrada es nula o instancia clonada
### clone() {#clone--}
```
public abstract T clone()
```


Clonar la instancia actual

**Returns:**
T - instancia clonada
### copyFrom(T t) {#copyFrom-T-}
```
public abstract void copyFrom(T t)
```


Copiar el estado interno del argumento t

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| t | T | instancia fuente a copiar |

