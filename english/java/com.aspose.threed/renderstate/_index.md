---
title: RenderState
second_title: Aspose.3D for Java API Reference
description: Render state for building the pipeline
 The changes made on render state will not affect the created pipeline instances.
type: docs
weight: 136
url: /java/com.aspose.threed/renderstate/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable, java.lang.Comparable
```
public class RenderState implements Closeable, Comparable<RenderState>
```

Render state for building the pipeline The changes made on render state will not affect the created pipeline instances.
## Constructors

| Constructor | Description |
| --- | --- |
| [RenderState()](#RenderState--) | Constructor of com.aspose.threed.RenderState |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returns a value indicating whether this instance is equal to a specified object. |
| [getBlend()](#getBlend--) | Enable or disable the fragment blending. |
| [setBlend(boolean value)](#setBlend-boolean-) | Enable or disable the fragment blending. |
| [getBlendColor()](#getBlendColor--) | Gets the blend color where used in com.aspose.threed.BlendFactor\#CONSTANT\_COLOR |
| [setBlendColor(FVector4 value)](#setBlendColor-com.aspose.threed.FVector4-) | Sets the blend color where used in com.aspose.threed.BlendFactor\#CONSTANT\_COLOR |
| [getSourceBlendFactor()](#getSourceBlendFactor--) | Gets how the color is blended. |
| [setSourceBlendFactor(BlendFactor value)](#setSourceBlendFactor-com.aspose.threed.BlendFactor-) | Sets how the color is blended. |
| [getDestinationBlendFactor()](#getDestinationBlendFactor--) | Gets how the color is blended. |
| [setDestinationBlendFactor(BlendFactor value)](#setDestinationBlendFactor-com.aspose.threed.BlendFactor-) | Sets how the color is blended. |
| [getCullFace()](#getCullFace--) | Enable or disable cull face |
| [setCullFace(boolean value)](#setCullFace-boolean-) | Enable or disable cull face |
| [getCullFaceMode()](#getCullFaceMode--) | Gets which face will be culled. |
| [setCullFaceMode(int value)](#setCullFaceMode-int-) | Sets which face will be culled. |
| [getFrontFace()](#getFrontFace--) | Gets which order is front face. |
| [setFrontFace(FrontFace value)](#setFrontFace-com.aspose.threed.FrontFace-) | Sets which order is front face. |
| [getDepthTest()](#getDepthTest--) | Enable or disable the depth test. |
| [setDepthTest(boolean value)](#setDepthTest-boolean-) | Enable or disable the depth test. |
| [getDepthMask()](#getDepthMask--) | Enable or disable the depth writing. |
| [setDepthMask(boolean value)](#setDepthMask-boolean-) | Enable or disable the depth writing. |
| [getDepthFunction()](#getDepthFunction--) | Gets the compare function used in depth test |
| [setDepthFunction(CompareFunction value)](#setDepthFunction-com.aspose.threed.CompareFunction-) | Sets the compare function used in depth test |
| [getStencilTest()](#getStencilTest--) | Enable or disable the stencil test. |
| [setStencilTest(boolean value)](#setStencilTest-boolean-) | Enable or disable the stencil test. |
| [getStencilReference()](#getStencilReference--) | Gets the reference value for the stencil test. |
| [setStencilReference(int value)](#setStencilReference-int-) | Sets the reference value for the stencil test. |
| [getStencilMask()](#getStencilMask--) | Gets the mask that is ANDed with the both reference and stored stencil value when test is done. |
| [setStencilMask(int value)](#setStencilMask-int-) | Sets the mask that is ANDed with the both reference and stored stencil value when test is done. |
| [getStencilFrontFace()](#getStencilFrontFace--) | Gets the stencil state for front face. |
| [getStencilBackFace()](#getStencilBackFace--) | Gets the stencil state for back face. |
| [getScissorTest()](#getScissorTest--) | Enable or disable scissor test |
| [setScissorTest(boolean value)](#setScissorTest-boolean-) | Enable or disable scissor test |
| [getScissorBox()](#getScissorBox--) | Gets the scissor box |
| [setScissorBox(Rectangle value)](#setScissorBox-java.awt.Rectangle-) | Sets the scissor box |
| [getPolygonMode()](#getPolygonMode--) | Gets the polygon's render mode. |
| [setPolygonMode(PolygonMode value)](#setPolygonMode-com.aspose.threed.PolygonMode-) | Sets the polygon's render mode. |
| [compareTo(RenderState other)](#compareTo-com.aspose.threed.RenderState-) | Compare the render state with another instance |
| [hashCode()](#hashCode--) | Returns the hash code for this instance. |
| [close()](#close--) | Dispose the com.aspose.threed.RenderState and release all internal resources. |
### RenderState() {#RenderState--}
```
public RenderState()
```


Constructor of com.aspose.threed.RenderState

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returns a value indicating whether this instance is equal to a specified object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getBlend() {#getBlend--}
```
public boolean getBlend()
```


Enable or disable the fragment blending.

**Returns:**
boolean
### setBlend(boolean value) {#setBlend-boolean-}
```
public void setBlend(boolean value)
```


Enable or disable the fragment blending.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | New value |

### getBlendColor() {#getBlendColor--}
```
public FVector4 getBlendColor()
```


Gets the blend color where used in com.aspose.threed.BlendFactor\#CONSTANT\_COLOR

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### setBlendColor(FVector4 value) {#setBlendColor-com.aspose.threed.FVector4-}
```
public void setBlendColor(FVector4 value)
```


Sets the blend color where used in com.aspose.threed.BlendFactor\#CONSTANT\_COLOR

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FVector4](../../com.aspose.threed/fvector4) | New value |

### getSourceBlendFactor() {#getSourceBlendFactor--}
```
public BlendFactor getSourceBlendFactor()
```


Gets how the color is blended.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor)
### setSourceBlendFactor(BlendFactor value) {#setSourceBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setSourceBlendFactor(BlendFactor value)
```


Sets how the color is blended.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | New value |

### getDestinationBlendFactor() {#getDestinationBlendFactor--}
```
public BlendFactor getDestinationBlendFactor()
```


Gets how the color is blended.

**Returns:**
[BlendFactor](../../com.aspose.threed/blendfactor)
### setDestinationBlendFactor(BlendFactor value) {#setDestinationBlendFactor-com.aspose.threed.BlendFactor-}
```
public void setDestinationBlendFactor(BlendFactor value)
```


Sets how the color is blended.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BlendFactor](../../com.aspose.threed/blendfactor) | New value |

### getCullFace() {#getCullFace--}
```
public boolean getCullFace()
```


Enable or disable cull face

**Returns:**
boolean
### setCullFace(boolean value) {#setCullFace-boolean-}
```
public void setCullFace(boolean value)
```


Enable or disable cull face

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | New value |

### getCullFaceMode() {#getCullFaceMode--}
```
public int getCullFaceMode()
```


Gets which face will be culled.

**Returns:**
int
### setCullFaceMode(int value) {#setCullFaceMode-int-}
```
public void setCullFaceMode(int value)
```


Sets which face will be culled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | New value |

### getFrontFace() {#getFrontFace--}
```
public FrontFace getFrontFace()
```


Gets which order is front face.

**Returns:**
[FrontFace](../../com.aspose.threed/frontface)
### setFrontFace(FrontFace value) {#setFrontFace-com.aspose.threed.FrontFace-}
```
public void setFrontFace(FrontFace value)
```


Sets which order is front face.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FrontFace](../../com.aspose.threed/frontface) | New value |

### getDepthTest() {#getDepthTest--}
```
public boolean getDepthTest()
```


Enable or disable the depth test.

**Returns:**
boolean
### setDepthTest(boolean value) {#setDepthTest-boolean-}
```
public void setDepthTest(boolean value)
```


Enable or disable the depth test.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | New value |

### getDepthMask() {#getDepthMask--}
```
public boolean getDepthMask()
```


Enable or disable the depth writing.

**Returns:**
boolean
### setDepthMask(boolean value) {#setDepthMask-boolean-}
```
public void setDepthMask(boolean value)
```


Enable or disable the depth writing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | New value |

### getDepthFunction() {#getDepthFunction--}
```
public CompareFunction getDepthFunction()
```


Gets the compare function used in depth test

**Returns:**
[CompareFunction](../../com.aspose.threed/comparefunction)
### setDepthFunction(CompareFunction value) {#setDepthFunction-com.aspose.threed.CompareFunction-}
```
public void setDepthFunction(CompareFunction value)
```


Sets the compare function used in depth test

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [CompareFunction](../../com.aspose.threed/comparefunction) | New value |

### getStencilTest() {#getStencilTest--}
```
public boolean getStencilTest()
```


Enable or disable the stencil test.

**Returns:**
boolean
### setStencilTest(boolean value) {#setStencilTest-boolean-}
```
public void setStencilTest(boolean value)
```


Enable or disable the stencil test.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | New value |

### getStencilReference() {#getStencilReference--}
```
public int getStencilReference()
```


Gets the reference value for the stencil test.

**Returns:**
int
### setStencilReference(int value) {#setStencilReference-int-}
```
public void setStencilReference(int value)
```


Sets the reference value for the stencil test.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | New value |

### getStencilMask() {#getStencilMask--}
```
public int getStencilMask()
```


Gets the mask that is ANDed with the both reference and stored stencil value when test is done.

**Returns:**
int
### setStencilMask(int value) {#setStencilMask-int-}
```
public void setStencilMask(int value)
```


Sets the mask that is ANDed with the both reference and stored stencil value when test is done.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | New value |

### getStencilFrontFace() {#getStencilFrontFace--}
```
public StencilState getStencilFrontFace()
```


Gets the stencil state for front face.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate)
### getStencilBackFace() {#getStencilBackFace--}
```
public StencilState getStencilBackFace()
```


Gets the stencil state for back face.

**Returns:**
[StencilState](../../com.aspose.threed/stencilstate)
### getScissorTest() {#getScissorTest--}
```
public boolean getScissorTest()
```


Enable or disable scissor test

**Returns:**
boolean
### setScissorTest(boolean value) {#setScissorTest-boolean-}
```
public void setScissorTest(boolean value)
```


Enable or disable scissor test

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | New value |

### getScissorBox() {#getScissorBox--}
```
public Rectangle getScissorBox()
```


Gets the scissor box

**Returns:**
java.awt.Rectangle
### setScissorBox(Rectangle value) {#setScissorBox-java.awt.Rectangle-}
```
public void setScissorBox(Rectangle value)
```


Sets the scissor box

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Rectangle | New value |

### getPolygonMode() {#getPolygonMode--}
```
public PolygonMode getPolygonMode()
```


Gets the polygon's render mode.

**Returns:**
[PolygonMode](../../com.aspose.threed/polygonmode)
### setPolygonMode(PolygonMode value) {#setPolygonMode-com.aspose.threed.PolygonMode-}
```
public void setPolygonMode(PolygonMode value)
```


Sets the polygon's render mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PolygonMode](../../com.aspose.threed/polygonmode) | New value |

### compareTo(RenderState other) {#compareTo-com.aspose.threed.RenderState-}
```
public int compareTo(RenderState other)
```


Compare the render state with another instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [RenderState](../../com.aspose.threed/renderstate) |  |

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns the hash code for this instance.

**Returns:**
int
### close() {#close--}
```
public void close()
```


Dispose the com.aspose.threed.RenderState and release all internal resources.
