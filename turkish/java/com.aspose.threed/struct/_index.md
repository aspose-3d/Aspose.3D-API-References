---
title: "Struct"
second_title: "Aspose.3D for Java API Referansı"
description: "lexchou tarafından 13/11/2017 tarihinde oluşturuldu."
type: docs
weight: 262
url: /tr/java/com.aspose.threed/struct/
---

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public interface Struct<T> extends Cloneable, Serializable
```

lexchou tarafından 13/11/2017 tarihinde oluşturuldu.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [<T>byVal(T value)](#-T-byVal-T-) | Giriş değerini, eğer Struct ise kopyalamayı dene |
| [clone()](#clone--) | Geçerli örneği kopyala |
| [copyFrom(T t)](#copyFrom-T-) | t argümanından iç durumu kopyala |
### <T>byVal(T value) {#-T-byVal-T-}
```
public static T <T>byVal(T value)
```


Giriş değerini, eğer Struct ise kopyalamayı dene

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | T | kopyalanacak giriş değeri |

**Returns:**
T - giriş null ise null veya kopyalanmış örnek
### clone() {#clone--}
```
public abstract T clone()
```


Geçerli örneği kopyala

**Returns:**
T - kopyalanmış örnek
### copyFrom(T t) {#copyFrom-T-}
```
public abstract void copyFrom(T t)
```


t argümanından iç durumu kopyala

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| t | T | kopyalanacak kaynak örnek |

