---
title: "ApertureMode"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Modes d'ouverture de la caméra."
type: docs
weight: 264
url: /fr/java/com.aspose.threed/aperturemode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ApertureMode extends Enum<ApertureMode>
```

Modes d'ouverture de la caméra. Le mode d'ouverture détermine quelles valeurs contrôlent l'ouverture de la caméra. Si le mode d'ouverture est HorizAndVert, Horizontal ou Vertical, alors le champ de vision est utilisé. Si le mode d'ouverture est FocalLength, alors la distance focale est utilisée.
## Champs

| Champ | Description |
| --- | --- |
| [FOCAL_LENGTH](#FOCAL-LENGTH) | Utilisez la distance focale directement. |
| [HORIZONTAL](#HORIZONTAL) | Définissez uniquement l'angle horizontal. |
| [HORIZ_AND_VERT](#HORIZ-AND-VERT) | Définissez les valeurs d'angle pour les réglages horizontal et vertical. |
| [VERTICAL](#VERTICAL) | Définissez uniquement l'angle vertical. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FOCAL_LENGTH {#FOCAL-LENGTH}
```
public static final ApertureMode FOCAL_LENGTH
```


Utilisez la distance focale directement.

### HORIZONTAL {#HORIZONTAL}
```
public static final ApertureMode HORIZONTAL
```


Définissez uniquement l'angle horizontal.

### HORIZ_AND_VERT {#HORIZ-AND-VERT}
```
public static final ApertureMode HORIZ_AND_VERT
```


Définissez les valeurs d'angle pour les réglages horizontal et vertical.

### VERTICAL {#VERTICAL}
```
public static final ApertureMode VERTICAL
```


Définissez uniquement l'angle vertical.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ApertureMode valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[ApertureMode](../../com.aspose.threed/aperturemode)
### values() {#values--}
```
public static ApertureMode[] values()
```




**Returns:**
com.aspose.threed.ApertureMode[]
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

