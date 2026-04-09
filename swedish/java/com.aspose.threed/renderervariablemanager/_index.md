---
title: RendererVariableManager
second_title: Aspose.3D for Java API-referens
description: Denna klass hanterar variabler som används vid rendering
type: docs
weight: 154
url: /sv/java/com.aspose.threed/renderervariablemanager/
---

**Inheritance:**
java.lang.Object
```
public abstract class RendererVariableManager
```

Denna klass hanterar variabler som används vid rendering
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | Kamerans position i världens koordinatsystem |
| [getClass()](#getClass--) |  |
| [getDepthBias()](#getDepthBias--) | Djupförskjutning för skuggmappning, standardvärdet är 0.001 |
| [getMatrixLightSpace()](#getMatrixLightSpace--) | Matris för ljusutrymmestransformation |
| [getMatrixProjection()](#getMatrixProjection--) | Matris för projektionstransformation |
| [getMatrixView()](#getMatrixView--) | Matris för vytransformation |
| [getMatrixViewProjection()](#getMatrixViewProjection--) | Matris för vy- och projektionstransformation. |
| [getMatrixWorld()](#getMatrixWorld--) | Matris för världstransformation |
| [getMatrixWorldNormal()](#getMatrixWorldNormal--) | Matris för att konvertera normal från objekt till världsrummet. |
| [getMatrixWorldViewProjection()](#getMatrixWorldViewProjection--) | Matris för världsvy och projektionstransformation |
| [getShadowCaster()](#getShadowCaster--) | Position för skuggkastare i världens koordinatsystem |
| [getShadowmap()](#getShadowmap--) | Djuptexturen som används för skuggkartering |
| [getViewportSize()](#getViewportSize--) | Storlek på visningsområdet, mätt i pixlar |
| [getWorldAmbient()](#getWorldAmbient--) | Omgivningsfärg definierad i visningsområdet. |
| [getWorldTime()](#getWorldTime--) | Tid i sekunder |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(FVector3 value)](#setCameraPosition-com.aspose.threed.FVector3-) | Kamerans position i världens koordinatsystem |
| [setDepthBias(float value)](#setDepthBias-float-) | Djupförskjutning för skuggmappning, standardvärdet är 0.001 |
| [setMatrixLightSpace(FMatrix4 value)](#setMatrixLightSpace-com.aspose.threed.FMatrix4-) | Matris för ljusutrymmestransformation |
| [setMatrixProjection(FMatrix4 value)](#setMatrixProjection-com.aspose.threed.FMatrix4-) | Matris för projektionstransformation |
| [setMatrixView(FMatrix4 value)](#setMatrixView-com.aspose.threed.FMatrix4-) | Matris för vytransformation |
| [setShadowCaster(FVector3 value)](#setShadowCaster-com.aspose.threed.FVector3-) | Position för skuggkastare i världens koordinatsystem |
| [setShadowmap(ITextureUnit value)](#setShadowmap-com.aspose.threed.ITextureUnit-) | Djuptexturen som används för skuggkartering |
| [setViewportSize(FVector2 value)](#setViewportSize-com.aspose.threed.FVector2-) | Storlek på visningsområdet, mätt i pixlar |
| [setWorldAmbient(FVector3 value)](#setWorldAmbient-com.aspose.threed.FVector3-) | Omgivningsfärg definierad i visningsområdet. |
| [setWorldTime(float value)](#setWorldTime-float-) | Tid i sekunder |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getCameraPosition() {#getCameraPosition--}
```
public FVector3 getCameraPosition()
```


Kamerans position i världens koordinatsystem

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


Djupförskjutning för skuggmappning, standardvärdet är 0.001

**Returns:**
float - Djupförskjutning för skuggkartering, standardvärdet är 0.001
### getMatrixLightSpace() {#getMatrixLightSpace--}
```
public FMatrix4 getMatrixLightSpace()
```


Matris för ljusutrymmestransformation

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for light space transformation
### getMatrixProjection() {#getMatrixProjection--}
```
public FMatrix4 getMatrixProjection()
```


Matris för projektionstransformation

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for projection transformation
### getMatrixView() {#getMatrixView--}
```
public FMatrix4 getMatrixView()
```


Matris för vytransformation

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view transformation
### getMatrixViewProjection() {#getMatrixViewProjection--}
```
public FMatrix4 getMatrixViewProjection()
```


Matris för vy- och projektionstransformation.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view and projection transformation.
### getMatrixWorld() {#getMatrixWorld--}
```
public FMatrix4 getMatrixWorld()
```


Matris för världstransformation

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world transformation
### getMatrixWorldNormal() {#getMatrixWorldNormal--}
```
public FMatrix4 getMatrixWorldNormal()
```


Matris för att konvertera normal från objekt till världsrummet.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for converting normal from object to world space.
### getMatrixWorldViewProjection() {#getMatrixWorldViewProjection--}
```
public FMatrix4 getMatrixWorldViewProjection()
```


Matris för världsvy och projektionstransformation

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world view and projection transformation
### getShadowCaster() {#getShadowCaster--}
```
public FVector3 getShadowCaster()
```


Position för skuggkastare i världens koordinatsystem

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Position of shadow caster in world coordinate system
### getShadowmap() {#getShadowmap--}
```
public ITextureUnit getShadowmap()
```


Djuptexturen som används för skuggkartering

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - The depth texture used for shadow mapping
### getViewportSize() {#getViewportSize--}
```
public FVector2 getViewportSize()
```


Storlek på visningsområdet, mätt i pixlar

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - Size of viewport, measured in pixel
### getWorldAmbient() {#getWorldAmbient--}
```
public FVector3 getWorldAmbient()
```


Omgivningsfärg definierad i visningsområdet.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Ambient color defined in viewport.
### getWorldTime() {#getWorldTime--}
```
public float getWorldTime()
```


Tid i sekunder

**Returns:**
float - Tid i sekunder
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


Kamerans position i världens koordinatsystem

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Nytt värde |

### setDepthBias(float value) {#setDepthBias-float-}
```
public void setDepthBias(float value)
```


Djupförskjutning för skuggmappning, standardvärdet är 0.001

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Nytt värde |

### setMatrixLightSpace(FMatrix4 value) {#setMatrixLightSpace-com.aspose.threed.FMatrix4-}
```
public void setMatrixLightSpace(FMatrix4 value)
```


Matris för ljusutrymmestransformation

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Nytt värde |

### setMatrixProjection(FMatrix4 value) {#setMatrixProjection-com.aspose.threed.FMatrix4-}
```
public void setMatrixProjection(FMatrix4 value)
```


Matris för projektionstransformation

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Nytt värde |

### setMatrixView(FMatrix4 value) {#setMatrixView-com.aspose.threed.FMatrix4-}
```
public void setMatrixView(FMatrix4 value)
```


Matris för vytransformation

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Nytt värde |

### setShadowCaster(FVector3 value) {#setShadowCaster-com.aspose.threed.FVector3-}
```
public void setShadowCaster(FVector3 value)
```


Position för skuggkastare i världens koordinatsystem

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Nytt värde |

### setShadowmap(ITextureUnit value) {#setShadowmap-com.aspose.threed.ITextureUnit-}
```
public void setShadowmap(ITextureUnit value)
```


Djuptexturen som används för skuggkartering

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ITextureUnit](../../com.aspose.threed/itextureunit) | Nytt värde |

### setViewportSize(FVector2 value) {#setViewportSize-com.aspose.threed.FVector2-}
```
public void setViewportSize(FVector2 value)
```


Storlek på visningsområdet, mätt i pixlar

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FVector2](../../com.aspose.threed/fvector2) | Nytt värde |

### setWorldAmbient(FVector3 value) {#setWorldAmbient-com.aspose.threed.FVector3-}
```
public void setWorldAmbient(FVector3 value)
```


Omgivningsfärg definierad i visningsområdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Nytt värde |

### setWorldTime(float value) {#setWorldTime-float-}
```
public void setWorldTime(float value)
```


Tid i sekunder

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Nytt värde |

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

