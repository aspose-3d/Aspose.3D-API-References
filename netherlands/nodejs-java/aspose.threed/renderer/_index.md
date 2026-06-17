---
title: "Renderer"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/renderer/
---
## Renderer class

De context over de renderer.  @hideconstructor


## Methoden

### getShaderSet{#getShaderSet}

| Naam | Beschrijving |
| --- | --- |
| getShaderSet() | Haalt op of stelt de shader set in die wordt gebruikt om de scène te renderen. |

 **Result:**



---


### setShaderSet{#setShaderSet}

| Naam | Beschrijving |
| --- | --- |
| setShaderSet(value) | Haalt op of stelt de shader set in die wordt gebruikt om de scène te renderen. |

 **Result:**



---


### getVariables{#getVariables}

| Naam | Beschrijving |
| --- | --- |
| getVariables() | Toegang tot de interne variabelen die worden gebruikt voor het renderen. |

 **Result:**



---


### getPresetShaders{#getPresetShaders}

| Naam | Beschrijving |
| --- | --- |
| getPresetShaders() | Haalt op of stelt de vooraf ingestelde shader-set in. De waarde van de eigenschap is een PresetShaders integer-constante. |

 **Result:**



---


### setPresetShaders{#setPresetShaders}

| Naam | Beschrijving |
| --- | --- |
| setPresetShaders(value) | Haalt op of stelt de vooraf ingestelde shader-set in. De waarde van de eigenschap is een PresetShaders integer-constante. |

 **Result:**



---


### getRenderFactory{#getRenderFactory}

| Naam | Beschrijving |
| --- | --- |
| getRenderFactory() | Haalt de fabriek op om render-gerelateerde objecten te bouwen. |

 **Result:**



---


### getAssetDirectories{#getAssetDirectories}

| Naam | Beschrijving |
| --- | --- |
| getAssetDirectories() | Mappen die externe assets opslaan. |

 **Result:**



---


### getPostProcessings{#getPostProcessings}

| Naam | Beschrijving |
| --- | --- |
| getPostProcessings() | Actieve post-processing keten |

 **Result:**



---


### getEnableShadows{#getEnableShadows}

| Naam | Beschrijving |
| --- | --- |
| getEnableShadows() | Haalt op of stelt in of schaduwen ingeschakeld moeten worden. |

 **Result:**



---


### setEnableShadows{#setEnableShadows}

| Naam | Beschrijving |
| --- | --- |
| setEnableShadows(value) | Haalt op of stelt in of schaduwen ingeschakeld moeten worden. |

 **Result:**



---


### getRenderTarget{#getRenderTarget}

| Naam | Beschrijving |
| --- | --- |
| getRenderTarget() | Specificeer het renderdoel waarop de volgende renderbewerkingen zullen worden uitgevoerd. |

 **Result:**



---


### getNode{#getNode}

| Naam | Beschrijving |
| --- | --- |
| getNode() | Haalt op of stelt de Node‑instantie in die wordt gebruikt om de wereldtransformatiematrix te leveren. |

 **Result:**



---


### setNode{#setNode}

| Naam | Beschrijving |
| --- | --- |
| setNode(value) | Haalt op of stelt de Node‑instantie in die wordt gebruikt om de wereldtransformatiematrix te leveren. |

 **Result:**



---


### getFrustum{#getFrustum}

| Naam | Beschrijving |
| --- | --- |
| getFrustum() | Haalt op of stelt de frustum in die wordt gebruikt om de kijkmatrix te leveren. |

 **Result:**



---


### setFrustum{#setFrustum}

| Naam | Beschrijving |
| --- | --- |
| setFrustum(value) | Haalt op of stelt de frustum in die wordt gebruikt om de kijkmatrix te leveren. |

 **Result:**



---


### getRenderStage{#getRenderStage}

| Naam | Beschrijving |
| --- | --- |
| getRenderStage() | Haalt de huidige renderfase op. De waarde van de eigenschap is de gehele constante RenderStage. |

 **Result:**



---


### getMaterial{#getMaterial}

| Naam | Beschrijving |
| --- | --- |
| getMaterial() | Haalt op of stelt het materiaal in dat wordt gebruikt om materiaalinformatie te leveren die door shaders wordt gebruikt. |

 **Result:**



---


### setMaterial{#setMaterial}

| Naam | Beschrijving |
| --- | --- |
| setMaterial(value) | Haalt op of stelt het materiaal in dat wordt gebruikt om materiaalinformatie te leveren die door shaders wordt gebruikt. |

 **Result:**



---


### getShader{#getShader}

| Naam | Beschrijving |
| --- | --- |
| getShader() | Haalt op of stelt de shader‑instantie in die wordt gebruikt voor het renderen van de geometrie. |

 **Result:**



---


### setShader{#setShader}

| Naam | Beschrijving |
| --- | --- |
| setShader(value) | Haalt op of stelt de shader‑instantie in die wordt gebruikt voor het renderen van de geometrie. |

 **Result:**



---


### getFallbackEntityRenderer{#getFallbackEntityRenderer}

| Naam | Beschrijving |
| --- | --- |
| getFallbackEntityRenderer() | Haalt op of stelt de fallback‑entity‑renderer in wanneer de entity geen speciale renderer heeft gedefinieerd. |

 **Result:**



---


### setFallbackEntityRenderer{#setFallbackEntityRenderer}

| Naam | Beschrijving |
| --- | --- |
| setFallbackEntityRenderer(value) | Haalt op of stelt de fallback‑entity‑renderer in wanneer de entity geen speciale renderer heeft gedefinieerd. |

 **Result:**



---


### clearCache{#clearCache}

| Naam | Beschrijving |
| --- | --- |
| clearCache() | Maak de cache handmatig leeg. Aspose.3D zal sommige objecten zoals materialen/geometrieën cachen in interne types die compatibel zijn met de render‑pipeline. Dit moet handmatig worden aangeroepen wanneer de scène grote wijzigingen ondergaat. |

 **Result:**



---


### getPostProcessing{#getPostProcessing}

| Naam | Beschrijving |
| --- | --- |
| getPostProcessing(name) | Haalt een ingebouwde post‑processor op die door de renderer wordt ondersteund. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| nam | String | null |

 **Result:**
PostProcessing


---


### execute{#execute}

| Naam | Beschrijving |
| --- | --- |
| execute(postProcessing, result) | Voer een post‑processing uit op het opgegeven renderdoel. |

 **Result:**
PostProcessing


---


### createRenderer{#createRenderer}

| Naam | Beschrijving |
| --- | --- |
| createRenderer() | Maakt een nieuwe Renderer aan met het standaardprofiel. |

 **Result:**
Renderer


---


### registerEntityRenderer{#registerEntityRenderer}

| Naam | Beschrijving |
| --- | --- |
| registerEntityRenderer(renderer) | Registreer de entiteit-renderer voor de opgegeven entiteit |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| rendere | EntityRenderer | null |

 **Result:**
Renderer


---


### render{#render}

| Naam | Beschrijving |
| --- | --- |
| render(renderTarget) | Render het opgegeven doel. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| renderTarge | IRenderTarget | null |

 **Result:**
Renderer


---



