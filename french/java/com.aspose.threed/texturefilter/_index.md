---
title: "TextureFilter"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Options de filtrage lors de l'échantillonnage de texture."
type: docs
weight: 305
url: /fr/java/com.aspose.threed/texturefilter/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextureFilter extends Enum<TextureFilter>
```

Options de filtrage lors de l'échantillonnage de texture.
## Champs

| Champ | Description |
| --- | --- |
| [ANISOTROPIC](#ANISOTROPIC) | Utilisez l'interpolation anisotrope pour l'échantillonnage, cela n'est utilisé que par le filtre de minification. |
| [LINEAR](#LINEAR) | Utilisez l'interpolation linéaire pour l'échantillonnage |
| [NONE](#NONE) | Pas de minification, cela n'est utilisé que par le filtre de minification. |
| [POINT](#POINT) | Utilisez l'échantillonnage ponctuel |
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
### ANISOTROPIC {#ANISOTROPIC}
```
public static final TextureFilter ANISOTROPIC
```


Utilisez l'interpolation anisotrope pour l'échantillonnage, cela n'est utilisé que par le filtre de minification.

### LINEAR {#LINEAR}
```
public static final TextureFilter LINEAR
```


Utilisez l'interpolation linéaire pour l'échantillonnage

### NONE {#NONE}
```
public static final TextureFilter NONE
```


Pas de minification, cela n'est utilisé que par le filtre de minification.

### POINT {#POINT}
```
public static final TextureFilter POINT
```


Utilisez l'échantillonnage ponctuel

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
public static TextureFilter valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter)
### values() {#values--}
```
public static TextureFilter[] values()
```




**Returns:**
com.aspose.threed.TextureFilter[]
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

