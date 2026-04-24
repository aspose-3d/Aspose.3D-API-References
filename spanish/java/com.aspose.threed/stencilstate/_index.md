---
title: StencilState
second_title: Referencia de API de Aspose.3D para Java
description: Estados de stencil por cara.
type: docs
weight: 175
url: /es/java/com.aspose.threed/stencilstate/
---

**Inheritance:**
java.lang.Object
```
public class StencilState
```

Estados de stencil por cara.
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Devuelve un valor que indica si esta instancia es igual a un objeto especificado. |
| [getClass()](#getClass--) |  |
| [getCompare()](#getCompare--) | Obtiene la función de comparación utilizada en la prueba de stencil. |
| [getDepthFailAction()](#getDepthFailAction--) | Obtiene la acción de stencil cuando la prueba de stencil pasa pero la prueba de profundidad falla. |
| [getFailAction()](#getFailAction--) | Obtiene la acción de stencil cuando la prueba de stencil falla. |
| [getPassAction()](#getPassAction--) | Obtiene la acción de stencil cuando tanto la prueba de stencil como la prueba de profundidad pasan. |
| [hashCode()](#hashCode--) | Devuelve el código hash para esta instancia. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompare(CompareFunction value)](#setCompare-com.aspose.threed.CompareFunction-) | Establece la función de comparación utilizada en la prueba de stencil. |
| [setDepthFailAction(StencilAction value)](#setDepthFailAction-com.aspose.threed.StencilAction-) | Establece la acción de stencil cuando la prueba de stencil pasa pero la prueba de profundidad falla. |
| [setFailAction(StencilAction value)](#setFailAction-com.aspose.threed.StencilAction-) | Establece la acción de stencil cuando la prueba de stencil falla. |
| [setPassAction(StencilAction value)](#setPassAction-com.aspose.threed.StencilAction-) | Establece la acción de stencil cuando tanto la prueba de stencil como la prueba de profundidad pasan. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompare() {#getCompare--}
```
public CompareFunction getCompare()
```


Obtiene la función de comparación utilizada en la prueba de stencil.

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in stencil test
### getDepthFailAction() {#getDepthFailAction--}
```
public StencilAction getDepthFailAction()
```


Obtiene la acción de stencil cuando la prueba de stencil pasa pero la prueba de profundidad falla.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test pass but depth test fails.
### getFailAction() {#getFailAction--}
```
public StencilAction getFailAction()
```


Obtiene la acción de stencil cuando la prueba de stencil falla.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when stencil test fails.
### getPassAction() {#getPassAction--}
```
public StencilAction getPassAction()
```


Obtiene la acción de stencil cuando tanto la prueba de stencil como la prueba de profundidad pasan.

**Returns:**
[StencilAction](../../com.aspose.threed/stencilaction) - the stencil action when both stencil test and depth test passes.
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




### setCompare(CompareFunction value) {#setCompare-com.aspose.threed.CompareFunction-}
```
public void setCompare(CompareFunction value)
```


Establece la función de comparación utilizada en la prueba de stencil.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | Nuevo valor |

### setDepthFailAction(StencilAction value) {#setDepthFailAction-com.aspose.threed.StencilAction-}
```
public void setDepthFailAction(StencilAction value)
```


Establece la acción de stencil cuando la prueba de stencil pasa pero la prueba de profundidad falla.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Nuevo valor |

### setFailAction(StencilAction value) {#setFailAction-com.aspose.threed.StencilAction-}
```
public void setFailAction(StencilAction value)
```


Establece la acción de stencil cuando la prueba de stencil falla.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Nuevo valor |

### setPassAction(StencilAction value) {#setPassAction-com.aspose.threed.StencilAction-}
```
public void setPassAction(StencilAction value)
```


Establece la acción de stencil cuando tanto la prueba de stencil como la prueba de profundidad pasan.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StencilAction](../../com.aspose.threed/stencilaction) | Nuevo valor |

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

