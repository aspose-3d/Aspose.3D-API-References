---
title: "RenderState"
second_title: "Référence d'API Aspose.3D pour Node.js via Java"
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/renderstate/
---
## RenderState class

État de rendu pour la construction du pipeline  Les modifications apportées à l'état de rendu n'affecteront pas les instances de pipeline créées.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Constructeur de RenderState |

 **Result:**



---


### getBlend{#getBlend}

| Nom | Description |
| --- | --- |
| getBlend() | Active ou désactive le mélange des fragments. |

 **Result:**



---


### setBlend{#setBlend}

| Nom | Description |
| --- | --- |
| setBlend(value) | Active ou désactive le mélange des fragments. |

 **Result:**



---


### getBlendColor{#getBlendColor}

| Nom | Description |
| --- | --- |
| getBlendColor() | Obtient ou définit la couleur de mélange utilisée dans BlendFactor.CONSTANT_COLOR |

 **Result:**



---


### setBlendColor{#setBlendColor}

| Nom | Description |
| --- | --- |
| setBlendColor(value) | Obtient ou définit la couleur de mélange utilisée dans BlendFactor.CONSTANT_COLOR |

 **Result:**



---


### getSourceBlendFactor{#getSourceBlendFactor}

| Nom | Description |
| --- | --- |
| getSourceBlendFactor() | Obtient ou définit comment la couleur est mélangée. La valeur de la propriété est une constante entière BlendFactor. |

 **Result:**



---


### setSourceBlendFactor{#setSourceBlendFactor}

| Nom | Description |
| --- | --- |
| setSourceBlendFactor(value) | Obtient ou définit comment la couleur est mélangée. La valeur de la propriété est une constante entière BlendFactor. |

 **Result:**



---


### getDestinationBlendFactor{#getDestinationBlendFactor}

| Nom | Description |
| --- | --- |
| getDestinationBlendFactor() | Obtient ou définit comment la couleur est mélangée. La valeur de la propriété est une constante entière BlendFactor. |

 **Result:**



---


### setDestinationBlendFactor{#setDestinationBlendFactor}

| Nom | Description |
| --- | --- |
| setDestinationBlendFactor(value) | Obtient ou définit comment la couleur est mélangée. La valeur de la propriété est une constante entière BlendFactor. |

 **Result:**



---


### getCullFace{#getCullFace}

| Nom | Description |
| --- | --- |
| getCullFace() | Active ou désactive le cull face |

 **Result:**



---


### setCullFace{#setCullFace}

| Nom | Description |
| --- | --- |
| setCullFace(value) | Active ou désactive le cull face |

 **Result:**



---


### getCullFaceMode{#getCullFaceMode}

| Nom | Description |
| --- | --- |
| getCullFaceMode() | Obtient ou définit quelle face sera éliminée. La valeur de la propriété est la constante entière CullFaceMode. |

 **Result:**



---


### setCullFaceMode{#setCullFaceMode}

| Nom | Description |
| --- | --- |
| setCullFaceMode(value) | Obtient ou définit quelle face sera éliminée. La valeur de la propriété est la constante entière CullFaceMode. |

 **Result:**



---


### getFrontFace{#getFrontFace}

| Nom | Description |
| --- | --- |
| getFrontFace() | Obtient ou définit quel ordre correspond à la face avant. La valeur de la propriété est la constante entière FrontFace. |

 **Result:**



---


### setFrontFace{#setFrontFace}

| Nom | Description |
| --- | --- |
| setFrontFace(value) | Obtient ou définit quel ordre correspond à la face avant. La valeur de la propriété est la constante entière FrontFace. |

 **Result:**



---


### getDepthTest{#getDepthTest}

| Nom | Description |
| --- | --- |
| getDepthTest() | Active ou désactive le test de profondeur. |

 **Result:**



---


### setDepthTest{#setDepthTest}

