---
title: EntityRenderer
second_title: Referencia de API de Aspose.3D para Java
description: Cree una subclase de esto para implementar el renderizado de diferentes tipos de entidades.
type: docs
weight: 53
url: /es/java/com.aspose.threed/entityrenderer/
---

**Inheritance:**
java.lang.Object
```
public class EntityRenderer
```

Cree una subclase de esto para implementar el renderizado de diferentes tipos de entidades.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EntityRenderer(String key, byte features)](#EntityRenderer-java.lang.String-byte-) | Constructor de [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| [EntityRenderer(String key)](#EntityRenderer-java.lang.String-) | Constructor de [EntityRenderer](../../com.aspose.threed/entityrenderer) |
## Métodos

| Método | Descripción |
| --- | --- |
| [dispose()](#dispose--) | El renderizador de entidad se está eliminando, libere los recursos compartidos. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [frameBegin(Renderer renderer, IRenderQueue renderQueue)](#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Iniciar el renderizado de un fotograma |
| [frameEnd(Renderer renderer, IRenderQueue renderQueue)](#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Finaliza el renderizado de un fotograma |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [initialize(Renderer renderer)](#initialize-com.aspose.threed.Renderer-) | Inicializar el renderizador de entidad |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity)](#prepareRenderQueue-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-com.aspose.threed.Node-com.aspose.threed.Entity-) | Preparar comandos de renderizado para el par nodo/entidad especificado. |
| [renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)](#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-) | Cada tarea de renderizado enviada a la [IRenderQueue](../../com.aspose.threed/irenderqueue) tendrá una llamada RenderEntity correspondiente para ejecutar el trabajo de renderizado concreto. |
| [resetSceneCache()](#resetSceneCache--) | La escena ha cambiado o se ha eliminado, es necesario disponer de los recursos de renderizado a nivel de escena en este caso |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EntityRenderer(String key, byte features) {#EntityRenderer-java.lang.String-byte-}
```
public EntityRenderer(String key, byte features)
```


Constructor de [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | java.lang.String | La clave del renderizador de entidad |
| características | byte | Las características extra del renderizador de entidad |

### EntityRenderer(String key) {#EntityRenderer-java.lang.String-}
```
public EntityRenderer(String key)
```


Constructor de [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clave | java.lang.String | La clave del renderizador de entidad |

### dispose() {#dispose--}
```
public void dispose()
```


El renderizador de entidad se está eliminando, libere los recursos compartidos.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### frameBegin(Renderer renderer, IRenderQueue renderQueue) {#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameBegin(Renderer renderer, IRenderQueue renderQueue)
```


Iniciar el renderizado de un fotograma

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Renderizador actual |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Cola de renderizado |

### frameEnd(Renderer renderer, IRenderQueue renderQueue) {#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameEnd(Renderer renderer, IRenderQueue renderQueue)
```


Finaliza el renderizado de un fotograma

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Renderizador actual |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Cola de renderizado |

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


Inicializar el renderizador de entidad

**Parameters:**
| Parámetro | Tipo | Descripción |
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


Preparar comandos de renderizado para el par nodo/entidad especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | La instancia actual del renderizador |
| queue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | La cola de renderizado utilizada para gestionar tareas de renderizado |
| node | [Node](../../com.aspose.threed/node) | Nodo actual |
| entity | [Entity](../../com.aspose.threed/entity) | La entidad que necesita ser renderizada |

### renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity) {#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-}
```
public void renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)
```


Cada tarea de renderizado enviada a la [IRenderQueue](../../com.aspose.threed/irenderqueue) tendrá una llamada RenderEntity correspondiente para ejecutar el trabajo de renderizado concreto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | El renderizador |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) | La commandList utilizada para registrar los comandos de renderizado |
| node | [Node](../../com.aspose.threed/node) | El mismo nodo que se pasó a PrepareRenderQueue de la entidad que será renderizada |
| renderableResource | java.lang.Object | El objeto personalizado que se pasó a IRenderQueue durante el PrepareRenderQueue |
| subEntity | int | El índice de la subentidad que se pasó a IRenderQueue |

### resetSceneCache() {#resetSceneCache--}
```
public void resetSceneCache()
```


La escena ha cambiado o se ha eliminado, es necesario disponer de los recursos de renderizado a nivel de escena en este caso

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

