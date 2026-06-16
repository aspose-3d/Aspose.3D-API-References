---
title: "EntityRenderer"
second_title: "Aspose.3D for Java API Referansı"
description: "Farklı türdeki varlıklar için renderleme uygulamak amacıyla bunu alt sınıf yapın."
type: docs
weight: 53
url: /tr/java/com.aspose.threed/entityrenderer/
---

**Inheritance:**
java.lang.Object
```
public class EntityRenderer
```

Farklı türdeki varlıklar için renderleme uygulamak amacıyla bunu alt sınıf yapın.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EntityRenderer(String key, byte features)](#EntityRenderer-java.lang.String-byte-) | [EntityRenderer](../../com.aspose.threed/entityrenderer) yapıcısı |
| [EntityRenderer(String key)](#EntityRenderer-java.lang.String-) | [EntityRenderer](../../com.aspose.threed/entityrenderer) yapıcısı |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [dispose()](#dispose--) | EntityRenderer temizleniyor, paylaşılan kaynakları serbest bırak. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [frameBegin(Renderer renderer, IRenderQueue renderQueue)](#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Bir çerçeveyi render etmeye başla |
| [frameEnd(Renderer renderer, IRenderQueue renderQueue)](#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Bir çerçeveyi render etmeyi bitir |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [initialize(Renderer renderer)](#initialize-com.aspose.threed.Renderer-) | EntityRenderer'ı başlat |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity)](#prepareRenderQueue-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-com.aspose.threed.Node-com.aspose.threed.Entity-) | Belirtilen düğüm/varlık çifti için render komutlarını hazırla. |
| [renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)](#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-) | Her render görevi [IRenderQueue](../../com.aspose.threed/irenderqueue)'ye itildiğinde, somut render işini gerçekleştirmek için karşılık gelen RenderEntity çağrısı olacaktır. |
| [resetSceneCache()](#resetSceneCache--) | Sahne değişti veya kaldırıldı, bu durumda sahne düzeyindeki render kaynaklarını serbest bırakmak gerekiyor. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EntityRenderer(String key, byte features) {#EntityRenderer-java.lang.String-byte-}
```
public EntityRenderer(String key, byte features)
```


[EntityRenderer](../../com.aspose.threed/entityrenderer) yapıcısı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Varlık oluşturucusunun anahtarı |
| özellikler | bayt | Varlık oluşturucusunun ek özellikleri |

### EntityRenderer(String key) {#EntityRenderer-java.lang.String-}
```
public EntityRenderer(String key)
```


[EntityRenderer](../../com.aspose.threed/entityrenderer) yapıcısı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Varlık oluşturucusunun anahtarı |

### dispose() {#dispose--}
```
public void dispose()
```


EntityRenderer temizleniyor, paylaşılan kaynakları serbest bırak.

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


Bir çerçeveyi render etmeye başla

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Mevcut oluşturucu |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Oluşturma kuyruğu |

### frameEnd(Renderer renderer, IRenderQueue renderQueue) {#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameEnd(Renderer renderer, IRenderQueue renderQueue)
```


Bir çerçeveyi render etmeyi bitir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Mevcut oluşturucu |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Oluşturma kuyruğu |

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


EntityRenderer'ı başlat

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


Belirtilen düğüm/varlık çifti için render komutlarını hazırla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Mevcut oluşturucu örneği |
| queue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Oluşturma görevlerini yönetmek için kullanılan oluşturma kuyruğu |
| node | [Node](../../com.aspose.threed/node) | Mevcut düğüm |
| entity | [Entity](../../com.aspose.threed/entity) | Oluşturulması gereken varlık |

### renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity) {#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-}
```
public void renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)
```


Her render görevi [IRenderQueue](../../com.aspose.threed/irenderqueue)'ye itildiğinde, somut render işini gerçekleştirmek için karşılık gelen RenderEntity çağrısı olacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Oluşturucu |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) | Oluşturma komutlarını kaydetmek için kullanılan commandList |
| node | [Node](../../com.aspose.threed/node) | Oluşturulacak varlığın PrepareRenderQueue'ına geçirilen aynı düğüm |
| renderableResource | java.lang.Object | PrepareRenderQueue sırasında IRenderQueue'ye geçirilen özel nesne |
| subEntity | int | IRenderQueue'ye geçirilen alt varlığın indeksi |

### resetSceneCache() {#resetSceneCache--}
```
public void resetSceneCache()
```


Sahne değişti veya kaldırıldı, bu durumda sahne düzeyindeki render kaynaklarını serbest bırakmak gerekiyor.

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

