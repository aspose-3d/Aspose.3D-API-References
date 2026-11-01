---
title: "Struct"
second_title: "مرجع Aspose.3D لـ Java API"
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
| [clone()](#clone--) | استنساخ الكائن الحالي |
| [copyFrom(T t)](#copyFrom-T-) | نسخ الحالة الداخلية من الوسيط t |
### <T>byVal(T value) {#-T-byVal-T-}
```
public static T <T>byVal(T value)
```


حاول نسخ القيمة المدخلة إذا كانت Struct

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | T | القيمة المدخلة للاستنساخ |

**Returns:**
T - null إذا كان الإدخال null أو نسخة مستنسخة
### clone() {#clone--}
```
public abstract T clone()
```


استنساخ الكائن الحالي

**Returns:**
T - نسخة مستنسخة
### copyFrom(T t) {#copyFrom-T-}
```
public abstract void copyFrom(T t)
```


نسخ الحالة الداخلية من الوسيط t

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| t | T | مثيل المصدر للنسخ |

