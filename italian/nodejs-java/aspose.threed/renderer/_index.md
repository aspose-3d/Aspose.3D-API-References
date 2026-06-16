---
title: "Renderer"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/renderer/
---
## Renderer class

Il contesto relativo al renderer.  @hideconstructor


## Metodi

### getShaderSet{#getShaderSet}

| Nome | Descrizione |
| --- | --- |
| getShaderSet() | Ottiene o imposta il set di shader utilizzato per renderizzare la scena |

 **Result:**



---


### setShaderSet{#setShaderSet}

| Nome | Descrizione |
| --- | --- |
| setShaderSet(value) | Ottiene o imposta il set di shader utilizzato per renderizzare la scena |

 **Result:**



---


### getVariables{#getVariables}

| Nome | Descrizione |
| --- | --- |
| getVariables() | Accesso alle variabili interne utilizzate per il rendering |

 **Result:**



---


### getPresetShaders{#getPresetShaders}

| Nome | Descrizione |
| --- | --- |
| getPresetShaders() | Ottiene o imposta il set di shader predefinito. Il valore della proprietà è la costante intera PresetShaders. |

 **Result:**



---


### setPresetShaders{#setPresetShaders}

| Nome | Descrizione |
| --- | --- |
| setPresetShaders(value) | Ottiene o imposta il set di shader predefinito. Il valore della proprietà è la costante intera PresetShaders. |

 **Result:**



---


### getRenderFactory{#getRenderFactory}

| Nome | Descrizione |
| --- | --- |
| getRenderFactory() | Ottiene la factory per creare oggetti correlati al rendering. |

 **Result:**



---


### getAssetDirectories{#getAssetDirectories}

| Nome | Descrizione |
| --- | --- |
| getAssetDirectories() | Directory che memorizzano risorse esterne |

 **Result:**



---


### getPostProcessings{#getPostProcessings}

| Nome | Descrizione |
| --- | --- |
| getPostProcessings() | Catena di post-processing attiva |

 **Result:**



---


### getEnableShadows{#getEnableShadows}

| Nome | Descrizione |
| --- | --- |
| getEnableShadows() | Ottiene o imposta se abilitare le ombre. |

 **Result:**



---


### setEnableShadows{#setEnableShadows}

| Nome | Descrizione |
| --- | --- |
| setEnableShadows(value) | Ottiene o imposta se abilitare le ombre. |

 **Result:**



---


### getRenderTarget{#getRenderTarget}

| Nome | Descrizione |
| --- | --- |
| getRenderTarget() | Specifica il target di rendering su cui verranno eseguite le successive operazioni di rendering. |

 **Result:**



---


### getNode{#getNode}

| Nome | Descrizione |
| --- | --- |
| getNode() | Ottiene o imposta l'istanza Node utilizzata per fornire la matrice di trasformazione mondiale. |

 **Result:**



---


### setNode{#setNode}

| Nome | Descrizione |
| --- | --- |
| setNode(value) | Ottiene o imposta l'istanza Node utilizzata per fornire la matrice di trasformazione mondiale. |

 **Result:**



---


### getFrustum{#getFrustum}

| Nome | Descrizione |
| --- | --- |
| getFrustum() | Ottiene o imposta il frustum utilizzato per fornire la matrice di visualizzazione. |

 **Result:**



---


### setFrustum{#setFrustum}

| Nome | Descrizione |
| --- | --- |
| setFrustum(value) | Ottiene o imposta il frustum utilizzato per fornire la matrice di visualizzazione. |

 **Result:**



---


### getRenderStage{#getRenderStage}

| Nome | Descrizione |
| --- | --- |
| getRenderStage() | Ottiene lo stato di rendering corrente. Il valore della proprietà è la costante intera RenderStage. |

 **Result:**



---


### getMaterial{#getMaterial}

| Nome | Descrizione |
| --- | --- |
| getMaterial() | Ottiene o imposta il materiale utilizzato per fornire le informazioni sui materiali usate dagli shader. |

 **Result:**



---


### setMaterial{#setMaterial}

| Nome | Descrizione |
| --- | --- |
| setMaterial(value) | Ottiene o imposta il materiale utilizzato per fornire le informazioni sui materiali usate dagli shader. |

 **Result:**



---


### getShader{#getShader}

| Nome | Descrizione |
| --- | --- |
| getShader() | Ottiene o imposta l'istanza shader utilizzata per il rendering della geometria. |

 **Result:**



---


### setShader{#setShader}

| Nome | Descrizione |
| --- | --- |
| setShader(value) | Ottiene o imposta l'istanza shader utilizzata per il rendering della geometria. |

 **Result:**



---


### getFallbackEntityRenderer{#getFallbackEntityRenderer}

| Nome | Descrizione |
| --- | --- |
| getFallbackEntityRenderer() | Ottiene o imposta il renderer di fallback dell'entità quando l'entità non ha un renderer speciale definito. |

 **Result:**



---


### setFallbackEntityRenderer{#setFallbackEntityRenderer}

| Nome | Descrizione |
| --- | --- |
| setFallbackEntityRenderer(value) | Ottiene o imposta il renderer di fallback dell'entità quando l'entità non ha un renderer speciale definito. |

 **Result:**



---


### clearCache{#clearCache}

| Nome | Descrizione |
| --- | --- |
| clearCache() | Cancella manualmente la cache. Aspose.3D memorizzerà nella cache alcuni oggetti come materiali/geometrie in tipi interni compatibili con la pipeline di rendering. Questo dovrebbe essere chiamato manualmente quando la scena subisce cambiamenti importanti. |

 **Result:**



---


### getPostProcessing{#getPostProcessing}

| Nome | Descrizione |
| --- | --- |
| getPostProcessing(name) | Ottiene un post-processore integrato supportato dal renderer. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| nam | Stringa | null |

 **Result:**
PostProcessing


---


### execute{#execute}

| Nome | Descrizione |
| --- | --- |
| execute(postProcessing, result) | Esegue un post-processing sul target di rendering specificato |

 **Result:**
PostProcessing


---


### createRenderer{#createRenderer}

| Nome | Descrizione |
| --- | --- |
| createRenderer() | Crea un nuovo Renderer con profilo predefinito. |

 **Result:**
Renderer


---


### registerEntityRenderer{#registerEntityRenderer}

| Nome | Descrizione |
| --- | --- |
| registerEntityRenderer(renderer) | Registra il renderer dell'entità per l'entità specificata |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| rendere | EntityRenderer | null |

 **Result:**
Renderer


---


### render{#render}

| Nome | Descrizione |
| --- | --- |
| render(renderTarget) | Esegui il rendering del target specificato |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| renderTarge | IRenderTarget | null |

 **Result:**
Renderer


---



