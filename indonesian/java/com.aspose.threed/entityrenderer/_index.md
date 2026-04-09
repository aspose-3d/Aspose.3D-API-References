---
title: EntityRenderer
second_title: Referensi API Aspose.3D untuk Java
description: Buat subclass ini untuk mengimplementasikan rendering untuk berbagai jenis entitas.
type: docs
weight: 53
url: /id/java/com.aspose.threed/entityrenderer/
---

**Inheritance:**
java.lang.Object
```
public class EntityRenderer
```

Buat subclass ini untuk mengimplementasikan rendering untuk berbagai jenis entitas.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [EntityRenderer(String key, byte features)](#EntityRenderer-java.lang.String-byte-) | Konstruktor dari [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| [EntityRenderer(String key)](#EntityRenderer-java.lang.String-) | Konstruktor dari [EntityRenderer](../../com.aspose.threed/entityrenderer) |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [dispose()](#dispose--) | Entity renderer sedang dibuang, lepaskan sumber daya bersama. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [frameBegin(Renderer renderer, IRenderQueue renderQueue)](#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Mulai merender sebuah frame |
| [frameEnd(Renderer renderer, IRenderQueue renderQueue)](#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Mengakhiri merender sebuah frame |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [initialize(Renderer renderer)](#initialize-com.aspose.threed.Renderer-) | Inisialisasi entity renderer |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity)](#prepareRenderQueue-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-com.aspose.threed.Node-com.aspose.threed.Entity-) | Siapkan perintah rendering untuk pasangan node/entity yang ditentukan. |
| [renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)](#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-) | Setiap tugas render yang didorong ke [IRenderQueue](../../com.aspose.threed/irenderqueue) akan memiliki panggilan RenderEntity yang sesuai untuk melakukan pekerjaan rendering konkret. |
| [resetSceneCache()](#resetSceneCache--) | Adegan telah berubah atau dihapus, perlu membuang sumber daya render tingkat adegan dalam ini |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EntityRenderer(String key, byte features) {#EntityRenderer-java.lang.String-byte-}
```
public EntityRenderer(String key, byte features)
```


Konstruktor dari [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kunci | java.lang.String | Kunci dari renderer entitas |
| fitur | byte | Fitur tambahan dari renderer entitas |

### EntityRenderer(String key) {#EntityRenderer-java.lang.String-}
```
public EntityRenderer(String key)
```


Konstruktor dari [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kunci | java.lang.String | Kunci dari renderer entitas |

### dispose() {#dispose--}
```
public void dispose()
```


Entity renderer sedang dibuang, lepaskan sumber daya bersama.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### frameBegin(Renderer renderer, IRenderQueue renderQueue) {#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameBegin(Renderer renderer, IRenderQueue renderQueue)
```


Mulai merender sebuah frame

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Renderer saat ini |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Antrian render |

### frameEnd(Renderer renderer, IRenderQueue renderQueue) {#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameEnd(Renderer renderer, IRenderQueue renderQueue)
```


Mengakhiri merender sebuah frame

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Renderer saat ini |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Antrian render |

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


Inisialisasi entity renderer

**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Siapkan perintah rendering untuk pasangan node/entity yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Instansi renderer saat ini |
| queue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Antrian render yang digunakan untuk mengelola tugas render |
| node | [Node](../../com.aspose.threed/node) | Node saat ini |
| entity | [Entity](../../com.aspose.threed/entity) | Entitas yang perlu dirender |

### renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity) {#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-}
```
public void renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)
```


Setiap tugas render yang didorong ke [IRenderQueue](../../com.aspose.threed/irenderqueue) akan memiliki panggilan RenderEntity yang sesuai untuk melakukan pekerjaan rendering konkret.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Renderer |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) | commandList yang digunakan untuk merekam perintah rendering |
| node | [Node](../../com.aspose.threed/node) | Node yang sama yang diteruskan ke PrepareRenderQueue dari entitas yang akan dirender |
| renderableResource | java.lang.Object | Objek khusus yang diteruskan ke IRenderQueue selama PrepareRenderQueue |
| subEntity | int | Indeks sub entitas yang diteruskan ke IRenderQueue |

### resetSceneCache() {#resetSceneCache--}
```
public void resetSceneCache()
```


Adegan telah berubah atau dihapus, perlu membuang sumber daya render tingkat adegan dalam ini

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

