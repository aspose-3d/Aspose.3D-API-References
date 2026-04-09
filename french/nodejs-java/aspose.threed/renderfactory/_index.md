---
title: RenderFactory
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/renderfactory/
---
## RenderFactory class

RenderFactory crée toutes les ressources représentées dans le pipeline de rendu.  @hideconstructor


## Méthodes

### createRenderTexture{#createRenderTexture}

| Nom | Description |
| --- | --- |
| createRenderTexture(parameters, targets, width, height) | Créez une cible de rendu qui rend sur la texture |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| paramètres | RenderParameters | Paramètres de rendu pour créer la texture de rendu |
| cibles | Number | Combien de cibles de sortie couleur |
| largeur | Number | La largeur de la texture de rendu |
| hauteur | Number | La hauteur de la texture de rendu |

 **Result:**
IRenderTexture


---


### createRenderTexture{#createRenderTexture}

| Nom | Description |
| --- | --- |
| createRenderTexture(parameters, width, height) | Créez une cible de rendu contenant 1 cible qui rend sur la texture |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| paramètres | RenderParameters | Paramètres de rendu pour créer la texture de rendu |
| largeur | Number | La largeur de la texture de rendu |
| hauteur | Number | La hauteur de la texture de rendu |

 **Result:**
IRenderTexture


---


### createDescriptorSet{#createDescriptorSet}

| Nom | Description |
| --- | --- |
| createDescriptorSet(shader) | Créez l'ensemble de descripteurs pour le programme de shader spécifié. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| shader | ShaderProgram | Le programme de shader |

 **Result:**
IDescriptorSet


---


### createCubeRenderTexture{#createCubeRenderTexture}

| Nom | Description |
| --- | --- |
| createCubeRenderTexture(parameters, width, height) | Créez une cible de rendu contenant 1 texture cube |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| paramètres | RenderParameters | Paramètres de rendu pour créer la texture de rendu |
| largeur | Number | La largeur de la texture de rendu |
| hauteur | Number | La hauteur de la texture de rendu |

 **Result:**
IRenderTexture


---


### createRenderWindow{#createRenderWindow}

| Nom | Description |
| --- | --- |
| createRenderWindow(parameters, handle) | Créez une cible de rendu qui rend sur la fenêtre native. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| paramètres | RenderParameters | Paramètres de rendu pour créer la fenêtre de rendu |
| handle | WindowHandle | Le handle de la fenêtre à rendre |

 **Result:**
IRenderWindow


---


### createVertexBuffer{#createVertexBuffer}

| Nom | Description |
| --- | --- |
| createVertexBuffer(declaration) | Créez une instance com.aspose.threed.IVertexBuffer pour stocker les informations de sommet du polygone. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |

 **Result:**
IVertexBuffer


---


### createIndexBuffer{#createIndexBuffer}

| Nom | Description |
| --- | --- |
| createIndexBuffer() | Créez une instance com.aspose.threed.IIndexBuffer pour stocker les informations de face du polygone. |

 **Result:**
IIndexBuffer


---


### createTextureUnit{#createTextureUnit}

| Nom | Description |
| --- | --- |
| createTextureUnit(textureType) | Créez une unité de texture accessible par le shader. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| textureType | TextureType | TextureType |

 **Result:**
ITextureUnit


---


### createTextureUnit{#createTextureUnit}

| Nom | Description |
| --- | --- |
| createTextureUnit() | Créez une unité de texture 2D accessible par le shader. |

 **Result:**
ITextureUnit


---


### createShaderProgram{#createShaderProgram}

| Nom | Description |
| --- | --- |
| createShaderProgram(shaderSource) | Créez un objet ShaderProgram |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| shaderSource | ShaderSource | Le code source du shader |

 **Result:**
ShaderProgram


---


### createPipeline{#createPipeline}

| Nom | Description |
| --- | --- |
| createPipeline(shader, renderState, vertexDeclaration, drawOperation) | Créez un pipeline graphique préconfiguré avec un shader/état de rendu/déclaration de vertex préconfigurés et des opérations de dessin. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| shader | ShaderProgram | Le shader utilisé lors du rendu |
| renderState | RenderState | L'état de rendu utilisé lors du rendu |
| vertexDeclaration | VertexDeclaration | La déclaration de vertex des données de vertex d'entrée |
| drawOperation | DrawOperation | DrawOperation |

 **Result:**
IPipeline


---


### createUniformBuffer{#createUniformBuffer}

| Nom | Description |
| --- | --- |
| createUniformBuffer(size) | Créez un nouveau tampon uniforme côté GPU avec une taille préallouée. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| taille | Number | La taille du tampon uniforme |

 **Result:**
IBuffer


---



