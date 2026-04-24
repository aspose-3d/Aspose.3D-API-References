---
title: Interpolatie
second_title: Aspose.3D for Java API-referentie
description: Het interpolatietype van de keyframes.
type: docs
weight: 283
url: /nl/java/com.aspose.threed/interpolation/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Interpolation extends Enum<Interpolation>
```

Het interpolatietype van de keyframe.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [BEZIER](#BEZIER) | Een Bézier- of Hermite‑splines. |
| [B_SPLINE](#B-SPLINE) | Basis-splines worden gedefinieerd door een reeks controlepunten, waarvoor de curve gegarandeerd alleen door het eerste en het laatste punt loopt. |
| [CARDINAL_SPLINE](#CARDINAL-SPLINE) | Een cardinal spline is een kubieke Hermite spline waarvan de tangenten worden gedefinieerd door de eindpunten en een spanningparameter. |
| [CONSTANT](#CONSTANT) | De waarde blijft constant gelijk aan de waarde van het eerste punt tot het volgende segment. |
| [LINEAR](#LINEAR) | Lineaire interpolatie is een rechte lijn tussen twee punten. |
| [TCB_SPLINE](#TCB-SPLINE) | Ook wel Kochanek-Bartels spline genoemd, wordt het gedrag van de tangent gedefinieerd door spanning/bias/continuïteit |
## Methoden

| Methode | Beschrijving |
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


Een Bézier- of Hermite‑splines.

### B_SPLINE {#B-SPLINE}
```
public static final Interpolation B_SPLINE
```


Basis-splines worden gedefinieerd door een reeks controlepunten, waarvoor de curve gegarandeerd alleen door het eerste en het laatste punt loopt.

### CARDINAL_SPLINE {#CARDINAL-SPLINE}
```
public static final Interpolation CARDINAL_SPLINE
```


Een cardinal spline is een kubieke Hermite spline waarvan de tangenten worden gedefinieerd door de eindpunten en een spanningparameter.

### CONSTANT {#CONSTANT}
```
public static final Interpolation CONSTANT
```


De waarde blijft constant gelijk aan de waarde van het eerste punt tot het volgende segment.

### LINEAR {#LINEAR}
```
public static final Interpolation LINEAR
```


Lineaire interpolatie is een rechte lijn tussen twee punten.

### TCB_SPLINE {#TCB-SPLINE}
```
public static final Interpolation TCB_SPLINE
```


Ook wel Kochanek-Bartels spline genoemd, wordt het gedrag van de tangent gedefinieerd door spanning/bias/continuïteit

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

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

