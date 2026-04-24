---
title: RenderState
second_title: Справочник API Aspose.3D для Java
description: Состояние рендеринга для построения конвейера. Изменения, внесённые в состояние рендеринга, не повлияют на созданные экземпляры конвейера.
type: docs
weight: 151
url: /ru/java/com.aspose.threed/renderstate/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable, java.lang.Comparable
```
public class RenderState implements Closeable, Comparable<RenderState>
```

Состояние рендеринга для построения конвейера. Изменения, внесённые в состояние рендеринга, не повлияют на созданные экземпляры конвейера.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RenderState()](#RenderState--) | Конструктор [RenderState](../../com.aspose.threed/renderstate) |
## Методы

| Метод | Описание |
| --- | --- |
| [close()](#close--) | Освободить [RenderState](../../com.aspose.threed/renderstate) и освободить все внутренние ресурсы. |
| [compareTo(RenderState other)](#compareTo-com.aspose.threed.RenderState-) | Сравнить состояние рендеринга с другим экземпляром |
| [equals(Object obj)](#equals-java.lang.Object-) | Возвращает значение, указывающее, равен ли данный экземпляр указанному объекту. |
| [getBlend()](#getBlend--) | Включить или отключить смешивание фрагментов. |
| [getBlendColor()](#getBlendColor--) | Получает цвет смешивания, используемый в [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [getClass()](#getClass--) |  |
| [getCullFace()](#getCullFace--) | Включить или отключить отсечение граней |
| [getCullFaceMode()](#getCullFaceMode--) | Получает, какая грань будет отсеяна. |
| [getDepthFunction()](#getDepthFunction--) | Получает функцию сравнения, используемую в тесте глубины. |
| [getDepthMask()](#getDepthMask--) | Включить или отключить запись глубины. |
| [getDepthTest()](#getDepthTest--) | Включить или отключить тест глубины. |
| [getDestinationBlendFactor()](#getDestinationBlendFactor--) | Получает, как происходит смешивание цвета. |
| [getFrontFace()](#getFrontFace--) | Получает, какой порядок считается передней гранью. |
| [getPolygonMode()](#getPolygonMode--) | Получает режим рендеринга полигона. |
| [getScissorTest()](#getScissorTest--) | Включить или отключить тест ножниц. |
| [getSourceBlendFactor()](#getSourceBlendFactor--) | Получает, как происходит смешивание цвета. |
| [getStencilBackFace()](#getStencilBackFace--) | Получает состояние трафарета для задней грани. |
| [getStencilFrontFace()](#getStencilFrontFace--) | Получает состояние трафарета для передней грани. |
| [getStencilMask()](#getStencilMask--) | Получает маску, которая применяется оператором AND к ссылочному и сохранённому значению трафарета при выполнении теста. |
| [getStencilReference()](#getStencilReference--) | Получает ссылочное значение для теста трафарета. |
| [getStencilTest()](#getStencilTest--) | Включить или отключить тест трафарета. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для данного экземпляра. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlend(boolean value)](#setBlend-boolean-) | Включить или отключить смешивание фрагментов. |
| [setBlendColor(FVector4 value)](#setBlendColor-com.aspose.threed.FVector4-) | Устанавливает цвет смешивания, используемый в [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [setCullFace(boolean value)](#setCullFace-boolean-) | Включить или отключить отсечение граней |
| [setCullFaceMode(int value)](#setCullFaceMode-int-) | Устанавливает, какая грань будет отсеяна. |
| [setDepthFunction(CompareFunction value)](#setDepthFunction-com.aspose.threed.CompareFunction-) | Устанавливает функцию сравнения, используемую в тесте глубины. |
| [setDepthMask(boolean value)](#setDepthMask-boolean-) | Включить или отключить запись глубины. |
| [setDepthTest(boolean value)](#setDepthTest-boolean-) | Включить или отключить тест глубины. |
| [setDestinationBlendFactor(BlendFactor value)](#setDestinationBlendFactor-com.aspose.threed.BlendFactor-) | Устанавливает, как происходит смешивание цвета. |
| [setFrontFace(FrontFace value)](#setFrontFace-com.aspose.threed.FrontFace-) | Устанавливает, какой порядок считается передней гранью. |
| [setPolygonMode(PolygonMode value)](#setPolygonMode-com.aspose.threed.PolygonMode-) | Устанавливает режим отрисовки полигона. |
| [setScissorTest(boolean value)](#setScissorTest-boolean-) | Включить или отключить тест ножниц. |
| [setSourceBlendFactor(BlendFactor value)](#setSourceBlendFactor-com.aspose.threed.BlendFactor-) | Устанавливает, как происходит смешивание цвета. |
| [setStencilMask(int value)](#setStencilMask-int-) | Устанавливает маску, которая ANDed с обоими эталонным и сохранённым значением трафарета при завершении теста. |
| [setStencilReference(int value)](#setStencilReference-int-) | Устанавливает эталонное значение для теста трафарета. |
| [setStencilTest(boolean value)](#setStencilTest-boolean-) | Включить или отключить тест трафарета. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderState() {#RenderState--}
```
public RenderState()
```


Конструктор [RenderState](../../com.aspose.threed/renderstate)

### close() {#close--}
```
public void close()
```


Освободить [RenderState](../../com.aspose.threed/renderstate) и освободить все внутренние ресурсы.

### compareTo(RenderState other) {#compareTo-com.aspose.threed.RenderState-}
```
public int compareTo(RenderState other)
```


Сравнить состояние рендеринга с другим экземпляром

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [RenderState](../../com.aspose.threed/renderstate) | Другое состояние отрисовки для сравнения |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Возвращает значение, указывающее, равен ли данный экземпляр указанному объекту.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getBlend() {#getBlend--}
```
public boolean getBlend()
```


Включить или отключить смешивание фрагментов.

**Returns:**
boolean — включить или отключить смешивание фрагментов.
### getBlendColor() {#getBlendColor--}
```
public FVector4 getBlendColor()
```


Получает цвет смешивания, используемый в [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCullFace() {#getCullFace--}
```
public boolean getCullFace()
```


Включить или отключить отсечение граней

**Returns:**
boolean — включить или отключить отсечение граней
### getCullFaceMode() {#getCullFaceMode--}
```
public int getCullFaceMode()
```


Получает, какая грань будет отсеяна.

**Returns:**
int — какая грань будет отсечена.
### getDepthFunction() {#getDepthFunction--}
```
public CompareFunction getDepthFunction()
```


Получает функцию сравнения, используемую в тесте глубины.

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in depth test
### getDepthMask() {#getDepthMask--}
```
public boolean getDepthMask()
```


Включить или отключить запись глубины.

**Returns:**
boolean — включить или отключить запись глубины.
### getDepthTest() {#getDepthTest--}
```
public boolean getDepthTest()
```


Включить или отключить тест глубины.

**Returns:**
boolean — включить или отключить тест глубины.
### getDestinationBlendFactor() {#getDestinationBlendFactor--}
```
public BlendFactor getDestinationBlendFactor()
```


Получает, как происходит смешивание цвета.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getFrontFace() {#getFrontFace--}
```
public FrontFace getFrontFace()
```


Получает, какой порядок считается передней гранью.

**Returns:**
[FrontFace](../../com.aspose.threed/frontface) - which order is front face.
### getPolygonMode() {#getPolygonMode--}
```
public PolygonMode getPolygonMode()
```


Получает режим рендеринга полигона.

**Returns:**
[PolygonMode](../../com.aspose.threed/polygonmode) - the polygon's render mode.
### getScissorTest() {#getScissorTest--}
```
public boolean getScissorTest()
```


Включить или отключить тест ножниц.

**Returns:**
boolean — включить или отключить тест ножниц
### getSourceBlendFactor() {#getSourceBlendFactor--}
```
public BlendFactor getSourceBlendFactor()
```


Получает, как происходит смешивание цвета.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getStencilBackFace() {#getStencilBackFace--}
```
public StencilState getStencilBackFace()
```


Получает состояние трафарета для задней грани.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for back face.
### getStencilFrontFace() {#getStencilFrontFace--}
```
public StencilState getStencilFrontFace()
```


Получает состояние трафарета для передней грани.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for front face.
### getStencilMask() {#getStencilMask--}
```
public int getStencilMask()
```


Получает маску, которая применяется оператором AND к ссылочному и сохранённому значению трафарета при выполнении теста.

**Returns:**
int — маска, которая ANDed с обоими эталонным и сохранённым значением трафарета при завершении теста.
### getStencilReference() {#getStencilReference--}
```
public int getStencilReference()
```


Получает ссылочное значение для теста трафарета.

**Returns:**
int — эталонное значение для теста трафарета.
### getStencilTest() {#getStencilTest--}
```
public boolean getStencilTest()
```


Включить или отключить тест трафарета.

**Returns:**
boolean — включить или отключить тест трафарета.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для данного экземпляра.

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




### setBlend(boolean value) {#setBlend-boolean-}
```
public void setBlend(boolean value)
```


Включить или отключить смешивание фрагментов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setBlendColor(FVector4 value) {#setBlendColor-com.aspose.threed.FVector4-}
```
public void setBlendColor(FVector4 value)
```


Устанавливает цвет смешивания, используемый в [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FVector4](../../com.aspose.threed/fvector4) | Новое значение |

### setCullFace(boolean value) {#setCullFace-boolean-}
```
public void setCullFace(boolean value)
```


Включить или отключить отсечение граней

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setCullFaceMode(int value) {#setCullFaceMode-int-}
```
public void setCullFaceMode(int value)
```


Устанавливает, какая грань будет отсеяна.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setDepthFunction(CompareFunction value) {#setDepthFunction-com.aspose.threed.CompareFunction-}
```
public void setDepthFunction(CompareFunction value)
```


Устанавливает функцию сравнения, используемую в тесте глубины.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | Новое значение |

### setDepthMask(boolean value) {#setDepthMask-boolean-}
```
public void setDepthMask(boolean value)
```


Включить или отключить запись глубины.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setDepthTest(boolean value) {#setDepthTest-boolean-}
```
public void setDepthTest(boolean value)
```


Включить или отключить тест глубины.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setDestinationBlendFactor(BlendFactor value) {#setDestinationBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setDestinationBlendFactor(BlendFactor value)
```


Устанавливает, как происходит смешивание цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | Новое значение |

### setFrontFace(FrontFace value) {#setFrontFace-com.aspose.threed.FrontFace-}
```
public void setFrontFace(FrontFace value)
```


Устанавливает, какой порядок считается передней гранью.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FrontFace](../../com.aspose.threed/frontface) | Новое значение |

### setPolygonMode(PolygonMode value) {#setPolygonMode-com.aspose.threed.PolygonMode-}
```
public void setPolygonMode(PolygonMode value)
```


Устанавливает режим отрисовки полигона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PolygonMode](../../com.aspose.threed/polygonmode) | Новое значение |

### setScissorTest(boolean value) {#setScissorTest-boolean-}
```
public void setScissorTest(boolean value)
```


Включить или отключить тест ножниц.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setSourceBlendFactor(BlendFactor value) {#setSourceBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setSourceBlendFactor(BlendFactor value)
```


Устанавливает, как происходит смешивание цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | Новое значение |

### setStencilMask(int value) {#setStencilMask-int-}
```
public void setStencilMask(int value)
```


Устанавливает маску, которая ANDed с обоими эталонным и сохранённым значением трафарета при завершении теста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setStencilReference(int value) {#setStencilReference-int-}
```
public void setStencilReference(int value)
```


Устанавливает эталонное значение для теста трафарета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setStencilTest(boolean value) {#setStencilTest-boolean-}
```
public void setStencilTest(boolean value)
```


Включить или отключить тест трафарета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

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

