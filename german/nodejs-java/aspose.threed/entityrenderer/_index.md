---
title: "EntityRenderer"
second_title: "Aspose.3D für Node.js via Java API-Referenz"
description: 
type: docs

url: /de/nodejs-java/aspose.threed/entityrenderer/
---
## EntityRenderer class

Leiten Sie davon ab, um das Rendering für verschiedene Arten von Entitäten zu implementieren.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(key, features) | Konstruktor von EntityRenderer |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| key | String | Der Schlüssel des EntityRenderers |
| features | byte | EntityRendererFeatures |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(key) | Konstruktor von EntityRenderer |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| key | String | Der Schlüssel des EntityRenderers |

 **Result:**



---


### initialize{#initialize}

| Name | Beschreibung |
| --- | --- |
| initialize(renderer) | Initialisiere den EntityRenderer |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| rendere | Renderer | null |

 **Result:**



---


### resetSceneCache{#resetSceneCache}

| Name | Beschreibung |
| --- | --- |
| resetSceneCache() | Die Szene wurde geändert oder entfernt, daher müssen hier die renderbezogenen Ressourcen auf Szenenebene freigegeben werden. |

 **Result:**



---


### frameBegin{#frameBegin}

| Name | Beschreibung |
| --- | --- |
| frameBegin(renderer, renderQueue) | Beginne das Rendern eines Frames |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Renderer | Renderer | Aktueller Renderer |
| renderQueue | IRenderQueue | Render-Warteschlange |

 **Result:**



---


### frameEnd{#frameEnd}

| Name | Beschreibung |
| --- | --- |
| frameEnd(renderer, renderQueue) | Beendet das Rendern eines Frames |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Renderer | Renderer | Aktueller Renderer |
| renderQueue | IRenderQueue | Render-Warteschlange |

 **Result:**



---


### prepareRenderQueue{#prepareRenderQueue}

| Name | Beschreibung |
| --- | --- |
| prepareRenderQueue(renderer, queue, node, entity) | Bereite Renderbefehle für das angegebene node/entity-Paar vor. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Renderer | Renderer | Die aktuelle Renderer-Instanz |
| Warteschlange | IRenderQueue | Die Render-Warteschlange, die zur Verwaltung von Renderaufgaben verwendet wird |
| Knoten | Knoten | Aktueller Knoten |
| Entität | Entität | Die Entität, die gerendert werden muss |

 **Result:**



---


### renderEntity{#renderEntity}

| Name | Beschreibung |
| --- | --- |
| renderEntity(renderer, commandList, node, renderableResource, subEntity) | Jede Renderaufgabe, die in die com.aspose.threed.IRenderQueue geschoben wird, hat einen entsprechenden RenderEntity-Aufruf, um den konkreten Rendering-Job auszuführen. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Renderer | Renderer | Der Renderer |
| Befehlsliste | ICommandList | Die commandList, die zum Aufzeichnen der Rendering-Befehle verwendet wird |
| Knoten | Knoten | Der gleiche Knoten, der an PrepareRenderQueue der Entität übergeben wurde, die gerendert wird |
| renderableResource | Objekt | Das benutzerdefinierte Objekt, das an IRenderQueue während des PrepareRenderQueue übergeben wurde. |
| subEntity | Zahl | Der Index der Sub-Entität, die an IRenderQueue übergeben wurde. |

 **Result:**



---


### dispose{#dispose}

| Name | Beschreibung |
| --- | --- |
| dispose() | Der Entity-Renderer wird entsorgt, freigeben Sie gemeinsam genutzte Ressourcen. |

 **Result:**



---



