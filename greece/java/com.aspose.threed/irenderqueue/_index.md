---
title: IRenderQueue
second_title: Aspose.3D for Java API Reference
description: Ο αποδότης οντοτήτων χρησιμοποιεί αυτήν την ουρά για τη διαχείριση εργασιών απόδοσης.
type: docs
weight: 248
url: /el/java/com.aspose.threed/irenderqueue/
---
```
public interface IRenderQueue
```

Ο αποδότης οντοτήτων χρησιμοποιεί αυτήν την ουρά για τη διαχείριση εργασιών απόδοσης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)](#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-) | Προσθέστε εργασία απόδοσης στην ουρά απόδοσης. |
### add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity) {#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-}
```
public abstract void add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)
```


Προσθέστε εργασία απόδοσης στην ουρά απόδοσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| groupId | [RenderQueueGroupId](../../com.aspose.threed/renderqueuegroupid) | Σε ποια ομάδα της ουράς θα βρίσκεται η εργασία απόδοσης |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) | Η παρουσία του pipeline που χρησιμοποιείται για αυτήν την εργασία απόδοσης |
| renderableResource | java.lang.Object | Προσαρμοσμένο αντικείμενο που θα αποσταλεί στο [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| subEntity | int | Ο δείκτης των υπο-οντοτήτων, χρήσιμο όταν η οντότητα αποτελείται από περισσότερα από ένα υπο-αποδοτικά στοιχεία. |

