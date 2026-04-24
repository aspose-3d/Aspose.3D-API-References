---
title: PdfRenderMode
second_title: Справочник API Aspose.3D для Java
description: Режим рендеринга указывает стиль, в котором рендерится 3D‑артворк.
type: docs
weight: 289
url: /ru/java/com.aspose.threed/pdfrendermode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PdfRenderMode extends Enum<PdfRenderMode>
```

Режим рендеринга указывает стиль, в котором рендерится 3D‑артворк.
## Поля

| Поле | Описание |
| --- | --- |
| [BOUNDING_BOX](#BOUNDING-BOX) | Отображает ребра ограничивающего прямоугольника каждого узла, выровненные по осям локального координатного пространства этого узла. |
| [HIDDEN_WIREFRAME](#HIDDEN-WIREFRAME) | Отображает ребра одним цветом, однако удаляет обратные и скрытые ребра. |
| [ILLUSTRATION](#ILLUSTRATION) | Отображает контурные ребра с поверхностями, удаляет скрытые линии. |
| [SHADED_ILLUSTRATION](#SHADED-ILLUSTRATION) | Отображает контурные ребра с освещёнными и текстурированными поверхностями и дополнительным эмиссионным компонентом для удаления слабо освещённых областей произведения. |
| [SHADED_VERTICES](#SHADED-VERTICES) | Отображает только вершины, однако использует их цвет вершин и применяет освещение. |
| [SHADED_WIREFRAME](#SHADED-WIREFRAME) | Отображает только ребра, однако интерполирует их цвет между двумя вершинами и применяет освещение. |
| [SOLID](#SOLID) | Отображает текстурированные и освещённые геометрические формы. |
| [SOLID_OUTLINE](#SOLID-OUTLINE) | Отображает контурные ребра с освещёнными и текстурированными поверхностями, удаляет скрытые линии. |
| [SOLID_WIREFRAME](#SOLID-WIREFRAME) | Отображает текстурированные и освещённые геометрические формы (треугольники) с одноцветными ребрами поверх них. |
| [TRANSPARENT](#TRANSPARENT) | Отображает текстурированные и освещённые геометрические формы (треугольники) с добавленным уровнем прозрачности. |
| [TRANSPARENT_BOUNDING_BOX](#TRANSPARENT-BOUNDING-BOX) | Отображает грани ограничивающих коробок каждого узла, выровненные по осям локального координатного пространства этого узла, с добавленным уровнем прозрачности. |
| [TRANSPARENT_BOUNDING_BOX_OUTLINE](#TRANSPARENT-BOUNDING-BOX-OUTLINE) | Отображает ребра и грани ограничивающих коробок каждого узла, выровненные по осям локального координатного пространства этого узла, с добавленным уровнем прозрачности. |
| [TRANSPARENT_WIREFRAME](#TRANSPARENT-WIREFRAME) | Отображает текстурированные и освещённые геометрические формы (треугольники) с добавленным уровнем прозрачности, с одноцветными непрозрачными ребрами поверх них. |
| [VERTICES](#VERTICES) | Отображает только вершины одним цветом. |
| [WIREFRAME](#WIREFRAME) | Отображает только ребра одним цветом. |
## Методы

| Метод | Описание |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BOUNDING_BOX {#BOUNDING-BOX}
```
public static final PdfRenderMode BOUNDING_BOX
```


Отображает ребра ограничивающего прямоугольника каждого узла, выровненные по осям локального координатного пространства этого узла.

### HIDDEN_WIREFRAME {#HIDDEN-WIREFRAME}
```
public static final PdfRenderMode HIDDEN_WIREFRAME
```


Отображает ребра одним цветом, однако удаляет обратные и скрытые ребра.

### ILLUSTRATION {#ILLUSTRATION}
```
public static final PdfRenderMode ILLUSTRATION
```


Отображает контурные ребра с поверхностями, удаляет скрытые линии.

### SHADED_ILLUSTRATION {#SHADED-ILLUSTRATION}
```
public static final PdfRenderMode SHADED_ILLUSTRATION
```


Отображает контурные ребра с освещёнными и текстурированными поверхностями и дополнительным эмиссионным компонентом для удаления слабо освещённых областей произведения.

### SHADED_VERTICES {#SHADED-VERTICES}
```
public static final PdfRenderMode SHADED_VERTICES
```


Отображает только вершины, однако использует их цвет вершин и применяет освещение.

### SHADED_WIREFRAME {#SHADED-WIREFRAME}
```
public static final PdfRenderMode SHADED_WIREFRAME
```


Отображает только ребра, однако интерполирует их цвет между двумя вершинами и применяет освещение.

### SOLID {#SOLID}
```
public static final PdfRenderMode SOLID
```


Отображает текстурированные и освещённые геометрические формы.

### SOLID_OUTLINE {#SOLID-OUTLINE}
```
public static final PdfRenderMode SOLID_OUTLINE
```


Отображает контурные ребра с освещёнными и текстурированными поверхностями, удаляет скрытые линии.

### SOLID_WIREFRAME {#SOLID-WIREFRAME}
```
public static final PdfRenderMode SOLID_WIREFRAME
```


Отображает текстурированные и освещённые геометрические формы (треугольники) с одноцветными ребрами поверх них.

### TRANSPARENT {#TRANSPARENT}
```
public static final PdfRenderMode TRANSPARENT
```


Отображает текстурированные и освещённые геометрические формы (треугольники) с добавленным уровнем прозрачности.

### TRANSPARENT_BOUNDING_BOX {#TRANSPARENT-BOUNDING-BOX}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX
```


Отображает грани ограничивающих коробок каждого узла, выровненные по осям локального координатного пространства этого узла, с добавленным уровнем прозрачности.

### TRANSPARENT_BOUNDING_BOX_OUTLINE {#TRANSPARENT-BOUNDING-BOX-OUTLINE}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX_OUTLINE
```


Отображает ребра и грани ограничивающих коробок каждого узла, выровненные по осям локального координатного пространства этого узла, с добавленным уровнем прозрачности.

### TRANSPARENT_WIREFRAME {#TRANSPARENT-WIREFRAME}
```
public static final PdfRenderMode TRANSPARENT_WIREFRAME
```


Отображает текстурированные и освещённые геометрические формы (треугольники) с добавленным уровнем прозрачности, с одноцветными непрозрачными ребрами поверх них.

### VERTICES {#VERTICES}
```
public static final PdfRenderMode VERTICES
```


Отображает только вершины одним цветом.

### WIREFRAME {#WIREFRAME}
```
public static final PdfRenderMode WIREFRAME
```


Отображает только ребра одним цветом.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PdfRenderMode valueOf(String name)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[PdfRenderMode](../../com.aspose.threed/pdfrendermode)
### values() {#values--}
```
public static PdfRenderMode[] values()
```




**Returns:**
com.aspose.threed.PdfRenderMode[]
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

