---
title: RenderResource
second_title: Справочник API Aspose.3D для Java
description: Абстрактный класс всех ресурсов рендеринга. Все ресурсы рендеринга будут освобождены при освобождении рендерера.
type: docs
weight: 150
url: /ru/java/com.aspose.threed/renderresource/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class RenderResource implements Closeable
```

Абстрактный класс всех ресурсов рендеринга. Все ресурсы рендеринга будут освобождены при освобождении рендерера. Классы, такие как [Mesh](../../com.aspose.threed/mesh)/[Texture](../../com.aspose.threed/texture), будут иметь соответствующий RenderResource
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RenderResource()](#RenderResource--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [close()](#close--) | Освободить внутренние ресурсы, используемые [RenderResource](../../com.aspose.threed/renderresource) |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderResource() {#RenderResource--}
```
public RenderResource()
```


### close() {#close--}
```
public void close()
```


Освободить внутренние ресурсы, используемые [RenderResource](../../com.aspose.threed/renderresource)

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

