---
title: "Κλάση Watermark"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Utilities.Watermark κλάση. Εργαλείο για κωδικοποίηση/αποκωδικοποίηση τυφλού υδατογραφήματος σε/από ένα πλέγμα"
type: docs
weight: 2950
url: /el/net/aspose.threed.utilities/watermark/
---
## Watermark class

Βοηθητικό πρόγραμμα για κωδικοποίηση/αποκωδικοποίηση τυφλού υδατογραφήματος σε/από ένα πλέγμα.

```csharp
public class Watermark
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [DecodeWatermark](../../aspose.threed.utilities/watermark/decodewatermark/#decodewatermark)(Mesh) | Αποκωδικοποίηση του υδατογραφήματος από ένα πλέγμα |
| static [DecodeWatermark](../../aspose.threed.utilities/watermark/decodewatermark/#decodewatermark_1)(Mesh, string) | Αποκωδικοποίηση του υδατογραφήματος από ένα πλέγμα |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark)(Mesh, string) | Κωδικοποίηση κειμένου σε τυφλό υδατογράφημα πλέγματος. |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark_1)(Mesh, string, string) | Κωδικοποίηση κειμένου σε τυφλό υδατογράφημα πλέγματος. |
| static [EncodeWatermark](../../aspose.threed.utilities/watermark/encodewatermark/#encodewatermark_2)(Mesh, string, string, bool) | Κωδικοποίηση κειμένου σε τυφλό υδατογράφημα πλέγματος. |

## Παρατηρήσεις

Και τα [`EncodeWatermark`](./encodewatermark/) και [`DecodeWatermark`](./decodewatermark/) θα εκτελέσουν έλεγχο άδειας. Η χρήση σε δοκιμαστική έκδοση θα προκαλέσει εξαίρεση, μπορείτε να χρησιμοποιήσετε το [`SuppressTrialException`](../../aspose.threed/trialexception/suppresstrialexception/) για να καταστείλετε την εξαίρεση, αλλά δεν θα αφαιρέσει τον περιορισμό εδώ. Απαιτείται έγκυρη άδεια για τη χρήση αυτών των λειτουργιών χωρίς περιορισμούς.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να κωδικοποιήσετε ένα τυφλό υδατογράφημα σε ένα πλέγμα και να το αποκωδικοποιήσετε.

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", null);
var watermark = Watermark.DecodeWatermark(encodedMesh, null);
```

### Δείτε επίσης

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


