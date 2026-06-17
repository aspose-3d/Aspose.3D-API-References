---
title: "RenderFactory"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/renderfactory/
---
## RenderFactory class

RenderFactory skapar alla resurser som representeras i renderingspipeline.  @hideconstructor


## Metoder

### createRenderTexture{#createRenderTexture}

| Namn | Beskrivning |
| --- | --- |
| createRenderTexture(parameters, targets, width, height) | Skapa ett renderingsmål som renderar till texturen |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| parametrar | RenderParameters | Renderingsparametrar för att skapa rendertexturen |
| mål | Nummer | Hur många färgoutputmål |
| bredd | Nummer | Rendertexturens bredd |
| height | Nummer | Rendertexturens höjd |

 **Result:**
IRenderTexture


---


### createRenderTexture{#createRenderTexture}

| Namn | Beskrivning |
| --- | --- |
| createRenderTexture(parameters, width, height) | Skapa ett renderingsmål som innehåller 1 mål och renderar till texturen |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| parametrar | RenderParameters | Renderingsparametrar för att skapa rendertexturen |
| bredd | Nummer | Rendertexturens bredd |
| height | Nummer | Rendertexturens höjd |

 **Result:**
IRenderTexture


---


### createDescriptorSet{#createDescriptorSet}

| Namn | Beskrivning |
| --- | --- |
| createDescriptorSet(shader) | Skapa descriptor-setet för specificerat shaderprogram. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| shader | ShaderProgram | Shaderprogrammet |

 **Result:**
IDescriptorSet


---


### createCubeRenderTexture{#createCubeRenderTexture}

| Namn | Beskrivning |
| --- | --- |
| createCubeRenderTexture(parameters, width, height) | Skapa ett renderingsmål som innehåller 1 kubtextur |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| parametrar | RenderParameters | Renderingsparametrar för att skapa rendertexturen |
| bredd | Nummer | Rendertexturens bredd |
| height | Nummer | Rendertexturens höjd |

 **Result:**
IRenderTexture


---


### createRenderWindow{#createRenderWindow}

| Namn | Beskrivning |
| --- | --- |
| createRenderWindow(parameters, handle) | Skapa ett renderingsmål som renderar till det inbyggda fönstret. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| parametrar | RenderParameters | Renderingsparametrar för att skapa renderfönstret |
| handtag | WindowHandle | Handtaget för fönstret som ska renderas |

 **Result:**
IRenderWindow


---


### createVertexBuffer{#createVertexBuffer}

| Namn | Beskrivning |
| --- | --- |
| createVertexBuffer(declaration) | Skapa en com.aspose.threed.IVertexBuffer-instans för att lagra polygonens vertexinformation. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |

 **Result:**
IVertexBuffer


---


### createIndexBuffer{#createIndexBuffer}

| Namn | Beskrivning |
| --- | --- |
| createIndexBuffer() | Skapa en com.aspose.threed.IIndexBuffer-instans för att lagra polygonens ytinformation. |

 **Result:**
IIndexBuffer


---


### createTextureUnit{#createTextureUnit}

| Namn | Beskrivning |
| --- | --- |
| createTextureUnit(textureType) | Skapa en texture-enhet som kan nås av shader. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| textureType | TextureType | TextureType |

 **Result:**
ITextureUnit


---


### createTextureUnit{#createTextureUnit}

| Namn | Beskrivning |
| --- | --- |
| createTextureUnit() | Skapa en 2D texture-enhet som kan nås av shader. |

 **Result:**
ITextureUnit


---


### createShaderProgram{#createShaderProgram}

| Namn | Beskrivning |
| --- | --- |
| createShaderProgram(shaderSource) | Skapa ett ShaderProgram-objekt |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| shaderSource | ShaderSource | Källkoden för shadern |

 **Result:**
ShaderProgram


---


### createPipeline{#createPipeline}

| Namn | Beskrivning |
| --- | --- |
| createPipeline(shader, renderState, vertexDeclaration, drawOperation) | Skapa en förkonfigurerad grafikpipeline med förkonfigurerad shader/render state/vertex declaration och draw operations. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| shader | ShaderProgram | Shadern som används i rendering |
| renderState | RenderState | Render state som används i rendering |
| vertexDeclaration | VertexDeclaration | Vertex declaration för indata vertexdata |
| drawOperation | DrawOperation | DrawOperation |

 **Result:**
IPipeline


---


### createUniformBuffer{#createUniformBuffer}

| Namn | Beskrivning |
| --- | --- |
| createUniformBuffer(size) | Skapa en ny uniform buffer på GPU-sidan med förallokerad storlek. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| storlek | Nummer | Storleken på uniform buffer |

 **Result:**
IBuffer


---



