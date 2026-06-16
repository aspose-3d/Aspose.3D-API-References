---
title: "Interpolation"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Le type d'interpolation des images clés."
type: docs
weight: 283
url: /fr/java/com.aspose.threed/interpolation/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Interpolation extends Enum<Interpolation>
```

Le type d'interpolation de la trame clé.
## Champs

| Champ | Description |
| --- | --- |
| [BEZIER](#BEZIER) | Une spline Bézier ou Hermite. |
| [B_SPLINE](#B-SPLINE) | Les splines de base sont définies par une série de points de contrôle, pour lesquels la courbe ne passe que par le premier et le dernier point. |
| [CARDINAL_SPLINE](#CARDINAL-SPLINE) | Un cardinal spline est un spline cubique de Hermite dont les tangentes sont définies par les points d'extrémité et un paramètre de tension. |
| [CONSTANT](#CONSTANT) | La valeur restera constante à la valeur du premier point jusqu'au segment suivant. |
| [LINEAR](#LINEAR) | L'interpolation linéaire est une ligne droite entre deux points. |
| [TCB_SPLINE](#TCB-SPLINE) | Également appelé spline de Kochanek-Bartels, le comportement de la tangente est défini par tension/biais/continuité |
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
### BEZIER {#BEZIER}
```
public static final Interpolation BEZIER
```


Une spline Bézier ou Hermite.

### B_SPLINE {#B-SPLINE}
```
public static final Interpolation B_SPLINE
```


Les splines de base sont définies par une série de points de contrôle, pour lesquels la courbe ne passe que par le premier et le dernier point.

### CARDINAL_SPLINE {#CARDINAL-SPLINE}
```
public static final Interpolation CARDINAL_SPLINE
```


Un cardinal spline est un spline cubique de Hermite dont les tangentes sont définies par les points d'extrémité et un paramètre de tension.

### CONSTANT {#CONSTANT}
```
public static final Interpolation CONSTANT
```


La valeur restera constante à la valeur du premier point jusqu'au segment suivant.

### LINEAR {#LINEAR}
```
public static final Interpolation LINEAR
```


L'interpolation linéaire est une ligne droite entre deux points.

### TCB_SPLINE {#TCB-SPLINE}
```
public static final Interpolation TCB_SPLINE
```


Également appelé spline de Kochanek-Bartels, le comportement de la tangente est défini par tension/biais/continuité

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
public static Interpolation valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[Interpolation](../../com.aspose.threed/interpolation)
### values() {#values--}
```
public static Interpolation[] values()
```




**Returns:**
com.aspose.threed.Interpolation[]
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

