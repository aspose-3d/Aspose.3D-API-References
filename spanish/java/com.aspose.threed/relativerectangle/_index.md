---
title: RelativeRectangle
second_title: Referencia de API de Aspose.3D para Java
description: Rectángulo relativo  La fórmula entre el componente relativo y el valor absoluto es  Scale  Reference Width  offset  Por lo tanto, si queremos que represente un valor absoluto, deje todos los campos de escala en cero y use los campos de desplazamiento en su lugar.
type: docs
weight: 147
url: /es/java/com.aspose.threed/relativerectangle/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class RelativeRectangle implements Struct<RelativeRectangle>, Serializable
```

Rectángulo relativo La fórmula entre el componente relativo y el valor absoluto es: Scale \* (Reference Width) + offset. Así que si queremos que represente un valor absoluto, deje todos los campos de escala en cero y use los campos de desplazamiento en su lugar.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [RelativeRectangle(int left, int top, int width, int height)](#RelativeRectangle-int-int-int-int-) | Construir un [RelativeRectangle](../../com.aspose.threed/relativerectangle) |
| [RelativeRectangle()](#RelativeRectangle--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(RelativeRectangle src)](#copyFrom-com.aspose.threed.RelativeRectangle-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)](#fromScale-float-float-float-float-) | Construir un [RelativeRectangle](../../com.aspose.threed/relativerectangle) con todos los campos de desplazamiento en cero y los campos de escala a partir de los parámetros dados. |
| [getClass()](#getClass--) |  |
| [getOffsetHeight()](#getOffsetHeight--) | Obtiene el desplazamiento para la altura |
| [getOffsetWidth()](#getOffsetWidth--) | Obtiene el desplazamiento para el ancho |
| [getOffsetX()](#getOffsetX--) | Obtiene el desplazamiento para la coordenada X |
| [getOffsetY()](#getOffsetY--) | Obtiene el desplazamiento para la coordenada Y |
| [getScaleHeight()](#getScaleHeight--) | Altura relativa |
| [getScaleWidth()](#getScaleWidth--) | Ancho relativo |
| [getScaleX()](#getScaleX--) | Coordenada X relativa |
| [getScaleY()](#getScaleY--) | Coordenada Y relativa |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffsetHeight(int value)](#setOffsetHeight-int-) | Establece el desplazamiento para la altura |
| [setOffsetWidth(int value)](#setOffsetWidth-int-) | Establece el desplazamiento para el ancho |
| [setOffsetX(int value)](#setOffsetX-int-) | Establece el desplazamiento para la coordenada X |
| [setOffsetY(int value)](#setOffsetY-int-) | Establece el desplazamiento para la coordenada Y |
| [setScaleHeight(float value)](#setScaleHeight-float-) | Altura relativa |
| [setScaleWidth(float value)](#setScaleWidth-float-) | Ancho relativo |
| [setScaleX(float value)](#setScaleX-float-) | Coordenada X relativa |
| [setScaleY(float value)](#setScaleY-float-) | Coordenada Y relativa |
| [toAbsolute(int left, int top, int width, int height)](#toAbsolute-int-int-int-int-) | Convertir el rectángulo relativo a rectángulo absoluto |
| [toString()](#toString--) | Convierte el valor de esta instancia a un java.lang.String. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelativeRectangle(int left, int top, int width, int height) {#RelativeRectangle-int-int-int-int-}
```
public RelativeRectangle(int left, int top, int width, int height)
```


Construir un [RelativeRectangle](../../com.aspose.threed/relativerectangle)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| izquierda | int |  |
| superior | int |  |
| ancho | int |  |
| altura | int |  |

### RelativeRectangle() {#RelativeRectangle--}
```
public RelativeRectangle()
```


### clone() {#clone--}
```
public RelativeRectangle clone()
```


Clonar la instancia actual

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle)
### copyFrom(RelativeRectangle src) {#copyFrom-com.aspose.threed.RelativeRectangle-}
```
public void copyFrom(RelativeRectangle src)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | [RelativeRectangle](../../com.aspose.threed/relativerectangle) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight) {#fromScale-float-float-float-float-}
```
public static RelativeRectangle fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)
```


Construir un [RelativeRectangle](../../com.aspose.threed/relativerectangle) con todos los campos de desplazamiento en cero y los campos de escala a partir de los parámetros dados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scaleX | float |  |
| scaleY | float |  |
| scaleWidth | float |  |
| scaleHeight | float |  |

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOffsetHeight() {#getOffsetHeight--}
```
public int getOffsetHeight()
```


Obtiene el desplazamiento para la altura

**Returns:**
int - el desplazamiento para la altura
### getOffsetWidth() {#getOffsetWidth--}
```
public int getOffsetWidth()
```


Obtiene el desplazamiento para el ancho

**Returns:**
int - el desplazamiento para el ancho
### getOffsetX() {#getOffsetX--}
```
public int getOffsetX()
```


Obtiene el desplazamiento para la coordenada X

**Returns:**
int - el desplazamiento para la coordenada X
### getOffsetY() {#getOffsetY--}
```
public int getOffsetY()
```


Obtiene el desplazamiento para la coordenada Y

**Returns:**
int - el desplazamiento para la coordenada Y
### getScaleHeight() {#getScaleHeight--}
```
public float getScaleHeight()
```


Altura relativa

**Returns:**
float - Altura relativa
### getScaleWidth() {#getScaleWidth--}
```
public float getScaleWidth()
```


Ancho relativo

**Returns:**
float - Ancho relativo
### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


Coordenada X relativa

**Returns:**
float - Coordenada relativa X
### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


Coordenada Y relativa

**Returns:**
float - Coordenada relativa Y
### hashCode() {#hashCode--}
```
public int hashCode()
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




### setOffsetHeight(int value) {#setOffsetHeight-int-}
```
public void setOffsetHeight(int value)
```


Establece el desplazamiento para la altura

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Nuevo valor |

### setOffsetWidth(int value) {#setOffsetWidth-int-}
```
public void setOffsetWidth(int value)
```


Establece el desplazamiento para el ancho

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Nuevo valor |

### setOffsetX(int value) {#setOffsetX-int-}
```
public void setOffsetX(int value)
```


Establece el desplazamiento para la coordenada X

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Nuevo valor |

### setOffsetY(int value) {#setOffsetY-int-}
```
public void setOffsetY(int value)
```


Establece el desplazamiento para la coordenada Y

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Nuevo valor |

### setScaleHeight(float value) {#setScaleHeight-float-}
```
public void setScaleHeight(float value)
```


Altura relativa

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | Nuevo valor |

### setScaleWidth(float value) {#setScaleWidth-float-}
```
public void setScaleWidth(float value)
```


Ancho relativo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | Nuevo valor |

### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


Coordenada X relativa

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | Nuevo valor |

### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


Coordenada Y relativa

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | Nuevo valor |

### toAbsolute(int left, int top, int width, int height) {#toAbsolute-int-int-int-int-}
```
public Rect toAbsolute(int left, int top, int width, int height)
```


Convertir el rectángulo relativo a rectángulo absoluto

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| izquierda | int | Izquierda del rectángulo |
| superior | int | Superior del rectángulo |
| ancho | int | Ancho del rectángulo |
| altura | int | Altura del rectángulo |

**Returns:**
[Rect](../../com.aspose.threed/rect)
### toString() {#toString--}
```
public String toString()
```


Convierte el valor de esta instancia a un java.lang.String.

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

