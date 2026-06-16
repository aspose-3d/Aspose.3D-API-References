---
title: "PropertyCollection"
second_title: "Référence d'API Aspose.3D pour Java"
description: "La collection de propriétés"
type: docs
weight: 140
url: /fr/java/com.aspose.threed/propertycollection/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class PropertyCollection implements Iterable<Property>
```

La collection de propriétés
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String property)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [get(int idx)](#get-int-) | Obtient la propriété par index. |
| [get(String property)](#get-java.lang.String-) | Obtient la valeur de la propriété par son nom. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime une propriété dynamique. |
| [set(String property, Object value)](#set-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété par son nom. |
| [size()](#size--) | Obtient le nombre de propriétés déclarées. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### findProperty(String property) {#findProperty-java.lang.String-}
```
public Property findProperty(String property)
```


Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Nom de la propriété. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### get(int idx) {#get-int-}
```
public Property get(int idx)
```


Obtient la propriété par index.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| idx | int | L'index basé sur 0 de la propriété |

**Returns:**
[Property](../../com.aspose.threed/property) - the property by index.
### get(String property) {#get-java.lang.String-}
```
public Object get(String property)
```


Obtient la valeur de la propriété par son nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Le nom de la propriété |

**Returns:**
java.lang.Object - La valeur de la propriété
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public Iterator<Property> iterator()
```


Renvoie un énumérateur qui parcourt la collection.

**Returns:**
java.util.Iterator<com.aspose.threed.Property>
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


Supprime une propriété dynamique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Quelle propriété supprimer |

**Returns:**
boolean - vrai si la propriété est supprimée avec succès
### set(String property, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String property, Object value)
```


Définit la valeur de la propriété par son nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Le nom de la propriété |
| valeur | java.lang.Object | Nouvelle valeur |

### size() {#size--}
```
public int size()
```


Obtient le nombre de propriétés déclarées.

**Returns:**
int - le nombre de propriétés déclarées.
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

