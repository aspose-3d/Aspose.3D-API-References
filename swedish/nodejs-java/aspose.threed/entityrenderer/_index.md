---
title: "EntityRenderer"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/entityrenderer/
---
## EntityRenderer class

Skapa en underklass för att implementera rendering för olika typer av enheter.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor(key, features) | Konstruktor för EntityRenderer |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| key | Sträng | Nyckeln för entity renderer |
| features | byte | EntityRendererFeatures |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(key) | Konstruktor för EntityRenderer |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| key | Sträng | Nyckeln för entity renderer |

 **Result:**



---


### initialize{#initialize}

| Namn | Beskrivning |
| --- | --- |
| initialize(renderer) | Initiera entity renderer |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| rendere | Renderare | null |

 **Result:**



---


### resetSceneCache{#resetSceneCache}

| Namn | Beskrivning |
| --- | --- |
| resetSceneCache() | Scenen har ändrats eller tagits bort, så resurser på scen‑nivå måste avyttras här |

 **Result:**



---


### frameBegin{#frameBegin}

| Namn | Beskrivning |
| --- | --- |
| frameBegin(renderer, renderQueue) | Starta rendering av en ram |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| renderare | Renderare | Aktuell renderare |
| renderQueue | IRenderQueue | Renderingskö |

 **Result:**



---


### frameEnd{#frameEnd}

| Namn | Beskrivning |
| --- | --- |
| frameEnd(renderer, renderQueue) | Avslutar rendering av en ram |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| renderare | Renderare | Aktuell renderare |
| renderQueue | IRenderQueue | Renderingskö |

 **Result:**



---


### prepareRenderQueue{#prepareRenderQueue}

| Namn | Beskrivning |
| --- | --- |
| prepareRenderQueue(renderer, queue, node, entity) | Förbered renderingskommandon för angivet nod-/entitetspar. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| renderare | Renderare | Den aktuella renderarinstansen |
| kö | IRenderQueue | Renderingskön som används för att hantera renderingsuppgifter |
| nod | Nod | Aktuell nod |
| entitet | Entitet | Entiteten som behöver renderas |

 **Result:**



---


### renderEntity{#renderEntity}

| Namn | Beskrivning |
| --- | --- |
| renderEntity(renderer, commandList, node, renderableResource, subEntity) | Varje renderingsuppgift som läggs till i com.aspose.threed.IRenderQueue kommer att ha ett motsvarande RenderEntity‑anrop för att utföra det konkreta renderingsarbetet. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| renderare | Renderare | Renderaren |
| commandList | ICommandList | commandList som används för att spela in renderingskommandon |
| nod | Nod | Samma nod som skickas till PrepareRenderQueue för den enhet som ska renderas |
| renderableResource | Objekt | Det anpassade objektet som skickas till IRenderQueue under PrepareRenderQueue |
| subEntity | Nummer | Index för delentiteten som skickas till IRenderQueue |

 **Result:**



---


### dispose{#dispose}

| Namn | Beskrivning |
| --- | --- |
| dispose() | Entitetsrenderaren håller på att avyttras, släpp delade resurser. |

 **Result:**



---



