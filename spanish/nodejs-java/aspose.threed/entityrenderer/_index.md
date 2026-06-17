---
title: "EntityRenderer"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/entityrenderer/
---
## EntityRenderer class

Subclase esto para implementar renderizado para diferentes tipos de entidades.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor(key, features) | Constructor de EntityRenderer |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| key | Cadena | La clave del renderizador de entidad |
| features | byte | EntityRendererFeatures |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(key) | Constructor de EntityRenderer |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| key | Cadena | La clave del renderizador de entidad |

 **Result:**



---


### initialize{#initialize}

| Nombre | Descripción |
| --- | --- |
| initialize(renderer) | Inicializar el renderizador de entidad |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| rendere | Renderizador | null |

 **Result:**



---


### resetSceneCache{#resetSceneCache}

| Nombre | Descripción |
| --- | --- |
| resetSceneCache() | La escena ha cambiado o se ha eliminado, es necesario liberar los recursos de renderizado a nivel de escena en esto |

 **Result:**



---


### frameBegin{#frameBegin}

| Nombre | Descripción |
| --- | --- |
| frameBegin(renderer, renderQueue) | Iniciar el renderizado de un fotograma |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| renderizador | Renderizador | Renderizador actual |
| renderQueue | IRenderQueue | Cola de renderizado |

 **Result:**



---


### frameEnd{#frameEnd}

| Nombre | Descripción |
| --- | --- |
| frameEnd(renderer, renderQueue) | Finaliza el renderizado de un fotograma |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| renderizador | Renderizador | Renderizador actual |
| renderQueue | IRenderQueue | Cola de renderizado |

 **Result:**



---


### prepareRenderQueue{#prepareRenderQueue}

| Nombre | Descripción |
| --- | --- |
| prepareRenderQueue(renderer, queue, node, entity) | Preparar comandos de renderizado para el par nodo/entidad especificado. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| renderizador | Renderizador | La instancia del renderizador actual |
| cola | IRenderQueue | La cola de renderizado utilizada para gestionar tareas de renderizado |
| nodo | Nodo | Nodo actual |
| entidad | Entidad | La entidad que necesita ser renderizada |

 **Result:**



---


### renderEntity{#renderEntity}

| Nombre | Descripción |
| --- | --- |
| renderEntity(renderer, commandList, node, renderableResource, subEntity) | Cada tarea de renderizado enviada a com.aspose.threed.IRenderQueue tendrá una llamada correspondiente a RenderEntity para ejecutar el trabajo de renderizado concreto. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| renderizador | Renderizador | El renderizador |
| commandList | ICommandList | La commandList utilizada para registrar los comandos de renderizado |
| nodo | Nodo | El mismo nodo que se pasó a PrepareRenderQueue de la entidad que será renderizada |
| renderableResource | Objeto | El objeto personalizado que se pasó a IRenderQueue durante el PrepareRenderQueue |
| subEntity | Número | El índice del sub entity que se pasó a IRenderQueue |

 **Result:**



---


### dispose{#dispose}

| Nombre | Descripción |
| --- | --- |
| dispose() | El renderizador de entidad se está disponiendo, libere los recursos compartidos. |

 **Result:**



---



