---
title: "EntityRenderer"
second_title: "Aspose.3D for Node.js via Java API Referansı"
description: 
type: docs

url: /tr/nodejs-java/aspose.threed/entityrenderer/
---
## EntityRenderer class

Farklı türde varlıklar için renderleme uygulamak amacıyla bunu alt sınıf yapın.


## Yöntemler

### constructor{#constructor}

| Ad | Açıklama |
| --- | --- |
| constructor(key, features) | EntityRenderer yapıcısı |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| key | String | entity renderer'ın anahtarı |
| features | byte | EntityRendererFeatures |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Ad | Açıklama |
| --- | --- |
| constructor_overload(key) | EntityRenderer yapıcısı |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| key | String | entity renderer'ın anahtarı |

 **Result:**



---


### initialize{#initialize}

| Ad | Açıklama |
| --- | --- |
| initialize(renderer) | Varlık renderlayıcısını başlat |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| rendere | Renderer | null |

 **Result:**



---


### resetSceneCache{#resetSceneCache}

| Ad | Açıklama |
| --- | --- |
| resetSceneCache() | Sahne değişti veya kaldırıldı, bu durumda sahne düzeyindeki render kaynaklarını serbest bırakmanız gerekiyor |

 **Result:**



---


### frameBegin{#frameBegin}

| Ad | Açıklama |
| --- | --- |
| frameBegin(renderer, renderQueue) | Bir çerçeve renderlamaya başla |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| renderer | Renderer | Mevcut renderlayıcı |
| renderQueue | IRenderQueue | Render kuyruğu |

 **Result:**



---


### frameEnd{#frameEnd}

| Ad | Açıklama |
| --- | --- |
| frameEnd(renderer, renderQueue) | Bir çerçeve renderlamayı sonlandırır |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| renderer | Renderer | Mevcut renderlayıcı |
| renderQueue | IRenderQueue | Render kuyruğu |

 **Result:**



---


### prepareRenderQueue{#prepareRenderQueue}

| Ad | Açıklama |
| --- | --- |
| prepareRenderQueue(renderer, queue, node, entity) | Belirtilen düğüm/varlık çifti için render komutlarını hazırla. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| renderer | Renderer | Mevcut renderlayıcı örneği |
| queue | IRenderQueue | Render görevlerini yönetmek için kullanılan render kuyruğu |
| node | Node | Mevcut düğüm |
| varlık | Varlık | Render edilmesi gereken varlık |

 **Result:**



---


### renderEntity{#renderEntity}

| Ad | Açıklama |
| --- | --- |
| renderEntity(renderer, commandList, node, renderableResource, subEntity) | com.aspose.threed.IRenderQueue'ye itilen her render görevi, somut render işini gerçekleştirmek için karşılık gelen RenderEntity çağrısına sahip olacaktır. |

 **Parameters:**

| Ad | Tür | Açıklama |
| --- | --- | --- |
| renderer | Renderer | Renderlayıcı |
| commandList | ICommandList | Render komutlarını kaydetmek için kullanılan commandList |
| node | Node | Render edilecek varlığın PrepareRenderQueue metoduna geçirilen aynı düğüm |
| renderableResource | Object | PrepareRenderQueue sırasında IRenderQueue'ye geçirilen özel nesne |
| subEntity | Sayı | IRenderQueue'ye geçirilen alt varlığın indeksi |

 **Result:**



---


### dispose{#dispose}

| Ad | Açıklama |
| --- | --- |
| dispose() | Varlık renderlayıcısı iptal ediliyor, paylaşılan kaynaklar serbest bırakılıyor. |

 **Result:**



---



