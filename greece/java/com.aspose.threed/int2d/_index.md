---
title: Int2D
second_title: Aspose.3D for Java API Reference
description: Δημιουργήθηκε από lexchou στις 5/17/2017.
type: docs
weight: 86
url: /el/java/com.aspose.threed/int2d/
---

**Inheritance:**
java.lang.Object
```
public final class Int2D
```

Δημιουργήθηκε από τον lexchou στις 5/17/2017. Περιτύλιγμα πίνακα ακεραίων 2 διαστάσεων
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Int2D(int rows, int columns)](#Int2D-int-int-) | Δημιουργήστε έναν 2D πίνακα ακεραίων με προεπιλεγμένη κατανομή δεδομένων. |
| [Int2D(int rows, int columns, int[] data)](#Int2D-int-int-int---) | Δημιουργήστε έναν 2D πίνακα ακεραίων με δεδομένα που παρέχονται |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int r, int c)](#get-int-int-) | Λαμβάνει το στοιχείο στη συγκεκριμένη θέση |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) |  |
| [getLength(int rank)](#getLength-int-) |  |
| [getRows()](#getRows--) |  |
| [hashCode()](#hashCode--) |  |
| [length()](#length--) | Λαμβάνει το συνολικό μήκος αυτού του 2d πίνακα |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(int r, int c, int v)](#set-int-int-int-) | Ορίζει το στοιχείο στη συγκεκριμένη θέση |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Int2D(int rows, int columns) {#Int2D-int-int-}
```
public Int2D(int rows, int columns)
```


Δημιουργήστε έναν 2D πίνακα ακεραίων με προεπιλεγμένη κατανομή δεδομένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γραμμές | int | Αριθμός γραμμών του 2D πίνακα |
| στήλες | int | Αριθμός στηλών του 2D πίνακα |

### Int2D(int rows, int columns, int[] data) {#Int2D-int-int-int---}
```
public Int2D(int rows, int columns, int[] data)
```


Δημιουργήστε έναν 2D πίνακα ακεραίων με δεδομένα που παρέχονται

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γραμμές | int | Αριθμός γραμμών του 2D πίνακα |
| στήλες | int | Αριθμός στηλών του 2D πίνακα |
| δεδομένα | int[] | Πίνακας για περιτύλιξη, το Float2D θα χρησιμοποιήσει αυτόν τον πίνακα εσωτερικά. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int r, int c) {#get-int-int-}
```
public int get(int r, int c)
```


Λαμβάνει το στοιχείο στη συγκεκριμένη θέση

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| r | int | Γραμμή |
| c | int | Στήλη |

**Returns:**
int - η τιμή στη συγκεκριμένη θέση
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| βαθμός | int |  |

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


Λαμβάνει το συνολικό μήκος αυτού του 2d πίνακα

**Returns:**
int - ο συνολικός αριθμός των float σε αυτόν τον 2d πίνακα.
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


Ορίζει το στοιχείο στη συγκεκριμένη θέση

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| r | int | Γραμμή |
| c | int | Στήλη |
| v | int | Τιμή |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

