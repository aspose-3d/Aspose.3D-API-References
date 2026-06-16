---
title: "Int2D"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "تم الإنشاء بواسطة lexchou في 17/5/2017."
type: docs
weight: 86
url: /ar/java/com.aspose.threed/int2d/
---

**Inheritance:**
java.lang.Object
```
public final class Int2D
```

تم الإنشاء بواسطة lexchou في 5/17/2017. غلاف مصفوفة أعداد صحيحة ثنائية الأبعاد
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Int2D(int rows, int columns)](#Int2D-int-int-) | إنشاء مصفوفة أعداد صحيحة ثنائية الأبعاد مع تخصيص البيانات الافتراضي. |
| [Int2D(int rows, int columns, int[] data)](#Int2D-int-int-int---) | إنشاء مصفوفة أعداد صحيحة ثنائية الأبعاد بالبيانات المعطاة |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int r, int c)](#get-int-int-) | يسترجع العنصر في الموضع المحدد |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) |  |
| [getLength(int rank)](#getLength-int-) |  |
| [getRows()](#getRows--) |  |
| [hashCode()](#hashCode--) |  |
| [length()](#length--) | يسترجع الطول الكلي لهذه المصفوفة الثنائية الأبعاد |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(int r, int c, int v)](#set-int-int-int-) | يعيّن العنصر في الموضع المحدد |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Int2D(int rows, int columns) {#Int2D-int-int-}
```
public Int2D(int rows, int columns)
```


إنشاء مصفوفة أعداد صحيحة ثنائية الأبعاد مع تخصيص البيانات الافتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| صفوف | int | عدد الصفوف في المصفوفة الثنائية الأبعاد |
| أعمدة | int | عدد الأعمدة في المصفوفة الثنائية الأبعاد |

### Int2D(int rows, int columns, int[] data) {#Int2D-int-int-int---}
```
public Int2D(int rows, int columns, int[] data)
```


إنشاء مصفوفة أعداد صحيحة ثنائية الأبعاد بالبيانات المعطاة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| صفوف | int | عدد الصفوف في المصفوفة الثنائية الأبعاد |
| أعمدة | int | عدد الأعمدة في المصفوفة الثنائية الأبعاد |
| بيانات | int[] | المصفوفة التي سيتم تغليفها، سيستخدم Float2D هذه المصفوفة داخليًا. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int r, int c) {#get-int-int-}
```
public int get(int r, int c)
```


يسترجع العنصر في الموضع المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| r | int | صف |
| c | int | عمود |

**Returns:**
int - القيمة في الموضع المحدد
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumns() {#getColumns--}
```
public int getColumns()
```




**Returns:**
int
### getLength(int rank) {#getLength-int-}
```
public int getLength(int rank)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الرتبة | int |  |

**Returns:**
int
### getRows() {#getRows--}
```
public int getRows()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### length() {#length--}
```
public int length()
```


يسترجع الطول الكلي لهذه المصفوفة الثنائية الأبعاد

**Returns:**
int - العدد الكلي للـ floats في هذه المصفوفة الثنائية الأبعاد.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### set(int r, int c, int v) {#set-int-int-int-}
```
public void set(int r, int c, int v)
```


يعيّن العنصر في الموضع المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| r | int | صف |
| c | int | عمود |
| v | int | القيمة |

### toString() {#toString--}
```
public String toString()
```




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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

