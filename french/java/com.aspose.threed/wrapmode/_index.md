---
title: "WrapMode"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Mode d'enveloppement des textures."
type: docs
weight: 310
url: /fr/java/com.aspose.threed/wrapmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum WrapMode extends Enum<WrapMode>
```

Mode d'enroulement de la texture.
## Champs

| Champ | Description |
| --- | --- |
| [BORDER](#BORDER) | Les coordonnées qui sont en dehors de la plage [0.0, 1.0] sont définies à une couleur de bordure spécifiée. |
| [CLAMP](#CLAMP) | Contraint la texture au dernier pixel à la bordure. |
| [MIRROR](#MIRROR) | La texture sera répétée, mais elle sera miroir lorsque la partie entière de la coordonnée est impaire. |
| [MIRROR_ONCE](#MIRROR-ONCE) | La texture sera miroir une fois, puis sera contrainte à la valeur maximale. |
| [WRAP](#WRAP) | Mosaïquage de la texture sur la surface du modèle, créant un motif répétitif. |
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
### BORDER {#BORDER}
```
public static final WrapMode BORDER
```


Les coordonnées qui sont en dehors de la plage [0.0, 1.0] sont définies à une couleur de bordure spécifiée.

### CLAMP {#CLAMP}
```
public static final WrapMode CLAMP
```


Contraint la texture au dernier pixel à la bordure.

### MIRROR {#MIRROR}
```
public static final WrapMode MIRROR
```


La texture sera répétée, mais elle sera miroir lorsque la partie entière de la coordonnée est impaire.

### MIRROR_ONCE {#MIRROR-ONCE}
```
public static final WrapMode MIRROR_ONCE
```


La texture sera miroir une fois, puis sera contrainte à la valeur maximale.

### WRAP {#WRAP}
```
public static final WrapMode WRAP
```


Mosaïquage de la texture sur la surface du modèle, créant un motif répétitif.

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
public static WrapMode valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode)
### values() {#values--}
```
public static WrapMode[] values()
```




**Returns:**
com.aspose.threed.WrapMode[]
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

