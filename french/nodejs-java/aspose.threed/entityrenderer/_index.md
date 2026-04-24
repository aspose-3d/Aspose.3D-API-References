---
title: EntityRenderer
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/entityrenderer/
---
## EntityRenderer class

Sous-classez ceci pour implémenter le rendu pour différents types d'entités.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor(key, features) | Constructeur de EntityRenderer |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| clé | String | La clé du rendu d'entité |
| fonctionnalités | octet | EntityRendererFeatures |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(key) | Constructeur de EntityRenderer |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| clé | String | La clé du rendu d'entité |

 **Result:**



---


### initialize{#initialize}

| Nom | Description |
| --- | --- |
| initialize(renderer) | Initialiser le entity renderer |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| rendu | Renderer | null |

 **Result:**



---


### resetSceneCache{#resetSceneCache}

| Nom | Description |
| --- | --- |
| resetSceneCache() | La scène a changé ou a été supprimée, il faut libérer les ressources de rendu au niveau de la scène dans ce cas. |

 **Result:**



---


### frameBegin{#frameBegin}

| Nom | Description |
| --- | --- |
| frameBegin(renderer, renderQueue) | Commencer le rendu d'une image |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| renderer | Renderer | Rendu actuel |
| renderQueue | IRenderQueue | File d'attente de rendu |

 **Result:**



---


### frameEnd{#frameEnd}

| Nom | Description |
| --- | --- |
| frameEnd(renderer, renderQueue) | Termine le rendu d'une image |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| renderer | Renderer | Rendu actuel |
| renderQueue | IRenderQueue | File d'attente de rendu |

 **Result:**



---


### prepareRenderQueue{#prepareRenderQueue}

| Nom | Description |
| --- | --- |
| prepareRenderQueue(renderer, queue, node, entity) | Préparer les commandes de rendu pour la paire nœud/entité spécifiée. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| renderer | Renderer | L'instance du rendu actuel |
| queue | IRenderQueue | La file d'attente de rendu utilisée pour gérer les tâches de rendu |
| node | Node | Nœud actuel |
| entity | Entity | L'entité qui doit être rendue |

 **Result:**



---


### renderEntity{#renderEntity}

| Nom | Description |
| --- | --- |
| renderEntity(renderer, commandList, node, renderableResource, subEntity) | Chaque tâche de rendu poussée dans le com.aspose.threed.IRenderQueue aura un appel RenderEntity correspondant pour effectuer le travail de rendu concret. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| renderer | Renderer | Le moteur de rendu |
| commandList | ICommandList | La commandList utilisée pour enregistrer les commandes de rendu |
| node | Node | Le même nœud qui a été passé à PrepareRenderQueue de l'entité qui sera rendue |
| renderableResource | Object | L'objet personnalisé qui a été passé à IRenderQueue pendant le PrepareRenderQueue |
| subEntity | Number | L'index de la sous‑entité qui a été passé à IRenderQueue |

 **Result:**



---


### dispose{#dispose}

| Nom | Description |
| --- | --- |
| dispose() | Le entity renderer est en cours de libération, libérez les ressources partagées. |

 **Result:**



---



