---
title: IRenderQueue
second_title: Referencia de API de Aspose.3D para Java
description: El renderizador de entidades usa esta cola para gestionar tareas de renderizado.
type: docs
weight: 248
url: /es/java/com.aspose.threed/irenderqueue/
---
```
public interface IRenderQueue
```

El renderizador de entidades usa esta cola para gestionar tareas de renderizado.
## Métodos

| Método | Descripción |
| --- | --- |
| [add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)](#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-) | Agregar tarea de renderizado a la cola de renderizado. |
### add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity) {#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-}
```
public abstract void add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)
```


Agregar tarea de renderizado a la cola de renderizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| groupId | [RenderQueueGroupId](../../com.aspose.threed/renderqueuegroupid) | En qué grupo de la cola estará la tarea de renderizado |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) | La instancia de la canalización utilizada para esta tarea de renderizado |
| renderableResource | java.lang.Object | Objeto personalizado que se enviará a [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| subEntity | int | El índice de subentidades, útil cuando la entidad consta de más de un componente renderizable secundario. |

