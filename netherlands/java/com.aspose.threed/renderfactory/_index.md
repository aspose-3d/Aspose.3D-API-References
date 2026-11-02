---
title: "RenderFactory"
second_title: "Aspose.3D voor Java API-referentie"
description: "RenderFactory maakt alle bronnen aan die worden weergegeven in de renderpipeline."
type: docs
weight: 148
url: /nl/java/com.aspose.threed/renderfactory/
---

**Inheritance:**
java.lang.Object
```
public abstract class RenderFactory
```

RenderFactory maakt alle bronnen aan die worden weergegeven in de renderpipeline.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [RenderFactory()](#RenderFactory--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createCubeRenderTexture(RenderParameters parameters, int width, int height)](#createCubeRenderTexture-com.aspose.threed.RenderParameters-int-int-) | Maak een renderdoel dat 1 kubus‑texture bevat |
| [createDescriptorSet(ShaderProgram shader)](#createDescriptorSet-com.aspose.threed.ShaderProgram-) | Maak de descriptor‑set voor het opgegeven shader‑programma. |
| [createIndexBuffer()](#createIndexBuffer--) | Maak een [IIndexBuffer](../../com.aspose.threed/iindexbuffer)‑instantie om de vlak‑informatie van polygonen op te slaan. |
| [createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)](#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-) | Maak een vooraf geconfigureerde grafische pijplijn met vooraf geconfigureerde shader/render‑status/vertex‑declaratie en teken‑operaties. |
| [createRenderTexture(RenderParameters parameters, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-) | Maak een renderdoel dat 1 doel bevat dat naar de texture rendert |
| [createRenderTexture(RenderParameters parameters, int targets, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-) | Maak een renderdoel dat naar de texture rendert |
| [createRenderWindow(RenderParameters parameters, WindowHandle handle)](#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-) | Maak een renderdoel dat naar het native venster rendert. |
| [createShaderProgram(ShaderSource shaderSource)](#createShaderProgram-com.aspose.threed.ShaderSource-) | Maak een [ShaderProgram](../../com.aspose.threed/shaderprogram)‑object |
| [createTextureUnit()](#createTextureUnit--) | Maak een 2D‑texture‑eenheid die door de shader benaderd kan worden. |
| [createTextureUnit(TextureType textureType)](#createTextureUnit-com.aspose.threed.TextureType-) | Maak een texture‑eenheid die door de shader benaderd kan worden. |
| [createUniformBuffer(int size)](#createUniformBuffer-int-) | Maak een nieuwe uniforme buffer aan de GPU‑kant met vooraf toegewezen grootte. |
| [createVertexBuffer(VertexDeclaration declaration)](#createVertexBuffer-com.aspose.threed.VertexDeclaration-) | Maak een [IVertexBuffer](../../com.aspose.threed/ivertexbuffer)‑instantie om de vertex‑informatie van polygonen op te slaan. |
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


Maak een renderdoel dat 1 kubus‑texture bevat

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Render‑parameters om de render‑texture te maken |
| breedte | int | De breedte van de render‑texture |
| hoogte | int | De hoogte van de render‑texture |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createDescriptorSet(ShaderProgram shader) {#createDescriptorSet-com.aspose.threed.ShaderProgram-}
```
public abstract IDescriptorSet createDescriptorSet(ShaderProgram shader)
```


Maak de descriptor‑set voor het opgegeven shader‑programma.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Het shaderprogramma |

**Returns:**
[IDescriptorSet](../../com.aspose.threed/idescriptorset) - A new descriptor set instance
### createIndexBuffer() {#createIndexBuffer--}
```
public abstract IIndexBuffer createIndexBuffer()
```


Maak een [IIndexBuffer](../../com.aspose.threed/iindexbuffer)‑instantie om de vlak‑informatie van polygonen op te slaan.

**Returns:**
[IIndexBuffer](../../com.aspose.threed/iindexbuffer)
### createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation) {#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-}
```
public abstract IPipeline createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)
```


Maak een vooraf geconfigureerde grafische pijplijn met vooraf geconfigureerde shader/render‑status/vertex‑declaratie en teken‑operaties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | De shader die bij het renderen wordt gebruikt |
| renderState | [RenderState](../../com.aspose.threed/renderstate) | De render‑status die bij het renderen wordt gebruikt |
| vertexDeclaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | De vertex‑declaratie van de invoer‑vertex‑gegevens |
| drawOperation | [DrawOperation](../../com.aspose.threed/drawoperation) | Tekenbewerking |

**Returns:**
[IPipeline](../../com.aspose.threed/ipipeline) - A new pipeline instance
### createRenderTexture(RenderParameters parameters, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int width, int height)
```


Maak een renderdoel dat 1 doel bevat dat naar de texture rendert

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Render‑parameters om de render‑texture te maken |
| breedte | int | De breedte van de render‑texture |
| hoogte | int | De hoogte van de render‑texture |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderTexture(RenderParameters parameters, int targets, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int targets, int width, int height)
```


Maak een renderdoel dat naar de texture rendert

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Render‑parameters om de render‑texture te maken |
| doelen | int | Hoeveel kleuruitvoerdoelen |
| breedte | int | De breedte van de render‑texture |
| hoogte | int | De hoogte van de render‑texture |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderWindow(RenderParameters parameters, WindowHandle handle) {#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-}
```
public abstract IRenderWindow createRenderWindow(RenderParameters parameters, WindowHandle handle)
```


Maak een renderdoel dat naar het native venster rendert.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Renderparameters om het rendervenster te maken. |
| handle | [WindowHandle](../../com.aspose.threed/windowhandle) | De handle van het venster om te renderen. |

**Returns:**
[IRenderWindow](../../com.aspose.threed/irenderwindow)
### createShaderProgram(ShaderSource shaderSource) {#createShaderProgram-com.aspose.threed.ShaderSource-}
```
public abstract ShaderProgram createShaderProgram(ShaderSource shaderSource)
```


Maak een [ShaderProgram](../../com.aspose.threed/shaderprogram)‑object

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shaderSource | [ShaderSource](../../com.aspose.threed/shadersource) | De broncode van de shader. |

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram)
### createTextureUnit() {#createTextureUnit--}
```
public ITextureUnit createTextureUnit()
```


Maak een 2D‑texture‑eenheid die door de shader benaderd kan worden.

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createTextureUnit(TextureType textureType) {#createTextureUnit-com.aspose.threed.TextureType-}
```
public abstract ITextureUnit createTextureUnit(TextureType textureType)
```


Maak een texture‑eenheid die door de shader benaderd kan worden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| textureType | [TextureType](../../com.aspose.threed/texturetype) | Type van de texture. |

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createUniformBuffer(int size) {#createUniformBuffer-int-}
```
public abstract IBuffer createUniformBuffer(int size)
```


Maak een nieuwe uniforme buffer aan de GPU‑kant met vooraf toegewezen grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| grootte | int | De grootte van de uniforme buffer. |

**Returns:**
[IBuffer](../../com.aspose.threed/ibuffer) - The uniform buffer instance
### createVertexBuffer(VertexDeclaration declaration) {#createVertexBuffer-com.aspose.threed.VertexDeclaration-}
```
public abstract IVertexBuffer createVertexBuffer(VertexDeclaration declaration)
```


Maak een [IVertexBuffer](../../com.aspose.threed/ivertexbuffer)‑instantie om de vertex‑informatie van polygonen op te slaan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
[IVertexBuffer](../../com.aspose.threed/ivertexbuffer)
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

