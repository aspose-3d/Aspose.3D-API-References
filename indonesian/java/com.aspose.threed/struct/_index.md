---
title: Struktur
second_title: Referensi API Aspose.3D untuk Java
description: Dibuat oleh lexchou pada 13/11/2017.
type: docs
weight: 262
url: /id/java/com.aspose.threed/struct/
---

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public interface Struct<T> extends Cloneable, Serializable
```

Dibuat oleh lexchou pada 13/11/2017.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [<T>byVal(T value)](#-T-byVal-T-) | Coba salin nilai masukan jika itu Struct |
| [clone()](#clone--) | Clone current instance |
| [copyFrom(T t)](#copyFrom-T-) | Salin status internal dari argumen t |
### <T>byVal(T value) {#-T-byVal-T-}
```
public static T <T>byVal(T value)
```


Coba salin nilai masukan jika itu Struct

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | T | nilai masukan untuk digandakan |

**Returns:**
T - null jika masukan null atau instance yang digandakan
### clone() {#clone--}
```
public abstract T clone()
```


Clone current instance

**Returns:**
T - instance yang digandakan
### copyFrom(T t) {#copyFrom-T-}
```
public abstract void copyFrom(T t)
```


Salin status internal dari argumen t

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| t | T | instance sumber untuk disalin |

