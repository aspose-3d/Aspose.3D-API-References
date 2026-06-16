---
title: "RenderFactory"
second_title: "Référence d'API Aspose.3D pour Node.js via Java"
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
| createRenderTexture(parameters, targets, width, height) | Créer une cible de rendu qui rend sur la texture |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| paramètres | RenderParameters | Paramètres de rendu pour créer la texture de rendu |
| cibles | Nombre | Combien de cibles de sortie couleur |
| largeur | Nombre | La largeur de la texture de rendu |
| height | Nombre | La hauteur de la texture de rendu |

 **Result:**
IRenderTexture


---


### createRenderTexture{#createRenderTexture}

| Nom | Description |
| --- | --- |
| createRenderTexture(parameters, width, height) | Créer une cible de rendu contenant 1 cible qui rend sur la texture |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| paramètres | RenderParameters | Paramètres de rendu pour créer la texture de rendu |
| largeur | Nombre | La largeur de la texture de rendu |
| height | Nombre | La hauteur de la texture de rendu |

 **Result:**
IRenderTexture


---


### createDescriptorSet{#createDescriptorSet}

| Nom | Description |
| --- | --- |
| createDescriptorSet(shader) | Créer l'ensemble de descripteurs pour le programme shader spécifié. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| shader | ShaderProgram | Le programme shader |

 **Result:**
IDescriptorSet


---


### createCubeRenderTexture{#createCubeRenderTexture}

| Nom | Description |
| --- | --- |
| createCubeRenderTexture(parameters, width, height) | Créer une cible de rendu contenant 1 texture cube |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| paramètres | RenderParameters | Paramètres de rendu pour créer la texture de rendu |
| largeur | Nombre | La largeur de la texture de rendu |
| height | Nombre | La hauteur de la texture de rendu |

 **Result:**
IRenderTexture


---


### createRenderWindow{#createRenderWindow}

| Nom | Description |
| --- | --- |
| createRenderWindow(parameters, handle) | Créer une cible de rendu qui rend sur la fenêtre native. |

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
| déclaration | VertexDeclaration | null |

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
| createTextureUnit(textureType) | Créez une unité de texture qui peut être accédée par le shader. |

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
| createTextureUnit() | Créez une unité de texture 2D qui peut être accédée par le shader. |

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
| createPipeline(shader, renderState, vertexDeclaration, drawOperation) | Créez un pipeline graphique préconfiguré avec un shader/état de rendu/déclaration de sommet préconfigurés et des opérations de dessin. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| shader | ShaderProgram | Le shader utilisé lors du rendu |
| renderState | RenderState | L'état de rendu utilisé lors du rendu |
| vertexDeclaration | VertexDeclaration | La déclaration de sommet des données de sommet d'entrée |
| drawOperation | DrawOperation | DrawOperation |

 **Result:**
IPipeline


---


### createUniformBuffer{#createUniformBuffer}

| Nom | Description |
| --- | --- |
| createUniformBuffer(size) | Créez un nouveau tampon uniforme du côté GPU avec une taille pré-allouée. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| size | Nombre | La taille du tampon uniforme |

 **Result:**
IBuffer


---



