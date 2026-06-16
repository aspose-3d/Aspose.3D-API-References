---
title: "EntityRenderer"
second_title: "Referensi API Aspose.3D untuk Node.js via Java"
description: 
type: docs

url: /id/nodejs-java/aspose.threed/entityrenderer/
---
## EntityRenderer class

Buat subclass ini untuk mengimplementasikan rendering bagi berbagai jenis entitas.


## Metode

### constructor{#constructor}

| Nama | Deskripsi |
| --- | --- |
| constructor(key, features) | Konstruktor EntityRenderer |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| key | String | Kunci entity renderer |
| features | byte | EntityRendererFeatures |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nama | Deskripsi |
| --- | --- |
| constructor_overload(key) | Konstruktor EntityRenderer |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| key | String | Kunci entity renderer |

 **Result:**



---


### initialize{#initialize}

| Nama | Deskripsi |
| --- | --- |
| initialize(renderer) | Inisialisasi entity renderer |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| rendere | Renderer | null |

 **Result:**



---


### resetSceneCache{#resetSceneCache}

| Nama | Deskripsi |
| --- | --- |
| resetSceneCache() | Adegan telah berubah atau dihapus, perlu membuang sumber daya render tingkat adegan dalam hal ini |

 **Result:**



---


### frameBegin{#frameBegin}

| Nama | Deskripsi |
| --- | --- |
| frameBegin(renderer, renderQueue) | Mulai merender sebuah frame |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| renderer | Renderer | Renderer saat ini |
| renderQueue | IRenderQueue | Antrian render |

 **Result:**



---


### frameEnd{#frameEnd}

| Nama | Deskripsi |
| --- | --- |
| frameEnd(renderer, renderQueue) | Mengakhiri merender sebuah frame |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| renderer | Renderer | Renderer saat ini |
| renderQueue | IRenderQueue | Antrian render |

 **Result:**



---


### prepareRenderQueue{#prepareRenderQueue}

| Nama | Deskripsi |
| --- | --- |
| prepareRenderQueue(renderer, queue, node, entity) | Siapkan perintah render untuk pasangan node/entitas yang ditentukan. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| renderer | Renderer | Instansi renderer saat ini |
| queue | IRenderQueue | Antrian render yang digunakan untuk mengelola tugas render |
| node | Node | Node saat ini |
| entity | Entity | Entitas yang perlu dirender |

 **Result:**



---


### renderEntity{#renderEntity}

| Nama | Deskripsi |
| --- | --- |
| renderEntity(renderer, commandList, node, renderableResource, subEntity) | Setiap tugas render yang didorong ke com.aspose.threed.IRenderQueue akan memiliki panggilan RenderEntity yang sesuai untuk melakukan pekerjaan render konkret. |

 **Parameters:**

| Nama | Tipe | Deskripsi |
| --- | --- | --- |
| renderer | Renderer | Renderer |
| commandList | ICommandList | commandList yang digunakan untuk merekam perintah rendering |
| node | Node | Node yang sama yang diteruskan ke PrepareRenderQueue dari entitas yang akan dirender |
| renderableResource | Object | Objek khusus yang diteruskan ke IRenderQueue selama PrepareRenderQueue |
| subEntity | Angka | Indeks sub entitas yang diteruskan ke IRenderQueue |

 **Result:**



---


### dispose{#dispose}

| Nama | Deskripsi |
| --- | --- |
| dispose() | Renderer entitas sedang dibuang, lepaskan sumber daya bersama. |

 **Result:**



---



