---
title: "مقبض النافذة"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "مقبض نافذة مغلق لمنصات مختلفة."
type: docs
weight: 232
url: /ar/java/com.aspose.threed/windowhandle/
---

**Inheritance:**
java.lang.Object
```
public class WindowHandle
```

مقبض نافذة مغلق لمنصات مختلفة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromWayland(long display, long surface)](#fromWayland-long-long-) | إنشاء [WindowHandle](../../com.aspose.threed/windowhandle) من سطح Wayland |
| [fromWin32(long hWnd)](#fromWin32-long-) | مثيل HWND الأصلي في بيئة Windows. |
| [fromXlib(long display, long window)](#fromXlib-long-long-) | إنشاء [WindowHandle](../../com.aspose.threed/windowhandle) من نافذة Xlib |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromWayland(long display, long surface) {#fromWayland-long-long-}
```
public static WindowHandle fromWayland(long display, long surface)
```


إنشاء [WindowHandle](../../com.aspose.threed/windowhandle) من سطح Wayland

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | long | مثيل العرض لخادم Wayland |
| السطح | long | مقبض السطح |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromWin32(long hWnd) {#fromWin32-long-}
```
public static WindowHandle fromWin32(long hWnd)
```


مثيل HWND الأصلي في بيئة Windows.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| hWnd | long | مقبض نافذة Win32 الأصلية |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromXlib(long display, long window) {#fromXlib-long-long-}
```
public static WindowHandle fromXlib(long display, long window)
```


إنشاء [WindowHandle](../../com.aspose.threed/windowhandle) من نافذة Xlib

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | long | مثيل العرض لخادم X |
| النافذة | long | مقبض النافذة |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

