---
title: RendererVariableManager
second_title: Справочник API Aspose.3D для Java
description: Этот класс управляет переменными, используемыми в рендеринге.
type: docs
weight: 154
url: /ru/java/com.aspose.threed/renderervariablemanager/
---

**Inheritance:**
java.lang.Object
```
public abstract class RendererVariableManager
```

Этот класс управляет переменными, используемыми в рендеринге.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | Позиция камеры в мировой системе координат |
| [getClass()](#getClass--) |  |
| [getDepthBias()](#getDepthBias--) | Смещение глубины для теневого отображения, значение по умолчанию — 0.001 |
| [getMatrixLightSpace()](#getMatrixLightSpace--) | Матрица преобразования в световое пространство |
| [getMatrixProjection()](#getMatrixProjection--) | Матрица проекционного преобразования |
| [getMatrixView()](#getMatrixView--) | Матрица преобразования вида |
| [getMatrixViewProjection()](#getMatrixViewProjection--) | Матрица преобразования вида и проекции. |
| [getMatrixWorld()](#getMatrixWorld--) | Матрица преобразования мира |
| [getMatrixWorldNormal()](#getMatrixWorldNormal--) | Матрица преобразования нормали из объектного в мировое пространство. |
| [getMatrixWorldViewProjection()](#getMatrixWorldViewProjection--) | Матрица для преобразования вида мира и проекции |
| [getShadowCaster()](#getShadowCaster--) | Позиция источника тени в мировой системе координат |
| [getShadowmap()](#getShadowmap--) | Текстура глубины, используемая для теневого отображения |
| [getViewportSize()](#getViewportSize--) | Размер области просмотра, измеренный в пикселях |
| [getWorldAmbient()](#getWorldAmbient--) | Фоновый цвет, определённый в области просмотра. |
| [getWorldTime()](#getWorldTime--) | Время в секундах |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(FVector3 value)](#setCameraPosition-com.aspose.threed.FVector3-) | Позиция камеры в мировой системе координат |
| [setDepthBias(float value)](#setDepthBias-float-) | Смещение глубины для теневого отображения, значение по умолчанию — 0.001 |
| [setMatrixLightSpace(FMatrix4 value)](#setMatrixLightSpace-com.aspose.threed.FMatrix4-) | Матрица преобразования в световое пространство |
| [setMatrixProjection(FMatrix4 value)](#setMatrixProjection-com.aspose.threed.FMatrix4-) | Матрица проекционного преобразования |
| [setMatrixView(FMatrix4 value)](#setMatrixView-com.aspose.threed.FMatrix4-) | Матрица преобразования вида |
| [setShadowCaster(FVector3 value)](#setShadowCaster-com.aspose.threed.FVector3-) | Позиция источника тени в мировой системе координат |
| [setShadowmap(ITextureUnit value)](#setShadowmap-com.aspose.threed.ITextureUnit-) | Текстура глубины, используемая для теневого отображения |
| [setViewportSize(FVector2 value)](#setViewportSize-com.aspose.threed.FVector2-) | Размер области просмотра, измеренный в пикселях |
| [setWorldAmbient(FVector3 value)](#setWorldAmbient-com.aspose.threed.FVector3-) | Фоновый цвет, определённый в области просмотра. |
| [setWorldTime(float value)](#setWorldTime-float-) | Время в секундах |
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
### getCameraPosition() {#getCameraPosition--}
```
public FVector3 getCameraPosition()
```


Позиция камеры в мировой системе координат

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


Смещение глубины для теневого отображения, значение по умолчанию — 0.001

**Returns:**
float - Смещение глубины для теневого отображения, значение по умолчанию 0.001
### getMatrixLightSpace() {#getMatrixLightSpace--}
```
public FMatrix4 getMatrixLightSpace()
```


Матрица преобразования в световое пространство

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for light space transformation
### getMatrixProjection() {#getMatrixProjection--}
```
public FMatrix4 getMatrixProjection()
```


Матрица проекционного преобразования

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for projection transformation
### getMatrixView() {#getMatrixView--}
```
public FMatrix4 getMatrixView()
```


Матрица преобразования вида

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view transformation
### getMatrixViewProjection() {#getMatrixViewProjection--}
```
public FMatrix4 getMatrixViewProjection()
```


Матрица преобразования вида и проекции.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view and projection transformation.
### getMatrixWorld() {#getMatrixWorld--}
```
public FMatrix4 getMatrixWorld()
```


Матрица преобразования мира

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world transformation
### getMatrixWorldNormal() {#getMatrixWorldNormal--}
```
public FMatrix4 getMatrixWorldNormal()
```


Матрица преобразования нормали из объектного в мировое пространство.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for converting normal from object to world space.
### getMatrixWorldViewProjection() {#getMatrixWorldViewProjection--}
```
public FMatrix4 getMatrixWorldViewProjection()
```


Матрица для преобразования вида мира и проекции

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world view and projection transformation
### getShadowCaster() {#getShadowCaster--}
```
public FVector3 getShadowCaster()
```


Позиция источника тени в мировой системе координат

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Position of shadow caster in world coordinate system
### getShadowmap() {#getShadowmap--}
```
public ITextureUnit getShadowmap()
```


Текстура глубины, используемая для теневого отображения

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - The depth texture used for shadow mapping
### getViewportSize() {#getViewportSize--}
```
public FVector2 getViewportSize()
```


Размер области просмотра, измеренный в пикселях

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - Size of viewport, measured in pixel
### getWorldAmbient() {#getWorldAmbient--}
```
public FVector3 getWorldAmbient()
```


Фоновый цвет, определённый в области просмотра.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Ambient color defined in viewport.
### getWorldTime() {#getWorldTime--}
```
public float getWorldTime()
```


Время в секундах

**Returns:**
float - Время в секундах
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


Позиция камеры в мировой системе координат

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Новое значение |

### setDepthBias(float value) {#setDepthBias-float-}
```
public void setDepthBias(float value)
```


Смещение глубины для теневого отображения, значение по умолчанию — 0.001

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Новое значение |

### setMatrixLightSpace(FMatrix4 value) {#setMatrixLightSpace-com.aspose.threed.FMatrix4-}
```
public void setMatrixLightSpace(FMatrix4 value)
```


Матрица преобразования в световое пространство

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Новое значение |

### setMatrixProjection(FMatrix4 value) {#setMatrixProjection-com.aspose.threed.FMatrix4-}
```
public void setMatrixProjection(FMatrix4 value)
```


Матрица проекционного преобразования

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Новое значение |

### setMatrixView(FMatrix4 value) {#setMatrixView-com.aspose.threed.FMatrix4-}
```
public void setMatrixView(FMatrix4 value)
```


Матрица преобразования вида

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Новое значение |

### setShadowCaster(FVector3 value) {#setShadowCaster-com.aspose.threed.FVector3-}
```
public void setShadowCaster(FVector3 value)
```


Позиция источника тени в мировой системе координат

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Новое значение |

### setShadowmap(ITextureUnit value) {#setShadowmap-com.aspose.threed.ITextureUnit-}
```
public void setShadowmap(ITextureUnit value)
```


Текстура глубины, используемая для теневого отображения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ITextureUnit](../../com.aspose.threed/itextureunit) | Новое значение |

### setViewportSize(FVector2 value) {#setViewportSize-com.aspose.threed.FVector2-}
```
public void setViewportSize(FVector2 value)
```


Размер области просмотра, измеренный в пикселях

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FVector2](../../com.aspose.threed/fvector2) | Новое значение |

### setWorldAmbient(FVector3 value) {#setWorldAmbient-com.aspose.threed.FVector3-}
```
public void setWorldAmbient(FVector3 value)
```


Фоновый цвет, определённый в области просмотра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Новое значение |

### setWorldTime(float value) {#setWorldTime-float-}
```
public void setWorldTime(float value)
```


Время в секундах

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Новое значение |

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

