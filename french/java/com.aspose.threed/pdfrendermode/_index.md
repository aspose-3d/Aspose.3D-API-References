---
title: "PdfRenderMode"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Le mode de rendu spécifie le style dans lequel l'œuvre 3D est rendue."
type: docs
weight: 289
url: /fr/java/com.aspose.threed/pdfrendermode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PdfRenderMode extends Enum<PdfRenderMode>
```

Le mode de rendu spécifie le style dans lequel l'œuvre 3D est rendue.
## Champs

| Champ | Description |
| --- | --- |
| [BOUNDING_BOX](#BOUNDING-BOX) | Affiche les arêtes de la boîte englobante de chaque nœud, alignées avec les axes de l'espace de coordonnées local de ce nœud. |
| [HIDDEN_WIREFRAME](#HIDDEN-WIREFRAME) | Affiche les arêtes en une seule couleur, tout en supprimant les arêtes orientées vers l'arrière et les arêtes occultées. |
| [ILLUSTRATION](#ILLUSTRATION) | Affiche les arêtes de silhouette avec les surfaces, supprime les lignes occultées. |
| [SHADED_ILLUSTRATION](#SHADED-ILLUSTRATION) | Affiche les arêtes de silhouette avec des surfaces éclairées et texturées ainsi qu'un terme émissif supplémentaire pour éliminer les zones mal éclairées de l'œuvre. |
| [SHADED_VERTICES](#SHADED-VERTICES) | Affiche uniquement les sommets, tout en utilisant leur couleur de sommet et en appliquant l'éclairage. |
| [SHADED_WIREFRAME](#SHADED-WIREFRAME) | Affiche uniquement les arêtes, tout en interpolant leur couleur entre leurs deux sommets et en appliquant l'éclairage. |
| [SOLID](#SOLID) | Affiche des formes géométriques texturées et éclairées. |
| [SOLID_OUTLINE](#SOLID-OUTLINE) | Affiche les arêtes de silhouette avec des surfaces éclairées et texturées, supprime les lignes occultées. |
| [SOLID_WIREFRAME](#SOLID-WIREFRAME) | Affiche des formes géométriques texturées et éclairées (triangles) avec des arêtes d'une seule couleur au-dessus. |
| [TRANSPARENT](#TRANSPARENT) | Affiche des formes géométriques texturées et éclairées (triangles) avec un niveau de transparence supplémentaire. |
| [TRANSPARENT_BOUNDING_BOX](#TRANSPARENT-BOUNDING-BOX) | Affiche les faces des boîtes englobantes de chaque nœud, alignées avec les axes de l'espace de coordonnées local de ce nœud, avec un niveau de transparence supplémentaire. |
| [TRANSPARENT_BOUNDING_BOX_OUTLINE](#TRANSPARENT-BOUNDING-BOX-OUTLINE) | Affiche les arêtes et les faces des boîtes englobantes de chaque nœud, alignées avec les axes de l'espace de coordonnées local de ce nœud, avec un niveau de transparence supplémentaire. |
| [TRANSPARENT_WIREFRAME](#TRANSPARENT-WIREFRAME) | Affiche des formes géométriques texturées et éclairées (triangles) avec un niveau de transparence supplémentaire, avec des arêtes opaques d'une seule couleur au-dessus. |
| [VERTICES](#VERTICES) | Affiche uniquement les sommets en une seule couleur. |
| [WIREFRAME](#WIREFRAME) | Affiche uniquement les arêtes en une seule couleur. |
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
### BOUNDING_BOX {#BOUNDING-BOX}
```
public static final PdfRenderMode BOUNDING_BOX
```


Affiche les arêtes de la boîte englobante de chaque nœud, alignées avec les axes de l'espace de coordonnées local de ce nœud.

### HIDDEN_WIREFRAME {#HIDDEN-WIREFRAME}
```
public static final PdfRenderMode HIDDEN_WIREFRAME
```


Affiche les arêtes en une seule couleur, tout en supprimant les arêtes orientées vers l'arrière et les arêtes occultées.

### ILLUSTRATION {#ILLUSTRATION}
```
public static final PdfRenderMode ILLUSTRATION
```


Affiche les arêtes de silhouette avec les surfaces, supprime les lignes occultées.

### SHADED_ILLUSTRATION {#SHADED-ILLUSTRATION}
```
public static final PdfRenderMode SHADED_ILLUSTRATION
```


Affiche les arêtes de silhouette avec des surfaces éclairées et texturées ainsi qu'un terme émissif supplémentaire pour éliminer les zones mal éclairées de l'œuvre.

### SHADED_VERTICES {#SHADED-VERTICES}
```
public static final PdfRenderMode SHADED_VERTICES
```


Affiche uniquement les sommets, tout en utilisant leur couleur de sommet et en appliquant l'éclairage.

### SHADED_WIREFRAME {#SHADED-WIREFRAME}
```
public static final PdfRenderMode SHADED_WIREFRAME
```


Affiche uniquement les arêtes, tout en interpolant leur couleur entre leurs deux sommets et en appliquant l'éclairage.

### SOLID {#SOLID}
```
public static final PdfRenderMode SOLID
```


Affiche des formes géométriques texturées et éclairées.

### SOLID_OUTLINE {#SOLID-OUTLINE}
```
public static final PdfRenderMode SOLID_OUTLINE
```


Affiche les arêtes de silhouette avec des surfaces éclairées et texturées, supprime les lignes occultées.

### SOLID_WIREFRAME {#SOLID-WIREFRAME}
```
public static final PdfRenderMode SOLID_WIREFRAME
```


Affiche des formes géométriques texturées et éclairées (triangles) avec des arêtes d'une seule couleur au-dessus.

### TRANSPARENT {#TRANSPARENT}
```
public static final PdfRenderMode TRANSPARENT
```


Affiche des formes géométriques texturées et éclairées (triangles) avec un niveau de transparence supplémentaire.

### TRANSPARENT_BOUNDING_BOX {#TRANSPARENT-BOUNDING-BOX}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX
```


Affiche les faces des boîtes englobantes de chaque nœud, alignées avec les axes de l'espace de coordonnées local de ce nœud, avec un niveau de transparence supplémentaire.

### TRANSPARENT_BOUNDING_BOX_OUTLINE {#TRANSPARENT-BOUNDING-BOX-OUTLINE}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX_OUTLINE
```


Affiche les arêtes et les faces des boîtes englobantes de chaque nœud, alignées avec les axes de l'espace de coordonnées local de ce nœud, avec un niveau de transparence supplémentaire.

### TRANSPARENT_WIREFRAME {#TRANSPARENT-WIREFRAME}
```
public static final PdfRenderMode TRANSPARENT_WIREFRAME
```


Affiche des formes géométriques texturées et éclairées (triangles) avec un niveau de transparence supplémentaire, avec des arêtes opaques d'une seule couleur au-dessus.

### VERTICES {#VERTICES}
```
public static final PdfRenderMode VERTICES
```


Affiche uniquement les sommets en une seule couleur.

### WIREFRAME {#WIREFRAME}
```
public static final PdfRenderMode WIREFRAME
```


Affiche uniquement les arêtes en une seule couleur.

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
public static PdfRenderMode valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

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

