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
| createRenderTexture(parameters, targets, width, height) | Dokuya render yapan bir render hedefi oluştur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| parameters | RenderParameters | Render dokusunu oluşturmak için render parametreleri |
| targets | Sayı | Kaç renk çıkış hedefi |
| width | Sayı | Render dokusunun genişliği |
| height | Sayı | Render dokusunun yüksekliği |

 **Result:**
IRenderTexture


---


### createRenderTexture{#createRenderTexture}

| Ad | Açıklama |
| --- | --- |
| createRenderTexture(parameters, width, height) | Dokuya render yapan 1 hedef içeren bir render hedefi oluştur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| parameters | RenderParameters | Render dokusunu oluşturmak için render parametreleri |
| width | Sayı | Render dokusunun genişliği |
| height | Sayı | Render dokusunun yüksekliği |

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
| createCubeRenderTexture(parameters, width, height) | 1 küp dokusu içeren bir render hedefi oluştur. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| parameters | RenderParameters | Render dokusunu oluşturmak için render parametreleri |
| width | Sayı | Render dokusunun genişliği |
| height | Sayı | Render dokusunun yüksekliği |

 **Result:**
IRenderTexture


---


### createRenderWindow{#createRenderWindow}

| Ad | Açıklama |
| --- | --- |
| createRenderWindow(parameters, handle) | Yerel pencereye render yapan bir render hedefi oluşturun. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| parameters | RenderParameters | Render penceresini oluşturmak için render parametreleri |
| tanıtıcı | WindowHandle | Render edilecek pencerenin tanıtıcısı |

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
| createTextureUnit(textureType) | Shader tarafından erişilebilen bir doku birimi oluşturun. |

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
| createTextureUnit() | Shader tarafından erişilebilen 2D bir doku birimi oluşturun. |

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
| createPipeline(shader, renderState, vertexDeclaration, drawOperation) | Önceden yapılandırılmış shader/render state/köşe bildirimi ve çizim işlemleriyle önceden yapılandırılmış bir grafik işlem hattı oluşturun. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| shader | ShaderProgram | Render işlemesinde kullanılan shader |
| renderState | RenderState | Render işlemi sırasında kullanılan render durumu |
| vertexDeclaration | VertexDeclaration | Girdi vertex verisinin vertex bildirimi |
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
| boyut | Sayı | Uniform tamponun boyutu |

 **Result:**
IBuffer


---



