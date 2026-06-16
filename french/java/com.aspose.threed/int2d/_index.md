---
title: "Int2D"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Créé par lexchou le 17/05/2017."
type: docs
weight: 86
url: /fr/java/com.aspose.threed/int2d/
---

**Inheritance:**
java.lang.Object
```
public final class Int2D
```

Créé par lexchou le 17/05/2017. Wrapper de tableau d'entiers à 2 dimensions
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Int2D(int rows, int columns)](#Int2D-int-int-) | Construire un tableau d'entiers 2D avec allocation de données par défaut. |
| [Int2D(int rows, int columns, int[] data)](#Int2D-int-int-int---) | Construire un tableau d'entiers 2D avec les données fournies |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int r, int c)](#get-int-int-) | Obtient l'élément à la position spécifiée |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) |  |
| [getLength(int rank)](#getLength-int-) |  |
| [getRows()](#getRows--) |  |
| [hashCode()](#hashCode--) |  |
| [length()](#length--) | Obtient la longueur totale de ce tableau 2d |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(int r, int c, int v)](#set-int-int-int-) | Définit l'élément à la position spécifiée |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Int2D(int rows, int columns) {#Int2D-int-int-}
```
public Int2D(int rows, int columns)
```


Construire un tableau d'entiers 2D avec allocation de données par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lignes | int | Nombre de lignes du tableau 2D |
| colonnes | int | Nombre de colonnes du tableau 2D |

### Int2D(int rows, int columns, int[] data) {#Int2D-int-int-int---}
```
public Int2D(int rows, int columns, int[] data)
```


Construire un tableau d'entiers 2D avec les données fournies

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lignes | int | Nombre de lignes du tableau 2D |
| colonnes | int | Nombre de colonnes du tableau 2D |
| données | int[] | Tableau à encapsuler, Float2D utilisera ce tableau en interne. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int r, int c) {#get-int-int-}
```
public int get(int r, int c)
```


Obtient l'élément à la position spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| r | int | Ligne |
| c | int | Colonne |

**Returns:**
int - la valeur à la position spécifiée
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
| Paramètre | Type | Description |
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


Obtient la longueur totale de ce tableau 2d

**Returns:**
int - le nombre total de flottants dans ce tableau 2d.
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


Définit l'élément à la position spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| r | int | Ligne |
| c | int | Colonne |
| v | int | Valeur |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

