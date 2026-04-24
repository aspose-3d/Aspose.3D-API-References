---
title: Viewport
second_title: Aspose.3D for Java API-referens
description: En  innehåller minst en viewport för att rendera scenen.
type: docs
weight: 229
url: /sv/java/com.aspose.threed/viewport/
---

**Inheritance:**
java.lang.Object
```
public class Viewport
```

En [IRenderTarget](../../com.aspose.threed/irendertarget) innehåller minst en viewport för att rendera scenen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [clone()](#clone--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArea()](#getArea--) | Hämtar viewportens område i render target. |
| [getBackgroundColor()](#getBackgroundColor--) | Hämtar bakgrundsfärgen för viewporten. |
| [getClass()](#getClass--) |  |
| [getDepthClear()](#getDepthClear--) | Hämtar djupvärdet som används när viewporten rensas med depth buffer-bit satt. |
| [getEnabled()](#getEnabled--) | Aktivera eller inaktivera denna viewport. |
| [getFrustum()](#getFrustum--) | Hämtar kameran för denna [Viewport](../../com.aspose.threed/viewport) |
| [getRenderTarget()](#getRenderTarget--) | Hämtar render target som skapade denna viewport. |
| [getZOrder()](#getZOrder--) | Hämtar Z-ordningen för visningsområdet. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArea(RelativeRectangle value)](#setArea-com.aspose.threed.RelativeRectangle-) | Ställer in området för visningsområdet i rendermålet. |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | Ställer in bakgrundsfärgen för visningsområdet. |
| [setDepthClear(float value)](#setDepthClear-float-) | Ställer in djupvärdet som används när visningsområdet rensas med djupbuffertbiten satt. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Aktivera eller inaktivera denna viewport. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | Ställer in kameran för detta [Viewport](../../com.aspose.threed/viewport) |
| [setZOrder(int value)](#setZOrder-int-) | Ställer in Z-ordningen för visningsområdet. |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getArea() {#getArea--}
```
public RelativeRectangle getArea()
```


Hämtar viewportens område i render target.

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle) - the area of the viewport in render target.
### getBackgroundColor() {#getBackgroundColor--}
```
public Vector3 getBackgroundColor()
```


Hämtar bakgrundsfärgen för viewporten.

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


Hämtar djupvärdet som används när viewporten rensas med depth buffer-bit satt.

**Returns:**
float – djupvärdet som används när visningsområdet rensas med djupbuffertbiten satt.
### getEnabled() {#getEnabled--}
```
public boolean getEnabled()
```


Aktivera eller inaktivera denna viewport.

**Returns:**
boolean – Aktivera eller inaktivera detta visningsområde.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


Hämtar kameran för denna [Viewport](../../com.aspose.threed/viewport)

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the camera of this [Viewport](../../com.aspose.threed/viewport)
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


Hämtar render target som skapade denna viewport.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - the render target that created this viewport.
### getZOrder() {#getZOrder--}
```
public int getZOrder()
```


Hämtar Z-ordningen för visningsområdet.

**Returns:**
int – Z-ordningen för visningsområdet.
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


Ställer in området för visningsområdet i rendermålet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Nytt värde |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


Ställer in bakgrundsfärgen för visningsområdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde |

### setDepthClear(float value) {#setDepthClear-float-}
```
public void setDepthClear(float value)
```


Ställer in djupvärdet som används när visningsområdet rensas med djupbuffertbiten satt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Nytt värde |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Aktivera eller inaktivera denna viewport.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


Ställer in kameran för detta [Viewport](../../com.aspose.threed/viewport)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | Nytt värde |

### setZOrder(int value) {#setZOrder-int-}
```
public void setZOrder(int value)
```


Ställer in Z-ordningen för visningsområdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Nytt värde |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

