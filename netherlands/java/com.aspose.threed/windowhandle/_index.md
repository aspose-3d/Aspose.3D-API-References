---
title: WindowHandle
second_title: Aspose.3D for Java API-referentie
description: Ingekapselde vensterhandle voor verschillende platformen.
type: docs
weight: 232
url: /nl/java/com.aspose.threed/windowhandle/
---

**Inheritance:**
java.lang.Object
```
public class WindowHandle
```

Ingekapselde vensterhandle voor verschillende platformen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromWayland(long display, long surface)](#fromWayland-long-long-) | Maak een [WindowHandle](../../com.aspose.threed/windowhandle) van een Wayland-oppervlak |
| [fromWin32(long hWnd)](#fromWin32-long-) | De native HWND-instantie in Windows-omgeving. |
| [fromXlib(long display, long window)](#fromXlib-long-long-) | Maak een [WindowHandle](../../com.aspose.threed/windowhandle) van een Xlib-venster |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromWayland(long display, long surface) {#fromWayland-long-long-}
```
public static WindowHandle fromWayland(long display, long surface)
```


Maak een [WindowHandle](../../com.aspose.threed/windowhandle) van een Wayland-oppervlak

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scherm | long | De display-instantie van de Wayland-server |
| oppervlak | long | De handle van het oppervlak |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromWin32(long hWnd) {#fromWin32-long-}
```
public static WindowHandle fromWin32(long hWnd)
```


De native HWND-instantie in Windows-omgeving.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hWnd | long | De handle van het native Win32-venster |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromXlib(long display, long window) {#fromXlib-long-long-}
```
public static WindowHandle fromXlib(long display, long window)
```


Maak een [WindowHandle](../../com.aspose.threed/windowhandle) van een Xlib-venster

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scherm | long | De display-instantie van de X-server |
| venster | long | De handle van het venster |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

