---
title: Int2D
second_title: Aspose.3D for Java API-referens
description: Skapat av lexchou den 2017-05-17.
type: docs
weight: 86
url: /sv/java/com.aspose.threed/int2d/
---

**Inheritance:**
java.lang.Object
```
public final class Int2D
```

Skapad av lexchou den 5/17/2017. 2-dimensionell int‑array‑omslag
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Int2D(int rows, int columns)](#Int2D-int-int-) | Skapa en 2D int‑array med standarddatatilldelning. |
| [Int2D(int rows, int columns, int[] data)](#Int2D-int-int-int---) | Skapa en 2D int‑array med given data |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int r, int c)](#get-int-int-) | Hämtar elementet på angiven position |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) |  |
| [getLength(int rank)](#getLength-int-) |  |
| [getRows()](#getRows--) |  |
| [hashCode()](#hashCode--) |  |
| [length()](#length--) | Hämtar den totala längden på denna 2d-array |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(int r, int c, int v)](#set-int-int-int-) | Sätter elementet på angiven position |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Int2D(int rows, int columns) {#Int2D-int-int-}
```
public Int2D(int rows, int columns)
```


Skapa en 2D int‑array med standarddatatilldelning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rader | int | Antal rader i 2D-arrayen |
| kolumner | int | Antal kolumner i 2D-arrayen |

### Int2D(int rows, int columns, int[] data) {#Int2D-int-int-int---}
```
public Int2D(int rows, int columns, int[] data)
```


Skapa en 2D int‑array med given data

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rader | int | Antal rader i 2D-arrayen |
| kolumner | int | Antal kolumner i 2D-arrayen |
| data | int[] | Array att omsluta, Float2D kommer att använda denna array internt. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int r, int c) {#get-int-int-}
```
public int get(int r, int c)
```


Hämtar elementet på angiven position

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| r | int | Rad |
| c | int | Kolumn |

**Returns:**
int - värdet på angiven position
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rang | int |  |

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


Hämtar den totala längden på denna 2d-array

**Returns:**
int - det totala antalet flyttal i denna 2d-array.
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


Sätter elementet på angiven position

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| r | int | Rad |
| c | int | Kolumn |
| v | int | Värde |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

