---
title: StructuralMetadata.Property
second_title: Aspose.3D for Java API-referentie
description: De eigenschapsdefinitie in metadata‑klassen.
type: docs
weight: 13
url: /nl/java/com.aspose.threed/structuralmetadata.property/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.Property
```

De eigenschapsdefinitie in de klassen van metadata
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-) | Constructor van de eigenschap van metadata. |
| [Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) | Constructor van de eigenschap van metadata. |
| [Property(String name, Class<?> type)](#Property-java.lang.String-java.lang.Class----) | Constructor van de eigenschap van metadata. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Aantal gegevens voor een array met vaste grootte. |
| [getDescription()](#getDescription--) | De beschrijving van de eigenschap. |
| [getDisplayName()](#getDisplayName--) | De naam van de eigenschap, gebruikt door de UI voor weergave. |
| [getEnumType()](#getEnumType--) | Het enumtype. |
| [getName()](#getName--) | De unieke naam van de eigenschap. |
| [getNormalized()](#getNormalized--) | Is de data genormaliseerd. |
| [getType()](#getType--) | Het gegevenstype van de eigenschap. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(Integer value)](#setCount-java.lang.Integer-) | Aantal gegevens voor een array met vaste grootte. |
| [setDescription(String value)](#setDescription-java.lang.String-) | De beschrijving van de eigenschap. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | De naam van de eigenschap, gebruikt door de UI voor weergave. |
| [setEnumType(StructuralMetadata.EnumType value)](#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-) | Het enumtype. |
| [setNormalized(boolean value)](#setNormalized-boolean-) | Is de data genormaliseerd. |
| [toString()](#toString--) | Haalt de tekenreeksrepresentatie van dit exemplaar op. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)
```


Constructor van de eigenschap van metadata.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De unieke naam van de eigenschap. |
| displayName | java.lang.String | De naam van de eigenschap, gebruikt door de UI voor weergave. |
| description | java.lang.String | De beschrijving van de eigenschap. |
| type | java.lang.Class<?> | Gegevenstype van de eigenschap |
| normalized | boolean | Is de data genormaliseerd |
| aantal | java.lang.Integer | Aantal gegevens voor een vaste-grootte array |

### Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)
```


Constructor van de eigenschap van metadata.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De unieke naam van de eigenschap. |
| displayName | java.lang.String | De naam van de eigenschap, gebruikt door de UI voor weergave. |
| description | java.lang.String | De beschrijving van de eigenschap. |
| type | [EnumType](../../com.aspose.threed/enumtype) | Gegevenstype van de eigenschap |
| array | boolean | Is elke eigenschapswaarde een array of een scalair |
| aantal | java.lang.Integer | Aantal gegevens voor een vaste-grootte array |

### Property(String name, Class<?> type) {#Property-java.lang.String-java.lang.Class----}
```
public Property(String name, Class<?> type)
```


Constructor van de eigenschap van metadata.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | De unieke naam van de eigenschap. |
| type | java.lang.Class<?> | Gegevenstype van de eigenschap |

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


Aantal gegevens voor een array met vaste grootte.

**Returns:**
java.lang.Integer - Aantal gegevens voor een vaste-grootte array.
### getDescription() {#getDescription--}
```
public String getDescription()
```


De beschrijving van de eigenschap.

**Returns:**
java.lang.String - De beschrijving van de eigenschap
### getDisplayName() {#getDisplayName--}
```
public String getDisplayName()
```


De naam van de eigenschap, gebruikt door de UI voor weergave.

**Returns:**
java.lang.String - De naam van de eigenschap, gebruikt door de UI voor weergave.
### getEnumType() {#getEnumType--}
```
public StructuralMetadata.EnumType getEnumType()
```


Het enumtype.

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - The enum type
### getName() {#getName--}
```
public String getName()
```


De unieke naam van de eigenschap.

**Returns:**
java.lang.String - De unieke naam van de eigenschap
### getNormalized() {#getNormalized--}
```
public boolean getNormalized()
```


Is de data genormaliseerd.

**Returns:**
boolean - Is de data genormaliseerd.
### getType() {#getType--}
```
public Class<?> getType()
```


Het gegevenstype van de eigenschap.

**Returns:**
java.lang.Class<?> - Het gegevenstype van de eigenschap
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


Aantal gegevens voor een array met vaste grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Integer | Nieuwe waarde |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


De beschrijving van de eigenschap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public void setDisplayName(String value)
```


De naam van de eigenschap, gebruikt door de UI voor weergave.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setEnumType(StructuralMetadata.EnumType value) {#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-}
```
public void setEnumType(StructuralMetadata.EnumType value)
```


Het enumtype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [EnumType](../../com.aspose.threed/enumtype) | Nieuwe waarde |

### setNormalized(boolean value) {#setNormalized-boolean-}
```
public void setNormalized(boolean value)
```


Is de data genormaliseerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### toString() {#toString--}
```
public String toString()
```


Haalt de tekenreeksrepresentatie van dit exemplaar op.

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

