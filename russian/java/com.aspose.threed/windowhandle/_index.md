---
title: WindowHandle
second_title: Справочник API Aspose.3D для Java
description: Инкапсулированный дескриптор окна для разных платформ.
type: docs
weight: 232
url: /ru/java/com.aspose.threed/windowhandle/
---

**Inheritance:**
java.lang.Object
```
public class WindowHandle
```

Инкапсулированный дескриптор окна для разных платформ.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromWayland(long display, long surface)](#fromWayland-long-long-) | Создать [WindowHandle](../../com.aspose.threed/windowhandle) из Wayland‑поверхности |
| [fromWin32(long hWnd)](#fromWin32-long-) | Нативный экземпляр HWND в среде Windows. |
| [fromXlib(long display, long window)](#fromXlib-long-long-) | Создать [WindowHandle](../../com.aspose.threed/windowhandle) из окна Xlib |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromWayland(long display, long surface) {#fromWayland-long-long-}
```
public static WindowHandle fromWayland(long display, long surface)
```


Создать [WindowHandle](../../com.aspose.threed/windowhandle) из Wayland‑поверхности

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| дисплей | long | Экземпляр дисплея Wayland‑сервера |
| поверхность | long | Дескриптор поверхности |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromWin32(long hWnd) {#fromWin32-long-}
```
public static WindowHandle fromWin32(long hWnd)
```


Нативный экземпляр HWND в среде Windows.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hWnd | long | Дескриптор нативного окна Win32 |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromXlib(long display, long window) {#fromXlib-long-long-}
```
public static WindowHandle fromXlib(long display, long window)
```


Создать [WindowHandle](../../com.aspose.threed/windowhandle) из окна Xlib

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| дисплей | long | Экземпляр дисплея X‑сервера |
| окно | long | Дескриптор окна |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

