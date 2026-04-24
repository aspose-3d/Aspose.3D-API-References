---
title: RenderFactory
second_title: Aspose.3D for Java API Reference
description: RenderFactory crea tutte le risorse rappresentate nella pipeline di rendering.
type: docs
weight: 148
url: /it/java/com.aspose.threed/renderfactory/
---

**Inheritance:**
java.lang.Object
```
public abstract class RenderFactory
```

RenderFactory crea tutte le risorse rappresentate nella pipeline di rendering.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RenderFactory()](#RenderFactory--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createCubeRenderTexture(RenderParameters parameters, int width, int height)](#createCubeRenderTexture-com.aspose.threed.RenderParameters-int-int-) | Crea un render target che contiene 1 texture cubica |
| [createDescriptorSet(ShaderProgram shader)](#createDescriptorSet-com.aspose.threed.ShaderProgram-) | Crea il set di descrittori per lo shader program specificato. |
| [createIndexBuffer()](#createIndexBuffer--) | Crea un'istanza di [IIndexBuffer](../../com.aspose.threed/iindexbuffer) per memorizzare le informazioni delle facce del poligono. |
| [createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)](#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-) | Crea una pipeline grafica preconfigurata con shader/stato di rendering/dichiarazione dei vertici preconfigurati e operazioni di disegno. |
| [createRenderTexture(RenderParameters parameters, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-) | Crea un render target che contiene 1 target che renderizza sulla texture |
| [createRenderTexture(RenderParameters parameters, int targets, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-) | Crea un render target che renderizza sulla texture |
| [createRenderWindow(RenderParameters parameters, WindowHandle handle)](#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-) | Crea un render target che renderizza sulla finestra nativa. |
| [createShaderProgram(ShaderSource shaderSource)](#createShaderProgram-com.aspose.threed.ShaderSource-) | Crea un oggetto [ShaderProgram](../../com.aspose.threed/shaderprogram) |
| [createTextureUnit()](#createTextureUnit--) | Crea un'unità di texture 2D accessibile dallo shader. |
| [createTextureUnit(TextureType textureType)](#createTextureUnit-com.aspose.threed.TextureType-) | Crea un'unità di texture accessibile dallo shader. |
| [createUniformBuffer(int size)](#createUniformBuffer-int-) | Crea un nuovo buffer uniforme sul lato GPU con dimensione preallocata. |
| [createVertexBuffer(VertexDeclaration declaration)](#createVertexBuffer-com.aspose.threed.VertexDeclaration-) | Crea un'istanza di [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) per memorizzare le informazioni dei vertici del poligono. |
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


Crea un render target che contiene 1 texture cubica

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Parametri di rendering per creare la texture di rendering |
| larghezza | int | La larghezza della texture di rendering |
| altezza | int | L'altezza della texture di rendering |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createDescriptorSet(ShaderProgram shader) {#createDescriptorSet-com.aspose.threed.ShaderProgram-}
```
public abstract IDescriptorSet createDescriptorSet(ShaderProgram shader)
```


Crea il set di descrittori per lo shader program specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Il programma shader |

**Returns:**
[IDescriptorSet](../../com.aspose.threed/idescriptorset) - A new descriptor set instance
### createIndexBuffer() {#createIndexBuffer--}
```
public abstract IIndexBuffer createIndexBuffer()
```


Crea un'istanza di [IIndexBuffer](../../com.aspose.threed/iindexbuffer) per memorizzare le informazioni delle facce del poligono.

**Returns:**
[IIndexBuffer](../../com.aspose.threed/iindexbuffer)
### createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation) {#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-}
```
public abstract IPipeline createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)
```


Crea una pipeline grafica preconfigurata con shader/stato di rendering/dichiarazione dei vertici preconfigurati e operazioni di disegno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Lo shader utilizzato nel rendering |
| renderState | [RenderState](../../com.aspose.threed/renderstate) | Lo stato di rendering utilizzato nel rendering |
| vertexDeclaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | La dichiarazione dei vertici dei dati di input dei vertici |
| drawOperation | [DrawOperation](../../com.aspose.threed/drawoperation) | Operazione di disegno |

**Returns:**
[IPipeline](../../com.aspose.threed/ipipeline) - A new pipeline instance
### createRenderTexture(RenderParameters parameters, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int width, int height)
```


Crea un render target che contiene 1 target che renderizza sulla texture

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Parametri di rendering per creare la texture di rendering |
| larghezza | int | La larghezza della texture di rendering |
| altezza | int | L'altezza della texture di rendering |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderTexture(RenderParameters parameters, int targets, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int targets, int width, int height)
```


Crea un render target che renderizza sulla texture

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Parametri di rendering per creare la texture di rendering |
| obiettivi | int | Quanti target di output colore |
| larghezza | int | La larghezza della texture di rendering |
| altezza | int | L'altezza della texture di rendering |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderWindow(RenderParameters parameters, WindowHandle handle) {#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-}
```
public abstract IRenderWindow createRenderWindow(RenderParameters parameters, WindowHandle handle)
```


Crea un render target che renderizza sulla finestra nativa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Parametri di rendering per creare la finestra di rendering |
| handle | [WindowHandle](../../com.aspose.threed/windowhandle) | Il handle della finestra da renderizzare |

**Returns:**
[IRenderWindow](../../com.aspose.threed/irenderwindow)
### createShaderProgram(ShaderSource shaderSource) {#createShaderProgram-com.aspose.threed.ShaderSource-}
```
public abstract ShaderProgram createShaderProgram(ShaderSource shaderSource)
```


Crea un oggetto [ShaderProgram](../../com.aspose.threed/shaderprogram)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shaderSource | [ShaderSource](../../com.aspose.threed/shadersource) | Il codice sorgente dello shader |

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram)
### createTextureUnit() {#createTextureUnit--}
```
public ITextureUnit createTextureUnit()
```


Crea un'unità di texture 2D accessibile dallo shader.

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createTextureUnit(TextureType textureType) {#createTextureUnit-com.aspose.threed.TextureType-}
```
public abstract ITextureUnit createTextureUnit(TextureType textureType)
```


Crea un'unità di texture accessibile dallo shader.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textureType | [TextureType](../../com.aspose.threed/texturetype) | Tipo della texture |

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createUniformBuffer(int size) {#createUniformBuffer-int-}
```
public abstract IBuffer createUniformBuffer(int size)
```


Crea un nuovo buffer uniforme sul lato GPU con dimensione preallocata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dimensione | int | La dimensione del buffer uniforme |

**Returns:**
[IBuffer](../../com.aspose.threed/ibuffer) - The uniform buffer instance
### createVertexBuffer(VertexDeclaration declaration) {#createVertexBuffer-com.aspose.threed.VertexDeclaration-}
```
public abstract IVertexBuffer createVertexBuffer(VertexDeclaration declaration)
```


Crea un'istanza di [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) per memorizzare le informazioni dei vertici del poligono.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
[IVertexBuffer](../../com.aspose.threed/ivertexbuffer)
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

