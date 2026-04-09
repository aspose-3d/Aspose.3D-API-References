---
title: Viewport
second_title: Aspose.3D for Java API-referentie
description: Een  bevat minstens één viewport voor het renderen van de scène.
type: docs
weight: 229
url: /nl/java/com.aspose.threed/viewport/
---

**Inheritance:**
java.lang.Object
```
public class Viewport
```

Een [IRenderTarget](../../com.aspose.threed/irendertarget) bevat minstens één viewport voor het renderen van de scène.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [clone()](#clone--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArea()](#getArea--) | Haalt het gebied van de viewport in het renderdoel op. |
| [getBackgroundColor()](#getBackgroundColor--) | Haalt de achtergrondkleur van de viewport op. |
| [getClass()](#getClass--) |  |
| [getDepthClear()](#getDepthClear--) | Haalt de dieptewaarde op die wordt gebruikt bij het wissen van de viewport met de dieptebufferbit ingesteld. |
| [getEnabled()](#getEnabled--) | Schakel deze viewport in of uit. |
| [getFrustum()](#getFrustum--) | Haalt de camera van deze [Viewport](../../com.aspose.threed/viewport) op. |
| [getRenderTarget()](#getRenderTarget--) | Haalt het renderdoel op dat deze viewport heeft gemaakt. |
| [getZOrder()](#getZOrder--) | Haalt de Z-volgorde van de viewport op. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArea(RelativeRectangle value)](#setArea-com.aspose.threed.RelativeRectangle-) | Stelt het gebied van de viewport in het renderdoel in. |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | Stelt de achtergrondkleur van de viewport in. |
| [setDepthClear(float value)](#setDepthClear-float-) | Stelt de dieptewaarde in die wordt gebruikt bij het wissen van de viewport met de dieptebufferbit ingesteld. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Schakel deze viewport in of uit. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | Stelt de camera van deze [Viewport](../../com.aspose.threed/viewport) in. |
| [setZOrder(int value)](#setZOrder-int-) | Stelt de Z-volgorde van de viewport in. |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getArea() {#getArea--}
```
public RelativeRectangle getArea()
```


Haalt het gebied van de viewport in het renderdoel op.

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle) - the area of the viewport in render target.
### getBackgroundColor() {#getBackgroundColor--}
```
public Vector3 getBackgroundColor()
```


Haalt de achtergrondkleur van de viewport op.

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


Haalt de dieptewaarde op die wordt gebruikt bij het wissen van de viewport met de dieptebufferbit ingesteld.

**Returns:**
float - de dieptewaarde die wordt gebruikt bij het wissen van de viewport met de dieptebufferbit ingesteld.
### getEnabled() {#getEnabled--}
```
public boolean getEnabled()
```


Schakel deze viewport in of uit.

**Returns:**
boolean - Schakel deze viewport in of uit.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


Haalt de camera van deze [Viewport](../../com.aspose.threed/viewport) op.

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the camera of this [Viewport](../../com.aspose.threed/viewport)
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


Haalt het renderdoel op dat deze viewport heeft gemaakt.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - the render target that created this viewport.
### getZOrder() {#getZOrder--}
```
public int getZOrder()
```


Haalt de Z-volgorde van de viewport op.

**Returns:**
int - de Z-volgorde van de viewport.
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


Stelt het gebied van de viewport in het renderdoel in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Nieuwe waarde |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


Stelt de achtergrondkleur van de viewport in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setDepthClear(float value) {#setDepthClear-float-}
```
public void setDepthClear(float value)
```


Stelt de dieptewaarde in die wordt gebruikt bij het wissen van de viewport met de dieptebufferbit ingesteld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Nieuwe waarde |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public void setEnabled(boolean value)
```


Schakel deze viewport in of uit.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


Stelt de camera van deze [Viewport](../../com.aspose.threed/viewport) in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | Nieuwe waarde |

### setZOrder(int value) {#setZOrder-int-}
```
public void setZOrder(int value)
```


Stelt de Z-volgorde van de viewport in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Nieuwe waarde |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

