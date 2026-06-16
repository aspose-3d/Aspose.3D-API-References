---
title: "RenderState"
second_title: "Referencia de API de Aspose.3D para Java"
description: "Estado de renderizado para construir la canalización. Los cambios realizados en el estado de renderizado no afectarán a las instancias de canalización creadas."
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
| [RenderState()](#RenderState--) | Constructor de [RenderState](../../com.aspose.threed/renderstate) |
## Métodos

| Método | Descripción |
| --- | --- |
| [close()](#close--) | Descarta el [RenderState](../../com.aspose.threed/renderstate) y libera todos los recursos internos. |
| [compareTo(RenderState other)](#compareTo-com.aspose.threed.RenderState-) | Compara el estado de renderizado con otra instancia |
| [equals(Object obj)](#equals-java.lang.Object-) | Devuelve un valor que indica si esta instancia es igual a un objeto especificado. |
| [getBlend()](#getBlend--) | Habilita o deshabilita la mezcla de fragmentos. |
| [getBlendColor()](#getBlendColor--) | Obtiene el color de mezcla donde se usa en [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [getClass()](#getClass--) |  |
| [getCullFace()](#getCullFace--) | Habilita o deshabilita la eliminación de caras |
| [getCullFaceMode()](#getCullFaceMode--) | Obtiene qué cara será eliminada. |
| [getDepthFunction()](#getDepthFunction--) | Obtiene la función de comparación usada en la prueba de profundidad |
| [getDepthMask()](#getDepthMask--) | Habilita o deshabilita la escritura de profundidad. |
| [getDepthTest()](#getDepthTest--) | Habilita o deshabilita la prueba de profundidad. |
| [getDestinationBlendFactor()](#getDestinationBlendFactor--) | Obtiene cómo se mezcla el color. |
| [getFrontFace()](#getFrontFace--) | Obtiene cuál es el orden de la cara frontal. |
| [getPolygonMode()](#getPolygonMode--) | Obtiene el modo de renderizado del polígono. |
| [getScissorTest()](#getScissorTest--) | Habilita o deshabilita la prueba de recorte |
| [getSourceBlendFactor()](#getSourceBlendFactor--) | Obtiene cómo se mezcla el color. |
| [getStencilBackFace()](#getStencilBackFace--) | Obtiene el estado de stencil para la cara trasera. |
| [getStencilFrontFace()](#getStencilFrontFace--) | Obtiene el estado de stencil para la cara frontal. |
| [getStencilMask()](#getStencilMask--) | Obtiene la máscara que se ANDea con la referencia y el valor de stencil almacenado cuando se completa la prueba. |
| [getStencilReference()](#getStencilReference--) | Obtiene el valor de referencia para la prueba de stencil. |
| [getStencilTest()](#getStencilTest--) | Habilita o deshabilita la prueba de stencil |
| [hashCode()](#hashCode--) | Devuelve el código hash para esta instancia. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlend(boolean value)](#setBlend-boolean-) | Habilita o deshabilita la mezcla de fragmentos. |
| [setBlendColor(FVector4 value)](#setBlendColor-com.aspose.threed.FVector4-) | Establece el color de mezcla donde se usa en [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [setCullFace(boolean value)](#setCullFace-boolean-) | Habilita o deshabilita la eliminación de caras |
| [setCullFaceMode(int value)](#setCullFaceMode-int-) | Establece qué cara será eliminada. |
| [setDepthFunction(CompareFunction value)](#setDepthFunction-com.aspose.threed.CompareFunction-) | Establece la función de comparación usada en la prueba de profundidad |
| [setDepthMask(boolean value)](#setDepthMask-boolean-) | Habilita o deshabilita la escritura de profundidad. |
| [setDepthTest(boolean value)](#setDepthTest-boolean-) | Habilita o deshabilita la prueba de profundidad. |
| [setDestinationBlendFactor(BlendFactor value)](#setDestinationBlendFactor-com.aspose.threed.BlendFactor-) | Establece cómo se mezcla el color. |
| [setFrontFace(FrontFace value)](#setFrontFace-com.aspose.threed.FrontFace-) | Establece cuál es el orden de la cara frontal. |
| [setPolygonMode(PolygonMode value)](#setPolygonMode-com.aspose.threed.PolygonMode-) | Establece el modo de renderizado del polígono. |
| [setScissorTest(boolean value)](#setScissorTest-boolean-) | Habilita o deshabilita la prueba de recorte |
| [setSourceBlendFactor(BlendFactor value)](#setSourceBlendFactor-com.aspose.threed.BlendFactor-) | Establece cómo se mezcla el color. |
| [setStencilMask(int value)](#setStencilMask-int-) | Establece la máscara que se ANDea con el valor de referencia y el valor de plantilla almacenado cuando se realiza la prueba. |
| [setStencilReference(int value)](#setStencilReference-int-) | Establece el valor de referencia para la prueba de plantilla. |
| [setStencilTest(boolean value)](#setStencilTest-boolean-) | Habilita o deshabilita la prueba de stencil |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderState() {#RenderState--}
```
public RenderState()
```


Constructor de [RenderState](../../com.aspose.threed/renderstate)

### close() {#close--}
```
public void close()
```


Descarta el [RenderState](../../com.aspose.threed/renderstate) y libera todos los recursos internos.

### compareTo(RenderState other) {#compareTo-com.aspose.threed.RenderState-}
```
public int compareTo(RenderState other)
```


Compara el estado de renderizado con otra instancia

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


Habilita o deshabilita la mezcla de fragmentos.

**Returns:**
boolean - Habilitar o deshabilitar la mezcla de fragmentos.
### getBlendColor() {#getBlendColor--}
```
public FVector4 getBlendColor()
```


Obtiene el color de mezcla donde se usa en [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

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


Habilita o deshabilita la eliminación de caras

**Returns:**
boolean - Habilitar o deshabilitar la eliminación de caras
### getCullFaceMode() {#getCullFaceMode--}
```
public int getCullFaceMode()
```


Obtiene qué cara será eliminada.

**Returns:**
int - qué cara será eliminada.
### getDepthFunction() {#getDepthFunction--}
```
public CompareFunction getDepthFunction()
```


Obtiene la función de comparación usada en la prueba de profundidad

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in depth test
### getDepthMask() {#getDepthMask--}
```
public boolean getDepthMask()
```


Habilita o deshabilita la escritura de profundidad.

**Returns:**
boolean - Habilitar o deshabilitar la escritura de profundidad.
### getDepthTest() {#getDepthTest--}
```
public boolean getDepthTest()
```


Habilita o deshabilita la prueba de profundidad.

**Returns:**
boolean - Habilitar o deshabilitar la prueba de profundidad.
### getDestinationBlendFactor() {#getDestinationBlendFactor--}
```
public BlendFactor getDestinationBlendFactor()
```


Obtiene cómo se mezcla el color.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getFrontFace() {#getFrontFace--}
```
public FrontFace getFrontFace()
```


Obtiene cuál es el orden de la cara frontal.

**Returns:**
[FrontFace](../../com.aspose.threed/frontface) - which order is front face.
### getPolygonMode() {#getPolygonMode--}
```
public PolygonMode getPolygonMode()
```


Obtiene el modo de renderizado del polígono.

**Returns:**
[PolygonMode](../../com.aspose.threed/polygonmode) - the polygon's render mode.
### getScissorTest() {#getScissorTest--}
```
public boolean getScissorTest()
```


Habilita o deshabilita la prueba de recorte

**Returns:**
boolean - Habilitar o deshabilitar la prueba de recorte
### getSourceBlendFactor() {#getSourceBlendFactor--}
```
public BlendFactor getSourceBlendFactor()
```


Obtiene cómo se mezcla el color.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getStencilBackFace() {#getStencilBackFace--}
```
public StencilState getStencilBackFace()
```


Obtiene el estado de stencil para la cara trasera.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for back face.
### getStencilFrontFace() {#getStencilFrontFace--}
```
public StencilState getStencilFrontFace()
```


Obtiene el estado de stencil para la cara frontal.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for front face.
### getStencilMask() {#getStencilMask--}
```
public int getStencilMask()
```


Obtiene la máscara que se ANDea con la referencia y el valor de stencil almacenado cuando se completa la prueba.

**Returns:**
int - la máscara que se ANDea con el valor de referencia y el valor de plantilla almacenado cuando se realiza la prueba.
### getStencilReference() {#getStencilReference--}
```
public int getStencilReference()
```


Obtiene el valor de referencia para la prueba de stencil.

**Returns:**
int - el valor de referencia para la prueba de plantilla.
### getStencilTest() {#getStencilTest--}
```
public boolean getStencilTest()
```


Habilita o deshabilita la prueba de stencil

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


Habilita o deshabilita la mezcla de fragmentos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setBlendColor(FVector4 value) {#setBlendColor-com.aspose.threed.FVector4-}
```
public void setBlendColor(FVector4 value)
```


Establece el color de mezcla donde se usa en [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FVector4](../../com.aspose.threed/fvector4) | Nuevo valor |

### setCullFace(boolean value) {#setCullFace-boolean-}
```
public void setCullFace(boolean value)
```


Habilita o deshabilita la eliminación de caras

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setCullFaceMode(int value) {#setCullFaceMode-int-}
```
public void setCullFaceMode(int value)
```


Establece qué cara será eliminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Nuevo valor |

### setDepthFunction(CompareFunction value) {#setDepthFunction-com.aspose.threed.CompareFunction-}
```
public void setDepthFunction(CompareFunction value)
```


Establece la función de comparación usada en la prueba de profundidad

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | Nuevo valor |

### setDepthMask(boolean value) {#setDepthMask-boolean-}
```
public void setDepthMask(boolean value)
```


Habilita o deshabilita la escritura de profundidad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setDepthTest(boolean value) {#setDepthTest-boolean-}
```
public void setDepthTest(boolean value)
```


Habilita o deshabilita la prueba de profundidad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setDestinationBlendFactor(BlendFactor value) {#setDestinationBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setDestinationBlendFactor(BlendFactor value)
```


Establece cómo se mezcla el color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | Nuevo valor |

### setFrontFace(FrontFace value) {#setFrontFace-com.aspose.threed.FrontFace-}
```
public void setFrontFace(FrontFace value)
```


Establece cuál es el orden de la cara frontal.

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


Habilita o deshabilita la prueba de recorte

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setSourceBlendFactor(BlendFactor value) {#setSourceBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setSourceBlendFactor(BlendFactor value)
```


Establece cómo se mezcla el color.

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


Habilita o deshabilita la prueba de stencil

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

