---
title: WindowHandle
second_title: Aspose.3D for Java API Reference
description: विभिन्न प्लेटफ़ॉर्म के लिए संलग्न विंडो हैंडल।
type: docs
weight: 232
url: /hi/java/com.aspose.threed/windowhandle/
---

**Inheritance:**
java.lang.Object
```
public class WindowHandle
```

विभिन्न प्लेटफ़ॉर्म के लिए संलग्न विंडो हैंडल।
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromWayland(long display, long surface)](#fromWayland-long-long-) | Wayland सतह से [WindowHandle](../../com.aspose.threed/windowhandle) बनाएं |
| [fromWin32(long hWnd)](#fromWin32-long-) | Windows वातावरण में मूल HWND इंस्टेंस। |
| [fromXlib(long display, long window)](#fromXlib-long-long-) | Xlib विंडो से [WindowHandle](../../com.aspose.threed/windowhandle) बनाएं |
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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromWayland(long display, long surface) {#fromWayland-long-long-}
```
public static WindowHandle fromWayland(long display, long surface)
```


Wayland सतह से [WindowHandle](../../com.aspose.threed/windowhandle) बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| डिस्प्ले | long | Wayland सर्वर का डिस्प्ले इंस्टेंस |
| सतह | long | सतह का हैंडल |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromWin32(long hWnd) {#fromWin32-long-}
```
public static WindowHandle fromWin32(long hWnd)
```


Windows वातावरण में मूल HWND इंस्टेंस।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| hWnd | long | मूल Win32 विंडो का हैंडल |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromXlib(long display, long window) {#fromXlib-long-long-}
```
public static WindowHandle fromXlib(long display, long window)
```


Xlib विंडो से [WindowHandle](../../com.aspose.threed/windowhandle) बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| डिस्प्ले | long | X सर्वर का डिस्प्ले इंस्टेंस |
| विंडो | long | विंडो का हैंडल |

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

