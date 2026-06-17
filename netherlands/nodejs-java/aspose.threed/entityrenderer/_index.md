---
title: "EntityRenderer"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/entityrenderer/
---
## EntityRenderer class

Maak hier een subklasse van om rendering te implementeren voor verschillende soorten entiteiten.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor(key, features) | Constructor van EntityRenderer |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| key | String | De sleutel van de entity renderer |
| features | byte | EntityRendererFeatures |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(key) | Constructor van EntityRenderer |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| key | String | De sleutel van de entity renderer |

 **Result:**



---


### initialize{#initialize}

| Naam | Beschrijving |
| --- | --- |
| initialize(renderer) | Initialiseer de entity renderer |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| rendere | Renderer | null |

 **Result:**



---


### resetSceneCache{#resetSceneCache}

| Naam | Beschrijving |
| --- | --- |
| resetSceneCache() | De scène is gewijzigd of verwijderd, er moeten renderbronnen op scenenniveau worden vrijgegeven in dit |

 **Result:**



---


### frameBegin{#frameBegin}

| Naam | Beschrijving |
| --- | --- |
| frameBegin(renderer, renderQueue) | Begin met het renderen van een frame |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| renderer | Renderer | Huidige renderer |
| renderQueue | IRenderQueue | Renderwachtrij |

 **Result:**



---


### frameEnd{#frameEnd}

| Naam | Beschrijving |
| --- | --- |
| frameEnd(renderer, renderQueue) | Beëindigt het renderen van een frame |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| renderer | Renderer | Huidige renderer |
| renderQueue | IRenderQueue | Renderwachtrij |

 **Result:**



---


### prepareRenderQueue{#prepareRenderQueue}

| Naam | Beschrijving |
| --- | --- |
| prepareRenderQueue(renderer, queue, node, entity) | Bereid renderopdrachten voor voor het opgegeven node/entity-paar. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| renderer | Renderer | De huidige renderer-instantie |
| queue | IRenderQueue | De renderwachtrij die wordt gebruikt om rendertaken te beheren |
| node | Node | Huidige node |
| entity | Entity | De entiteit die moet worden gerenderd |

 **Result:**



---


### renderEntity{#renderEntity}

| Naam | Beschrijving |
| --- | --- |
| renderEntity(renderer, commandList, node, renderableResource, subEntity) | Elke rendertaak die naar de com.aspose.threed.IRenderQueue wordt gepusht, krijgt een overeenkomstige RenderEntity-aanroep om de concrete rendertaak uit te voeren. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| renderer | Renderer | De renderer |
| commandList | ICommandList | De commandList die wordt gebruikt om de renderopdrachten op te nemen |
| node | Node | Dezelfde node die is doorgegeven aan PrepareRenderQueue van de entiteit die zal worden gerenderd |
| renderableResource | Object | Het aangepaste object dat is doorgegeven aan IRenderQueue tijdens de PrepareRenderQueue |
| subEntity | Number | De index van de sub entity die is doorgegeven aan IRenderQueue |

 **Result:**



---


### dispose{#dispose}

| Naam | Beschrijving |
| --- | --- |
| dispose() | De entity renderer wordt verwijderd, maak gedeelde bronnen vrij. |

 **Result:**



---



