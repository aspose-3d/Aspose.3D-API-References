---
title: RenderFactory
second_title: Referencia de API de Aspose.3D para Java
description: RenderFactory crea todos los recursos que se representan en la canalización de renderizado.
type: docs
weight: 148
url: /es/java/com.aspose.threed/renderfactory/
---

**Inheritance:**
java.lang.Object
```
public abstract class RenderFactory
```

RenderFactory crea todos los recursos que se representan en la canalización de renderizado.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [RenderFactory()](#RenderFactory--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [createCubeRenderTexture(RenderParameters parameters, int width, int height)](#createCubeRenderTexture-com.aspose.threed.RenderParameters-int-int-) | Crear un objetivo de renderizado que contiene 1 textura de cubo |
| [createDescriptorSet(ShaderProgram shader)](#createDescriptorSet-com.aspose.threed.ShaderProgram-) | Crear el conjunto de descriptores para el programa de sombreado especificado. |
| [createIndexBuffer()](#createIndexBuffer--) | Crear una instancia de [IIndexBuffer](../../com.aspose.threed/iindexbuffer) para almacenar la información de las caras del polígono. |
| [createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)](#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-) | Crear una canalización gráfica preconfigurada con sombreado/estado de renderizado/declaración de vértices preconfigurados y operaciones de dibujo. |
| [createRenderTexture(RenderParameters parameters, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-) | Crear un objetivo de renderizado que contiene 1 objetivo que renderiza a la textura |
| [createRenderTexture(RenderParameters parameters, int targets, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-) | Crear un objetivo de renderizado que renderiza a la textura |
| [createRenderWindow(RenderParameters parameters, WindowHandle handle)](#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-) | Crear un objetivo de renderizado que renderiza a la ventana nativa. |
| [createShaderProgram(ShaderSource shaderSource)](#createShaderProgram-com.aspose.threed.ShaderSource-) | Crear un objeto [ShaderProgram](../../com.aspose.threed/shaderprogram) |
| [createTextureUnit()](#createTextureUnit--) | Crear una unidad de textura 2D que pueda ser accedida por el shader. |
| [createTextureUnit(TextureType textureType)](#createTextureUnit-com.aspose.threed.TextureType-) | Crear una unidad de textura que pueda ser accedida por el shader. |
| [createUniformBuffer(int size)](#createUniformBuffer-int-) | Crear un nuevo búfer uniforme en el lado de la GPU con tamaño preasignado. |
| [createVertexBuffer(VertexDeclaration declaration)](#createVertexBuffer-com.aspose.threed.VertexDeclaration-) | Crear una instancia de [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) para almacenar la información de los vértices del polígono. |
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


Crear un objetivo de renderizado que contiene 1 textura de cubo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Parámetros de renderizado para crear la textura de renderizado |
| ancho | int | El ancho de la textura de renderizado |
| altura | int | La altura de la textura de renderizado |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createDescriptorSet(ShaderProgram shader) {#createDescriptorSet-com.aspose.threed.ShaderProgram-}
```
public abstract IDescriptorSet createDescriptorSet(ShaderProgram shader)
```


Crear el conjunto de descriptores para el programa de sombreado especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | El programa de shader. |

**Returns:**
[IDescriptorSet](../../com.aspose.threed/idescriptorset) - A new descriptor set instance
### createIndexBuffer() {#createIndexBuffer--}
```
public abstract IIndexBuffer createIndexBuffer()
```


Crear una instancia de [IIndexBuffer](../../com.aspose.threed/iindexbuffer) para almacenar la información de las caras del polígono.

**Returns:**
[IIndexBuffer](../../com.aspose.threed/iindexbuffer)
### createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation) {#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-}
```
public abstract IPipeline createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)
```


Crear una canalización gráfica preconfigurada con sombreado/estado de renderizado/declaración de vértices preconfigurados y operaciones de dibujo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | El shader usado en el renderizado |
| renderState | [RenderState](../../com.aspose.threed/renderstate) | El estado de renderizado usado en el renderizado |
| vertexDeclaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | La declaración de vértices de los datos de vértices de entrada |
| drawOperation | [DrawOperation](../../com.aspose.threed/drawoperation) | Operación de dibujo |

**Returns:**
[IPipeline](../../com.aspose.threed/ipipeline) - A new pipeline instance
### createRenderTexture(RenderParameters parameters, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int width, int height)
```


Crear un objetivo de renderizado que contiene 1 objetivo que renderiza a la textura

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Parámetros de renderizado para crear la textura de renderizado |
| ancho | int | El ancho de la textura de renderizado |
| altura | int | La altura de la textura de renderizado |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderTexture(RenderParameters parameters, int targets, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int targets, int width, int height)
```


Crear un objetivo de renderizado que renderiza a la textura

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Parámetros de renderizado para crear la textura de renderizado |
| objetivos | int | Cuántos objetivos de salida de color |
| ancho | int | El ancho de la textura de renderizado |
| altura | int | La altura de la textura de renderizado |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderWindow(RenderParameters parameters, WindowHandle handle) {#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-}
```
public abstract IRenderWindow createRenderWindow(RenderParameters parameters, WindowHandle handle)
```


Crear un objetivo de renderizado que renderiza a la ventana nativa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Parámetros de renderizado para crear la ventana de renderizado |
| handle | [WindowHandle](../../com.aspose.threed/windowhandle) | El identificador de la ventana a renderizar |

**Returns:**
[IRenderWindow](../../com.aspose.threed/irenderwindow)
### createShaderProgram(ShaderSource shaderSource) {#createShaderProgram-com.aspose.threed.ShaderSource-}
```
public abstract ShaderProgram createShaderProgram(ShaderSource shaderSource)
```


Crear un objeto [ShaderProgram](../../com.aspose.threed/shaderprogram)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shaderSource | [ShaderSource](../../com.aspose.threed/shadersource) | El código fuente del shader |

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram)
### createTextureUnit() {#createTextureUnit--}
```
public ITextureUnit createTextureUnit()
```


Crear una unidad de textura 2D que pueda ser accedida por el shader.

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createTextureUnit(TextureType textureType) {#createTextureUnit-com.aspose.threed.TextureType-}
```
public abstract ITextureUnit createTextureUnit(TextureType textureType)
```


Crear una unidad de textura que pueda ser accedida por el shader.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| textureType | [TextureType](../../com.aspose.threed/texturetype) | Tipo de la textura |

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createUniformBuffer(int size) {#createUniformBuffer-int-}
```
public abstract IBuffer createUniformBuffer(int size)
```


Crear un nuevo búfer uniforme en el lado de la GPU con tamaño preasignado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tamaño | int | El tamaño del búfer uniforme |

**Returns:**
[IBuffer](../../com.aspose.threed/ibuffer) - The uniform buffer instance
### createVertexBuffer(VertexDeclaration declaration) {#createVertexBuffer-com.aspose.threed.VertexDeclaration-}
```
public abstract IVertexBuffer createVertexBuffer(VertexDeclaration declaration)
```


Crear una instancia de [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) para almacenar la información de los vértices del polígono.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
[IVertexBuffer](../../com.aspose.threed/ivertexbuffer)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

