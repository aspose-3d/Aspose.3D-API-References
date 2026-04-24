---
title: Int2D
second_title: Aspose.3D for Java API-referentie
description: Gemaakt door lexchou op 17-5-2017.
type: docs
weight: 86
url: /nl/java/com.aspose.threed/int2d/
---

**Inheritance:**
java.lang.Object
```
public final class Int2D
```

Gemaakt door lexchou op 5/17/2017. 2-dimensionale int-array wrapper
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Int2D(int rows, int columns)](#Int2D-int-int-) | Construeer een 2D int-array met standaard gegevensallocatie. |
| [Int2D(int rows, int columns, int[] data)](#Int2D-int-int-int---) | Construeer een 2D int-array met opgegeven gegevens |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int r, int c)](#get-int-int-) | Haalt het element op op de opgegeven positie |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) |  |
| [getLength(int rank)](#getLength-int-) |  |
| [getRows()](#getRows--) |  |
| [hashCode()](#hashCode--) |  |
| [length()](#length--) | Haalt de totale lengte van deze 2D-array op |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(int r, int c, int v)](#set-int-int-int-) | Stelt het element in op de opgegeven positie |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Int2D(int rows, int columns) {#Int2D-int-int-}
```
public Int2D(int rows, int columns)
```


Construeer een 2D int-array met standaard gegevensallocatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rijen | int | Aantal rijen van de 2D-array |
| kolommen | int | Aantal kolommen van de 2D-array |

### Int2D(int rows, int columns, int[] data) {#Int2D-int-int-int---}
```
public Int2D(int rows, int columns, int[] data)
```


Construeer een 2D int-array met opgegeven gegevens

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rijen | int | Aantal rijen van de 2D-array |
| kolommen | int | Aantal kolommen van de 2D-array |
| gegevens | int[] | Array om te omhullen, Float2D zal deze array intern gebruiken. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int r, int c) {#get-int-int-}
```
public int get(int r, int c)
```


Haalt het element op op de opgegeven positie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| r | int | Rij |
| c | int | Kolom |

**Returns:**
int - de waarde op de opgegeven positie
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
| Parameter | Type | Beschrijving |
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


Haalt de totale lengte van deze 2D-array op

**Returns:**
int - het totale aantal floats in deze 2D-array.
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


Stelt het element in op de opgegeven positie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| r | int | Rij |
| c | int | Kolom |
| v | int | Waarde |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

