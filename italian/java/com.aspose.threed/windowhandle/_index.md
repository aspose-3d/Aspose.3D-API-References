---
title: WindowHandle
second_title: Aspose.3D for Java API Reference
description: Handle della finestra incapsulato per diverse piattaforme.
type: docs
weight: 232
url: /it/java/com.aspose.threed/windowhandle/
---

**Inheritance:**
java.lang.Object
```
public class WindowHandle
```

Handle della finestra incapsulato per diverse piattaforme.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromWayland(long display, long surface)](#fromWayland-long-long-) | Crea [WindowHandle](../../com.aspose.threed/windowhandle) da una superficie Wayland |
| [fromWin32(long hWnd)](#fromWin32-long-) | L'istanza nativa HWND nell'ambiente Windows. |
| [fromXlib(long display, long window)](#fromXlib-long-long-) | Crea [WindowHandle](../../com.aspose.threed/windowhandle) da una finestra Xlib |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromWayland(long display, long surface) {#fromWayland-long-long-}
```
public static WindowHandle fromWayland(long display, long surface)
```


Crea [WindowHandle](../../com.aspose.threed/windowhandle) da una superficie Wayland

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| schermo | long | L'istanza display del server Wayland |
| superficie | long | Il handle della superficie |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromWin32(long hWnd) {#fromWin32-long-}
```
public static WindowHandle fromWin32(long hWnd)
```


L'istanza nativa HWND nell'ambiente Windows.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hWnd | long | Il handle della finestra nativa Win32 |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromXlib(long display, long window) {#fromXlib-long-long-}
```
public static WindowHandle fromXlib(long display, long window)
```


Crea [WindowHandle](../../com.aspose.threed/windowhandle) da una finestra Xlib

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| schermo | long | L'istanza display del server X |
| finestra | long | Il handle della finestra |

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

