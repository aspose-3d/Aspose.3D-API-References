---
title: "StencilAction"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Les actions du test de pochoir"
type: docs
weight: 303
url: /fr/java/com.aspose.threed/stencilaction/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum StencilAction extends Enum<StencilAction>
```

Les actions du test de pochoir
## Champs

| Champ | Description |
| --- | --- |
| [DECREMENT](#DECREMENT) | Incrémente la valeur actuelle du tampon de pochoir, limite à 0. |
| [DECREMENT_WRAP](#DECREMENT-WRAP) | Décrémente la valeur actuelle du tampon de pochoir et la ramène à la valeur maximale lorsqu'elle atteint zéro. |
| [INCREMENT](#INCREMENT) | Incrémente la valeur actuelle du tampon de pochoir, limite à la valeur maximale. |
| [INCREMENT_WRAP](#INCREMENT-WRAP) | Incrémente la valeur actuelle du tampon de pochoir et la ramène à zéro lorsqu'elle atteint la valeur maximale. |
| [INVERT](#INVERT) | Inverse bit à bit la valeur actuelle du tampon de pochoir. |
| [KEEP](#KEEP) | Conserve la valeur actuelle |
| [REPLACE](#REPLACE) | Définit le tampon de pochoir à ref tel que défini dans [RenderState.getStencilReference](../../com.aspose.threed/renderstate\#getStencilReference) |
| [ZERO](#ZERO) | Définit la valeur du tampon de pochoir à 0 |
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
### DECREMENT {#DECREMENT}
```
public static final StencilAction DECREMENT
```


Incrémente la valeur actuelle du tampon de pochoir, limite à 0.

### DECREMENT_WRAP {#DECREMENT-WRAP}
```
public static final StencilAction DECREMENT_WRAP
```


Décrémente la valeur actuelle du tampon de pochoir et la ramène à la valeur maximale lorsqu'elle atteint zéro.

### INCREMENT {#INCREMENT}
```
public static final StencilAction INCREMENT
```


Incrémente la valeur actuelle du tampon de pochoir, limite à la valeur maximale.

### INCREMENT_WRAP {#INCREMENT-WRAP}
```
public static final StencilAction INCREMENT_WRAP
```


Incrémente la valeur actuelle du tampon de pochoir et la ramène à zéro lorsqu'elle atteint la valeur maximale.

### INVERT {#INVERT}
```
public static final StencilAction INVERT
```


Inverse bit à bit la valeur actuelle du tampon de pochoir.

### KEEP {#KEEP}
```
public static final StencilAction KEEP
```


Conserve la valeur actuelle

### REPLACE {#REPLACE}
```
public static final StencilAction REPLACE
```


Définit le tampon de pochoir à ref tel que défini dans [RenderState.getStencilReference](../../com.aspose.threed/renderstate\#getStencilReference)

### ZERO {#ZERO}
```
public static final StencilAction ZERO
```


Définit la valeur du tampon de pochoir à 0

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
public static StencilAction valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction)
### values() {#values--}
```
public static StencilAction[] values()
```




**Returns:**
com.aspose.threed.StencilAction[]
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

