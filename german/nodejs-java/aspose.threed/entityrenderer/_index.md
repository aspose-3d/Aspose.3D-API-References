---
title: EntityRenderer
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/entityrenderer/
---
## EntityRenderer class

Erben Sie davon, um das Rendering für verschiedene Arten von Entitäten zu implementieren.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(key, features) | Konstruktor von EntityRenderer |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | String | Der Schlüssel des Entity-Renderers |
| Funktionen | Byte | EntityRendererFeatures |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Name | Beschreibung |
| --- | --- |
| constructor_overload(key) | Konstruktor von EntityRenderer |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| Schlüssel | String | Der Schlüssel des Entity-Renderers |

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
| resetSceneCache() | Die Szene wurde geändert oder entfernt, szenenbezogene Renderressourcen müssen freigegeben werden. |

 **Result:**



---


### frameBegin{#frameBegin}

| Name | Beschreibung |
| --- | --- |
| frameBegin(renderer, renderQueue) | Beginne das Rendern eines Frames |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| renderer | Renderer | Aktueller Renderer |
| renderQueue | IRenderQueue | Renderwarteschlange |

 **Result:**



---


### frameEnd{#frameEnd}

| Name | Beschreibung |
| --- | --- |
| frameEnd(renderer, renderQueue) | Beendet das Rendern eines Frames |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| renderer | Renderer | Aktueller Renderer |
| renderQueue | IRenderQueue | Renderwarteschlange |

 **Result:**



---


### prepareRenderQueue{#prepareRenderQueue}

| Name | Beschreibung |
| --- | --- |
| prepareRenderQueue(renderer, queue, node, entity) | Bereite Renderbefehle für das angegebene Knoten/Entity-Paar vor. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| renderer | Renderer | Die aktuelle Renderer-Instanz |
| queue | IRenderQueue | Die Renderwarteschlange, die zur Verwaltung von Renderaufgaben verwendet wird |
| node | Node | Aktueller Knoten |
| entity | Entity | Das Entity, das gerendert werden muss |

 **Result:**



---


### renderEntity{#renderEntity}

| Name | Beschreibung |
| --- | --- |
| renderEntity(renderer, commandList, node, renderableResource, subEntity) | Each render task pushed to the com.aspose.threed.IRenderQueue will have a corresponding RenderEntity call to perform the concrete rendering job. |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| renderer | Renderer | Der Renderer |
| commandList | ICommandList | Die commandList, die zum Aufzeichnen der Rendering-Befehle verwendet wird |
| node | Node | Der gleiche Knoten, der an PrepareRenderQueue des zu rendernden Entity übergeben wurde |
| renderableResource | Object | Das benutzerdefinierte Objekt, das während der PrepareRenderQueue an IRenderQueue übergeben wurde |
| subEntity | Number | Der Index des Sub-Entity, das an IRenderQueue übergeben wurde |

 **Result:**



---


### dispose{#dispose}

| Name | Beschreibung |
| --- | --- |
| dispose() | Der EntityRenderer wird entsorgt, gemeinsame Ressourcen freigegeben. |

 **Result:**



---



