---
title: "StructuralMetadata.PropertyTable"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Table des propriétés."
type: docs
weight: 14
url: /fr/java/com.aspose.threed/structuralmetadata.propertytable/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.PropertyTable
```

Table des propriétés.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PropertyTable(String name, StructuralMetadata.ClassType mclass)](#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | Constructeur de la table de propriétés. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addValue(StructuralMetadata.Property prop, Object value)](#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-) | Ajouter une nouvelle propriété à la table de propriétés. |
| [addValue(String propName, Object value)](#addValue-java.lang.String-java.lang.Object-) | Ajouter une nouvelle propriété à la table de propriétés. |
| [attach(VertexElementUserData userData)](#attach-com.aspose.threed.VertexElementUserData-) | Attacher la table de propriétés actuelle aux données utilisateur spécifiées |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(VertexElementUserData userData)](#from-com.aspose.threed.VertexElementUserData-) | Extraire la table de propriétés attachée des données utilisateur spécifiées |
| [getClass()](#getClass--) |  |
| [getMetaClass()](#getMetaClass--) | La méta‑classe de cette table de propriétés. |
| [getName()](#getName--) | Nom de la table de propriétés. |
| [getValue(String name)](#getValue-java.lang.String-) | Obtient la valeur du nom de propriété spécifié |
| [getValues()](#getValues--) | Valeurs de la table de propriétés. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PropertyTable(String name, StructuralMetadata.ClassType mclass) {#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-}
```
public PropertyTable(String name, StructuralMetadata.ClassType mclass)
```


Constructeur de la table de propriétés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Le nom de cette instance de table. |
| mclass | [ClassType](../../com.aspose.threed/classtype) | La définition de la méta‑classe de cette table de propriétés |

### addValue(StructuralMetadata.Property prop, Object value) {#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-}
```
public void addValue(StructuralMetadata.Property prop, Object value)
```


Ajouter une nouvelle propriété à la table de propriétés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| prop | [Property](../../com.aspose.threed/property) | Quelle propriété ajouter avec la valeur |
| valeur | java.lang.Object | Tableau de valeurs |

### addValue(String propName, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String propName, Object value)
```


Ajouter une nouvelle propriété à la table de propriétés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propName | java.lang.String | Quelle propriété ajouter avec la valeur |
| valeur | java.lang.Object | Tableau de valeurs |

### attach(VertexElementUserData userData) {#attach-com.aspose.threed.VertexElementUserData-}
```
public void attach(VertexElementUserData userData)
```


Attacher la table de propriétés actuelle aux données utilisateur spécifiées

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) |  |

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
### from(VertexElementUserData userData) {#from-com.aspose.threed.VertexElementUserData-}
```
public static StructuralMetadata.PropertyTable from(VertexElementUserData userData)
```


Extraire la table de propriétés attachée des données utilisateur spécifiées

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) | Les données utilisateur associées à une table de propriétés |

**Returns:**
[PropertyTable](../../com.aspose.threed/propertytable) - The associated property table instance
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMetaClass() {#getMetaClass--}
```
public StructuralMetadata.ClassType getMetaClass()
```


La méta‑classe de cette table de propriétés.

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - The meta class of this property table.
### getName() {#getName--}
```
public String getName()
```


Nom de la table de propriétés.

**Returns:**
java.lang.String - Nom de la table de propriétés.
### getValue(String name) {#getValue-java.lang.String-}
```
public Object getValue(String name)
```


Obtient la valeur du nom de propriété spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom de la propriété |

**Returns:**
java.lang.Object - Valeur de la propriété ou null si non trouvée
### getValues() {#getValues--}
```
public HashMap<String,Object> getValues()
```


Valeurs de la table de propriétés.

**Returns:**
java.util.HashMap<java.lang.String,java.lang.Object> - Valeurs de la table de propriétés.
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




### toString() {#toString--}
```
public String toString()
```




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

