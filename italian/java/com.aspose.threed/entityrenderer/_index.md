---
title: EntityRenderer
second_title: Aspose.3D for Java API Reference
description: Crea una sottoclasse di questa per implementare il rendering per diversi tipi di entità.
type: docs
weight: 53
url: /it/java/com.aspose.threed/entityrenderer/
---

**Inheritance:**
java.lang.Object
```
public class EntityRenderer
```

Crea una sottoclasse di questa per implementare il rendering per diversi tipi di entità.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EntityRenderer(String key, byte features)](#EntityRenderer-java.lang.String-byte-) | Costruttore di [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| [EntityRenderer(String key)](#EntityRenderer-java.lang.String-) | Costruttore di [EntityRenderer](../../com.aspose.threed/entityrenderer) |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [dispose()](#dispose--) | Il renderer dell'entità è in fase di smaltimento, rilascia le risorse condivise. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [frameBegin(Renderer renderer, IRenderQueue renderQueue)](#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Inizia il rendering di un fotogramma |
| [frameEnd(Renderer renderer, IRenderQueue renderQueue)](#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Termina il rendering di un fotogramma |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [initialize(Renderer renderer)](#initialize-com.aspose.threed.Renderer-) | Inizializza il renderer dell'entità |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity)](#prepareRenderQueue-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-com.aspose.threed.Node-com.aspose.threed.Entity-) | Prepara i comandi di rendering per la coppia nodo/entità specificata. |
| [renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)](#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-) | Ogni attività di rendering inviata alla [IRenderQueue](../../com.aspose.threed/irenderqueue) avrà una chiamata RenderEntity corrispondente per eseguire il lavoro di rendering concreto. |
| [resetSceneCache()](#resetSceneCache--) | La scena è cambiata o rimossa, è necessario liberare le risorse di rendering a livello di scena in questo |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EntityRenderer(String key, byte features) {#EntityRenderer-java.lang.String-byte-}
```
public EntityRenderer(String key, byte features)
```


Costruttore di [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chiave | java.lang.String | La chiave del renderer dell'entità |
| funzionalità | byte | Le funzionalità aggiuntive del renderer dell'entità |

### EntityRenderer(String key) {#EntityRenderer-java.lang.String-}
```
public EntityRenderer(String key)
```


Costruttore di [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chiave | java.lang.String | La chiave del renderer dell'entità |

### dispose() {#dispose--}
```
public void dispose()
```


Il renderer dell'entità è in fase di smaltimento, rilascia le risorse condivise.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### frameBegin(Renderer renderer, IRenderQueue renderQueue) {#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameBegin(Renderer renderer, IRenderQueue renderQueue)
```


Inizia il rendering di un fotogramma

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Renderer corrente |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Coda di rendering |

### frameEnd(Renderer renderer, IRenderQueue renderQueue) {#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameEnd(Renderer renderer, IRenderQueue renderQueue)
```


Termina il rendering di un fotogramma

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Renderer corrente |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Coda di rendering |

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


Inizializza il renderer dell'entità

**Parameters:**
| Parametro | Tipo | Descrizione |
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


Prepara i comandi di rendering per la coppia nodo/entità specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | L'istanza corrente del renderer |
| queue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | La coda di rendering utilizzata per gestire le attività di rendering |
| node | [Node](../../com.aspose.threed/node) | Nodo corrente |
| entity | [Entity](../../com.aspose.threed/entity) | L'entità che deve essere renderizzata |

### renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity) {#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-}
```
public void renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)
```


Ogni attività di rendering inviata alla [IRenderQueue](../../com.aspose.threed/irenderqueue) avrà una chiamata RenderEntity corrispondente per eseguire il lavoro di rendering concreto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Il renderer |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) | La commandList usata per registrare i comandi di rendering |
| node | [Node](../../com.aspose.threed/node) | Lo stesso nodo passato a PrepareRenderQueue dell'entità che verrà renderizzata |
| renderableResource | java.lang.Object | L'oggetto personalizzato passato a IRenderQueue durante il PrepareRenderQueue |
| subEntity | int | L'indice della sottoentità passata a IRenderQueue |

### resetSceneCache() {#resetSceneCache--}
```
public void resetSceneCache()
```


La scena è cambiata o rimossa, è necessario liberare le risorse di rendering a livello di scena in questo

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

