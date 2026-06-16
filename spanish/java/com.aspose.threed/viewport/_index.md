---
title: Viewport
second_title: Referencia de API de Aspose.3D para Java
description: Un  contiene al menos un viewport para renderizar la escena.
type: docs
weight: 229
url: /es/java/com.aspose.threed/viewport/
---

**Inheritance:**
java.lang.Object
```
public class Viewport
```

Un [IRenderTarget](../../com.aspose.threed/irendertarget) contiene al menos un viewport para renderizar la escena.
## Métodos

| Método | Descripción |
| --- | --- |
| [clone()](#clone--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArea()](#getArea--) | Obtiene el área del viewport en el objetivo de renderizado. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtiene el color de fondo del viewport. |
| [getClass()](#getClass--) |  |
| [getDepthClear()](#getDepthClear--) | Obtiene el valor de profundidad usado al limpiar el viewport con el bit de búfer de profundidad activado. |
| [getEnabled()](#getEnabled--) | Habilita o deshabilita este viewport. |
| [getFrustum()](#getFrustum--) | Obtiene la cámara de este [Viewport](../../com.aspose.threed/viewport) |
| [getRenderTarget()](#getRenderTarget--) | Obtiene el objetivo de renderizado que creó este viewport. |
| [getZOrder()](#getZOrder--) | Obtiene el orden Z del viewport. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArea(RelativeRectangle value)](#setArea-com.aspose.threed.RelativeRectangle-) | Establece el área del viewport en el objetivo de renderizado. |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | Establece el color de fondo del viewport. |
| [setDepthClear(float value)](#setDepthClear-float-) | Establece el valor de profundidad usado al limpiar el viewport con el bit de búfer de profundidad activado. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Habilita o deshabilita este viewport. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | Establece la cámara de este [Viewport](../../com.aspose.threed/viewport) |
| [setZOrder(int value)](#setZOrder-int-) | Establece el orden Z del viewport. |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getArea() {#getArea--}
```
public RelativeRectangle getArea()
```


Obtiene el área del viewport en el objetivo de renderizado.

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle) - the area of the viewport in render target.
### getBackgroundColor() {#getBackgroundColor--}
```
public Vector3 getBackgroundColor()
```


Obtiene el color de fondo del viewport.

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


Obtiene el valor de profundidad usado al limpiar el viewport con el bit de búfer de profundidad activado.

**Returns:**
float - el valor de profundidad usado al limpiar el viewport con el bit de búfer de profundidad activado.
### getEnabled() {#getEnabled--}
```
public boolean getEnabled()
```


Habilita o deshabilita este viewport.

**Returns:**
boolean - Habilitar o deshabilitar este viewport.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


Obtiene la cámara de este [Viewport](../../com.aspose.threed/viewport)

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the camera of this [Viewport](../../com.aspose.threed/viewport)
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


Obtiene el objetivo de renderizado que creó este viewport.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - the render target that created this viewport.
### getZOrder() {#getZOrder--}
```
public int getZOrder()
```


Obtiene el orden Z del viewport.

**Returns:**
int - el orden Z del viewport.
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


Establece el área del viewport en el objetivo de renderizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Nuevo valor |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


Establece el color de fondo del viewport.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor |

### setDepthClear(float value) {#setDepthClear-float-}
```
public void setDepthClear(float value)
```


Establece el valor de profundidad usado al limpiar el viewport con el bit de búfer de profundidad activado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | Nuevo valor |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Habilita o deshabilita este viewport.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


Establece la cámara de este [Viewport](../../com.aspose.threed/viewport)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | Nuevo valor |

### setZOrder(int value) {#setZOrder-int-}
```
public void setZOrder(int value)
```


Establece el orden Z del viewport.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Nuevo valor |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

