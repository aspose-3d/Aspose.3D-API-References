---
title: "EntityRenderer.RenderEntity"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος EntityRenderer. Κάθε εργασία απόδοσης που προωθείται στο IRenderQueue θα έχει μια αντίστοιχη κλήση RenderEntity για την εκτέλεση της συγκεκριμένης εργασίας απόδοσης"
type: docs
weight: 70
url: /el/net/aspose.threed.render/entityrenderer/renderentity/
---
## EntityRenderer.RenderEntity method

Κάθε εργασία απόδοσης που προωθείται στο [`IRenderQueue`](../../irenderqueue/) θα έχει μια αντίστοιχη κλήση RenderEntity για την εκτέλεση της συγκεκριμένης εργασίας απόδοσης.

```csharp
public virtual void RenderEntity(Renderer renderer, ICommandList commandList, Node node, 
    object renderableResource, int subEntity)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| renderer | Renderer | Ο αποτυπωτής |
| λίστα εντολών | ICommandList | Η λίστα εντολών που χρησιμοποιείται για την καταγραφή των εντολών απόδοσης |
| κόμβος | Κόμβος | Ο ίδιος κόμβος που περάστηκε στο PrepareRenderQueue της οντότητας που θα αποδοθεί |
| renderableResource | Αντικείμενο | Το προσαρμοσμένο αντικείμενο που μεταβιβάστηκε στο IRenderQueue κατά τη διάρκεια του PrepareRenderQueue |
| subEntity | Int32 | Ο δείκτης της υποοντότητας που μεταβιβάστηκε στο IRenderQueue |

### Δείτε επίσης

* class [Renderer](../../renderer/)
* interface [ICommandList](../../icommandlist/)
* class [Node](../../../aspose.threed/node/)
* class [EntityRenderer](../)
* namespace [Aspose.ThreeD.Render](../../entityrenderer/)
* assembly [Aspose.3D](../../../)


