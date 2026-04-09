---
title: RendererVariableManager
second_title: Aspose.3D for Java API Reference
description: Questa classe gestisce le variabili usate nel rendering
type: docs
weight: 154
url: /it/java/com.aspose.threed/renderervariablemanager/
---

**Inheritance:**
java.lang.Object
```
public abstract class RendererVariableManager
```

Questa classe gestisce le variabili usate nel rendering
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | Posizione della fotocamera nel sistema di coordinate del mondo |
| [getClass()](#getClass--) |  |
| [getDepthBias()](#getDepthBias--) | Bias di profondità per la mappatura delle ombre, il valore predefinito è 0.001 |
| [getMatrixLightSpace()](#getMatrixLightSpace--) | Matrice per la trasformazione dello spazio luce |
| [getMatrixProjection()](#getMatrixProjection--) | Matrice per la trasformazione di proiezione |
| [getMatrixView()](#getMatrixView--) | Matrice per la trasformazione di visualizzazione |
| [getMatrixViewProjection()](#getMatrixViewProjection--) | Matrice per la trasformazione di visualizzazione e proiezione. |
| [getMatrixWorld()](#getMatrixWorld--) | Matrice per la trasformazione del mondo |
| [getMatrixWorldNormal()](#getMatrixWorldNormal--) | Matrice per la conversione della normale da oggetto a spazio mondo. |
| [getMatrixWorldViewProjection()](#getMatrixWorldViewProjection--) | Matrice per la vista del mondo e la trasformazione di proiezione |
| [getShadowCaster()](#getShadowCaster--) | Posizione dell'emettitore di ombra nel sistema di coordinate del mondo |
| [getShadowmap()](#getShadowmap--) | La texture di profondità utilizzata per il mapping delle ombre |
| [getViewportSize()](#getViewportSize--) | Dimensione della viewport, misurata in pixel |
| [getWorldAmbient()](#getWorldAmbient--) | Colore ambientale definito nella viewport. |
| [getWorldTime()](#getWorldTime--) | Tempo in secondi |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(FVector3 value)](#setCameraPosition-com.aspose.threed.FVector3-) | Posizione della fotocamera nel sistema di coordinate del mondo |
| [setDepthBias(float value)](#setDepthBias-float-) | Bias di profondità per la mappatura delle ombre, il valore predefinito è 0.001 |
| [setMatrixLightSpace(FMatrix4 value)](#setMatrixLightSpace-com.aspose.threed.FMatrix4-) | Matrice per la trasformazione dello spazio luce |
| [setMatrixProjection(FMatrix4 value)](#setMatrixProjection-com.aspose.threed.FMatrix4-) | Matrice per la trasformazione di proiezione |
| [setMatrixView(FMatrix4 value)](#setMatrixView-com.aspose.threed.FMatrix4-) | Matrice per la trasformazione di visualizzazione |
| [setShadowCaster(FVector3 value)](#setShadowCaster-com.aspose.threed.FVector3-) | Posizione dell'emettitore di ombra nel sistema di coordinate del mondo |
| [setShadowmap(ITextureUnit value)](#setShadowmap-com.aspose.threed.ITextureUnit-) | La texture di profondità utilizzata per il mapping delle ombre |
| [setViewportSize(FVector2 value)](#setViewportSize-com.aspose.threed.FVector2-) | Dimensione della viewport, misurata in pixel |
| [setWorldAmbient(FVector3 value)](#setWorldAmbient-com.aspose.threed.FVector3-) | Colore ambientale definito nella viewport. |
| [setWorldTime(float value)](#setWorldTime-float-) | Tempo in secondi |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getCameraPosition() {#getCameraPosition--}
```
public FVector3 getCameraPosition()
```


Posizione della fotocamera nel sistema di coordinate del mondo

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


Bias di profondità per la mappatura delle ombre, il valore predefinito è 0.001

**Returns:**
float - Bias di profondità per il mapping delle ombre, il valore predefinito è 0.001
### getMatrixLightSpace() {#getMatrixLightSpace--}
```
public FMatrix4 getMatrixLightSpace()
```


Matrice per la trasformazione dello spazio luce

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for light space transformation
### getMatrixProjection() {#getMatrixProjection--}
```
public FMatrix4 getMatrixProjection()
```


Matrice per la trasformazione di proiezione

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for projection transformation
### getMatrixView() {#getMatrixView--}
```
public FMatrix4 getMatrixView()
```


Matrice per la trasformazione di visualizzazione

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view transformation
### getMatrixViewProjection() {#getMatrixViewProjection--}
```
public FMatrix4 getMatrixViewProjection()
```


Matrice per la trasformazione di visualizzazione e proiezione.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for view and projection transformation.
### getMatrixWorld() {#getMatrixWorld--}
```
public FMatrix4 getMatrixWorld()
```


Matrice per la trasformazione del mondo

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world transformation
### getMatrixWorldNormal() {#getMatrixWorldNormal--}
```
public FMatrix4 getMatrixWorldNormal()
```


Matrice per la conversione della normale da oggetto a spazio mondo.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for converting normal from object to world space.
### getMatrixWorldViewProjection() {#getMatrixWorldViewProjection--}
```
public FMatrix4 getMatrixWorldViewProjection()
```


Matrice per la vista del mondo e la trasformazione di proiezione

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Matrix for world view and projection transformation
### getShadowCaster() {#getShadowCaster--}
```
public FVector3 getShadowCaster()
```


Posizione dell'emettitore di ombra nel sistema di coordinate del mondo

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Position of shadow caster in world coordinate system
### getShadowmap() {#getShadowmap--}
```
public ITextureUnit getShadowmap()
```


La texture di profondità utilizzata per il mapping delle ombre

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit) - The depth texture used for shadow mapping
### getViewportSize() {#getViewportSize--}
```
public FVector2 getViewportSize()
```


Dimensione della viewport, misurata in pixel

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - Size of viewport, measured in pixel
### getWorldAmbient() {#getWorldAmbient--}
```
public FVector3 getWorldAmbient()
```


Colore ambientale definito nella viewport.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Ambient color defined in viewport.
### getWorldTime() {#getWorldTime--}
```
public float getWorldTime()
```


Tempo in secondi

**Returns:**
float - Tempo in secondi
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


Posizione della fotocamera nel sistema di coordinate del mondo

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Nuovo valore |

### setDepthBias(float value) {#setDepthBias-float-}
```
public void setDepthBias(float value)
```


Bias di profondità per la mappatura delle ombre, il valore predefinito è 0.001

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Nuovo valore |

### setMatrixLightSpace(FMatrix4 value) {#setMatrixLightSpace-com.aspose.threed.FMatrix4-}
```
public void setMatrixLightSpace(FMatrix4 value)
```


Matrice per la trasformazione dello spazio luce

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Nuovo valore |

### setMatrixProjection(FMatrix4 value) {#setMatrixProjection-com.aspose.threed.FMatrix4-}
```
public void setMatrixProjection(FMatrix4 value)
```


Matrice per la trasformazione di proiezione

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Nuovo valore |

### setMatrixView(FMatrix4 value) {#setMatrixView-com.aspose.threed.FMatrix4-}
```
public void setMatrixView(FMatrix4 value)
```


Matrice per la trasformazione di visualizzazione

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FMatrix4](../../com.aspose.threed/fmatrix4) | Nuovo valore |

### setShadowCaster(FVector3 value) {#setShadowCaster-com.aspose.threed.FVector3-}
```
public void setShadowCaster(FVector3 value)
```


Posizione dell'emettitore di ombra nel sistema di coordinate del mondo

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Nuovo valore |

### setShadowmap(ITextureUnit value) {#setShadowmap-com.aspose.threed.ITextureUnit-}
```
public void setShadowmap(ITextureUnit value)
```


La texture di profondità utilizzata per il mapping delle ombre

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ITextureUnit](../../com.aspose.threed/itextureunit) | Nuovo valore |

### setViewportSize(FVector2 value) {#setViewportSize-com.aspose.threed.FVector2-}
```
public void setViewportSize(FVector2 value)
```


Dimensione della viewport, misurata in pixel

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FVector2](../../com.aspose.threed/fvector2) | Nuovo valore |

### setWorldAmbient(FVector3 value) {#setWorldAmbient-com.aspose.threed.FVector3-}
```
public void setWorldAmbient(FVector3 value)
```


Colore ambientale definito nella viewport.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FVector3](../../com.aspose.threed/fvector3) | Nuovo valore |

### setWorldTime(float value) {#setWorldTime-float-}
```
public void setWorldTime(float value)
```


Tempo in secondi

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Nuovo valore |

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

