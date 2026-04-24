---
title: RenderState
second_title: Aspose.3D for Java API Reference
description: Stato di rendering per la costruzione della pipeline. Le modifiche apportate allo stato di rendering non influiranno sulle istanze di pipeline create.
type: docs
weight: 151
url: /it/java/com.aspose.threed/renderstate/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable, java.lang.Comparable
```
public class RenderState implements Closeable, Comparable<RenderState>
```

Stato di rendering per la costruzione della pipeline. Le modifiche apportate allo stato di rendering non influenzeranno le istanze di pipeline create.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RenderState()](#RenderState--) | Costruttore di [RenderState](../../com.aspose.threed/renderstate) |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [close()](#close--) | Rilascia il [RenderState](../../com.aspose.threed/renderstate) e libera tutte le risorse interne. |
| [compareTo(RenderState other)](#compareTo-com.aspose.threed.RenderState-) | Confronta lo stato di rendering con un'altra istanza |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un oggetto specificato. |
| [getBlend()](#getBlend--) | Abilita o disabilita la fusione dei frammenti. |
| [getBlendColor()](#getBlendColor--) | Ottiene il colore di fusione dove è usato in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [getClass()](#getClass--) |  |
| [getCullFace()](#getCullFace--) | Abilita o disabilita il cull face |
| [getCullFaceMode()](#getCullFaceMode--) | Ottiene quale faccia verrà cullata. |
| [getDepthFunction()](#getDepthFunction--) | Ottiene la funzione di confronto usata nel test di profondità |
| [getDepthMask()](#getDepthMask--) | Abilita o disabilita la scrittura della profondità. |
| [getDepthTest()](#getDepthTest--) | Abilita o disabilita il test di profondità. |
| [getDestinationBlendFactor()](#getDestinationBlendFactor--) | Ottiene come il colore è mescolato. |
| [getFrontFace()](#getFrontFace--) | Ottiene quale ordine è la front face. |
| [getPolygonMode()](#getPolygonMode--) | Ottiene la modalità di rendering del poligono. |
| [getScissorTest()](#getScissorTest--) | Abilita o disabilita lo scissor test |
| [getSourceBlendFactor()](#getSourceBlendFactor--) | Ottiene come il colore è mescolato. |
| [getStencilBackFace()](#getStencilBackFace--) | Ottiene lo stato dello stencil per la faccia posteriore. |
| [getStencilFrontFace()](#getStencilFrontFace--) | Ottiene lo stato dello stencil per la faccia anteriore. |
| [getStencilMask()](#getStencilMask--) | Ottiene la maschera che viene ANData sia con il valore di riferimento sia con il valore di stencil memorizzato quando il test è completato. |
| [getStencilReference()](#getStencilReference--) | Ottiene il valore di riferimento per il test di stencil. |
| [getStencilTest()](#getStencilTest--) | Abilita o disabilita il test di stencil. |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlend(boolean value)](#setBlend-boolean-) | Abilita o disabilita la fusione dei frammenti. |
| [setBlendColor(FVector4 value)](#setBlendColor-com.aspose.threed.FVector4-) | Imposta il colore di fusione dove è usato in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [setCullFace(boolean value)](#setCullFace-boolean-) | Abilita o disabilita il cull face |
| [setCullFaceMode(int value)](#setCullFaceMode-int-) | Imposta quale faccia sarà cullata. |
| [setDepthFunction(CompareFunction value)](#setDepthFunction-com.aspose.threed.CompareFunction-) | Imposta la funzione di confronto usata nel test di profondità |
| [setDepthMask(boolean value)](#setDepthMask-boolean-) | Abilita o disabilita la scrittura della profondità. |
| [setDepthTest(boolean value)](#setDepthTest-boolean-) | Abilita o disabilita il test di profondità. |
| [setDestinationBlendFactor(BlendFactor value)](#setDestinationBlendFactor-com.aspose.threed.BlendFactor-) | Imposta come il colore è mescolato. |
| [setFrontFace(FrontFace value)](#setFrontFace-com.aspose.threed.FrontFace-) | Imposta quale ordine è la front face. |
| [setPolygonMode(PolygonMode value)](#setPolygonMode-com.aspose.threed.PolygonMode-) | Sets the polygon's render mode. |
| [setScissorTest(boolean value)](#setScissorTest-boolean-) | Abilita o disabilita lo scissor test |
| [setSourceBlendFactor(BlendFactor value)](#setSourceBlendFactor-com.aspose.threed.BlendFactor-) | Imposta come il colore è mescolato. |
| [setStencilMask(int value)](#setStencilMask-int-) | Sets the mask that is ANDed with the both reference and stored stencil value when test is done. |
| [setStencilReference(int value)](#setStencilReference-int-) | Sets the reference value for the stencil test. |
| [setStencilTest(boolean value)](#setStencilTest-boolean-) | Abilita o disabilita il test di stencil. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderState() {#RenderState--}
```
public RenderState()
```


Costruttore di [RenderState](../../com.aspose.threed/renderstate)

### close() {#close--}
```
public void close()
```


Rilascia il [RenderState](../../com.aspose.threed/renderstate) e libera tutte le risorse interne.

### compareTo(RenderState other) {#compareTo-com.aspose.threed.RenderState-}
```
public int compareTo(RenderState other)
```


Confronta lo stato di rendering con un'altra istanza

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [RenderState](../../com.aspose.threed/renderstate) | Another render state to compare |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Restituisce un valore che indica se questa istanza è uguale a un oggetto specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getBlend() {#getBlend--}
```
public boolean getBlend()
```


Abilita o disabilita la fusione dei frammenti.

**Returns:**
boolean - Enable or disable the fragment blending.
### getBlendColor() {#getBlendColor--}
```
public FVector4 getBlendColor()
```


Ottiene il colore di fusione dove è usato in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

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


Abilita o disabilita il cull face

**Returns:**
boolean - Enable or disable cull face
### getCullFaceMode() {#getCullFaceMode--}
```
public int getCullFaceMode()
```


Ottiene quale faccia verrà cullata.

**Returns:**
int - which face will be culled.
### getDepthFunction() {#getDepthFunction--}
```
public CompareFunction getDepthFunction()
```


Ottiene la funzione di confronto usata nel test di profondità

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in depth test
### getDepthMask() {#getDepthMask--}
```
public boolean getDepthMask()
```


Abilita o disabilita la scrittura della profondità.

**Returns:**
boolean - Enable or disable the depth writing.
### getDepthTest() {#getDepthTest--}
```
public boolean getDepthTest()
```


Abilita o disabilita il test di profondità.

**Returns:**
boolean - Enable or disable the depth test.
### getDestinationBlendFactor() {#getDestinationBlendFactor--}
```
public BlendFactor getDestinationBlendFactor()
```


Ottiene come il colore è mescolato.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getFrontFace() {#getFrontFace--}
```
public FrontFace getFrontFace()
```


Ottiene quale ordine è la front face.

**Returns:**
[FrontFace](../../com.aspose.threed/frontface) - which order is front face.
### getPolygonMode() {#getPolygonMode--}
```
public PolygonMode getPolygonMode()
```


Ottiene la modalità di rendering del poligono.

**Returns:**
[PolygonMode](../../com.aspose.threed/polygonmode) - the polygon's render mode.
### getScissorTest() {#getScissorTest--}
```
public boolean getScissorTest()
```


Abilita o disabilita lo scissor test

**Returns:**
boolean - Enable or disable scissor test
### getSourceBlendFactor() {#getSourceBlendFactor--}
```
public BlendFactor getSourceBlendFactor()
```


Ottiene come il colore è mescolato.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getStencilBackFace() {#getStencilBackFace--}
```
public StencilState getStencilBackFace()
```


Ottiene lo stato dello stencil per la faccia posteriore.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for back face.
### getStencilFrontFace() {#getStencilFrontFace--}
```
public StencilState getStencilFrontFace()
```


Ottiene lo stato dello stencil per la faccia anteriore.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for front face.
### getStencilMask() {#getStencilMask--}
```
public int getStencilMask()
```


Ottiene la maschera che viene ANData sia con il valore di riferimento sia con il valore di stencil memorizzato quando il test è completato.

**Returns:**
int - the mask that is ANDed with the both reference and stored stencil value when test is done.
### getStencilReference() {#getStencilReference--}
```
public int getStencilReference()
```


Ottiene il valore di riferimento per il test di stencil.

**Returns:**
int - the reference value for the stencil test.
### getStencilTest() {#getStencilTest--}
```
public boolean getStencilTest()
```


Abilita o disabilita il test di stencil.

**Returns:**
boolean - Enable or disable the stencil test.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash per questa istanza.

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


Abilita o disabilita la fusione dei frammenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setBlendColor(FVector4 value) {#setBlendColor-com.aspose.threed.FVector4-}
```
public void setBlendColor(FVector4 value)
```


Imposta il colore di fusione dove è usato in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FVector4](../../com.aspose.threed/fvector4) | Nuovo valore |

### setCullFace(boolean value) {#setCullFace-boolean-}
```
public void setCullFace(boolean value)
```


Abilita o disabilita il cull face

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setCullFaceMode(int value) {#setCullFaceMode-int-}
```
public void setCullFaceMode(int value)
```


Imposta quale faccia sarà cullata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Nuovo valore |

### setDepthFunction(CompareFunction value) {#setDepthFunction-com.aspose.threed.CompareFunction-}
```
public void setDepthFunction(CompareFunction value)
```


Imposta la funzione di confronto usata nel test di profondità

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | Nuovo valore |

### setDepthMask(boolean value) {#setDepthMask-boolean-}
```
public void setDepthMask(boolean value)
```


Abilita o disabilita la scrittura della profondità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setDepthTest(boolean value) {#setDepthTest-boolean-}
```
public void setDepthTest(boolean value)
```


Abilita o disabilita il test di profondità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setDestinationBlendFactor(BlendFactor value) {#setDestinationBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setDestinationBlendFactor(BlendFactor value)
```


Imposta come il colore è mescolato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | Nuovo valore |

### setFrontFace(FrontFace value) {#setFrontFace-com.aspose.threed.FrontFace-}
```
public void setFrontFace(FrontFace value)
```


Imposta quale ordine è la front face.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FrontFace](../../com.aspose.threed/frontface) | Nuovo valore |

### setPolygonMode(PolygonMode value) {#setPolygonMode-com.aspose.threed.PolygonMode-}
```
public void setPolygonMode(PolygonMode value)
```


Sets the polygon's render mode.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PolygonMode](../../com.aspose.threed/polygonmode) | Nuovo valore |

### setScissorTest(boolean value) {#setScissorTest-boolean-}
```
public void setScissorTest(boolean value)
```


Abilita o disabilita lo scissor test

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setSourceBlendFactor(BlendFactor value) {#setSourceBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setSourceBlendFactor(BlendFactor value)
```


Imposta come il colore è mescolato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | Nuovo valore |

### setStencilMask(int value) {#setStencilMask-int-}
```
public void setStencilMask(int value)
```


Sets the mask that is ANDed with the both reference and stored stencil value when test is done.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Nuovo valore |

### setStencilReference(int value) {#setStencilReference-int-}
```
public void setStencilReference(int value)
```


Sets the reference value for the stencil test.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Nuovo valore |

### setStencilTest(boolean value) {#setStencilTest-boolean-}
```
public void setStencilTest(boolean value)
```


Abilita o disabilita il test di stencil.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

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

