---
title: WindowHandle
second_title: Aspose.3D for Java API 레퍼런스
description: 다양한 플랫폼용 캡슐화된 윈도우 핸들.
type: docs
weight: 232
url: /ko/java/com.aspose.threed/windowhandle/
---

**Inheritance:**
java.lang.Object
```
public class WindowHandle
```

다양한 플랫폼용 캡슐화된 윈도우 핸들.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromWayland(long display, long surface)](#fromWayland-long-long-) | Wayland 표면에서 [WindowHandle](../../com.aspose.threed/windowhandle)를 생성합니다 |
| [fromWin32(long hWnd)](#fromWin32-long-) | Windows 환경에서의 네이티브 HWND 인스턴스입니다. |
| [fromXlib(long display, long window)](#fromXlib-long-long-) | Xlib 창에서 [WindowHandle](../../com.aspose.threed/windowhandle)를 생성합니다 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromWayland(long display, long surface) {#fromWayland-long-long-}
```
public static WindowHandle fromWayland(long display, long surface)
```


Wayland 표면에서 [WindowHandle](../../com.aspose.threed/windowhandle)를 생성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 디스플레이 | long | Wayland 서버의 디스플레이 인스턴스입니다. |
| 표면 | long | 표면의 핸들입니다. |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromWin32(long hWnd) {#fromWin32-long-}
```
public static WindowHandle fromWin32(long hWnd)
```


Windows 환경에서의 네이티브 HWND 인스턴스입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hWnd | long | 네이티브 Win32 창의 핸들입니다. |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromXlib(long display, long window) {#fromXlib-long-long-}
```
public static WindowHandle fromXlib(long display, long window)
```


Xlib 창에서 [WindowHandle](../../com.aspose.threed/windowhandle)를 생성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 디스플레이 | long | X 서버의 디스플레이 인스턴스입니다. |
| 창 | long | 창의 핸들입니다. |

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

