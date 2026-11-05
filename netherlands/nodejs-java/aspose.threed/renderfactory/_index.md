---
title: "RenderFactory"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/renderfactory/
---
## RenderFactory class

RenderFactory maakt alle bronnen aan die worden weergegeven in de renderpipeline.  @hideconstructor


## Methoden

### createRenderTexture{#createRenderTexture}

| Naam | Beschrijving |
| --- | --- |
| createRenderTexture(parameters, targets, width, height) | Maak een renderdoel dat naar de textuur rendert |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| parameters | RenderParameters | Renderparameters om de rendertextuur te maken |
| targets | Nummer | Hoeveel kleuruitvoertargets |
| width | Nummer | De breedte van de rendertextuur |
| height | Nummer | De hoogte van de rendertextuur |

 **Result:**
IRenderTexture


---


### createRenderTexture{#createRenderTexture}

| Naam | Beschrijving |
| --- | --- |
| createRenderTexture(parameters, width, height) | Maak een renderdoel dat 1 target bevat en naar de textuur rendert |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| parameters | RenderParameters | Renderparameters om de rendertextuur te maken |
| width | Nummer | De breedte van de rendertextuur |
| height | Nummer | De hoogte van de rendertextuur |

 **Result:**
IRenderTexture


---


### createDescriptorSet{#createDescriptorSet}

| Naam | Beschrijving |
| --- | --- |
| createDescriptorSet(shader) | Maak de descriptorset voor het opgegeven shader‑programma. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| shader | ShaderProgram | Het shader‑programma |

 **Result:**
IDescriptorSet


---


### createCubeRenderTexture{#createCubeRenderTexture}

| Naam | Beschrijving |
| --- | --- |
| createCubeRenderTexture(parameters, width, height) | Maak een renderdoel dat 1 cube‑textuur bevat |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| parameters | RenderParameters | Renderparameters om de rendertextuur te maken |
| width | Nummer | De breedte van de rendertextuur |
| height | Nummer | De hoogte van de rendertextuur |

 **Result:**
IRenderTexture


---


### createRenderWindow{#createRenderWindow}

| Naam | Beschrijving |
| --- | --- |
| createRenderWindow(parameters, handle) | Maak een renderdoel dat rendert naar het native venster. |

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
| createVertexBuffer(declaration) | Maak een com.aspose.threed.IVertexBuffer-instantie om de vertex-informatie van het polygon op te slaan. |

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
| createIndexBuffer() | Maak een com.aspose.threed.IIndexBuffer-instantie om de vlak-informatie van het polygon op te slaan. |

 **Result:**
IIndexBuffer


---


### createTextureUnit{#createTextureUnit}

| Naam | Beschrijving |
| --- | --- |
| createTextureUnit(textureType) | Maak een texture-eenheid die toegankelijk is voor de shader. |

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
| createTextureUnit() | Maak een 2D-texture-eenheid die toegankelijk is voor de shader. |

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
| createPipeline(shader, renderState, vertexDeclaration, drawOperation) | Maak een vooraf geconfigureerde graphics-pipeline met vooraf geconfigureerde shader/render-state/vertex-declaratie en teken-operaties. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| shader | ShaderProgram | De shader die wordt gebruikt bij het renderen |
| renderState | RenderState | De renderstatus die wordt gebruikt bij het renderen |
| vertexDeclaration | VertexDeclaration | De vertexdeclaratie van invoer-vertexgegevens |
| drawOperation | DrawOperation | DrawOperation |

 **Result:**
IPipeline


---


### createUniformBuffer{#createUniformBuffer}

| Naam | Beschrijving |
| --- | --- |
| createUniformBuffer(size) | Maak een nieuwe uniforme buffer aan de GPU-kant met vooraf toegewezen grootte. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| grootte | Nummer | De grootte van de uniforme buffer |

 **Result:**
IBuffer


---



