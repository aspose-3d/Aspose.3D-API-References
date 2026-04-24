---
title: WindowHandle
second_title: Aspose.3D for Java API-referens
description: Inkapslad fönsterhandtag för olika plattformar.
type: docs
weight: 232
url: /sv/java/com.aspose.threed/windowhandle/
---

**Inheritance:**
java.lang.Object
```
public class WindowHandle
```

Inkapslad fönsterhandtag för olika plattformar.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromWayland(long display, long surface)](#fromWayland-long-long-) | Skapa [WindowHandle](../../com.aspose.threed/windowhandle) från en Wayland-yta |
| [fromWin32(long hWnd)](#fromWin32-long-) | Den inhemska HWND-instansen i Windows-miljö. |
| [fromXlib(long display, long window)](#fromXlib-long-long-) | Skapa [WindowHandle](../../com.aspose.threed/windowhandle) från ett Xlib-fönster |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromWayland(long display, long surface) {#fromWayland-long-long-}
```
public static WindowHandle fromWayland(long display, long surface)
```


Skapa [WindowHandle](../../com.aspose.threed/windowhandle) från en Wayland-yta

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| display | long | Display-instansen för Wayland-servern |
| yta | long | Handtaget för ytan |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromWin32(long hWnd) {#fromWin32-long-}
```
public static WindowHandle fromWin32(long hWnd)
```


Den inhemska HWND-instansen i Windows-miljö.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hWnd | long | Handtaget för det inhemska Win32-fönstret |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromXlib(long display, long window) {#fromXlib-long-long-}
```
public static WindowHandle fromXlib(long display, long window)
```


Skapa [WindowHandle](../../com.aspose.threed/windowhandle) från ett Xlib-fönster

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| display | long | Display-instansen för X-servern |
| fönster | long | Handtaget för fönstret |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

