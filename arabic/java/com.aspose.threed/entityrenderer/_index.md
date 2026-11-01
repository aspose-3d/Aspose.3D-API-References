---
title: "EntityRenderer"
second_title: "مرجع Aspose.3D لـ Java API"
description: "قم بإنشاء فئة فرعية من هذا لتنفيذ العرض لأنواع مختلفة من الكيانات."
type: docs
weight: 53
url: /ar/java/com.aspose.threed/entityrenderer/
---

**Inheritance:**
java.lang.Object
```
public class EntityRenderer
```

قم بإنشاء فئة فرعية من هذا لتنفيذ العرض لأنواع مختلفة من الكيانات.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [EntityRenderer(String key, byte features)](#EntityRenderer-java.lang.String-byte-) | منشئ [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| [EntityRenderer(String key)](#EntityRenderer-java.lang.String-) | منشئ [EntityRenderer](../../com.aspose.threed/entityrenderer) |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [dispose()](#dispose--) | يتم التخلص من معالج الكيان، وإطلاق الموارد المشتركة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [frameBegin(Renderer renderer, IRenderQueue renderQueue)](#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | بدء عرض إطار |
| [frameEnd(Renderer renderer, IRenderQueue renderQueue)](#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | إنهاء عرض إطار |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [initialize(Renderer renderer)](#initialize-com.aspose.threed.Renderer-) | تهيئة معالج الكيان |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity)](#prepareRenderQueue-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-com.aspose.threed.Node-com.aspose.threed.Entity-) | تحضير أوامر العرض للزوج المحدد من العقدة/الكيان. |
| [renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)](#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-) | كل مهمة عرض تُدفع إلى [IRenderQueue](../../com.aspose.threed/irenderqueue) ستحصل على استدعاء RenderEntity المقابل لتنفيذ مهمة العرض الفعلية. |
| [resetSceneCache()](#resetSceneCache--) | المشهد قد تغير أو أُزيل، تحتاج إلى التخلص من موارد العرض على مستوى المشهد في هذا |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EntityRenderer(String key, byte features) {#EntityRenderer-java.lang.String-byte-}
```
public EntityRenderer(String key, byte features)
```


منشئ [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | المفتاح الخاص بمُعالج الكيان |
| الميزات | بايت | الميزات الإضافية لمُعالج الكيان |

### EntityRenderer(String key) {#EntityRenderer-java.lang.String-}
```
public EntityRenderer(String key)
```


منشئ [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المفتاح | java.lang.String | المفتاح الخاص بمُعالج الكيان |

### dispose() {#dispose--}
```
public void dispose()
```


يتم التخلص من معالج الكيان، وإطلاق الموارد المشتركة.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### frameBegin(Renderer renderer, IRenderQueue renderQueue) {#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameBegin(Renderer renderer, IRenderQueue renderQueue)
```


بدء عرض إطار

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | المُعالج الحالي |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | قائمة انتظار التصيير |

### frameEnd(Renderer renderer, IRenderQueue renderQueue) {#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameEnd(Renderer renderer, IRenderQueue renderQueue)
```


إنهاء عرض إطار

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | المُعالج الحالي |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | قائمة انتظار التصيير |

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


تهيئة معالج الكيان

**Parameters:**
| معامل | نوع | الوصف |
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


تحضير أوامر العرض للزوج المحدد من العقدة/الكيان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | مثيل المُعالج الحالي |
| queue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | قائمة انتظار التصيير المستخدمة لإدارة مهام التصيير |
| node | [Node](../../com.aspose.threed/node) | العقدة الحالية |
| entity | [Entity](../../com.aspose.threed/entity) | الكيان الذي يحتاج إلى التصيير |

### renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity) {#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-}
```
public void renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)
```


كل مهمة عرض تُدفع إلى [IRenderQueue](../../com.aspose.threed/irenderqueue) ستحصل على استدعاء RenderEntity المقابل لتنفيذ مهمة العرض الفعلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | المُعالج |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) | قائمة الأوامر commandList المستخدمة لتسجيل أوامر التصيير |
| node | [Node](../../com.aspose.threed/node) | العقدة نفسها التي تم تمريرها إلى PrepareRenderQueue للكيان الذي سيتم تصييره |
| renderableResource | java.lang.Object | الكائن المخصص الذي تم تمريره إلى IRenderQueue أثناء PrepareRenderQueue |
| الكيان الفرعي | int | فهرس الكيان الفرعي الذي تم تمريره إلى IRenderQueue |

### resetSceneCache() {#resetSceneCache--}
```
public void resetSceneCache()
```


المشهد قد تغير أو أُزيل، تحتاج إلى التخلص من موارد العرض على مستوى المشهد في هذا

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

