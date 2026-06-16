---
title: "MorphTargetDeformer"
second_title: "Référence d'API Aspose.3D pour Java"
description: "MorphTargetDeformer fournit une animation par sommet."
type: docs
weight: 108
url: /fr/java/com.aspose.threed/morphtargetdeformer/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Deformer](../../com.aspose.threed/deformer)
```
public class MorphTargetDeformer extends Deformer
```

MorphTargetDeformer fournit une animation par sommet. MorphTargetDeformer organise toutes les cibles via [MorphTargetChannel](../../com.aspose.threed/morphtargetchannel), chaque canal peut organiser plusieurs cibles. Une utilisation courante du déformeur de cible morphologique est d'appliquer une expression faciale à un personnage. Plus de détails sont disponibles sur https://en.wikipedia.org/wiki/Morph\_target\_animation
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MorphTargetDeformer(String name)](#MorphTargetDeformer-java.lang.String-) | Initialise une nouvelle instance de la classe [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer). |
| [MorphTargetDeformer()](#MorphTargetDeformer--) | Initialise une nouvelle instance de la classe [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [get(Shape target)](#get-com.aspose.threed.Shape-) | Obtient le poids pour la géométrie donnée, c'est une façon raccourcie de modifier le poids d'une cible sans accéder au canal. |
| [getChannels()](#getChannels--) | Obtient tous les canaux contenus dans ce déformeur |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Obtient le nom. |
| [getOwner()](#getOwner--) | Obtient la géométrie qui possède ce deformer |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [set(Shape target, double value)](#set-com.aspose.threed.Shape-double-) | Définit le poids pour la géométrie donnée, c'est une façon raccourcie de modifier le poids d'une cible sans accéder au canal. |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MorphTargetDeformer(String name) {#MorphTargetDeformer-java.lang.String-}
```
public MorphTargetDeformer(String name)
```


Initialise une nouvelle instance de la classe [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom. |

### MorphTargetDeformer() {#MorphTargetDeformer--}
```
public MorphTargetDeformer()
```


Initialise une nouvelle instance de la classe [MorphTargetDeformer](../../com.aspose.threed/morphtargetdeformer).

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
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | Nom de la propriété. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### get(Shape target) {#get-com.aspose.threed.Shape-}
```
public double get(Shape target)
```


Obtient le poids pour la géométrie donnée, c'est une façon raccourcie de modifier le poids d'une cible sans accéder au canal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Géométrie cible |

**Returns:**
double - Poids
### getChannels() {#getChannels--}
```
public List<MorphTargetChannel> getChannels()
```


Obtient tous les canaux contenus dans ce déformeur

**Returns:**
java.util.List<com.aspose.threed.MorphTargetChannel> - tous les canaux contenus dans ce déformeur
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName() {#getName--}
```
public String getName()
```


Obtient le nom.

**Returns:**
java.lang.String - le nom.
### getOwner() {#getOwner--}
```
public Geometry getOwner()
```


Obtient la géométrie qui possède ce deformer

**Returns:**
[Geometry](../../com.aspose.threed/geometry) - the geometry which owns this deformer
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Obtient la collection de toutes les propriétés.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Obtenir la valeur de la propriété spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Nom de la propriété |

**Returns:**
java.lang.Object - La valeur de la propriété trouvée
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




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Supprime une propriété dynamique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Quelle propriété supprimer |

**Returns:**
boolean - vrai si la propriété est supprimée avec succès
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Supprime la propriété spécifiée identifiée par son nom

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Quelle propriété supprimer |

**Returns:**
boolean - vrai si la propriété est supprimée avec succès
### set(Shape target, double value) {#set-com.aspose.threed.Shape-double-}
```
public void set(Shape target, double value)
```


Définit le poids pour la géométrie donnée, c'est une façon raccourcie de modifier le poids d'une cible sans accéder au canal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| target | [Shape](../../com.aspose.threed/shape) | Géométrie cible |
| valeur | double | Nouvelle valeur |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Définit le nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Définit la valeur de la propriété spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Nom de la propriété |
| valeur | java.lang.Object | La valeur de la propriété |

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

