---
title: WindowHandle
second_title: Referencia de API de Aspose.3D para Java
description: Manejador de ventana encapsulado para diferentes plataformas.
type: docs
weight: 232
url: /es/java/com.aspose.threed/windowhandle/
---

**Inheritance:**
java.lang.Object
```
public class WindowHandle
```

Manejador de ventana encapsulado para diferentes plataformas.
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromWayland(long display, long surface)](#fromWayland-long-long-) | Crear [WindowHandle](../../com.aspose.threed/windowhandle) a partir de una superficie Wayland |
| [fromWin32(long hWnd)](#fromWin32-long-) | La instancia nativa HWND en el entorno Windows. |
| [fromXlib(long display, long window)](#fromXlib-long-long-) | Crear [WindowHandle](../../com.aspose.threed/windowhandle) a partir de una ventana Xlib |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### fromWayland(long display, long surface) {#fromWayland-long-long-}
```
public static WindowHandle fromWayland(long display, long surface)
```


Crear [WindowHandle](../../com.aspose.threed/windowhandle) a partir de una superficie Wayland

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| display | long | La instancia de pantalla del servidor Wayland |
| surface | long | El identificador de la superficie |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromWin32(long hWnd) {#fromWin32-long-}
```
public static WindowHandle fromWin32(long hWnd)
```


La instancia nativa HWND en el entorno Windows.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hWnd | long | El identificador de la ventana nativa Win32 |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromXlib(long display, long window) {#fromXlib-long-long-}
```
public static WindowHandle fromXlib(long display, long window)
```


Crear [WindowHandle](../../com.aspose.threed/windowhandle) a partir de una ventana Xlib

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| display | long | La instancia de pantalla del servidor X |
| window | long | El identificador de la ventana |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
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

