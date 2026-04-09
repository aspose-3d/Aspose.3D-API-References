---
title: WindowHandle
second_title: Aspose.3D for Java API リファレンス
description: 異なるプラットフォーム用のカプセル化されたウィンドウハンドル。
type: docs
weight: 232
url: /ja/java/com.aspose.threed/windowhandle/
---

**Inheritance:**
java.lang.Object
```
public class WindowHandle
```

異なるプラットフォーム用のカプセル化されたウィンドウハンドル。
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromWayland(long display, long surface)](#fromWayland-long-long-) | Wayland サーフェスから [WindowHandle](../../com.aspose.threed/windowhandle) を作成します |
| [fromWin32(long hWnd)](#fromWin32-long-) | Windows 環境におけるネイティブ HWND インスタンスです。 |
| [fromXlib(long display, long window)](#fromXlib-long-long-) | Xlib ウィンドウから [WindowHandle](../../com.aspose.threed/windowhandle) を作成します |
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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromWayland(long display, long surface) {#fromWayland-long-long-}
```
public static WindowHandle fromWayland(long display, long surface)
```


Wayland サーフェスから [WindowHandle](../../com.aspose.threed/windowhandle) を作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ディスプレイ | long | Wayland サーバーのディスプレイインスタンスです |
| サーフェス | long | サーフェスのハンドルです |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromWin32(long hWnd) {#fromWin32-long-}
```
public static WindowHandle fromWin32(long hWnd)
```


Windows 環境におけるネイティブ HWND インスタンスです。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| hWnd | long | ネイティブ Win32 ウィンドウのハンドルです |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromXlib(long display, long window) {#fromXlib-long-long-}
```
public static WindowHandle fromXlib(long display, long window)
```


Xlib ウィンドウから [WindowHandle](../../com.aspose.threed/windowhandle) を作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ディスプレイ | long | X サーバーのディスプレイインスタンスです |
| ウィンドウ | long | ウィンドウのハンドルです |

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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

