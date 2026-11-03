---
title: "Κλάση Renderer"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Render.Renderer. Το πλαίσιο σχετικά με τον αποδοχέα"
type: docs
weight: 2340
url: /el/net/aspose.threed.render/renderer/
---
## Renderer class

Το πλαίσιο σχετικά με τον αποτυπωτή.

```csharp
public abstract class Renderer : IDisposable
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AssetDirectories](../../aspose.threed.render/renderer/assetdirectories/) { get; } | Κατάλογοι που αποθηκεύουν εξωτερικά περιουσιακά στοιχεία |
| [EnableShadows](../../aspose.threed.render/renderer/enableshadows/) { get; set; } | Λαμβάνει ή ορίζει αν ενεργοποιηθούν οι σκιές. |
| [FallbackEntityRenderer](../../aspose.threed.render/renderer/fallbackentityrenderer/) { get; set; } | Λαμβάνει ή ορίζει τον εναλλακτικό αποτυπωτή οντότητας όταν η οντότητα δεν έχει ορισμένο ειδικό αποτυπωτή. |
| virtual [Frustum](../../aspose.threed.render/renderer/frustum/) { get; set; } | Λαμβάνει ή ορίζει το προβολικό που χρησιμοποιείται για την παροχή του πίνακα προβολής. |
| virtual [Material](../../aspose.threed.render/renderer/material/) { get; set; } | Λαμβάνει ή ορίζει το υλικό που χρησιμοποιείται για την παροχή πληροφοριών υλικού που χρησιμοποιούν οι shaders. |
| [Node](../../aspose.threed.render/renderer/node/) { get; set; } | Λαμβάνει ή ορίζει το στιγμιότυπο [`Node`](./node/) που χρησιμοποιείται για την παροχή του πίνακα μετασχηματισμού του κόσμου. |
| [PostProcessings](../../aspose.threed.render/renderer/postprocessings/) { get; } | Ενεργή αλυσίδα μετα-επεξεργασίας |
| [PresetShaders](../../aspose.threed.render/renderer/presetshaders/) { get; set; } | Λαμβάνει ή ορίζει το προκαθορισμένο σύνολο shaders |
| abstract [RenderFactory](../../aspose.threed.render/renderer/renderfactory/) { get; } | Λαμβάνει το εργοστάσιο για τη δημιουργία αντικειμένων σχετικών με την απόδοση. |
| [RenderStage](../../aspose.threed.render/renderer/renderstage/) { get; } | Λαμβάνει το τρέχον στάδιο απόδοσης. |
| [RenderTarget](../../aspose.threed.render/renderer/rendertarget/) { get; } | Καθορίστε τον προορισμό απόδοσης στον οποίο θα εκτελεστούν οι παρακάτω λειτουργίες απόδοσης. |
| [Shader](../../aspose.threed.render/renderer/shader/) { get; set; } | Λαμβάνει ή ορίζει το στιγμιότυπο shader που χρησιμοποιείται για την απόδοση της γεωμετρίας. |
| [ShaderSet](../../aspose.threed.render/renderer/shaderset/) { get; set; } | Λαμβάνει ή ορίζει το σύνολο shaders που χρησιμοποιείται για την απόδοση της σκηνής. |
| [Variables](../../aspose.threed.render/renderer/variables/) { get; } | Πρόσβαση στις εσωτερικές μεταβλητές που χρησιμοποιούνται για την απόδοση. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [CreateRenderer](../../aspose.threed.render/renderer/createrenderer/)() | Δημιουργεί ένα νέο `Renderer` με προεπιλεγμένο προφίλ. |
| virtual [ClearCache](../../aspose.threed.render/renderer/clearcache/)() | Καθαρίστε τη μνήμη cache χειροκίνητα. Το Aspose.3D θα αποθηκεύει σε cache ορισμένα αντικείμενα όπως υλικά/γεωμετρίες σε εσωτερικούς τύπους που είναι συμβατοί με τη γραμμή παραγωγής απόδοσης. Αυτό πρέπει να κληθεί χειροκίνητα όταν η σκηνή υποστεί σημαντικές αλλαγές. |
| [Dispose](../../aspose.threed.render/renderer/dispose/)() | Αποδεσμεύστε το `Renderer` και όλους τους σχετικούς πόρους. |
| abstract [Execute](../../aspose.threed.render/renderer/execute/)(PostProcessing, IRenderTarget) | Εκτελέστε μια μετα-επεξεργασία στον καθορισμένο προορισμό απόδοσης. |
| [GetPostProcessing](../../aspose.threed.render/renderer/getpostprocessing/)(string) | Λαμβάνει έναν ενσωματωμένο μετα-επεξεργαστή που υποστηρίζεται από τον αποτυπωτή. |
| virtual [RegisterEntityRenderer](../../aspose.threed.render/renderer/registerentityrenderer/)(EntityRenderer) | Καταχωρίστε τον αποτυπωτή οντότητας για την καθορισμένη οντότητα. |
| virtual [Render](../../aspose.threed.render/renderer/render/)(IRenderTarget) | Αποδώστε τον καθορισμένο προορισμό. |

### Δείτε επίσης

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


