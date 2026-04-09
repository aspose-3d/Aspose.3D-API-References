---
title: Renderer
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/renderer/
---
## Renderer class

Le contexte du rendu.  @hideconstructor


## Méthodes

### getShaderSet{#getShaderSet}

| Nom | Description |
| --- | --- |
| getShaderSet() | Obtient ou définit l'ensemble de shaders utilisé pour rendre la scène |

 **Result:**



---


### setShaderSet{#setShaderSet}

| Nom | Description |
| --- | --- |
| setShaderSet(value) | Obtient ou définit l'ensemble de shaders utilisé pour rendre la scène |

 **Result:**



---


### getVariables{#getVariables}

| Nom | Description |
| --- | --- |
| getVariables() | Accès aux variables internes utilisées pour le rendu |

 **Result:**



---


### getPresetShaders{#getPresetShaders}

| Nom | Description |
| --- | --- |
| getPresetShaders() | Obtient ou définit l'ensemble de shaders prédéfini. La valeur de la propriété est la constante entière PresetShaders. |

 **Result:**



---


### setPresetShaders{#setPresetShaders}

| Nom | Description |
| --- | --- |
| setPresetShaders(value) | Obtient ou définit l'ensemble de shaders prédéfini. La valeur de la propriété est la constante entière PresetShaders. |

 **Result:**



---


### getRenderFactory{#getRenderFactory}

| Nom | Description |
| --- | --- |
| getRenderFactory() | Obtient la fabrique permettant de créer les objets liés au rendu. |

 **Result:**



---


### getAssetDirectories{#getAssetDirectories}

| Nom | Description |
| --- | --- |
| getAssetDirectories() | Répertoires qui stockent les ressources externes |

 **Result:**



---


### getPostProcessings{#getPostProcessings}

| Nom | Description |
| --- | --- |
| getPostProcessings() | Chaîne de post-traitement active |

 **Result:**



---


### getEnableShadows{#getEnableShadows}

| Nom | Description |
| --- | --- |
| getEnableShadows() | Obtient ou définit si les ombres sont activées. |

 **Result:**



---


### setEnableShadows{#setEnableShadows}

| Nom | Description |
| --- | --- |
| setEnableShadows(value) | Obtient ou définit si les ombres sont activées. |

 **Result:**



---


### getRenderTarget{#getRenderTarget}

| Nom | Description |
| --- | --- |
| getRenderTarget() | Spécifiez la cible de rendu sur laquelle les opérations de rendu suivantes seront effectuées. |

 **Result:**



---


### getNode{#getNode}

| Nom | Description |
| --- | --- |
| getNode() | Obtient ou définit l'instance Node utilisée pour fournir la matrice de transformation du monde. |

 **Result:**



---


### setNode{#setNode}

| Nom | Description |
| --- | --- |
| setNode(value) | Obtient ou définit l'instance Node utilisée pour fournir la matrice de transformation du monde. |

 **Result:**



---


### getFrustum{#getFrustum}

| Nom | Description |
| --- | --- |
| getFrustum() | Obtient ou définit le frustrum utilisé pour fournir la matrice de vue. |

 **Result:**



---


### setFrustum{#setFrustum}

| Nom | Description |
| --- | --- |
| setFrustum(value) | Obtient ou définit le frustrum utilisé pour fournir la matrice de vue. |

 **Result:**



---


### getRenderStage{#getRenderStage}

| Nom | Description |
| --- | --- |
| getRenderStage() | Obtient l'étape de rendu actuelle. La valeur de la propriété est la constante entière RenderStage. |

 **Result:**



---


### getMaterial{#getMaterial}

| Nom | Description |
| --- | --- |
| getMaterial() | Obtient ou définit le matériau utilisé pour fournir les informations de matériau utilisées par les shaders. |

 **Result:**



---


### setMaterial{#setMaterial}

| Nom | Description |
| --- | --- |
| setMaterial(value) | Obtient ou définit le matériau utilisé pour fournir les informations de matériau utilisées par les shaders. |

 **Result:**



---


### getShader{#getShader}

| Nom | Description |
| --- | --- |
| getShader() | Obtient ou définit l'instance de shader utilisée pour le rendu de la géométrie. |

 **Result:**



---


### setShader{#setShader}

| Nom | Description |
| --- | --- |
| setShader(value) | Obtient ou définit l'instance de shader utilisée pour le rendu de la géométrie. |

 **Result:**



---


### getFallbackEntityRenderer{#getFallbackEntityRenderer}

| Nom | Description |
| --- | --- |
| getFallbackEntityRenderer() | Obtient ou définit le fallback entity renderer lorsque l'entité n'a aucun rendu spécial défini. |

 **Result:**



---


### setFallbackEntityRenderer{#setFallbackEntityRenderer}

| Nom | Description |
| --- | --- |
| setFallbackEntityRenderer(value) | Obtient ou définit le fallback entity renderer lorsque l'entité n'a aucun rendu spécial défini. |

 **Result:**



---


### clearCache{#clearCache}

| Nom | Description |
| --- | --- |
| clearCache() | Effacez manuellement le cache. Aspose.3D met en cache certains objets comme les matériaux/géométries dans des types internes compatibles avec le pipeline de rendu. Cela doit être appelé manuellement lorsque la scène subit des changements majeurs. |

 **Result:**



---


### getPostProcessing{#getPostProcessing}

| Nom | Description |
| --- | --- |
| getPostProcessing(name) | Obtient un post-processeur intégré pris en charge par le renderer. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | null |

 **Result:**
PostProcessing


---


### execute{#execute}

| Nom | Description |
| --- | --- |
| execute(postProcessing, result) | Exécutez un post-traitement sur la cible de rendu spécifiée |

 **Result:**
PostProcessing


---


### createRenderer{#createRenderer}

| Nom | Description |
| --- | --- |
| createRenderer() | Crée un nouveau Renderer avec le profil par défaut. |

 **Result:**
Renderer


---


### registerEntityRenderer{#registerEntityRenderer}

| Nom | Description |
| --- | --- |
| registerEntityRenderer(renderer) | Enregistrez le rendu d'entité pour l'entité spécifiée |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| rendu | EntityRenderer | null |

 **Result:**
Renderer


---


### render{#render}

| Nom | Description |
| --- | --- |
| render(renderTarget) | Rendre la cible spécifiée |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| renderTarge | IRenderTarget | null |

 **Result:**
Renderer


---



