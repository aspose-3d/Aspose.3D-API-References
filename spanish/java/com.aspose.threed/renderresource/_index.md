---
title: RenderResource
second_title: Referencia de API de Aspose.3D para Java
description: La clase abstracta de todos los recursos de renderizado. Todos los recursos de renderizado se liberarán cuando el renderizador sea liberado.
type: docs
weight: 150
url: /es/java/com.aspose.threed/renderresource/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class RenderResource implements Closeable
```

La clase abstracta de todos los recursos de renderizado. Todos los recursos de renderizado se liberarán cuando el renderizador sea liberado. Clases como [Mesh](../../com.aspose.threed/mesh)/[Texture](../../com.aspose.threed/texture) tendrán un RenderResource correspondiente
## Constructores

| Constructor | Descripción |
| --- | --- |
| [RenderResource()](#RenderResource--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [close()](#close--) | Liberar los recursos internos utilizados por [RenderResource](../../com.aspose.threed/renderresource) |
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


Liberar los recursos internos utilizados por [RenderResource](../../com.aspose.threed/renderresource)

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

