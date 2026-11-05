---
title: "RenderFactory"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/renderfactory/
---
## RenderFactory class

RenderFactory erstellt alle Ressourcen, die in der Rendering-Pipeline dargestellt werden.  @hideconstructor


## Methoden

### createRenderTexture{#createRenderTexture}

| Name | Beschreibung |
| --- | --- |
| createRenderTexture(parameters, targets, width, height) | Erstellt ein Renderziel, das in die Textur rendert |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Parameter | RenderParameters | Renderparameter zum Erstellen der Render-Textur |
| Ziele | Zahl | Wie viele Farbausgabeziele |
| width | Zahl | Die Breite der Render-Textur |
| height | Zahl | Die Höhe der Render-Textur |

 **Result:**
IRenderTexture


---


### createRenderTexture{#createRenderTexture}

| Name | Beschreibung |
| --- | --- |
| createRenderTexture(parameters, width, height) | Erstelle ein Renderziel, das 1 Ziel enthält und in die Textur rendert. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Parameter | RenderParameters | Renderparameter zum Erstellen der Render-Textur |
| width | Zahl | Die Breite der Render-Textur |
| height | Zahl | Die Höhe der Render-Textur |

 **Result:**
IRenderTexture


---


### createDescriptorSet{#createDescriptorSet}

| Name | Beschreibung |
| --- | --- |
| createDescriptorSet(shader) | Erstelle das Deskriptorset für das angegebene Shader-Programm. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Shader | ShaderProgram | Das Shader-Programm |

 **Result:**
IDescriptorSet


---


### createCubeRenderTexture{#createCubeRenderTexture}

| Name | Beschreibung |
| --- | --- |
| createCubeRenderTexture(parameters, width, height) | Erstelle ein Renderziel, das 1 Cube-Textur enthält. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Parameter | RenderParameters | Renderparameter zum Erstellen der Render-Textur |
| width | Zahl | Die Breite der Render-Textur |
| height | Zahl | Die Höhe der Render-Textur |

 **Result:**
IRenderTexture


---


### createRenderWindow{#createRenderWindow}

| Name | Beschreibung |
| --- | --- |
| createRenderWindow(parameters, handle) | Erstelle ein Renderziel, das in das native Fenster rendert. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Parameter | RenderParameters | Renderparameter zum Erstellen des Renderfensters |
| Handle | WindowHandle | Der Handle des zu rendernden Fensters |

 **Result:**
IRenderWindow


---


### createVertexBuffer{#createVertexBuffer}

| Name | Beschreibung |
| --- | --- |
| createVertexBuffer(declaration) | Erstelle eine com.aspose.threed.IVertexBuffer-Instanz, um die Scheitelpunktinformationen des Polygons zu speichern. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |

 **Result:**
IVertexBuffer


---


### createIndexBuffer{#createIndexBuffer}

| Name | Beschreibung |
| --- | --- |
| createIndexBuffer() | Erstelle eine com.aspose.threed.IIndexBuffer-Instanz, um die Flächeninformationen des Polygons zu speichern. |

 **Result:**
IIndexBuffer


---


### createTextureUnit{#createTextureUnit}

| Name | Beschreibung |
| --- | --- |
| createTextureUnit(textureType) | Erstelle eine Textureinheit, die vom Shader aus zugänglich ist. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| textureType | TextureType | TextureType |

 **Result:**
ITextureUnit


---


### createTextureUnit{#createTextureUnit}

| Name | Beschreibung |
| --- | --- |
| createTextureUnit() | Erstelle eine 2D-Textureinheit, die vom Shader aus zugänglich ist. |

 **Result:**
ITextureUnit


---


### createShaderProgram{#createShaderProgram}

| Name | Beschreibung |
| --- | --- |
| createShaderProgram(shaderSource) | Erstelle ein ShaderProgram-Objekt |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| shaderSource | ShaderSource | Der Quellcode des Shaders |

 **Result:**
ShaderProgram


---


### createPipeline{#createPipeline}

| Name | Beschreibung |
| --- | --- |
| createPipeline(shader, renderState, vertexDeclaration, drawOperation) | Erstelle eine vorkonfigurierte Grafikpipeline mit vorkonfiguriertem Shader/Renderzustand/Vertex-Deklaration und Zeichenoperationen. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Shader | ShaderProgram | Der im Rendering verwendete Shader |
| renderState | RenderState | Der im Rendering verwendete Renderzustand |
| vertexDeclaration | VertexDeclaration | Die Vertex-Deklaration der Eingabe-Vertex-Daten |
| drawOperation | DrawOperation | DrawOperation |

 **Result:**
IPipeline


---


### createUniformBuffer{#createUniformBuffer}

| Name | Beschreibung |
| --- | --- |
| createUniformBuffer(size) | Erstelle einen neuen Uniform-Puffer auf der GPU-Seite mit vorab zugewiesener Größe. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Größe | Zahl | Die Größe des Uniform-Puffers |

 **Result:**
IBuffer


---



