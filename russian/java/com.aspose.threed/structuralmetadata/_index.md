---
title: StructuralMetadata
second_title: Справочник API Aspose.3D для Java
description: Этот класс предоставляет поддержку EXT_structural_metadata, используемого только в glTF.
type: docs
weight: 180
url: /ru/java/com.aspose.threed/structuralmetadata/
---

**Inheritance:**
java.lang.Object
```
public class StructuralMetadata
```

Этот класс предоставляет поддержку EXT\_structural\_metadata, используется только в glTF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [StructuralMetadata()](#StructuralMetadata--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [attach(Scene scene)](#attach-com.aspose.threed.Scene-) | Присоединить текущие метаданные к указанной сцене |
| [createClass(String name)](#createClass-java.lang.String-) | Создать тип метакласса |
| [createEnum(String name)](#createEnum-java.lang.String-) | Создать тип перечисления |
| [createPropertyTable(String name, StructuralMetadata.ClassType clazz)](#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | Создать новую таблицу свойств с указанным типом метакласса |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(Scene scene)](#from-com.aspose.threed.Scene-) | Получить [StructuralMetadata](../../com.aspose.threed/structuralmetadata), связанный с указанной сценой. |
| [getClass()](#getClass--) |  |
| [getClasses()](#getClasses--) | Определения классов. |
| [getEnums()](#getEnums--) | Определения типов перечислений |
| [getPropertyTables()](#getPropertyTables--) | Таблицы свойств в этих метаданных. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StructuralMetadata() {#StructuralMetadata--}
```
public StructuralMetadata()
```


### attach(Scene scene) {#attach-com.aspose.threed.Scene-}
```
public void attach(Scene scene)
```


Присоединить текущие метаданные к указанной сцене

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### createClass(String name) {#createClass-java.lang.String-}
```
public StructuralMetadata.ClassType createClass(String name)
```


Создать тип метакласса

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя класса |

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - Instance of the meta class
### createEnum(String name) {#createEnum-java.lang.String-}
```
public StructuralMetadata.EnumType createEnum(String name)
```


Создать тип перечисления

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя типа перечисления |

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - Instance of the enum type
### createPropertyTable(String name, StructuralMetadata.ClassType clazz) {#createPropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-}
```
public StructuralMetadata.PropertyTable createPropertyTable(String name, StructuralMetadata.ClassType clazz)
```


Создать новую таблицу свойств с указанным типом метакласса

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя таблицы свойств |
| clazz | [ClassType](../../com.aspose.threed/classtype) | Тип класса новой таблицы свойств |

**Returns:**
[PropertyTable](../../com.aspose.threed/propertytable) - The new instance of property table
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
### from(Scene scene) {#from-com.aspose.threed.Scene-}
```
public static StructuralMetadata from(Scene scene)
```


Получить [StructuralMetadata](../../com.aspose.threed/structuralmetadata), связанный с указанной сценой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Сцена, в которой искать структурные метаданные |

**Returns:**
[StructuralMetadata](../../com.aspose.threed/structuralmetadata) - A valid instance of [StructuralMetadata](../../com.aspose.threed/structuralmetadata) if its found in the scene, otherwise null returned
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClasses() {#getClasses--}
```
public HashMap<String,StructuralMetadata.ClassType> getClasses()
```


Определения классов.

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.ClassType> - Определения классов.
### getEnums() {#getEnums--}
```
public HashMap<String,StructuralMetadata.EnumType> getEnums()
```


Определения типов перечислений

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.threed.StructuralMetadata.EnumType> - Определения типов перечислений
### getPropertyTables() {#getPropertyTables--}
```
public ArrayList<StructuralMetadata.PropertyTable> getPropertyTables()
```


Таблицы свойств в этих метаданных.

**Returns:**
java.util.ArrayList<com.aspose.threed.StructuralMetadata.PropertyTable> - Таблицы свойств в этих метаданных.
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

