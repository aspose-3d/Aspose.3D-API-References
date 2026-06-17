---
title: "RenderFactory"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/renderfactory/
---
## RenderFactory class

RenderFactory crea todos los recursos que se representan en la canalización de renderizado.  @hideconstructor


## Métodos

### createRenderTexture{#createRenderTexture}

| Nombre | Descripción |
| --- | --- |
| createRenderTexture(parameters, targets, width, height) | Crear un objetivo de renderizado que renderiza a la textura |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| parámetros | RenderParameters | Parámetros de renderizado para crear la textura de renderizado |
| objetivos | Número | Cuántos objetivos de salida de color |
| ancho | Número | El ancho de la textura de renderizado |
| height | Número | La altura de la textura de renderizado |

 **Result:**
IRenderTexture


---


### createRenderTexture{#createRenderTexture}

| Nombre | Descripción |
| --- | --- |
| createRenderTexture(parameters, width, height) | Crear un objetivo de renderizado que contiene 1 objetivo y renderiza a la textura |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| parámetros | RenderParameters | Parámetros de renderizado para crear la textura de renderizado |
| ancho | Número | El ancho de la textura de renderizado |
| height | Número | La altura de la textura de renderizado |

 **Result:**
IRenderTexture


---


### createDescriptorSet{#createDescriptorSet}

| Nombre | Descripción |
| --- | --- |
| createDescriptorSet(shader) | Crear el conjunto de descriptores para el programa de shader especificado. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| shader | ShaderProgram | El programa de shader |

 **Result:**
IDescriptorSet


---


### createCubeRenderTexture{#createCubeRenderTexture}

| Nombre | Descripción |
| --- | --- |
| createCubeRenderTexture(parameters, width, height) | Crear un objetivo de renderizado que contiene 1 textura cúbica |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| parámetros | RenderParameters | Parámetros de renderizado para crear la textura de renderizado |
| ancho | Número | El ancho de la textura de renderizado |
| height | Número | La altura de la textura de renderizado |

 **Result:**
IRenderTexture


---


### createRenderWindow{#createRenderWindow}

| Nombre | Descripción |
| --- | --- |
| createRenderWindow(parameters, handle) | Crear un objetivo de renderizado que renderiza en la ventana nativa. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| parámetros | RenderParameters | Parámetros de renderizado para crear la ventana de renderizado |
| handle | WindowHandle | El handle de la ventana a renderizar |

 **Result:**
IRenderWindow


---


### createVertexBuffer{#createVertexBuffer}

| Nombre | Descripción |
| --- | --- |
| createVertexBuffer(declaration) | Crea una instancia de com.aspose.threed.IVertexBuffer para almacenar la información de los vértices del polígono. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| declaración | VertexDeclaration | null |

 **Result:**
IVertexBuffer


---


### createIndexBuffer{#createIndexBuffer}

| Nombre | Descripción |
| --- | --- |
| createIndexBuffer() | Crea una instancia de com.aspose.threed.IIndexBuffer para almacenar la información de las caras del polígono. |

 **Result:**
IIndexBuffer


---


### createTextureUnit{#createTextureUnit}

| Nombre | Descripción |
| --- | --- |
| createTextureUnit(textureType) | Crea una unidad de textura que pueda ser accedida por el shader. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| textureType | TextureType | TextureType |

 **Result:**
ITextureUnit


---


### createTextureUnit{#createTextureUnit}

| Nombre | Descripción |
| --- | --- |
| createTextureUnit() | Crea una unidad de textura 2D que pueda ser accedida por el shader. |

 **Result:**
ITextureUnit


---


### createShaderProgram{#createShaderProgram}

| Nombre | Descripción |
| --- | --- |
| createShaderProgram(shaderSource) | Crea un objeto ShaderProgram |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| shaderSource | ShaderSource | El código fuente del shader |

 **Result:**
ShaderProgram


---


### createPipeline{#createPipeline}

| Nombre | Descripción |
| --- | --- |
| createPipeline(shader, renderState, vertexDeclaration, drawOperation) | Crea una canalización gráfica preconfigurada con shader/renderState/vertexDeclaration y operaciones de dibujo preconfiguradas. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| shader | ShaderProgram | El shader usado en la renderización |
| renderState | RenderState | El estado de renderizado usado en la renderización |
| vertexDeclaration | VertexDeclaration | La declaración de vértices de los datos de vértices de entrada |
| drawOperation | DrawOperation | DrawOperation |

 **Result:**
IPipeline


---


### createUniformBuffer{#createUniformBuffer}

| Nombre | Descripción |
| --- | --- |
| createUniformBuffer(size) | Crear un nuevo búfer uniforme en el lado GPU con tamaño preasignado. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| tamaño | Número | El tamaño del búfer uniforme |

 **Result:**
IBuffer


---



