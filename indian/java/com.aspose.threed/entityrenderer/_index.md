---
title: EntityRenderer
second_title: Aspose.3D for Java API Reference
description: विभिन्न प्रकार की इकाइयों के लिए रेंडरिंग लागू करने हेतु इसे सबक्लास करें।
type: docs
weight: 53
url: /hi/java/com.aspose.threed/entityrenderer/
---

**Inheritance:**
java.lang.Object
```
public class EntityRenderer
```

विभिन्न प्रकार की इकाइयों के लिए रेंडरिंग लागू करने हेतु इसे सबक्लास करें।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [EntityRenderer(String key, byte features)](#EntityRenderer-java.lang.String-byte-) | Constructor of [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| [EntityRenderer(String key)](#EntityRenderer-java.lang.String-) | Constructor of [EntityRenderer](../../com.aspose.threed/entityrenderer) |
## Methods

| Method | विवरण |
| --- | --- |
| [dispose()](#dispose--) | The entity renderer is being disposed, release shared resources. |
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
| Parameter | Type | विवरण |
| --- | --- | --- |
| कुंजी | java.lang.String | एंटिटी रेंडरर की कुंजी |
| विशेषताएँ | बाइट | एंटिटी रेंडरर की अतिरिक्त विशेषताएँ |

### EntityRenderer(String key) {#EntityRenderer-java.lang.String-}
```
public EntityRenderer(String key)
```


Constructor of [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| कुंजी | java.lang.String | एंटिटी रेंडरर की कुंजी |

### dispose() {#dispose--}
```
public void dispose()
```


The entity renderer is being disposed, release shared resources.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
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
| Parameter | Type | विवरण |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | वर्तमान रेंडरर |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | रेंडर कतार |

### frameEnd(Renderer renderer, IRenderQueue renderQueue) {#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameEnd(Renderer renderer, IRenderQueue renderQueue)
```


Ends rendering a frame

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | वर्तमान रेंडरर |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | रेंडर कतार |

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
| Parameter | Type | विवरण |
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
| Parameter | Type | विवरण |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | वर्तमान रेंडरर इंस्टेंस |
| queue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | रेंडर कार्यों को प्रबंधित करने के लिए उपयोग की जाने वाली रेंडर कतार |
| node | [Node](../../com.aspose.threed/node) | वर्तमान नोड |
| entity | [Entity](../../com.aspose.threed/entity) | वह एंटिटी जिसे रेंडर किया जाना है |

### renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity) {#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-}
```
public void renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)
```


Each render task pushed to the [IRenderQueue](../../com.aspose.threed/irenderqueue) will have a corresponding RenderEntity call to perform the concrete rendering job.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | रेंडरर |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) | रेंडरिंग कमांड्स को रिकॉर्ड करने के लिए उपयोग किया गया कमांडलिस्ट |
| node | [Node](../../com.aspose.threed/node) | वही नोड जो रेंडर की जाने वाली एंटिटी की PrepareRenderQueue को पास किया गया |
| renderableResource | java.lang.Object | कस्टम ऑब्जेक्ट जो PrepareRenderQueue के दौरान IRenderQueue को पास किया गया |
| subEntity | int | सब एंटिटी का इंडेक्स जो IRenderQueue को पास किया गया |

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

