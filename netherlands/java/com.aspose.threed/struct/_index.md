---
title: Struct
second_title: Aspose.3D for Java API-referentie
description: Gemaakt door lexchou op 13-11-2017.
type: docs
weight: 262
url: /nl/java/com.aspose.threed/struct/
---

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public interface Struct<T> extends Cloneable, Serializable
```

Gemaakt door lexchou op 13-11-2017.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [<T>byVal(T value)](#-T-byVal-T-) | Probeer de invoerwaarde te kopiëren als het een Struct is |
| [clone()](#clone--) | Kloon huidige instantie |
| [copyFrom(T t)](#copyFrom-T-) | Kopieer de interne staat van argument t |
### <T>byVal(T value) {#-T-byVal-T-}
```
public static T <T>byVal(T value)
```


Probeer de invoerwaarde te kopiëren als het een Struct is

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | T | invoerwaarde om te klonen |

**Returns:**
T - null als invoer null is of gekloonde instantie
### clone() {#clone--}
```
public abstract T clone()
```


Kloon huidige instantie

**Returns:**
T - gekloonde instantie
### copyFrom(T t) {#copyFrom-T-}
```
public abstract void copyFrom(T t)
```


Kopieer de interne staat van argument t

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| t | T | broninstantie om te kopiëren |

