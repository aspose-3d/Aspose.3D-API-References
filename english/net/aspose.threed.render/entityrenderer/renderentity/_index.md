---
title: EntityRenderer.RenderEntity
second_title: Aspose.3D for .NET API Reference
description: EntityRenderer method. Each render task pushed to the IRenderQueue will have a corresponding RenderEntity call to perform the concrete rendering job
type: docs
weight: 70
url: /net/aspose.threed.render/entityrenderer/renderentity/
---
## EntityRenderer.RenderEntity method

Each render task pushed to the [`IRenderQueue`](../../irenderqueue/) will have a corresponding RenderEntity call to perform the concrete rendering job.

```csharp
public virtual void RenderEntity(Renderer renderer, ICommandList commandList, Node node, 
    object renderableResource, int subEntity)
```

| Parameter | Type | Description |
| --- | --- | --- |
| renderer | Renderer | The renderer |
| commandList | ICommandList | The commandList used to record the rendering commands |
| node | Node | The same node that passed to PrepareRenderQueue of the entity that will be rendered |
| renderableResource | Object | The custom object that passed to IRenderQueue during the PrepareRenderQueue |
| subEntity | Int32 | The index of the sub entity that passed to IRenderQueue |

### See Also

* class [Renderer](../../renderer/)
* interface [ICommandList](../../icommandlist/)
* class [Node](../../../aspose.threed/node/)
* class [EntityRenderer](../)
* namespace [Aspose.ThreeD.Render](../../entityrenderer/)
* assembly [Aspose.3D](../../../)


