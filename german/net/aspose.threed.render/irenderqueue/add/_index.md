---
title: "IRenderQueue.Add"
second_title: "Aspose.3D für .NET API-Referenz"
description: "IRenderQueue-Methode. Fügt einen Render-Auftrag zur Renderwarteschlange hinzu"
type: docs
weight: 10
url: /de/net/aspose.threed.render/irenderqueue/add/
---
## IRenderQueue.Add method

Renderaufgabe zur Renderwarteschlange hinzufügen.

```csharp
public void Add(RenderQueueGroupId groupId, IPipeline pipeline, object renderableResource, 
    int subEntity)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| groupId | RenderQueueGroupId | Welche Gruppe der Warteschlange der Render-Auftrag zugeordnet wird |
| pipeline | IPipeline | Die Pipeline-Instanz, die für diesen Render-Auftrag verwendet wird |
| renderableResource | Object | Benutzerdefiniertes Objekt, das an [`RenderEntity`](../../entityrenderer/renderentity/) gesendet wird |
| subEntity | Int32 | Der Index der Unter-Entitäten, nützlich, wenn die Entität aus mehr als einer renderbaren Unterkomponente besteht. |

### Siehe auch

* enum [RenderQueueGroupId](../../renderqueuegroupid/)
* interface [IPipeline](../../ipipeline/)
* interface [IRenderQueue](../)
* namespace [Aspose.ThreeD.Render](../../irenderqueue/)
* assembly [Aspose.3D](../../../)


