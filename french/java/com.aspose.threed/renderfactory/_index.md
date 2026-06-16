---
title: "RenderFactory"
second_title: "Référence d'API Aspose.3D pour Java"
description: "RenderFactory crée toutes les ressources représentées dans le pipeline de rendu."
type: docs
weight: 148
url: /fr/java/com.aspose.threed/renderfactory/
---

**Inheritance:**
java.lang.Object
```
public abstract class RenderFactory
```

RenderFactory crée toutes les ressources représentées dans le pipeline de rendu.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RenderFactory()](#RenderFactory--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createCubeRenderTexture(RenderParameters parameters, int width, int height)](#createCubeRenderTexture-com.aspose.threed.RenderParameters-int-int-) | Créez une cible de rendu contenant 1 texture cube |
| [createDescriptorSet(ShaderProgram shader)](#createDescriptorSet-com.aspose.threed.ShaderProgram-) | Créez l'ensemble de descripteurs pour le programme de shader spécifié. |
| [createIndexBuffer()](#createIndexBuffer--) | Créez une instance de [IIndexBuffer](../../com.aspose.threed/iindexbuffer) pour stocker les informations des faces du polygone. |
| [createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)](#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-) | Créez un pipeline graphique préconfiguré avec un shader/état de rendu/déclaration de vertex préconfigurés et des opérations de dessin. |
| [createRenderTexture(RenderParameters parameters, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-) | Créez une cible de rendu contenant 1 cible qui rend sur la texture |
| [createRenderTexture(RenderParameters parameters, int targets, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-) | Créez une cible de rendu qui rend sur la texture |
| [createRenderWindow(RenderParameters parameters, WindowHandle handle)](#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-) | Créez une cible de rendu qui rend sur la fenêtre native. |
| [createShaderProgram(ShaderSource shaderSource)](#createShaderProgram-com.aspose.threed.ShaderSource-) | Créez un objet [ShaderProgram](../../com.aspose.threed/shaderprogram) |
| [createTextureUnit()](#createTextureUnit--) | Créez une unité de texture 2D accessible par le shader. |
| [createTextureUnit(TextureType textureType)](#createTextureUnit-com.aspose.threed.TextureType-) | Créez une unité de texture accessible par le shader. |
| [createUniformBuffer(int size)](#createUniformBuffer-int-) | Créez un nouveau tampon uniforme côté GPU avec une taille préallouée. |
| [createVertexBuffer(VertexDeclaration declaration)](#createVertexBuffer-com.aspose.threed.VertexDeclaration-) | Créez une instance de [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) pour stocker les informations des vertex du polygone. |
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


Créez une cible de rendu contenant 1 texture cube

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Paramètres de rendu pour créer la texture de rendu |
| largeur | int | La largeur de la texture de rendu |
| hauteur | int | La hauteur de la texture de rendu |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createDescriptorSet(ShaderProgram shader) {#createDescriptorSet-com.aspose.threed.ShaderProgram-}
```
public abstract IDescriptorSet createDescriptorSet(ShaderProgram shader)
```


Créez l'ensemble de descripteurs pour le programme de shader spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Le programme de shader |

**Returns:**
[IDescriptorSet](../../com.aspose.threed/idescriptorset) - A new descriptor set instance
### createIndexBuffer() {#createIndexBuffer--}
```
public abstract IIndexBuffer createIndexBuffer()
```


Créez une instance de [IIndexBuffer](../../com.aspose.threed/iindexbuffer) pour stocker les informations des faces du polygone.

**Returns:**
[IIndexBuffer](../../com.aspose.threed/iindexbuffer)
### createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation) {#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-}
```
public abstract IPipeline createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)
```


Créez un pipeline graphique préconfiguré avec un shader/état de rendu/déclaration de vertex préconfigurés et des opérations de dessin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Le shader utilisé lors du rendu |
| renderState | [RenderState](../../com.aspose.threed/renderstate) | L'état de rendu utilisé lors du rendu |
| vertexDeclaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | La déclaration de vertex des données de vertex d'entrée |
| drawOperation | [DrawOperation](../../com.aspose.threed/drawoperation) | Opération de dessin |

**Returns:**
[IPipeline](../../com.aspose.threed/ipipeline) - A new pipeline instance
### createRenderTexture(RenderParameters parameters, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int width, int height)
```


Créez une cible de rendu contenant 1 cible qui rend sur la texture

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Paramètres de rendu pour créer la texture de rendu |
| largeur | int | La largeur de la texture de rendu |
| hauteur | int | La hauteur de la texture de rendu |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderTexture(RenderParameters parameters, int targets, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int targets, int width, int height)
```


Créez une cible de rendu qui rend sur la texture

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Paramètres de rendu pour créer la texture de rendu |
| cibles | int | Combien de cibles de sortie couleur |
| largeur | int | La largeur de la texture de rendu |
| hauteur | int | La hauteur de la texture de rendu |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderWindow(RenderParameters parameters, WindowHandle handle) {#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-}
```
public abstract IRenderWindow createRenderWindow(RenderParameters parameters, WindowHandle handle)
```


Créez une cible de rendu qui rend sur la fenêtre native.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Paramètres de rendu pour créer la fenêtre de rendu |
| handle | [WindowHandle](../../com.aspose.threed/windowhandle) | Le handle de la fenêtre à rendre |

**Returns:**
[IRenderWindow](../../com.aspose.threed/irenderwindow)
### createShaderProgram(ShaderSource shaderSource) {#createShaderProgram-com.aspose.threed.ShaderSource-}
```
public abstract ShaderProgram createShaderProgram(ShaderSource shaderSource)
```


Créez un objet [ShaderProgram](../../com.aspose.threed/shaderprogram)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| shaderSource | [ShaderSource](../../com.aspose.threed/shadersource) | Le code source du shader |

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram)
### createTextureUnit() {#createTextureUnit--}
```
public ITextureUnit createTextureUnit()
```


Créez une unité de texture 2D accessible par le shader.

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createTextureUnit(TextureType textureType) {#createTextureUnit-com.aspose.threed.TextureType-}
```
public abstract ITextureUnit createTextureUnit(TextureType textureType)
```


Créez une unité de texture accessible par le shader.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| textureType | [TextureType](../../com.aspose.threed/texturetype) | Type de la texture |

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createUniformBuffer(int size) {#createUniformBuffer-int-}
```
public abstract IBuffer createUniformBuffer(int size)
```


Créez un nouveau tampon uniforme côté GPU avec une taille préallouée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| taille | int | La taille du tampon uniforme |

**Returns:**
[IBuffer](../../com.aspose.threed/ibuffer) - The uniform buffer instance
### createVertexBuffer(VertexDeclaration declaration) {#createVertexBuffer-com.aspose.threed.VertexDeclaration-}
```
public abstract IVertexBuffer createVertexBuffer(VertexDeclaration declaration)
```


Créez une instance de [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) pour stocker les informations des vertex du polygone.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
[IVertexBuffer](../../com.aspose.threed/ivertexbuffer)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

