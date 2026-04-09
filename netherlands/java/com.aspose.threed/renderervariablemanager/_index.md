---
title: RendererVariableManager
second_title: Aspose.3D for Java API-referentie
description: Deze klasse beheert variabelen die worden gebruikt bij het renderen
type: docs
weight: 154
url: /nl/java/com.aspose.threed/renderervariablemanager/
---

**Inheritance:**
java.lang.Object
```
public abstract class RendererVariableManager
```

Deze klasse beheert variabelen die worden gebruikt bij het renderen
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | Positie van de camera in het wereldcoördinatensysteem |
| [getClass()](#getClass--) |  |
| [getDepthBias()](#getDepthBias--) | Dieptebias voor schaduwmapping, standaardwaarde is 0.001 |
| [getMatrixLightSpace()](#getMatrixLightSpace--) | Matrix voor lichtruimtetransformatie |
| [getMatrixProjection()](#getMatrixProjection--) | Matrix voor projectietransformatie |
| [getMatrixView()](#getMatrixView--) | Matrix voor weergavetransformatie |
| [getMatrixViewProjection()](#getMatrixViewProjection--) | Matrix voor weergave- en projectietransformatie. |
| [getMatrixWorld()](#getMatrixWorld--) | Matrix voor wereldtransformatie |
| [getMatrixWorldNormal()](#getMatrixWorldNormal--) | Matrix voor het converteren van normaal van object naar wereldruimte. |
| [getMatrixWorldViewProjection()](#getMatrixWorldViewProjection--) | Matrix voor wereldweergave en projectietransformatie |
| [getShadowCaster()](#getShadowCaster--) | Positie van de schaduwwerper in het wereldcoördinatensysteem |
| [getShadowmap()](#getShadowmap--) | De diepte-textuur die wordt gebruikt voor schaduwmapping |
| [getViewportSize()](#getViewportSize--) | Grootte van het viewport, gemeten in pixels |
| [getWorldAmbient()](#getWorldAmbient--) | Omgevingskleur gedefinieerd in het viewport. |
| [getWorldTime()](#getWorldTime--) | Tijd in seconden |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(FVector3 value)](#setCameraPosition-com.aspose.threed.FVector3-) | Positie van de camera in het wereldcoördinatensysteem |
| [setDepthBias(float value)](#setDepthBias-float-) | Dieptebias voor schaduwmapping, standaardwaarde is 0.001 |
| [setMatrixLightSpace(FMatrix4 value)](#setMatrixLightSpace-com.aspose.threed.FMatrix4-) | Matrix voor lichtruimtetransformatie |
| [setMatrixProjection(FMatrix4 value)](#setMatrixProjection-com.aspose.threed.FMatrix4-) | Matrix voor projectietransformatie |
| [setMatrixView(FMatrix4 value)](#setMatrixView-com.aspose.threed.FMatrix4-) | Matrix voor weergavetransformatie |
| [setShadowCaster(FVector3 value)](#setShadowCaster-com.aspose.threed.FVector3-) | Positie van de schaduwwerper in het wereldcoördinatensysteem |
| [setShadowmap(ITextureUnit value)](#setShadowmap-com.aspose.threed.ITextureUnit-) | De diepte-textuur die wordt gebruikt voor schaduwmapping |
| [setViewportSize(FVector2 value)](#setViewportSize-com.aspose.threed.FVector2-) | Grootte van het viewport, gemeten in pixels |
| [setWorldAmbient(FVector3 value)](#setWorldAmbient-com.aspose.threed.FVector3-) | Omgevingskleur gedefinieerd in het viewport. |
| [setWorldTime(float value)](#setWorldTime-float-) | Tijd in seconden |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getCameraPosition() {#getCameraPosition--}
```
public FVector3 getCameraPosition()
```


Positie van de camera in het wereldcoördinatensysteem

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


Dieptebias voor schaduwmapping, standaardwaarde is 0.001

**Returns:**
float - Dieptebias voor schaduwmapping, standaardwaarde is 0.001
### getMatrixLightSpace() {#getMatrixLightSpace--}
```
public FMatrix4 getMatrixLightSpace()
```


Matrix voor lichtruimtetransformatie

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for light space transformation
### getMatrixProjection() {#getMatrixProjection--}
```
public FMatrix4 getMatrixProjection()
```


Matrix voor projectietransformatie

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for projection transformation
### getMatrixView() {#getMatrixView--}
```
public FMatrix4 getMatrixView()
```


Matrix voor weergavetransformatie

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view transformation
### getMatrixViewProjection() {#getMatrixViewProjection--}
```
public FMatrix4 getMatrixViewProjection()
```


Matrix voor weergave- en projectietransformatie.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view and projection transformation.
### getMatrixWorld() {#getMatrixWorld--}
```
public FMatrix4 getMatrixWorld()
```


Matrix voor wereldtransformatie

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world transformation
### getMatrixWorldNormal() {#getMatrixWorldNormal--}
```
public FMatrix4 getMatrixWorldNormal()
```


Matrix voor het converteren van normaal van object naar wereldruimte.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for converting normal from object to world space.
### getMatrixWorldViewProjection() {#getMatrixWorldViewProjection--}
```
public FMatrix4 getMatrixWorldViewProjection()
```


Matrix voor wereldweergave en projectietransformatie

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world view and projection transformation
### getShadowCaster() {#getShadowCaster--}
```
public FVector3 getShadowCaster()
```


Positie van de schaduwwerper in het wereldcoördinatensysteem

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Position of shadow caster in world coordinate system
### getShadowmap() {#getShadowmap--}
```
public ITextureUnit getShadowmap()
```


De diepte-textuur die wordt gebruikt voor schaduwmapping

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - The depth texture used for shadow mapping
### getViewportSize() {#getViewportSize--}
```
public FVector2 getViewportSize()
```


Grootte van het viewport, gemeten in pixels

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - Size of viewport, measured in pixel
### getWorldAmbient() {#getWorldAmbient--}
```
public FVector3 getWorldAmbient()
```


Omgevingskleur gedefinieerd in het viewport.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Ambient color defined in viewport.
### getWorldTime() {#getWorldTime--}
```
public float getWorldTime()
```


Tijd in seconden

**Returns:**
float - Tijd in seconden
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


Positie van de camera in het wereldcoördinatensysteem

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Nieuwe waarde |

### setDepthBias(float value) {#setDepthBias-float-}
```
public void setDepthBias(float value)
```


Dieptebias voor schaduwmapping, standaardwaarde is 0.001

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Nieuwe waarde |

### setMatrixLightSpace(FMatrix4 value) {#setMatrixLightSpace-com.aspose.threed.FMatrix4-}
```
public void setMatrixLightSpace(FMatrix4 value)
```


Matrix voor lichtruimtetransformatie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Nieuwe waarde |

### setMatrixProjection(FMatrix4 value) {#setMatrixProjection-com.aspose.threed.FMatrix4-}
```
public void setMatrixProjection(FMatrix4 value)
```


Matrix voor projectietransformatie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Nieuwe waarde |

### setMatrixView(FMatrix4 value) {#setMatrixView-com.aspose.threed.FMatrix4-}
```
public void setMatrixView(FMatrix4 value)
```


Matrix voor weergavetransformatie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Nieuwe waarde |

### setShadowCaster(FVector3 value) {#setShadowCaster-com.aspose.threed.FVector3-}
```
public void setShadowCaster(FVector3 value)
```


Positie van de schaduwwerper in het wereldcoördinatensysteem

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Nieuwe waarde |

### setShadowmap(ITextureUnit value) {#setShadowmap-com.aspose.threed.ITextureUnit-}
```
public void setShadowmap(ITextureUnit value)
```


De diepte-textuur die wordt gebruikt voor schaduwmapping

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ITextureUnit](../../com.aspose.threed/itextureunit) | Nieuwe waarde |

### setViewportSize(FVector2 value) {#setViewportSize-com.aspose.threed.FVector2-}
```
public void setViewportSize(FVector2 value)
```


Grootte van het viewport, gemeten in pixels

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FVector2](../../com.aspose.threed/fvector2) | Nieuwe waarde |

### setWorldAmbient(FVector3 value) {#setWorldAmbient-com.aspose.threed.FVector3-}
```
public void setWorldAmbient(FVector3 value)
```


Omgevingskleur gedefinieerd in het viewport.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Nieuwe waarde |

### setWorldTime(float value) {#setWorldTime-float-}
```
public void setWorldTime(float value)
```


Tijd in seconden

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Nieuwe waarde |

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

