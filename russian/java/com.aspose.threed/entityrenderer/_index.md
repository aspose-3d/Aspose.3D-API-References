---
title: EntityRenderer
second_title: Справочник API Aspose.3D для Java
description: Наследуйте этот класс, чтобы реализовать рендеринг для разных типов сущностей.
type: docs
weight: 53
url: /ru/java/com.aspose.threed/entityrenderer/
---

**Inheritance:**
java.lang.Object
```
public class EntityRenderer
```

Наследуйте этот класс, чтобы реализовать рендеринг для разных типов сущностей.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EntityRenderer(String key, byte features)](#EntityRenderer-java.lang.String-byte-) | Конструктор [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| [EntityRenderer(String key)](#EntityRenderer-java.lang.String-) | Конструктор [EntityRenderer](../../com.aspose.threed/entityrenderer) |
## Методы

| Метод | Описание |
| --- | --- |
| [dispose()](#dispose--) | Рендерер сущностей освобождается, освобождая общие ресурсы. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [frameBegin(Renderer renderer, IRenderQueue renderQueue)](#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Начать рендеринг кадра |
| [frameEnd(Renderer renderer, IRenderQueue renderQueue)](#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Завершить рендеринг кадра |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [initialize(Renderer renderer)](#initialize-com.aspose.threed.Renderer-) | Инициализировать рендерер сущностей |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity)](#prepareRenderQueue-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-com.aspose.threed.Node-com.aspose.threed.Entity-) | Подготовить команды рендеринга для указанной пары node/entity. |
| [renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)](#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-) | Каждая задача рендеринга, помещённая в [IRenderQueue](../../com.aspose.threed/irenderqueue), будет иметь соответствующий вызов RenderEntity для выполнения конкретной задачи рендеринга. |
| [resetSceneCache()](#resetSceneCache--) | Сцена изменена или удалена, необходимо освободить ресурсы рендеринга уровня сцены в этом |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EntityRenderer(String key, byte features) {#EntityRenderer-java.lang.String-byte-}
```
public EntityRenderer(String key, byte features)
```


Конструктор [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | java.lang.String | Ключ рендерера сущности |
| функции | байт | Дополнительные функции рендерера сущности |

### EntityRenderer(String key) {#EntityRenderer-java.lang.String-}
```
public EntityRenderer(String key)
```


Конструктор [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | java.lang.String | Ключ рендерера сущности |

### dispose() {#dispose--}
```
public void dispose()
```


Рендерер сущностей освобождается, освобождая общие ресурсы.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### frameBegin(Renderer renderer, IRenderQueue renderQueue) {#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameBegin(Renderer renderer, IRenderQueue renderQueue)
```


Начать рендеринг кадра

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Текущий рендерер |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Очередь рендеринга |

### frameEnd(Renderer renderer, IRenderQueue renderQueue) {#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameEnd(Renderer renderer, IRenderQueue renderQueue)
```


Завершить рендеринг кадра

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Текущий рендерер |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Очередь рендеринга |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initialize(Renderer renderer) {#initialize-com.aspose.threed.Renderer-}
```
public void initialize(Renderer renderer)
```


Инициализировать рендерер сущностей

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) |  |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity) {#prepareRenderQueue-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-com.aspose.threed.Node-com.aspose.threed.Entity-}
```
public void prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity)
```


Подготовить команды рендеринга для указанной пары node/entity.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Экземпляр текущего рендерера |
| queue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Очередь рендеринга, используемая для управления задачами рендеринга |
| node | [Node](../../com.aspose.threed/node) | Текущий узел |
| entity | [Entity](../../com.aspose.threed/entity) | Сущность, которую необходимо отрисовать |

### renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity) {#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-}
```
public void renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)
```


Каждая задача рендеринга, помещённая в [IRenderQueue](../../com.aspose.threed/irenderqueue), будет иметь соответствующий вызов RenderEntity для выполнения конкретной задачи рендеринга.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Рендерер |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) | Список команд, используемый для записи команд рендеринга |
| node | [Node](../../com.aspose.threed/node) | Тот же узел, который передан в PrepareRenderQueue сущности, которая будет отрисована |
| renderableResource | java.lang.Object | Пользовательский объект, переданный в IRenderQueue во время PrepareRenderQueue |
| subEntity | int | Индекс подсущности, переданный в IRenderQueue |

### resetSceneCache() {#resetSceneCache--}
```
public void resetSceneCache()
```


Сцена изменена или удалена, необходимо освободить ресурсы рендеринга уровня сцены в этом

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

