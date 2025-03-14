---
title: IRenderQueue.Add
second_title: Aspose.3D for .NET API Reference
description: IRenderQueue method. Add render task to the render queue
type: docs
weight: 10
url: /net/aspose.threed.render/irenderqueue/add/
---
## IRenderQueue.Add method

Add render task to the render queue.

```csharp
public void Add(RenderQueueGroupId groupId, IPipeline pipeline, object renderableResource, 
    int subEntity)
```

| Parameter | Type | Description |
| --- | --- | --- |
| groupId | RenderQueueGroupId | Which group of the queue the render task will be in |
| pipeline | IPipeline | The pipeline instance used for this render task |
| renderableResource | Object | Custom object that will be sent to [`RenderEntity`](../../entityrenderer/renderentity/) |
| subEntity | Int32 | The index of sub entities, useful when the entity is consisting of more than one sub renderable components. |

### See Also

* enum [RenderQueueGroupId](../../renderqueuegroupid/)
* interface [IPipeline](../../ipipeline/)
* interface [IRenderQueue](../)
* namespace [Aspose.ThreeD.Render](../../irenderqueue/)
* assembly [Aspose.3D](../../../)


