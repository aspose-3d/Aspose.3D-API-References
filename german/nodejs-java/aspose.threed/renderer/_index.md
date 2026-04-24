---
title: Renderer
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/renderer/
---
## Renderer class

Der Kontext zum Renderer.  @hideconstructor


## Methoden

### getShaderSet{#getShaderSet}

| Name | Beschreibung |
| --- | --- |
| getShaderSet() | Liest oder setzt das Shader-Set, das zum Rendern der Szene verwendet wird. |

 **Result:**



---


### setShaderSet{#setShaderSet}

| Name | Beschreibung |
| --- | --- |
| setShaderSet(value) | Liest oder setzt das Shader-Set, das zum Rendern der Szene verwendet wird. |

 **Result:**



---


### getVariables{#getVariables}

| Name | Beschreibung |
| --- | --- |
| getVariables() | Zugriff auf die internen Variablen, die für das Rendering verwendet werden |

 **Result:**



---


### getPresetShaders{#getPresetShaders}

| Name | Beschreibung |
| --- | --- |
| getPresetShaders() | Liest oder setzt das voreingestellte Shader-Set. Der Wert der Eigenschaft ist die Ganzzahlkonstante PresetShaders. |

 **Result:**



---


### setPresetShaders{#setPresetShaders}

| Name | Beschreibung |
| --- | --- |
| setPresetShaders(value) | Liest oder setzt das voreingestellte Shader-Set. Der Wert der Eigenschaft ist die Ganzzahlkonstante PresetShaders. |

 **Result:**



---


### getRenderFactory{#getRenderFactory}

| Name | Beschreibung |
| --- | --- |
| getRenderFactory() | Gibt die Fabrik zurück, um renderbezogene Objekte zu erstellen. |

 **Result:**



---


### getAssetDirectories{#getAssetDirectories}

| Name | Beschreibung |
| --- | --- |
| getAssetDirectories() | Verzeichnisse, die externe Assets speichern. |

 **Result:**



---


### getPostProcessings{#getPostProcessings}

| Name | Beschreibung |
| --- | --- |
| getPostProcessings() | Aktive Post‑Processing‑Kette |

 **Result:**



---


### getEnableShadows{#getEnableShadows}

| Name | Beschreibung |
| --- | --- |
| getEnableShadows() | Liest oder setzt, ob Schatten aktiviert werden sollen. |

 **Result:**



---


### setEnableShadows{#setEnableShadows}

| Name | Beschreibung |
| --- | --- |
| setEnableShadows(value) | Liest oder setzt, ob Schatten aktiviert werden sollen. |

 **Result:**



---


### getRenderTarget{#getRenderTarget}

| Name | Beschreibung |
| --- | --- |
| getRenderTarget() | Geben Sie das Renderziel an, auf dem die folgenden Render‑Operationen ausgeführt werden. |

 **Result:**



---


### getNode{#getNode}

| Name | Beschreibung |
| --- | --- |
| getNode() | Liest oder setzt die Node-Instanz, die zur Bereitstellung der Welttransformationsmatrix verwendet wird. |

 **Result:**



---


### setNode{#setNode}

| Name | Beschreibung |
| --- | --- |
| setNode(value) | Liest oder setzt die Node-Instanz, die zur Bereitstellung der Welttransformationsmatrix verwendet wird. |

 **Result:**



---


### getFrustum{#getFrustum}

| Name | Beschreibung |
| --- | --- |
| getFrustum() | Liest oder setzt das Frustum, das zur Bereitstellung der Ansichtsmatrix verwendet wird. |

 **Result:**



---


### setFrustum{#setFrustum}

| Name | Beschreibung |
| --- | --- |
| setFrustum(value) | Liest oder setzt das Frustum, das zur Bereitstellung der Ansichtsmatrix verwendet wird. |

 **Result:**



---


### getRenderStage{#getRenderStage}

| Name | Beschreibung |
| --- | --- |
| getRenderStage() | Liest die aktuelle Renderstufe. Der Wert der Eigenschaft ist die ganzzahlige Konstante RenderStage. |

 **Result:**



---


### getMaterial{#getMaterial}

| Name | Beschreibung |
| --- | --- |
| getMaterial() | Liest oder setzt das Material, das zur Bereitstellung von Materialinformationen verwendet wird, die von Shadern genutzt werden. |

 **Result:**



---


### setMaterial{#setMaterial}

| Name | Beschreibung |
| --- | --- |
| setMaterial(value) | Liest oder setzt das Material, das zur Bereitstellung von Materialinformationen verwendet wird, die von Shadern genutzt werden. |

 **Result:**



---


### getShader{#getShader}

| Name | Beschreibung |
| --- | --- |
| getShader() | Liest oder setzt die Shader-Instanz, die zum Rendern der Geometrie verwendet wird. |

 **Result:**



---


### setShader{#setShader}

| Name | Beschreibung |
| --- | --- |
| setShader(value) | Liest oder setzt die Shader-Instanz, die zum Rendern der Geometrie verwendet wird. |

 **Result:**



---


### getFallbackEntityRenderer{#getFallbackEntityRenderer}

| Name | Beschreibung |
| --- | --- |
| getFallbackEntityRenderer() | Liest oder setzt den Fallback-Entity-Renderer, wenn für das Entity kein spezieller Renderer definiert ist. |

 **Result:**



---


### setFallbackEntityRenderer{#setFallbackEntityRenderer}

| Name | Beschreibung |
| --- | --- |
| setFallbackEntityRenderer(value) | Liest oder setzt den Fallback-Entity-Renderer, wenn für das Entity kein spezieller Renderer definiert ist. |

 **Result:**



---


### clearCache{#clearCache}

| Name | Beschreibung |
| --- | --- |
| clearCache() | Cache manuell leeren. Aspose.3D cached einige Objekte wie Materialien/Geometrien in internen Typen, die mit der Rendering‑Pipeline kompatibel sind. Dies sollte manuell aufgerufen werden, wenn die Szene größere Änderungen erfährt. |

 **Result:**



---


### getPostProcessing{#getPostProcessing}

| Name | Beschreibung |
| --- | --- |
| getPostProcessing(name) | Gibt einen integrierten Postprozessor zurück, der vom Renderer unterstützt wird. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| nam | String | null |

 **Result:**
PostProcessing


---


### execute{#execute}

| Name | Beschreibung |
| --- | --- |
| execute(postProcessing, result) | Führen Sie eine Nachbearbeitung auf dem angegebenen Renderziel aus. |

 **Result:**
PostProcessing


---


### createRenderer{#createRenderer}

| Name | Beschreibung |
| --- | --- |
| createRenderer() | Erstellt einen neuen Renderer mit dem Standardprofil. |

 **Result:**
Renderer


---


### registerEntityRenderer{#registerEntityRenderer}

| Name | Beschreibung |
| --- | --- |
| registerEntityRenderer(renderer) | Registrieren Sie den Entitätsrenderer für die angegebene Entität |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| rendere | EntityRenderer | null |

 **Result:**
Renderer


---


### render{#render}

| Name | Beschreibung |
| --- | --- |
| render(renderTarget) | Rendern Sie das angegebene Ziel |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| renderTarge | IRenderTarget | null |

 **Result:**
Renderer


---



