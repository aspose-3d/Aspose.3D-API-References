---
title: "هيكل"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "تم الإنشاء بواسطة lexchou في 13/11/2017."
type: docs
weight: 262
url: /ar/java/com.aspose.threed/struct/
---

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public interface Struct<T> extends Cloneable, Serializable
```

تم الإنشاء بواسطة lexchou في 13/11/2017.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [<T>byVal(T value)](#-T-byVal-T-) | حاول نسخ القيمة المدخلة إذا كانت Struct |
| [clone()](#clone--) | استنساخ النسخة الحالية |
| [copyFrom(T t)](#copyFrom-T-) | انسخ الحالة الداخلية من المتغير t |
### <T>byVal(T value) {#-T-byVal-T-}
```
public static T <T>byVal(T value)
```


حاول نسخ القيمة المدخلة إذا كانت Struct

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | T | القيمة المدخلة للاستنساخ |

**Returns:**
T - null إذا كان الإدخال null أو نسخة مستنسخة
### clone() {#clone--}
```
public abstract T clone()
```


استنساخ النسخة الحالية

**Returns:**
T - نسخة مستنسخة
### copyFrom(T t) {#copyFrom-T-}
```
public abstract void copyFrom(T t)
```


انسخ الحالة الداخلية من المتغير t

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| t | T | مثيل المصدر للنسخ |

