---
title: "WindowHandle"
second_title: "Aspose.3D for Java API 参考"
description: "针对不同平台的封装窗口句柄。"
type: docs
weight: 232
url: /zh/java/com.aspose.threed/windowhandle/
---

**Inheritance:**
java.lang.Object
```
public class WindowHandle
```

针对不同平台的封装窗口句柄。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromWayland(long display, long surface)](#fromWayland-long-long-) | 从 Wayland 表面创建 [WindowHandle](../../com.aspose.threed/windowhandle) |
| [fromWin32(long hWnd)](#fromWin32-long-) | Windows 环境中的本机 HWND 实例。 |
| [fromXlib(long display, long window)](#fromXlib-long-long-) | 从 Xlib 窗口创建 [WindowHandle](../../com.aspose.threed/windowhandle) |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### fromWayland(long display, long surface) {#fromWayland-long-long-}
```
public static WindowHandle fromWayland(long display, long surface)
```


从 Wayland 表面创建 [WindowHandle](../../com.aspose.threed/windowhandle)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 显示 | long | Wayland 服务器的显示实例 |
| 表面 | long | 表面的句柄 |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromWin32(long hWnd) {#fromWin32-long-}
```
public static WindowHandle fromWin32(long hWnd)
```


Windows 环境中的本机 HWND 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hWnd | long | 本机 Win32 窗口的句柄 |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromXlib(long display, long window) {#fromXlib-long-long-}
```
public static WindowHandle fromXlib(long display, long window)
```


从 Xlib 窗口创建 [WindowHandle](../../com.aspose.threed/windowhandle)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 显示 | long | X 服务器的显示实例 |
| 窗口 | long | 窗口的句柄 |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

