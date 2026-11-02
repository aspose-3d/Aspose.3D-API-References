---
title: "PdfRenderMode"
second_title: "Aspose.3D for Java API Referansı"
description: "Render modu, 3D sanat eserinin render edildiği stili belirtir."
type: docs
weight: 289
url: /tr/java/com.aspose.threed/pdfrendermode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PdfRenderMode extends Enum<PdfRenderMode>
```

Render modu, 3D sanat eserinin render edildiği stili belirtir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [BOUNDING_BOX](#BOUNDING-BOX) | Her düğümün sınırlayıcı kutu kenarlarını, o düğümün yerel koordinat uzayının eksenlerine hizalanmış şekilde gösterir. |
| [HIDDEN_WIREFRAME](#HIDDEN-WIREFRAME) | Kenarları tek bir renkte gösterir, ancak geri yönlü ve gizlenmiş kenarları kaldırır. |
| [ILLUSTRATION](#ILLUSTRATION) | Silüet kenarlarını yüzeylerle birlikte gösterir, gizlenmiş çizgileri kaldırır. |
| [SHADED_ILLUSTRATION](#SHADED-ILLUSTRATION) | Aydınlatılmış ve dokulu yüzeylerle silüet kenarlarını gösterir ve yetersiz aydınlatılmış alanları kaldırmak için ek bir ışınım terimi ekler. |
| [SHADED_VERTICES](#SHADED-VERTICES) | Yalnızca köşe noktalarını gösterir, ancak köşe renklerini kullanır ve aydınlatma uygular. |
| [SHADED_WIREFRAME](#SHADED-WIREFRAME) | Yalnızca kenarları gösterir, ancak renklerini iki köşe arasında ara değer alarak belirler ve aydınlatma uygular. |
| [SOLID](#SOLID) | Doku ve aydınlatmalı geometrik şekilleri gösterir. |
| [SOLID_OUTLINE](#SOLID-OUTLINE) | Aydınlatılmış ve dokulu yüzeylerle silüet kenarlarını gösterir, gizlenmiş çizgileri kaldırır. |
| [SOLID_WIREFRAME](#SOLID-WIREFRAME) | Doku ve aydınlatmalı geometrik şekilleri (üçgenler) tek renk kenarlarla üstünde gösterir. |
| [TRANSPARENT](#TRANSPARENT) | Doku ve aydınlatmalı geometrik şekilleri (üçgenler) ek bir şeffaflık seviyesiyle gösterir. |
| [TRANSPARENT_BOUNDING_BOX](#TRANSPARENT-BOUNDING-BOX) | Her düğümün sınırlayıcı kutu yüzeylerini, yerel koordinat uzayının eksenlerine hizalanmış şekilde ve ek bir şeffaflık seviyesiyle gösterir. |
| [TRANSPARENT_BOUNDING_BOX_OUTLINE](#TRANSPARENT-BOUNDING-BOX-OUTLINE) | Her düğümün sınırlayıcı kutu kenarlarını ve yüzeylerini, yerel koordinat uzayının eksenlerine hizalanmış şekilde ve ek bir şeffaflık seviyesiyle gösterir. |
| [TRANSPARENT_WIREFRAME](#TRANSPARENT-WIREFRAME) | Doku ve aydınlatmalı geometrik şekilleri (üçgenler) ek bir şeffaflık seviyesiyle ve üstünde tek renk opak kenarlarla gösterir. |
| [VERTICES](#VERTICES) | Yalnızca köşe noktalarını tek bir renkte gösterir. |
| [WIREFRAME](#WIREFRAME) | Yalnızca kenarları tek bir renkte gösterir. |
## Yöntemler

| Yöntem | Açıklama |
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
### BOUNDING_BOX {#BOUNDING-BOX}
```
public static final PdfRenderMode BOUNDING_BOX
```


Her düğümün sınırlayıcı kutu kenarlarını, o düğümün yerel koordinat uzayının eksenlerine hizalanmış şekilde gösterir.

### HIDDEN_WIREFRAME {#HIDDEN-WIREFRAME}
```
public static final PdfRenderMode HIDDEN_WIREFRAME
```


Kenarları tek bir renkte gösterir, ancak geri yönlü ve gizlenmiş kenarları kaldırır.

### ILLUSTRATION {#ILLUSTRATION}
```
public static final PdfRenderMode ILLUSTRATION
```


Silüet kenarlarını yüzeylerle birlikte gösterir, gizlenmiş çizgileri kaldırır.

### SHADED_ILLUSTRATION {#SHADED-ILLUSTRATION}
```
public static final PdfRenderMode SHADED_ILLUSTRATION
```


Aydınlatılmış ve dokulu yüzeylerle silüet kenarlarını gösterir ve yetersiz aydınlatılmış alanları kaldırmak için ek bir ışınım terimi ekler.

### SHADED_VERTICES {#SHADED-VERTICES}
```
public static final PdfRenderMode SHADED_VERTICES
```


Yalnızca köşe noktalarını gösterir, ancak köşe renklerini kullanır ve aydınlatma uygular.

### SHADED_WIREFRAME {#SHADED-WIREFRAME}
```
public static final PdfRenderMode SHADED_WIREFRAME
```


Yalnızca kenarları gösterir, ancak renklerini iki köşe arasında ara değer alarak belirler ve aydınlatma uygular.

### SOLID {#SOLID}
```
public static final PdfRenderMode SOLID
```


Doku ve aydınlatmalı geometrik şekilleri gösterir.

### SOLID_OUTLINE {#SOLID-OUTLINE}
```
public static final PdfRenderMode SOLID_OUTLINE
```


Aydınlatılmış ve dokulu yüzeylerle silüet kenarlarını gösterir, gizlenmiş çizgileri kaldırır.

### SOLID_WIREFRAME {#SOLID-WIREFRAME}
```
public static final PdfRenderMode SOLID_WIREFRAME
```


Doku ve aydınlatmalı geometrik şekilleri (üçgenler) tek renk kenarlarla üstünde gösterir.

### TRANSPARENT {#TRANSPARENT}
```
public static final PdfRenderMode TRANSPARENT
```


Doku ve aydınlatmalı geometrik şekilleri (üçgenler) ek bir şeffaflık seviyesiyle gösterir.

### TRANSPARENT_BOUNDING_BOX {#TRANSPARENT-BOUNDING-BOX}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX
```


