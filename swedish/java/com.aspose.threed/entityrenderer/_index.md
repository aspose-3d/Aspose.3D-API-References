---
title: EntityRenderer
second_title: Aspose.3D for Java API-referens
description: Skapa en underklass av detta för att implementera rendering för olika typer av entiteter.
type: docs
weight: 53
url: /sv/java/com.aspose.threed/entityrenderer/
---

**Inheritance:**
java.lang.Object
```
public class EntityRenderer
```

Skapa en underklass av detta för att implementera rendering för olika typer av entiteter.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EntityRenderer(String key, byte features)](#EntityRenderer-java.lang.String-byte-) | Konstruktor för [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| [EntityRenderer(String key)](#EntityRenderer-java.lang.String-) | Konstruktor för [EntityRenderer](../../com.aspose.threed/entityrenderer) |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [dispose()](#dispose--) | EntityRenderer avyttras, frigör delade resurser. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [frameBegin(Renderer renderer, IRenderQueue renderQueue)](#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Börja rendera en ram |
| [frameEnd(Renderer renderer, IRenderQueue renderQueue)](#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Avslutar rendera en ram |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [initialize(Renderer renderer)](#initialize-com.aspose.threed.Renderer-) | Initiera EntityRenderer |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity)](#prepareRenderQueue-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-com.aspose.threed.Node-com.aspose.threed.Entity-) | Förbered renderingskommandon för angivet nod/entity-par. |
| [renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)](#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-) | Varje renderingsuppgift som läggs till i [IRenderQueue](../../com.aspose.threed/irenderqueue) kommer att ha ett motsvarande RenderEntity-anrop för att utföra det konkreta renderingsjobbet. |
| [resetSceneCache()](#resetSceneCache--) | Scenen har ändrats eller tagits bort, behöver avyttra renderingsresurser på scennivå i detta. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EntityRenderer(String key, byte features) {#EntityRenderer-java.lang.String-byte-}
```
public EntityRenderer(String key, byte features)
```


Konstruktor för [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Nyckeln för entitetsrenderaren |
| funktioner | byte | De extra funktionerna för entitetsrenderaren |

### EntityRenderer(String key) {#EntityRenderer-java.lang.String-}
```
public EntityRenderer(String key)
```


Konstruktor för [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyckel | java.lang.String | Nyckeln för entitetsrenderaren |

### dispose() {#dispose--}
```
public void dispose()
```


EntityRenderer avyttras, frigör delade resurser.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### frameBegin(Renderer renderer, IRenderQueue renderQueue) {#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameBegin(Renderer renderer, IRenderQueue renderQueue)
```


Börja rendera en ram

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Aktuell renderare |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Renderingskö |

### frameEnd(Renderer renderer, IRenderQueue renderQueue) {#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameEnd(Renderer renderer, IRenderQueue renderQueue)
```


Avslutar rendera en ram

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Aktuell renderare |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Renderingskö |

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


Initiera EntityRenderer

**Parameters:**
| Parameter | Typ | Beskrivning |
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


Förbered renderingskommandon för angivet nod/entity-par.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Den aktuella renderarinstansen |
| queue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Renderingskön som används för att hantera renderingsuppgifter |
| node | [Node](../../com.aspose.threed/node) | Aktuell nod |
| entity | [Entity](../../com.aspose.threed/entity) | Entiteten som behöver renderas |

### renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity) {#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-}
```
public void renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)
```


Varje renderingsuppgift som läggs till i [IRenderQueue](../../com.aspose.threed/irenderqueue) kommer att ha ett motsvarande RenderEntity-anrop för att utföra det konkreta renderingsjobbet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Renderaren |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) | commandList som används för att spela in renderingskommandona |
| node | [Node](../../com.aspose.threed/node) | Samma nod som skickades till PrepareRenderQueue för entiteten som kommer att renderas |
| renderableResource | java.lang.Object | Det anpassade objektet som skickades till IRenderQueue under PrepareRenderQueue |
| subEntity | int | Indexet för subentiteten som skickades till IRenderQueue |

### resetSceneCache() {#resetSceneCache--}
```
public void resetSceneCache()
```


Scenen har ändrats eller tagits bort, behöver avyttra renderingsresurser på scennivå i detta.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

