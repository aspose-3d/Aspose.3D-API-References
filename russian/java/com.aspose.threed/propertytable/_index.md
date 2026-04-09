---
title: StructuralMetadata.PropertyTable
second_title: Справочник API Aspose.3D для Java
description: Таблица свойств.
type: docs
weight: 14
url: /ru/java/com.aspose.threed/structuralmetadata.propertytable/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.PropertyTable
```

Таблица свойств.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PropertyTable(String name, StructuralMetadata.ClassType mclass)](#PropertyTable-java.lang.String-com.aspose.threed.StructuralMetadata.ClassType-) | Конструктор таблицы свойств. |
## Методы

| Метод | Описание |
| --- | --- |
| [addValue(StructuralMetadata.Property prop, Object value)](#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-) | Добавить новое свойство в таблицу свойств. |
| [addValue(String propName, Object value)](#addValue-java.lang.String-java.lang.Object-) | Добавить новое свойство в таблицу свойств. |
| [attach(VertexElementUserData userData)](#attach-com.aspose.threed.VertexElementUserData-) | Привязать текущую таблицу свойств к указанным пользовательским данным |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [from(VertexElementUserData userData)](#from-com.aspose.threed.VertexElementUserData-) | Извлечь прикреплённую таблицу свойств из указанных пользовательских данных |
| [getClass()](#getClass--) |  |
| [getMetaClass()](#getMetaClass--) | Метакласс этой таблицы свойств. |
| [getName()](#getName--) | Имя таблицы свойств. |
| [getValue(String name)](#getValue-java.lang.String-) | Получает значение указанного имени свойства |
| [getValues()](#getValues--) | Значения таблицы свойств. |
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


Конструктор таблицы свойств.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя этого экземпляра таблицы. |
| mclass | [ClassType](../../com.aspose.threed/classtype) | Определение метакласса этой таблицы свойств |

### addValue(StructuralMetadata.Property prop, Object value) {#addValue-com.aspose.threed.StructuralMetadata.Property-java.lang.Object-}
```
public void addValue(StructuralMetadata.Property prop, Object value)
```


Добавить новое свойство в таблицу свойств.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| prop | [Property](../../com.aspose.threed/property) | Какое свойство добавить со значением |
| значение | java.lang.Object | Массив значений |

### addValue(String propName, Object value) {#addValue-java.lang.String-java.lang.Object-}
```
public void addValue(String propName, Object value)
```


Добавить новое свойство в таблицу свойств.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| propName | java.lang.String | Какое свойство добавить со значением |
| значение | java.lang.Object | Массив значений |

### attach(VertexElementUserData userData) {#attach-com.aspose.threed.VertexElementUserData-}
```
public void attach(VertexElementUserData userData)
```


Привязать текущую таблицу свойств к указанным пользовательским данным

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) |  |

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
### from(VertexElementUserData userData) {#from-com.aspose.threed.VertexElementUserData-}
```
public static StructuralMetadata.PropertyTable from(VertexElementUserData userData)
```


Извлечь прикреплённую таблицу свойств из указанных пользовательских данных

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| userData | [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata) | Пользовательские данные, связанные с таблицей свойств |

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


Метакласс этой таблицы свойств.

**Returns:**
[ClassType](../../com.aspose.threed/classtype) - The meta class of this property table.
### getName() {#getName--}
```
public String getName()
```


Имя таблицы свойств.

**Returns:**
java.lang.String — имя таблицы свойств.
### getValue(String name) {#getValue-java.lang.String-}
```
public Object getValue(String name)
```


Получает значение указанного имени свойства

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя свойства |

**Returns:**
java.lang.Object — значение свойства или null, если не найдено.
### getValues() {#getValues--}
```
public HashMap<String,Object> getValues()
```


Значения таблицы свойств.

**Returns:**
java.util.HashMap<java.lang.String,java.lang.Object> — значения таблицы свойств.
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

