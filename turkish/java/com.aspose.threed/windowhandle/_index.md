---
title: "WindowHandle"
second_title: "Aspose.3D for Java API Referansı"
description: "Farklı platformlar için kapsüllenmiş pencere tanıtıcısı."
type: docs
weight: 232
url: /tr/java/com.aspose.threed/windowhandle/
---

**Inheritance:**
java.lang.Object
```
public class WindowHandle
```

Farklı platformlar için kapsüllenmiş pencere tanıtıcısı.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromWayland(long display, long surface)](#fromWayland-long-long-) | Bir Wayland yüzeyinden [WindowHandle](../../com.aspose.threed/windowhandle) oluştur |
| [fromWin32(long hWnd)](#fromWin32-long-) | Windows ortamında yerel HWND örneği. |
| [fromXlib(long display, long window)](#fromXlib-long-long-) | Bir Xlib penceresinden [WindowHandle](../../com.aspose.threed/windowhandle) oluştur |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromWayland(long display, long surface) {#fromWayland-long-long-}
```
public static WindowHandle fromWayland(long display, long surface)
```


Bir Wayland yüzeyinden [WindowHandle](../../com.aspose.threed/windowhandle) oluştur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| display | long | Wayland sunucusunun display örneği |
| surface | long | Yüzeyin tutamacı |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromWin32(long hWnd) {#fromWin32-long-}
```
public static WindowHandle fromWin32(long hWnd)
```


Windows ortamında yerel HWND örneği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hWnd | long | Yerel Win32 penceresinin tutamacı |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromXlib(long display, long window) {#fromXlib-long-long-}
```
public static WindowHandle fromXlib(long display, long window)
```


Bir Xlib penceresinden [WindowHandle](../../com.aspose.threed/windowhandle) oluştur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| display | long | X sunucusunun display örneği |
| pencere | long | Pencerenin tutamacı |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

