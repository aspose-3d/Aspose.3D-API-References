---
title: "EntityRenderer"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/entityrenderer/
---
## EntityRenderer class

Создайте подкласс, чтобы реализовать рендеринг для различных типов сущностей.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor(key, features) | Конструктор EntityRenderer |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| key | String | Ключ рендерера сущности |
| features | byte | EntityRendererFeatures |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(key) | Конструктор EntityRenderer |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| key | String | Ключ рендерера сущности |

 **Result:**



---


### initialize{#initialize}

| Имя | Описание |
| --- | --- |
| initialize(renderer) | Инициализировать рендерер сущности |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| rendere | Renderer | null |

 **Result:**



---


### resetSceneCache{#resetSceneCache}

| Имя | Описание |
| --- | --- |
| resetSceneCache() | Сцена была изменена или удалена, необходимо освободить ресурсы рендеринга уровня сцены в этом |

 **Result:**



---


### frameBegin{#frameBegin}

| Имя | Описание |
| --- | --- |
| frameBegin(renderer, renderQueue) | Начать рендеринг кадра |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| renderer | Renderer | Текущий renderer |
| renderQueue | IRenderQueue | Очередь рендеринга |

 **Result:**



---


### frameEnd{#frameEnd}

| Имя | Описание |
| --- | --- |
| frameEnd(renderer, renderQueue) | Завершает рендеринг кадра |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| renderer | Renderer | Текущий renderer |
| renderQueue | IRenderQueue | Очередь рендеринга |

 **Result:**



---


### prepareRenderQueue{#prepareRenderQueue}

| Имя | Описание |
| --- | --- |
| prepareRenderQueue(renderer, queue, node, entity) | Подготовить команды рендеринга для указанной пары node/entity. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| renderer | Renderer | Текущий экземпляр renderer |
| queue | IRenderQueue | Очередь рендеринга, используемая для управления задачами рендеринга |
| node | Node | Текущий node |
| entity | Entity | entity, которую необходимо отрендерить |

 **Result:**



---


### renderEntity{#renderEntity}

| Имя | Описание |
| --- | --- |
| renderEntity(renderer, commandList, node, renderableResource, subEntity) | Каждая задача рендеринга, отправленная в com.aspose.threed.IRenderQueue, будет иметь соответствующий вызов RenderEntity для выполнения конкретной задачи рендеринга. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| renderer | Renderer | Рендерер |
| commandList | ICommandList | commandList, используемый для записи команд рендеринга |
| node | Node | Тот же узел, который передан в PrepareRenderQueue сущности, которая будет отрисована |
| renderableResource | Object | Пользовательский объект, переданный в IRenderQueue во время PrepareRenderQueue |
| subEntity | Number | Индекс под‑сущности, переданный в IRenderQueue |

 **Result:**



---


### dispose{#dispose}

| Имя | Описание |
| --- | --- |
| dispose() | Рендерер сущности освобождается, освобождая общие ресурсы. |

 **Result:**



---



