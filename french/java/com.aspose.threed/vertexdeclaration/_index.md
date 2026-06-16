---
title: "VertexDeclaration"
second_title: "Référence d'API Aspose.3D pour Java"
description: "La déclaration d'une structure de sommets définie sur mesure."
type: docs
weight: 206
url: /fr/java/com.aspose.threed/vertexdeclaration/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable, java.lang.Comparable
```
public final class VertexDeclaration implements Iterable<VertexField>, Comparable<VertexDeclaration>
```

La déclaration de la structure d'un sommet défini sur mesure
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [VertexDeclaration()](#VertexDeclaration--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addField(int dataType, VertexFieldSemantic semantic)](#addField-int-com.aspose.threed.VertexFieldSemantic-) | Ajouter un nouveau champ de sommet |
| [addField(int dataType, VertexFieldSemantic semantic, int index)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-) | Ajouter un nouveau champ de sommet |
| [addField(int dataType, VertexFieldSemantic semantic, int index, String alias)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-) | Ajouter un nouveau champ de sommet |
| [clear()](#clear--) | Effacer tous les champs. |
| [compareTo(VertexDeclaration other)](#compareTo-com.aspose.threed.VertexDeclaration-) | Compare cette instance à un objet spécifié et renvoie une indication de leurs valeurs relatives. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si cette instance et un objet spécifié, qui doit également être un objet [VertexDeclaration](../../com.aspose.threed/vertexdeclaration), ont la même valeur. |
| [fromGeometry(Geometry geometry, boolean useFloat)](#fromGeometry-com.aspose.threed.Geometry-boolean-) | Créer une [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) basée sur la disposition d'une [Geometry](../../com.aspose.threed/geometry). |
| [get(int index)](#get-int-) | Obtient le [VertexField](../../com.aspose.threed/vertexfield) par indice |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Obtient le nombre de tous les champs définis dans cette [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |
| [getSealed()](#getSealed--) | Une [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) sera scellée lorsqu'elle aura été utilisée par [TriMesh](../../com.aspose.threed/trimesh), aucune modification supplémentaire n'est autorisée. |
| [getSize()](#getSize--) | La taille en octets de la structure de sommet. |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette chaîne. |
| [iterator()](#iterator--) | Obtient un énumérateur pour parcourir tous les champs de sommet de cette instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Représentation sous forme de chaîne de caractères de [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexDeclaration() {#VertexDeclaration--}
```
public VertexDeclaration()
```


### addField(int dataType, VertexFieldSemantic semantic) {#addField-int-com.aspose.threed.VertexFieldSemantic-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic)
```


Ajouter un nouveau champ de sommet

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataType | int | Le type de données du champ de sommet |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Comment ce champ sera-t-il utilisé |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index)
```


Ajouter un nouveau champ de sommet

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataType | int | Le type de données du champ de sommet |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Comment ce champ sera-t-il utilisé |
| indice | int | L'index pour la même sémantique de champ, -1 pour la génération automatique |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index, String alias) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index, String alias)
```


Ajouter un nouveau champ de sommet

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataType | int | Le type de données du champ de sommet |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Comment ce champ sera-t-il utilisé |
| indice | int | L'index pour la même sémantique de champ, -1 pour la génération automatique |
| alias | java.lang.String | Le nom d'alias du champ |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### clear() {#clear--}
```
public void clear()
```


Effacer tous les champs.

### compareTo(VertexDeclaration other) {#compareTo-com.aspose.threed.VertexDeclaration-}
```
public int compareTo(VertexDeclaration other)
```


Compare cette instance à un objet spécifié et renvoie une indication de leurs valeurs relatives.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si cette instance et un objet spécifié, qui doit également être un objet [VertexDeclaration](../../com.aspose.threed/vertexdeclaration), ont la même valeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromGeometry(Geometry geometry, boolean useFloat) {#fromGeometry-com.aspose.threed.Geometry-boolean-}
```
public static VertexDeclaration fromGeometry(Geometry geometry, boolean useFloat)
```


Créer une [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) basée sur la disposition d'une [Geometry](../../com.aspose.threed/geometry).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) |  |
| useFloat | boolean | Utilisez float au lieu du type double |

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### get(int index) {#get-int-}
```
public VertexField get(int index)
```


Obtient le [VertexField](../../com.aspose.threed/vertexfield) par indice

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indice | int |  |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield) - the [VertexField](../../com.aspose.threed/vertexfield) by index
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


Obtient le nombre de tous les champs définis dans cette [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)

**Returns:**
int - le nombre de tous les champs définis dans ce [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### getSealed() {#getSealed--}
```
public boolean getSealed()
```


Une [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) sera scellée lorsqu'elle aura été utilisée par [TriMesh](../../com.aspose.threed/trimesh), aucune modification supplémentaire n'est autorisée.

**Returns:**
boolean - Un [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) sera scellé lorsqu'il aura été utilisé par [TriMesh](../../com.aspose.threed/trimesh), aucune modification supplémentaire n'est autorisée.
### getSize() {#getSize--}
```
public int getSize()
```


La taille en octets de la structure de sommet.

**Returns:**
int - La taille en octets de la structure de sommet.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage pour cette chaîne.

**Returns:**
int - Un code de hachage entier signé de 32 bits.
### iterator() {#iterator--}
```
public Iterator<VertexField> iterator()
```


Obtient un énumérateur pour parcourir tous les champs de sommet de cette instance.

**Returns:**
java.util.Iterator<com.aspose.threed.VertexField> - Énumérateur
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


Représentation sous forme de chaîne de caractères de [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)

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

