---
title: StructuralMetadata.PropertyTable
second_title: Aspose.3D for Java API-referentie
description: Eigenschapstabel.
type: docs
weight: 14
url: /nl/java/com.aspose.threed/structuralmetadata.propertytable/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.PropertyTable
```

Eigenschapstabel.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PropertyTable(String name, StructuralMetadata.ClassType mclass)](#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | Constructor van de property table. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addValue(StructuralMetadata.Property prop, Object value)](#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-) | Voeg een nieuwe eigenschap toe aan de property table. |
| [addValue(String propName, Object value)](#addValue-java.lang.String-java.lang.Object-) | Voeg een nieuwe eigenschap toe aan de property table. |
| [attach(VertexElementUserData userData)](#attach-com.aspose.threed.VertexElementUserData-) | Koppel de huidige property table aan de opgegeven gebruikersgegevens |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(VertexElementUserData userData)](#from-com.aspose.threed.VertexElementUserData-) | Extraheer de gekoppelde property table uit de opgegeven gebruikersgegevens |
| [getClass()](#getClass--) |  |
| [getMetaClass()](#getMetaClass--) | De meta‑klasse van deze property table. |
| [getName()](#getName--) | Naam van de property table. |
| [getValue(String name)](#getValue-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschapsnaam |
| [getValues()](#getValues--) | Waarden van de property table. |
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


Constructor van de property table.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De naam van deze tabelinstantie. |
| mclass | [ClassType](../../com.aspose.threed/classtype) | De meta‑klassedefinitie van deze property table |

### addValue(StructuralMetadata.Property prop, Object value) {#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-}
```
public void addValue(StructuralMetadata.Property prop, Object value)
```


Voeg een nieuwe eigenschap toe aan de property table.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| prop | [Property](../../com.aspose.threed/property) | Welke eigenschap toe te voegen met waarde |
| waarde | java.lang.Object | Array van waarden |

### addValue(String propName, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String propName, Object value)
```


Voeg een nieuwe eigenschap toe aan de property table.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propName | java.lang.String | Welke eigenschap toe te voegen met waarde |
| waarde | java.lang.Object | Array van waarden |

### attach(VertexElementUserData userData) {#attach-com.aspose.threed.VertexElementUserData-}
```
public void attach(VertexElementUserData userData)
```


Koppel de huidige property table aan de opgegeven gebruikersgegevens

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) |  |

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
### from(VertexElementUserData userData) {#from-com.aspose.threed.VertexElementUserData-}
```
public static StructuralMetadata.PropertyTable from(VertexElementUserData userData)
```


Extraheer de gekoppelde property table uit de opgegeven gebruikersgegevens

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) | De gebruikersgegevens die geassocieerd zijn met een property table |

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


De meta‑klasse van deze property table.

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - The meta class of this property table.
### getName() {#getName--}
```
public String getName()
```


Naam van de property table.

**Returns:**
java.lang.String - Naam van de property table.
### getValue(String name) {#getValue-java.lang.String-}
```
public Object getValue(String name)
```


Haalt de waarde op van de opgegeven eigenschapsnaam

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam van eigenschap |

**Returns:**
java.lang.Object - Eigenschapswaarde of null indien niet gevonden
### getValues() {#getValues--}
```
public HashMap<String,Object> getValues()
```


Waarden van de property table.

**Returns:**
java.util.HashMap<java.lang.String,java.lang.Object> - Waarden van de property table.
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

