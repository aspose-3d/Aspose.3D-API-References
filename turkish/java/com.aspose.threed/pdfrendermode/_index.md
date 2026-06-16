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
| [BOUNDING_BOX](#BOUNDING-BOX) | Her düğümün sınırlayıcı kutu kenarlarını, o düğümün yerel koordinat uzayının eksenlerine hizalanmış şekilde görüntüler. |
| [HIDDEN_WIREFRAME](#HIDDEN-WIREFRAME) | Kenarlıkları tek bir renkte görüntüler, ancak geri yönlü ve gizlenmiş kenarları kaldırır. |
| [ILLUSTRATION](#ILLUSTRATION) | Silüet kenarlarını yüzeylerle birlikte görüntüler, gizlenmiş çizgileri kaldırır. |
| [SHADED_ILLUSTRATION](#SHADED-ILLUSTRATION) | Aydınlatılmış ve dokulu yüzeylerle birlikte silüet kenarlarını görüntüler ve eser üzerindeki yetersiz aydınlatılmış alanları kaldırmak için ek bir yayılımlı terim ekler. |
| [SHADED_VERTICES](#SHADED-VERTICES) | Yalnızca köşe noktalarını görüntüler, ancak köşe renklerini kullanır ve aydınlatma uygular. |
| [SHADED_WIREFRAME](#SHADED-WIREFRAME) | Yalnızca kenarları görüntüler, ancak renklerini iki köşe arasında ara değer alarak ve aydınlatma uygular. |
| [SOLID](#SOLID) | Dokulu ve aydınlatılmış geometrik şekilleri görüntüler. |
| [SOLID_OUTLINE](#SOLID-OUTLINE) | Aydınlatılmış ve dokulu yüzeylerle birlikte silüet kenarlarını görüntüler, gizlenmiş çizgileri kaldırır. |
| [SOLID_WIREFRAME](#SOLID-WIREFRAME) | Dokulu ve aydınlatılmış geometrik şekilleri (üçgenler) tek renk kenarlarla üstünde görüntüler. |
| [TRANSPARENT](#TRANSPARENT) | Dokulu ve aydınlatılmış geometrik şekilleri (üçgenler) ek bir şeffaflık seviyesiyle görüntüler. |
| [TRANSPARENT_BOUNDING_BOX](#TRANSPARENT-BOUNDING-BOX) | Her düğümün sınırlayıcı kutu yüzeylerini, o düğümün yerel koordinat uzayının eksenlerine hizalanmış şekilde ve ek bir şeffaflık seviyesiyle görüntüler. |
| [TRANSPARENT_BOUNDING_BOX_OUTLINE](#TRANSPARENT-BOUNDING-BOX-OUTLINE) | Her düğümün sınırlayıcı kutu kenarlarını ve yüzeylerini, o düğümün yerel koordinat uzayının eksenlerine hizalanmış şekilde ve ek bir şeffaflık seviyesiyle görüntüler. |
| [TRANSPARENT_WIREFRAME](#TRANSPARENT-WIREFRAME) | Dokulu ve aydınlatılmış geometrik şekilleri (üçgenler) ek bir şeffaflık seviyesiyle ve üzerlerinde tek renk opak kenarlarla görüntüler. |
| [VERTICES](#VERTICES) | Yalnızca köşe noktalarını tek bir renkte görüntüler. |
| [WIREFRAME](#WIREFRAME) | Yalnızca kenarları tek bir renkte görüntüler. |
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


Her düğümün sınırlayıcı kutu kenarlarını, o düğümün yerel koordinat uzayının eksenlerine hizalanmış şekilde görüntüler.

### HIDDEN_WIREFRAME {#HIDDEN-WIREFRAME}
```
public static final PdfRenderMode HIDDEN_WIREFRAME
```


Kenarlıkları tek bir renkte görüntüler, ancak geri yönlü ve gizlenmiş kenarları kaldırır.

### ILLUSTRATION {#ILLUSTRATION}
```
public static final PdfRenderMode ILLUSTRATION
```


Silüet kenarlarını yüzeylerle birlikte görüntüler, gizlenmiş çizgileri kaldırır.

### SHADED_ILLUSTRATION {#SHADED-ILLUSTRATION}
```
public static final PdfRenderMode SHADED_ILLUSTRATION
```


Aydınlatılmış ve dokulu yüzeylerle birlikte silüet kenarlarını görüntüler ve eser üzerindeki yetersiz aydınlatılmış alanları kaldırmak için ek bir yayılımlı terim ekler.

### SHADED_VERTICES {#SHADED-VERTICES}
```
public static final PdfRenderMode SHADED_VERTICES
```


Yalnızca köşe noktalarını görüntüler, ancak köşe renklerini kullanır ve aydınlatma uygular.

### SHADED_WIREFRAME {#SHADED-WIREFRAME}
```
public static final PdfRenderMode SHADED_WIREFRAME
```


Yalnızca kenarları görüntüler, ancak renklerini iki köşe arasında ara değer alarak ve aydınlatma uygular.

### SOLID {#SOLID}
```
public static final PdfRenderMode SOLID
```


Dokulu ve aydınlatılmış geometrik şekilleri görüntüler.

### SOLID_OUTLINE {#SOLID-OUTLINE}
```
public static final PdfRenderMode SOLID_OUTLINE
```


Aydınlatılmış ve dokulu yüzeylerle birlikte silüet kenarlarını görüntüler, gizlenmiş çizgileri kaldırır.

### SOLID_WIREFRAME {#SOLID-WIREFRAME}
```
public static final PdfRenderMode SOLID_WIREFRAME
```


Dokulu ve aydınlatılmış geometrik şekilleri (üçgenler) tek renk kenarlarla üstünde görüntüler.

### TRANSPARENT {#TRANSPARENT}
```
public static final PdfRenderMode TRANSPARENT
```


Dokulu ve aydınlatılmış geometrik şekilleri (üçgenler) ek bir şeffaflık seviyesiyle görüntüler.

### TRANSPARENT_BOUNDING_BOX {#TRANSPARENT-BOUNDING-BOX}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX
```


Her düğümün sınırlayıcı kutu yüzeylerini, o düğümün yerel koordinat uzayının eksenlerine hizalanmış şekilde ve ek bir şeffaflık seviyesiyle görüntüler.

### TRANSPARENT_BOUNDING_BOX_OUTLINE {#TRANSPARENT-BOUNDING-BOX-OUTLINE}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX_OUTLINE
```


Her düğümün sınırlayıcı kutu kenarlarını ve yüzeylerini, o düğümün yerel koordinat uzayının eksenlerine hizalanmış şekilde ve ek bir şeffaflık seviyesiyle görüntüler.

### TRANSPARENT_WIREFRAME {#TRANSPARENT-WIREFRAME}
```
public static final PdfRenderMode TRANSPARENT_WIREFRAME
```


Dokulu ve aydınlatılmış geometrik şekilleri (üçgenler) ek bir şeffaflık seviyesiyle ve üzerlerinde tek renk opak kenarlarla görüntüler.

### VERTICES {#VERTICES}
```
public static final PdfRenderMode VERTICES
```


Yalnızca köşe noktalarını tek bir renkte görüntüler.

### WIREFRAME {#WIREFRAME}
```
public static final PdfRenderMode WIREFRAME
```


Yalnızca kenarları tek bir renkte görüntüler.

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

