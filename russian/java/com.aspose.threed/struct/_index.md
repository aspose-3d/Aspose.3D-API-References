---
title: Struct
second_title: Справочник API Aspose.3D для Java
description: Создано lexchou 13.11.2017.
type: docs
weight: 262
url: /ru/java/com.aspose.threed/struct/
---

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public interface Struct<T> extends Cloneable, Serializable
```

Создано lexchou 13.11.2017.
## Методы

| Метод | Описание |
| --- | --- |
| [<T>byVal(T value)](#-T-byVal-T-) | Попробовать скопировать входное значение, если оно является Struct |
| [clone()](#clone--) | Клонировать текущий экземпляр |
| [copyFrom(T t)](#copyFrom-T-) | Скопировать внутреннее состояние из аргумента t |
### <T>byVal(T value) {#-T-byVal-T-}
```
public static T <T>byVal(T value)
```


Попробовать скопировать входное значение, если оно является Struct

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | T | входное значение для клонирования |

**Returns:**
T - null, если входное значение null или клонированный экземпляр
### clone() {#clone--}
```
public abstract T clone()
```


Клонировать текущий экземпляр

**Returns:**
T - клонированный экземпляр
### copyFrom(T t) {#copyFrom-T-}
```
public abstract void copyFrom(T t)
```


Скопировать внутреннее состояние из аргумента t

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| t | T | исходный экземпляр для копирования |