| Nom | Description |
| --- | --- |
| setDepthTest(value) | Active ou désactive le test de profondeur. |

 **Result:**



---


### getDepthMask{#getDepthMask}

| Nom | Description |
| --- | --- |
| getDepthMask() | Active ou désactive l'écriture de profondeur. |

 **Result:**



---


### setDepthMask{#setDepthMask}

| Nom | Description |
| --- | --- |
| setDepthMask(value) | Active ou désactive l'écriture de profondeur. |

 **Result:**



---


### getDepthFunction{#getDepthFunction}

| Nom | Description |
| --- | --- |
| getDepthFunction() | Obtient ou définit la fonction de comparaison utilisée dans le test de profondeur. La valeur de la propriété est la constante entière CompareFunction. |

 **Result:**



---


### setDepthFunction{#setDepthFunction}

| Nom | Description |
| --- | --- |
| setDepthFunction(value) | Obtient ou définit la fonction de comparaison utilisée dans le test de profondeur. La valeur de la propriété est la constante entière CompareFunction. |

 **Result:**



---


### getStencilTest{#getStencilTest}

| Nom | Description |
| --- | --- |
| getStencilTest() | Active ou désactive le test de pochoir. |

 **Result:**



---


### setStencilTest{#setStencilTest}

| Nom | Description |
| --- | --- |
| setStencilTest(value) | Active ou désactive le test de pochoir. |

 **Result:**



---


### getStencilReference{#getStencilReference}

| Nom | Description |
| --- | --- |
| getStencilReference() | Obtient ou définit la valeur de référence pour le test de pochoir. |

 **Result:**



---


### setStencilReference{#setStencilReference}

| Nom | Description |
| --- | --- |
| setStencilReference(value) | Obtient ou définit la valeur de référence pour le test de pochoir. |

 **Result:**



---


### getStencilMask{#getStencilMask}

| Nom | Description |
| --- | --- |
| getStencilMask() | Obtient ou définit le masque qui est combiné en AND avec la référence et la valeur de pochoir stockée lorsque le test est terminé. |

 **Result:**



---


### getStencilFrontFace{#getStencilFrontFace}

| Nom | Description |
| --- | --- |
| getStencilFrontFace() | Obtient l'état du pochoir pour la face avant. |

 **Result:**



---


### getStencilBackFace{#getStencilBackFace}

| Nom | Description |
| --- | --- |
| getStencilBackFace() | Obtient l'état du stencil pour la face arrière. |

 **Result:**



---


### getScissorTest{#getScissorTest}

| Nom | Description |
| --- | --- |
| getScissorTest() | Activer ou désactiver le test de ciseaux |

 **Result:**



---


### setScissorTest{#setScissorTest}

| Nom | Description |
| --- | --- |
| setScissorTest(value) | Activer ou désactiver le test de ciseaux |

 **Result:**



---


### getPolygonMode{#getPolygonMode}

| Nom | Description |
| --- | --- |
| getPolygonMode() | Obtient ou définit le mode de rendu du polygone. La valeur de la propriété est la constante entière PolygonMode. |

 **Result:**



---


### setPolygonMode{#setPolygonMode}

| Nom | Description |
| --- | --- |
| setPolygonMode(value) | Obtient ou définit le mode de rendu du polygone. La valeur de la propriété est la constante entière PolygonMode. |

 **Result:**



---


### equals{#equals}

| Nom | Description |
| --- | --- |
| equals(obj) | Renvoie une valeur indiquant si cette instance est égale à un objet spécifié. |

 **Result:**



---


### hashCode{#hashCode}

| Nom | Description |
| --- | --- |
| hashCode() | Renvoie le code de hachage pour cette instance. |

 **Result:**



---


### compareTo{#compareTo}

| Nom | Description |
| --- | --- |
| compareTo(other) | Comparer l'état de rendu avec une autre instance |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| othe | RenderState | null |

 **Result:**
Nombre


---



