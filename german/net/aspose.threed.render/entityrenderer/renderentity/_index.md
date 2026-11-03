---
title: "EntityRenderer.RenderEntity"
second_title: "Aspose.3D für .NET API-Referenz"
description: "EntityRenderer-Methode. Jeder Renderauftrag, der an die IRenderQueue übergeben wird, hat einen entsprechenden RenderEntity-Aufruf, um den konkreten Rendering-Job auszuführen."
type: docs
weight: 70
url: /de/net/aspose.threed.render/entityrenderer/renderentity/
---
## EntityRenderer.RenderEntity method

Jeder Renderauftrag, der an die [`IRenderQueue`](../../irenderqueue/) übergeben wird, hat einen entsprechenden RenderEntity-Aufruf, um den konkreten Rendering-Job auszuführen.

```csharp
public virtual void RenderEntity(Renderer renderer, ICommandList commandList, Node node, 
    object renderableResource, int subEntity)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Renderer | Renderer | Der Renderer |
| commandList | ICommandList | Die commandList, die zum Aufzeichnen der Rendering-Befehle verwendet wird |
| Knoten | Knoten | Der gleiche Knoten, der an PrepareRenderQueue des zu rendernden Entity übergeben wurde. |
| renderableResource | Objekt | Das benutzerdefinierte Objekt, das während der PrepareRenderQueue an IRenderQueue übergeben wurde |
| subEntity | Int32 | Der Index der Unter-Entity, die an IRenderQueue übergeben wurde. |

### Siehe auch

* class [Renderer](../../renderer/)
* interface [ICommandList](../../icommandlist/)
* class [Node](../../../aspose.threed/node/)
* class [EntityRenderer](../)
* namespace [Aspose.ThreeD.Render](../../entityrenderer/)
* assembly [Aspose.3D](../../../)