Her düğümün sınırlayıcı kutu yüzeylerini, yerel koordinat uzayının eksenlerine hizalanmış şekilde ve ek bir şeffaflık seviyesiyle gösterir.

### TRANSPARENT_BOUNDING_BOX_OUTLINE {#TRANSPARENT-BOUNDING-BOX-OUTLINE}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX_OUTLINE
```


Her düğümün sınırlayıcı kutu kenarlarını ve yüzeylerini, yerel koordinat uzayının eksenlerine hizalanmış şekilde ve ek bir şeffaflık seviyesiyle gösterir.

### TRANSPARENT_WIREFRAME {#TRANSPARENT-WIREFRAME}
```
public static final PdfRenderMode TRANSPARENT_WIREFRAME
```


Doku ve aydınlatmalı geometrik şekilleri (üçgenler) ek bir şeffaflık seviyesiyle ve üstünde tek renk opak kenarlarla gösterir.

### VERTICES {#VERTICES}
```
public static final PdfRenderMode VERTICES
```


Yalnızca köşe noktalarını tek bir renkte gösterir.

### WIREFRAME {#WIREFRAME}
```
public static final PdfRenderMode WIREFRAME
```


Yalnızca kenarları tek bir renkte gösterir.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
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
public static PdfRenderMode valueOf(String name)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
[PdfRenderMode](../../com.aspose.threed/pdfrendermode)
### values() {#values--}
```
public static PdfRenderMode[] values()
```




**Returns:**
com.aspose.threed.PdfRenderMode[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

