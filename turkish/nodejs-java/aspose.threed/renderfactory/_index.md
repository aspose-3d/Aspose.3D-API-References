---
title: "RenderFactory"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/renderfactory/
---
## RenderFactory class

RenderFactory, renderleme hattında temsil edilen tüm kaynakları oluşturur.  @hideconstructor


## Yöntemler

### createRenderTexture{#createRenderTexture}

| Ad | Açıklama |
| --- | --- |
| createRenderTexture(parameters, targets, width, height) | Dokuya render yapan bir render hedefi oluştur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| parametreler | RenderParameters | Render dokusunu oluşturmak için render parametreleri |
| hedefler | Number | Kaç renk çıkış hedefi |
| genişlik | Number | Render dokusunun genişliği |
| height | Number | Render dokusunun yüksekliği |

 **Result:**
IRenderTexture


---


### createRenderTexture{#createRenderTexture}

| Ad | Açıklama |
| --- | --- |
| createRenderTexture(parameters, width, height) | Dokuya render yapan 1 hedef içeren bir render hedefi oluştur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| parametreler | RenderParameters | Render dokusunu oluşturmak için render parametreleri |
| genişlik | Number | Render dokusunun genişliği |
| height | Number | Render dokusunun yüksekliği |

 **Result:**
IRenderTexture


---


### createDescriptorSet{#createDescriptorSet}

| Ad | Açıklama |
| --- | --- |
| createDescriptorSet(shader) | Belirtilen shader programı için tanımlayıcı seti oluştur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| shader | ShaderProgram | Shader programı |

 **Result:**
IDescriptorSet


---


### createCubeRenderTexture{#createCubeRenderTexture}

| Ad | Açıklama |
| --- | --- |
| createCubeRenderTexture(parameters, width, height) | 1 küp dokusu içeren bir render hedefi oluştur |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| parametreler | RenderParameters | Render dokusunu oluşturmak için render parametreleri |
| genişlik | Number | Render dokusunun genişliği |
| height | Number | Render dokusunun yüksekliği |

 **Result:**
IRenderTexture


---


### createRenderWindow{#createRenderWindow}

| Ad | Açıklama |
| --- | --- |
| createRenderWindow(parameters, handle) | Yerel pencereye render yapan bir render hedefi oluştur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| parametreler | RenderParameters | Render penceresini oluşturmak için render parametreleri |
| handle | WindowHandle | Render edilecek pencerenin handle'ı |

 **Result:**
IRenderWindow


---


### createVertexBuffer{#createVertexBuffer}

| Ad | Açıklama |
| --- | --- |
| createVertexBuffer(declaration) | Poligonun köşe bilgilerini depolamak için bir com.aspose.threed.IVertexBuffer örneği oluşturun. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |

 **Result:**
IVertexBuffer


---


### createIndexBuffer{#createIndexBuffer}

| Ad | Açıklama |
| --- | --- |
| createIndexBuffer() | Poligonun yüzey bilgilerini depolamak için bir com.aspose.threed.IIndexBuffer örneği oluşturun. |

 **Result:**
IIndexBuffer


---


### createTextureUnit{#createTextureUnit}

| Ad | Açıklama |
| --- | --- |
| createTextureUnit(textureType) | Shader tarafından erişilebilecek bir doku birimi oluşturun. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| textureType | TextureType | TextureType |

 **Result:**
ITextureUnit


---


### createTextureUnit{#createTextureUnit}

| Ad | Açıklama |
| --- | --- |
| createTextureUnit() | Shader tarafından erişilebilecek 2D bir doku birimi oluşturun. |

 **Result:**
ITextureUnit


---


### createShaderProgram{#createShaderProgram}

| Ad | Açıklama |
| --- | --- |
| createShaderProgram(shaderSource) | Bir ShaderProgram nesnesi oluşturun |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| shaderSource | ShaderSource | Shader'ın kaynak kodu |

 **Result:**
ShaderProgram


---


### createPipeline{#createPipeline}

| Ad | Açıklama |
| --- | --- |
| createPipeline(shader, renderState, vertexDeclaration, drawOperation) | Önceden yapılandırılmış shader, render durumu, köşe bildirimi ve çizim işlemleriyle bir önceden yapılandırılmış grafik boru hattı oluşturun. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| shader | ShaderProgram | Render işlemi sırasında kullanılan shader |
| renderState | RenderState | Render işlemi sırasında kullanılan render durumu |
| vertexDeclaration | VertexDeclaration | Giriş köşe verisinin köşe bildirimi |
| drawOperation | DrawOperation | DrawOperation |

 **Result:**
IPipeline


---


### createUniformBuffer{#createUniformBuffer}

| Ad | Açıklama |
| --- | --- |
| createUniformBuffer(size) | GPU tarafında önceden ayrılmış boyutla yeni bir uniform tampon oluşturun. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| boyut | Number | Uniform tamponun boyutu |

 **Result:**
IBuffer


---



