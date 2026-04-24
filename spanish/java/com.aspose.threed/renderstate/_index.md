---
title: RenderState
second_title: Referencia de API de Aspose.3D para Java
description: Estado de renderizado para construir la canalización. Los cambios realizados en el estado de renderizado no afectarán a las instancias de canalización creadas.
type: docs
weight: 151
url: /es/java/com.aspose.threed/renderstate/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable, java.lang.Comparable
```
public class RenderState implements Closeable, Comparable<RenderState>
```

Estado de renderizado para construir la canalización. Los cambios realizados en el estado de renderizado no afectarán a las instancias de canalización creadas.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [RenderState()](#RenderState--) | Constructor of [RenderState](../../com.aspose.threed/renderstate) |
## Métodos

| Método | Descripción |
| --- | --- |
| [close()](#close--) | Dispose the [RenderState](../../com.aspose.threed/renderstate) and release all internal resources. |
| [compareTo(RenderState other)](#compareTo-com.aspose.threed.RenderState-) | Compare the render state with another instance |
| [equals(Object obj)](#equals-java.lang.Object-) | Devuelve un valor que indica si esta instancia es igual a un objeto especificado. |
| [getBlend()](#getBlend--) | Enable or disable the fragment blending. |
| [getBlendColor()](#getBlendColor--) | Gets the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [getClass()](#getClass--) |  |
| [getCullFace()](#getCullFace--) | Enable or disable cull face |
| [getCullFaceMode()](#getCullFaceMode--) | Gets which face will be culled. |
| [getDepthFunction()](#getDepthFunction--) | Gets the compare function used in depth test |
| [getDepthMask()](#getDepthMask--) | Enable or disable the depth writing. |
| [getDepthTest()](#getDepthTest--) | Enable or disable the depth test. |
| [getDestinationBlendFactor()](#getDestinationBlendFactor--) | Gets how the color is blended. |
| [getFrontFace()](#getFrontFace--) | Gets which order is front face. |
| [getPolygonMode()](#getPolygonMode--) | Gets the polygon's render mode. |
| [getScissorTest()](#getScissorTest--) | Enable or disable scissor test |
| [getSourceBlendFactor()](#getSourceBlendFactor--) | Gets how the color is blended. |
| [getStencilBackFace()](#getStencilBackFace--) | Gets the stencil state for back face. |
| [getStencilFrontFace()](#getStencilFrontFace--) | Gets the stencil state for front face. |
| [getStencilMask()](#getStencilMask--) | Gets the mask that is ANDed with the both reference and stored stencil value when test is done. |
| [getStencilReference()](#getStencilReference--) | Gets the reference value for the stencil test. |
| [getStencilTest()](#getStencilTest--) | Enable or disable the stencil test. |
| [hashCode()](#hashCode--) | Devuelve el código hash para esta instancia. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlend(boolean value)](#setBlend-boolean-) | Enable or disable the fragment blending. |
| [setBlendColor(FVector4 value)](#setBlendColor-com.aspose.threed.FVector4-) | Sets the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [setCullFace(boolean value)](#setCullFace-boolean-) | Enable or disable cull face |
| [setCullFaceMode(int value)](#setCullFaceMode-int-) | Sets which face will be culled. |
| [setDepthFunction(CompareFunction value)](#setDepthFunction-com.aspose.threed.CompareFunction-) | Sets the compare function used in depth test |
| [setDepthMask(boolean value)](#setDepthMask-boolean-) | Enable or disable the depth writing. |
| [setDepthTest(boolean value)](#setDepthTest-boolean-) | Enable or disable the depth test. |
| [setDestinationBlendFactor(BlendFactor value)](#setDestinationBlendFactor-com.aspose.threed.BlendFactor-) | Sets how the color is blended. |
| [setFrontFace(FrontFace value)](#setFrontFace-com.aspose.threed.FrontFace-) | Sets which order is front face. |
| [setPolygonMode(PolygonMode value)](#setPolygonMode-com.aspose.threed.PolygonMode-) | Establece el modo de renderizado del polígono. |
| [setScissorTest(boolean value)](#setScissorTest-boolean-) | Enable or disable scissor test |
| [setSourceBlendFactor(BlendFactor value)](#setSourceBlendFactor-com.aspose.threed.BlendFactor-) | Sets how the color is blended. |
| [setStencilMask(int value)](#setStencilMask-int-) | Establece la máscara que se ANDea con el valor de referencia y el valor de plantilla almacenado cuando se realiza la prueba. |
| [setStencilReference(int value)](#setStencilReference-int-) | Establece el valor de referencia para la prueba de plantilla. |
| [setStencilTest(boolean value)](#setStencilTest-boolean-) | Enable or disable the stencil test. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderState() {#RenderState--}
```
public RenderState()
```


Constructor of [RenderState](../../com.aspose.threed/renderstate)

### close() {#close--}
```
public void close()
```


Dispose the [RenderState](../../com.aspose.threed/renderstate) and release all internal resources.

### compareTo(RenderState other) {#compareTo-com.aspose.threed.RenderState-}
```
public int compareTo(RenderState other)
```


Compare the render state with another instance

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [RenderState](../../com.aspose.threed/renderstate) | Otro estado de renderizado para comparar |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Devuelve un valor que indica si esta instancia es igual a un objeto especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getBlend() {#getBlend--}
```
public boolean getBlend()
```


Enable or disable the fragment blending.

**Returns:**
boolean - Habilitar o deshabilitar la mezcla de fragmentos.
### getBlendColor() {#getBlendColor--}
```
public FVector4 getBlendColor()
```


Gets the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

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


Enable or disable cull face

**Returns:**
boolean - Habilitar o deshabilitar la eliminación de caras
### getCullFaceMode() {#getCullFaceMode--}
```
public int getCullFaceMode()
```


Gets which face will be culled.

**Returns:**
int - qué cara será eliminada.
### getDepthFunction() {#getDepthFunction--}
```
public CompareFunction getDepthFunction()
```


Gets the compare function used in depth test

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in depth test
### getDepthMask() {#getDepthMask--}
```
public boolean getDepthMask()
```


Enable or disable the depth writing.

**Returns:**
boolean - Habilitar o deshabilitar la escritura de profundidad.
### getDepthTest() {#getDepthTest--}
```
public boolean getDepthTest()
```


Enable or disable the depth test.

**Returns:**
boolean - Habilitar o deshabilitar la prueba de profundidad.
### getDestinationBlendFactor() {#getDestinationBlendFactor--}
```
public BlendFactor getDestinationBlendFactor()
```


Gets how the color is blended.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getFrontFace() {#getFrontFace--}
```
public FrontFace getFrontFace()
```


Gets which order is front face.

**Returns:**
[FrontFace](../../com.aspose.threed/frontface) - which order is front face.
### getPolygonMode() {#getPolygonMode--}
```
public PolygonMode getPolygonMode()
```


Gets the polygon's render mode.

**Returns:**
[PolygonMode](../../com.aspose.threed/polygonmode) - the polygon's render mode.
### getScissorTest() {#getScissorTest--}
```
public boolean getScissorTest()
```


Enable or disable scissor test

**Returns:**
boolean - Habilitar o deshabilitar la prueba de recorte
### getSourceBlendFactor() {#getSourceBlendFactor--}
```
public BlendFactor getSourceBlendFactor()
```


Gets how the color is blended.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getStencilBackFace() {#getStencilBackFace--}
```
public StencilState getStencilBackFace()
```


Gets the stencil state for back face.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for back face.
### getStencilFrontFace() {#getStencilFrontFace--}
```
public StencilState getStencilFrontFace()
```


Gets the stencil state for front face.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for front face.
### getStencilMask() {#getStencilMask--}
```
public int getStencilMask()
```


Gets the mask that is ANDed with the both reference and stored stencil value when test is done.

**Returns:**
int - la máscara que se ANDea con el valor de referencia y el valor de plantilla almacenado cuando se realiza la prueba.
### getStencilReference() {#getStencilReference--}
```
public int getStencilReference()
```


Gets the reference value for the stencil test.

**Returns:**
int - el valor de referencia para la prueba de plantilla.
### getStencilTest() {#getStencilTest--}
```
public boolean getStencilTest()
```


Enable or disable the stencil test.

**Returns:**
boolean - Habilitar o deshabilitar la prueba de plantilla.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash para esta instancia.

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


Enable or disable the fragment blending.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setBlendColor(FVector4 value) {#setBlendColor-com.aspose.threed.FVector4-}
```
public void setBlendColor(FVector4 value)
```


Sets the blend color where used in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FVector4](../../com.aspose.threed/fvector4) | Nuevo valor |

### setCullFace(boolean value) {#setCullFace-boolean-}
```
public void setCullFace(boolean value)
```


Enable or disable cull face

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setCullFaceMode(int value) {#setCullFaceMode-int-}
```
public void setCullFaceMode(int value)
```


Sets which face will be culled.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Nuevo valor |

### setDepthFunction(CompareFunction value) {#setDepthFunction-com.aspose.threed.CompareFunction-}
```
public void setDepthFunction(CompareFunction value)
```


Sets the compare function used in depth test

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | Nuevo valor |

### setDepthMask(boolean value) {#setDepthMask-boolean-}
```
public void setDepthMask(boolean value)
```


Enable or disable the depth writing.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setDepthTest(boolean value) {#setDepthTest-boolean-}
```
public void setDepthTest(boolean value)
```


Enable or disable the depth test.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setDestinationBlendFactor(BlendFactor value) {#setDestinationBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setDestinationBlendFactor(BlendFactor value)
```


Sets how the color is blended.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | Nuevo valor |

### setFrontFace(FrontFace value) {#setFrontFace-com.aspose.threed.FrontFace-}
```
public void setFrontFace(FrontFace value)
```


Sets which order is front face.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FrontFace](../../com.aspose.threed/frontface) | Nuevo valor |

### setPolygonMode(PolygonMode value) {#setPolygonMode-com.aspose.threed.PolygonMode-}
```
public void setPolygonMode(PolygonMode value)
```


Establece el modo de renderizado del polígono.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PolygonMode](../../com.aspose.threed/polygonmode) | Nuevo valor |

### setScissorTest(boolean value) {#setScissorTest-boolean-}
```
public void setScissorTest(boolean value)
```


Enable or disable scissor test

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setSourceBlendFactor(BlendFactor value) {#setSourceBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setSourceBlendFactor(BlendFactor value)
```


Sets how the color is blended.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | Nuevo valor |

### setStencilMask(int value) {#setStencilMask-int-}
```
public void setStencilMask(int value)
```


Establece la máscara que se ANDea con el valor de referencia y el valor de plantilla almacenado cuando se realiza la prueba.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Nuevo valor |

### setStencilReference(int value) {#setStencilReference-int-}
```
public void setStencilReference(int value)
```


Establece el valor de referencia para la prueba de plantilla.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Nuevo valor |

### setStencilTest(boolean value) {#setStencilTest-boolean-}
```
public void setStencilTest(boolean value)
```


Enable or disable the stencil test.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

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

