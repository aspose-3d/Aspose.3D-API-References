---
title: "RenderFactory"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/renderfactory/
---
## RenderFactory class

RenderFactory crea tutte le risorse rappresentate nella pipeline di rendering.  @hideconstructor


## Metodi

### createRenderTexture{#createRenderTexture}

| Nome | Descrizione |
| --- | --- |
| createRenderTexture(parameters, targets, width, height) | Crea un render target che rende nella texture |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| parameters | RenderParameters | Parametri di rendering per creare la texture di rendering |
| targets | Numero | Quanti target di output colore |
| width | Numero | La larghezza della texture di rendering |
| height | Numero | L'altezza della texture di rendering |

 **Result:**
IRenderTexture


---


### createRenderTexture{#createRenderTexture}

| Nome | Descrizione |
| --- | --- |
| createRenderTexture(parameters, width, height) | Crea un render target che contiene 1 target e rende nella texture |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| parameters | RenderParameters | Parametri di rendering per creare la texture di rendering |
| width | Numero | La larghezza della texture di rendering |
| height | Numero | L'altezza della texture di rendering |

 **Result:**
IRenderTexture


---


### createDescriptorSet{#createDescriptorSet}

| Nome | Descrizione |
| --- | --- |
| createDescriptorSet(shader) | Crea il set di descrittori per il programma shader specificato. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| shader | ShaderProgram | Il programma shader |

 **Result:**
IDescriptorSet


---


### createCubeRenderTexture{#createCubeRenderTexture}

| Nome | Descrizione |
| --- | --- |
| createCubeRenderTexture(parameters, width, height) | Crea un render target che contiene 1 texture cubica |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| parameters | RenderParameters | Parametri di rendering per creare la texture di rendering |
| width | Numero | La larghezza della texture di rendering |
| height | Numero | L'altezza della texture di rendering |

 **Result:**
IRenderTexture


---


### createRenderWindow{#createRenderWindow}

| Nome | Descrizione |
| --- | --- |
| createRenderWindow(parameters, handle) | Crea un target di rendering che rende nella finestra nativa. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| parameters | RenderParameters | Parametri di rendering per creare la finestra di rendering |
| handle | WindowHandle | Il handle della finestra da renderizzare |

 **Result:**
IRenderWindow


---


### createVertexBuffer{#createVertexBuffer}

| Nome | Descrizione |
| --- | --- |
| createVertexBuffer(declaration) | Crea un'istanza di com.aspose.threed.IVertexBuffer per memorizzare le informazioni dei vertici del poligono. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| dichiarazione | VertexDeclaration | null |

 **Result:**
IVertexBuffer


---


### createIndexBuffer{#createIndexBuffer}

| Nome | Descrizione |
| --- | --- |
| createIndexBuffer() | Crea un'istanza di com.aspose.threed.IIndexBuffer per memorizzare le informazioni delle facce del poligono. |

 **Result:**
IIndexBuffer


---


### createTextureUnit{#createTextureUnit}

| Nome | Descrizione |
| --- | --- |
| createTextureUnit(textureType) | Crea un'unità di texture che può essere accessibile dallo shader. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| textureType | TextureType | TextureType |

 **Result:**
ITextureUnit


---


### createTextureUnit{#createTextureUnit}

| Nome | Descrizione |
| --- | --- |
| createTextureUnit() | Crea un'unità di texture 2D che può essere accessibile dallo shader. |

 **Result:**
ITextureUnit


---


### createShaderProgram{#createShaderProgram}

| Nome | Descrizione |
| --- | --- |
| createShaderProgram(shaderSource) | Crea un oggetto ShaderProgram |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| shaderSource | ShaderSource | Il codice sorgente dello shader |

 **Result:**
ShaderProgram


---


### createPipeline{#createPipeline}

| Nome | Descrizione |
| --- | --- |
| createPipeline(shader, renderState, vertexDeclaration, drawOperation) | Crea una pipeline grafica preconfigurata con shader, stato di rendering, dichiarazione di vertici e operazioni di disegno preconfigurati. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| shader | ShaderProgram | Lo shader usato nel rendering |
| renderState | RenderState | Lo stato di rendering usato nella resa |
| vertexDeclaration | VertexDeclaration | La dichiarazione del vertice dei dati di input |
| drawOperation | DrawOperation | DrawOperation |

 **Result:**
IPipeline


---


### createUniformBuffer{#createUniformBuffer}

| Nome | Descrizione |
| --- | --- |
| createUniformBuffer(size) | Crea un nuovo buffer uniforme sul lato GPU con dimensione preallocata. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| dimensione | Numero | La dimensione del buffer uniforme |

 **Result:**
IBuffer


---



