---
title: VertexDeclaration
second_title: Справочник API Aspose.3D для Java
description: Объявление пользовательской структуры вершин
type: docs
weight: 206
url: /ru/java/com.aspose.threed/vertexdeclaration/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable, java.lang.Comparable
```
public final class VertexDeclaration implements Iterable<VertexField>, Comparable<VertexDeclaration>
```

Объявление структуры пользовательской вершины
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [VertexDeclaration()](#VertexDeclaration--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [addField(int dataType, VertexFieldSemantic semantic)](#addField-int-com.aspose.threed.VertexFieldSemantic-) | Добавить новое поле вершины |
| [addField(int dataType, VertexFieldSemantic semantic, int index)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-) | Добавить новое поле вершины |
| [addField(int dataType, VertexFieldSemantic semantic, int index, String alias)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-) | Добавить новое поле вершины |
| [clear()](#clear--) | Очистить все поля. |
| [compareTo(VertexDeclaration other)](#compareTo-com.aspose.threed.VertexDeclaration-) | Сравнивает этот экземпляр с указанным объектом и возвращает указание их относительных значений. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, имеют ли этот экземпляр и указанный объект, который также должен быть объектом [VertexDeclaration](../../com.aspose.threed/vertexdeclaration), одинаковое значение. |
| [fromGeometry(Geometry geometry, boolean useFloat)](#fromGeometry-com.aspose.threed.Geometry-boolean-) | Создать [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) на основе макета [Geometry](../../com.aspose.threed/geometry). |
| [get(int index)](#get-int-) | Получает [VertexField](../../com.aspose.threed/vertexfield) по индексу |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Получает количество всех полей, определённых в этом [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |
| [getSealed()](#getSealed--) | A [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) будет запечатан, когда его использует [TriMesh](../../com.aspose.threed/trimesh), дальнейшие изменения не допускаются. |
| [getSize()](#getSize--) | Размер в байтах структуры вершины. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этой строки. |
| [iterator()](#iterator--) | Получает перечислитель для обхода всех полей вершины в этом экземпляре. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Строковое представление [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexDeclaration() {#VertexDeclaration--}
```
public VertexDeclaration()
```


### addField(int dataType, VertexFieldSemantic semantic) {#addField-int-com.aspose.threed.VertexFieldSemantic-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic)
```


Добавить новое поле вершины

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataType | int | Тип данных поля вершины |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Как будет использоваться это поле |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index)
```


Добавить новое поле вершины

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataType | int | Тип данных поля вершины |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Как будет использоваться это поле |
| индекс | int | Индекс для той же семантики поля, -1 для автоматической генерации |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index, String alias) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index, String alias)
```


Добавить новое поле вершины

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataType | int | Тип данных поля вершины |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | Как будет использоваться это поле |
| индекс | int | Индекс для той же семантики поля, -1 для автоматической генерации |
| псевдоним | java.lang.String | Имя псевдонима поля |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### clear() {#clear--}
```
public void clear()
```


Очистить все поля.

### compareTo(VertexDeclaration other) {#compareTo-com.aspose.threed.VertexDeclaration-}
```
public int compareTo(VertexDeclaration other)
```


Сравнивает этот экземпляр с указанным объектом и возвращает указание их относительных значений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, имеют ли этот экземпляр и указанный объект, который также должен быть объектом [VertexDeclaration](../../com.aspose.threed/vertexdeclaration), одинаковое значение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromGeometry(Geometry geometry, boolean useFloat) {#fromGeometry-com.aspose.threed.Geometry-boolean-}
```
public static VertexDeclaration fromGeometry(Geometry geometry, boolean useFloat)
```


Создать [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) на основе макета [Geometry](../../com.aspose.threed/geometry).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) |  |
| useFloat | boolean | Использовать тип float вместо double |

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### get(int index) {#get-int-}
```
public VertexField get(int index)
```


Получает [VertexField](../../com.aspose.threed/vertexfield) по индексу

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int |  |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield) - the [VertexField](../../com.aspose.threed/vertexfield) by index
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


Получает количество всех полей, определённых в этом [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)

**Returns:**
int - количество всех полей, определённых в этом [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### getSealed() {#getSealed--}
```
public boolean getSealed()
```


A [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) будет запечатан, когда его использует [TriMesh](../../com.aspose.threed/trimesh), дальнейшие изменения не допускаются.

**Returns:**
boolean - [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) будет запечатан, когда его использует [TriMesh](../../com.aspose.threed/trimesh), дальнейшие изменения запрещены.
### getSize() {#getSize--}
```
public int getSize()
```


Размер в байтах структуры вершины.

**Returns:**
int - Размер структуры вершины в байтах.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этой строки.

**Returns:**
int - 32-битный знаковый целочисленный хеш-код.
### iterator() {#iterator--}
```
public Iterator<VertexField> iterator()
```


Получает перечислитель для обхода всех полей вершины в этом экземпляре.

**Returns:**
java.util.Iterator<com.aspose.threed.VertexField> - Перечислитель
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


Строковое представление [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)

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

