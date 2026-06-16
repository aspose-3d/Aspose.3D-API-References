---
title: "VertexElementUV"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Définit les coordonnées UV pour les composants spécifiés."
type: docs
weight: 220
url: /fr/java/com.aspose.threed/vertexelementuv/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.VertexElement](../../com.aspose.threed/vertexelement), [com.aspose.threed.VertexElementVector4](../../com.aspose.threed/vertexelementvector4)
```
public class VertexElementUV extends VertexElementVector4
```

Définit les coordonnées UV pour les composants spécifiés. Une géométrie peut contenir plusieurs éléments [VertexElementUV](../../com.aspose.threed/vertexelementuv), et chacun d'eux possède différents [TextureMapping](../../com.aspose.threed/texturemapping)s.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [VertexElementUV()](#VertexElementUV--) | Initialise une nouvelle instance de la classe [VertexElementUV](../../com.aspose.threed/vertexelementuv). |
| [VertexElementUV(TextureMapping textureMapping)](#VertexElementUV-com.aspose.threed.TextureMapping-) | Initialise une nouvelle instance de la classe [VertexElementUV](../../com.aspose.threed/vertexelementuv). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addData(Iterable<Vector2> data)](#addData-java.lang.Iterable-com.aspose.threed.Vector2--) | Ajoute un ensemble de [Vector2](../../com.aspose.threed/vector2) à VertexElementUV.Data. |
| [addData2(Iterable<Vector3> data)](#addData2-java.lang.Iterable-com.aspose.threed.Vector3--) | Ajoute un ensemble de [Vector3](../../com.aspose.threed/vector3) à VertexElementUV.Data. |
| [clear()](#clear--) | Supprime tous les éléments des tableaux direct et d'index. |
| [clone(boolean withData)](#clone-boolean-) | Clone en profondeur l'élément de sommet. |
| [clone(boolean withDirect, boolean withIndice)](#clone-boolean-boolean-) |  |
| [copyTo(VertexElementVector4 target)](#copyTo-com.aspose.threed.VertexElementVector4-) | Copie les données vers l'élément spécifié. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Obtient les données du sommet. |
| [getIndices()](#getIndices--) | Obtient les données des indices. |
| [getMappingMode()](#getMappingMode--) | Obtient la façon dont l'élément est mappé. |
| [getName()](#getName--) | Obtient le nom. |
| [getReferenceMode()](#getReferenceMode--) | Obtient la façon dont l'élément est référencé. |
| [getVertexElementType()](#getVertexElementType--) | Obtient le type du [VertexElement](../../com.aspose.threed/vertexelement). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setData(Vector4[] data)](#setData-com.aspose.threed.Vector4---) | Charge les données. |
| [setIndices(int[] data)](#setIndices-int---) | Charge les indices. |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | Définit la façon dont l'élément est mappé. |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | Définit la façon dont l'élément est référencé. |
| [toString()](#toString--) | Représentation sous forme de chaîne de l'élément de sommet. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexElementUV() {#VertexElementUV--}
```
public VertexElementUV()
```


Initialise une nouvelle instance de la classe [VertexElementUV](../../com.aspose.threed/vertexelementuv). Le type de mappage de texture par défaut est [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE)

### VertexElementUV(TextureMapping textureMapping) {#VertexElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV(TextureMapping textureMapping)
```


Initialise une nouvelle instance de la classe [VertexElementUV](../../com.aspose.threed/vertexelementuv).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Le type de mappage de texture. |

### addData(Iterable<Vector2> data) {#addData-java.lang.Iterable-com.aspose.threed.Vector2--}
```
public void addData(Iterable<Vector2> data)
```


Ajoute un ensemble de [Vector2](../../com.aspose.threed/vector2) à VertexElementUV.Data. Il s'agit d'un raccourci, cette méthode convertira le [Vector2](../../com.aspose.threed/vector2) en [Vector4](../../com.aspose.threed/vector4) avec z à 0 et w à 0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | java.lang.Iterable<com.aspose.threed.Vector2> |  |

### addData2(Iterable<Vector3> data) {#addData2-java.lang.Iterable-com.aspose.threed.Vector3--}
```
public void addData2(Iterable<Vector3> data)
```


Ajoute un ensemble de [Vector3](../../com.aspose.threed/vector3) à VertexElementUV.Data. Il s'agit d'un raccourci, cette méthode convertira le [Vector3](../../com.aspose.threed/vector3) en [Vector4](../../com.aspose.threed/vector4) avec w à 0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | java.lang.Iterable<com.aspose.threed.Vector3> |  |

### clear() {#clear--}
```
public void clear()
```


Supprime tous les éléments des tableaux direct et d'index.

### clone(boolean withData) {#clone-boolean-}
```
public VertexElement clone(boolean withData)
```


Clone en profondeur l'élément de sommet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| withData | boolean | Clone le sommet avec les tableaux direct et d'index. |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
### clone(boolean withDirect, boolean withIndice) {#clone-boolean-boolean-}
```
public VertexElement clone(boolean withDirect, boolean withIndice)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| withDirect | boolean |  |
| withIndice | boolean |  |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
### copyTo(VertexElementVector4 target) {#copyTo-com.aspose.threed.VertexElementVector4-}
```
public void copyTo(VertexElementVector4 target)
```


Copie les données vers l'élément spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| target | [VertexElementVector4](../../com.aspose.threed/vertexelementvector4) | Cible. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public List<Vector4> getData()
```


Obtient les données du sommet.

**Returns:**
java.util.List<com.aspose.threed.Vector4> - les données de sommet
### getIndices() {#getIndices--}
```
public List<Integer> getIndices()
```


Obtient les données des indices.

**Returns:**
java.util.List<java.lang.Integer> - les données des indices
### getMappingMode() {#getMappingMode--}
```
public MappingMode getMappingMode()
```


Obtient la façon dont l'élément est mappé.

**Returns:**
[MappingMode](../../com.aspose.threed/mappingmode) - how the element is mapped.
### getName() {#getName--}
```
public String getName()
```


Obtient le nom.

**Returns:**
java.lang.String - le nom.
### getReferenceMode() {#getReferenceMode--}
```
public ReferenceMode getReferenceMode()
```


Obtient la façon dont l'élément est référencé.

**Returns:**
[ReferenceMode](../../com.aspose.threed/referencemode) - how the element is referenced.
### getVertexElementType() {#getVertexElementType--}
```
public VertexElementType getVertexElementType()
```


Obtient le type du [VertexElement](../../com.aspose.threed/vertexelement).

**Returns:**
[VertexElementType](../../com.aspose.threed/vertexelementtype) - the type of the [VertexElement](../../com.aspose.threed/vertexelement)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setData(Vector4[] data) {#setData-com.aspose.threed.Vector4---}
```
public void setData(Vector4[] data)
```


Charge les données.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| data | [Vector4\[\]](../../com.aspose.threed/vector4) |  |

### setIndices(int[] data) {#setIndices-int---}
```
public void setIndices(int[] data)
```


Charge les indices.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | int[] |  |

### setMappingMode(MappingMode value) {#setMappingMode-com.aspose.threed.MappingMode-}
```
public void setMappingMode(MappingMode value)
```


Définit la façon dont l'élément est mappé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [MappingMode](../../com.aspose.threed/mappingmode) | Nouvelle valeur |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Définit le nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setReferenceMode(ReferenceMode value) {#setReferenceMode-com.aspose.threed.ReferenceMode-}
```
public void setReferenceMode(ReferenceMode value)
```


Définit la façon dont l'élément est référencé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ReferenceMode](../../com.aspose.threed/referencemode) | Nouvelle valeur |

### toString() {#toString--}
```
public String toString()
```


Représentation sous forme de chaîne de l'élément de sommet.

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

