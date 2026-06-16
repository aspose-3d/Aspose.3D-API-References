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
| [fromWayland(long display, long surface)](#fromWayland-long-long-) | [WindowHandle](../../com.aspose.threed/windowhandle) nesnesini bir Wayland yüzeyinden oluştur |
| [fromWin32(long hWnd)](#fromWin32-long-) | Windows ortamındaki yerel HWND örneği. |
| [fromXlib(long display, long window)](#fromXlib-long-long-) | [WindowHandle](../../com.aspose.threed/windowhandle) nesnesini bir Xlib penceresinden oluştur |
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


[WindowHandle](../../com.aspose.threed/windowhandle) nesnesini bir Wayland yüzeyinden oluştur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ekran | long | Wayland sunucusunun ekran örneği |
| yüzey | long | Yüzeyin tutamağı |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromWin32(long hWnd) {#fromWin32-long-}
```
public static WindowHandle fromWin32(long hWnd)
```


Windows ortamındaki yerel HWND örneği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hWnd | long | Yerel Win32 penceresinin tutamağı |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromXlib(long display, long window) {#fromXlib-long-long-}
```
public static WindowHandle fromXlib(long display, long window)
```


[WindowHandle](../../com.aspose.threed/windowhandle) nesnesini bir Xlib penceresinden oluştur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ekran | long | X sunucusunun ekran örneği |
| pencere | long | Pencerenin tutamağı |

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

