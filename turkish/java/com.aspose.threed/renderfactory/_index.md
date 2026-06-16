---
title: "RenderFactory"
second_title: "Aspose.3D for Java API Referansı"
description: "RenderFactory, render hattında temsil edilen tüm kaynakları oluşturur."
type: docs
weight: 148
url: /tr/java/com.aspose.threed/renderfactory/
---

**Inheritance:**
java.lang.Object
```
public abstract class RenderFactory
```

RenderFactory, render hattında temsil edilen tüm kaynakları oluşturur.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RenderFactory()](#RenderFactory--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createCubeRenderTexture(RenderParameters parameters, int width, int height)](#createCubeRenderTexture-com.aspose.threed.RenderParameters-int-int-) | 1 küp doku içeren bir render hedefi oluştur. |
| [createDescriptorSet(ShaderProgram shader)](#createDescriptorSet-com.aspose.threed.ShaderProgram-) | Belirtilen shader programı için tanımlayıcı kümesini oluştur. |
| [createIndexBuffer()](#createIndexBuffer--) | Poligonun yüz bilgilerini depolamak için bir [IIndexBuffer](../../com.aspose.threed/iindexbuffer) örneği oluştur. |
| [createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)](#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-) | Önceden yapılandırılmış shader/render durumu/vertex bildirimi ve çizim işlemleriyle bir önceden yapılandırılmış grafik boru hattı oluştur. |
| [createRenderTexture(RenderParameters parameters, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-) | Dokuya render yapan 1 hedef içeren bir render hedefi oluştur. |
| [createRenderTexture(RenderParameters parameters, int targets, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-) | Dokuya render yapan bir render hedefi oluştur. |
| [createRenderWindow(RenderParameters parameters, WindowHandle handle)](#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-) | Yerel pencereye render yapan bir render hedefi oluştur. |
| [createShaderProgram(ShaderSource shaderSource)](#createShaderProgram-com.aspose.threed.ShaderSource-) | Bir [ShaderProgram](../../com.aspose.threed/shaderprogram) nesnesi oluştur. |
| [createTextureUnit()](#createTextureUnit--) | Shader tarafından erişilebilen bir 2D doku birimi oluştur. |
| [createTextureUnit(TextureType textureType)](#createTextureUnit-com.aspose.threed.TextureType-) | Shader tarafından erişilebilen bir doku birimi oluştur. |
| [createUniformBuffer(int size)](#createUniformBuffer-int-) | Önceden ayrılmış boyutla GPU tarafında yeni bir uniform tampon oluştur. |
| [createVertexBuffer(VertexDeclaration declaration)](#createVertexBuffer-com.aspose.threed.VertexDeclaration-) | Poligonun vertex bilgilerini depolamak için bir [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) örneği oluştur. |
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


1 küp doku içeren bir render hedefi oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Render dokusunu oluşturmak için render parametreleri |
| genişlik | int | Render dokusunun genişliği |
| yükseklik | int | Render dokusunun yüksekliği |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createDescriptorSet(ShaderProgram shader) {#createDescriptorSet-com.aspose.threed.ShaderProgram-}
```
public abstract IDescriptorSet createDescriptorSet(ShaderProgram shader)
```


Belirtilen shader programı için tanımlayıcı kümesini oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Shader programı. |

**Returns:**
[IDescriptorSet](../../com.aspose.threed/idescriptorset) - A new descriptor set instance
### createIndexBuffer() {#createIndexBuffer--}
```
public abstract IIndexBuffer createIndexBuffer()
```


Poligonun yüz bilgilerini depolamak için bir [IIndexBuffer](../../com.aspose.threed/iindexbuffer) örneği oluştur.

**Returns:**
[IIndexBuffer](../../com.aspose.threed/iindexbuffer)
### createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation) {#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-}
```
public abstract IPipeline createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)
```


Önceden yapılandırılmış shader/render durumu/vertex bildirimi ve çizim işlemleriyle bir önceden yapılandırılmış grafik boru hattı oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | Render işlemi sırasında kullanılan shader |
| renderState | [RenderState](../../com.aspose.threed/renderstate) | Render işlemi sırasında kullanılan render durumu |
| vertexDeclaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | Giriş vertex verisinin vertex bildirimi |
| drawOperation | [DrawOperation](../../com.aspose.threed/drawoperation) | Çizim işlemi |

**Returns:**
[IPipeline](../../com.aspose.threed/ipipeline) - A new pipeline instance
### createRenderTexture(RenderParameters parameters, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int width, int height)
```


Dokuya render yapan 1 hedef içeren bir render hedefi oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Render dokusunu oluşturmak için render parametreleri |
| genişlik | int | Render dokusunun genişliği |
| yükseklik | int | Render dokusunun yüksekliği |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderTexture(RenderParameters parameters, int targets, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int targets, int width, int height)
```


Dokuya render yapan bir render hedefi oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Render dokusunu oluşturmak için render parametreleri |
| hedefler | int | Kaç renk çıkış hedefi |
| genişlik | int | Render dokusunun genişliği |
| yükseklik | int | Render dokusunun yüksekliği |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderWindow(RenderParameters parameters, WindowHandle handle) {#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-}
```
public abstract IRenderWindow createRenderWindow(RenderParameters parameters, WindowHandle handle)
```


Yerel pencereye render yapan bir render hedefi oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Render penceresini oluşturmak için render parametreleri |
| handle | [WindowHandle](../../com.aspose.threed/windowhandle) | Render edilecek pencerenin tutamağı |

**Returns:**
[IRenderWindow](../../com.aspose.threed/irenderwindow)
### createShaderProgram(ShaderSource shaderSource) {#createShaderProgram-com.aspose.threed.ShaderSource-}
```
public abstract ShaderProgram createShaderProgram(ShaderSource shaderSource)
```


Bir [ShaderProgram](../../com.aspose.threed/shaderprogram) nesnesi oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shaderSource | [ShaderSource](../../com.aspose.threed/shadersource) | Shader'ın kaynak kodu |

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram)
### createTextureUnit() {#createTextureUnit--}
```
public ITextureUnit createTextureUnit()
```


Shader tarafından erişilebilen bir 2D doku birimi oluştur.

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createTextureUnit(TextureType textureType) {#createTextureUnit-com.aspose.threed.TextureType-}
```
public abstract ITextureUnit createTextureUnit(TextureType textureType)
```


Shader tarafından erişilebilen bir doku birimi oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| textureType | [TextureType](../../com.aspose.threed/texturetype) | Doku tipi |

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createUniformBuffer(int size) {#createUniformBuffer-int-}
```
public abstract IBuffer createUniformBuffer(int size)
```


Önceden ayrılmış boyutla GPU tarafında yeni bir uniform tampon oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| boyut | int | Uniform tamponun boyutu |

**Returns:**
[IBuffer](../../com.aspose.threed/ibuffer) - The uniform buffer instance
### createVertexBuffer(VertexDeclaration declaration) {#createVertexBuffer-com.aspose.threed.VertexDeclaration-}
```
public abstract IVertexBuffer createVertexBuffer(VertexDeclaration declaration)
```


Poligonun vertex bilgilerini depolamak için bir [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) örneği oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
[IVertexBuffer](../../com.aspose.threed/ivertexbuffer)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

