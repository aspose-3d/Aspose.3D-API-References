---
title: "WindowHandle"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Gestionnaire de fenêtre encapsulé pour différentes plateformes."
type: docs
weight: 232
url: /fr/java/com.aspose.threed/windowhandle/
---

**Inheritance:**
java.lang.Object
```
public class WindowHandle
```

Gestionnaire de fenêtre encapsulé pour différentes plateformes.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromWayland(long display, long surface)](#fromWayland-long-long-) | Créer [WindowHandle](../../com.aspose.threed/windowhandle) à partir d'une surface Wayland |
| [fromWin32(long hWnd)](#fromWin32-long-) | L'instance native HWND dans l'environnement Windows. |
| [fromXlib(long display, long window)](#fromXlib-long-long-) | Créer [WindowHandle](../../com.aspose.threed/windowhandle) à partir d'une fenêtre Xlib |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromWayland(long display, long surface) {#fromWayland-long-long-}
```
public static WindowHandle fromWayland(long display, long surface)
```


Créer [WindowHandle](../../com.aspose.threed/windowhandle) à partir d'une surface Wayland

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| affichage | long | L'instance d'affichage du serveur Wayland |
| surface | long | Le handle de la surface |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromWin32(long hWnd) {#fromWin32-long-}
```
public static WindowHandle fromWin32(long hWnd)
```


L'instance native HWND dans l'environnement Windows.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| hWnd | long | Le handle de la fenêtre native Win32 |

**Returns:**
[WindowHandle](../../com.aspose.threed/windowhandle)
### fromXlib(long display, long window) {#fromXlib-long-long-}
```
public static WindowHandle fromXlib(long display, long window)
```


Créer [WindowHandle](../../com.aspose.threed/windowhandle) à partir d'une fenêtre Xlib

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| affichage | long | L'instance d'affichage du serveur X |
| fenêtre | long | Le handle de la fenêtre |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

