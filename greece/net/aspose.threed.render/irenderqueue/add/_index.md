---
title: "IRenderQueue.Add"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος IRenderQueue. Προσθέτει εργασία απόδοσης στην ουρά απόδοσης."
type: docs
weight: 10
url: /el/net/aspose.threed.render/irenderqueue/add/
---
## IRenderQueue.Add method

Προσθέστε εργασία απόδοσης στην ουρά απόδοσης.

```csharp
public void Add(RenderQueueGroupId groupId, IPipeline pipeline, object renderableResource, 
    int subEntity)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| groupId | RenderQueueGroupId | Ποια ομάδα της ουράς θα περιλαμβάνει την εργασία απόδοσης |
| pipeline | IPipeline | Η παρουσία του pipeline που χρησιμοποιείται για αυτήν την εργασία απόδοσης |
| renderableResource | Object | Προσαρμοσμένο αντικείμενο που θα σταλεί στο [`RenderEntity`](../../entityrenderer/renderentity/) |
| subEntity | Int32 | Ο δείκτης των sub entities, χρήσιμος όταν η οντότητα αποτελείται από περισσότερα από ένα υπο-συστατικά που μπορούν να αποδοθούν. |

### Δείτε επίσης

* enum [RenderQueueGroupId](../../renderqueuegroupid/)
* interface [IPipeline](../../ipipeline/)
* interface [IRenderQueue](../)
* namespace [Aspose.ThreeD.Render](../../irenderqueue/)
* assembly [Aspose.3D](../../../)


