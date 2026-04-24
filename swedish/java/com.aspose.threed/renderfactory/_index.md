---
title: RenderFactory
second_title: Aspose.3D for Java API-referens
description: RenderFactory skapar alla resurser som representeras i renderings‑pipeline.
type: docs
weight: 148
url: /sv/java/com.aspose.threed/renderfactory/
---

**Inheritance:**
java.lang.Object
```
public abstract class RenderFactory
```

RenderFactory skapar alla resurser som representeras i renderings‑pipeline.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [RenderFactory()](#RenderFactory--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createCubeRenderTexture(RenderParameters parameters, int width, int height)](#createCubeRenderTexture-com.aspose.threed.RenderParameters-int-int-) | Skapa ett renderingsmål som innehåller 1 kubtextur |
| [createDescriptorSet(ShaderProgram shader)](#createDescriptorSet-com.aspose.threed.ShaderProgram-) | Skapa beskrivaruppsättningen för angivet shaderprogram. |
| [createIndexBuffer()](#createIndexBuffer--) | Skapa en [IIndexBuffer](../../com.aspose.threed/iindexbuffer)-instans för att lagra polygonens ansiktsinformation. |
| [createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)](#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-) | Skapa en förkonfigurerad grafikpipeline med förkonfigurerad shader/render‑tillstånd/vertex‑deklaration och ritoperationer. |
| [createRenderTexture(RenderParameters parameters, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-) | Skapa ett renderingsmål som innehåller 1 mål som renderar till texturen |
| [createRenderTexture(RenderParameters parameters, int targets, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-) | Skapa ett renderingsmål som renderar till texturen |
| [createRenderWindow(RenderParameters parameters, WindowHandle handle)](#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-) | Skapa ett renderingsmål som renderar till det inbyggda fönstret. |
| [createShaderProgram(ShaderSource shaderSource)](#createShaderProgram-com.aspose.threed.ShaderSource-) | Skapa ett [ShaderProgram](../../com.aspose.threed/shaderprogram)-objekt |
| [createTextureUnit()](#createTextureUnit--) | Skapa en 2D-texturenhet som kan nås av shader. |
| [createTextureUnit(TextureType textureType)](#createTextureUnit-com.aspose.threed.TextureType-) | Skapa en texturenhet som kan nås av shader. |
| [createUniformBuffer(int size)](#createUniformBuffer-int-) | Skapa en ny uniform buffer på GPU-sidan med förallokerad storlek. |
| [createVertexBuffer(VertexDeclaration declaration)](#createVertexBuffer-com.aspose.threed.VertexDeclaration-) | Skapa en [IVertexBuffer](../../com.aspose.threed/ivertexbuffer)-instans för att lagra polygonens vertexinformation. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderFactory() {#RenderFactory--}
```
public RenderFactory()
```


### createCubeRenderTexture(RenderParameters parameters, int width, int height) {#createCubeRenderTexture-com.aspose.threed.RenderParameters-int-int-}
```
public abstract IRenderTexture createCubeRenderTexture(RenderParameters parameters, int width, int height)
```


Skapa ett renderingsmål som innehåller 1 kubtextur

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Renderingsparametrar för att skapa rendertexturen |
| bredd | int | Bredden på rendertexturen |
| höjd | int | Höjden på rendertexturen |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createDescriptorSet(ShaderProgram shader) {#createDescriptorSet-com.aspose.threed.ShaderProgram-}
```
public abstract IDescriptorSet createDescriptorSet(ShaderProgram shader)
```


Skapa beskrivaruppsättningen för angivet shaderprogram.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Shaderprogrammet |

**Returns:**
[IDescriptorSet](../../com.aspose.threed/idescriptorset) - A new descriptor set instance
### createIndexBuffer() {#createIndexBuffer--}
```
public abstract IIndexBuffer createIndexBuffer()
```


Skapa en [IIndexBuffer](../../com.aspose.threed/iindexbuffer)-instans för att lagra polygonens ansiktsinformation.

**Returns:**
[IIndexBuffer](../../com.aspose.threed/iindexbuffer)
### createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation) {#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-}
```
public abstract IPipeline createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)
```


Skapa en förkonfigurerad grafikpipeline med förkonfigurerad shader/render‑tillstånd/vertex‑deklaration och ritoperationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Shadern som används i rendering |
| renderState | [RenderState](../../com.aspose.threed/renderstate) | Render‑tillståndet som används i rendering |
| vertexDeclaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | Vertexdeklarationen för indata vertexdata |
| drawOperation | [DrawOperation](../../com.aspose.threed/drawoperation) | Draw operation |

**Returns:**
[IPipeline](../../com.aspose.threed/ipipeline) - A new pipeline instance
### createRenderTexture(RenderParameters parameters, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int width, int height)
```


Skapa ett renderingsmål som innehåller 1 mål som renderar till texturen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Renderingsparametrar för att skapa rendertexturen |
| bredd | int | Bredden på rendertexturen |
| höjd | int | Höjden på rendertexturen |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderTexture(RenderParameters parameters, int targets, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int targets, int width, int height)
```


Skapa ett renderingsmål som renderar till texturen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Renderingsparametrar för att skapa rendertexturen |
| targets | int | How many color output targets |
| bredd | int | Bredden på rendertexturen |
| höjd | int | Höjden på rendertexturen |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderWindow(RenderParameters parameters, WindowHandle handle) {#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-}
```
public abstract IRenderWindow createRenderWindow(RenderParameters parameters, WindowHandle handle)
```


Skapa ett renderingsmål som renderar till det inbyggda fönstret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Render parameters to create the render window |
| handle | [WindowHandle](../../com.aspose.threed/windowhandle) | The handle of the window to render |

**Returns:**
[IRenderWindow](../../com.aspose.threed/irenderwindow)
### createShaderProgram(ShaderSource shaderSource) {#createShaderProgram-com.aspose.threed.ShaderSource-}
```
public abstract ShaderProgram createShaderProgram(ShaderSource shaderSource)
```


Skapa ett [ShaderProgram](../../com.aspose.threed/shaderprogram)-objekt

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shaderSource | [ShaderSource](../../com.aspose.threed/shadersource) | The source code of the shader |

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram)
### createTextureUnit() {#createTextureUnit--}
```
public ITextureUnit createTextureUnit()
```


Skapa en 2D-texturenhet som kan nås av shader.

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createTextureUnit(TextureType textureType) {#createTextureUnit-com.aspose.threed.TextureType-}
```
public abstract ITextureUnit createTextureUnit(TextureType textureType)
```


Skapa en texturenhet som kan nås av shader.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textureType | [TextureType](../../com.aspose.threed/texturetype) | Type of the texture |

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createUniformBuffer(int size) {#createUniformBuffer-int-}
```
public abstract IBuffer createUniformBuffer(int size)
```


Skapa en ny uniform buffer på GPU-sidan med förallokerad storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| storlek | int | The size of the uniform buffer |

**Returns:**
[IBuffer](../../com.aspose.threed/ibuffer) - The uniform buffer instance
### createVertexBuffer(VertexDeclaration declaration) {#createVertexBuffer-com.aspose.threed.VertexDeclaration-}
```
public abstract IVertexBuffer createVertexBuffer(VertexDeclaration declaration)
```


Skapa en [IVertexBuffer](../../com.aspose.threed/ivertexbuffer)-instans för att lagra polygonens vertexinformation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
[IVertexBuffer](../../com.aspose.threed/ivertexbuffer)
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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

