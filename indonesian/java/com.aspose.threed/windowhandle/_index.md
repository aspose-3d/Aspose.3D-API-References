---
title: WindowHandle
second_title: Referensi API Aspose.3D untuk Java
description: Handle jendela yang dibungkus untuk berbagai platform.
type: docs
weight: 232
url: /id/java/com.aspose.threed/windowhandle/
---

**Inheritance:**
java.lang.Object
```
public class WindowHandle
```

Handle jendela yang dibungkus untuk berbagai platform.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromWayland(long display, long surface)](#fromWayland-long-long-) | Membuat [WindowHandle](../../com.aspose.threed/windowhandle) dari permukaan Wayland |
| [fromWin32(long hWnd)](#fromWin32-long-) | Instansi HWND asli dalam lingkungan Windows. |
| [fromXlib(long display, long window)](#fromXlib-long-long-) | Membuat [WindowHandle](../../com.aspose.threed/windowhandle) dari jendela Xlib |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromWayland(long display, long surface) {#fromWayland-long-long-}
```
public static WindowHandle fromWayland(long display, long surface)
```


Membuat [WindowHandle](../../com.aspose.threed/windowhandle) dari permukaan Wayland

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tampilan | long | Instansi tampilan dari server Wayland |
| permukaan | long | Pegangan permukaan |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromWin32(long hWnd) {#fromWin32-long-}
```
public static WindowHandle fromWin32(long hWnd)
```


Instansi HWND asli dalam lingkungan Windows.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hWnd | long | Pegangan jendela Win32 asli |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromXlib(long display, long window) {#fromXlib-long-long-}
```
public static WindowHandle fromXlib(long display, long window)
```


Membuat [WindowHandle](../../com.aspose.threed/windowhandle) dari jendela Xlib

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tampilan | long | Instansi tampilan dari server X |
| jendela | long | Pegangan jendela |

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

