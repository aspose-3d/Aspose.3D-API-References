---
title: "EntityRenderer"
second_title: "Aspose.3D for Java API Reference"
description: "विभिन्न प्रकार की इकाइयों के लिए रेंडरिंग लागू करने हेतु इसे सबक्लास करें।"
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
## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [EntityRenderer(String key, byte features)](#EntityRenderer-java.lang.String-byte-) | [EntityRenderer](../../com.aspose.threed/entityrenderer) का कंस्ट्रक्टर |
| [EntityRenderer(String key)](#EntityRenderer-java.lang.String-) | [EntityRenderer](../../com.aspose.threed/entityrenderer) का कंस्ट्रक्टर |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [dispose()](#dispose--) | एंटिटी रेंडरर को नष्ट किया जा रहा है, साझा संसाधनों को रिलीज़ करें। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [frameBegin(Renderer renderer, IRenderQueue renderQueue)](#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | फ़्रेम रेंडरिंग शुरू करें |
| [frameEnd(Renderer renderer, IRenderQueue renderQueue)](#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | फ़्रेम रेंडरिंग समाप्त करता है |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [initialize(Renderer renderer)](#initialize-com.aspose.threed.Renderer-) | एंटिटी रेंडरर को इनिशियलाइज़ करें |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity)](#prepareRenderQueue-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-com.aspose.threed.Node-com.aspose.threed.Entity-) | निर्दिष्ट नोड/एंटिटी जोड़ी के लिए रेंडरिंग कमांड तैयार करें। |
| [renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)](#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-) | प्रत्येक रेंडर टास्क जो [IRenderQueue](../../com.aspose.threed/irenderqueue) में पुश किया जाता है, उसके पास एक संबंधित RenderEntity कॉल होगा जो ठोस रेंडरिंग कार्य को निष्पादित करेगा। |
| [resetSceneCache()](#resetSceneCache--) | दृश्य बदल गया है या हटाया गया है, इस में सीन-स्तर के रेंडर संसाधनों को नष्ट करने की आवश्यकता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EntityRenderer(String key, byte features) {#EntityRenderer-java.lang.String-byte-}
```
public EntityRenderer(String key, byte features)
```


[EntityRenderer](../../com.aspose.threed/entityrenderer) का कंस्ट्रक्टर

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| कुंजी | java.lang.String | एंटिटी रेंडरर की कुंजी |
| विशेषताएँ | बाइट | एंटिटी रेंडरर की अतिरिक्त विशेषताएँ |

### EntityRenderer(String key) {#EntityRenderer-java.lang.String-}
```
public EntityRenderer(String key)
```


[EntityRenderer](../../com.aspose.threed/entityrenderer) का कंस्ट्रक्टर

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| कुंजी | java.lang.String | एंटिटी रेंडरर की कुंजी |

### dispose() {#dispose--}
```
public void dispose()
```


एंटिटी रेंडरर को नष्ट किया जा रहा है, साझा संसाधनों को रिलीज़ करें।

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### frameBegin(Renderer renderer, IRenderQueue renderQueue) {#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameBegin(Renderer renderer, IRenderQueue renderQueue)
```


फ़्रेम रेंडरिंग शुरू करें

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | वर्तमान रेंडरर |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | रेंडर कतार |

### frameEnd(Renderer renderer, IRenderQueue renderQueue) {#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameEnd(Renderer renderer, IRenderQueue renderQueue)
```


फ़्रेम रेंडरिंग समाप्त करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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


एंटिटी रेंडरर को इनिशियलाइज़ करें

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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


निर्दिष्ट नोड/एंटिटी जोड़ी के लिए रेंडरिंग कमांड तैयार करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | वर्तमान रेंडरर इंस्टेंस |
| queue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | रेंडर कार्यों को प्रबंधित करने के लिए उपयोग की जाने वाली रेंडर कतार |
| node | [Node](../../com.aspose.threed/node) | वर्तमान नोड |
| entity | [Entity](../../com.aspose.threed/entity) | वह एंटिटी जिसे रेंडर किया जाना है |

### renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity) {#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-}
```
public void renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)
```


प्रत्येक रेंडर टास्क जो [IRenderQueue](../../com.aspose.threed/irenderqueue) में पुश किया जाता है, उसके पास एक संबंधित RenderEntity कॉल होगा जो ठोस रेंडरिंग कार्य को निष्पादित करेगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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


दृश्य बदल गया है या हटाया गया है, इस में सीन-स्तर के रेंडर संसाधनों को नष्ट करने की आवश्यकता है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

