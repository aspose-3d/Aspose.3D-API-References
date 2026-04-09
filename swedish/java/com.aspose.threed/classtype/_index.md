---
title: StructuralMetadata.ClassType
second_title: Aspose.3D for Java API-referens
description: Klassdefinition i metadata
type: docs
weight: 10
url: /sv/java/com.aspose.threed/structuralmetadata.classtype/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.ClassType
```

Klassdefinition i metadata
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ClassType(String name, String displayName, String description, ArrayList<StructuralMetadata.Property> properties)](#ClassType-java.lang.String-java.lang.String-java.lang.String-java.util.ArrayList-com.aspose.threed.StructuralMetadata.Property--) | Konstruktor för klassdefinitionen |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addProperty(StructuralMetadata.Property property)](#addProperty-com.aspose.threed.StructuralMetadata.Property-) | Lägg till en specificerad egenskap till denna klass |
| [addProperty(String name, StructuralMetadata.EnumType type, boolean array)](#addProperty-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-) |  |
| [addProperty(String name, StructuralMetadata.EnumType type, boolean array, Integer count)](#addProperty-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) |  |
| [addProperty(String name, Class<?> type)](#addProperty-java.lang.String-java.lang.Class----) | Lägg till en ny egenskap med specificerad typ |
| [addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array)](#addProperty-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-) |  |
| [addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)](#addProperty-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) |  |
| [addProperty(String name, String displayName, String description, Class<?> type)](#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----) |  |
| [addProperty(String name, String displayName, String description, Class<?> type, boolean normalized)](#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-) |  |
| [addProperty(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)](#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Beskrivning av klassen |
| [getDisplayName()](#getDisplayName--) | Namnet på klassen, som används av UI för representation |
| [getName()](#getName--) | Det unika namnet på klassen |
| [getProperties()](#getProperties--) | Egenskaperna som definierats i denna klass. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDescription(String value)](#setDescription-java.lang.String-) | Beskrivning av klassen |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Namnet på klassen, som används av UI för representation |
| [toString()](#toString--) | Hämtar strängrepresentationen av denna instans. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ClassType(String name, String displayName, String description, ArrayList<StructuralMetadata.Property> properties) {#ClassType-java.lang.String-java.lang.String-java.lang.String-java.util.ArrayList-com.aspose.threed.StructuralMetadata.Property--}
```
public ClassType(String name, String displayName, String description, ArrayList<StructuralMetadata.Property> properties)
```


Konstruktor för klassdefinitionen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Det unika namnet på klassen |
| displayName | java.lang.String | Namnet på klassen, som används av UI för representation |
| description | java.lang.String | Beskrivning av klassen |
| egenskaper | java.util.ArrayList<com.aspose.threed.StructuralMetadata.Property> | Egenskaperna som definierats i denna klass |

### addProperty(StructuralMetadata.Property property) {#addProperty-com.aspose.threed.StructuralMetadata.Property-}
```
public void addProperty(StructuralMetadata.Property property)
```


Lägg till en specificerad egenskap till denna klass

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) |  |

### addProperty(String name, StructuralMetadata.EnumType type, boolean array) {#addProperty-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-}
```
public StructuralMetadata.Property addProperty(String name, StructuralMetadata.EnumType type, boolean array)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |
| type | [EnumType](../../com.aspose.threed/enumtype) |  |
| array | boolean |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, StructuralMetadata.EnumType type, boolean array, Integer count) {#addProperty-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public StructuralMetadata.Property addProperty(String name, StructuralMetadata.EnumType type, boolean array, Integer count)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |
| type | [EnumType](../../com.aspose.threed/enumtype) |  |
| array | boolean |  |
| antal | java.lang.Integer |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, Class<?> type) {#addProperty-java.lang.String-java.lang.Class----}
```
public StructuralMetadata.Property addProperty(String name, Class<?> type)
```


Lägg till en ny egenskap med specificerad typ

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Egenskapens namn |
| type | java.lang.Class<?> | Egenskapens datatyp |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array) {#addProperty-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-}
```
public StructuralMetadata.Property addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |
| displayName | java.lang.String |  |
| description | java.lang.String |  |
| type | [EnumType](../../com.aspose.threed/enumtype) |  |
| array | boolean |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count) {#addProperty-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public StructuralMetadata.Property addProperty(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |
| displayName | java.lang.String |  |
| description | java.lang.String |  |
| type | [EnumType](../../com.aspose.threed/enumtype) |  |
| array | boolean |  |
| antal | java.lang.Integer |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, String displayName, String description, Class<?> type) {#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----}
```
public StructuralMetadata.Property addProperty(String name, String displayName, String description, Class<?> type)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |
| displayName | java.lang.String |  |
| description | java.lang.String |  |
| type | java.lang.Class<?> |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, String displayName, String description, Class<?> type, boolean normalized) {#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-}
```
public StructuralMetadata.Property addProperty(String name, String displayName, String description, Class<?> type, boolean normalized)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |
| displayName | java.lang.String |  |
| description | java.lang.String |  |
| type | java.lang.Class<?> |  |
| normalized | boolean |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### addProperty(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count) {#addProperty-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-}
```
public StructuralMetadata.Property addProperty(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |
| displayName | java.lang.String |  |
| description | java.lang.String |  |
| type | java.lang.Class<?> |  |
| normalized | boolean |  |
| antal | java.lang.Integer |  |

**Returns:**
[Property](../../com.aspose.threed/property)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
### getDescription() {#getDescription--}
```
public String getDescription()
```


Beskrivning av klassen

**Returns:**
java.lang.String - Beskrivning av klassen
### getDisplayName() {#getDisplayName--}
```
public String getDisplayName()
```


Namnet på klassen, som används av UI för representation

**Returns:**
java.lang.String - Namnet på klassen, som används av UI för representation
### getName() {#getName--}
```
public String getName()
```


Det unika namnet på klassen

**Returns:**
java.lang.String - Det unika namnet på klassen
### getProperties() {#getProperties--}
```
public List<StructuralMetadata.Property> getProperties()
```


Egenskaperna som definierats i denna klass.

**Returns:**
java.util.List<com.aspose.threed.StructuralMetadata.Property> - Egenskaperna som definierats i denna klass.
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




### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Beskrivning av klassen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public void setDisplayName(String value)
```


Namnet på klassen, som används av UI för representation

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### toString() {#toString--}
```
public String toString()
```


Hämtar strängrepresentationen av denna instans.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

