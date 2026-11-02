---
title: "EntityRenderer"
second_title: "Aspose.3D for Java API Referansı"
description: "Farklı türdeki varlıklar için renderleme uygulamak üzere bunu alt sınıfa geçirin."
type: docs
weight: 53
url: /tr/java/com.aspose.threed/entityrenderer/
---

**Inheritance:**
java.lang.Object
```
public class EntityRenderer
```

Farklı türdeki varlıklar için renderleme uygulamak üzere bunu alt sınıfa geçirin.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EntityRenderer(String key, byte features)](#EntityRenderer-java.lang.String-byte-) | Yapıcı [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| [EntityRenderer(String key)](#EntityRenderer-java.lang.String-) | Yapıcı [EntityRenderer](../../com.aspose.threed/entityrenderer) |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [dispose()](#dispose--) | Entity renderer nesnesi kaldırılıyor, paylaşılan kaynaklar serbest bırakılıyor. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [frameBegin(Renderer renderer, IRenderQueue renderQueue)](#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Bir çerçeve renderlamaya başla |
| [frameEnd(Renderer renderer, IRenderQueue renderQueue)](#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Bir çerçeve renderlamayı bitir |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [initialize(Renderer renderer)](#initialize-com.aspose.threed.Renderer-) | Entity renderer'ı başlat |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity)](#prepareRenderQueue-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-com.aspose.threed.Node-com.aspose.threed.Entity-) | Belirtilen düğüm/entity çifti için render komutlarını hazırla. |
| [renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)](#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-) | IRenderQueue'ya itilen her render görevi, somut render işini gerçekleştirmek için karşılık gelen RenderEntity çağrısına sahip olacaktır. |
| [resetSceneCache()](#resetSceneCache--) | Sahne değişti veya kaldırıldı, bu durumda sahne seviyesindeki render kaynaklarını serbest bırakmak gerekir. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EntityRenderer(String key, byte features) {#EntityRenderer-java.lang.String-byte-}
```
public EntityRenderer(String key, byte features)
```


Yapıcı [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Varlık işleyicisinin anahtarı |
| özellikler | bayt | Varlık işleyicisinin ekstra özellikleri |

### EntityRenderer(String key) {#EntityRenderer-java.lang.String-}
```
public EntityRenderer(String key)
```


Yapıcı [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Varlık işleyicisinin anahtarı |

### dispose() {#dispose--}
```
public void dispose()
```


Entity renderer nesnesi kaldırılıyor, paylaşılan kaynaklar serbest bırakılıyor.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### frameBegin(Renderer renderer, IRenderQueue renderQueue) {#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameBegin(Renderer renderer, IRenderQueue renderQueue)
```


Bir çerçeve renderlamaya başla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Mevcut işleyici |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | İşleme kuyruğu |

### frameEnd(Renderer renderer, IRenderQueue renderQueue) {#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameEnd(Renderer renderer, IRenderQueue renderQueue)
```


Bir çerçeve renderlamayı bitir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Mevcut işleyici |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | İşleme kuyruğu |

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


Entity renderer'ı başlat

**Parameters:**
| Parametre | Tür | Açıklama |
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


Belirtilen düğüm/entity çifti için render komutlarını hazırla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Mevcut işleyici örneği |
| queue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | İşleme görevlerini yönetmek için kullanılan işleme kuyruğu |
| node | [Node](../../com.aspose.threed/node) | Mevcut düğüm |
| entity | [Entity](../../com.aspose.threed/entity) | İşlenmesi gereken varlık |

### renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity) {#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-}
```
public void renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)
```


IRenderQueue'ya itilen her render görevi, somut render işini gerçekleştirmek için karşılık gelen RenderEntity çağrısına sahip olacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | İşleyici |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) | İşleme komutlarını kaydetmek için kullanılan commandList |
| node | [Node](../../com.aspose.threed/node) | İşlenecek varlığın PrepareRenderQueue metoduna geçirilen aynı düğüm |
| renderableResource | java.lang.Object | PrepareRenderQueue sırasında IRenderQueue'ye geçirilen özel nesne |
| subEntity | int | IRenderQueue'ye geçirilen alt varlığın indeksi |

### resetSceneCache() {#resetSceneCache--}
```
public void resetSceneCache()
```


Sahne değişti veya kaldırıldı, bu durumda sahne seviyesindeki render kaynaklarını serbest bırakmak gerekir.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

