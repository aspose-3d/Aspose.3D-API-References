---
title: "IRenderQueue.Add"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método IRenderQueue. Añade una tarea de renderizado a la cola de renderizado"
type: docs
weight: 10
url: /es/net/aspose.threed.render/irenderqueue/add/
---
## IRenderQueue.Add method

Agregar tarea de renderizado a la cola de renderizado.

```csharp
public void Add(RenderQueueGroupId groupId, IPipeline pipeline, object renderableResource, 
    int subEntity)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| groupId | RenderQueueGroupId | Qué grupo de la cola contendrá la tarea de renderizado |
| pipeline | IPipeline | La instancia del pipeline utilizada para esta tarea de renderizado |
| renderableResource | Object | Objeto personalizado que se enviará a [`RenderEntity`](../../entityrenderer/renderentity/) |
| subEntity | Int32 | El índice de subentidades, útil cuando la entidad está compuesta por más de un componente renderizable secundario. |

### Ver también

* enum [RenderQueueGroupId](../../renderqueuegroupid/)
* interface [IPipeline](../../ipipeline/)
* interface [IRenderQueue](../)
* namespace [Aspose.ThreeD.Render](../../irenderqueue/)
* assembly [Aspose.3D](../../../)


