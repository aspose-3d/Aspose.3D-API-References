---
title: "Renderare"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/renderer/
---
## Renderer class

Kontexten om renderaren.  @hideconstructor


## Metoder

### getShaderSet{#getShaderSet}

| Namn | Beskrivning |
| --- | --- |
| getShaderSet() | Hämtar eller anger shader-uppsättningen som används för att rendera scenen |

 **Result:**



---


### setShaderSet{#setShaderSet}

| Namn | Beskrivning |
| --- | --- |
| setShaderSet(value) | Hämtar eller anger shader-uppsättningen som används för att rendera scenen |

 **Result:**



---


### getVariables{#getVariables}

| Namn | Beskrivning |
| --- | --- |
| getVariables() | Åtkomst till de interna variablerna som används för rendering |

 **Result:**



---


### getPresetShaders{#getPresetShaders}

| Namn | Beskrivning |
| --- | --- |
| getPresetShaders() | Hämtar eller anger den förinställda shader-uppsättningen. Värdet på egenskapen är heltalskonstanten PresetShaders. |

 **Result:**



---


### setPresetShaders{#setPresetShaders}

| Namn | Beskrivning |
| --- | --- |
| setPresetShaders(value) | Hämtar eller anger den förinställda shader-uppsättningen. Värdet på egenskapen är heltalskonstanten PresetShaders. |

 **Result:**



---


### getRenderFactory{#getRenderFactory}

| Namn | Beskrivning |
| --- | --- |
| getRenderFactory() | Hämtar fabriken för att skapa renderingsrelaterade objekt. |

 **Result:**



---


### getAssetDirectories{#getAssetDirectories}

| Namn | Beskrivning |
| --- | --- |
| getAssetDirectories() | Kataloger som lagrar externa resurser |

 **Result:**



---


### getPostProcessings{#getPostProcessings}

| Namn | Beskrivning |
| --- | --- |
| getPostProcessings() | Aktiv efterbehandlingskedja |

 **Result:**



---


### getEnableShadows{#getEnableShadows}

| Namn | Beskrivning |
| --- | --- |
| getEnableShadows() | Hämtar eller anger om skuggor ska aktiveras. |

 **Result:**



---


### setEnableShadows{#setEnableShadows}

| Namn | Beskrivning |
| --- | --- |
| setEnableShadows(value) | Hämtar eller anger om skuggor ska aktiveras. |

 **Result:**



---


### getRenderTarget{#getRenderTarget}

| Namn | Beskrivning |
| --- | --- |
| getRenderTarget() | Ange render‑målet som de följande renderingsoperationerna kommer att utföras på. |

 **Result:**



---


### getNode{#getNode}

| Namn | Beskrivning |
| --- | --- |
| getNode() | Hämtar eller anger Node‑instansen som används för att tillhandahålla världstransformmatrisen. |

 **Result:**



---


### setNode{#setNode}

| Namn | Beskrivning |
| --- | --- |
| setNode(value) | Hämtar eller anger Node‑instansen som används för att tillhandahålla världstransformmatrisen. |

 **Result:**



---


### getFrustum{#getFrustum}

| Namn | Beskrivning |
| --- | --- |
| getFrustum() | Hämtar eller anger frustum som används för att tillhandahålla vy‑matrisen. |

 **Result:**



---


### setFrustum{#setFrustum}

| Namn | Beskrivning |
| --- | --- |
| setFrustum(value) | Hämtar eller anger frustum som används för att tillhandahålla vy‑matrisen. |

 **Result:**



---


### getRenderStage{#getRenderStage}

| Namn | Beskrivning |
| --- | --- |
| getRenderStage() | Hämtar det aktuella renderingsstadiet. Värdet på egenskapen är en heltalskonstant för RenderStage. |

 **Result:**



---


### getMaterial{#getMaterial}

| Namn | Beskrivning |
| --- | --- |
| getMaterial() | Hämtar eller anger materialet som används för att tillhandahålla materialinformation som shaders använder. |

 **Result:**



---


### setMaterial{#setMaterial}

| Namn | Beskrivning |
| --- | --- |
| setMaterial(value) | Hämtar eller anger materialet som används för att tillhandahålla materialinformation som shaders använder. |

 **Result:**



---


### getShader{#getShader}

| Namn | Beskrivning |
| --- | --- |
| getShader() | Hämtar eller anger shader‑instansen som används för att rendera geometrin. |

 **Result:**



---


### setShader{#setShader}

| Namn | Beskrivning |
| --- | --- |
| setShader(value) | Hämtar eller anger shader‑instansen som används för att rendera geometrin. |

 **Result:**



---


### getFallbackEntityRenderer{#getFallbackEntityRenderer}

| Namn | Beskrivning |
| --- | --- |
| getFallbackEntityRenderer() | Hämtar eller anger reserv‑entity‑renderaren när enheten inte har någon speciell renderare definierad. |

 **Result:**



---


### setFallbackEntityRenderer{#setFallbackEntityRenderer}

| Namn | Beskrivning |
| --- | --- |
| setFallbackEntityRenderer(value) | Hämtar eller anger reserv‑entity‑renderaren när enheten inte har någon speciell renderare definierad. |

 **Result:**



---


### clearCache{#clearCache}

| Namn | Beskrivning |
| --- | --- |
| clearCache() | Rensa cachen manuellt. Aspose.3D kommer att cacha vissa objekt som material/geometrier i interna typer som är kompatibla med renderings‑pipen. Detta bör anropas manuellt när scenen har större förändringar. |

 **Result:**



---


### getPostProcessing{#getPostProcessing}

| Namn | Beskrivning |
| --- | --- |
| getPostProcessing(name) | Hämtar en inbyggd post‑processor som stöds av renderaren. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| nam | Sträng | null |

 **Result:**
PostProcessing


---


### execute{#execute}

| Namn | Beskrivning |
| --- | --- |
| execute(postProcessing, result) | Utför en efterbehandling på angivet render‑mål. |

 **Result:**
PostProcessing


---


### createRenderer{#createRenderer}

| Namn | Beskrivning |
| --- | --- |
| createRenderer() | Skapar en ny Renderer med standardprofil. |

 **Result:**
Renderare


---


### registerEntityRenderer{#registerEntityRenderer}

| Namn | Beskrivning |
| --- | --- |
| registerEntityRenderer(renderer) | Registrera enhetsrenderaren för angiven entitet |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| rendere | EntityRenderer | null |

 **Result:**
Renderare


---


### render{#render}

| Namn | Beskrivning |
| --- | --- |
| render(renderTarget) | Rendera det angivna målet |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| renderTarge | IRenderTarget | null |

 **Result:**
Renderare


---



