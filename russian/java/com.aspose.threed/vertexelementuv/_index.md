---
title: VertexElementUV
second_title: Справочник API Aspose.3D для Java
description: Определяет UV‑координаты для указанных компонентов.
type: docs
weight: 220
url: /ru/java/com.aspose.threed/vertexelementuv/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.VertexElement](../../com.aspose.threed/vertexelement), [com.aspose.threed.VertexElementVector4](../../com.aspose.threed/vertexelementvector4)
```
public class VertexElementUV extends VertexElementVector4
```

Определяет UV‑координаты для указанных компонентов. Геометрия может иметь несколько элементов [VertexElementUV](../../com.aspose.threed/vertexelementuv), и каждый из них имеет разные [TextureMapping](../../com.aspose.threed/texturemapping).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [VertexElementUV()](#VertexElementUV--) | Инициализирует новый экземпляр класса [VertexElementUV](../../com.aspose.threed/vertexelementuv). |
| [VertexElementUV(TextureMapping textureMapping)](#VertexElementUV-com.aspose.threed.TextureMapping-) | Инициализирует новый экземпляр класса [VertexElementUV](../../com.aspose.threed/vertexelementuv). |
## Методы

| Метод | Описание |
| --- | --- |
| [addData(Iterable<Vector2> data)](#addData-java.lang.Iterable-com.aspose.threed.Vector2--) | Добавьте набор [Vector2](../../com.aspose.threed/vector2) в VertexElementUV.Data. |
| [addData2(Iterable<Vector3> data)](#addData2-java.lang.Iterable-com.aspose.threed.Vector3--) | Добавьте набор [Vector3](../../com.aspose.threed/vector3) в VertexElementUV.Data. |
| [clear()](#clear--) | Удаляет все элементы из массивов direct и index. |
| [clone(boolean withData)](#clone-boolean-) | Глубокое клонирование элемента вершины |
| [clone(boolean withDirect, boolean withIndice)](#clone-boolean-boolean-) |  |
| [copyTo(VertexElementVector4 target)](#copyTo-com.aspose.threed.VertexElementVector4-) | Копирует данные в указанный элемент |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Получает данные вершины |
| [getIndices()](#getIndices--) | Получает данные индексов |
| [getMappingMode()](#getMappingMode--) | Получает, как элемент отображён. |
| [getName()](#getName--) | Получает имя. |
| [getReferenceMode()](#getReferenceMode--) | Получает, как элемент ссылается. |
| [getVertexElementType()](#getVertexElementType--) | Получает тип [VertexElement](../../com.aspose.threed/vertexelement) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setData(Vector4[] data)](#setData-com.aspose.threed.Vector4---) | Загрузить данные |
| [setIndices(int[] data)](#setIndices-int---) | Загрузить индексы |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | Устанавливает способ отображения элемента. |
| [setName(String value)](#setName-java.lang.String-) | Устанавливает имя. |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | Устанавливает, как элемент ссылается. |
| [toString()](#toString--) | Строковое представление элемента вершины. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexElementUV() {#VertexElementUV--}
```
public VertexElementUV()
```


Инициализирует новый экземпляр класса [VertexElementUV](../../com.aspose.threed/vertexelementuv). Тип текстурного отображения по умолчанию — [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE).

### VertexElementUV(TextureMapping textureMapping) {#VertexElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV(TextureMapping textureMapping)
```


Инициализирует новый экземпляр класса [VertexElementUV](../../com.aspose.threed/vertexelementuv).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | Тип текстурного отображения. |

### addData(Iterable<Vector2> data) {#addData-java.lang.Iterable-com.aspose.threed.Vector2--}
```
public void addData(Iterable<Vector2> data)
```


Добавьте набор [Vector2](../../com.aspose.threed/vector2) в VertexElementUV.Data. Это сокращение, данный метод преобразует [Vector2](../../com.aspose.threed/vector2) в [Vector4](../../com.aspose.threed/vector4), задавая z = 0 и w = 0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | java.lang.Iterable<com.aspose.threed.Vector2> |  |

### addData2(Iterable<Vector3> data) {#addData2-java.lang.Iterable-com.aspose.threed.Vector3--}
```
public void addData2(Iterable<Vector3> data)
```


Добавьте набор [Vector3](../../com.aspose.threed/vector3) в VertexElementUV.Data. Это сокращение, данный метод преобразует [Vector3](../../com.aspose.threed/vector3) в [Vector4](../../com.aspose.threed/vector4), задавая w = 0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | java.lang.Iterable<com.aspose.threed.Vector3> |  |

### clear() {#clear--}
```
public void clear()
```


Удаляет все элементы из массивов direct и index.

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
### copyTo(VertexElementVector4 target) {#copyTo-com.aspose.threed.VertexElementVector4-}
```
public void copyTo(VertexElementVector4 target)
```


Копирует данные в указанный элемент

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| target | [VertexElementVector4](../../com.aspose.threed/vertexelementvector4) | Цель. |

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
public List<Vector4> getData()
```


Получает данные вершины

**Returns:**
java.util.List<com.aspose.threed.Vector4> - данные вершины
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




### setData(Vector4[] data) {#setData-com.aspose.threed.Vector4---}
```
public void setData(Vector4[] data)
```


Загрузить данные

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | [Vector4\[\]](../../com.aspose.threed/vector4) |  |

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

