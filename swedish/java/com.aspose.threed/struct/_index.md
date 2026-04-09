---
title: Struct
second_title: Aspose.3D for Java API-referens
description: Skapad av lexchou den 13/11/2017.
type: docs
weight: 262
url: /sv/java/com.aspose.threed/struct/
---

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public interface Struct<T> extends Cloneable, Serializable
```

Skapad av lexchou den 13/11/2017.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [<T>byVal(T value)](#-T-byVal-T-) | Försök att kopiera inmatningsvärdet om det är en Struct |
| [clone()](#clone--) | Clone current instance |
| [copyFrom(T t)](#copyFrom-T-) | Kopiera internt tillstånd från argumentet t |
### <T>byVal(T value) {#-T-byVal-T-}
```
public static T <T>byVal(T value)
```


Försök att kopiera inmatningsvärdet om det är en Struct

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | T | inmatningsvärde att klona |

**Returns:**
T – null om inmatningen är null eller klonad instans
### clone() {#clone--}
```
public abstract T clone()
```


Clone current instance

**Returns:**
T – klonad instans
### copyFrom(T t) {#copyFrom-T-}
```
public abstract void copyFrom(T t)
```


Kopiera internt tillstånd från argumentet t

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| t | T | källinstans att kopiera |

