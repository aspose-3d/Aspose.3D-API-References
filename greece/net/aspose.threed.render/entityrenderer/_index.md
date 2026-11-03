---
title: "Κλάση EntityRenderer"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Render.EntityRenderer class. Υποκλάσηστε το για να υλοποιήσετε την απόδοση διαφορετικών ειδών οντοτήτων"
type: docs
weight: 1970
url: /el/net/aspose.threed.render/entityrenderer/
---
## EntityRenderer class

Κληρονομήστε αυτήν την κλάση για να υλοποιήσετε την απόδοση διαφορετικών τύπων οντοτήτων.

```csharp
public class EntityRenderer
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [EntityRenderer](entityrenderer/#constructor)(string) | Κατασκευαστής του `EntityRenderer` |
| [EntityRenderer](entityrenderer/#constructor_1)(string, EntityRendererFeatures) | Κατασκευαστής του `EntityRenderer` |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| virtual [Dispose](../../aspose.threed.render/entityrenderer/dispose/)() | Ο αποδοχέας οντοτήτων καταστρέφεται, απελευθερώστε τους κοινόχρηστους πόρους. |
| virtual [FrameBegin](../../aspose.threed.render/entityrenderer/framebegin/)(Renderer, IRenderQueue) | Ξεκινήστε την απόδοση ενός καρέ |
| virtual [FrameEnd](../../aspose.threed.render/entityrenderer/frameend/)(Renderer, IRenderQueue) | Τελειώνει η απόδοση ενός καρέ |
| virtual [Initialize](../../aspose.threed.render/entityrenderer/initialize/)(Renderer) | Αρχικοποιήστε τον αποδοχέα οντοτήτων |
| virtual [PrepareRenderQueue](../../aspose.threed.render/entityrenderer/preparerenderqueue/)(Renderer, IRenderQueue, Node, Entity) | Ετοιμάστε τις εντολές απόδοσης για το συγκεκριμένο ζεύγος κόμβου/οντότητας. |
| virtual [RenderEntity](../../aspose.threed.render/entityrenderer/renderentity/)(Renderer, ICommandList, Node, object, int) | Κάθε εργασία απόδοσης που προωθείται στην [`IRenderQueue`](../irenderqueue/) θα έχει μια αντίστοιχη κλήση RenderEntity για την εκτέλεση της συγκεκριμένης εργασίας απόδοσης. |
| virtual [ResetSceneCache](../../aspose.threed.render/entityrenderer/resetscenecache/)() | Η σκηνή έχει αλλάξει ή αφαιρεθεί, χρειάζεται να απελευθερώσετε τους πόρους απόδοσης επιπέδου σκηνής σε αυτό |

### Δείτε επίσης

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


