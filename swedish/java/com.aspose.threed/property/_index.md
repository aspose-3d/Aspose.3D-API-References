---
title: StructuralMetadata.Property
second_title: Aspose.3D for Java API-referens
description: Egendomsdefinitionen i metadataklasser
type: docs
weight: 13
url: /sv/java/com.aspose.threed/structuralmetadata.property/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.Property
```

Egenskapsdefinitionen i metadataklassernas
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-) | Konstruktor för metadataegenskap |
| [Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) | Konstruktor för metadataegenskap |
| [Property(String name, Class<?> type)](#Property-java.lang.String-java.lang.Class----) | Konstruktor för metadataegenskap |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Antal data för en fast storlek array. |
| [getDescription()](#getDescription--) | Beskrivningen av egenskapen |
| [getDisplayName()](#getDisplayName--) | Namnet på egenskapen, används av UI för representation. |
| [getEnumType()](#getEnumType--) | Enum-typen |
| [getName()](#getName--) | Det unika namnet på egenskapen |
| [getNormalized()](#getNormalized--) | Är data normaliserad. |
| [getType()](#getType--) | Datatypen för egenskapen |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(Integer value)](#setCount-java.lang.Integer-) | Antal data för en fast storlek array. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Beskrivningen av egenskapen |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Namnet på egenskapen, används av UI för representation. |
| [setEnumType(StructuralMetadata.EnumType value)](#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-) | Enum-typen |
| [setNormalized(boolean value)](#setNormalized-boolean-) | Är data normaliserad. |
| [toString()](#toString--) | Hämtar strängrepresentationen av denna instans. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)
```


Konstruktor för metadataegenskap

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Det unika namnet på egenskapen |
| displayName | java.lang.String | Namnet på egenskapen, används av UI för representation. |
| description | java.lang.String | Beskrivningen av egenskapen |
| type | java.lang.Class<?> | Datatyp för egenskapen |
| normalized | boolean | Är data normaliserad |
| antal | java.lang.Integer | Antal data för en faststorleksarray |

### Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)
```


Konstruktor för metadataegenskap

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Det unika namnet på egenskapen |
| displayName | java.lang.String | Namnet på egenskapen, används av UI för representation. |
| description | java.lang.String | Beskrivningen av egenskapen |
| type | [EnumType](../../com.aspose.threed/enumtype) | Datatyp för egenskapen |
| array | boolean | Är varje egenskapsvärde en array eller en skalär |
| antal | java.lang.Integer | Antal data för en faststorleksarray |

### Property(String name, Class<?> type) {#Property-java.lang.String-java.lang.Class----}
```
public Property(String name, Class<?> type)
```


Konstruktor för metadataegenskap

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Det unika namnet på egenskapen |
| type | java.lang.Class<?> | Datatyp för egenskapen |

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
### getCount() {#getCount--}
```
public Integer getCount()
```


Antal data för en fast storlek array.

**Returns:**
java.lang.Integer - Antal data för en faststorleksarray.
### getDescription() {#getDescription--}
```
public String getDescription()
```


Beskrivningen av egenskapen

**Returns:**
java.lang.String - Beskrivningen av egenskapen
### getDisplayName() {#getDisplayName--}
```
public String getDisplayName()
```


Namnet på egenskapen, används av UI för representation.

**Returns:**
java.lang.String - Namnet på egenskapen, som används av UI för representation.
### getEnumType() {#getEnumType--}
```
public StructuralMetadata.EnumType getEnumType()
```


Enum-typen

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - The enum type
### getName() {#getName--}
```
public String getName()
```


Det unika namnet på egenskapen

**Returns:**
java.lang.String - Det unika namnet på egenskapen
### getNormalized() {#getNormalized--}
```
public boolean getNormalized()
```


Är data normaliserad.

**Returns:**
boolean - Är data normaliserad.
### getType() {#getType--}
```
public Class<?> getType()
```


Datatypen för egenskapen

**Returns:**
java.lang.Class<?> - Datatypen för egenskapen
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




### setCount(Integer value) {#setCount-java.lang.Integer-}
```
public void setCount(Integer value)
```


Antal data för en fast storlek array.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Integer | Nytt värde |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Beskrivningen av egenskapen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public void setDisplayName(String value)
```


Namnet på egenskapen, används av UI för representation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setEnumType(StructuralMetadata.EnumType value) {#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-}
```
public void setEnumType(StructuralMetadata.EnumType value)
```


Enum-typen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EnumType](../../com.aspose.threed/enumtype) | Nytt värde |

### setNormalized(boolean value) {#setNormalized-boolean-}
```
public void setNormalized(boolean value)
```


Är data normaliserad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

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

