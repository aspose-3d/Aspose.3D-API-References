---
title: Viewport
second_title: Aspose.3D for Java API Reference
description: Un  contiene almeno un viewport per il rendering della scena.
type: docs
weight: 229
url: /it/java/com.aspose.threed/viewport/
---

**Inheritance:**
java.lang.Object
```
public class Viewport
```

Un [IRenderTarget](../../com.aspose.threed/irendertarget) contiene almeno un viewport per il rendering della scena.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clone()](#clone--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArea()](#getArea--) | Ottiene l'area del viewport nel render target. |
| [getBackgroundColor()](#getBackgroundColor--) | Ottiene il colore di sfondo del viewport. |
| [getClass()](#getClass--) |  |
| [getDepthClear()](#getDepthClear--) | Ottiene il valore di profondità usato quando si pulisce il viewport con il bit del buffer di profondità impostato. |
| [getEnabled()](#getEnabled--) | Abilita o disabilita questo viewport. |
| [getFrustum()](#getFrustum--) | Ottiene la telecamera di questo [Viewport](../../com.aspose.threed/viewport) |
| [getRenderTarget()](#getRenderTarget--) | Ottiene il render target che ha creato questo viewport. |
| [getZOrder()](#getZOrder--) | Ottiene l'ordine Z del viewport. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArea(RelativeRectangle value)](#setArea-com.aspose.threed.RelativeRectangle-) | Imposta l'area del viewport nel target di rendering. |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | Imposta il colore di sfondo del viewport. |
| [setDepthClear(float value)](#setDepthClear-float-) | Imposta il valore di profondità usato quando si pulisce il viewport con il bit del buffer di profondità impostato. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Abilita o disabilita questo viewport. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | Imposta la telecamera di questo [Viewport](../../com.aspose.threed/viewport) |
| [setZOrder(int value)](#setZOrder-int-) | Imposta l'ordine Z del viewport. |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getArea() {#getArea--}
```
public RelativeRectangle getArea()
```


Ottiene l'area del viewport nel render target.

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle) - the area of the viewport in render target.
### getBackgroundColor() {#getBackgroundColor--}
```
public Vector3 getBackgroundColor()
```


Ottiene il colore di sfondo del viewport.

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


Ottiene il valore di profondità usato quando si pulisce il viewport con il bit del buffer di profondità impostato.

**Returns:**
float - il valore di profondità usato quando si pulisce il viewport con il bit del buffer di profondità impostato.
### getEnabled() {#getEnabled--}
```
public boolean getEnabled()
```


Abilita o disabilita questo viewport.

**Returns:**
boolean - Abilita o disabilita questo viewport.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


Ottiene la telecamera di questo [Viewport](../../com.aspose.threed/viewport)

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the camera of this [Viewport](../../com.aspose.threed/viewport)
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


Ottiene il render target che ha creato questo viewport.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - the render target that created this viewport.
### getZOrder() {#getZOrder--}
```
public int getZOrder()
```


Ottiene l'ordine Z del viewport.

**Returns:**
int - l'ordine Z del viewport.
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


Imposta l'area del viewport nel target di rendering.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Nuovo valore |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


Imposta il colore di sfondo del viewport.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

### setDepthClear(float value) {#setDepthClear-float-}
```
public void setDepthClear(float value)
```


Imposta il valore di profondità usato quando si pulisce il viewport con il bit del buffer di profondità impostato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Nuovo valore |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Abilita o disabilita questo viewport.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


Imposta la telecamera di questo [Viewport](../../com.aspose.threed/viewport)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | Nuovo valore |

### setZOrder(int value) {#setZOrder-int-}
```
public void setZOrder(int value)
```


Imposta l'ordine Z del viewport.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Nuovo valore |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

