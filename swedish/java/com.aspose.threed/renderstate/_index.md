---
title: RenderState
second_title: Aspose.3D for Java API-referens
description: Render‑tillstånd för att bygga pipeline‑kedjan. Ändringarna som görs på render‑tillståndet påverkar inte de skapade pipeline‑instanserna.
type: docs
weight: 151
url: /sv/java/com.aspose.threed/renderstate/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable, java.lang.Comparable
```
public class RenderState implements Closeable, Comparable<RenderState>
```

Render‑tillstånd för att bygga pipeline‑tillståndet Ändringarna som görs på render‑tillståndet kommer inte att påverka de skapade pipeline‑instanserna.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [RenderState()](#RenderState--) | Konstruktor för [RenderState](../../com.aspose.threed/renderstate) |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [close()](#close--) | Frigör [RenderState](../../com.aspose.threed/renderstate) och släpp alla interna resurser. |
| [compareTo(RenderState other)](#compareTo-com.aspose.threed.RenderState-) | Jämför renderingsstatus med en annan instans |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om den här instansen är lika med ett angivet objekt. |
| [getBlend()](#getBlend--) | Aktivera eller inaktivera fragmentblandning. |
| [getBlendColor()](#getBlendColor--) | Hämtar blandningsfärgen där den används i [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [getClass()](#getClass--) |  |
| [getCullFace()](#getCullFace--) | Aktivera eller inaktivera cull face |
| [getCullFaceMode()](#getCullFaceMode--) | Hämtar vilken yta som kommer att cullas. |
| [getDepthFunction()](#getDepthFunction--) | Hämtar jämförelsefunktionen som används i djup-testet |
| [getDepthMask()](#getDepthMask--) | Aktivera eller inaktivera djupskrivning. |
| [getDepthTest()](#getDepthTest--) | Aktivera eller inaktivera djuptestet. |
| [getDestinationBlendFactor()](#getDestinationBlendFactor--) | Hämtar hur färgen blandas. |
| [getFrontFace()](#getFrontFace--) | Hämtar vilken ordning som är front face. |
| [getPolygonMode()](#getPolygonMode--) | Hämtar polygonens renderingsläge. |
| [getScissorTest()](#getScissorTest--) | Aktivera eller inaktivera scissor-test |
| [getSourceBlendFactor()](#getSourceBlendFactor--) | Hämtar hur färgen blandas. |
| [getStencilBackFace()](#getStencilBackFace--) | Hämtar stenciltillståndet för back face. |
| [getStencilFrontFace()](#getStencilFrontFace--) | Hämtar stenciltillståndet för front face. |
| [getStencilMask()](#getStencilMask--) | Hämtar masken som ANDas med både referens‑ och lagrat stencilvärde när testet är klart. |
| [getStencilReference()](#getStencilReference--) | Hämtar referensvärdet för stenciltestet. |
| [getStencilTest()](#getStencilTest--) | Aktivera eller inaktivera stenciltestet. |
| [hashCode()](#hashCode--) | Returnerar hashkoden för den här instansen. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlend(boolean value)](#setBlend-boolean-) | Aktivera eller inaktivera fragmentblandning. |
| [setBlendColor(FVector4 value)](#setBlendColor-com.aspose.threed.FVector4-) | Ställer in blandningsfärgen där den används i [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [setCullFace(boolean value)](#setCullFace-boolean-) | Aktivera eller inaktivera cull face |
| [setCullFaceMode(int value)](#setCullFaceMode-int-) | Ställer in vilken yta som ska cullas. |
| [setDepthFunction(CompareFunction value)](#setDepthFunction-com.aspose.threed.CompareFunction-) | Ställer in jämförelsefunktionen som används i djup-testet |
| [setDepthMask(boolean value)](#setDepthMask-boolean-) | Aktivera eller inaktivera djupskrivning. |
| [setDepthTest(boolean value)](#setDepthTest-boolean-) | Aktivera eller inaktivera djuptestet. |
| [setDestinationBlendFactor(BlendFactor value)](#setDestinationBlendFactor-com.aspose.threed.BlendFactor-) | Ställer in hur färgen blandas. |
| [setFrontFace(FrontFace value)](#setFrontFace-com.aspose.threed.FrontFace-) | Ställer in vilken ordning som är front face. |
| [setPolygonMode(PolygonMode value)](#setPolygonMode-com.aspose.threed.PolygonMode-) | Ställer in polygonens renderingsläge. |
| [setScissorTest(boolean value)](#setScissorTest-boolean-) | Aktivera eller inaktivera scissor-test |
| [setSourceBlendFactor(BlendFactor value)](#setSourceBlendFactor-com.aspose.threed.BlendFactor-) | Ställer in hur färgen blandas. |
| [setStencilMask(int value)](#setStencilMask-int-) | Ställer in masken som ANDas med både referens- och lagrat stencilvärde när testet är klart. |
| [setStencilReference(int value)](#setStencilReference-int-) | Ställer in referensvärdet för stenciltestet. |
| [setStencilTest(boolean value)](#setStencilTest-boolean-) | Aktivera eller inaktivera stenciltestet. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderState() {#RenderState--}
```
public RenderState()
```


Konstruktor för [RenderState](../../com.aspose.threed/renderstate)

### close() {#close--}
```
public void close()
```


Frigör [RenderState](../../com.aspose.threed/renderstate) och släpp alla interna resurser.

### compareTo(RenderState other) {#compareTo-com.aspose.threed.RenderState-}
```
public int compareTo(RenderState other)
```


Jämför renderingsstatus med en annan instans

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [RenderState](../../com.aspose.threed/renderstate) | Ett annat renderingsläge att jämföra |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returnerar ett värde som indikerar om den här instansen är lika med ett angivet objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getBlend() {#getBlend--}
```
public boolean getBlend()
```


Aktivera eller inaktivera fragmentblandning.

**Returns:**
boolean - Aktivera eller inaktivera fragmentblandning.
### getBlendColor() {#getBlendColor--}
```
public FVector4 getBlendColor()
```


Hämtar blandningsfärgen där den används i [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

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


Aktivera eller inaktivera cull face

**Returns:**
boolean - Aktivera eller inaktivera cull face
### getCullFaceMode() {#getCullFaceMode--}
```
public int getCullFaceMode()
```


Hämtar vilken yta som kommer att cullas.

**Returns:**
int - vilken yta som kommer att cullas.
### getDepthFunction() {#getDepthFunction--}
```
public CompareFunction getDepthFunction()
```


Hämtar jämförelsefunktionen som används i djup-testet

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in depth test
### getDepthMask() {#getDepthMask--}
```
public boolean getDepthMask()
```


Aktivera eller inaktivera djupskrivning.

**Returns:**
boolean - Aktivera eller inaktivera djupskrivning.
### getDepthTest() {#getDepthTest--}
```
public boolean getDepthTest()
```


Aktivera eller inaktivera djuptestet.

**Returns:**
boolean - Aktivera eller inaktivera djupstest.
### getDestinationBlendFactor() {#getDestinationBlendFactor--}
```
public BlendFactor getDestinationBlendFactor()
```


Hämtar hur färgen blandas.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getFrontFace() {#getFrontFace--}
```
public FrontFace getFrontFace()
```


Hämtar vilken ordning som är front face.

**Returns:**
[FrontFace](../../com.aspose.threed/frontface) - which order is front face.
### getPolygonMode() {#getPolygonMode--}
```
public PolygonMode getPolygonMode()
```


Hämtar polygonens renderingsläge.

**Returns:**
[PolygonMode](../../com.aspose.threed/polygonmode) - the polygon's render mode.
### getScissorTest() {#getScissorTest--}
```
public boolean getScissorTest()
```


Aktivera eller inaktivera scissor-test

**Returns:**
boolean - Aktivera eller inaktivera scissortest
### getSourceBlendFactor() {#getSourceBlendFactor--}
```
public BlendFactor getSourceBlendFactor()
```


Hämtar hur färgen blandas.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getStencilBackFace() {#getStencilBackFace--}
```
public StencilState getStencilBackFace()
```


Hämtar stenciltillståndet för back face.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for back face.
### getStencilFrontFace() {#getStencilFrontFace--}
```
public StencilState getStencilFrontFace()
```


Hämtar stenciltillståndet för front face.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for front face.
### getStencilMask() {#getStencilMask--}
```
public int getStencilMask()
```


Hämtar masken som ANDas med både referens‑ och lagrat stencilvärde när testet är klart.

**Returns:**
int - masken som ANDas med både referens- och lagrat stencilvärde när testet är klart.
### getStencilReference() {#getStencilReference--}
```
public int getStencilReference()
```


Hämtar referensvärdet för stenciltestet.

**Returns:**
int - referensvärdet för stenciltestet.
### getStencilTest() {#getStencilTest--}
```
public boolean getStencilTest()
```


Aktivera eller inaktivera stenciltestet.

**Returns:**
boolean - Aktivera eller inaktivera stenciltestet.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hashkoden för den här instansen.

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


Aktivera eller inaktivera fragmentblandning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setBlendColor(FVector4 value) {#setBlendColor-com.aspose.threed.FVector4-}
```
public void setBlendColor(FVector4 value)
```


Ställer in blandningsfärgen där den används i [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FVector4](../../com.aspose.threed/fvector4) | Nytt värde |

### setCullFace(boolean value) {#setCullFace-boolean-}
```
public void setCullFace(boolean value)
```


Aktivera eller inaktivera cull face

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setCullFaceMode(int value) {#setCullFaceMode-int-}
```
public void setCullFaceMode(int value)
```


Ställer in vilken yta som ska cullas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Nytt värde |

### setDepthFunction(CompareFunction value) {#setDepthFunction-com.aspose.threed.CompareFunction-}
```
public void setDepthFunction(CompareFunction value)
```


Ställer in jämförelsefunktionen som används i djup-testet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | Nytt värde |

### setDepthMask(boolean value) {#setDepthMask-boolean-}
```
public void setDepthMask(boolean value)
```


Aktivera eller inaktivera djupskrivning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setDepthTest(boolean value) {#setDepthTest-boolean-}
```
public void setDepthTest(boolean value)
```


Aktivera eller inaktivera djuptestet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setDestinationBlendFactor(BlendFactor value) {#setDestinationBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setDestinationBlendFactor(BlendFactor value)
```


Ställer in hur färgen blandas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | Nytt värde |

### setFrontFace(FrontFace value) {#setFrontFace-com.aspose.threed.FrontFace-}
```
public void setFrontFace(FrontFace value)
```


Ställer in vilken ordning som är front face.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FrontFace](../../com.aspose.threed/frontface) | Nytt värde |

### setPolygonMode(PolygonMode value) {#setPolygonMode-com.aspose.threed.PolygonMode-}
```
public void setPolygonMode(PolygonMode value)
```


Ställer in polygonens renderingsläge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PolygonMode](../../com.aspose.threed/polygonmode) | Nytt värde |

### setScissorTest(boolean value) {#setScissorTest-boolean-}
```
public void setScissorTest(boolean value)
```


Aktivera eller inaktivera scissor-test

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setSourceBlendFactor(BlendFactor value) {#setSourceBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setSourceBlendFactor(BlendFactor value)
```


Ställer in hur färgen blandas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | Nytt värde |

### setStencilMask(int value) {#setStencilMask-int-}
```
public void setStencilMask(int value)
```


Ställer in masken som ANDas med både referens- och lagrat stencilvärde när testet är klart.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Nytt värde |

### setStencilReference(int value) {#setStencilReference-int-}
```
public void setStencilReference(int value)
```


Ställer in referensvärdet för stenciltestet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Nytt värde |

### setStencilTest(boolean value) {#setStencilTest-boolean-}
```
public void setStencilTest(boolean value)
```


Aktivera eller inaktivera stenciltestet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

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

