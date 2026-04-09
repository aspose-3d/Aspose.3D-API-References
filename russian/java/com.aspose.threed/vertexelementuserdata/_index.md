---
title: VertexElementUserData
second_title: Справочник API Aspose.3D для Java
description: Определяет пользовательские данные для указанных компонентов.
type: docs
weight: 221
url: /ru/java/com.aspose.threed/vertexelementuserdata/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.VertexElement](../../com.aspose.threed/vertexelement)
```
public class VertexElementUserData extends VertexElement
```

Определяет пользовательские данные для указанных компонентов. Обычно это данные, специфичные для приложения, предназначенные для особых целей.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [VertexElementUserData()](#VertexElementUserData--) | Инициализирует новый экземпляр класса [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata). |
## Методы

| Метод | Описание |
| --- | --- |
| [clear()](#clear--) | Очищает все данные этого элемента вершины. |
| [clone(boolean withData)](#clone-boolean-) | Глубокое клонирование элемента вершины |
| [clone(boolean withDirect, boolean withIndice)](#clone-boolean-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Пользовательские данные, прикрепленные к этому элементу |
| [getIndices()](#getIndices--) | Получает данные индексов |
| [getMappingMode()](#getMappingMode--) | Получает, как элемент отображён. |
| [getName()](#getName--) | Получает имя. |
| [getReferenceMode()](#getReferenceMode--) | Получает, как элемент ссылается. |
| [getVertexElementType()](#getVertexElementType--) | Получает тип [VertexElement](../../com.aspose.threed/vertexelement) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setData(Object value)](#setData-java.lang.Object-) | Пользовательские данные, прикрепленные к этому элементу |
| [setIndices(int[] data)](#setIndices-int---) | Загрузить индексы |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | Устанавливает способ отображения элемента. |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | Устанавливает, как элемент ссылается. |
| [toString()](#toString--) | Строковое представление элемента вершины. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexElementUserData() {#VertexElementUserData--}
```
public VertexElementUserData()
```


Инициализирует новый экземпляр класса [VertexElementUserData](../../com.aspose.threed/vertexelementuserdata).

### clear() {#clear--}
```
public void clear()
```


Очищает все данные этого элемента вершины.

### clone(boolean withData) {#clone-boolean-}
```
public VertexElement clone(boolean withData)
```


Глубокое клонирование элемента вершины

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| withData | boolean | Клонировать вершину с массивами direct и index |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
### clone(boolean withDirect, boolean withIndice) {#clone-boolean-boolean-}
```
public VertexElement clone(boolean withDirect, boolean withIndice)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| withDirect | boolean |  |
| withIndice | boolean |  |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
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
### getData() {#getData--}
```
public Object getData()
```


Пользовательские данные, прикрепленные к этому элементу

**Returns:**
java.lang.Object - Пользовательские данные, прикрепленные к этому элементу
### getIndices() {#getIndices--}
```
public List<Integer> getIndices()
```


Получает данные индексов

**Returns:**
java.util.List<java.lang.Integer> - данные индексов
### getMappingMode() {#getMappingMode--}
```
public MappingMode getMappingMode()
```


Получает, как элемент отображён.

**Returns:**
[MappingMode](../../com.aspose.threed/mappingmode) - how the element is mapped.
### getName() {#getName--}
```
public String getName()
```


Получает имя.

**Returns:**
java.lang.String - имя.
### getReferenceMode() {#getReferenceMode--}
```
public ReferenceMode getReferenceMode()
```


Получает, как элемент ссылается.

**Returns:**
[ReferenceMode](../../com.aspose.threed/referencemode) - how the element is referenced.
### getVertexElementType() {#getVertexElementType--}
```
public VertexElementType getVertexElementType()
```


Получает тип [VertexElement](../../com.aspose.threed/vertexelement)

**Returns:**
[VertexElementType](../../com.aspose.threed/vertexelementtype) - the type of the [VertexElement](../../com.aspose.threed/vertexelement)
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




### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```


Пользовательские данные, прикрепленные к этому элементу

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object | Новое значение |

### setIndices(int[] data) {#setIndices-int---}
```
public void setIndices(int[] data)
```


Загрузить индексы

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | int[] |  |

### setMappingMode(MappingMode value) {#setMappingMode-com.aspose.threed.MappingMode-}
```
public void setMappingMode(MappingMode value)
```


Устанавливает способ отображения элемента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MappingMode](../../com.aspose.threed/mappingmode) | Новое значение |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Устанавливает имя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setReferenceMode(ReferenceMode value) {#setReferenceMode-com.aspose.threed.ReferenceMode-}
```
public void setReferenceMode(ReferenceMode value)
```


Устанавливает, как элемент ссылается.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ReferenceMode](../../com.aspose.threed/referencemode) | Новое значение |

### toString() {#toString--}
```
public String toString()
```


Строковое представление элемента вершины.

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

