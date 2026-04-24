---
title: RendererVariableManager
second_title: Referencia de API de Aspose.3D para Java
description: Esta clase gestiona variables usadas en el renderizado
type: docs
weight: 154
url: /es/java/com.aspose.threed/renderervariablemanager/
---

**Inheritance:**
java.lang.Object
```
public abstract class RendererVariableManager
```

Esta clase gestiona variables usadas en el renderizado
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | Posición de la cámara en el sistema de coordenadas del mundo |
| [getClass()](#getClass--) |  |
| [getDepthBias()](#getDepthBias--) | Sesgo de profundidad para mapeado de sombras, el valor predeterminado es 0.001 |
| [getMatrixLightSpace()](#getMatrixLightSpace--) | Matriz para la transformación del espacio de luz |
| [getMatrixProjection()](#getMatrixProjection--) | Matriz para la transformación de proyección |
| [getMatrixView()](#getMatrixView--) | Matriz para la transformación de vista |
| [getMatrixViewProjection()](#getMatrixViewProjection--) | Matriz para la transformación de vista y proyección. |
| [getMatrixWorld()](#getMatrixWorld--) | Matriz para la transformación del mundo |
| [getMatrixWorldNormal()](#getMatrixWorldNormal--) | Matriz para convertir la normal del objeto al espacio mundial. |
| [getMatrixWorldViewProjection()](#getMatrixWorldViewProjection--) | Matriz para la vista del mundo y transformación de proyección |
| [getShadowCaster()](#getShadowCaster--) | Posición del lanzador de sombras en el sistema de coordenadas del mundo |
| [getShadowmap()](#getShadowmap--) | La textura de profundidad utilizada para el mapeo de sombras |
| [getViewportSize()](#getViewportSize--) | Tamaño del viewport, medido en píxeles |
| [getWorldAmbient()](#getWorldAmbient--) | Color ambiental definido en el viewport. |
| [getWorldTime()](#getWorldTime--) | Tiempo en segundos |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(FVector3 value)](#setCameraPosition-com.aspose.threed.FVector3-) | Posición de la cámara en el sistema de coordenadas del mundo |
| [setDepthBias(float value)](#setDepthBias-float-) | Sesgo de profundidad para mapeado de sombras, el valor predeterminado es 0.001 |
| [setMatrixLightSpace(FMatrix4 value)](#setMatrixLightSpace-com.aspose.threed.FMatrix4-) | Matriz para la transformación del espacio de luz |
| [setMatrixProjection(FMatrix4 value)](#setMatrixProjection-com.aspose.threed.FMatrix4-) | Matriz para la transformación de proyección |
| [setMatrixView(FMatrix4 value)](#setMatrixView-com.aspose.threed.FMatrix4-) | Matriz para la transformación de vista |
| [setShadowCaster(FVector3 value)](#setShadowCaster-com.aspose.threed.FVector3-) | Posición del lanzador de sombras en el sistema de coordenadas del mundo |
| [setShadowmap(ITextureUnit value)](#setShadowmap-com.aspose.threed.ITextureUnit-) | La textura de profundidad utilizada para el mapeo de sombras |
| [setViewportSize(FVector2 value)](#setViewportSize-com.aspose.threed.FVector2-) | Tamaño del viewport, medido en píxeles |
| [setWorldAmbient(FVector3 value)](#setWorldAmbient-com.aspose.threed.FVector3-) | Color ambiental definido en el viewport. |
| [setWorldTime(float value)](#setWorldTime-float-) | Tiempo en segundos |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getCameraPosition() {#getCameraPosition--}
```
public FVector3 getCameraPosition()
```


Posición de la cámara en el sistema de coordenadas del mundo

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Camera's position in world coordinate system
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDepthBias() {#getDepthBias--}
```
public float getDepthBias()
```


Sesgo de profundidad para mapeado de sombras, el valor predeterminado es 0.001

**Returns:**
float - Sesgo de profundidad para el mapeo de sombras, el valor predeterminado es 0.001
### getMatrixLightSpace() {#getMatrixLightSpace--}
```
public FMatrix4 getMatrixLightSpace()
```


Matriz para la transformación del espacio de luz

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for light space transformation
### getMatrixProjection() {#getMatrixProjection--}
```
public FMatrix4 getMatrixProjection()
```


Matriz para la transformación de proyección

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for projection transformation
### getMatrixView() {#getMatrixView--}
```
public FMatrix4 getMatrixView()
```


Matriz para la transformación de vista

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view transformation
### getMatrixViewProjection() {#getMatrixViewProjection--}
```
public FMatrix4 getMatrixViewProjection()
```


Matriz para la transformación de vista y proyección.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view and projection transformation.
### getMatrixWorld() {#getMatrixWorld--}
```
public FMatrix4 getMatrixWorld()
```


Matriz para la transformación del mundo

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world transformation
### getMatrixWorldNormal() {#getMatrixWorldNormal--}
```
public FMatrix4 getMatrixWorldNormal()
```


Matriz para convertir la normal del objeto al espacio mundial.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for converting normal from object to world space.
### getMatrixWorldViewProjection() {#getMatrixWorldViewProjection--}
```
public FMatrix4 getMatrixWorldViewProjection()
```


Matriz para la vista del mundo y transformación de proyección

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world view and projection transformation
### getShadowCaster() {#getShadowCaster--}
```
public FVector3 getShadowCaster()
```


Posición del lanzador de sombras en el sistema de coordenadas del mundo

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Position of shadow caster in world coordinate system
### getShadowmap() {#getShadowmap--}
```
public ITextureUnit getShadowmap()
```


La textura de profundidad utilizada para el mapeo de sombras

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - The depth texture used for shadow mapping
### getViewportSize() {#getViewportSize--}
```
public FVector2 getViewportSize()
```


Tamaño del viewport, medido en píxeles

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - Size of viewport, measured in pixel
### getWorldAmbient() {#getWorldAmbient--}
```
public FVector3 getWorldAmbient()
```


Color ambiental definido en el viewport.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Ambient color defined in viewport.
### getWorldTime() {#getWorldTime--}
```
public float getWorldTime()
```


Tiempo en segundos

**Returns:**
float - Tiempo en segundos
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




### setCameraPosition(FVector3 value) {#setCameraPosition-com.aspose.threed.FVector3-}
```
public void setCameraPosition(FVector3 value)
```


Posición de la cámara en el sistema de coordenadas del mundo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Nuevo valor |

### setDepthBias(float value) {#setDepthBias-float-}
```
public void setDepthBias(float value)
```


Sesgo de profundidad para mapeado de sombras, el valor predeterminado es 0.001

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | Nuevo valor |

### setMatrixLightSpace(FMatrix4 value) {#setMatrixLightSpace-com.aspose.threed.FMatrix4-}
```
public void setMatrixLightSpace(FMatrix4 value)
```


Matriz para la transformación del espacio de luz

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Nuevo valor |

### setMatrixProjection(FMatrix4 value) {#setMatrixProjection-com.aspose.threed.FMatrix4-}
```
public void setMatrixProjection(FMatrix4 value)
```


Matriz para la transformación de proyección

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Nuevo valor |

### setMatrixView(FMatrix4 value) {#setMatrixView-com.aspose.threed.FMatrix4-}
```
public void setMatrixView(FMatrix4 value)
```


Matriz para la transformación de vista

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Nuevo valor |

### setShadowCaster(FVector3 value) {#setShadowCaster-com.aspose.threed.FVector3-}
```
public void setShadowCaster(FVector3 value)
```


Posición del lanzador de sombras en el sistema de coordenadas del mundo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Nuevo valor |

### setShadowmap(ITextureUnit value) {#setShadowmap-com.aspose.threed.ITextureUnit-}
```
public void setShadowmap(ITextureUnit value)
```


La textura de profundidad utilizada para el mapeo de sombras

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ITextureUnit](../../com.aspose.threed/itextureunit) | Nuevo valor |

### setViewportSize(FVector2 value) {#setViewportSize-com.aspose.threed.FVector2-}
```
public void setViewportSize(FVector2 value)
```


Tamaño del viewport, medido en píxeles

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FVector2](../../com.aspose.threed/fvector2) | Nuevo valor |

### setWorldAmbient(FVector3 value) {#setWorldAmbient-com.aspose.threed.FVector3-}
```
public void setWorldAmbient(FVector3 value)
```


Color ambiental definido en el viewport.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Nuevo valor |

### setWorldTime(float value) {#setWorldTime-float-}
```
public void setWorldTime(float value)
```


Tiempo en segundos

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | Nuevo valor |

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

