---
title: EntityRenderer
second_title: Aspose.3D for Java API Reference
description: Κληρονομήστε αυτήν την κλάση για να υλοποιήσετε την απόδοση διαφορετικών τύπων οντοτήτων.
type: docs
weight: 53
url: /el/java/com.aspose.threed/entityrenderer/
---

**Inheritance:**
java.lang.Object
```
public class EntityRenderer
```

Κληρονομήστε αυτήν την κλάση για να υλοποιήσετε την απόδοση διαφορετικών τύπων οντοτήτων.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [EntityRenderer(String key, byte features)](#EntityRenderer-java.lang.String-byte-) | Constructor of [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| [EntityRenderer(String key)](#EntityRenderer-java.lang.String-) | Constructor of [EntityRenderer](../../com.aspose.threed/entityrenderer) |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [dispose()](#dispose--) | Ο renderer της οντότητας διαγράφεται, απελευθερώστε τους κοινόχρηστους πόρους. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [frameBegin(Renderer renderer, IRenderQueue renderQueue)](#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Begin rendering a frame |
| [frameEnd(Renderer renderer, IRenderQueue renderQueue)](#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Ends rendering a frame |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [initialize(Renderer renderer)](#initialize-com.aspose.threed.Renderer-) | Initialize the entity renderer |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity)](#prepareRenderQueue-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-com.aspose.threed.Node-com.aspose.threed.Entity-) | Prepare rendering commands for specified node/entity pair. |
| [renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)](#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-) | Each render task pushed to the [IRenderQueue](../../com.aspose.threed/irenderqueue) will have a corresponding RenderEntity call to perform the concrete rendering job. |
| [resetSceneCache()](#resetSceneCache--) | The scene has changed or removed, need to dispose scene-level render resources in this |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EntityRenderer(String key, byte features) {#EntityRenderer-java.lang.String-byte-}
```
public EntityRenderer(String key, byte features)
```


Constructor of [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | java.lang.String | Το κλειδί του entity renderer |
| χαρακτηριστικά | byte | The extra features of the entity renderer |

### EntityRenderer(String key) {#EntityRenderer-java.lang.String-}
```
public EntityRenderer(String key)
```


Constructor of [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | java.lang.String | Το κλειδί του entity renderer |

### dispose() {#dispose--}
```
public void dispose()
```


Ο renderer της οντότητας διαγράφεται, απελευθερώστε τους κοινόχρηστους πόρους.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### frameBegin(Renderer renderer, IRenderQueue renderQueue) {#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameBegin(Renderer renderer, IRenderQueue renderQueue)
```


Begin rendering a frame

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Current renderer |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Render queue |

### frameEnd(Renderer renderer, IRenderQueue renderQueue) {#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameEnd(Renderer renderer, IRenderQueue renderQueue)
```


Ends rendering a frame

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Current renderer |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Render queue |

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


Initialize the entity renderer

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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


Prepare rendering commands for specified node/entity pair.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | The current renderer instance |
| queue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | The render queue used to manage render tasks |
| node | [Node](../../com.aspose.threed/node) | Current node |
| entity | [Entity](../../com.aspose.threed/entity) | The entity that need to be rendered |

### renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity) {#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-}
```
public void renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)
```


Each render task pushed to the [IRenderQueue](../../com.aspose.threed/irenderqueue) will have a corresponding RenderEntity call to perform the concrete rendering job.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Ο renderer |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) | Η commandList που χρησιμοποιείται για την καταγραφή των εντολών απόδοσης |
| node | [Node](../../com.aspose.threed/node) | Ο ίδιος κόμβος που περάστηκε στο PrepareRenderQueue της οντότητας που θα αποδοθεί |
| renderableResource | java.lang.Object | Το προσαρμοσμένο αντικείμενο που περάστηκε στο IRenderQueue κατά τη διάρκεια του PrepareRenderQueue |
| subEntity | int | Το ευρετήριο της υποοντότητας που περάστηκε στο IRenderQueue |

### resetSceneCache() {#resetSceneCache--}
```
public void resetSceneCache()
```


The scene has changed or removed, need to dispose scene-level render resources in this

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

