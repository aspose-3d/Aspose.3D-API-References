---
title: IRenderQueue
second_title: Referensi API Aspose.3D untuk Java
description: Renderer entitas menggunakan antrian ini untuk mengelola tugas render.
type: docs
weight: 248
url: /id/java/com.aspose.threed/irenderqueue/
---
```
public interface IRenderQueue
```

Renderer entitas menggunakan antrian ini untuk mengelola tugas render.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)](#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-) | Tambahkan tugas render ke antrian render. |
### add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity) {#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-}
```
public abstract void add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)
```


Tambahkan tugas render ke antrian render.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| groupId | [RenderQueueGroupId](../../com.aspose.threed/renderqueuegroupid) | Grup antrian mana yang akan berisi tugas render |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) | Instansi pipeline yang digunakan untuk tugas render ini |
| renderableResource | java.lang.Object | Objek khusus yang akan dikirim ke [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| subEntity | int | Indeks sub entitas, berguna ketika entitas terdiri dari lebih dari satu komponen renderable sub. |

