---
title: Group
second_title: Справочник API Aspose.3D для Java
description: A  represents the logical relationships of .
type: docs
weight: 75
url: /ru/java/com.aspose.threed/group/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class Group extends A3DObject
```

A [Group](../../com.aspose.threed/group) represents the logical relationships of [Node](../../com.aspose.threed/node).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Group(String name)](#Group-java.lang.String-) | Construct a new instance of [Group](../../com.aspose.threed/group) |
| [Group()](#Group--) | Construct a new instance of [Group](../../com.aspose.threed/group) |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Находит свойство. |
| [getClass()](#getClass--) |  |
| [getGroups()](#getGroups--) | Sub-groups |
| [getName()](#getName--) | Получает имя. |
| [getNodes()](#getNodes--) | The nodes in this group |
| [getParent()](#getParent--) | Parent group of current group |
| [getProperties()](#getProperties--) | Получает коллекцию всех свойств. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Получить значение указанного свойства |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Удаляет динамическое свойство. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Удалить указанное свойство, определяемое по имени |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Устанавливает значение указанного свойства |
| [toString()](#toString--) | Получает строковое представление [Group](../../com.aspose.threed/group) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Group(String name) {#Group-java.lang.String-}
```
public Group(String name)
```


Construct a new instance of [Group](../../com.aspose.threed/group)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String | Имя группы |

### Group() {#Group--}
```
public Group()
```


Construct a new instance of [Group](../../com.aspose.threed/group)

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
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Находит свойство. Оно может быть динамическим свойством (созданным с помощью CreateDynamicProperty/SetProperty) или нативным свойством (определяемым по его имени)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| propertyName | java.lang.String | Имя свойства. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGroups() {#getGroups--}
```
public List<Group> getGroups()
```


Sub-groups

**Returns:**
java.util.List<com.aspose.threed.Group> - Подгруппы
### getName() {#getName--}
```
public String getName()
```


Получает имя.

**Returns:**
java.lang.String - имя.
### getNodes() {#getNodes--}
```
public List<Node> getNodes()
```


The nodes in this group

**Returns:**
java.util.List<com.aspose.threed.Node> - Узлы в этой группе
### getParent() {#getParent--}
```
public Group getParent()
```


Parent group of current group

**Returns:**
[Group](../../com.aspose.threed/group) - Parent group of current group
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Получает коллекцию всех свойств.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Получить значение указанного свойства

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| свойство | java.lang.String | Имя свойства |

**Returns:**
java.lang.Object - Значение найденного свойства
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




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Удаляет динамическое свойство.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Какое свойство удалить |

**Returns:**
boolean - true, если свойство успешно удалено
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Удалить указанное свойство, определяемое по имени

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| свойство | java.lang.String | Какое свойство удалить |

**Returns:**
boolean - true, если свойство успешно удалено
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Устанавливает имя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Устанавливает значение указанного свойства

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| свойство | java.lang.String | Имя свойства |
| значение | java.lang.Object | Значение свойства |

### toString() {#toString--}
```
public String toString()
```


Получает строковое представление [Group](../../com.aspose.threed/group)

**Returns:**
java.lang.String - Строковое представление текущего экземпляра
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

