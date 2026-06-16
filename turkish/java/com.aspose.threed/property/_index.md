---
title: "StructuralMetadata.Property"
second_title: "Aspose.3D for Java API Referansı"
description: "Meta veri sınıflarındaki özellik tanımı"
type: docs
weight: 13
url: /tr/java/com.aspose.threed/structuralmetadata.property/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.Property
```

Meta verinin sınıflarındaki özellik tanımı
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-) | Meta verinin özelliğinin yapıcı yöntemi |
| [Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) | Meta verinin özelliğinin yapıcı yöntemi |
| [Property(String name, Class<?> type)](#Property-java.lang.String-java.lang.Class----) | Meta verinin özelliğinin yapıcı yöntemi |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Sabit boyutlu dizi için veri sayısı. |
| [getDescription()](#getDescription--) | Özelliğin açıklaması |
| [getDisplayName()](#getDisplayName--) | Özelliğin adı, UI tarafından temsil için kullanılır. |
| [getEnumType()](#getEnumType--) | Enum tipi |
| [getName()](#getName--) | Özelliğin benzersiz adı |
| [getNormalized()](#getNormalized--) | Veri normalleştirilmiş mi. |
| [getType()](#getType--) | Özelliğin veri tipi |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(Integer value)](#setCount-java.lang.Integer-) | Sabit boyutlu dizi için veri sayısı. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Özelliğin açıklaması |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Özelliğin adı, UI tarafından temsil için kullanılır. |
| [setEnumType(StructuralMetadata.EnumType value)](#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-) | Enum tipi |
| [setNormalized(boolean value)](#setNormalized-boolean-) | Veri normalleştirilmiş mi. |
| [toString()](#toString--) | Bu örneğin string temsilini alır. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)
```


Meta verinin özelliğinin yapıcı yöntemi

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Özelliğin benzersiz adı |
| displayName | java.lang.String | Özelliğin adı, UI tarafından temsil için kullanılır. |
| description | java.lang.String | Özelliğin açıklaması |
| type | java.lang.Class<?> | Özelliğin veri tipi |
| normalized | boolean | Veri normalleştirilmiş mi |
| sayım | java.lang.Integer | Sabit boyutlu dizi için verinin sayısı |

### Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)
```


Meta verinin özelliğinin yapıcı yöntemi

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Özelliğin benzersiz adı |
| displayName | java.lang.String | Özelliğin adı, UI tarafından temsil için kullanılır. |
| description | java.lang.String | Özelliğin açıklaması |
| type | [EnumType](../../com.aspose.threed/enumtype) | Özelliğin veri tipi |
| dizi | boolean | Her özellik değeri dizi mi yoksa skaler mi |
| sayım | java.lang.Integer | Sabit boyutlu dizi için verinin sayısı |

### Property(String name, Class<?> type) {#Property-java.lang.String-java.lang.Class----}
```
public Property(String name, Class<?> type)
```


Meta verinin özelliğinin yapıcı yöntemi

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Özelliğin benzersiz adı |
| type | java.lang.Class<?> | Özelliğin veri tipi |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Sabit boyutlu dizi için veri sayısı.

**Returns:**
java.lang.Integer - Sabit boyutlu dizi için verinin sayısı.
### getDescription() {#getDescription--}
```
public String getDescription()
```


Özelliğin açıklaması

**Returns:**
java.lang.String - Özelliğin açıklaması
### getDisplayName() {#getDisplayName--}
```
public String getDisplayName()
```


Özelliğin adı, UI tarafından temsil için kullanılır.

**Returns:**
java.lang.String - Özelliğin adı, UI tarafından temsil için kullanılır.
### getEnumType() {#getEnumType--}
```
public StructuralMetadata.EnumType getEnumType()
```


Enum tipi

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - The enum type
### getName() {#getName--}
```
public String getName()
```


Özelliğin benzersiz adı

**Returns:**
java.lang.String - Özelliğin benzersiz adı
### getNormalized() {#getNormalized--}
```
public boolean getNormalized()
```


Veri normalleştirilmiş mi.

**Returns:**
boolean - Verinin normalleştirilip normalleştirilmediği.
### getType() {#getType--}
```
public Class<?> getType()
```


Özelliğin veri tipi

**Returns:**
java.lang.Class<?> - Özelliğin veri tipi
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


Sabit boyutlu dizi için veri sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Integer | Yeni değer |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Özelliğin açıklaması

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public void setDisplayName(String value)
```


Özelliğin adı, UI tarafından temsil için kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setEnumType(StructuralMetadata.EnumType value) {#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-}
```
public void setEnumType(StructuralMetadata.EnumType value)
```


Enum tipi

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EnumType](../../com.aspose.threed/enumtype) | Yeni değer |

### setNormalized(boolean value) {#setNormalized-boolean-}
```
public void setNormalized(boolean value)
```


Veri normalleştirilmiş mi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### toString() {#toString--}
```
public String toString()
```


Bu örneğin string temsilini alır.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

