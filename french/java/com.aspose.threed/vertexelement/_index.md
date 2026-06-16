---
title: "VertexElement"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Classe de base des éléments de sommet."
type: docs
weight: 207
url: /fr/java/com.aspose.threed/vertexelement/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.threed.IIndexedVertexElement](../../com.aspose.threed/iindexedvertexelement)
```
public abstract class VertexElement implements IIndexedVertexElement
```

Classe de base des éléments de sommet. Un type d'élément de sommet est identifié par VertexElementType. Un VertexElement décrit comment l'élément de sommet est mappé à une surface géométrique et comment les informations de mappage sont organisées en mémoire. Un VertexElement contient des normales, des UV ou d'autres types d'informations.
## Méthodes

| Méthode | Description |
| --- | --- |
| [clear()](#clear--) | Efface toutes les données de cet élément de sommet. |
| [clone(boolean withData)](#clone-boolean-) | Clone en profondeur l'élément de sommet. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getIndices()](#getIndices--) | Obtient les données des indices. |
| [getMappingMode()](#getMappingMode--) | Obtient la façon dont l'élément est mappé. |
| [getName()](#getName--) | Obtient le nom. |
| [getReferenceMode()](#getReferenceMode--) | Obtient la façon dont l'élément est référencé. |
| [getVertexElementType()](#getVertexElementType--) | Obtient le type du [VertexElement](../../com.aspose.threed/vertexelement). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setIndices(int[] data)](#setIndices-int---) | Charge les indices. |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | Définit la façon dont l'élément est mappé. |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | Définit la façon dont l'élément est référencé. |
| [toString()](#toString--) | Représentation sous forme de chaîne de l'élément de sommet. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clear() {#clear--}
```
public abstract void clear()
```


Efface toutes les données de cet élément de sommet.

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

