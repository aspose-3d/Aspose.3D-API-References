---
title: "RenderFactory"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/renderfactory/
---
## RenderFactory class

RenderFactory maakt alle bronnen die worden weergegeven in de renderpipeline.  @hideconstructor


## Methoden

### createRenderTexture{#createRenderTexture}

| Naam | Beschrijving |
| --- | --- |
| createRenderTexture(parameters, targets, width, height) | Maak een renderdoel dat naar de texture rendert |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| parameters | RenderParameters | Renderparameters om de rendertexture te maken |
| targets | Number | Hoeveel kleuruitvoertargets |
| breedte | Number | De breedte van de rendertexture |
| height | Number | De hoogte van de rendertexture |

 **Result:**
IRenderTexture


---


### createRenderTexture{#createRenderTexture}

| Naam | Beschrijving |
| --- | --- |
| createRenderTexture(parameters, width, height) | Maak een renderdoel dat 1 target bevat en naar de texture rendert |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| parameters | RenderParameters | Renderparameters om de rendertexture te maken |
| breedte | Number | De breedte van de rendertexture |
| height | Number | De hoogte van de rendertexture |

 **Result:**
IRenderTexture


---


### createDescriptorSet{#createDescriptorSet}

| Naam | Beschrijving |
| --- | --- |
| createDescriptorSet(shader) | Maak de descriptorset voor het opgegeven shaderprogramma. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| shader | ShaderProgram | Het shaderprogramma |

 **Result:**
IDescriptorSet


---


### createCubeRenderTexture{#createCubeRenderTexture}

| Naam | Beschrijving |
| --- | --- |
| createCubeRenderTexture(parameters, width, height) | Maak een renderdoel dat 1 cube texture bevat |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| parameters | RenderParameters | Renderparameters om de rendertexture te maken |
| breedte | Number | De breedte van de rendertexture |
| height | Number | De hoogte van de rendertexture |

 **Result:**
IRenderTexture


---


### createRenderWindow{#createRenderWindow}

| Naam | Beschrijving |
| --- | --- |
| createRenderWindow(parameters, handle) | Maak een renderdoel dat naar het native venster rendert. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| parameters | RenderParameters | Renderparameters om het rendervenster te maken |
| handle | WindowHandle | De handle van het venster om te renderen |

 **Result:**
IRenderWindow


---


### createVertexBuffer{#createVertexBuffer}

| Naam | Beschrijving |
| --- | --- |
| createVertexBuffer(declaration) | Maak een com.aspose.threed.IVertexBuffer instance om de vertexinformatie van de polygoon op te slaan. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |

 **Result:**
IVertexBuffer


---


### createIndexBuffer{#createIndexBuffer}

| Naam | Beschrijving |
| --- | --- |
| createIndexBuffer() | Maak een com.aspose.threed.IIndexBuffer instance om de gezichtsinformatie van de polygoon op te slaan. |

 **Result:**
IIndexBuffer


---


### createTextureUnit{#createTextureUnit}

| Naam | Beschrijving |
| --- | --- |
| createTextureUnit(textureType) | Maak een texture unit die door de shader kan worden benaderd. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| textureType | TextureType | TextureType |

 **Result:**
ITextureUnit


---


### createTextureUnit{#createTextureUnit}

| Naam | Beschrijving |
| --- | --- |
| createTextureUnit() | Maak een 2D texture unit die door de shader kan worden benaderd. |

 **Result:**
ITextureUnit


---


### createShaderProgram{#createShaderProgram}

| Naam | Beschrijving |
| --- | --- |
| createShaderProgram(shaderSource) | Maak een ShaderProgram-object |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| shaderSource | ShaderSource | De broncode van de shader |

 **Result:**
ShaderProgram


---


### createPipeline{#createPipeline}

| Naam | Beschrijving |
| --- | --- |
| createPipeline(shader, renderState, vertexDeclaration, drawOperation) | Maak een vooraf geconfigureerde graphics-pijplijn met vooraf geconfigureerde shader/render state/vertex declaration en draw operations. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| shader | ShaderProgram | De shader die wordt gebruikt bij het renderen. |
| renderState | RenderState | De render state die wordt gebruikt bij het renderen. |
| vertexDeclaration | VertexDeclaration | De vertex declaration van de invoer vertexgegevens. |
| drawOperation | DrawOperation | DrawOperation |

 **Result:**
IPipeline


---


### createUniformBuffer{#createUniformBuffer}

| Naam | Beschrijving |
| --- | --- |
| createUniformBuffer(size) | Maak een nieuwe uniforme buffer aan de GPU‑kant met vooraf toegewezen grootte. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| grootte | Number | De grootte van de uniforme buffer |

 **Result:**
IBuffer


---



