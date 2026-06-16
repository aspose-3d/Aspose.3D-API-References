---
title: "EntityRenderer"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/entityrenderer/
---
## EntityRenderer class

Estendi questa classe per implementare il rendering per diversi tipi di entità.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor(key, features) | Costruttore di EntityRenderer |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| key | Stringa | La chiave di EntityRenderer |
| features | byte | EntityRendererFeatures |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nome | Descrizione |
| --- | --- |
| constructor_overload(key) | Costruttore di EntityRenderer |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| key | Stringa | La chiave di EntityRenderer |

 **Result:**



---


### initialize{#initialize}

| Nome | Descrizione |
| --- | --- |
| initialize(renderer) | Inizializza EntityRenderer |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| rendere | Renderer | null |

 **Result:**



---


### resetSceneCache{#resetSceneCache}

| Nome | Descrizione |
| --- | --- |
| resetSceneCache() | La scena è cambiata o rimossa, è necessario liberare le risorse di rendering a livello di scena in questo |

 **Result:**



---


### frameBegin{#frameBegin}

| Nome | Descrizione |
| --- | --- |
| frameBegin(renderer, renderQueue) | Inizia il rendering di un fotogramma |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| renderer | Renderer | Renderer corrente |
| renderQueue | IRenderQueue | Coda di rendering |

 **Result:**



---


### frameEnd{#frameEnd}

| Nome | Descrizione |
| --- | --- |
| frameEnd(renderer, renderQueue) | Termina il rendering di un fotogramma |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| renderer | Renderer | Renderer corrente |
| renderQueue | IRenderQueue | Coda di rendering |

 **Result:**



---


### prepareRenderQueue{#prepareRenderQueue}

| Nome | Descrizione |
| --- | --- |
| prepareRenderQueue(renderer, queue, node, entity) | Prepara i comandi di rendering per la coppia nodo/entità specificata. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| renderer | Renderer | L'istanza corrente del renderer |
| queue | IRenderQueue | La coda di rendering utilizzata per gestire i compiti di rendering |
| node | Nodo | Nodo corrente |
| entity | Entità | L'entità che deve essere renderizzata |

 **Result:**



---


### renderEntity{#renderEntity}

| Nome | Descrizione |
| --- | --- |
| renderEntity(renderer, commandList, node, renderableResource, subEntity) | Ogni compito di rendering inserito nella com.aspose.threed.IRenderQueue avrà una chiamata corrispondente a RenderEntity per eseguire il lavoro di rendering concreto. |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| renderer | Renderer | Il renderer |
| commandList | ICommandList | Il commandList usato per registrare i comandi di rendering |
| node | Nodo | Lo stesso nodo che è stato passato a PrepareRenderQueue dell'entità che sarà renderizzata |
| renderableResource | Oggetto | L'oggetto personalizzato che è stato passato a IRenderQueue durante il PrepareRenderQueue |
| subEntity | Numero | L'indice della sub entity che è stato passato a IRenderQueue |

 **Result:**



---


### dispose{#dispose}

| Nome | Descrizione |
| --- | --- |
| dispose() | Il renderer dell'entità è in fase di smaltimento, rilascia le risorse condivise. |

 **Result:**



---



