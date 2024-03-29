---
title: RenderEntity
second_title: Aspose.3D voor .NET API-referentie
description: Elke rendertaak wordt gepusht naar hetIRenderQueueaspose.threed.render/irenderqueue/ zal een overeenkomstige RenderEntityaanroep hebben om de concrete weergavetaak uit te voeren.
type: docs
weight: 70
url: /nl/net/aspose.threed.render/entityrenderer/renderentity/
---
## EntityRenderer.RenderEntity method

Elke rendertaak wordt gepusht naar het[`IRenderQueue`](../../irenderqueue/) zal een overeenkomstige RenderEntity-aanroep hebben om de concrete weergavetaak uit te voeren.

```csharp
public virtual void RenderEntity(Renderer renderer, ICommandList commandList, Node node, 
    object renderableResource, int subEntity)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| renderer | Renderer | De renderer |
| commandList | ICommandList | De commandList die wordt gebruikt om de rendering-opdrachten op te nemen |
| node | Node | Hetzelfde knooppunt dat is doorgegeven aan PrepareRenderQueue van de entiteit die wordt weergegeven |
| renderableResource | Object | Het aangepaste object dat is doorgegeven aan IRenderQueue tijdens de PrepareRenderQueue |
| subEntity | Int32 | De index van de subentiteit die is doorgegeven aan IRenderQueue |

### Zie ook

* class [Renderer](../../renderer/)
* interface [ICommandList](../../icommandlist/)
* class [Node](../../../aspose.threed/node/)
* class [EntityRenderer](../)
* naamruimte [Aspose.ThreeD.Render](../../entityrenderer/)
* montage [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
