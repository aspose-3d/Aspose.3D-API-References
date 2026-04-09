---
title: RenderState
second_title: Aspose.3D for Java API-referentie
description: Renderstatus voor het bouwen van de pijplijn. De wijzigingen die op de renderstatus worden aangebracht, hebben geen invloed op de gemaakte pijplijn‑instanties.
type: docs
weight: 151
url: /nl/java/com.aspose.threed/renderstate/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable, java.lang.Comparable
```
public class RenderState implements Closeable, Comparable<RenderState>
```

Renderstatus voor het bouwen van de pipeline. De wijzigingen die op de renderstatus worden aangebracht, hebben geen invloed op de gemaakte pipeline-instanties.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [RenderState()](#RenderState--) | Constructor van [RenderState](../../com.aspose.threed/renderstate) |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [close()](#close--) | Verwijder de [RenderState](../../com.aspose.threed/renderstate) en geef alle interne bronnen vrij. |
| [compareTo(RenderState other)](#compareTo-com.aspose.threed.RenderState-) | Vergelijk de renderstatus met een andere instantie |
| [equals(Object obj)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven object. |
| [getBlend()](#getBlend--) | Schakel het fragmentblenden in of uit. |
| [getBlendColor()](#getBlendColor--) | Haalt de blendkleur op die wordt gebruikt in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [getClass()](#getClass--) |  |
| [getCullFace()](#getCullFace--) | Schakel cull face in of uit |
| [getCullFaceMode()](#getCullFaceMode--) | Haalt op welke face wordt gecullt. |
| [getDepthFunction()](#getDepthFunction--) | Haalt de vergelijkingsfunctie op die wordt gebruikt in de dieptetest |
| [getDepthMask()](#getDepthMask--) | Schakel het schrijven van diepte in of uit. |
| [getDepthTest()](#getDepthTest--) | Schakel de dieptetest in uit. |
| [getDestinationBlendFactor()](#getDestinationBlendFactor--) | Haalt op hoe de kleur wordt gemengd. |
| [getFrontFace()](#getFrontFace--) | Haalt op welke volgorde de front face is. |
| [getPolygonMode()](#getPolygonMode--) | Haalt de rendermodus van de polygoon op. |
| [getScissorTest()](#getScissorTest--) | Schakel de scissortest in of uit. |
| [getSourceBlendFactor()](#getSourceBlendFactor--) | Haalt op hoe de kleur wordt gemengd. |
| [getStencilBackFace()](#getStencilBackFace--) | Haalt de stencilstatus op voor de back face. |
| [getStencilFrontFace()](#getStencilFrontFace--) | Haalt de stencilstatus op voor de front face. |
| [getStencilMask()](#getStencilMask--) | Haalt het masker op dat wordt ge-AND met zowel de referentie- als de opgeslagen stencilwaarde wanneer de test is voltooid. |
| [getStencilReference()](#getStencilReference--) | Haalt de referentiewaarde op voor de stenciltest. |
| [getStencilTest()](#getStencilTest--) | Schakel de stenciltest in of uit. |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlend(boolean value)](#setBlend-boolean-) | Schakel het fragmentblenden in of uit. |
| [setBlendColor(FVector4 value)](#setBlendColor-com.aspose.threed.FVector4-) | Stelt de blendkleur in die wordt gebruikt in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR) |
| [setCullFace(boolean value)](#setCullFace-boolean-) | Schakel cull face in of uit |
| [setCullFaceMode(int value)](#setCullFaceMode-int-) | Stelt in welke face wordt gecullt. |
| [setDepthFunction(CompareFunction value)](#setDepthFunction-com.aspose.threed.CompareFunction-) | Stelt de vergelijkingsfunctie in die wordt gebruikt in de dieptetest |
| [setDepthMask(boolean value)](#setDepthMask-boolean-) | Schakel het schrijven van diepte in of uit. |
| [setDepthTest(boolean value)](#setDepthTest-boolean-) | Schakel de dieptetest in uit. |
| [setDestinationBlendFactor(BlendFactor value)](#setDestinationBlendFactor-com.aspose.threed.BlendFactor-) | Stelt in hoe de kleur wordt gemengd. |
| [setFrontFace(FrontFace value)](#setFrontFace-com.aspose.threed.FrontFace-) | Stelt in welke volgorde de front face is. |
| [setPolygonMode(PolygonMode value)](#setPolygonMode-com.aspose.threed.PolygonMode-) | Stelt de rendermodus van de polygoon in. |
| [setScissorTest(boolean value)](#setScissorTest-boolean-) | Schakel de scissortest in of uit. |
| [setSourceBlendFactor(BlendFactor value)](#setSourceBlendFactor-com.aspose.threed.BlendFactor-) | Stelt in hoe de kleur wordt gemengd. |
| [setStencilMask(int value)](#setStencilMask-int-) | Stelt het masker in dat wordt EN-gelijkt met zowel de referentiewaarde als de opgeslagen stencilwaarde wanneer de test is voltooid. |
| [setStencilReference(int value)](#setStencilReference-int-) | Stelt de referentiewaarde in voor de stenciltest. |
| [setStencilTest(boolean value)](#setStencilTest-boolean-) | Schakel de stenciltest in of uit. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderState() {#RenderState--}
```
public RenderState()
```


Constructor van [RenderState](../../com.aspose.threed/renderstate)

### close() {#close--}
```
public void close()
```


Verwijder de [RenderState](../../com.aspose.threed/renderstate) en geef alle interne bronnen vrij.

### compareTo(RenderState other) {#compareTo-com.aspose.threed.RenderState-}
```
public int compareTo(RenderState other)
```


Vergelijk de renderstatus met een andere instantie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [RenderState](../../com.aspose.threed/renderstate) | Een andere renderstatus om te vergelijken |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getBlend() {#getBlend--}
```
public boolean getBlend()
```


Schakel het fragmentblenden in of uit.

**Returns:**
boolean - Inschakelen of uitschakelen van fragmentblending.
### getBlendColor() {#getBlendColor--}
```
public FVector4 getBlendColor()
```


Haalt de blendkleur op die wordt gebruikt in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

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


Schakel cull face in of uit

**Returns:**
boolean - Inschakelen of uitschakelen van cull face
### getCullFaceMode() {#getCullFaceMode--}
```
public int getCullFaceMode()
```


Haalt op welke face wordt gecullt.

**Returns:**
int - welke face zal worden geculld.
### getDepthFunction() {#getDepthFunction--}
```
public CompareFunction getDepthFunction()
```


Haalt de vergelijkingsfunctie op die wordt gebruikt in de dieptetest

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction) - the compare function used in depth test
### getDepthMask() {#getDepthMask--}
```
public boolean getDepthMask()
```


Schakel het schrijven van diepte in of uit.

**Returns:**
boolean - Inschakelen of uitschakelen van diepte‑schrijven.
### getDepthTest() {#getDepthTest--}
```
public boolean getDepthTest()
```


Schakel de dieptetest in uit.

**Returns:**
boolean - Inschakelen of uitschakelen van dieptetest.
### getDestinationBlendFactor() {#getDestinationBlendFactor--}
```
public BlendFactor getDestinationBlendFactor()
```


Haalt op hoe de kleur wordt gemengd.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getFrontFace() {#getFrontFace--}
```
public FrontFace getFrontFace()
```


Haalt op welke volgorde de front face is.

**Returns:**
[FrontFace](../../com.aspose.threed/frontface) - which order is front face.
### getPolygonMode() {#getPolygonMode--}
```
public PolygonMode getPolygonMode()
```


Haalt de rendermodus van de polygoon op.

**Returns:**
[PolygonMode](../../com.aspose.threed/polygonmode) - the polygon's render mode.
### getScissorTest() {#getScissorTest--}
```
public boolean getScissorTest()
```


Schakel de scissortest in of uit.

**Returns:**
boolean - Inschakelen of uitschakelen van scissortest
### getSourceBlendFactor() {#getSourceBlendFactor--}
```
public BlendFactor getSourceBlendFactor()
```


Haalt op hoe de kleur wordt gemengd.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor) - how the color is blended.
### getStencilBackFace() {#getStencilBackFace--}
```
public StencilState getStencilBackFace()
```


Haalt de stencilstatus op voor de back face.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for back face.
### getStencilFrontFace() {#getStencilFrontFace--}
```
public StencilState getStencilFrontFace()
```


Haalt de stencilstatus op voor de front face.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate) - the stencil state for front face.
### getStencilMask() {#getStencilMask--}
```
public int getStencilMask()
```


Haalt het masker op dat wordt ge-AND met zowel de referentie- als de opgeslagen stencilwaarde wanneer de test is voltooid.

**Returns:**
int - het masker dat wordt EN-gelijkt met zowel de referentiewaarde als de opgeslagen stencilwaarde wanneer de test is voltooid.
### getStencilReference() {#getStencilReference--}
```
public int getStencilReference()
```


Haalt de referentiewaarde op voor de stenciltest.

**Returns:**
int - de referentiewaarde voor de stenciltest.
### getStencilTest() {#getStencilTest--}
```
public boolean getStencilTest()
```


Schakel de stenciltest in of uit.

**Returns:**
boolean - Inschakelen of uitschakelen van de stenciltest.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor deze instantie.

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


Schakel het fragmentblenden in of uit.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setBlendColor(FVector4 value) {#setBlendColor-com.aspose.threed.FVector4-}
```
public void setBlendColor(FVector4 value)
```


Stelt de blendkleur in die wordt gebruikt in [BlendFactor.CONSTANT\_COLOR](../../com.aspose.threed/blendfactor\#CONSTANT-COLOR)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FVector4](../../com.aspose.threed/fvector4) | Nieuwe waarde |

### setCullFace(boolean value) {#setCullFace-boolean-}
```
public void setCullFace(boolean value)
```


Schakel cull face in of uit

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setCullFaceMode(int value) {#setCullFaceMode-int-}
```
public void setCullFaceMode(int value)
```


Stelt in welke face wordt gecullt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Nieuwe waarde |

### setDepthFunction(CompareFunction value) {#setDepthFunction-com.aspose.threed.CompareFunction-}
```
public void setDepthFunction(CompareFunction value)
```


Stelt de vergelijkingsfunctie in die wordt gebruikt in de dieptetest

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | Nieuwe waarde |

### setDepthMask(boolean value) {#setDepthMask-boolean-}
```
public void setDepthMask(boolean value)
```


Schakel het schrijven van diepte in of uit.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setDepthTest(boolean value) {#setDepthTest-boolean-}
```
public void setDepthTest(boolean value)
```


Schakel de dieptetest in uit.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setDestinationBlendFactor(BlendFactor value) {#setDestinationBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setDestinationBlendFactor(BlendFactor value)
```


Stelt in hoe de kleur wordt gemengd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | Nieuwe waarde |

### setFrontFace(FrontFace value) {#setFrontFace-com.aspose.threed.FrontFace-}
```
public void setFrontFace(FrontFace value)
```


Stelt in welke volgorde de front face is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FrontFace](../../com.aspose.threed/frontface) | Nieuwe waarde |

### setPolygonMode(PolygonMode value) {#setPolygonMode-com.aspose.threed.PolygonMode-}
```
public void setPolygonMode(PolygonMode value)
```


Stelt de rendermodus van de polygoon in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PolygonMode](../../com.aspose.threed/polygonmode) | Nieuwe waarde |

### setScissorTest(boolean value) {#setScissorTest-boolean-}
```
public void setScissorTest(boolean value)
```


Schakel de scissortest in of uit.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setSourceBlendFactor(BlendFactor value) {#setSourceBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setSourceBlendFactor(BlendFactor value)
```


Stelt in hoe de kleur wordt gemengd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | Nieuwe waarde |

### setStencilMask(int value) {#setStencilMask-int-}
```
public void setStencilMask(int value)
```


Stelt het masker in dat wordt EN-gelijkt met zowel de referentiewaarde als de opgeslagen stencilwaarde wanneer de test is voltooid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Nieuwe waarde |

### setStencilReference(int value) {#setStencilReference-int-}
```
public void setStencilReference(int value)
```


Stelt de referentiewaarde in voor de stenciltest.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Nieuwe waarde |

### setStencilTest(boolean value) {#setStencilTest-boolean-}
```
public void setStencilTest(boolean value)
```


Schakel de stenciltest in of uit.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

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

