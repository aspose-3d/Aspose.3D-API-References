---
title: Viewport
second_title: Справочник API Aspose.3D для Java
description: A  содержит по крайней мере один viewport для рендеринга сцены.
type: docs
weight: 229
url: /ru/java/com.aspose.threed/viewport/
---

**Inheritance:**
java.lang.Object
```
public class Viewport
```

A [IRenderTarget](../../com.aspose.threed/irendertarget) содержит по крайней мере один viewport для рендеринга сцены.
## Методы

| Метод | Описание |
| --- | --- |
| [clone()](#clone--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArea()](#getArea--) | Получает площадь viewport в render target. |
| [getBackgroundColor()](#getBackgroundColor--) | Получает цвет фона viewport. |
| [getClass()](#getClass--) |  |
| [getDepthClear()](#getDepthClear--) | Получает значение глубины, используемое при очистке viewport с установленным битом буфера глубины. |
| [getEnabled()](#getEnabled--) | Включить или отключить этот viewport. |
| [getFrustum()](#getFrustum--) | Получает камеру этого [Viewport](../../com.aspose.threed/viewport) |
| [getRenderTarget()](#getRenderTarget--) | Получает render target, создавший этот viewport. |
| [getZOrder()](#getZOrder--) | Получает порядок Z-слоя области просмотра. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArea(RelativeRectangle value)](#setArea-com.aspose.threed.RelativeRectangle-) | Устанавливает площадь области просмотра в целевом рендере. |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | Устанавливает цвет фона области просмотра. |
| [setDepthClear(float value)](#setDepthClear-float-) | Устанавливает значение глубины, используемое при очистке области просмотра с установленным битом буфера глубины. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Включить или отключить этот viewport. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | Устанавливает камеру этой [Viewport](../../com.aspose.threed/viewport) |
| [setZOrder(int value)](#setZOrder-int-) | Устанавливает порядок Z-слоя области просмотра. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clone() {#clone--}
```
public Viewport clone()
```




**Returns:**
[Viewport](../../com.aspose.threed/viewport)
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
### getArea() {#getArea--}
```
public RelativeRectangle getArea()
```


Получает площадь viewport в render target.

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle) - the area of the viewport in render target.
### getBackgroundColor() {#getBackgroundColor--}
```
public Vector3 getBackgroundColor()
```


Получает цвет фона viewport.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the background color of the viewport.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDepthClear() {#getDepthClear--}
```
public float getDepthClear()
```


Получает значение глубины, используемое при очистке viewport с установленным битом буфера глубины.

**Returns:**
float — значение глубины, используемое при очистке области просмотра с установленным битом буфера глубины.
### getEnabled() {#getEnabled--}
```
public boolean getEnabled()
```


Включить или отключить этот viewport.

**Returns:**
boolean — включить или отключить эту область просмотра.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


Получает камеру этого [Viewport](../../com.aspose.threed/viewport)

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the camera of this [Viewport](../../com.aspose.threed/viewport)
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


Получает render target, создавший этот viewport.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - the render target that created this viewport.
### getZOrder() {#getZOrder--}
```
public int getZOrder()
```


Получает порядок Z-слоя области просмотра.

**Returns:**
int — порядок Z-слоя области просмотра.
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




### setArea(RelativeRectangle value) {#setArea-com.aspose.threed.RelativeRectangle-}
```
public void setArea(RelativeRectangle value)
```


Устанавливает площадь области просмотра в целевом рендере.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Новое значение |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


Устанавливает цвет фона области просмотра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Новое значение |

### setDepthClear(float value) {#setDepthClear-float-}
```
public void setDepthClear(float value)
```


Устанавливает значение глубины, используемое при очистке области просмотра с установленным битом буфера глубины.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Новое значение |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Включить или отключить этот viewport.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


Устанавливает камеру этой [Viewport](../../com.aspose.threed/viewport)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | Новое значение |

### setZOrder(int value) {#setZOrder-int-}
```
public void setZOrder(int value)
```


Устанавливает порядок Z-слоя области просмотра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

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

