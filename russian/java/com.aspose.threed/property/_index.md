---
title: StructuralMetadata.Property
second_title: Справочник API Aspose.3D для Java
description: Определение свойства в классах метаданных.
type: docs
weight: 13
url: /ru/java/com.aspose.threed/structuralmetadata.property/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.Property
```

Определение свойства в классах метаданных
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-) | Конструктор свойства метаданных. |
| [Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) | Конструктор свойства метаданных. |
| [Property(String name, Class<?> type)](#Property-java.lang.String-java.lang.Class----) | Конструктор свойства метаданных. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Количество данных для массива фиксированного размера. |
| [getDescription()](#getDescription--) | Описание свойства. |
| [getDisplayName()](#getDisplayName--) | Имя свойства, используемое пользовательским интерфейсом для отображения. |
| [getEnumType()](#getEnumType--) | Тип перечисления. |
| [getName()](#getName--) | Уникальное имя свойства. |
| [getNormalized()](#getNormalized--) | Данные нормализованы. |
| [getType()](#getType--) | Тип данных свойства. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(Integer value)](#setCount-java.lang.Integer-) | Количество данных для массива фиксированного размера. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Описание свойства. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Имя свойства, используемое пользовательским интерфейсом для отображения. |
| [setEnumType(StructuralMetadata.EnumType value)](#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-) | Тип перечисления. |
| [setNormalized(boolean value)](#setNormalized-boolean-) | Данные нормализованы. |
| [toString()](#toString--) | Получает строковое представление этого экземпляра. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)
```


Конструктор свойства метаданных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Уникальное имя свойства. |
| displayName | java.lang.String | Имя свойства, используемое пользовательским интерфейсом для отображения. |
| description | java.lang.String | Описание свойства. |
| type | java.lang.Class<?> | Тип данных свойства. |
| normalized | boolean | Данные нормализованы. |
| количество | java.lang.Integer | Количество данных для массива фиксированного размера |

### Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)
```


Конструктор свойства метаданных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Уникальное имя свойства. |
| displayName | java.lang.String | Имя свойства, используемое пользовательским интерфейсом для отображения. |
| description | java.lang.String | Описание свойства. |
| type | [EnumType](../../com.aspose.threed/enumtype) | Тип данных свойства. |
| массив | boolean | Является ли каждое значение свойства массивом или скаляром |
| количество | java.lang.Integer | Количество данных для массива фиксированного размера |

### Property(String name, Class<?> type) {#Property-java.lang.String-java.lang.Class----}
```
public Property(String name, Class<?> type)
```


Конструктор свойства метаданных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Уникальное имя свойства. |
| type | java.lang.Class<?> | Тип данных свойства. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
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


Количество данных для массива фиксированного размера.

**Returns:**
java.lang.Integer - Количество данных для массива фиксированного размера.
### getDescription() {#getDescription--}
```
public String getDescription()
```


Описание свойства.

**Returns:**
java.lang.String - Описание свойства
### getDisplayName() {#getDisplayName--}
```
public String getDisplayName()
```


Имя свойства, используемое пользовательским интерфейсом для отображения.

**Returns:**
java.lang.String - Имя свойства, используемое UI для представления.
### getEnumType() {#getEnumType--}
```
public StructuralMetadata.EnumType getEnumType()
```


Тип перечисления.

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - The enum type
### getName() {#getName--}
```
public String getName()
```


Уникальное имя свойства.

**Returns:**
java.lang.String - Уникальное имя свойства
### getNormalized() {#getNormalized--}
```
public boolean getNormalized()
```


Данные нормализованы.

**Returns:**
boolean - Являются ли данные нормализованными.
### getType() {#getType--}
```
public Class<?> getType()
```


Тип данных свойства.

**Returns:**
java.lang.Class<?> - Тип данных свойства
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


Количество данных для массива фиксированного размера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Integer | Новое значение |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Описание свойства.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public void setDisplayName(String value)
```


Имя свойства, используемое пользовательским интерфейсом для отображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setEnumType(StructuralMetadata.EnumType value) {#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-}
```
public void setEnumType(StructuralMetadata.EnumType value)
```


Тип перечисления.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EnumType](../../com.aspose.threed/enumtype) | Новое значение |

### setNormalized(boolean value) {#setNormalized-boolean-}
```
public void setNormalized(boolean value)
```


Данные нормализованы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### toString() {#toString--}
```
public String toString()
```


Получает строковое представление этого экземпляра.

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

