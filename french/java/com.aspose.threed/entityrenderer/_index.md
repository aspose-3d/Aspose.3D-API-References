---
title: "EntityRenderer"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Sous-classez ceci pour implémenter le rendu pour différents types d'entités."
type: docs
weight: 53
url: /fr/java/com.aspose.threed/entityrenderer/
---

**Inheritance:**
java.lang.Object
```
public class EntityRenderer
```

Sous-classez ceci pour implémenter le rendu pour différents types d'entités.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EntityRenderer(String key, byte features)](#EntityRenderer-java.lang.String-byte-) | Constructeur de [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| [EntityRenderer(String key)](#EntityRenderer-java.lang.String-) | Constructeur de [EntityRenderer](../../com.aspose.threed/entityrenderer) |
## Méthodes

| Méthode | Description |
| --- | --- |
| [dispose()](#dispose--) | Le entity renderer est en cours de libération, libérez les ressources partagées. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [frameBegin(Renderer renderer, IRenderQueue renderQueue)](#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Commencer le rendu d'une image |
| [frameEnd(Renderer renderer, IRenderQueue renderQueue)](#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Termine le rendu d'une image |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [initialize(Renderer renderer)](#initialize-com.aspose.threed.Renderer-) | Initialiser le entity renderer |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity)](#prepareRenderQueue-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-com.aspose.threed.Node-com.aspose.threed.Entity-) | Préparer les commandes de rendu pour la paire nœud/entité spécifiée. |
| [renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)](#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-) | Chaque tâche de rendu poussée dans la [IRenderQueue](../../com.aspose.threed/irenderqueue) aura un appel RenderEntity correspondant pour exécuter le travail de rendu concret. |
| [resetSceneCache()](#resetSceneCache--) | La scène a changé ou a été supprimée, il faut libérer les ressources de rendu au niveau de la scène dans ce cas. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EntityRenderer(String key, byte features) {#EntityRenderer-java.lang.String-byte-}
```
public EntityRenderer(String key, byte features)
```


Constructeur de [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La clé du rendu d'entité |
| fonctionnalités | octet | Les fonctionnalités supplémentaires du rendu d'entité |

### EntityRenderer(String key) {#EntityRenderer-java.lang.String-}
```
public EntityRenderer(String key)
```


Constructeur de [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clé | java.lang.String | La clé du rendu d'entité |

### dispose() {#dispose--}
```
public void dispose()
```


Le entity renderer est en cours de libération, libérez les ressources partagées.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### frameBegin(Renderer renderer, IRenderQueue renderQueue) {#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameBegin(Renderer renderer, IRenderQueue renderQueue)
```


Commencer le rendu d'une image

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Rendu actuel |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | File d'attente de rendu |

### frameEnd(Renderer renderer, IRenderQueue renderQueue) {#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameEnd(Renderer renderer, IRenderQueue renderQueue)
```


Termine le rendu d'une image

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Rendu actuel |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | File d'attente de rendu |

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


Initialiser le entity renderer

**Parameters:**
| Paramètre | Type | Description |
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


Préparer les commandes de rendu pour la paire nœud/entité spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | L'instance du rendu actuel |
| queue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | La file d'attente de rendu utilisée pour gérer les tâches de rendu |
| node | [Node](../../com.aspose.threed/node) | Nœud actuel |
| entity | [Entity](../../com.aspose.threed/entity) | L'entité qui doit être rendue |

### renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity) {#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-}
```
public void renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)
```


Chaque tâche de rendu poussée dans la [IRenderQueue](../../com.aspose.threed/irenderqueue) aura un appel RenderEntity correspondant pour exécuter le travail de rendu concret.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Le moteur de rendu |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) | La commandList utilisée pour enregistrer les commandes de rendu |
| node | [Node](../../com.aspose.threed/node) | Le même nœud qui a été passé à PrepareRenderQueue de l'entité qui sera rendue |
| renderableResource | java.lang.Object | L'objet personnalisé qui a été passé à IRenderQueue pendant le PrepareRenderQueue |
| subEntity | int | L'index de la sous‑entité qui a été passé à IRenderQueue |

### resetSceneCache() {#resetSceneCache--}
```
public void resetSceneCache()
```


La scène a changé ou a été supprimée, il faut libérer les ressources de rendu au niveau de la scène dans ce cas.

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

