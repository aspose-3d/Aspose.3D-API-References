---
title: RenderFactory
second_title: Aspose.3D für Node.js via Java API-Referenz
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
| createRenderTexture(parameters, targets, width, height) | Erstellt ein Renderziel, das auf die Textur rendert |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Parameter | RenderParameters | Renderparameter zum Erstellen der Render-Textur |
| Ziele | Number | Wie viele Farbausgabeziele |
| Breite | Number | Die Breite der Render-Textur |
| height | Number | Die Höhe der Render-Textur |

 **Result:**
IRenderTexture


---


### createRenderTexture{#createRenderTexture}

| Name | Beschreibung |
| --- | --- |
| createRenderTexture(parameters, width, height) | Erstellt ein Renderziel, das 1 Ziel enthält, das auf die Textur rendert |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Parameter | RenderParameters | Renderparameter zum Erstellen der Render-Textur |
| Breite | Number | Die Breite der Render-Textur |
| height | Number | Die Höhe der Render-Textur |

 **Result:**
IRenderTexture


---


### createDescriptorSet{#createDescriptorSet}

| Name | Beschreibung |
| --- | --- |
| createDescriptorSet(shader) | Erstellt das Deskriptorset für das angegebene Shader-Programm. |

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
| createCubeRenderTexture(parameters, width, height) | Erstellt ein Renderziel, das 1 Würfeltextur enthält |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Parameter | RenderParameters | Renderparameter zum Erstellen der Render-Textur |
| Breite | Number | Die Breite der Render-Textur |
| height | Number | Die Höhe der Render-Textur |

 **Result:**
IRenderTexture


---


### createRenderWindow{#createRenderWindow}

| Name | Beschreibung |
| --- | --- |
| createRenderWindow(parameters, handle) | Erstellt ein Renderziel, das auf das native Fenster rendert. |

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
| createTextureUnit(textureType) | Erstellt eine Textureinheit, auf die vom Shader zugegriffen werden kann. |

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
| createTextureUnit() | Erstellt eine 2D-Textureinheit, auf die vom Shader zugegriffen werden kann. |

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
| createPipeline(shader, renderState, vertexDeclaration, drawOperation) | Erstellt eine vorkonfigurierte Grafikpipeline mit vorkonfiguriertem Shader-/Render-Status/Vertex-Deklaration und Zeichenoperationen. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Shader | ShaderProgram | Der im Rendering verwendete Shader |
| renderState | RenderState | Der im Rendering verwendete Render-Status |
| vertexDeclaration | VertexDeclaration | Die Vertex-Deklaration der Eingabe-Vertex-Daten |
| drawOperation | DrawOperation | DrawOperation |

 **Result:**
IPipeline


---


### createUniformBuffer{#createUniformBuffer}

| Name | Beschreibung |
| --- | --- |
| createUniformBuffer(size) | Erstellt einen neuen Uniform-Puffer auf der GPU-Seite mit vorab zugewiesener Größe. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Größe | Number | Die Größe des Uniform-Puffers |

 **Result:**
IBuffer


---



