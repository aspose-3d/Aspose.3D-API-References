---
title: RenderResource
second_title: Aspose.3D for Java API Reference
description: La classe astratta di tutte le risorse di rendering. Tutte le risorse di rendering saranno rilasciate quando il renderer viene rilasciato.
type: docs
weight: 150
url: /it/java/com.aspose.threed/renderresource/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class RenderResource implements Closeable
```

La classe astratta di tutte le risorse di rendering. Tutte le risorse di rendering saranno rilasciate quando il renderer viene rilasciato. Classi come [Mesh](../../com.aspose.threed/mesh)/[Texture](../../com.aspose.threed/texture) avranno un corrispondente RenderResource
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RenderResource()](#RenderResource--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [close()](#close--) | Rilascia le risorse interne utilizzate da [RenderResource](../../com.aspose.threed/renderresource) |
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


Rilascia le risorse interne utilizzate da [RenderResource](../../com.aspose.threed/renderresource)

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

