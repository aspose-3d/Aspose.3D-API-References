---
title: "Int2D"
second_title: "Aspose.3D for Java API Referansı"
description: "5/17/2017 tarihinde lexchou tarafından oluşturuldu."
type: docs
weight: 86
url: /tr/java/com.aspose.threed/int2d/
---

**Inheritance:**
java.lang.Object
```
public final class Int2D
```

lexchou tarafından 5/17/2017 tarihinde oluşturuldu. 2 boyutlu int dizi sarmalayıcısı
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Int2D(int rows, int columns)](#Int2D-int-int-) | Varsayılan veri tahsisiyle bir 2D int dizisi oluştur. |
| [Int2D(int rows, int columns, int[] data)](#Int2D-int-int-int---) | Verilen veriyle bir 2D int dizisi oluştur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int r, int c)](#get-int-int-) | Belirtilen konumdaki öğeyi alır |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) |  |
| [getLength(int rank)](#getLength-int-) |  |
| [getRows()](#getRows--) |  |
| [hashCode()](#hashCode--) |  |
| [length()](#length--) | Bu 2D dizinin toplam uzunluğunu alır |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(int r, int c, int v)](#set-int-int-int-) | Belirtilen konumdaki öğeyi ayarlar |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Int2D(int rows, int columns) {#Int2D-int-int-}
```
public Int2D(int rows, int columns)
```


Varsayılan veri tahsisiyle bir 2D int dizisi oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| satırlar | int | 2D dizinin satır sayısı |
| sütunlar | int | 2D dizinin sütun sayısı |

### Int2D(int rows, int columns, int[] data) {#Int2D-int-int-int---}
```
public Int2D(int rows, int columns, int[] data)
```


Verilen veriyle bir 2D int dizisi oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| satırlar | int | 2D dizinin satır sayısı |
| sütunlar | int | 2D dizinin sütun sayısı |
| veri | int[] | Sarılan dizi, Float2D bu diziyi dahili olarak kullanacaktır. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int r, int c) {#get-int-int-}
```
public int get(int r, int c)
```


Belirtilen konumdaki öğeyi alır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| r | int | Satır |
| c | int | Sütun |

**Returns:**
int - belirtilen konumdaki değer
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| derece | int |  |

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


Bu 2D dizinin toplam uzunluğunu alır

**Returns:**
int - bu 2D dizideki toplam float sayısı.
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


Belirtilen konumdaki öğeyi ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| r | int | Satır |
| c | int | Sütun |
| v | int | Değer |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

