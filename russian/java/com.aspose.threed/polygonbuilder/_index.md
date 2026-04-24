---
title: PolygonBuilder
second_title: Справочник API Aspose.3D для Java
description: Вспомогательный класс для построения полигонов для  Example
type: docs
weight: 133
url: /ru/java/com.aspose.threed/polygonbuilder/
---

**Inheritance:**
java.lang.Object
```
public final class PolygonBuilder
```

Вспомогательный класс для построения полигона для [Mesh](../../com.aspose.threed/mesh) **Пример:**

```
Mesh mesh = new Mesh();
  PolygonBuilder builder = new PolygonBuilder(mesh);
  builder.begin();
  builder.addVertex(0);
  builder.addVertex(1);
  builder.addVertex(2);
  builder.end();
```

Равно :

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

Если все индексы готовы к использованию, предпочтительнее использовать [Mesh](../../com.aspose.threed/mesh), иначе лучше выбрать [PolygonBuilder](../../com.aspose.threed/polygonbuilder).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PolygonBuilder(Mesh mesh)](#PolygonBuilder-com.aspose.threed.Mesh-) | Инициализирует новый экземпляр класса [PolygonBuilder](../../com.aspose.threed/polygonbuilder). |
## Методы

| Метод | Описание |
| --- | --- |
| [addVertex(int index)](#addVertex-int-) | Добавляет индекс вершины к полигону |
| [begin()](#begin--) | Начинает добавлять новый полигон |
| [end()](#end--) | Завершает создание полигона |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PolygonBuilder(Mesh mesh) {#PolygonBuilder-com.aspose.threed.Mesh-}
```
public PolygonBuilder(Mesh mesh)
```


Инициализирует новый экземпляр класса [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | На каком меше строить полигон. |

### addVertex(int index) {#addVertex-int-}
```
public void addVertex(int index)
```


Добавляет индекс вершины к полигону

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int |  |

### begin() {#begin--}
```
public void begin()
```


Начинает добавлять новый полигон

### end() {#end--}
```
public void end()
```


Завершает создание полигона

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

