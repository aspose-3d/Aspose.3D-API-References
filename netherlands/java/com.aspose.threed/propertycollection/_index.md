---
title: PropertyCollection
second_title: Aspose.3D for Java API-referentie
description: De verzameling van eigenschappen
type: docs
weight: 140
url: /nl/java/com.aspose.threed/propertycollection/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class PropertyCollection implements Iterable<Property>
```

De verzameling van eigenschappen
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String property)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [get(int idx)](#get-int-) | Haalt de eigenschap op op basis van index. |
| [get(String property)](#get-java.lang.String-) | Haalt de waarde van de eigenschap op op basis van de eigenschapsnaam. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijdert een dynamische eigenschap. |
| [set(String property, Object value)](#set-java.lang.String-java.lang.Object-) | Stelt de waarde van de eigenschap in op basis van de eigenschapsnaam. |
| [size()](#size--) | Haalt het aantal gedeclareerde eigenschappen op. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String property) {#findProperty-java.lang.String-}
```
public Property findProperty(String property)
```


Zoekt de eigenschap. Het kan een dynamische eigenschap zijn (gemaakt door CreateDynamicProperty/SetProperty) of een native eigenschap (geïdentificeerd op naam).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Eigenschapnaam. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### get(int idx) {#get-int-}
```
public Property get(int idx)
```


Haalt de eigenschap op op basis van index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| idx | int | De 0-gebaseerde index van de eigenschap |

**Returns:**
[Property](../../com.aspose.threed/property) - the property by index.
### get(String property) {#get-java.lang.String-}
```
public Object get(String property)
```


Haalt de waarde van de eigenschap op op basis van de eigenschapsnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | De naam van de eigenschap |

**Returns:**
java.lang.Object - De waarde van de eigenschap
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


Retourneert een enumerator die door de collectie itereert.

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


Verwijdert een dynamische eigenschap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Welke eigenschap moet worden verwijderd |

**Returns:**
boolean - true als de eigenschap succesvol is verwijderd
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Verwijdert een dynamische eigenschap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Welke eigenschap moet worden verwijderd |

**Returns:**
boolean - true als de eigenschap succesvol is verwijderd
### set(String property, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String property, Object value)
```


Stelt de waarde van de eigenschap in op basis van de eigenschapsnaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | De naam van de eigenschap |
| waarde | java.lang.Object | Nieuwe waarde |

### size() {#size--}
```
public int size()
```


Haalt het aantal gedeclareerde eigenschappen op.

**Returns:**
int - het aantal gedeclareerde eigenschappen.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

